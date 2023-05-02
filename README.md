# Assignment 4
## Welcome to graph
For each of the questions below, make sure that you clearly describe any assumptions you make. All code should be well commented. Your code should be generic where possible, but we will only test with numeric and String types. You may use non-graph data structures from the standard library (eg `ArrayList`, `HashMap` etc).

You may have written some of these classes and functions before but you should be able to do all of this with minimal JavaDoc reference.
Assignment: Graph Data Structures in Java

1. Design and implement a graph data structure. You should be able to handle weighted nodes and edges with `String` labels. We will discuss the interface in class. Ensure the graph has a **toString()** method which produces a legible representation of the graph. You will use this data structure for the remaining questions in this assignment, so read those first. Your class should be as general as possible - this means you can use it to solve problems that are not asked below. Implement the following methods for your graph. Make sure to write detailed comments explaining any design decisions you make. For each of these functions, report the time and space complexity of your implementation.
	**1** **isConnected** should check if the graph is connected.
	**2** **isCyclic** should check if the graph contains any cycles.
	**3** **maximumFlow** should return the maximum flow between two nodes in a flow network graph.  That is, if your graph were a set of pipes and edge weights represented how much water could flow through a pipe at any given moment, what is the maximum total amount of water that can be flowing into the target node at any given moment. We will try to solve this in class.

2. Describe/draw instances of graphs. You should use as many graphs as you need to demonstrate that your data structure is capable of representing any of the graphs you will need to represent for the remaining questions. Demonstrate instantiating these graphs in code.

3. Implement Dijkstra’s algorithm for finding the shortest path between two nodes in a weighted graph. Describe your algorithm in detail in the writeup. Read about other shortest path algorithms and explain how two of them differ from Dijkstra

4. Write a static method that determines whether a graph is bipartite or not. A graph is bipartite if its vertices can be divided into two disjoint sets such that every edge connects a vertex in one set to a vertex in the other set.

5. Implement the PageRank algorithm to rank the nodes in a directed graph based on their importance. The PageRank algorithm is an iterative algorithm that assigns a rank to each node in the graph, with the rank representing the probability that a random walk through the graph will end up at that node. Write a main method in this class to print the PageRank scores for each node in the graph. Use the examples from question Describe the PageRank algorithm in detail in your writeup. You will have to find sources and read about PageRank yourself. We will discuss PageRank in class on the first non-flunk day of next week.

Add a main method somewhere in your code that will run all of your examples with informative print statements in between. Make sure the main method is well documented so the TAs and I can easily try out variations on your examples.
