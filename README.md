# Logisim-BFS

Created a finite state machine model in logisim to implement BFS algorithm.
* The BFS process requires a queue to process the visiting nodes in the graph which is implemented using a modified register file with shifting of data through all adjacaent D Flip Flops.
* Distances are saved in a distance regiseter file.
* An adjacency matrix was designed using decoder along with register file which supports adding and reading of graph edges.
* The fsm takes front element out iterates on all the nodes reachable from the current node, checks if its distance is actually greater than current + 1. And pushes it in accordingly in the next cycle.
