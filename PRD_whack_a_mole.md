# PRD: Whack-a-Mole Game

## 1. Overview
This project adds a simple browser-based Whack-a-Mole game as a single HTML file. The game should be fast to load, easy to play, and work without any external dependencies.

The goal is to recreate the classic arcade-style gameplay in a minimal front-end project similar to the existing memory game pattern, using HTML, CSS, and JavaScript only.

---

## 2. Objective
Create a playable Whack-a-Mole game where the user clicks on random moles that appear in a grid. The game should keep score, countdown time, and high score tracking while remaining responsive and easy to understand.

---

## 3. User Story
As a player, I want to click on the appearing moles as quickly as possible so that I can earn points before the timer ends.

---

## 4. Core Features
- 3x3 grid of holes
- Random mole appearing in one hole at a time
- Score counter
- Countdown timer
- Start / restart button
- High score persistence with localStorage
- Responsive design for desktop and mobile devices
- Keyboard-accessible controls where possible

---

## 5. Functional Requirements
### 5.1 Game Layout
- The user sees a game board with nine holes.
- One hole may show a mole at a time.
- The board should update visually to show the active mole.

### 5.2 Game Logic
- The game starts when the user clicks Start.
- A random hole is selected repeatedly during gameplay.
- When the user clicks a visible mole, the score increases.
- The game ends when the countdown reaches zero.
- The final score is displayed to the user.

### 5.3 Score Tracking
- Score should increment by 1 for each successful hit.
- Time left should be displayed in seconds.
- Best score should be stored in localStorage.

### 5.4 User Experience
- The game should respond immediately to clicks.
- Clicking a mole should feel rewarding and clear.
- The active mole should be visually obvious and easy to target.

---

## 6. Non-Functional Requirements
- Works in modern browser environments
- No external libraries required
- Lightweight and easy to run by opening the HTML file directly
- Animation and interaction must remain smooth
- Layout should remain usable on smaller screens

---

## 7. Acceptance Criteria
1. The page loads and displays a playable board.
2. The user can start the game with a button.
3. A mole appears randomly in the grid during gameplay.
4. Clicking the mole increases the score.
5. The countdown timer decreases correctly.
6. The game ends when time reaches zero.
7. The best score persists in browser storage.
8. The game remains visually stable and responsive on different screen sizes.

---

## 8. Risks and Considerations
- Clicking too fast or repeatedly may cause accidental double count if the mole resets too quickly.
- The active mole timing should be tuned to feel fair and responsive.
- Visual contrast must remain strong enough for readability and accessibility.

---

## 9. Definition of Done
The feature is complete when the game loads, plays correctly, tracks score and timer, preserves the best score, and is ready to be opened and tested in a browser without any setup beyond opening the HTML file.
