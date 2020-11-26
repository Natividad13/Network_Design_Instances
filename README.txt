Instances for the covering problem.
n = number of nodes, m = number of edges, p = number of demand O/D pairs, CMAX = total budget for construction 
b = vector cost of nodes set, c = vector cost of edges set, d = Euclidean distance vector of edges set, g = demand vector of pairs set, u = private utility of pairs set.

We have two types of instances:

Random Instances: Instances with n in {10,20,40,60} nodes and edges are added randomly with a probability of 0.7 . Cost of nodes is created randomly generated as U(7,13).
Cost of edges is fixed as the Euclidean distance d. It means that building the edges cost 1 monetary unit per length unit. 
CMAX is set as 50% of the cost of building the whole underlying network considered. 
Parameter u is set to 2 times the length of the shortest path between each origin and destination. The demand g for each pair is randomly generated as U(10,300).
For each value of n we create 10 random instances.

Benchmark instances: Sioux and Sevilla networks are considered. With respect to Sioux network we have only used the topology of the graph. 
We have generated the parameters as for random  instances.

Each instance file has on its first line n, m, p and CMAX separated by a space. Nodes are enumerated from 0 to n-1. The following n lines represent each node and its asociated cost.
Then, the following m lines represent the edges: first two numbers represent the terminal nodes of the edge; the thirs and fourth number represent its cost and distance.
Last p lines represent the set of O/D pairs: the first two numbers are the origin and destination, and the thirs and fourth positions are the demand and private utility, respectively.
The name of each instance file "N_a_b_c" represent the number of nodes, edges and index of the network.
