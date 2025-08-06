# Snake Game

A classic Snake game implementation using Python and Pygame.

## Description

This is a complete implementation of the classic Snake game where you control a snake that grows longer as it eats food. The game features:

- Smooth snake movement using arrow keys
- Food spawning system
- Score tracking
- Collision detection (walls and self)
- Game over screen

## Features

- **Controls**: Use arrow keys to control the snake's direction
- **Scoring**: Score increases by 1 for each food eaten
- **Game Over**: Game ends when snake hits walls or itself
- **Visual Effects**: Snake has a gradient effect with two shades of blue

## Installation

### Prerequisites

- Python 3.x
- Pygame

### Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/snake-pygame.git
cd snake-pygame
```

2. Install Pygame:
```bash
pip install pygame
```

3. Run the game:
```bash
python snake_game.py
```

## How to Play

- Use **Arrow Keys** to control the snake's direction
- Eat the **red food** to grow and increase your score
- Avoid hitting the **walls** or **your own tail**
- Try to achieve the highest score possible!

## Game Controls

- **↑** - Move Up
- **↓** - Move Down
- **←** - Move Left
- **→** - Move Right

## Project Structure

```
snake-pygame/
├── snake_game.py    # Main game file
├── arial.ttf        # Font file
└── README.md        # This file
```

## Game Settings

You can modify these constants in `snake_game.py` to customize the game:

- `BLOCK_SIZE = 20` - Size of each snake segment and food
- `SPEED = 18` - Game speed (frames per second)
- `w=640, h=480` - Window dimensions

## Requirements

- Python 3.x
- Pygame library

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to fork this project and submit pull requests for any improvements!

## Author

Created as a Python/Pygame learning project. 