#Simple Generic N-ary Tree implementation in Java
 
##Utility methods:
 
1. To check if a node exists in the tree.
2. To find the total number of nodes in the tree
3. To find the total number of descendants of any node in the tree.
4. To get all the paths from the root to all the leaves as a List.
5. To get all longest path from the root to any leaf.
6. To get the pre-order/post-order traversal path as a List.
 
##Example Usage:
 
```java
// Create a new Integer type node
Node<Integer> root = new Node<Integer>(1);
 
// Add a child
root.addChild(new Node<Integer>(2));
 
// Create a tree, providing the root node
Tree<Integer> tree = new Tree<Integer>(root);
 
// Get the pre-order traversal
List<Node<Integer>> preOrder = tree.getPreOrderTraversal();
```

##Download:

Maven:

```
<dependency>
    <groupId>com.c05mic.generictree</groupId>
    <artifactId>GenericN-aryTree</artifactId>
    <version>1.1.1</version>
</dependency>
```

Gradle:

```
repositories {
  mavenCentral() // jcenter() works as well because it pulls from Maven Central
}

dependencies {
  compile 'com.c05mic.generictree:GenericN-aryTree:1.1.1'
}
```