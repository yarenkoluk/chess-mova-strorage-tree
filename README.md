# chess-mova-strorage-tree
# ♟️ Chess Move Storage Tree

This project implements a **tree-based data structure** to store and explore chess games and their possible variations.  
Each node represents a chess position after a move, while branches represent alternative continuations from the same position.

The project is designed to practice **data structures, tree traversal, and search algorithms** within an academic context.

---

## 📌 Project Motivation

In chess, a game does not progress in a single linear path.  
From any given position, multiple legal moves are possible, creating different variations.

To model this structure efficiently:
- A **tree** is used instead of arrays or linked lists
- Each position is stored as a node
- Variations are represented as child nodes

This approach is similar to professional chess analysis tools.

## 🌳 Data Structure Overview

- **Root Node**
  - Represents the initial chess position
  - Has no parent

- **Node**
  - Represents a position after a specific move
  - Stores:
    - Move notation (e4, Nf3, etc.)
    - Player to move (White / Black)
    - Move number
    - Parent reference
    - List of child nodes (variations)

- **Tree**
  - Manages the root node
  - Tracks the current position
  - Handles navigation and traversal
## ⚙️ Core Features (Planned)

- Add moves to the main line
- Add alternative variations at any position
- Navigate forward and backward in the move tree
- Display the main line from root to current node
- Print the entire tree using an ASCII-style structure
- Search moves using:
  - Depth-First Search (DFS)
  - Breadth-First Search (BFS)
- Generate basic statistics:
  - Maximum depth
  - Branching factor

## 🧠 Concepts Used

- Tree (n-ary tree)
- Parent–child relationships
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Recursion
- Object-Oriented Programming (OOP)

## 🚫 Constraints

- Chess move legality is **not** validated
- No circular references (tree structure only)
- Maximum depth and branching follow academic limits

## 📚 Academic Context

This project is inspired by a **Data Structures and Algorithms** course assignment and is implemented for learning and self-improvement purposes.

🚧 In development  
The project is being implemented step by step following a structured daily plan.
