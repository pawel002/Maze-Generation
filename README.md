# Maze Generating
Generating and solving a rectangular maze of any size using graph algorithms.

First we create a weighted graph which will be used to create a path, around which the labiryth will be generated. Next using edge weights we can create a MST of our graph. Because the path is a tree, it ensures that every two points are connected by only 1 valid path (trees are acyclic) and every two points are connected (trees are connected). After, we can easily generate a plot of a maze enclosing given paths. Finally using bidirectional BFS we can find a solution to the maze (from bottom left to top right). Last bit of code can be used to find mazes with longest paths from start to end.

![Grid graph](https://github.com/pawel002/generating-maze/blob/master/images/grid.png)
