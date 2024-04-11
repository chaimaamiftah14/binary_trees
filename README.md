0x1D. C - Binary trees
_________________________________________________________________________________________________


-- Understanding Binary Trees:
-------------------------------------------------------------------------------------------------

In the world of data structures, binary trees are stars in their own right. They're hierarchical structures composed of nodes, each node containing some data and pointers to its left and right children. This setup allows for efficient searching, insertion, and deletion operations.

-- Binary Tree vs. Binary Search Tree:
------------------------------------------------------------------------------------------------
One common type of binary tree is the Binary Search Tree (BST), where nodes are ordered in a specific way to facilitate efficient searching. Unlike a general binary tree, in a BST, the left child of a node contains values lesser than the node's value, and the right child contains values greater than the node's value.

-- Time Complexity Gain:
-------------------------------------------------------------------------------------------------
Compared to linked lists, binary trees offer significant gains in terms of time complexity, especially for search operations. While linked lists have a linear time complexity for search (O(n)), binary trees offer logarithmic complexity (O(log n)), making them much faster for large datasets.

-- Characteristics of Binary Trees:
-------------------------------------------------------------------------------------------------
The depth of a node refers to the length of the path from the root to that node. The height of a binary tree is the length of the longest path from the root to a leaf node. The size of a binary tree denotes the total number of nodes in the tree.

-- Traversing Binary Trees:
-------------------------------------------------------------------------------------------------
Various methods exist to traverse a binary tree, including pre-order, in-order, and post-order traversals. Each method has its unique way of visiting and processing nodes.

-- Types of Binary Trees:
-------------------------------------------------------------------------------------------------
Binary trees come in different flavors: complete, full, perfect, and balanced. A complete binary tree is one where every level except possibly the last is completely filled, and all nodes are as far left as possible. A full binary tree is a tree in which every node has either 0 or 2 children. A perfect binary tree is both complete and full. A balanced binary tree is one in which the height of the left and right subtrees of any node differs by no more than one.

-- Data Structures:
-------------------------------------------------------------------------------------------------
. Here's a basic structure for a binary tree node:
typedef struct binary_tree_s {
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
} binary_tree_t;

. And here are some additional structures:

Binary Search Tree: typedef struct binary_tree_s bst_t;
AVL Tree: typedef struct binary_tree_s avl_t;
Max Binary Heap: typedef struct binary_tree_s heap_t;
Tasks

. Now let's dive into some tasks to work with binary trees:

1- New Node: Write a function that creates a binary tree node.
2- Insert Left: Write a function that inserts a node as the left child of another node.
3- Insert Right: Write a function that inserts a node as the right child of another node.
4- Delete: Write a function that deletes an entire binary tree.
5- Is Leaf: Write a function that checks if a node is a leaf.
6- Is Root: Write a function that checks if a given node is a root.
7- Pre-order Traversal: Write a function that traverses a binary tree using pre-order traversal.
8- In-order Traversal: Write a function that traverses a binary tree using in-order traversal.
9- Post-order Traversal: Write a function that traverses a binary tree using post-order traversal.
10- Height: Write a function that measures the height of a binary tree.
11- Depth: Write a function that measures the depth of a node in a binary tree.
12- Size: Write a function that measures the size of a binary tree.
13- Leaves: Write a function that counts the leaves in a binary tree.
14- Nodes: Write a function that counts the nodes with at least 1 child in a binary tree.
15- Balance Factor: Write a function that measures the balance factor of a binary tree.
16- Is Full: Write a function that checks if a binary tree is full.
17- Is Perfect: Write a function that checks if a binary tree is perfect.
