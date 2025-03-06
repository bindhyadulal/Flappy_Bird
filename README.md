# Flappy Bird Game

**Flappy Bird** is a simple arcade game where the player controls a bird that must fly between pipes without touching them or the ground. The goal is to keep the bird flying for as long as possible while avoiding obstacles.

## Requirements

- Python 3.x
- Pygame library

To install Pygame, run the following command:
```bash
pip install pygame
```

## How to Play

1. **Start the Game**: 
   - Run the script using Python:
     ```bash
     python flappy_bird.py
     ```
   - On the main menu, click anywhere to start the game.

2. **Controls**:
   - **Mouse**: Click anywhere on the screen to make the bird jump.
   - **Spacebar**: Press the spacebar to make the bird jump.

3. **Objective**:
   - Keep the bird flying between pipes for as long as possible without hitting them or the ground.
   - The game gets progressively more challenging as you score more points.

4. **Game Over**:
   - The game ends when the bird touches the ground or collides with a pipe.
   - After the game is over, you can click the restart button to play again.

5. **High Score**:
   - The high score is displayed on the main menu and updated after every game session. The high score is saved and persists even after the game is closed.

## Game Structure

- **Bird**: The bird can jump and fall due to gravity. It is controlled either by mouse clicks or the spacebar.
- **Pipes**: The pipes are obstacles that the bird must avoid. They move from right to left across the screen. The player must navigate the bird through the gaps between pipes.
- **Ground**: The ground scrolls horizontally to simulate movement.

## Game Flow

1. The player starts the game from the main menu by clicking anywhere on the screen.
2. The bird is controlled by mouse clicks or the spacebar to jump and avoid pipes.
3. The score increases each time the bird successfully passes through a pipe.
4. The game ends if the bird collides with a pipe or the ground.
5. The final score is displayed, and the player can restart the game by clicking the restart button.

## Features

- Simple and intuitive controls (mouse or keyboard).
- High score tracking with persistent storage.
- Animated bird with smooth gravity and jump mechanics.
- Obstacle (pipe) generation with increasing difficulty.
- Scrollable background and ground for immersive experience.
- Restart button to replay after game over.

## How the Game Works

- The bird is initially placed in the center of the screen and starts falling due to gravity.
- The player must click the mouse or press the spacebar to make the bird jump, trying to navigate through the gaps between the pipes.
- Pipes are generated periodically and move from right to left.
- If the bird hits the ground or a pipe, the game is over, and the score is displayed.
- The player can click the restart button to reset the game.

## License

This game is open-source and free to use. You can modify and distribute it under the terms of the MIT License.


