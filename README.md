# Ship vs Obstacles Game

A fast-paced, action-packed game built using Python and Pygame. Navigate your ship through obstacles, collect coins, and power-ups while avoiding damage. Survive as long as possible and score the highest points!

## Features
- **Obstacles**: Avoid rocks that move across the screen. Collision will cost you health.
- **Coins**: Collect coins for extra points.
- **Power-ups**: Gain temporary boosts such as increased speed by collecting power-ups.
- **Difficulty**: The game difficulty increases as your score progresses, making obstacles and coins move faster.
- **Explosion Effect**: Experience explosion animations when you collide with obstacles.
- **Particles**: Small particles appear when collecting coins.
- **Pause & Resume**: Press "P" to pause the game and resume it at any time.
- **Game Over**: Once your health reaches zero, the game ends and you can restart by pressing "R".

## Installation
1. Clone the repository or download the code files.
2. Make sure you have Python and Pygame installed on your machine. You can install Pygame with:
   ```bash
   pip install pygame
   ```

## Game Setup
1. Place the following image files in your project directory:
   - `ship.png`: Image for the player's ship.
   - `rock1.png`: Image for the obstacles (rocks).
   - `background.png`: Background image for the game.
   - `powerup.png`: Image for the power-ups.
   - `coin.png`: Image for the coins.
   - `explosion.png`: Image for the explosion effect.
   - `game_over.png`: Image shown after the game ends.
2. Set the correct path for the font file (`font.otf`).

## Controls
- **Up Arrow (↑)**: Move the ship upwards.
- **Down Arrow (↓)**: Move the ship downwards.
- **Space**: Start the game.
- **P**: Pause or resume the game.
- **R**: Restart the game after a game over.

## Audio
The game includes sound effects:
- `collision.mp3`: Played when the ship collides with an obstacle.
- `powerup.mp3`: Played when the ship collects a power-up.
- `coin.mp3`: Played when the ship collects a coin.

## Known Issues
- Make sure the image and sound file paths are correct, as they may need to be updated based on your directory structure.
