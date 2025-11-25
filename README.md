# Tic Tac Toe Game

A classic game of Tic Tac Toe implemented in Pygame with a clean graphical interface, where two players can play smoothly.

Features

- **Graphical Interface:** Attractive teal-themed board; smooth graphics
- **Two-Player Gameplay**: Play with your friend on the same computer
- **Visual Feedback**: distinct X and O signs colored differently
- **Win Detection**: Automatically detects wins and tie games
- **Game Reset**: Quick restart with a single key press

- **User-Friendly**: Straightforward click-to-play interface

Requirements

- Python 3.x

- Pygame library
Installation

1. **Install Python** (if not already installed):
- Download from [python.org](https://www.python.org/downloads/)
- Check the box saying "Add Python to PATH" while installing

2. **Install Pygame**:

```bash
pip install pygame
```
## How to Run
1. Save the code to a file; for example, `tictactoe.py`
2. Open your terminal/command prompt

3. Go into that directory where the file is.

4. Execute the program:
```bash
python tictactoe.py
```
How to Play

Basic Rules
- The game is played on a 3x3 grid.
- Player X makes the first move, followed by Player O

- Players take turns clicking on empty squares
- First player to get 3 in a row wins (horizontally, vertically, or diagonally)
- If all squares are filled with no winner, it is a tie
Controls
- **Mouse Click**: Click any empty square to set your mark (X or O)
- **R Key**: Press 'R' to restart the game after it ends.

- **Close Window**: Click the X button to exit the game

Flus de jogo
1. Game starts by opening an empty 3x3 grid.
2. Player X clicks a square to make the first move
3. Player O clicks a square to make their move
4. Players continue to take turns until someone wins or the board is full.

5. When the game is over, a message shows who the winner is, or announces a tie
6. Hit 'R' to play again
Elements of Gameplay
Visual Design

- **Background**: Teal color for a modern look

- **Grid Lines**: Darker teal lines dividing the board
- **X Symbol**: Dark gray crossing lines
- **O Symbol**: Light beige circle
- **Game Over Screen**: Semi-transparent overlay with winner announcement
Win Conditions
The game verifies victories in:
- All 3 horizontal rows

- All 3 vertical columns
- 2 diagonal lines, top-left to bottom-right and top-right to bottom-left
Code Organization
Componentes principales
- **Board**: 3x3 list storing game state ('X', 'O', or empty)

- **draw_grid()**: Draws the game board lines

- **draw_symbols()**: Draws X and O symbols on the board

- **check_winner()**: Checks for all win conditions
- **check_tie()**: Checks if the game is tied
- **show_game_over()**: Displays end game message
- **reset_game()**: Clears the board for a new game
Game Loop
The main loop continuously:

1. Checks for user input (clicks and key presses)
2. Updating the game state
3. Redraws the display
4. Checks for win/tie conditions

## Customization

You can easily modify the game by changing these values:

Colors - RGB format
```python

background_color = (28, 170, 156)   # Board background
line_color = (23, 145, 135)         # Grid lines

x_color = (66, 66, 66)              # X symbol color
o_color = (239, 231, 200)           # O symbol color

怡 :
 Five years later, when her sister's husband was stricken with schizophrenia and confined to a mental hospital, Motherless Daughter inquired whether it was possible for him to have inherited it.

Size of Window
```python
width = 600   # Window width in pixels
height = 600  # Window height in pixels
```
Thickness of Line
Change the last parameter in `pygame.draw.line()` and `pygame.draw.circle()` calls
Troubleshooting
"pygame not found" error

- Make sure Pygame is installed : `pip install pygame`

- If using Python 3, try: `pip3 install pygame`
Game window does not open
- Make sure you have Python 3.x installed
- Make sure no firewall is blocking the application
Clicks not registering
- Make sure you're clicking inside the game window
- Click in the center of squares for best results

Future Enhancements

Possible improvements for future versions:

Single-player mode with AI opponent

- Difficulty levels (Easy, Medium, Hard) - Score tracking across multiple games - Animation effects for moves and wins Sound effects for moves and wins • Custom player names - Different board sizes: 4x4, 5x5 - Online multiplayer capability Theme customization menu ## Learning Objectives This project demonstrates: - Pygame basics: window creation, event handling, drawing 2D list/ array manipulation - Game loop implementation - Handling user input - Collision detection (click to grid conversion) - Game state management - Win condition algorithms License Free to use and modify for educational purposes. Credits Created in Python using Pygame for learning and fun.
