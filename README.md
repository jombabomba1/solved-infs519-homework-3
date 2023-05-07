Download Link: https://assignmentchef.com/product/solved-infs519-homework-3
<br>
In this program you will convert the BST from homework #2 to an AVL tree as the basis for your address book.

Your program will appear the same as Program 2 to the user <em>except </em>that the ” displayAll () ” operation will additionally display the <em>height </em>and <em>balance factor </em>of each node within the tree.

<ul>

 <li>The <strong>height </strong>of a node is the number of edges from the node to the deepest leaf.</li>

 <li>The <strong>balance factor </strong>of a node is the difference in heights of its two subtrees.</li>

</ul>

<strong><u>Internals </u></strong>

Again, you will write (among other classes) a class Table that will store entries comprised of (key/value) pairs of Strings. This class will have the same public methods as did Program 2, and will include (at a minimum) the following additional private methods:

<ul>

 <li>private void rebalance(Node n)</li>

 <li>private Node rotateLeft(Node n)</li>

 <li>private Node rotateRight(Node n)</li>

 <li>private Node rotateLeftThenRight(Node n)</li>

 <li>private Node rotateRightThenLeft(Node n)</li>

</ul>

Table will now be implemented as an AVL tree. Each node will have two String fields (for the name and address), along with an <em>int height </em>field and an <em>int balance </em>field. Optionally, you may include a <em>Node parent </em>field along with the <em>Node left </em>and <em>Node right</em>. Your code may be implemented either recursively, iteratively, or as a combination of the two. All other specifications from homework #2 carry over.