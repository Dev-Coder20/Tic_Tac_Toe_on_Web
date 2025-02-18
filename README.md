# Tic Tac Toe - Flask Web App

This is a simple Tic Tac Toe game built using Flask for the backend and HTML, CSS, and JavaScript for the frontend. The game allows a player to compete against a computer opponent.

## Features
- Single-player mode (against the computer)
- Dynamic game board using JavaScript
- Flask backend with game logic
- AJAX requests for smooth gameplay
- Responsive UI with CSS styling
- Restart functionality

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)

## Installation

### 1. Clone the Repository
```sh
git clone https://github.com/Dev-Coder20/Tic_Tac_Toe_on_Web.git
cd Tic_Tac_Toe_on_Web
```

### 2. Set Up Virtual Environment (Optional but Recommended)
```sh
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```sh
pip install flask
```

## Running the Game
```sh
python app.py
```

Then, open your browser and go to:
```
http://127.0.0.1:5000
```

## How to Play
1. The game starts with Player X (you) against the Computer (O).
2. Click on any available cell to make a move.
3. The computer will respond with its move automatically.
4. The game ends when a player wins or if it's a draw.
5. Click the "Restart Game" button to start over.

## Project Structure
```
/tic_tac_toe
│-- /static
│   │-- style.css       # Styles for the game board
│   │-- script.js       # JavaScript for game logic
│-- /templates
│   │-- index.html      # Frontend UI
│-- app.py              # Flask backend
│-- README.md           # Project documentation
```
