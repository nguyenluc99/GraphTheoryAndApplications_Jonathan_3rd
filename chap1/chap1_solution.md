## Chapter 1:  INTRODUCTION TO GRAPH MODELS

#### 1.1.33:
- There are 31 edges => There are 62 connections (sum of all degree)
- There are 1*3 + 4*7 = 31 connections occupied by three 1-valent vertices and seven 4-valent vertices. => There are 31 connections left for 13-1-4 = 8 edges.
- In order for the graph is a simple graph => This 8-edges sub-graph should form a simple graph with one-preserved connection, which means that there are 30 connections for these 8 edges. However, there are maximum of $7+6+5+4+3+2+1+0 = \\dfrac{8.7}{2} = 28 $ possible connections in case these 8 vertices are fully connected => There should be some edges which are self-loops or multi-arcs of each other. Therefore, this cannot form a simple graph.

### Vertex Cover
#### 1.1.34:
[//]:<> ( - Upper bounds: $n$, when all vertices are fully connected.)
[//]:<> ( - Lower bounds: $\left\[\dfrac{n+1}{2}\right\]$, when each pair is connected. If n is odd, the last vertex connects to itself.)
- Upper bound: $ n-1 $, happens in fully connected graph.
- Lower bound: 1, happens in star graph, where one vertex connects to all other vertices using n-1, there is no more edges. That vertex is enough in W.


#### 1.1.36:
The guards can be placed at the following position that give the best utilization: `a,c,e,g,k`


### Independent set of vertices
#### 1.1.37:


#### 1.1.38:


#### 1.1.39:
One maximum independent set of vertices is : `a,e,c,g,h,k`.
Hence, there are 6 elements in the maximum independent set.

### matching
#### 1.1.40 

#### 1.1.41 


### Dominating set
#### 1.1.43


#### 1.1.45:
The minimum dominating set can be chosen as: `b,g,k`
- For `b`, we obtain `N[b] = a,b,c,e`
- For `g`, we obtain `N[g] = d,g,h,j`
- For `k`, we obtain `N[k] = f,j,i,k`
The union of `N[b], N[g], N[k]` should be enough to cover all vertices in the graph.

