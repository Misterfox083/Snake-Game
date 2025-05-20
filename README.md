#!/bin/bash
cd "$(dirname "$0")"
open dist/snake.app
# 🐍 Snake Game

A classic Snake game built with Python and Tkinter.

![Snake Game](https://raw.githubusercontent.com/Misterfox083/Snake/main/screenshot.png)

## 🎮 Quick Start

### For Mac Users:
1. Download the game files
2. Double-click `start_game.command`
3. If you get a security warning, go to System Preferences > Security & Privacy and click "Open Anyway"

### For Windows Users:
1. Download the game files
2. Run `snake.exe` from the `dist` folder

### For Linux Users:
1. Download the game files
2. Make the game executable: `chmod +x dist/snake`
3. Run the game: `./dist/snake`

## 🎯 How to Play
- Use ⬆️ ⬇️ ⬅️ ➡️ arrow keys to control the snake
- Eat the 🍎 red food to grow and increase your score
- Avoid hitting the walls or your own body
- Press spacebar or click the restart button when game over

## 🛠️ For Developers

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

## 📝 Features
- Classic snake gameplay
- Score tracking
- Game over screen with restart option
- Spacebar to restart
- Arrow key controls

## 🤝 Contributing
Feel free to fork this repository and submit pull requests!

## 📄 License
MIT License
