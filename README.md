# snake-game

## Overview

The Snake Game is a classic arcade game where the player controls a snake that moves around the game area. The goal is to collect food that appears randomly on the screen while avoiding collisions with the snake's own body or the walls. As the snake eats more food, it grows longer, making the game increasingly challenging.

## Features

- **Control the Snake**: Use arrow keys or on-screen buttons to navigate the snake.
- **Food Generation**: Randomly placed food items that the snake can consume to grow.
- **Score Tracking**: The score increases with each food item collected.
- **Collision Detection**: The game ends if the snake collides with itself or the walls.
- **Responsive Controls**: Works with both keyboard and touch screen controls.

## Installation

To get the Snake Game up and running on your local machine, follow these steps:

1. **Clone the Repository**: 

    ```bash
    git clone  https://github.com/harsh3446/snake-game.git
    cd snake-game
    ```

2. **Open the Project**:

    Open the `index.html` file in your web browser. You don't need to install any additional software since the game runs entirely in the browser.

## Usage

1. **Starting the Game**:

    - **Keyboard Controls**: Use the arrow keys (`ArrowUp`, `ArrowDown`, `ArrowLeft`, `ArrowRight`) to control the snake.
    - **Touch Controls**: Use the on-screen buttons (`↑`, `↓`, `←`, `→`) to navigate the snake.

2. **Gameplay**:

    - The snake moves continuously in the direction of the last pressed arrow key or button.
    - Collect food to increase the snake's length and score.
    - Avoid colliding with the walls or the snake's own body to continue playing.

3. **Game Over**:

    - The game ends if the snake hits a wall or itself.
    - Upon game over, the snake resets to its initial position, and the score is reset to zero.

## Code Structure

- **`index.html`**: Contains the structure of the game, including the game container, score display, and control buttons.
- **`style.css`**: Defines the styles for the game layout and appearance.
- **`script.js`**: Contains the game logic, including rendering, controls, food generation, and collision detection.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or bug fixes. Please ensure that your contributions adhere to the existing coding style and include tests if applicable.

## Contact

For any questions or suggestions, please open an issue on the repository or contact me directly.

---
