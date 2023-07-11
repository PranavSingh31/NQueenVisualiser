# N Queen Visualizer
The N Queen is the problem of placing N chess queens on an N×N chessboard so that no two queens attack each other.

## Backtracking 
Backtracking is an algorithmic technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point in time (by time, here, is referred to the time elapsed till reaching any level of the search tree).

## Implementation
Backtracking Algorithm Method:
The idea is to arrange the queens in different rows one by one, beginning with the topmost row. When we put a queen in a row, we look for clashes with previously placed queens. If we locate a row in the current column with no collision, we mark this row and column as part of the solution. We backtrack and return false if we cannot discover such a row owing to clashes.

![be8c245f-5620-4178-9dea-aa408868088c_1621674069 4770846](https://user-images.githubusercontent.com/76558062/214358794-af24a83c-3f26-4a95-9291-542616ef0e18.gif)

#### Time Complexity: O(N!)
#### Auxiliary Space: O(N²)

Check out this Sorting Visualizer too : https://github.com/PranavSingh31/SortingVisualizer
