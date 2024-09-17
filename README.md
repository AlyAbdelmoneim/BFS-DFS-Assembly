# BFS-DFS-Assembly
MIPS Assembly Tree Traversal
This project involves MIPS assembly code to handle binary tree conversions and searches. The main functionalities include:

Conversion Functions:

BFS to DFS: Converts a binary tree from Breadth-First Search (BFS) order to Depth-First Search (DFS) order.
DFS to BFS: Converts a binary tree from DFS order to BFS order.
Search Functions:

Level-Order Search: Searches for a target value in the BFS array using level-order traversal.
Preorder Search: Searches for a target value in the BFS array using pre-order traversal.
Setup
Before calling the conversion or search functions, ensure the following registers are set up:

Conversion Functions:

la $a0, bfs - Address of BFS array
la $a1, dfs - Address of DFS array
lw $a2, length - Length of the array
li $a3, 0 - Start with root node index
li $s0, 0 - Initialize index
Search Functions:

la $a0, bfs - Address of BFS array
lw $a1, target - Target value to search
lw $a2, length - Length of the BFS array
Usage
Load the BFS or DFS array into memory.
Set up the registers as specified.
Call the respective conversion or search function.
License
This project is licensed under the MIT License. See the LICENSE file for details.

