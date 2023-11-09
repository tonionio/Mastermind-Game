# Mastermind Game

## Introduction
This project is a Python implementation of the classic board game Mastermind. The player's goal is to guess the correct color sequence within a limited number of tries.

## Game Rules
- The game randomly generates a secret code consisting of a sequence of 4 colors.
- The colors can be Red (R), Green (G), Blue (B), Yellow (Y), Orange (O), or Purple (P).
- The player has 10 attempts to guess the color sequence.
- After each guess, the game provides feedback:
  - Number of colors that are both correct and in the correct position.
  - Number of colors that are correct but in the wrong position.

## Requirements
- Python 3.x

## How to Play
1. Clone this repository to your local machine.
2. Run the game using Python:
   ```bash
   python game.py
