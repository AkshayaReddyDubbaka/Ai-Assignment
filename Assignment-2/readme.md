##output

Result (Best First Search):
Path length: 3 , Path: [(0, 0), (1, 1), (2, 2)]

Result (A* Search):
Path length: 3 , Path: [(0, 0), (1, 1), (2, 2)]

## ALGORITHM COMPARISON

Best First Search uses only the heuristic h(n) to expand the node that seems closest to the goal, which makes 
it fast but not guaranteed to find the optimal path.

A* Search uses both path cost g(n) and heuristic h(n), i.e., f(n)=g(n)+h(n), so it is more accurate and 
guarantees the optimal path if the heuristic is admissible.
