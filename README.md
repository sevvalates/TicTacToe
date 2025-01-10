# Tic-Tac-Toe

A simple React implementation of the classic Tic-Tac-Toe game. This project demonstrates the use of React components, state management, and a move history feature with move locations.

This project is a modified and improved version of the official Tic Tac Toe tutorial from React's official website.
**Original tutorial:** [React Tutorial - Tic Tac Toe](https://react.dev/learn/tutorial-tic-tac-toe)


## Features

- **Classic Gameplay:** Two players take turns placing "X" and "O" on a 3x3 grid.
- **Dynamic Move History:** Displays a list of all moves with their corresponding positions (row, col).
- **Winner Highlighting:** Highlights the three squares that form the winning combination.
- **Move Navigation:** Jump to any move in the game's history to view the board at that point.
- **Draw Detection:** Displays a message if the game ends in a draw.
- **Ascending/Descending Order Toggle:** Sort the move history list in ascending or descending order.
- **Restart Button:** A "Restart Game" button is provided to reset the game state back to its initial condition.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-react.git
   cd tic-tac-toe-react

2. **Install Dependencies:**
   ```bash
   npm install
   
3. **Start the Development Server:**
   ```bash
   npm start

## How to Play

1. The game starts with "X" as the first player.
2. Players alternate turns by clicking on any empty square.
3. The game ends when:
   -A player gets three of their marks in a row, column, or diagonal (winner is highlighted).
   -All squares are filled with no winner (game is a draw).
   
Use the move history list to jump to a previous game state.
Use "Sort Ascending/Descending" to toggle the sort order of the move history list.

