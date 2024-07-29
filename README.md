# A* & Dijkstra-based Path Planners

This repository contains MATLAB implementations of path planning algorithms based on Dijkstra's algorithm and A* algorithm for grid-based environments.

### Dijkstra's Algorithm
Dijkstra's algorithm finds the shortest path between nodes in a weighted graph by iteratively selecting the node with the smallest known distance, updating its neighbors' distances, and marking it as visited. It ensures the shortest path in graphs with non-negative
    weights.

### A* Algorithm
The A* algorithm enhances Dijkstra's by using heuristics to prioritize paths. It combines the actual cost to a node with an estimated cost to the goal, speeding up the search for the shortest path, especially in large graphs or grids.

## Contents

- **AStarGrid.m**: Implementation of the A* algorithm for grid-based pathfinding.
- **DijkstraGrid.m**: Implementation of Dijkstra's algorithm for grid-based pathfinding.
- **run.m**: Script to run and test the path planning algorithms.

## Features

- Path planning in grid-based environments
- Visualization of the pathfinding process
- Customizable start and goal positions

## Usage

- Run the script:
    ```sh
    run.m
    ```
