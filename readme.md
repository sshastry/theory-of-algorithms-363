
## Theory of Algorithms

This repository contains the exams (with solutions) for an upper level undergraduate course in algorithms which I taught in Spring 2012. The course covered chapters 1-6 and 8 of [Kleinberg and Tardos](http://www.amazon.com/Algorithm-Design-Jon-Kleinberg/dp/0321295358); the book is fantastic and is highly recommended.

The topics covered:

* introduction: the stable matching problem
* big-O notation
* heaps
* priority queues
* graph traversal
    * breadth first traversal of graphs
    * depth first traversal of graphs
    * data structures for implementing graph traversal: queues and stacks
    * directed acyclic graphs (DAGs) and topological ordering
* greedy algorithms
    * interval scheduling
    * Dijkstra's algorithm to find the shortest paths in a graph
    * minimum spanning trees: algorithms of Kruskal and Prim
        * data structure for Prim: priority queue
        * data structure for Kruskal: union-find
    * Huffman coding
* divide and conquer algorithms
    * the master theorem for recurrences
    * mergesort
    * integer multiplication of two n-bit factors in `O(n^{log_2(3)}) = O(n^{1.59})`
    * Fast Fourier Transform
* dynamic programming
    * memoized interval scheduling
    * segmented least squares
    * subset sum and knapsack
    * RNA secondary structures
    * sequence alignment
    * Bellman-Ford algorithm for finding shortest paths in a graph
    * detection of negative cycles in a graph
* complexity theory
    * polynomial time reductions
    * the definition of P
    * the definition of NP
    * problems and some reductions amongst them
        * vertex cover
        * set cover
        * SAT and 3-SAT
        * subset sum
        * traveling salesman
        * Hamiltonian cycle
        * graph coloring
        * circuit satisfiability
    * theorem: there exists an NP-complete problem

