# 23BCA10150--Tic-Tac-Toe
A simple, interactive, console-based Tic-Tac-Toe game implemented in C++ with a focus on basic Data Structures and Algorithms (DSA). This project demonstrates fundamental concepts like arrays, loops, and conditionals to manage game logic and player interactions.

How to Play-
The game starts with Player 'X' by default.
Players are prompted to enter the row and column (0-2) of the cell where they want to place their mark.
After each move, the board is displayed.
The game checks for a winner or draw after every turn. If there’s a winner, the game announces the winner and ends.
If all cells are filled with no winner, the game declares a draw.

Code Structure-
drawBoard: Function to render the game board after each turn.
checkWin: Function to check if the current player has won by forming a row, column, or diagonal.
main function: Controls the game flow, player inputs, and turn-switching.

Key Data Structures & Algorithms-
2D Array: A 3x3 array (board[3][3]) to represent the game board and keep track of player moves.
Looping and Conditional Statements: To iterate over the game board and validate user inputs.
Win-Checking Algorithm: Checks rows, columns, and diagonals for three consecutive same marks.
