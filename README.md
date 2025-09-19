# Sudoku Challenge

A web-based Sudoku game with difficulty selection, hints, timer, and confetti celebration on win.

## Features

- Three difficulty levels: Easy, Medium, Hard
- Lives system (3 lives per game)
- Timer display
- Hint button (3 hints per game)
- Show solution button
- Confetti animation on win
- Dark/Light theme toggle
- Responsive grid and UI

## How to Run

1. Clone or download this repository.
2. Open `index.html` in your web browser.

No build step or server required.

## File Structure

- [`index.html`](index.html): Main HTML file, contains UI and theme logic.
- [`style.css`](style.css): Styles for the game, grid, buttons, popups, and themes.
- [`sudoku.js`](sudoku.js): All game logic, including puzzle generation, input handling, timer, hints, and popups.

## How to Play

1. Select a difficulty and click **Start Game**.
2. Fill in the Sudoku grid. Pre-filled cells are read-only.
3. You have 3 lives. Incorrect entries reduce lives.
4. Use the **Hint** button for help (up to 3 times).
5. Click **Show Solution** to reveal the answer.
6. Win the game by filling all cells correctly!

