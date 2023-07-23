## Steps to run the program:

1. Place the below file in one folder.

   8Puzzle.ipynb : Program which implements the A* Search on given 8-puzzle using manhattan distance as heuristic.

2. Open the file '8Puzzle.ipynb' in Jupyter Notebook and run the program.

3. It prompts for start and goal states. Enter each row values in puzzle for every prompt and press enter(3 values with space separated).
   Sample input taken is:
   Start State:
   7 2 4
   5 0 6
   8 3 1
   Goal State:
   1 2 3
   4 5 6
   7 8 0

4. Please wait until all the steps are executed and open '8PuzzleOutput.txt' to check the output. This file contains the start state, goal state and sequence of moves to solve 8-puzzle. If there is no solution for given start and goal state, the output file contains start state, goal state and a statement "No solution found for the given puzzle". This file will get created in the same folder as the 8Puzzle.ipynb.