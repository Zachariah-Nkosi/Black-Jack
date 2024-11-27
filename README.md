
# Blackjack Game Practice

This project is a simple **Blackjack** game built with HTML, CSS, and JavaScript. It demonstrates basic concepts of JavaScript such as functions, arrays, conditionals, loops, DOM manipulation, and event handling.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [How to Run the Project](#how-to-run-the-project)
- [Gameplay Instructions](#gameplay-instructions)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Future Improvements](#future-improvements)

---

## Project Overview

The Blackjack game simulates a simple card game where a player draws cards with the goal of reaching a sum of 21 (Blackjack) or getting as close as possible without exceeding it. The project is designed as a practice to build proficiency in JavaScript programming, focusing on:

- Variables and data structures (objects and arrays)
- Functions and conditional statements
- DOM manipulation
- Event handling

---

## Features

- **Player Object:** Tracks the player's name and chips.
- **Random Card Generation:** Cards are randomly generated between 1 and 13.
- **Game Logic:** 
  - Player draws two initial cards.
  - Player can draw additional cards if the total sum is less than 21.
  - Displays appropriate messages based on the game state:
    - **Below 21:** Option to draw another card.
    - **21 (Blackjack):** Game declares a win.
    - **Above 21:** Game declares a loss.

---

## How to Run the Project

1. **Clone or Download** the project files.
2. Ensure you have a modern web browser installed (e.g., Chrome, Firefox, or Edge).
3. Open the `index.html` file in your browser.

---

## Gameplay Instructions

1. Open the game in a browser.
2. Click **START GAME** to draw two random cards.
3. Check the total sum of the cards:
   - If the sum is below 21, click **NEW CARD** to draw another card.
   - If the sum is 21, you win!
   - If the sum exceeds 21, you lose.
4. Keep track of your progress and chips.

---

## Technologies Used

- **HTML5:** Structure of the game interface.
- **CSS:** Basic styling for the game (using Normalize.css for consistent cross-browser styling).
- **JavaScript:** Game logic and interaction with the user interface.

---

## Folder Structure

```
/ (Project Root)
│
├── index.html         # Main HTML file for the Blackjack game
├── index.js           # JavaScript file containing the game logic
├── index.css          # Optional CSS file for custom styling
```

---

## Future Improvements

- **Add Dealer Logic:** Implement a dealer that competes with the player.
- **Add Betting System:** Allow players to bet chips and win/lose based on outcomes.
- **Improve UI/UX:** Add visual cards, animations, and better styling.
- **Implement Scoring:** Track the player's wins and losses over multiple rounds.
- **Mobile Compatibility:** Enhance the layout for mobile devices.

---

### Author
**Zachariah**  
This project is a practice to demonstrate a foundational understanding of JavaScript for web development.


Quick start:

```
$ npm install
$ npm start
````


