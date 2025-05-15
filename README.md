# ♟️ Chess Game in Python

A simple Chess game built using Python and the Pygame library. This project was created for learning purposes and demonstrates how to build a two-player chess game with graphical board rendering, move logic, and basic rule enforcement.

## 📸 Screenshot

(![Chess Game image](https://github.com/user-attachments/assets/aaf32295-a429-417d-acdb-a7eabb5e8db6))

## 📖 Features

- Classic 8x8 chess board
- All standard chess pieces and moves
- Castling..
- Graphical user interface using Pygame
- Move highlighting for valid moves
- Move history tracking (optional)
- End-game detection: Checkmate and Stalemate (optional/partially implemented)

## 📦 Requirements

- Python 3.x
- Pygame

## 🔧 Installation

1. Clone this repository:

```bash
git clone https://github.com/Jeevan1405/Chess-Game-Using-Python.git
cd Chess Game
```

2. Install the required Python packages:

```bash
pip install pygame
```

## ▶️ How to Run

Run the `main.py` file to start the game:

```bash
python main.py
```

The game window will open with a chessboard. Players take turns moving pieces by clicking on a piece and then clicking a destination square.

## 📁 Project Structure

```
Chess Game/
├── images/
│     ├── black king.png
│     ├── white queen.png
│     └── ... (other piece images)
├── additions.py
├── constants.py
└── main.py
```

## 📚 How It Works

- `additions.py` contain extra game logic or helper functions.
- `constants.py` stores game-related fixed values
- `main.py` uses Pygame to display the board and pieces, capture user input, and update the display based on moves.

## ✨ Future Improvements

- AI opponent using Minimax algorithm
- Full check/checkmate/stalemate detection
- Move history display
- Pawn promotion, and En passant moves
- Save and load games

## 🙌 Credits

- Piece images sourced from [Chess.com assets] or public domain icons.
- Developed by Jeevan.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
