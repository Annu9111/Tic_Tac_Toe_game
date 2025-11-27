# Tic_Tac_Toe_game



A simple, single‑file Tic‑Tac‑Toe game built with Python's tkinter GUI toolkit. Clean, minimal interface ideal for beginners learning GUI programming and basic game logic.

Demo




Play a local 2‑player game (no AI). Players alternate between X and O.

Features

3×3 Tic‑Tac‑Toe board made of tk.Button widgets.

Win detection for rows, columns and diagonals.

Tie detection (draw).

Winning combination highlighted when a player wins.

Simple status label showing which player's turn it is.

Files

tic_tac_toe.py — main script containing the full implementation (single file).

Put the code into tic_tac_toe.py (or any filename you prefer) and run with Python 3.

Requirements

Python 3.6+ (comes bundled with tkinter on most platforms)

No external dependencies

Installation

Make sure Python 3 is installed.

Save the script file (e.g. tic_tac_toe.py).

Usage

Run the game from the terminal:

python tic_tac_toe.py

The window will open with a 3×3 grid. Click an empty cell to place the current player's mark. The game ends when either a player wins or the board fills with a tie.

How it works (brief)

The GUI is built using tkinter.

Buttons are created in a list of 9 and placed in a 3×3 grid.

Each button click updates the text to the current player's symbol (X or O) and triggers win/tie checks.

When a win is detected, the three winning buttons are highlighted and a pop‑up informs the user of the winner.

Possible improvements

Add a Reset / Play Again button to restart without closing the window.

Add a single‑player mode with a basic AI (minimax or heuristic).

Maintain score between rounds.

Improve visuals (icons, animations, responsive layout).

Contributing

Contributions welcome! If you want to add features (AI, improved UI, tests), open an issue or submit a pull request.

License

This project is free to use — add your preferred license (e.g., MIT) if you plan to publish it.

Contact

If you use this project on your GitHub profile and want feedback or a code review, drop a link in the issues or ping me in the repo README.
