This one of the projects I did during my undergraduate studies, in 2014.

Project description: Enunciado.pdf (in Spanish)
(Brief summary in English below.)

In this project, you have to allow the Pacman agent to find the way through the maze to reach a particular position or collect food efficiently. The goal is to build general search algorithms and apply them to the given Pacman scenarios.
The code will consist of several Python files, some of which will need to be read and understood in order to accomplish the goal.

- search.py: Search algorithms. They must be written here.
- searchAgents.py: Agent information should be here.

- pacman.py: The main file that runs the Pacman game. This file describes a state of type GameState, which must be used in this project.
- game.py: The logic behind how Pacman works. Several types are described that are used to model behavior and graphics such as AgentState, Agent, Direction, and Grid.
- util.py: Useful data structures to implement search algorithms.

- graphicsDisplay.py: Graphics for Pacman
- graphicsUtils.py: Graphics utilities
- textDisplay.py: ASCII graphics for Pacman
- ghostAgents.py: Agents to control ghosts
- keyboardAgents.py: Keyboard interface to control Pacman
- layout.py: Code to read files and store their content.

Some useful commands:
python pacman.py
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
