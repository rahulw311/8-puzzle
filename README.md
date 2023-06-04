# 8-puzzle
Using heuristic search to solve the 8 puzzle problem

The 8-puzzle problem is a puzzle invented and popularized by Noyes Palmer Chapman in the 1870s. It is played on a 3-by-3 grid with 8 square blocks labeled 1 through 8 and a blank square. Your goal is to rearrange the blocks so that they are in order. You are permitted to slide blocks horizontally or vertically into the blank square. The following shows a sequence of legal moves from an initial board position (left) to the goal position (right).
This was a mini project as part of my Aritifical Intelligence course by Dr. Eamonn Keogh to solve this puzzle.

An example of this can be seen below- 
 
![8puzzle](https://github.com/rahulw311/8-puzzle/assets/95941770/ab19ce32-5c38-479d-9ba4-ceb1382025f6)

In this project 3 different methods have been used in order to solve the 8 puzzle problem-
1. Uniform Cost Search
Uniform-cost search is an uninformed search algorithm that uses the lowest cumulative cost to find a path from the source to the destination. Nodes are expanded, starting from the root, according to the minimum cumulative cost.
2. A* search using the Manhattan Distance heuistic
Manhattan Distance heuristic (also called the block distance heuristic) is a common heuristic function that is computed by counting the number of moves along the grid that each tile is displaced from its goal position, and summing these values over all tiles.
3. A* search using the Misplaced Tile heuristic
This heuristic will keep track of the number of “misplaced” tiles in the puzzle. A particular tile is said to be “misplaced” if its position is different from the corresponding numbered tile in the goal state.
