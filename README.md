# The-Maze
A simple assembly x86 maze generator game.

# Usage
    
    Download base.asm
    Download the bmps from game_images to support the GUI.
    Download DOSBox 0.74+.
    Download TASM (turbo assembler).
    Place the bpms and the game asm file in the tasm/bin folder.
    Run base.asm from DOSBox.
    
# How to play
    
  - Try to find your way through a gigantic maze!
  - Move the yellow dot from the upper-left corner to the lower-right corner using the WASD keys.
  - To quit the game before completing the maze click the return button and the correct path will appear.

# Algorithm

### Maze generation

  The maze is generated using an optimized prim algorithm, therefore it is always solvable.

### Solving 

  Solving the maze is done using dead-end filling.

### Random numbers generation

  Done using the Blum Blum Shub algorithm.

  #### Limitations

   Requires 2 different relatively big prime numbers whose multiplication is smaller than the board array size, resulting in ```861``` different generatable mazes.
  
  
  
  
## Enjoy!
