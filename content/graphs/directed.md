Title: Directed and Undirected Graphs
Category: Graphs
Date: 2016-06-26
Position: 2
Summary: Edges can have a direction

Edges in a graph join any two nodes, representing a relationship between
them. Sometimes, this relationship can be bilateral (or symmetric), e.g.,
"Alice and Bob are friends of each other", while other times, the
relationship can be unilateral (asymmetric): "Alice follows Bob's blog (but
not the other way around)".

When the relationship represented by the edges in a graph is symmetrical,
we draw them as lines or arcs and say the graph is **undirected**. When the
relationship is asymmetrical, we draw them with arrows and say the graph is
**directed**.

IMAGE

For this problem, you need to read a file from stdin and output two nodes:
the node with the hightest *outgoing* edges and the node with the hightest
*incoming* edges.

Note: for a given node `u`, the number of outgoing edges from `u` is called
*outdegree* of u, and the number of incoming edges to `u` is the *indgree*
of u.


### Input

The input is a file in which the first line contains two integers, `n` and
`m`, defining the number of nodes and edges, respectively. The next `m`
lines each contain two integers, `u` and `v`, reprsenting two nodes that
are joined by a directed edge, going from `u` to `v`.

### Output

Output two integers, representing the nodes with the highest outdegree and
highest indegree.


### Test Input

```
4 5
0 1
0 2
1 3
3 0
0 3

```

### Test Output

```
0 3

```
--------------------------------------------------------
[Solution](https://github.com/Leockard/erdos/blob/master/solutions/graphs/directed.py).