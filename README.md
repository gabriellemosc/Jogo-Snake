

# Snake Game in Python 

This is a classic Snake game developed in Python using the Pygame library. The goal of the game is to control the snake to eat the food that appears on the screen, making it grow. The game ends if the snake collides with the walls or its own body.

## Pre requisites

Before running the game, make sure you have Python installed on your system. Additionally, you'll need to install the Pygame library.



### Installing Pygame

To install Pygame, open your terminal or command prompt and run the following command:

```bash
pip install pygame
```

## How to Run the Game

1. **Clone the repository** (if you haven't already):

   ```bash
   git clone https://github.com/gabriellemosc/Jogo-Snake
   cd Snake_Game
   ```

2. **Run the game**:

   In the terminal, navigate to the folder where the game file is located and run the following command:

   ```bash
   python main.py
   ```

   The game will start automatically.

## How to Play

- Use the **arrow keys** (↑, ↓, ←, →) to control the direction of the snake.
- The goal is to eat the food (green square) that appears on the screen. Each time the snake eats the food, it grows, and your score increases.
- The game ends if the snake collides with the walls or its own body.

## Code Structure

The code is organized as follows:

- **Initial setup**: Defines colors, screen size, game speed, and other parameters.
- **Main functions**:
  - `generate_food()`: Generates the food's position randomly.
  - `draw_food()`: Draws the food on the screen.
  - `draw_snake()`: Draws the snake on the screen.
  - `draw_score()`: Displays the current score.
  - `select_speed()`: Controls the snake's direction based on the keys pressed.
  - `run_game()`: Main function that manages the game logic.
- **Game loop**: Handles screen updates, user events, and collision detection.

## Customization

You can customize the game by modifying the following parameters in the code:

- **Screen size**: Change the `width` and `height` variables.
- **Game speed**: Adjust the `game_speed` variable.
- **Colors**: Change the colors of the snake, food, and background by modifying the RGB values in the `black`, `white`, `red`, and `green` variables.



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---



