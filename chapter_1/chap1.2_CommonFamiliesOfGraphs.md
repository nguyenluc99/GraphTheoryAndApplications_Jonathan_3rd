# Chapter 1:  INTRODUCTION TO GRAPH MODELS

## Section 1.2: COMMON FAMILIES OF GRAPHS

#### 1.2.1: 
``K_n: n*(n-1)/2 = C_2^n``
``K_{m,n}: m*n``

#### 1.2.2:
What is the maximum possible number of edges in a simple bipartite graph on `m` vertices:
- Maximum number of edges in ``K_{a,b}`` is `a*b`, since `a+b=n`, maximum of `a*b` should be `n^2/4` when ``n`` is even (`a=b=n/2`) or `(n^2-1)/4` when `n` is odd (`a=(n-1)/2, b=(n+1)/2`)

#### 1.2.3: 
The smallest non-bipartite graph should contain no vertices or edges

#### 1.2.4:
The graph cannot be bipartite if it contains a triangle. Otherwise, it is.
-  `K_n:  n \leq 2`
-  `C_n: n % 2 == 0`, or `n` is a multiple of 2.
-  `P_n: `always, since it contains only two vertices.

#### 1.2.6:
Yes. Two sets could be ``{x;v}``, ``{z,u}``
#### 1.2.7: 
No. This completed graph contain odd number of edges.
#### 1.2.8:
Yes. Two sets could be `{x,z,u}` and `{y,v,w}`

#### 1.2.9:

#### 1.2.10:
Mark the first vertex as solid.
From this vertex, we traverse all the edge and read its bitstrings. If they differs from the initial vertex at odd position, mark them as hollow. If they differs from the initial vertex at even position, mark them as solid.
Since two vertices differ in exactly one bit, one should have bitstrings differing at odd number of position and the other should have bitstrings differing at even number of position compared to the initial vertex. Which means that one should be in the same status (solid/hollow) as the initial vertex and the other does not. Therefore, these two vertices are marked in the different status. Hence, the graph is bipartite.

#### 1.2.11:
- Tetrahedron: Yes - Yes
- Cube: Yes - Yes
- Octahedron: Yes - Yes
- Dodecahedron:  ... - ...
- Icosahedron: ... - ...

#### 1.2.12:
The sum of degree of all vertices in the graph should be an even since each edge contributes two degree increment to two vertices.
Therefore, there does not exists a 5-regular graph on 11-vertices.

#### 1.2.13:
a)
b) For each connection between two vertices, e.g. A and B, we can choose either a directed edge from A to B, B to A or two directed edges from A to B and B to A. Which means that we have three options for each connection between two vertices so that its underlying graph is completed. 
We can obtain 6 pairs from 4 vertex. Therefore, we have `3^6` as total of 4-vertex tournaments.

#### 1.2.14:
- If there are two edges with zero indegree, the connection between them will make one of them increased its indegree; therefore, make it no longer zero indegree.
- Similar to outdegree, there will not exist neither two vertices with zero indegree or zero outdegree.

#### 1.2.15:
This is the generalization of exercise  `1.2.13` part `b` which applies for `n` vertices.
There are `3^(n(n-1)/2)` `n`-vertex tournaments that can be drawn on those vertices.

#### 1.2.16:
The result is derived from remove the `a_1` element from the subsets `U`. Doing this makes U become `<a_2, a_3, ... , a_n>`, and the `W`, which remove `a_1` connections with `u1`, becomes `<b_1-1, b_2-1, ... b_{a_1+1}-1, b_{a_1+2}, ... , b_t>`. The two pairs of subsets has the same properties in being whether bigraphical or not. Therefore, the assumption is proved.





