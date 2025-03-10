# Pathfinding Using A* Algorithm

## Overview
This repository contains an implementation of the A* (A-star) algorithm for pathfinding in a grid environment. The A* algorithm is a widely-used and efficient algorithm that finds the shortest path from a starting node to a goal node by combining the strengths of Dijkstra's algorithm and Greedy Best-First-Search.

## Features
- **Heuristic Function**: Uses the Manhattan distance heuristic to estimate the cost from a node to the goal.
- **Priority Queue**: Implements a priority queue using the `heapq` module to manage nodes to be explored.
- **Path Reconstruction**: Reconstructs the path from the goal node to the start node once the goal is reached.
- **Grid Representation**: Represents the environment as a grid where 0 represents passable cells and 1 represents obstacles.

## Getting Started

### Prerequisites
- Python 3.x

### Installation
Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/pathfinding-a-star.git
cd pathfinding-a-star
