# Assembly-game

## Overview
- Assembly Endgame is a word-guessing game inspired by the classic game Hangman. Developed as part of Scrimba's course project, the goal is to guess the hidden word within a limited number of attempts while avoiding incorrect guesses. Each incorrect guess "eliminates" a programming language, and the game is over when all languages are lost.
  
---
## How to Play
1. A random programming-related word is selected (e.g., react).
2. You start with all programming languages "active."
3. Guess the word one letter at a time by clicking the displayed keyboard buttons.
4. Correct Guesses: Revealed in the hidden word.
5. Incorrect Guesses: A programming language is eliminated.
6. Lose the game if you make too many incorrect guesses.
7. Win the game by correctly guessing all letters in the word.

---


## Technologies Used
- React: For building the interactive UI.
- JavaScript: For game logic and dynamic rendering.
- CSS: For styling and animations.

---

## Installation
1. **Clone the repository:**

   ```bash
   git clone https://github.com/UlinduRasantha/Assembly-game.git
   cd Assembly-game

2.  **Install dependencies:**
    ```bash
    npm install

3. **Start the development server:**
     ```bash
    npm run dev
---
##  **Project Structure**

    ASSEMBLY--ENDGAME/
    ├── src/
    │   ├── assets/
    │   ├── App.jsx
    │   ├── index.css
    │   ├── index.jsx
    │   ├── languages.js
    │   ├── utils.js
    │   └── words.js
    ├── index.html
  

---

## Credits
This project was developed as part of <a href="https://scrimba.com/learn-react-c0e" target="_blank">Scrimba's Learn React </a>. A big thanks to the instructors and Scrimba community for their support.

