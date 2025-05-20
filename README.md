# Snake Game

A classic Snake game built with Python and Tkinter.

## Features
- Classic snake gameplay
- Score tracking
- Game over screen with restart option
- Spacebar to restart
- Arrow key controls

## For Regular Users (No Python Required)
1. Download the latest release from the [Releases](https://github.com/Misterfox083/Snake/releases) page
2. For Windows: Download and run `snake_game.exe`
3. For Mac: Download and run `snake_game.app`
4. For Linux: Download and run `snake_game`

## For Developers
### Requirements
- Python 3.x
- Tkinter (usually comes with Python)

### Installation
```bash
# Clone the repository
git clone https://github.com/Misterfox083/Snake.git

# Navigate to the project directory
cd Snake

# Install requirements
pip install -r requirements.txt

# Run the game
python snake.py
```

### Building the Executable
```bash
# Install PyInstaller
pip install -r requirements.txt

# Create executable
pyinstaller --onefile --windowed snake.py
```

## How to Play
1. Use arrow keys to control the snake
2. Eat the red food to grow and increase your score
3. Avoid hitting the walls or your own body
4. Press spacebar or click the restart button when game over

## License
MIT License
