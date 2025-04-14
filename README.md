# 🏗️ Tower Detection System

A C++ application for simulating and analyzing tower connectivity using graph algorithms like Prim's and Dijkstra's. The system includes a basic login and registration interface, file-based data persistence, and ASCII-art-based user interaction.

---

## 🚀 Features

- ✅ **User Authentication**
  - Register and login functionality with masked password input.
  - User data saved in `users.txt`.

- 🧠 **Graph-Based Tower Management**
  - Add towers (nodes) and links (edges with weights).
  - Display the full graph of tower connections.
  - Check network connectivity (DFS-based).
  - Find Minimum Spanning Tree (MST) using Prim’s algorithm.
  - Compute shortest paths between towers using Dijkstra’s algorithm.
  - Save/load graph to/from `graph.txt`.

- 🎨 **ASCII Art Interface**
  - Fun terminal visuals for a more interactive experience.

---

## 🛠️ Tech Stack

- **Language:** C++
- **Concepts Used:** OOP, Graph Theory, File Handling, Standard Template Library (STL)
- **Tools:** `g++`, `conio.h`, CLI

---

## 📂 File Structure

```bash
├── main.cpp               # Core application logic
├── users.txt              # Stores registered user credentials
├── graph.txt              # Stores saved graph data
├── README.md              # This file
└── (Optional) assets/     # Add any future assets like screenshots or diagrams
