# GEMINI.md - Project Context

## Project Overview
This is a classic Snake game implemented in Python using the `pygame` library. The project consists of a single-file game engine (`snake.py`) that handles graphics, user input, and game logic.

- **Main Technology**: Python 3
- **Graphics Library**: `pygame`
- **Architecture**: Procedural game loop with event-driven input handling.

## Building and Running

### Prerequisites
- Python 3.x installed.
- `pygame` library.

### Key Commands
- **Install Dependencies**:
  ```bash
  pip install pygame
  ```
- **Run the Game**:
  ```bash
  python snake.py
  ```

## Development Conventions

### Code Structure
- **Global Constants**: Screen dimensions (`WIDTH`, `HEIGHT`), colors, and game settings (`SNAKE_BLOCK`, `SNAKE_SPEED`) are defined at the top of `snake.py`.
- **Game Loop**: The core logic resides in the `gameLoop()` function, which manages state updates, rendering, and collision detection.
- **Rendering**: Custom functions like `our_snake()`, `message()`, and `show_score()` are used to abstract drawing operations.

### Coding Style
- Follows standard Python naming conventions (snake_case for variables and functions).
- Simple procedural logic without complex class hierarchies, prioritizing readability and ease of understanding for a basic game prototype.

### Testing
- No automated tests currently exist. Manual verification is required by running the script and observing game behavior (collision detection, scoring, movement).
