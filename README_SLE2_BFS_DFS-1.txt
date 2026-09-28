README – SLE-2: BFS vs DFS Profiling

Course: 02AML204 – Introduction to Artificial Intelligence
PRN: 24UAM014
Name: Shrivardhan Chavan
Division: A
Date: 22/9/2026

PROJECT TITLE
SLE-2 Profiling: BFS vs DFS on a Maze (Grid Graph)

DESCRIPTION
This project compares Breadth-First Search (BFS) and Depth-First Search (DFS)
for finding a path through a 20 × 20 grid maze represented as a graph.

MAZE SETUP
- Grid size: 20 × 20
- Wall probability: approximately 20%
- Start: (0, 0)
- Goal: (19, 19)

ALGORITHMS
1. BFS – Breadth-First Search
2. DFS – Depth-First Search (iterative, with a visited set)

PROFILING METHOD
Python's time.perf_counter() was used to measure execution time.
A manual node counter recorded the number of nodes expanded/popped.
Both algorithms were tested on the same maze and start/goal pair.
Each algorithm was run 3 times.

RESULTS

Metric                 BFS       DFS
Average Time (ms)      0.3268    0.1998
Nodes Expanded         328       225
Path Length (steps)    39        45

OBSERVATION
DFS was faster and expanded fewer nodes on this particular maze.
BFS found a shorter path.

CONCLUSION
The experiment demonstrates the difference between the two search methods:
BFS provides a shortest path in this unweighted grid, while DFS does not
guarantee the shortest path but found a path faster in this particular test.

FILES
- SLE2_PRN_24UAM014_Shrivardhan_Chavan-2.docx – Main profiling report
- SLE2_BFS_DFS_Graph.pdf – Graph and results table
- README_SLE2_BFS_DFS.txt – This README file

SOURCE NOTE
The information in this README is based on the uploaded SLE-2 profiling
report and accompanying project material.
