# A* PATHFINDING VISUALIZER

A* Pathfinding Visualizer is a python visualization of the A* pathfinding algorithm using Pygame and TKinter, which
allows users to pick a start and end location and view the process of finding the shortest path.

The A-star algorithm is employed here to determine the  shortest path between two nodes in a 2-D grid, with the option of placing the obstacles given to the user. Based on A-star's heuristic  function, different  paths  are traversed and the final path is determined using backtracking. 

The project thus helps in visually interpreting how  the A-Star algorithm functions.

## Requirements
1. The only requirement is to install Pygame,which can be done by either of the  following two commands

    pip install pygame

    python -m pip install pygame

After installing Pygame, simply run the command: python astar.py

## Steps to Run the Project

Initially, on a 2-D Grid you can choose two different position, starting and ending position, by right clicking on the 2-D grid. The starting position is marked by yellow and ending position is marked by a blue node.

Once it has been done, you can now start placing obstacles interactively by right clicking on the cells you want to. The obstacles are represented by black colour.

Once you're done with placing obstacles, press the Space Bar on your Keyboard to let the project function and determine paths heurestically from starting to ending node. The visualisation of the whole process can be seen using a red stream that flows from the starting node that tries to reach the ending node. The functioning A-Star algorithm is visualised through this manner.

Once the final node is reached, a stream of purple colour backtracks to find the optimal path free of obstacles from starting to ending node.

## Starting position, Ending Position And Obstacle Positioning Example

![pic1](https://user-images.githubusercontent.com/45738332/89524243-d9458400-d801-11ea-805d-52075f81cb45.JPG)

## A* Algorithm Pathfinding Visualization using red stream

![pic2](https://user-images.githubusercontent.com/45738332/89524441-36d9d080-d802-11ea-81dd-1ef50fb2dd95.JPG)

## Shortest Path highlighted with red stream

![pic3](https://user-images.githubusercontent.com/45738332/89524568-6c7eb980-d802-11ea-9c00-200c3975b414.JPG)
