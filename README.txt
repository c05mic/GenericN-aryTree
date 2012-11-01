Simple Generic N-ary Tree implementation in Java
------------------------------------------------

Utility methods:
----------------
1) To check if a node exists in the tree.
2) To find the total number of nodes in the tree
3) To find the total number of descendants of any node in the tree.
4) To get all the paths from the root to all the leaves as an ArrayList.
5) To get all longest path from the root to any leaf.
6) To get the pre-order/post-order traversal path as an ArrayList.

Example Usage:
--------------

Node<Integer> root = new Node<Integer>(1);

root.addChild(new Node<Integer>(2));

Tree<Integer> tree = new Tree<Integer>(root);

ArrayList<Node<Integer>> preOrder = tree.getPreOrderTraversal();


