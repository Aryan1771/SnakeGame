# Snake Game

Snake Game is a classic grid-based Snake implementation built with Python and Pygame. It includes a start screen, game-over screen, score display, background music, custom font loading, and PyInstaller build files.

## Features

- Classic Snake movement and collision rules
- Random apple placement
- Score display based on snake length
- Start screen and game-over screen
- Keyboard controls with arrow keys or WASD
- Background music playback through Pygame mixer
- Grid rendering for clear movement
- Resource path helper for PyInstaller builds
- Included PyInstaller spec file

## Tech Stack

- Python
- Pygame
- PyInstaller

## Project Structure

```text
Snake Game.py            Main game source
Snake Game.spec          PyInstaller build specification
freesansbold.ttf         Font asset
music.mp3                Background music
Snake Game/              Generated build output
```

## Getting Started

Install dependencies:

```powershell
pip install pygame pyinstaller
```

Run the game:

```powershell
python "Snake Game.py"
```

## Controls

- Arrow keys or `W`, `A`, `S`, `D`: move the snake
- `Esc`: quit the game

## Build an Executable

```powershell
pyinstaller "Snake Game.spec"
```

The executable is generated in the PyInstaller output directory.

## Notes

The game expects `music.mp3` and `freesansbold.ttf` to be available next to the Python file or bundled through PyInstaller.

## License

This repository is licensed under the GPL-3.0 license. See `LICENSE` for details.
