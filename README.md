# BFS
Breadth-First Search (BFS) is a graph traversal algorithm used to explore nodes and edges of a graph systematically. Starting from a source node, it explores all of its neighbors before moving on to the next level of nodes. BFS is particularly useful for finding the shortest path in an unweighted graph and can be applied to both directed and undirected graphs.
Characteristics of BFS:
1.	Level-wise exploration: BFS explores all nodes at the present depth level before moving on to nodes at the next depth level.
2.	Uses a queue: BFS employs a queue data structure to store the nodes that need to be explored. This ensures that nodes are processed in a FIFO (First In, First Out) manner.
3.	Shortest Path: In an unweighted graph, BFS guarantees the shortest path from the starting node to any other reachable node.
4.	Can be used for searching in graphs or networks: BFS is used in applications like finding the shortest path, solving puzzles, web crawlers, and more.
## Steps in BFS:
1.	Start by enqueueing the initial node and marking it as visited.
2.	Dequeue a node from the front of the queue.
3.	Visit all of its unvisited neighbors, enqueue them, and mark them as visited.
4.	Repeat the process until the queue is empty or all reachable nodes have been visited.
## BFS Algorithm:
1.	Initialize a queue.
2.	Put the starting node into the queue and mark it as visited.
3.	While the queue is not empty:
o	Dequeue a node from the queue.
o	Visit the node and process it (e.g., print it, check for a solution, etc.).
o	Enqueue all unvisited neighbors of the node.
4.	End when the queue is empty.
