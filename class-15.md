# Class-15:

## Trees
![](https://blog.penjee.com/wp-content/uploads/2015/11/binary-search-tree-degenerating-demo-animation.gif)
**Terminologies**
**Node** - A node is the individual item/data that makes up the data structure
**Root** - The root is the first/top Node in the tree
**Left Child** - The node that is positioned to the left of a root or node
**Right Child** - The node that is positioned to the right of a root or node
**Edge** - The edge in a tree is the link between a parent and child node
**Leaf** - A leaf is a node that does not contain any children
**Height** - The height of a tree is determined by the number of edges from the root to the bottommost node


## Traversals
Traversing a tree allows us to

* search for a node
* print out the contents of a tree and much more!


**Big O**
time complexity for inserting a new node is O(n)
Searching for a specific node will also be O(n)
Binary Search Trees
A Binary Search Tree (BST) is a type of tree that does have some structure attached to it.

In a BST, nodes are organized in a manner where all values that are
smaller than the root are placed to the left,
values that are larger than the root are placed to the right.
Searching a BST
Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.

**Big O**
time complexity for insertion and search operations is O(h)
space complexity of a BST search would be O(1).