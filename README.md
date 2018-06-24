# Pacman agent

All credit should go to UC Berkeley in their intro to AI for making the core of the code.

This code is my implementation of the few algorithms to solve the different problems:
* Breadth First Search
* Depth First Search
* A* with a few different heuristics
* Random search

The algorithms are implemented in the search.py.

Some agents have also different strategies and this is available in searchAgents.py.

Multiple Mazes are available.

To run the program, clone it and run pacman.py. Here are a few examples of use:

python pacman.py --layout testMaze --pacman GoWestAgent  
python pacman.py --layout tinyMaze --pacman GoWestAgent  
python pacman.py -h  
python pacman.py -l tinyMaze -p SearchAgent -a fn=tinyMazeSearch  
python pacman.py -l tinyMaze -p SearchAgent  
python pacman.py -l mediumMaze -p SearchAgent  
python pacman.py -l bigMaze -z .5 -p SearchAgent  
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs  
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5  
python eightpuzzle.py  
python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs  
python pacman.py -l mediumDottedMaze -p StayEastSearchAgent  
python pacman.py -l mediumScaryMaze -p StayWestSearchAgent  
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic   
python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem  
python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs,prob=CornersProblem  
python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5  
python pacman.py -l testSearch -p AStarFoodSearchAgent  
python pacman.py -l trickySearch -p AStarFoodSearchAgent  
python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5  
python pacman.py -l bigSearch -p ApproximateSearchAgent -z .5 -q  
