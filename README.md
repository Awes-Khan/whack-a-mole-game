# Whack-a-Mole Game

Welcome to the Whack-a-Mole game! In this fun and interactive game, players try to "whack" moles that pop up from various holes in a grid. The game features an enhanced mole animation that changes its appearance drastically when clicked, adding to the overall enjoyment.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run the Game](#how-to-run-the-game)
- [Code Overview](#code-overview)
- [Key Changes](#key-changes)
- [Final Result](#final-result)
- [License](#license)

## Features

- Interactive gameplay where players whack moles to earn points.
- Timer that counts down from 30 seconds.
- Enhanced mole animation that changes its appearance when clicked.
- Scoreboard displaying current score and time left.
- Start and restart game buttons.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Run the Game

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Awes-Khan/whack-a-mole-game.git
   cd whack-a-mole-game

2. **Open the `index.html` file in a web browser:**
  - Simply double-click the `index.html` file or open it using your preferred web browser.

3. **Start Playing:**
  - Click the "Start Game" button to begin playing. Click on the moles as they appear to score points!


## Code Overview

### HTML (index.html)

The HTML structure creates the foundation for the game, which includes:

- A game container with a title, scoreboard for tracking scores and time.
- A grid layout consisting of holes where moles will appear.
- Start and restart buttons to control the game flow.

### CSS (styles.css)

The CSS styles define the visual elements of the game, including:

- General styles for the body and game container to ensure a pleasant appearance.
- Specific styles for the mole to differentiate between its normal and "whacked" states.
- Responsive styling for the scoreboard and buttons to improve user interaction.

### JavaScript (script.js)

The JavaScript file manages the game's logic:

- It randomly selects a hole for the mole to pop up and tracks the currently active hole.
- The score is incremented when a mole is clicked, and the score display is updated accordingly.
- A countdown timer tracks the remaining time, updating the display and ending the game when time runs out.
- Event listeners are set up for each hole to handle mole whacking.

## Key Changes

1. **Mole Appearance:**
   - The mole starts as a cute character and transforms into a skull-and-crossbones symbol when hit.
   - An animation effect is added to create the illusion of the mole being squished upon impact.

2. **Whack Animation:**
   - The `squish` animation alters the mole's dimensions during a whack, enhancing the game's interactivity.

## Final Result

The Whack-a-Mole game features an engaging and visually appealing mole character that responds dynamically to player interactions. The enhancements create a fun and addictive gameplay experience, making it a delightful challenge for players of all ages.

## License

This project is open-source and available under the MIT License.
