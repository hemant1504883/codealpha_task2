# codealpha_task2

 Objective:
Implement a Sudoku solver using C++ that can solve a 9x9 Sudoku grid using backtracking.

 Key Points:
1. Grid Representation: Use a 2D array `grid[N][N]` where `N` is defined as 9, representing the Sudoku puzzle.
2. Functions:
   - isPresentInRow: Check if a number `num` is already present in a specified row.
   - isPresentInCol: Check if a number `num` is already present in a specified column.
   - isPresentInBox: Check if a number `num` is already present in the 3x3 sub-grid starting at `boxStartRow`, `boxStartCol`.
   - findEmptyPlace: Find an empty location (marked with 0) in the Sudoku grid.
   - isValidPlace: Validate if placing `num` at position `(row, col)` is allowed based on Sudoku rules (not present in the same row, column, or 3x3 sub-grid).
   - solveSudoku: Recursive function to solve the Sudoku grid using backtracking.
   - sudokuGrid: Print the solved Sudoku grid.

 Functions:
- isPresentInRow(int row, int num):
  - Checks if `num` is present in the specified `row` of the Sudoku grid.
  
- isPresentInCol(int col, int num):
  - Checks if `num` is present in the specified `col` of the Sudoku grid.
  
- isPresentInBox(int boxStartRow, int boxStartCol, int num):
  - Checks if `num` is present in the 3x3 sub-grid starting at `(boxStartRow, boxStartCol)`.

- sudokuGrid():
  - Prints the current state of the Sudoku grid after solving.

- findEmptyPlace(int &row, int &col):
  - Finds the next empty location in the Sudoku grid and updates `row` and `col` with its coordinates.

- isValidPlace(int row, int col, int num):
  - Checks if placing `num` at position `(row, col)` is valid according to Sudoku rules.

- solveSudoku():
  - Uses backtracking to recursively attempt to solve the Sudoku puzzle:
    - Finds an empty place.
    - Tries placing numbers from 1 to 9.
    - Checks if the placement is valid.
    - Recursively attempts to solve the rest of the grid.
    - Backtracks if a solution cannot be found with the current configuration.






