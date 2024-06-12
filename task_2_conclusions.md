This script demonstrates how to use DFS and BFS algorithms to find paths in a graph. It visualizes the paths found by both algorithms and explains the differences between them.


DFS (Depth-First Search) explores as far as possible along each branch before backtracking. 
It uses a stack (recursively or explicitly) to keep track of the current path.
In our example, DFS path from A to E: ['A', 'B', 'C', 'D', 'E'] (one possible path)
DFS path may vary depending on the order of neighbors.

BFS (Breadth-First Search) explores all the neighbors at the present depth level before moving on to nodes at the next depth level.
It uses a queue to keep track of the current level.
In our example, BFS path from A to E: ['A', 'F', 'C', 'G', 'E']
BFS always finds the shortest path in an unweighted graph.

By comparing the paths obtained using DFS and BFS, it is evident that BFS provides a more optimal and direct route, while DFS might explore more nodes and provide a longer path. The choice of algorithm depends on the specific requirements of the problem being solved.