# Tetris-using-python-Pygame-
This is one of the first projects I’ve built, and I’m excited to finally share it here!

This project is a Tetris game developed using Python and Pygame. While the code is not entirely written from scratch (I’ve learned and adapted parts from online resources), the main goal of this project was to understand how a complete game works — from user input to collision handling and scoring.

🧱 Game Overview

The game is built on a 10×20 grid, which represents the Tetris board.

Different Tetris block shapes are defined and randomly generated at the top of the grid.

Blocks fall downward automatically, and the falling speed increases as the player’s score increases.

The player can use the keyboard to move and rotate blocks.

⚙️ Core Mechanics

Collision Detection:
A trigger system detects when a falling block collides with another block or the bottom of the grid. Once a collision is detected, the block is fixed in place.

Row Clearing:
When a row is completely filled, it is removed and all rows above it shift downward.

Scoring System:
The score increases each time a row is cleared, and higher scores result in faster gameplay.

Game Over Condition:
The game ends when a new block cannot be placed because it collides with blocks at the top of the grid. A Game Over message is then displayed.

📌 Purpose

This project helped me understand:

Game loops and event handling in Pygame

Grid-based logic and collision detection

Managing increasing difficulty and scoring systems

Overall, this was a great learning experience and a fun way to apply Python concepts in a real project.
