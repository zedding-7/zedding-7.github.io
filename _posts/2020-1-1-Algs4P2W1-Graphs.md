## Undirected Graphs
### Definations
* The **degree** of a vertex is the number of edges incident on it.  
* A **path** in a graph is a sequence of vertices connected by edges, with no repeated edges.  
* A **simple path** is a path with no repeated vertices.  
* A graph is **connected** if there is a path from every vertex to every other vertex.  
* A **tree** is an acyclic connected graph.  
* A **spanning tree** of a connected graph is a subgraph that contains all of that graph's vertices and is a single tree.  
* A **spanning forest** of a graph is the union of the spanning trees of its connected components.  
* A **bipartite graph** is a graph whose vertices we can divide into two sets such that all edges connect a vertex in one set with a vertex in the other set.  

## Digraphs (Directed Graphs)
### Definations
* Two edges are **parallel** if they connect the *same ordered* pair of vertices.  
* The **outdegree** of a vertex is the number of edges pointing from it.  
* The *indegree* of a vertex is the number of edges pointing to it.  
* A **directed cycle** is **simple** if it has no repeated vertices (other than the requisite repetition of the first and last vertices).  
* We say that two vertices v and w are **strongly connected** if they are mutually reachable: there is a directed path from v to w and a directed path from w to v.  
* A digraph that is not strongly connected consists of a set of **strongly connected components**, which are maximal strongly connected subgraphs.  
* A **directed acyclic graph** (or **DAG**) is a digraph with no directed cycles.  
* **Topological sort** : given a digraph, put the vertices in order such that 
all its directed edges point from a vertex earlier in &emsp;&emsp;the order to a vertex later in the order 
(or report that doing so is not possible).   
&emsp;&emsp;a reverse postorder in a DAG provides a topological order.  
&emsp;&emsp;**Proposition.** A digraph has a topological order if and only if it is a DAG.
