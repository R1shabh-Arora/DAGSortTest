# DAGSortTest
The class contains a single method, sortDag(int[][]), which returns an array of integers (int[]). You have also been provided with the intended behaviour of this method, as described in the following Javadoc comments: Note the sortDAG(int[][] edges) method takes as input a 2-dimensional array representing the DAG. Nodes are assumed to be labelled from 0 to (edges.length - 1) and each row edges[i] represents the nodes immediately following node i (its immediate out-neighbours). For example, edges[0] = {1, 2, 5} means there are edges from node 0 to nodes 1, 2 and 5.  Write a JUnit 5 test class to test this unit of code. Your test class should thoroughly exercise the code, including how it deals with invalid input. You should consider that a DAG may have multiple valid topological orderings and your tests should be robust to this.  You can assume that the test class returns some output (so you do not need to test for infinite loops or memory issues), and you can assume that the code will never need to run on graphs larger than 1000 (so you do not need to test how the code behaves on graphs larger than this).
