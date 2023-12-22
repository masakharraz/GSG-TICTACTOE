Tic-Tac-Toe Dart Console Application
A simple console-based Tic-Tac-Toe game implemented in Dart. The game allows two players to take turns making moves on a 3x3 grid until one player wins or the game ends in a draw. The application provides an interactive and user-friendly experience.

How to Play
Run the Dart application.
The Tic-Tac-Toe grid will be displayed.
Players take turns entering their moves (1-9) when prompted.
The game continues until one player wins, or the board is full resulting in a draw.
After each game, players can choose to play again.
Game Rules
The Tic-Tac-Toe board is represented as a 3x3 grid.
Players are represented by 'X' and 'O'.
To make a move, enter a number from 1 to 9 corresponding to the cell where you want to place your symbol.
The game checks for a win by checking rows, columns, and diagonals.
The game declares a draw when the board is full, and no player has achieved a winning condition.
Implementation Details
The TicTacToe class encapsulates the game logic and state.
The displayBoard method prints the current state of the board.
The makeMove method validates and records the player's move.
The checkWin method checks for winning conditions.
The isBoardFull method checks if the board is full.
The switchPlayer method switches between 'X' and 'O' players.
The startGame method runs the main game loop, allowing players to take turns.
The main function initializes and starts the game.
How to Run
Ensure you have the Dart SDK installed.
Save the code in a file, e.g., tic_tac_toe.dart.
Open a terminal and run dart tic_tac_toe.dart.
Follow the on-screen instructions to play the game.
Enjoy playing Tic-Tac-Toe!
