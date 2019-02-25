# Game-Of-Life
Simulation of Conway's Game Of Life

This is a simulation built using reactjs framework(using create-react-app). The simulation is based on rules provided bu John Conway in his zero player game Game Of Life where the previous stage of game is dependent upon the next stage. The rules of the game is 

    Any live cell with fewer than two live neighbors dies, as if by underpopulation.
    Any live cell with two or three live neighbors lives on to the next generation.
    Any live cell with more than three live neighbors dies, as if by overpopulation.
    Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

To read more on this you can visit - https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

The application contains play, pause and clear button to perform intented actions. The Grid Size button lets user change grid size. The Fast and Slow button put speed either to 1000 or 100. The Seed button provides the inital live cell and each cell has 25% chance to be a live cell. The generation counter counts the number of generations passed.

You can use the app at - https://game-of-life-rapp.herokuapp.com/

# Screenshots

![image](https://user-images.githubusercontent.com/16362957/53360825-991b7a00-395c-11e9-88bd-346dc6bb4415.png)

# Dependencies
Node JS,
NPM,
React JS,
create-react-app takes care of other dependencies.

# Credits
Youtube Video that helped me make this - https://www.youtube.com/watch?v=PM0_Er3SvFQ&t
