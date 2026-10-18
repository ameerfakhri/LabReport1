# LabReport1
An interactive app that shows how Breadth-First Search (BFS) and Depth-First Search (DFS) traverse a directed graph, with alphabetical tie-breaking, step trace and graph visualisation.


## How it works
- **BFS** expands all nodes at one level before the next level, using a queue.
- **DFS** goes as deep as possible, then backtracks, using a stack. A node is marked as visited when it is taken from the stack, so the depth and parent follow the real DFS path.
- Time complexity of both: O(V + E), where V is the number of nodes and E is the number of edges.
