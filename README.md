# Tic-Tac-Toe
This project is a C implementation of the classic **Tic-Tac-Toe** game, where the player competes against the computer. The game features a 3x3 board and offers two difficulty levels: a standard mode and a challenging "God" mode. Scores for player wins, computer wins, and draws are tracked throughout the gameplay.

## Features

- **3x3 Tic-Tac-Toe board**.
- **Two difficulty levels**:
  - **Human Mode (Standard)**: Computer makes basic moves.
  - **God Mode (Impossible)**: Computer plays optimally, making it nearly unbeatable.
- **Score tracking**: Player wins, computer wins, and draws.
- **Dynamic computer moves**:
  - Blocks the player’s winning moves.
  - Prioritizes center and corner positions for better strategy.
- **Interactive gameplay**: Player inputs moves while the computer adapts to the game state.

## How to Run the Game

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-c.git
2. **Compile the program using GCC**:
   gcc tic_tac_toe.c
3. **Run the game**:
   ./a.out -For linux
   ./a.exe- For Windows

## Gameplay Instructions

After launching the game, select a difficulty level:
1 for Human Mode.
2 for God Mode.
The game alternates between the player and the computer, with the player always using X.
On your turn, enter the row and column (1-3) to place your X on the board.
The game continues until a player wins or the game is drawn.
After the game ends, you can choose to play again.
