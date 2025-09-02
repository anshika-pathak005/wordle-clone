# Wordle 🎯

A browser-based clone of the popular word-guessing game Wordle, built using HTML, CSS, and JavaScript. This was created just for fun — I loved understanding the game’s logic while building it and enjoy playing it myself.

## Overview

The game selects a hidden 5-letter word, and the player has 6 attempts to guess it. After each guess, the tiles change color to give hints:

- Green if the letter is correct and in the right spot  
- Orange/Brown if the letter is correct but in the wrong spot  
- Gray if the letter is not in the word at all  

I referred to a YouTube tutorial for guidance on Wordle’s logic and independently implemented the code step by step.

## Features ✨

- Interactive board — Displays guesses dynamically.  
- Color-coded hints — Correct, present, and absent letters are shown clearly.  
- Win/Loss detection — Alerts when the word is guessed correctly or attempts run out.  
- Keyboard input — Enter letters using the physical keyboard.  
- Clean, minimal design — Focus on gameplay without distractions.  

## Project Structure 📂

```

├── index.html   # Basic HTML layout
├── style.css    # Styling for the board and tiles
└── index.js     # Game logic for guesses and validation

```

## Installation / Usage 🚀

1. Clone or download this repository.  
2. Open `index.html` in any modern browser.  
3. Type your guesses using your keyboard and press Enter to submit.  
4. Try to guess the hidden word within 6 attempts!

## Screen-Shots
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/578b7be7-17b5-462d-b8ef-67df0177ca08" />

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/d70ab800-117e-4de3-b7e2-648a64b8082e" />

## What I Learned 🧠

- Handling keyboard events in JavaScript.  
- Managing game state dynamically with arrays.  
- Implementing logic for checking letter positions.  
- Creating simple yet responsive layouts using flexbox.  

## Credits 🙌

- Inspiration & Logic Guide: YouTube tutorial on building Wordle.  
- Code: Fully written by me while following along with the tutorial.  
