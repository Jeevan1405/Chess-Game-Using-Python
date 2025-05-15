# ♟️ Chess Game in Python

A simple Chess game built using Python and the Pygame library. This project was created for learning purposes and demonstrates how to build a two-player chess game with graphical board rendering, move logic, and basic rule enforcement.

## 📸 Screenshot

![Chess Game Screenshot](screenshot.png)

## 📖 Features

- Classic 8x8 chess board
- All standard chess pieces and moves
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
cd Chess-Game-Using-Python
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
Chess-Game-Using-Python/
├── assets/
│   └── images/
│       ├── wP.png
│       ├── bP.png
│       └── ... (other piece images)
├── main.py
├── chessEngine.py
├── README.md
└── requirements.txt
```

## 📚 How It Works

- `chessEngine.py` handles the game state, including the board, move logic, and validations.
- `main.py` uses Pygame to display the board and pieces, capture user input, and update the display based on moves.

## ✨ Future Improvements

- AI opponent using Minimax algorithm
- Full check/checkmate/stalemate detection
- Move history display
- Castling, pawn promotion, and en passant moves
- Save and load games

## 🙌 Credits

- Piece images sourced from [Chess.com assets] or public domain icons.
- Developed by Jeevan.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
