# AI-Project---Maze-Solver
# Introduction:

Pathfinding in computer games has become an investigated area for many years. It is just about the most popular but very difficult game Artificial Intelligence (AI) problem in game industry. The problem of pathfinding in commercial computer games has to be
solved in real-time, usually under demands of limited memory and CPU resources .Hence we have developed a MAZE SOLVER which solves a given maze using various blind search, informed search and local search algorithms and intend to do a comparative study of the algorithms.

# Input:
1. Input Sources:
The mazes have been created using Daedalus. software. It allows one to create mazes of many types.
The maze format is:
	

2. Input Format:
	The input taken is an image in .png format.
	The image is taken as input and loaded using PIL (Python Imaging Library)	

3. Input Processing:
	1. The image once loaded is processed using Image.getdata() function.
	2. It returns the contents of this image as a sequence object containing pixel values.
	3. The sequence object is flattened, so that values for line one follow directly after the values of line zero, and so on.
	4. The sequence object returned by this method is an internal PIL data type, which only supports certain sequence operations.
	5. To convert it to an ordinary sequence (e.g. for printing),  list(im.getdata()) is used.


# Code Description:
1. utils.py : A simple solver_maze class that imports and returns a relevant solver when provided a string. Not hugely necessary, but reduces the code in solver_main.py, making it easier to read.
2. solver_main.py: takes input file and method to solve and returns the output file containing the path to solve.
3. mazes.py: Contains Maze class which reads from the input image and stores the information in form of nodes.
4. depthfirst.py : solves the maze using DFS algorithm and stores the path
5. breadthfirst.py :solves the maze using BFS algorithm and stores the path
6. AstarandGA.ipynb : solves the maze using A* and Genetic algorithms.

# How to run?
In the solver_main.py file enter the input file path and method you wish to employ and run solver_main.py
