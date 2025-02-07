# PathFinding-Algorithm-Path-visualizer
# Hello there!
This Pathfinding Algorithm Visualizer is a dynamic web application that provides an interactive way to explore and compare pathfinding algorithms such as BFS, DFS, and Dijkstra's Algorithm. Users can visualize how different algorithms traverse a grid, analyze key metrics like path length and nodes explored, and generate random mazes for testing. The application runs multiple algorithms simultaneously, offering a side-by-side comparison of their efficiency. Built using HTML, CSS, JavaScript, React, and Firebase, it delivers a hands-on educational experience for understanding pathfinding in real-time.

## Here is the preview images for my project
### Before visualization:

![Screenshot 2021-02-11 224917](https://user-images.githubusercontent.com/58566745/107673174-bff32800-6cbb-11eb-81a7-8e240660369f.jpg)

### After visualization(ofcourse I just changed the theme from dark mode to light mode for this image):
This is the result after executing a maze generation algorithm and path-finding algorithm.

![Screenshot 2021-02-11 225049](https://user-images.githubusercontent.com/58566745/107673376-f3ce4d80-6cbb-11eb-907c-a8255ef9555e.jpg)

## Features in the application
### Algorithms
- _Dijsktra_ - Dijkstra's algorithm (or Dijkstra's Shortest Path First algorithm, SPF algorithm) is an algorithm for finding the shortest paths between nodes in a graph, which may represent, for example, road networks. It was conceived by computer scientist Edsger W. Dijkstra in 1956 and published three years later.

- _DFS_ - Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.

- _BFS_ - Breadth-first search (BFS) is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root (or some arbitrary node of a graph, sometimes referred to as a 'search key'), and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level. It uses the opposite strategy of depth-first search, which instead explores the node branch as far as possible before being forced to backtrack and expand other nodes.

- _A*_ - A* is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its O(b^d) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, as well as memory-bounded approaches; however, A* is still the best solution in many cases.

## Maze generation algorithms
- _Random Maze_ - It's just a simple algorithm which creates walls based on the output of a random function.

- _Recursive Division_ - Mazes can be created with recursive division, an algorithm which works as follows: Begin with the maze's space with no walls. Call this a chamber. Divide the chamber with a randomly positioned wall (or multiple walls) where each wall contains a randomly positioned passage opening within it. Then recursively repeat the process on the subchambers until all chambers are minimum sized. This method results in mazes with long straight walls crossing their space, making it easier to see which areas to avoid.
