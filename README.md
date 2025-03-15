# Tic-Tac-Toe Game

Welcome to the Tic-Tac-Toe game! 🎮

This project allows you to play a game of Tic-Tac-Toe against a bot named Pixi. The game offers different difficulty levels and interactive choices for players to customize their experience.

## Features
- **Interactive Name Input:** Players can enter their name to start the game.
- **Game Rules:** Players can choose to view the game rules at the start.
- **Symbol Selection:** Players can choose their symbol (X or O).
- **Bot Play Option:** Players can choose whether to start the game or let the bot play first.
- **Difficulty Levels:** Choose between easy, medium, or hard difficulty levels (hard mode is under development).
- **Replay Option:** After each game, players can choose to play again or exit.

## Functions

### `ask_name()`
Prompts the player to enter their name. The name must not be empty or contain only spaces.

### `show_rules()`
Allows players to view the game rules. The rules explain the goal of the game, the grid setup, and the bot's role.

### `choose_symbol()`
Prompts the player to choose their symbol (`X` or `O`). The bot automatically gets the opposite symbol.

### `choose_starter()`
Determines whether the player or the bot will start the game.

### `choose_difficulty()`
Allows the player to choose the game difficulty (`easy`, `medium`, `hard`). Hard mode is currently under development.

### `print_grid()`
Displays the current game grid.

### `ask_position()`
Prompts the player to input a valid position (row and column) on the grid.

### `check_victory()`
Checks if there is a winner after each move (horizontal, vertical, or diagonal).

### `easy_bot()`
Bot's behavior in easy mode, where it places its symbol in the first available space.

### `medium_bot()`
Bot's behavior in medium mode, where it blocks the player and tries to win when possible.

### `play_easy()`
Main game loop for easy mode.

### `play_medium()`
Main game loop for medium mode.

### `play_hard()`
Hard mode is currently under development.

### `ask_replay()`
Prompts the player to ask if they want to play again after the game ends.

## How to Play
1. Run the script.
2. Enter your name when prompted.
3. Choose to view the game rules (optional).
4. Choose your symbol (X or O).
5. Decide if you want to start the game or let the bot start.
6. Select the difficulty level (easy, medium, or hard).
7. Play the game by entering the row and column to place your symbol.
8. The bot plays automatically based on its difficulty level.
9. After the game ends, you can choose to play again.

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/clarisse-oyharcabal/clock.git
2. Navigate to the project directory:
   ```bash
   cd TicTacToe
4. Run the Python script:
   ```bash
   python main.py
