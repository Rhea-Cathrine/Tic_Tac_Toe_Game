## 🎮 Tic-Tac-Toe Game in C++

A simple **console-based Tic-Tac-Toe game** developed using **C++**. This project allows two players to play Tic-Tac-Toe by entering the row and column positions of their moves.

The program automatically validates user input, prevents players from selecting an occupied cell, checks for winning combinations, and declares the winner or a tie.

## 📌 Features

* 🎮 Two-player gameplay
* ❌ Player X and ⭕ Player O
* 🖥️ Console-based interface
* 🔢 Row and column input using values from `0–2`
* ✅ Input validation
* 🚫 Prevents selecting an already occupied tile
* 🏆 Automatically detects the winner
* ↔️ Checks horizontal rows
* ↕️ Checks vertical columns
* 🔀 Checks both diagonals
* 🤝 Detects a tie when all positions are filled

## 🛠️ Technologies Used

* **Language:** C++
* **Concepts:** Arrays, Loops, Conditional Statements, Functions/Logic, Input Validation
* **Compiler:** Any standard C++ compiler

## 🎯 How the Game Works

The game uses a **3 × 3 character array** to represent the Tic-Tac-Toe board.

```text
   |   |   
   |   |   
___|___|___
   |   |   
   |   |   
___|___|___
   |   |   
   |   |   
   |   |   
```

Players take turns entering the **row and column numbers**.

For example:

```text
Enter r c from 0-2 for row and column: 1 1
```

This places the player's symbol in the center of the board.

## 🎮 Game Rules

1. Player X starts the game.
2. Players take turns placing their symbols.
3. A player must enter a row and column between `0` and `2`.
4. An occupied position cannot be selected again.
5. A player wins by getting three matching symbols:

   * Horizontally
   * Vertically
   * Diagonally
6. If all nine positions are filled without a winner, the game ends in a tie.


## 💻 Example Gameplay

```text
   |   |   
 X | O |   
___|___|___
   |   |   
   | X |   
___|___|___
   |   |   
 O |   | X 
   |   |   

Current Player is O
Enter r c from 0-2 for row and column:
```

If a player completes a winning combination:

```text
PlayerX is the winner!
```

If all positions are filled without a winner:

```text
Tie!
```

## 🧠 Concepts Demonstrated

This project demonstrates several fundamental C++ programming concepts:

* Two-dimensional arrays
* Character variables
* `for` loops
* `while` loops
* `if-else` statements
* User input using `cin`
* Console output using `cout`
* Input validation
* Logical operators
* Conditional/ternary operator
* Game-state management

## 📂 Project Structure

```text
Tic-Tac-Toe/
│
├── main.cpp
└── README.md
```

## 🚀 Future Improvements

Possible improvements for future versions include:

* Add a graphical user interface
* Add single-player mode against the computer
* Add difficulty levels
* Add score tracking
* Allow players to restart without closing the program
* Improve the board design and user interface

## 👩‍💻 Author

**Rhea Cathrine Chella**




