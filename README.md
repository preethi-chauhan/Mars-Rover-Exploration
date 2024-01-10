# Mars-Exploration-Rover-Path

The working demo of the project can be accessed from here [Mars Exploration Rover](https://preeminent-donut-c4080b.netlify.app/).

This Project aims to use various path-finding algorithms for assisting the Martian Rover in concluding the shortest path to the destination while traversing a specific area.

To make the project more realistic, the user is provided with a feature to add nodes to the grid. The start and end positions would not always be the same hence, user can change the start and end positions in the grid by just dragging the respective nodes. After making the required changes, the user can then select any algorithm from the algorithms section. The display box displaying the distance, time, and the number of nodes travelled helps the user to compare various algorithms and find the shortest path for the martian rover.

This project provides the feature of adding obstacles in the form of a wall. If a wall is encountered while traversing the grid, that particular block is skipped and is not visited. Traversing happens until the destination block is reached.

The path is found by traversing the grid from the start node by any of the chosen algorithms, and on visiting the destination node, the path is reconstructed and added up to give the final path. It is beneficial for communication among mars rovers or if an intermediate location is to be found between two coordinates.

