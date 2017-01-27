2d shift puzzle. 

I am teaching myself Python and used this as a means of exercising my skills.  I added about 40 lines of code.  Thanks to LarsP90 for the basic game code.

ver. 1.1
  - Changed '/' operator to '//' in game loop for compatibililty with Python 3.
  - Added check_state function to check for winning condition (i.e. puzzle solved).  This resets the puzzle to the at_start state so the next user input will shuffle a new puzzle.
  - Added arrow key functionality for moving tiles.
  - Added initial splash screen with instructions and an end-game splash screen.

The initial display shows the solved puzzle. 
The first mouse click shuffles the tiles. 
After that, a left mouse click on a tile next to the empty tile moves that tile there. 
The right mouse button shows the solved puzzle image temporarily. 

The whole game is about 132 lines. 
It is meant to be a simple example of a 2d game with mouse control using pygame. 
It is also fun to play (for a while).
