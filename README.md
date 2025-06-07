# 💡 Lights-Out Puzzle AI Solver

This repository contains an AI-based solution to the **Lights-Out Puzzle**, a combinatorial logic game. The objective is to turn off all lights on an *n x n* grid, where toggling one light also toggles its adjacent lights. This project demonstrates the application of various **search algorithms** to efficiently solve the puzzle.

---

## 📁 Project Structure

- **`AI_CA1_Notebook.ipynb`**:  
  Interactive Jupyter notebook containing:
  - Problem formulation and grid rules.
  - Implementation of search algorithms:
    - Breadth-First Search (BFS)
    - Depth-First Search (DFS)
    - A* Search (with heuristics)
  - Step-by-step visual solution animation.
  - Runtime and memory usage analysis.

- **`Instruction.pdf`**:  
  Detailed assignment description, requirements, and evaluation criteria.

- **`Report.pdf`**:  
  Final report covering:
  - Explanation of implemented algorithms.
  - Trade-offs and insights.
  - Performance metrics (depth, time, space).
  - Discussion and future improvements.

---

## 🧮 Requirements
Python 3.x

Libraries:

numpy

random

heapq

tabulate

---

## 🎯 Insights

A* performed best in terms of efficiency and depth of solution.

BFS guaranteed optimal results but at high memory cost.

DFS was fastest in shallow depth but unreliable.

Visualizations in the notebook help to understand how toggling affects the grid.

---

## 📚 Academic Context

Course: Artificial Intelligence

University: University of Tehran

Instructor: Dr. YaghoobZadeh
