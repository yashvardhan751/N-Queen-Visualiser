View Project at :https://yashvardhan751.github.io/N-Queen-Visualiser/

Created a N-Queen Visualiser using HTML,CSS,JavaScript.

The N-Queens problem involves placing N queens on an N×N chessboard such that no two queens can attack each other. This means no two queens can share the same row, column, or diagonal. The goal is to find all possible arrangements where these conditions are met.

The conditions for solving the N-Queens problem are:

1. **No two queens can share the same row.**
2. **No two queens can share the same column.**
3. **No two queens can share the same diagonal.**

To solve the N-Queens problem using backtracking:

Initialize an empty N×N board.
Place a queen in the first column of the first row.
Move to the next row and place a queen in a safe column.
Continue placing queens row by row, ensuring no two queens threaten each other.
If a row is reached where no column is safe, backtrack to the previous row and move the queen to the next possible column.
Repeat the process until all queens are placed or all possibilities are exhausted.

