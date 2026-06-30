# 🚗 Smart Route Planner

A modular **Graph Algorithm Engine** developed in **Modern C++17** that simulates a smart route planning system using real-world graph algorithms.

Instead of being a simple implementation of individual algorithms, this project provides a reusable graph framework capable of solving shortest path, connectivity, minimum spanning tree, and network analysis problems through a menu-driven command-line interface.

---

# ✨ Project Highlights

- Developed using **Modern C++ (C++17)** and STL
- Modular Object-Oriented Design
- Menu-driven Command Line Interface
- Weighted & Unweighted Graph Support
- Directed & Undirected Graph Support
- File-based Graph Loading
- Reusable Graph Engine Architecture
- Efficient implementation using Adjacency List
- Optimized graph traversal using STL containers

---

# 📌 Algorithms Implemented

### Graph Traversal
- Breadth First Search (BFS)
- Depth First Search (DFS)

### Connectivity
- Connected Components
- Cycle Detection
- Strongly Connected Components (Kosaraju)

### Shortest Path Algorithms
- Dijkstra Algorithm
- Bellman-Ford Algorithm
- Floyd-Warshall Algorithm
- A* Search

### Minimum Spanning Tree
- Prim's Algorithm
- Kruskal's Algorithm
- Disjoint Set Union (Union-Find)

### Graph Analysis
- Topological Sort
- Bridges Detection
- Articulation Points

---

# 🛠 Technologies Used

- Modern C++17
- Standard Template Library (STL)
- Object-Oriented Programming (OOP)
- Graph Theory
- Priority Queue
- Queue
- Stack
- Hash Maps
- File Handling

---

# 📂 Project Structure

```text
SmartRoutePlanner/

├── include/
│   ├── Graph.h
│   ├── BFS.h
│   ├── DFS.h
│   ├── Dijkstra.h
│   ├── BellmanFord.h
│   ├── ...
│
├── src/
│   ├── Graph.cpp
│   ├── BFS.cpp
│   ├── DFS.cpp
│   ├── Dijkstra.cpp
│   ├── ...
│
├── input/
│   └── graph.txt
│
├── output/
│
└── README.md