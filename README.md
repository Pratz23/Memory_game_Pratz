# Memory Game Collection

This repository contains a small collection of browser-based childhood games built with plain HTML, CSS, and JavaScript. The project is designed to be lightweight, easy to run, and beginner-friendly.

## Included Games

### 1. Memory Game
File: `memory-game.html`

A responsive and accessible Memory (Concentration) card game with:
- 4x4 and 6x6 grid choices
- smooth card flip animations
- move counter and timer
- star rating system
- best score tracking with localStorage
- keyboard controls and responsive layout
- dark mode support

### 2. Whack-a-Mole
File: `whack-a-mole.html`

A simple arcade-style game where players hit popping moles before the timer runs out.

Features:
- 3x3 board
- score and timer tracking
- best score persistence with localStorage
- restart button
- responsive design

## Dark Theme
The Memory Game includes a dark mode toggle, and the theme preference is saved in the browser so it persists on reload.

## How to Run

Option 1:
- Open the HTML file directly in a browser.

Option 2:
- Run a local server from the project folder:

```bash
python -m http.server 8000
```

Then visit:
- `http://localhost:8000/memory-game.html`
- `http://localhost:8000/whack-a-mole.html`

## Project Structure

- `memory-game.html` – Memory card game
- `whack-a-mole.html` – Whack-a-Mole game
- `PRD_dark_theme.md` – product requirements for dark mode
- `PRD_whack_a_mole.md` – product requirements for the Whack-a-Mole game
- `context.md` – repository summary and context

## Technology Used

- HTML
- CSS
- JavaScript
- Browser localStorage for saved scores

## Notes

This project is intentionally simple and does not use frameworks or external libraries, making it easy to study, modify, and extend.