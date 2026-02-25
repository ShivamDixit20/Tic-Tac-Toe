# Tic-Tac-Toe

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## 🎮 Project Description

A classic Tic-Tac-Toe game built with vanilla HTML, CSS, and JavaScript. This interactive web application lets two players compete in the timeless game of X's and O's with a clean, modern interface. The game features real-time winner detection, draw detection, and the ability to reset or start a new game at any time.

## 🌐 Live Services

| Layer | Platform | Link |
|-------|----------|------|
| Frontend | GitHub Pages | [Play Now](https://shivamdixit20.github.io/Tic-Tac-Toe/) |

## 📁 Repository Structure

```
Tic-Tac-Toe/
├── index.html          # Main HTML file with game board structure
├── style.css           # Styling for the game interface
├── game.js             # Game logic and event handling
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## 🛠️ Tech Stack

**Languages:**
- HTML5
- CSS3
- JavaScript (Vanilla)

**Tools & Platforms:**
- GitHub Pages (Hosting)

## 🏗️ High-Level Architecture

The application follows a simple client-side architecture:

1. **HTML Structure** (`index.html`) - Defines the game board with 9 clickable boxes and control buttons
2. **Styling** (`style.css`) - Provides responsive design with flexbox layout and visual feedback
3. **Game Logic** (`game.js`) - Handles:
   - Turn management (Player X vs Player O)
   - User interactions (click events on game boxes)
   - Win condition checking against predefined patterns
   - Draw detection when all 9 boxes are filled
   - Game reset and initialization

## ✨ Features

- **Two-Player Gameplay** - Alternate turns between Player X and Player O
- **Win Detection** - Automatically detects winning combinations across 8 possible patterns
- **Draw Detection** - Identifies when the board is full with no winner
- **Reset Button** - Quickly reset the current game
- **New Game Button** - Start a fresh game from the winner/draw screen
- **Responsive Design** - Works seamlessly on different screen sizes
- **Visual Feedback** - Clear display of game status and winner announcement
- **Box Disabling** - Prevents overwriting of already-played boxes

## 📋 Game Rules

1. Players take turns marking boxes with X or O
2. The first player to get 3 marks in a row (horizontal, vertical, or diagonal) wins
3. If all 9 boxes are filled with no winner, the game is a draw
4. Use the Reset button to clear and start a new game anytime
5. Use the New Game button to start again after a game concludes

## 🚀 Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ShivamDixit20/Tic-Tac-Toe.git
   cd Tic-Tac-Toe
   ```

2. **Open the game:**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # Then navigate to http://localhost:8000
     ```

## 🎯 Usage Guide

1. **Starting the Game:**
   - Open `index.html` in your browser
   - Player O makes the first move

2. **Playing:**
   - Click any empty box to place your mark
   - Players alternate between O and X
   - Watch for the winner announcement or draw message

3. **Controls:**
   - **Reset Button** - Clears the board and starts a fresh game
   - **New Game Button** - Appears after game ends, starts a new round

## 🗺️ Roadmap

### Upcoming Features
- [ ] Player name customization
- [ ] Score tracking across multiple rounds
- [ ] Single player mode with AI opponent
- [ ] Game difficulty levels
- [ ] Sound effects and animations
- [ ] Move history/undo functionality
- [ ] Mobile app version

### Known Issues
- None currently reported

## 👨‍💻 Author

**Shivam Dixit**
- GitHub: [@ShivamDixit20](https://github.com/ShivamDixit20)
- Project: [Tic-Tac-Toe Repository](https://github.com/ShivamDixit20/Tic-Tac-Toe)




Enjoy playing Tic-Tac-Toe! 🎮
