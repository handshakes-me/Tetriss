Tetris Game
This is a simple Tetris game implemented in Python using the Pygame library.

Requirements
Python 3.x
Pygame
Installation
Clone the repository or download the source code.
Install the required dependencies using pip:
pip install -r requirements.txt

How to Play
Run the game by executing the main.py file:
python main.py

The game will start with a main menu. Press any key to begin the game.
Use the following controls to play the game:
Left Arrow: Move the piece left
Right Arrow: Move the piece right
Up Arrow: Rotate the piece
Down Arrow: Move the piece down faster
Game Description
The game grid is 10x20 squares.
There are 7 different shapes (S, Z, I, O, J, L, T) represented by different colors.
The goal is to clear as many rows as possible by completing horizontal lines without gaps.
The game ends when the pieces stack up to the top of the grid.

Code Structure
main.py: The main game file containing all the game logic and functions.
Functions
create_grid(locked_positions): Creates the game grid with locked positions.
convert_shape_format(shape): Converts the shape format to grid positions.
valid_space(shape, grid): Checks if the current shape is in a valid space.
check_lost(positions): Checks if the game is lost.
get_shape(): Returns a new random shape.
draw_text_middle(text, size, color, surface): Draws text in the middle of the screen.
draw_grid(surface, row, col): Draws the game grid.
clear_rows(grid, locked): Clears completed rows and updates the locked positions.
draw_next_shape(shape, surface): Draws the next shape on the screen.
