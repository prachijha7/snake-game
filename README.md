# The Snake Game 🐍

A classic Snake game made with Python's Turtle graphics module. Control the snake, collect food, and try to beat your high score without hitting the walls or your own tail.

## Features

- Control the snake using the arrow keys.
- Collect food to increase your score and grow the snake.
- Detect collisions with the walls and the snake's own tail.
- Keep track of your high score between game sessions.
- Play in a simple black window with a white snake and blue food.

## Built With

- **Python** — game logic and functionality
- **Turtle** — graphics, movement, and keyboard controls

## Project Structure

```text
snake-game/
├── main.py
├── snake.py
├── food.py
├── scoreboard.py
├── data.txt
└── README.md
```

## Getting Started

### Requirements

- Python 3 installed on your computer
- No additional Python packages required; the game uses Python's built-in `turtle`, `random`, and `time` modules.

### Run the Game

1. Clone or download this repository.

2. Open a terminal in the project folder.

3. Run:

   ```bash
   python3 main.py
   ```

4. Use the arrow keys to control the snake.

Keep `data.txt` in the project folder because it stores the high score.

## How to Play

- **Up Arrow:** Move up
- **Down Arrow:** Move down
- **Left Arrow:** Move left
- **Right Arrow:** Move right

Collect the blue food to earn points. Each food item increases the score and makes the snake longer. Avoid the walls and your own tail. When a collision occurs, the snake resets and the score returns to zero.

Your high score is saved in `data.txt` when a round ends, provided you have beaten the previous record.

## How the Code Works

- **`main.py`** sets up the game window, connects the keyboard controls, runs the game loop, and checks for food, wall, and tail collisions.
- **`snake.py`** creates the snake from square segments, moves its body, changes direction, and adds new segments when food is collected.
- **`food.py`** creates the blue food and moves it to a new random position when collected.
- **`scoreboard.py`** displays the current score and high score, updates the score, and saves a new high score to the data file.
- **`data.txt`** stores the high score so it can be loaded again when the game starts.

## What I Learned

This project helped me practise Python, object-oriented programming, functions, loops, keyboard event handling, collision detection, and file handling. It also gave me experience organizing a project across multiple Python files.
