💫 Tic Tac Toe 

This is simple version of tic tace toe game. <br>

♦️ Game Initialization<br>
▶️ Variables and Constants: The game initializes variables for game elements (cells, status text, restart button), win conditions, the game state (options array), the current player, and a running state to control the game flow.<br>
▶️ InitializeGame Function: This function sets up the game by attaching click event listeners to each cell and the restart button, setting the initial status text, and marking the game as running.<br>

♦️ Game Mechanics<br>
▶️ Function: Triggered when a cell is clicked. It checks if the cell is already filled or if the game is not running. If neither condition is met, it updates the cell with the current player's symbol and checks for a winner.<br>
▶️updateCell Function: Updates the game state and the cell's text content with the current player's symbol.<br>
▶️changePlayer Function: Toggles the current player between "X" and "O" and updates the status text to indicate whose turn it is.<br>
▶️checkWinner Function: Iterates through predefined win conditions to check if any have been met. If a player wins, it updates the status text with the winner and stops the game. If there's a draw (no empty cells left), it declares a draw. Otherwise, it changes the player.<br>
▶️restartGame Function: Resets the game state, game board, and status text, and sets the game to running.<br>

♦️ Gameplay Flow<br>
▶️Game Starts: initializeGame is called when the script runs, setting up the game board.<br>
▶️Player Interaction: Players take turns clicking on empty cells. The game checks for win conditions or a draw after each turn.<br>
▶️Winning or Drawing: The game displays a message when a player wins or the game ends in a draw.<br>
▶️Restarting: Clicking the restart button resets the game to its initial state.<br>

♦️ HTML Elements Required<br>
For this script to function correctly, your HTML must have elements with the classes .cell for the game cells, an element with the ID #statusText for displaying the game status, and a button with the ID #restartBtn for restarting the game. Each cell should also have a unique cellIndex attribute used to identify it.

♦️ Enhancements<br>
You could enhance the game by adding animations, sound effects, or a score tracker.<br>
Implementing a simple AI opponent or adding multiplayer support via websockets could also make the game more interesting.<br>

https://github.com/Codeliki/Tic-Tac-Toe/assets/159378076/7f816bec-3d4b-40d8-aac8-a522d80a1103


