# 8-puzzle-problem
Problem
Implement Depth-First Search (DFS), Breadth-First Search (BFS) and Iterative Deepening Search (IDS) algorithms to
solve the 8-puzzle problem. The 8-puzzle consists of a 3x3 grid with 8 numbered tiles and one blank space. The
goal is to rearrange the tiles to form a particular configuration. Your program should accept the initial
configuration of the puzzle as input and output the steps required to reach the goal state. In addition, compare
the efficiency of the three algorithms in terms of number of nodes visited, path cost, and time taken to find the
solution.
Sample Output
Enter start State: 120345678
Enter goal State: 012345678
-----------------
DFS Algorithm
-----------------
Time taken: 0.0010004043579101562 seconds
Path Cost: 2
No of Node Visited: 3
-----------------
1 2 0
3 4 5
6 7 8
-----
1 0 2
3 4 5
6 7 8
-----
0 1 2
3 4 5
6 7 8
-----
