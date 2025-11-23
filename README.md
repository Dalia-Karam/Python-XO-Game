# 🕹️ Tic-Tac-Toe (Python CLI Version)

## A simple, interactive Tic-Tac-Toe game played in the terminal using Python.
### Two players take turns placing X and O symbols on a 3×3 board until one wins or the game ends in a tie.

### 🚀 Features

- Two-player mode

- Input validation for names, choices, and moves

- Clear game menu (Play / Restart / Exit)

- Dynamic board display

- Winner and tie detection

- Automatic symbol assignment (if Player 1 chooses X, Player 2 gets O)

### 🎮 How to Play

1. Run the program:

   python XO.py

2. Enter player names (letters only).

   Player 1 chooses X or O → Player 2 gets the other symbol.

3. Players take turns choosing a row (0–2) and column (0–2).

4. The game ends when:

   => A player wins

   => All cells are filled (tie)

5. Choose Restart or Exit when the match ends.

### 🧠 How It Works (Short Overview)

- Player class holds name and symbol

- Menu displays the menus

- Board manages:

  -- The 3×3 grid

  -- Displaying the board

  -- Validating moves

  -- Turn switching

  -- Winner and tie detection

- main() controls the overall game loop

### 📦 Requirements

Python 3.7 or higher
(No external libraries needed)

### 📜 License

This project is open-source. Use it freely for learning and practice :white_heart:.
