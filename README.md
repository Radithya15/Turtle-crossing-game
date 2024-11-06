# Turtle Crossing Game

This is a simple Turtle Crossing game built using Python's Turtle graphics library. The objective of the game is to help the player (a turtle) cross the screen without getting hit by the moving cars. Each successful crossing increases the game difficulty.

## Features

- **Player Movement**: Move the player upward by pressing the "Up" arrow key.
- **Car Creation**: Cars of different colors appear randomly on the screen and move across.
- **Collision Detection**: If the player collides with a car, the game ends.
- **Leveling Up**: Each successful crossing increases the game level, which makes the cars move faster.
- **Score Display**: Shows the current level on the screen.

## Project Structure

- **main.py**: Initializes the game screen and contains the main game loop.
- **player.py**: Manages the player's movements and detects if it reached the finish line.
- **car_manager.py**: Manages the cars, including creation, movement, and increasing speed at each level.
- **scoreboard.py**: Displays the current level on the screen and shows a "Game Over" message when the game ends.

## Setup and Requirements

This project requires Python 3.6+ and uses the Turtle graphics library, which is included with Python's standard library.

## How to Play

1. Run the `main.py` file to start the game.
2. Press the "Up" arrow key to move the player upward.
3. Avoid getting hit by the cars to stay in the game.
4. Successfully reach the top to level up and increase the difficulty.

Enjoy the game, and see how many levels you can complete!
