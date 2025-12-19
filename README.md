# Maze-Game
A browser-based maze game that generates random mazes and finds the shortest path using classical graph algorithms.

<h2><b>🚀 Features</b></h2>
Random maze generation using:<br><br><ul><li>
Recursive Backtracker (DFS)</li><li>
Shortest path solver using Breadth-First Search (BFS)</li><li>
Grid-based movement system</li><li>
Player navigation with real-time path visualization</li>
</ul>
<h2><b>🧠 Core Concepts Used</b></h2>
<p>
Data Structures: Arrays, Stack, Queue, Hash Map
Algorithms:<ul><li>
Depth-First Search (DFS)</li><li>
Breadth-First Search (BFS)</li>
</ul>
Graph traversal and path reconstruction
</p>
<h2><b>🗂 Data Representation</b></h2><p>
The maze is stored as a 1D array mapped to a 2D grid<br><br>
Cell values:<ul><li>
1 → Wall</li><li>
0 → Path</li></ul>
Player position tracked using (row, column) coordinates
</p>
<h2><b>🔧 Maze Generation Algorithms</b></h2>
<p>
1. Recursive Backtracker (DFS)<br>
Creates deep, winding mazes by exploring paths recursively and backtracking when necessary.
</p>
<p>🧭 Pathfinding Algorithm<br><ul><li>
Breadth-First Search (BFS)</li><li>
Used to find the shortest path from start to end</li><li>
Guarantees optimal solution in an unweighted grid</li><li>
Uses a parent map to reconstruct the path</li></ul>
</p><p>
🕹 Game Logic<br><ul><li>
Player movement is restricted to valid path cells</li><li>
Game state tracks player position and solution path</li><li>
Timer starts when the game begins</li></ul>
</p>
<h2><b>🛠 Tech Stack</b></h2><ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
</ul>
<h2><b>📌 Learning Outcomes</b></h2><ul>
<li>Practical implementation of graph algorithms</li>
<li>Strong understanding of grid-based problem solving</li>
<li>Experience translating algorithms into interactive applications</li></ul>
