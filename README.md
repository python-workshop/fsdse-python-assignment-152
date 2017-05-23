# Find the shortest path between two nodes in a graph.

To determine the shorted path in an unweighted graph, we can use breadth-first search keeping track of the previous nodes ids for each node. Previous nodes ids can be a dictionary of key: current node id and value: previous node id

## Constraints
* Is the graph directed? - Yes
* Is the graph weighted? - No
* Can we assume we already have Graph and Node classes? - Yes
* Are the inputs two Nodes? - Yes
* Is the output a list of Node keys that make up the shortest path? - Yes
* If there is no path, should we return None? - Yes
* Can we assume this is a connected graph? - Yes
* Can we assume the inputs are valid? - Yes
* Can we assume this fits memory? - Yes