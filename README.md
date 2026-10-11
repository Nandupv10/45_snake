# Snake Game

A grid-based Snake game built using Python and Pygame. This project was improved using AI-assisted debugging and code review.

## Features

- Grid-based snake movement using keyboard controls.
- Food spawning, snake growth, and score tracking.
- Prevents direct 180-degree direction reversal.
- Handles wall collisions and self-collisions.
- Displays a Game Over screen with the final score.
- Provides a replay menu with Easy, Medium, Hard, and Exit options.
- Plays sound effects when food is eaten and when the game ends.
- Handles unavailable audio hardware gracefully.

## Requirements

- Python 3.10 or later
- Pygame (see `requirements.txt`)

## Setup and Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the game:

```bash
python main.py
```

## Controls

- Arrow keys or WASD: Move the snake.
- After Game Over: Select a replay difficulty or exit, as supported by the game controls.

## Project Structure

```text
45_snake/
├── main.py
├── requirements.txt
├── game/
│   ├── game_engine.py
│   ├── snake.py
│   └── food.py
└── README.md
```

## Submission Evidence

- `before.mp4`: Gameplay before the changes.
- `after.mp4`: Gameplay after the changes.
- `Chat_History.pdf` and `Chat_History.json`: AI-assisted development conversation records.

## Testing

The updated code was checked for Python compilation and basic direction-reversal and replay-reset behavior. Full gameplay should also be tested manually.
