# 🌳 AVL Tree: Self-Balancing Binary Search Tree in Python

This project implements an **AVL Tree**, a self-balancing Binary Search Tree (BST), in Python. It ensures logarithmic time complexity for insertions, deletions, and searches by maintaining balance through rotations. This repository includes the core AVL Tree logic, visualization using `networkx` and `matplotlib`, detailed comments, structured LaTeX report (APA format), and BibTeX references.

---

## 📌 Overview

Standard BSTs can degrade to a linear structure (like a linked list) when data is inserted in a sorted manner. AVL Trees solve this by keeping the height of the left and right subtrees balanced within a maximum difference of 1. In other words, It addresses the performance issue of standard BSTs, which can degrade to O(n) time complexity for operations like search, insertion, and deletion when skewed (e.g., with sorted insertions). The AVL Tree maintains a balance factor of -1, 0, or 1 at each node, ensuring O(log n) performance through rotations. Key features include:

- `AVLNode` and `AVLTree` classes for tree structure and operations.
- Rotations (Left-Left, Right-Right, Left-Right, Right-Left) for balancing while maintaining the BST property.
- Unit tests to verify correctness and balance.
- Tree visualization using `matplotlib` and `networkx`.

This project is useful for studying self-balancing trees and their applications in database indexing, search algorithms, and memory management.


