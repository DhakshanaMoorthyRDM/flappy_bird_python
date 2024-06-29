# Flappy Bird Game
This project implements a simple version of the classic Flappy Bird game using Python and the Pygame library. The game consists of various components to create a fully functional and interactive gaming experience.

![image](https://github.com/DhakshanaMoorthyRDM/LightGBM_Gold_Forecast/assets/121345776/75ec98b9-cacd-448d-9cb8-ae42c89c3fc8)


## Folder Structure
```bash
Flappy-Bird/
│
├── img/                    # Images used in the game
├── scrolling_background/   # Code for scrolling background effect
├── sprite_animation/       # Animation logic for sprites
├── game_physics/           # Physics engine for game mechanics
├── scrolling_pipes/        # Code to handle scrolling pipes
├── score_counter/          # Logic for scoring mechanism
├── game_over/              # Game over screen logic
├── flappy.py               # Main Python file for game execution
```

## Project Overview
This project recreates the Flappy Bird game in Python using the Pygame library. The game includes the following components:

1.Game Mechanics
Sprite Animation: Handles the animation logic for the bird and obstacles.

2.Game Physics: Implements the physics engine for gravity and collision detection.

3.Scrolling Background: Creates a scrolling effect to simulate continuous movement.

4.Scrolling Pipes: Manages the generation and movement of pipes that the bird must avoid.

5.Score Counter: Tracks and displays the player's score based on successful passes through pipes.

6.Game Over Screen: Displays game over message and handles restart functionality.

## Implementation Details
The main Python file flappy.py integrates all game components using Pygame. It includes event handling, game loop management, and screen rendering to create a seamless gaming experience.

## How to Play

#### Installation Requirements:

Python 3.x
Pygame library (pip install pygame)

#### Clone the Repository:

```bash
git clone https://github.com/yourusername/Flappy-Bird.git
cd Flappy-Bird
```
Run the Game:

```bash
python flappy.py
```

#### Game Controls:

RIGHT CLICK to make the bird flap and navigate through the pipes.
Avoid collision with pipes to continue playing and score points.
#### Game Over:

The game ends if the bird collides with a pipe or falls off the screen.
Press RESTART to restart the game after a game over.

## Files Description

1.flappy.py: Main Python script containing game logic and execution.

2.img/: Folder containing images used for sprites and backgrounds.

3.scrolling_background/: Code for creating a scrolling background effect.

4.sprite_animation/: Animation logic for sprites like the bird and pipes.

5.game_physics/: Physics engine for handling game mechanics.
scrolling_pipes/: Logic for generating and moving pipes in the game.

6.score_counter/: Code to manage scoring based on player performance.

7.game_over/: Handling the game over screen and restart functionality.

## Acknowledgements
Pygame community and contributors for the game development framework.

Inspiration drawn from the original Flappy Bird game by Dong Nguyen.

Enjoy playing Flappy Bird!
