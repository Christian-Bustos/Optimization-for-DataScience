This repository contains Python files structured to solve the Maximum Clique Problem (MCP) using various Frank-Wolfe algorithms. The files are organized as follows:

Loading Data:
This section is used to load data by reading a .clq file.
Specify the path to the .clq file in the last cell of this section to load the data.

L2 Regularization:
This section solves the MCP using the Frank-Wolfe (FW), Away-Step Frank-Wolfe (AFW), and Pairwise Frank-Wolfe (PFW) algorithms, taking into account the L2 regularization term.

L0 Regularization:
This section solves the MCP using the FW, AFW, and PFW algorithms, taking into account the L0 regularization term.
Sections 2 and 3 each have a final cell that summarizes the results obtained so far.



Notebooks

Main.ipynb:
Used to test a single specific initial node.

Dual_Main.ipynb:
Used to test the convergence rate using a stopping condition based on the duality gap.

TestALL.ipynb:
Tests all nodes as the initial node and returns the node for which the maximum clique and its size are found.



Data

DIMACS_subset_ascii:
Contains the DIMACS graphs in .clq format that are used to test our implementation.