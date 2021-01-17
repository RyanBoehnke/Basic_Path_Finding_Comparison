# Basic_Path_Finding_Comparison
A comparison of Dijkstra's Algorithm (DA), Greedy Best First Search (GBFS), and A* on a 256x256 pixel map. Each test will randomly generate a new set of blockers for a given blocker percentage.

The blank map file exists just to give a blank starting image to use.

The percentage of the map given over to blockers can be changed, and the likelihood that it will be unpathable increases with the blocker percentage.

Outputs 7 images to the results file. The base map with blockers, the nodes visted by the agent, as well as the visited nodes and path for each algorithm.

The algorithms use a blocker matrix to determine if the node is open or closed, with 1 being blocked, and 0 being open.
