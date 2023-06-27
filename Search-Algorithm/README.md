# Implementation of A* Search Algorithm for 8-Puzzle
This repository contains an implementation of the A* search algorithm applied to solve the classic 8-puzzle problem. The 8-puzzle is a sliding puzzle game consisting of a 3x3 grid with eight numbered tiles and one empty space. The goal is to rearrange the tiles from a given initial configuration to a desired target configuration by sliding them one at a time into the empty space.

The A* search algorithm is utilized to efficiently find the optimal solution to the 8-puzzle problem. A* combines elements of greedy best-first search, using a heuristic function to guide the search toward the goal state while considering the actual cost of reaching each node.
![image](https://github.com/BrenJay23/Artificial-Intelligence-Foundational-Algorithms/assets/110827709/b340aafd-b52d-4b93-8630-97d40605f048)
## Features
This implementation offers the following features:

1. **Heuristic Functions:** The repository provides three heuristic functions that can be used to estimate the distance from the current state to the goal state. Examples include the Manhattan distance, the number of misplaced tiles, and more. These heuristic functions play a crucial role in the A* search algorithm, influencing the efficiency and optimality of the solution. The heuristic functions used are as follows:\
   a. Number of Tiles in the Wrong Position\
   b. Manhattan Distance\
   c. Nilsson's Sequence Score (https://stackoverflow.com/questions/10584788/can-anyone-explain-nilssons-sequence-score-in-8-puzzle-more-clearly/10607141#10607141)

3. **Search Algorithms:** The repository includes an implementation of the A* search algorithm tailored specifically for the 8-puzzle problem. It intelligently explores the state space, prioritizing promising paths and minimizing the number of moves required to reach the goal state.

4. **Visualization:** The code also includes a visualization that allows you to see the step-by-step progression of the A* search algorithm. You can observe how the tiles are moved until it finds the optimal solution.

5. **Customizability:** The implementation provides flexibility to define your own initial and target configurations for the 8-puzzle by modifying the *astar_in.txt*. You can experiment with different setups and observe how the A* search algorithm finds the optimal solution for each case.
