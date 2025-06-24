# 2048 Game (Python + Tkinter)

A simple implementation of the classic [2048](https://en.wikipedia.org/wiki/2048_(video_game)) puzzle game using Python and Tkinter for the graphical user interface.

## Features

- **Classic 2048 gameplay**: Use arrow keys to slide and merge tiles.
- **Simple GUI**: Built with Tkinter, no external dependencies.
- **Score tracking**: See your score update as you play.
- **Game over detection**: Notifies you when no moves are left.

## How to Play

- Use the arrow keys (Up, Down, Left, Right) to move the tiles.
- When two tiles with the same number touch, they merge into one.
- Try to reach the 2048 tile!

## Project Structure

- `2048game.py` - Main source code for the game.

## How to Run

1. Make sure you have Python 3.x installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/abhishekbidare03/2048-Game-using-Python.git
   ```
3. Navigate to the project directory:
   ```bash
   cd 2048-game
   ```
4. Run the game:
   python 2048game.py


### About the Code

- The game uses a 4x4 grid, displayed using Tkinter `Label` widgets.
- Tiles are moved and merged according to the 2048 rules.
- The score is updated as you merge tiles.
- The game ends when no moves are left (no empty cells and no adjacent equal tiles).
- The code is organized in a single class `Game2048` for clarity and simplicity.

---

ENJOYY :)))))))))
