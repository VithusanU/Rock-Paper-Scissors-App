# Rock Paper Scissors x99

## Overview

This project is a custom version of Rock Paper Scissors where each player chooses three moves with different strength values, totaling 99 points. I built this to strengthen my understanding of JavaScript fundamentals like functions, global variables, and conditionals.

The game compares moves round by round, with the player winning two or more rounds declared the winner. If both move types are the same, the strength values are compared. This helped me practice logic, game loops, and structuring code over multiple rounds.

## How it Works

Players assign:
- A move type (Rock, Paper, or Scissors)
- A strength value (minimum 1, total of 99 for all three moves)

Example:
- Rock - 30
- Rock - 60
- Paper - 9

The game compares each move using RPS rules, or strength if the type is the same. If both strength and type match, it's a tie.

## Technologies Used

- JavaScript (core logic in `js/game-logic.js`)
- HTML/CSS (simple frontend interface)

## What I Learned

- Managing game state across rounds
- Using functions and variables to control flow
- Handling edge cases like ties and invalid inputs

## Bonus Features

- Random computer moves
- Input validation
- Testing with provided test suite

## Run the Game

1. Open `index.html` in Chrome.
2. Choose moves and play!

To run tests:

```bash
npm install
npm run test
