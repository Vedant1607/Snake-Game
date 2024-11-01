
# Snake Game

A classic Snake Game built using Python's `turtle` graphics library. Guide the snake to consume food, increase its length, and score points. Be cautious, though—if the snake collides with itself or the game boundaries, it’s game over!

## Features
- **Classic Gameplay:** Navigate the snake to eat the food, grow, and increase the score.
- **Score Tracking:** Real-time score updates and a game-over message upon collision.
- **User Controls:** Use arrow keys to control the snake's direction.

## Project Structure
The project contains the following files:

- **main.py**: Initializes the game screen, listens for user input, and manages the main game loop.
- **snake.py**: Defines the `Snake` class, responsible for creating the snake, handling its movement, growth, and direction.
- **food.py**: Contains the `Food` class, which randomly places food on the screen for the snake to consume.
- **scoreboard.py**: Contains the `Score` class, which tracks and displays the score and handles game-over functionality.

## Installation and Setup
1. Ensure you have Python installed on your system.
2. Clone the repository or download the source code files.
3. Run the following command to start the game:

   ```bash
   python main.py
   ```

## How to Play
- Use the **Up, Down, Left, and Right** arrow keys to control the snake’s direction.
- The objective is to eat the food that appears randomly on the screen. Each time the snake eats food, it grows longer, and the score increases by 1.
- Avoid hitting the boundaries or the snake’s own body, as this will end the game.

## Requirements
- Python 3.x

The game utilizes the `turtle` library, which is built into Python, so no additional installations are required.
