Introduction:Robot pathfinding is a critical aspect of robotics, enabling robots to navigate environments and reach specified goals. It involves finding the optimal or feasible path from a starting point to a target within a grid or map. 
Common pathfinding algorithms include Breadth-First Search (BFS), Depth-First Search (DFS), and Uniform Cost Search (UCS).

Pathfinding Algorithms Used:
BFS: Explores all possible moves level by level. Guarantees the shortest path in unweighted grids.
DFS: Explores as far as possible along a branch before backtracking. Suitable for exploring all paths but may not find the shortest one.
UCS: Finds the least-cost path by prioritizing moves with the lowest accumulated cost. Ensures optimal paths in weighted environments.

Objective:The implemented Python code demonstrates these algorithms on a grid-based environment. It visualizes the robot’s movement from the start to the goal, providing insights into each algorithm’s behavior.

Visualization Features:
The grid is displayed with obstacles cells (1s) and free spaces (0s) and cost cells(2s).
The robot’s start and goal positions are highlighted in green and red, respectively.
Animations illustrate the robot's movement along the computed path for each algorithm.
Insights:
BFS excels in finding the shortest path but can be computationally expensive for large grids.
DFS may quickly reach the goal but can get stuck in loops or find suboptimal paths.
UCS balances cost-effectiveness and pathfinding accuracy, particularly in grids with variable weights.
Applications:These algorithms are foundational for autonomous robots, maze-solving, delivery drones, and other navigation systems. Understanding their strengths and limitations aids in selecting the right approach for specific tasks.

Demo : https://drive.google.com/file/d/1PnMZ1e0wkDQljnWdNUedKcM7e5S_DWq0/view?usp=drive_link



