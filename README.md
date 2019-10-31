# AI-Project---Maze-Solver
# Introduction:
Maze-Solver attempts on solving the mazes using various algorithms like DFS, BFS, A* algorithm and one of the genetic or hill climbing algorithm. This is a prototype of the actual project, wherein we have employed DFS and BFS algorithms to solve mazes.

# Input:
Input format: .png
1. Each maze is black and white. White represents paths, black represents walls.
2. All mazes are surrounded entirely by black walls.
3. One white square exists on the top row of the image, and is the start of the maze.
4. One white square exists on the bottom row of the image, and is the end of the maze.

# Code Description:
1. utils.py : A simple solver_maze class that imports and returns a relevant solver when provided a string. Not hugely necessary, but reduces the code in solver_main.py, making it easier to read.
2. solver_main.py: takes input file and method to solve and returns the output file containing the path to solve.
3. mazes.py: Contains Maze class which reads from the input image and stores the information in form of nodes.
4. depthfirst.py : solves the maze using DFS algorithm and stores the path
5. breadthfirst.py :solves the maze using BFS algorithm and stores the path

# How to run?
In the solver_main.py file enter the input file path and method you wish to employ and run solver_main.py
