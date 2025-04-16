# ECAssignment1
Assignment 1: Finding Optimal Value for GAP.


This MATLAB script processes 12 benchmark GAP datasets (gap1.txt to gap12.txt) and computes the optimal assignment cost for each test case using Integer Linear Programming (ILP). It formats and displays the results in a grouped, readable structure while also saving them to gap_ilp_result.txt.

Reads input from gap1.txt to gap12.txt, each containing multiple GAP instances.
Uses intlinprog from MATLAB’s Optimization Toolbox to solve GAP as a binary integer linear program.
📁 Output
Text file: gap_ilp_result.txt
