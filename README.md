# 🎮 Tic-Tac-Toe

A simple **Tic-Tac-Toe game built entirely in Python**, playable through the command line. Created as a learning project after exploring Python classes and objects.

## ✨ Features

- **Command-Line Interface:** Play directly in the terminal without a GUI.
- **Computer Opponent:** Play against the computer.
- **Randomized AI:** The computer selects moves randomly, making its gameplay unpredictable but not particularly competitive.
- **Turn Skipping:** Selecting a cell that is already occupied will skip your turn instead of allowing you to retry.

## 🎯 Gameplay Example

Here's an example of what the board looks like during a game:

```text
Board:
| X | O | X |
|   |   |   |
|   |   |   |
```

In this state, the first row is already filled.

If you try to place another `X` in **Row 1, Column 1**, the cell is already occupied, so your turn will be skipped. You won't get another attempt for that turn.

## 🤖 Computer AI

The computer opponent uses **completely random moves** to choose its next cell.

Don't expect a challenging opponent just yet! This project focuses on implementing the game using Python rather than building an advanced AI.

## 🛠️ Built With

- **Python**
- Object-Oriented Programming (OOP)
- Classes and Objects

## 🚀 Getting Started

1. Make sure Python is installed on your system.
2. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

3. Navigate to the project directory:

   ```bash
   cd <your-project-folder>
   ```

4. Run the Python file:

   ```bash
   python game.py
   ```

## 📚 What I Learned

- Applying classes and objects in Python.
- Implementing game logic and managing a game board.
- Handling player moves and occupied cells.
- Creating a simple computer opponent.

---

*This is a beginner-friendly project built while learning Python and Object-Oriented Programming.*
