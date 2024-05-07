This Java program implements a simple Tic-Tac-Toe game using Swing GUI components. It allows two players to take turns placing their marks (X or O) on a 3x3 grid, and it checks for a winner or a tie after each move.

The tictactoe class contains:

- Instance variables for the game components like JFrame, JLabel, JPanel, and JButton.
- A constructor that sets up the game board layout and initializes the components.
- Methods to check for a winner, a tie, and to reset the game.
- Action listeners for the buttons representing the grid tiles to handle player moves.

The game GUI consists of a main frame with a title label, a panel for the game board, and a panel for control buttons (Reset and Exit). The game board is represented by a 3x3 grid of buttons, where players can click to place their marks.

The CheckWinner() method checks for winning conditions horizontally, vertically, diagonally, and anti-diagonally. It also checks for a tie if all tiles are filled without a winner.

The setWinner() method highlights the winning tiles and displays the winning player's message.

The SetTie() method highlights all tiles in case of a tie and displays a tie message.

The resetGame() method resets the game board to its initial state.

You can find the complete code for this Tic-Tac-Toe game on GitHub at [repository_link].
