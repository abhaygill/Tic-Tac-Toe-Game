# Tic-Tac-Toe-Game
This project is completed by using DSA concepts in C++ language.


1. Global Variables and Initial Setup:
•	board[3][3]: 2D array representing the Tic-Tac-Toe grid, initialized with positions (1-9).
•	choice, row, column: Store player's choice and map it to the grid.
•	turn: Tracks the current player's turn ('X' or 'O').
•	draw: Indicates if the game ended in a draw.

3. Display Board Function:
•	Displays the current state of the board on the console.
•	Organizes the board into a structured grid format with lines separating rows and columns.
•	Ensures players can clearly see the board’s status after every turn.

4. Player Turn Function:
•	Handles the player’s move by prompting them to choose a position on the board.
•	Converts the chosen position into row and column indices for the board.
•	Validates if the chosen cell is empty, updates the board with the player’s symbol, and switches the turn.
•	If an invalid move is made, it recursively prompts the player to choose again.

5. Game Over Function:
•	Checks for winning conditions by evaluating all rows, columns, and diagonals for three matching symbols.
•	Returns false to signal the end of the game if a player wins.
•	Checks if the board is full without a winner, sets the draw flag, and ends the game if true.
•	Returns true if no winning or draw conditions are met, allowing the game to continue.

6. Main Function:
•	Prompts players for their names and initializes the game.
•	Enters a loop that continues the game until a win or draw condition is met.
•	Repeatedly displays the board, handles player turns, and checks for game-over conditions.
•	After the loop, announces the winner or declares a draw based on the final state of the game.

# OUTPUT

![image](https://github.com/user-attachments/assets/76cc146f-3c17-49e1-9662-31c50f3949aa)
![image](https://github.com/user-attachments/assets/92e4897f-3bfa-4e1d-ae33-79da5f4d0165)




