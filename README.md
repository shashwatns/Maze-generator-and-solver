# Maze Pathfinder

## Description
This project provides a Python library (`pyamaze.py`) for generating various types of mazes and visualizing different pathfinding algorithms. It includes demonstrations for Breadth-First Search (BFS), Depth-First Search (DFS), and A* (A-Star) algorithms. Users can create mazes of different sizes, save them, load them, and see how agents navigate through them.

## Features
*   **Maze Generation:** Create mazes with customizable dimensions (rows and columns).
*   **Maze Patterns:** Generate mazes with horizontal or vertical passage biases.
*   **Loop Creation:** Introduce loops and multiple paths in mazes using `loopPercent`.
*   **Save/Load Mazes:** Save generated mazes to CSV files and load them for later use.
*   **Pathfinding Algorithms:**
    *   Breadth-First Search (BFS)
    *   Depth-First Search (DFS)
    *   A* (A-Star) Search
*   **Visualization:** Uses Tkinter to display mazes, agents, and algorithm paths.
*   **Agents:** Place agents on the maze with customizable shapes, colors, and footprints.
*   **Algorithm Comparison:** Includes scripts to compare the behavior and performance of different algorithms (e.g., BFS vs. A*, DFS vs. BFS).
*   **Themes:** Supports dark and light themes for the maze visualization.

## Files
*   `pyamaze.py`: The core library containing classes for maze creation (`maze`), agent representation (`agent`), and GUI elements (`COLOR`, `textLabel`).
*   `BFSDemo.py`: Demonstrates the Breadth-First Search algorithm.
*   `DFSDemo.py`: Demonstrates the Depth-First Search algorithm.
*   `aStarDemo.py`: Demonstrates the A* search algorithm.
*   `aStarDemo2.py`: Another demonstration for the A* algorithm.
*   `BFSvsAStar.py`: Compares BFS and A* algorithms.
*   `DFSvsBFS.py`: Compares DFS and BFS algorithms.
*   `astarHeuristicComparison.py`: Compares different heuristics for the A* algorithm.
*   `astardemo.csv`: An example CSV file representing a saved maze.

## Requirements
*   Python 3.x
*   Tkinter (usually included with standard Python installations)

## How to Run
1.  Ensure you have Python 3 installed.
2.  Clone or download the repository.
3.  Navigate to the directory containing the files.
4.  Run any of the demo scripts, for example:
    ```bash
    python BFSDemo.py
    python aStarDemo.py
    ```
    This will open a Tkinter window displaying the maze and the algorithm in action.

## Contributing
Contributions are welcome! If you have ideas for new features, algorithm implementations, or improvements, feel free to fork the repository, make your changes, and submit a pull request.
