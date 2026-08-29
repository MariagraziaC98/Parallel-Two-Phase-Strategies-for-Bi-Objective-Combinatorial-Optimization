# Parallel Two-Phase Strategies for Bi-Objective Combinatorial Optimization
This repository contains the data used in the study: *Parallel Two-Phase Strategies for Bi-Objective Combinatorial Optimization: A distributed and Shared-Memory Framework*.

Two classes of graphs have been used in this study:
- Complete graphs;
- Grid graphs.

For each graph size and cost correlation, the repository contains:
- the corresponding graph instances;
- the supported non-dominated points generated during the first phase of the two-phase method;
- the spanning trees corresponding to these points.

Each instance file specifies an undirected graph G=(N,E) together with the associated bi-objective edge costs:
- the first line indicates the graph topology (e.g., complete or grid graph);
- the second and third lines report the number of nodes, |N|=n, and the number of edges, |E|=m, respectively;
- each of the following lines corresponds to one edge (i,j)∈E and is given in the format i j c<sub>1</sub> c<sub>2</sub>, where i and j denote the endpoints of the edge and c<sub>1</sub>, c<sub>2</sub> are the corresponding integer costs on the two objectives.
