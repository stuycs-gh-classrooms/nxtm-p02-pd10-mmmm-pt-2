[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jiVqpuMN)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22153734)
# NeXtCS Final Project
### Name 0: Nabila Rahman
### Name 1: Marcus Markova
---

### Project Description
Provide a high-level description of your project. Include explanatory links if you think they will be helpful.

Our project is the game Tetris. The player controls falling blocks, rotating them to complete horizontal lines across the grid and gain points. The game speeds up as time passes, increasing difficulty. The game reaches a lose state when the blocks are stacked to the top. 
This will use a grid game board and collision detection.

### Skill Usage
Explain what skills from this semester you will be using in this project, and how they will be used.

Basic drawing functions: used to render the grid and blocks, and other UI elements like borders and score. 
Controlling Color State & Using Colors: fill() and stroke() used to differentiate tetris blocks by color. 
Primitive Variables & Types: int vals for grid dimension, score, positions
Working with Boolean Values: collision detection, game over
setup() and draw(): setup will initialize grid, colors, first tetris piece. draw will update the falling and read player input.
Controlling Program Speed: will use frame count to increase speed
Custom Functions: will need to create custom functions within the driver file, like drawBoard() or spawnPiece()
Writing Readable Code & Debugging Practices: will utilize white space, comments, and break large tasks into functions.
Conditional Statements: conditionals will be used for various things, like collisions and game over
Loops: will loop to iterate through the grid to find rows. both for and while
Handling Events: will respond to keyPressed() and mousePressed()
Using Objects & Writing Classes: we will need classes for tetris pieces and the board. we will include fields/methods, use constructors, and reference objects.
Using Arrays & 2D Arrays: grid will be 2d array, tetris shapes will be 1D or 2D depending on shape
Searching: scanning the grid for completed lines
Utilizing Randomness: next tetris piece will be decided using random selection


### Controls
How will your program be controlled? List all keyboard commands and mouse interactions.

Keyboard Commands:
- left arrow: Move piece left
- right arrow: Move piece right
- down arrow: Soft drop (fall faster)
- up Arrow: Rotate clockwise
- spacebar: Hard drop (places piece instantky)
- p: Pause or resume game
- r: Reset game

Mouse Control:
- Mouse movement: not used
- Mouse pressed: maybe used on title screen


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.

tetris block class:
- instance vars: array[][] shape, int pos, int color, int rotationstate, int type
- methods: display, move, rotate

board:
- instance vars: rows, cols, grid[][], int score, int level, boolean game over
- methods: display, clearline, placepiece


  
