# Tic-Tac-Toe-Game
# Tic-Tac-Toe Game

A simple Tic-Tac-Toe game with three game modes:

1. **Human vs Human**
2. **Human vs AI**
3. **AI vs AI**

## Features

- **Human vs Human**: Two players take turns playing against each other.
- **Human vs AI**: One player competes against an AI using the Minimax algorithm.
- **AI vs AI**: AI plays against another AI using random moves (you can replace this with a more sophisticated AI strategy).

## Requirements

- Python 3.x
- Libraries:
  - `tkinter`: For the graphical user interface.
  - `random`: For random AI moves in AI vs AI mode.
  - `subprocess`: For running external commands (like `Xvfb`).

### Installation

To install the required dependencies, create a virtual environment and install the packages listed below.

```bash
# Create a virtual environment (optional but recommended)
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install the required libraries
pip install -r requirements.txt
