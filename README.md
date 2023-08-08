# Maze Traversal using Breadth-First Traversal

![BFS_LeetCode](https://github.com/girik21/MazeTraversal/assets/87162191/200cd5ee-6933-4c66-a704-84813cadd14b)

## Presentation Link
[View Presentation](https://docs.google.com/presentation/d/1gVOdVBkyDdFI5u5WkCLFpiPU56wYlUsrIOcy1Q29uMs/edit?usp=sharing)

## Abstract
- Efficiently traverse mazes using the Breadth-First Search (BFS) algorithm.
- Implement a concise and elegant BFS solution for maze navigation.
- Explore diverse maze configurations and assess BFS performance.
- Successfully traverse mazes with rigorous testing.
- Showcase BFS efficiency and reliability in complex mazes.
- Provide insightful findings and future recommendations.

## Introduction
- Traverse from the starting point to the finishing line inside a maze.
- Utilize Breadth-First Search (BFS) algorithm for efficient maze traversal.
- Accomplish the maze-solving goal with an elegantly concise implementation, highlighting the power of BFS.

## Design
- Treat the maze as a 2D grid, where each cell is represented as a vertex for exploration.
- Explore the maze layer by layer, expanding in all directions from the starting point.
- Utilize a queue to manage the coordinates of cells for exploration.
- Mark each explored cell as visited to avoid re-exploration and ensure efficiency.
- BFS does not explicitly convert the maze into a graph representation.

## Implementation
- Represent the cells as a 2D matrix.
- Input the starting and the ending position.
- The class `Solution` contains methods to traverse the maze and find paths using BFS.
- Utilize a `visited` set to keep track of explored cells during maze traversal.
- Initialize the `visited` set as an empty set before starting the BFS traversal.
- Add the coordinates of each explored cell to the `visited` set to avoid revisiting.
<img width="881" alt="Screenshot 2023-08-07 at 5 14 55 PM" src="https://github.com/girik21/MazeTraversal-BFS/assets/87162191/36525e4c-6588-45cb-9053-b2608ceead1e">

## Test Cases
- Test the BFS maze traversal with various maze configurations.
- Ensure successful navigation from the starting point to the destination.
![Screenshot 2](https://github.com/girik21/MazeTraversal/assets/87162191/bce067c3-3200-421d-a9ca-e3fcdc31f29f)
  
## References
- `Leetcode`: [LeetCode Maze/](https://leetcode.com/problems/the-maze/)
- `Prof Henry Chang website`: [https://hc.labnet.sfbu.edu/~henry/npu/classes//algorithm/graph_alg/slide/maze.html#a1](https://hc.labnet.sfbu.edu/~henry/npu/classes//algorithm/graph_alg/slide/maze.html#a1)
- `ChatGPT How to solve BFS maze using python`: [ChatGPT/](https://chat.openai.com/)
