#N Queen Visualizer
The N Queen is the problem of placing N chess queens on an N×N chessboard so that no two queens attack each other.

##Implementation
Backtracking Algorithm Method:
The idea is to arrange the queens in different rows one by one, beginning with the topmost row. When we put a queen in a row, we look for clashes with previously placed queens. If we locate a row in the current column with no collision, we mark this row and column as part of the solution. We backtrack and return false if we cannot discover such a row owing to clashes.

![image](https://user-images.githubusercontent.com/76558062/214357376-f2ef3658-df0e-44e9-8959-6c43a43b8e68.png)

Time Complexity: O(N!)
Auxiliary Space: O(N2)

##Backtracking 
Backtracking is an algorithmic technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point in time (by time, here, is referred to the time elapsed till reaching any level of the search tree).
