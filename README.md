# first-project
How to Use
Login/Registration

On starting the program, choose to log in or register.
For registration, provide a unique username and password.
Manage Towers

After login, you can:
Add or view towers.
Connect towers with edges and weights.
Analyze the network's connectivity or calculate MST and shortest paths.
Save and Load

Save the graph to persist changes using the save option.
Reload previously saved graphs during program initialization.
Exit

Log out to end your session or exit the program.
Algorithms Used
Prim's Algorithm: For Minimum Spanning Tree (MST).
Dijkstra's Algorithm: For shortest path calculation.
Depth-First Search (DFS): For connectivity checks.
Files
Code File: main.cpp - The source code implementing the system.
Graph Data: graph.txt - Stores nodes and edges for the tower network.
User Data: users.txt - Stores registered user credentials.
Data Structures
Graph Representation: Adjacency list.
User Management: unordered_map for fast lookups.
Priority Queue: For efficient graph traversals in Prim's and Dijkstra's algorithms.
System Requirements
Compiler: A C++ compiler supporting C++11 or later.
OS: Windows (uses <conio.h> for secure password input).
