### Tic-Tac-Toe Game in Python

#### Overview
This project is a simple command-line implementation of the classic Tic-Tac-Toe game, where two players take turns marking spaces on a 3x3 grid. The game allows players to select their spots and checks for wins or ties after each turn.

#### How It Works
- The game initializes with an empty board represented by a list of dashes (`-`).
- Players take turns to input their move by selecting a number from 1 to 9, corresponding to the positions on the board.
- After each move, the game checks for a win or a tie:
  - A player wins if they have three of their marks in a row, either horizontally, vertically, or diagonally.
  - The game ends in a tie if all spots are filled without any player winning.
- The game continues until there is a winner or a tie.

#### Features
- **Player Input**: Players input their move by choosing a number between 1 and 9.
- **Win/Tie Detection**: The game checks for horizontal, vertical, and diagonal wins, as well as ties.
- **Player Switching**: The game alternates turns between Player X and Player O.

#### How to Play
1. Clone or download the repository.
2. Run the `tic_tac_toe.ipynb` file in a Python environment.
3. Follow the prompts to play the game.

#### Future Enhancements
- Implement a graphical user interface (GUI) using libraries like `Tkinter`.
- Add an AI opponent for single-player mode.
- Include an option to restart the game without exiting.

---
