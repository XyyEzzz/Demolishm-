# Demolishm! #

A browser-based puzzle game inspired by block-placement mechanics, developed using vanilla HTML, CSS, and JavaScript.

# Features
- 8×8 interactive game board
- Drag-and-drop block placement system
- Dynamic scoring and combo mechanics
- Persistent high score and max combo tracking using LocalStorage
- Smart "Anti-Stall" piece generator that analyzes the board and increases the chance of producing helpful pieces
- Responsive UI optimized for both desktop and mobile devices
- Animated menus, visual effects, and procedural sound effects generated with the Web Audio API
- Game-over detection and restart system

# Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)
- Web Audio API
- LocalStorage

# Highlights
Implemented a lightweight board-analysis algorithm that detects nearly completed rows or columns and generates supporting pieces, reducing unwinnable states while preserving gameplay challenge.
