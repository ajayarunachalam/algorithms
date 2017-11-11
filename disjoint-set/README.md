

A [disjoint-set](https://en.wikipedia.org/wiki/Disjoint-set_data_structure) data structure, also called a **union–find** data structure or **merge–find set**, is a data structure that keeps track of a set of elements partitioned into a number of disjoint (non-overlapping) subsets. It provides near-constant-time operations to add new sets, to merge existing sets, and to determine whether elements are in the same set. It plays a key role in Kruskal's algorithm for finding the minimum spanning tree of a graph.

Methods
--------

- *find()*: it returns the identifier of a given set.
- *connected()*: it determines if two elements are in the same set.
- *count()*: it retunrs the number of current sets.
- *union()*: it merges two components and decrement the set counter.

Material
--------
- **Coursera Algorithms Part 1**: week 1
- **Algorithms**, Sedgewick and Wayne (2014): Chapter 1.5