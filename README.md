Grid Path Finder

Overview

This project is a **Grid Path Finder** that generates a random grid and finds a path between a randomly chosen source and goal using the **Depth-First Search (DFS)** algorithm. The grid consists of cells that can either be blocked (represented by `1`) or open (represented by `0`). The DFS algorithm explores the grid from the source to the goal, while avoiding obstacles and tracking the order of visited nodes.

Features

Grid Generation: You can choose a grid size between 4 and 7, and you can decide whether you want a guaranteed path between the source and goal.
- **DFS Pathfinding**: The algorithm uses Depth-First Search (DFS) to find a path from the source to the goal, if one exists.
- **Visualization**: The grid is displayed with the source (`S`), goal (`G`), path (`.`), and obstacles (`1`).
- **Randomized Elements**: The source, goal, and obstacles are placed randomly within the grid.

## How It Works

1. **Grid Generation**: 
   - The grid is generated based on the user's input size.
   - If the user chooses a guaranteed path, the algorithm ensures that there will be a valid path from the source to the goal.

2. **DFS Algorithm**:
   - The algorithm starts at the source and explores neighboring cells recursively until the goal is reached or all possibilities are exhausted.
   - The cells are visited in a topological order, which is also recorded and displayed.

3. **Grid Visualization**: 
   - The grid is printed to the console, showing the source, goal, path, and obstacles.

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.
- Basic knowledge of Python programming and algorithms.


### Usage

1. Run the script and input a grid size between 4 and 7.
2. Choose whether you want a guaranteed path between the source and goal.
3. The script will generate a random grid and attempt to find a path from the source to the goal using DFS.
4. The grid, source, goal, and path will be printed in the console.

