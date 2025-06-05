<div align="center">

# Tower Detection System

![last-commit](https://img.shields.io/github/last-commit/Gushtasp47/Tower-Detection-System?style=flat&logo=git&logoColor=white&color=0080ff)
![repo-top-language](https://img.shields.io/github/languages/top/Gushtasp47/Tower-Detection-System?style=flat&color=0080ff)
![repo-language-count](https://img.shields.io/github/languages/count/Gushtasp47/Tower-Detection-System?style=flat&color=0080ff)

**Built with:**

![C++](https://img.shields.io/badge/C++-00599C.svg?style=flat&logo=C%2B%2B&logoColor=white)


Welcome to the **Tower Detection System**, a console-based C++ application designed to manage and analyze network connectivity between towers using graph algorithms such as **Prim's (for MST)** and **Dijkstra's (for shortest paths)**. It includes a simple **user authentication system**, file-based data persistence, and an interactive menu system.

---
</div>

 ## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [File Structure](#file-structure)
- [How to Compile and Run](#how-to-compile-and-run)
- [How to Use](#how-to-use)
- [Example Session](#example-session)
- [Notes](#notes)
- [License](#license)

---

## Overview

The Tower Detection System is a console-based C++ application designed to manage and analyze network connectivity between towers.

### Why Tower-Detection-System?

- **Graph Structure** – Efficient node relationship representation  
- **User Management** – Registration and login features  
- **Graph Algorithms** – Implements Prim’s and Dijkstra’s algorithms  
- **Data Persistence** – Save/load user and graph data  
- **Interactive Interface** – Easy-to-use console menu

## Features

-  **User Authentication System** (Register & Login)
-  Add nodes and edges dynamically
-  View all tower (graph) connections
-  Generate Minimum Spanning Tree (Prim's Algorithm)
-  Find Shortest Path between Towers (Dijkstra's Algorithm)
-  Check Graph Connectivity (DFS-based)
-  Save and Load graph from file (`graph.txt`)
-  Interactive ASCII-art menu interface

---

## File Structure

```plaintext
.
├── main.cpp             # Main C++ source code
├── graph.txt            # (Auto-created) Stores saved graph data
├── users.txt            # (Auto-created) Stores registered users
└── README.md            # This file
```

---

## How to Compile and Run

### On Windows (using g++)

1. **Compile the code:**
   ```bash
   g++ main.cpp -o tower_system
   ```

2. **Run the program:**
   ```bash
   tower_system
   ```

> ⚠️ Note: The code uses `<conio.h>` which is Windows-specific. If you're on Linux/macOS, you'll need to adapt/remove password masking logic.

---

## How to Use

1. **Launch the program** → You’ll be greeted with a welcome screen.
2. **Register or Login**
   - Register with a username and password if you're new
   - Login with existing credentials
3. After login, you'll see a menu:
   - Add towers (nodes)
   - Add connections (edges) with weights (e.g., distance)
   - View the graph structure
   - Compute MST or shortest paths
   - Check if all towers are connected
   - Save your progress
4. **Log out or exit** when done.

---

##  Example Session

```plaintext
=== Welcome to the Tower Detection System ===

1. Register
2. Login
3. Exit
Enter your choice: 1

--- New User Registration ---
Enter username: testuser
Enter password: ********
Registration successful!

--- User Login ---
Enter username: testuser
Enter password: ********
Login successful!

1. Add Node
2. Add Edge
3. Display Graph
...
Enter your choice: 1
Node 0 added successfully.

Enter your choice: 1
Node 1 added successfully.

Enter your choice: 2
Enter source, destination, and weight: 0 1 5
Edge added successfully.

Enter your choice: 3
--- Tower Graph Connections ---
Node 0: (1, 5)
Node 1: (0, 5)
```

---

## Notes

- `graph.txt` and `users.txt` are automatically created for saving/loading data.
- The program must be recompiled if you make code changes.
- Invalid node/edge entries are handled gracefully.
- Password input uses masked input (`*`) via `<conio.h>`.

---

## License

This project is open-source and free to use for educational purposes.
