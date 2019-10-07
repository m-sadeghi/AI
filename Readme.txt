before running this project, pygame should be installed.
in this project we aim to implement and test search algorithms like Breadth-First, Depth-First Search, etc.
there are two .py files named pipe.py and util.py, we implement search algorithms in pipe.py and util.py
includes data structures like stack and queue and there's no need to implement them again.
input.dat includes map of the game and should be included in the folder.
this projects prints path length, number of nodes for each tree, calculates Effective Branching Factor
and execution time.
there's also a heuristic search algorithm implemented.
current algorithms are implemented:
depthFirstSearch()
breadthFirstSearch()
iterativeDeepeningSearch()
uniformCostSearch()
manhattanHeuristicFunction()
heuristicFunction()
aStarSearch()