# Maya Sidorova

*Web-developer based in Shanghai*  
**Email:** mayasidorova@yahoo.com  
[**GitHub**](https://github.com/Mayumayumau) | [**LinkedIn**](https://www.linkedin.com/in/maya-sidorova-97a15686)  
## Skills  
- HTML/CSS
- JavaScript
- Python
- Git
- C/C++
## Languages
**Russian** - Native  
**English** - Fluent  
**Chinese** - Fluent  

## Education
*2019-2022 Tomsk State University of Control Systems and Radioelectronics - BS in Computer Science*  
*2005-2010 Tomsk State University - MA in Linguistics and Translation Studies*  

## Projects  
1) [Online zoo]()
2) [Virtual piano]()
3) [Photo editor]()

## Code example  
```
node * insert_node(node *tree, node *new_node) { // function inserting a node into AVL Tree
    if (!tree) return new_node;
    if (new_node->getKey() > tree->getKey()){
        tree->setRight(insert_node(tree->getRight(), new_node));
    } else {
            tree->setLeft(insert_node(tree->getLeft(), new_node));
        }
    return balance(tree);
}
```

