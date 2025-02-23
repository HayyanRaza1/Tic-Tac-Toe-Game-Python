# Tic-Tac-Toe Game in Python

## Description
This is a simple command-line Tic-Tac-Toe game implemented in Python. The game allows a human player to play against the computer. The computer makes random moves, while the player inputs their moves manually.

## Features
- The game board is displayed in a structured format.
- The player enters their move by choosing a number from 1 to 9.
- The computer makes a random move from the available spaces.
- The game checks for a winner after every move.
- The game ends when either the player or the computer wins or when the board is full, resulting in a tie.

## How to Play
1. The game starts with an initial board where the center square is occupied by an 'X' (computer's move).
2. The player is prompted to enter a number from 1 to 9 corresponding to an available position on the board.
3. The board updates accordingly, and the computer makes its move.
4. The game continues in turns until a player wins or the board is full.
5. The winner is displayed, or the game ends in a tie.

## Code Overview
- `display_board(board)`: Displays the Tic-Tac-Toe board.
- `enter_move(board)`: Allows the player to input their move.
- `make_list_of_free_fields(board)`: Generates a list of available positions.
- `victory_for(board, sgn)`: Checks if either the player ('O') or the computer ('X') has won.
- `draw_move(board)`: The computer makes a random move.

## Requirements
- Python 3.x

## Running the Game
Save the script as `tic_tac_toe.py` and run it using the following command:
```sh
python tic_tac_toe.py
```

## Example Output
```
+-------+-------+-------+
|       |       |       |
|   1   |   2   |   3   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   4   |   X   |   6   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   7   |   8   |   9   |
|       |       |       |
+-------+-------+-------+
Enter your move:
```

## License
This project is released under the MIT License.

