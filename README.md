# Tic Tac Toe Game


---

## Overview
This project is a classic Tic Tac Toe game built with **HTML**, **CSS**, and **JavaScript**. It is designed for two players who take turns marking the game board with `O` and `X`. The game automatically checks for winning combinations and declares a winner or a draw. It also features reset functionality and a responsive design suitable for both desktop and mobile devices.

---

## Features
- **Two-Player Mode:** Players alternate turns placing `O` and `X`.
- **Win & Draw Detection:** The game checks for a winner (three in a row horizontally, vertically, or diagonally) after every move. If all cells are filled without a winner, the game declares a draw.
- **Reset & New Game:** Buttons allow users to reset the board or start a new game.
- **Responsive Design:** The layout adjusts for various screen sizes, ensuring an optimal experience on desktops, tablets, and smartphones.

---

## File Structure


- **index.html:**  
  Contains the HTML markup for the game board (9 clickable boxes), control buttons (Reset/New Game), and the footer with copyright.

- **style.css:**  
  Provides styling for the game, including responsive layout, colors, button styles, and spacing. It ensures the game looks appealing and works well on different devices.

- **app.js:**  
  Implements the game logic:
  - Manages player turns with a boolean flag.
  - Tracks moves and checks winning patterns.
  - Displays win/draw messages.
  - Resets the board for a new game.

---

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Tic-Tac-Toe.git

cd Tic-Tac-Toe
How to Run
Directly Open the File:
Double-click the index.html file to open it in your default web browser.
Using a Local Server (Recommended for testing):
If you have Python installed, run:
bash
Copy
Edit
python -m http.server
This command starts a local server (by default on port 8000).
Open your browser and navigate to: http://localhost:8000
Game Logic Details
Turn Management:
A JavaScript boolean variable toggles between two players. When a box is clicked, it assigns either an O or an X based on the current turn.

Win Patterns:
An array defines all possible winning combinations (e.g., [0, 1, 2], [0, 4, 8], etc.). After each move, the game iterates through these combinations to check if one has been achieved.

Move Counting:
A counter tracks the number of moves. If the counter reaches 9 and no winning combination is found, the game ends in a draw.

Reset Functionality:
The Reset/New Game buttons trigger a function that clears the board, resets the move counter, and re-enables all game cells.

Future Enhancements
Single-Player Mode:
Add an AI opponent to allow solo play.
Score Tracking:
Implement a scoring system to keep track of wins, losses, and draws over multiple rounds.
Animations & Effects:
Enhance the UI with animations (e.g., highlighting the winning line).
Sound Effects:
Add audio feedback for moves, wins, and draws to improve user experience.
Improved Mobile Experience:
Further optimize touch interactions and layout for mobile devices.



