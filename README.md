# Sudoku-solver
This sudoku solver is made by using the backtracking algorithmm and the GUI uses the pygame library.Backtracking is simply reverting back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. We will use this principle of backtracking to implement the following algorithm.

Algorithm

Starting with an incomplete board:

    1.Find some empty space
    2.Attempt to place the digits 1-9 in that space
    3.Check if that digit is valid in the current spot based on the current board
     a. If the digit is valid, recursively attempt to fill the board using steps 1-3.
     b. If it is not valid, reset the square you just filled and go back to the previous step.
    4.Once the board is full by the definition of this algorithm we have found a solution.

