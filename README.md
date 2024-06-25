# Tic-Tac-Toe Game

## Objective

Create a Tic-Tac-Toe game in C++ where two players can play against each other. The game will use a two-dimensional array to represent the game board and loops to manage the game flow.

## Requirements

### Game Board Representation

The game should use a 3x3 two-dimensional array to represent the Tic-Tac-Toe board.

### Player Moves

The program should:
- Alternate between two players (Player 1 and Player 2).
- Allow players to input their moves (available spaces).
- Validate moves to ensure they are within the board and not on already occupied spaces.

### Game Logic

The program should:
- Check for a win condition (three in a row horizontally, vertically, or diagonally).
- Check for a draw condition (board is full with no winner).
- Announce the winner or if the game is a draw.

### Display

The program should display:
- The current state of the board after each move.
- Instructions for players on how to input their moves.
- The final result of the game (win/draw).

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`).

### 2. Define Variables

- Define a 3x3 two-dimensional array to represent the game board.
- Define variables to keep track of the current player.

### 3. Initialize the Game Board

- Create a function to initialize the game board with empty spaces or numbers indicating cell positions.

### 4. Display the Game Board

- Create a function to display the current state of the game board.

### 5. Player Move Input

- Create a function to prompt the current player to input their move (space 1-9).
- Validate the input to ensure it is within the board and the selected cell is empty.

### 6. Check Win Condition

- Create a function to check if the current player has won the game.

### 7. Check Draw Condition

- Create a function to check if the game is a draw.

### 8. Game Loop

- Implement the game loop to alternate between players, display the board, and check for win/draw conditions after each move.

### 9. Announce Result

- Announce the winner or if the game is a draw.

## Example User Interaction

```plaintext
*******************************
*        Tic-Tac-Toe          *
*******************************

  1 | 2 | 3
 ---+---+---
  4 | 5 | 6
 ---+---+---
  7 | 8 | 9

Player 1 (X), enter your move (available space): 1

  X | 2 | 3
 ---+---+---
  4 | 5 | 6
 ---+---+---
  7 | 8 | 9

Player 2 (O), enter your move (available space): 2

  X | O | 3
 ---+---+---
  4 | 5 | 6
 ---+---+---
  7 | 8 | 9

...

Player 1 (X), enter your move (available space): 5

  X | O | 3
 ---+---+---
  4 | X | 6
 ---+---+---
  7 | 8 | X

Player 1 (X) wins!
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
