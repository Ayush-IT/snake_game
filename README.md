# snake_game

Snake Game
This is a classic Snake game built using Python's Turtle module. The player controls the snake to eat food, which causes the snake to grow. The game ends if the snake collides with the walls or its own tail.

Features
Classic Snake game mechanics with movement and growth
Food appears randomly on the screen for the snake to eat
Scoreboard to track the player's score
Game over when the snake hits the wall or its own body

Project Structure
The project consists of the following Python files:

main.py: The main game loop where the snake, food, and scoreboard are initialized and the game is executed.
snake.py: Contains the Snake class that handles snake movement, growth, and direction control.
food.py: Contains the Food class that generates and positions the food randomly on the screen.
scoreboard.py: Contains the Scoreboard class to display the current score and handle game-over logic.


Gameplay Instructions
Player Controls:

Use the Up, Down, Left, and Right arrow keys to move the snake in the corresponding direction.
The objective of the game is to control the snake to eat the food. Each time the snake eats, it grows longer, and the player's score increases.

The game ends if:

The snake hits any of the four walls.
The snake collides with its own tail.
Installation and Running
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/snake-game.git
Navigate to the project directory:

bash
Copy code
cd snake-game
Install Python if you haven't already. You can download it here.

Run the game:

bash
Copy code
python main.py

Dependencies
This project uses the built-in Turtle module from Python, so no external libraries are required.
