# Vertex-Cover

A Vertex Cover (sometimes node cover) of a graph is a set of vertices such that each edge of the graph is incident to at least one vertex of the set.

#Approximation ALgorithm

Approximation Algorithms are efficient algorithms that find approximate solutions to NP-hard optimization problems with provable guarantees on the distance of the returned solution to the optimal one.The goal of an approximation algorithm is to come as close as possible to the optimum value in a reasonable amount of time which is at most polynomial time.

## Approximation Algorithm for Vertex Cover Problem

1) Initialize the result as {}
2) Consider a set of all edges in given graph.  Let the set be E.
3) Do following while E is not empty
    
    ...a) Pick an arbitrary edge (u, v) from set E and add 'u' and 'v' to result
    
    ...b) Remove all edges from E which are either incident on u or v
4) Return result 

Time Complexity of above algorithm is O(V + E).
