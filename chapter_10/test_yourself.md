Page 716

**Test Yourself**

1. Let $G$ be a graph and let $v$ and $w$ be vertices in $G$.

a. A walk from $v$ to $w$ is ____.

a finite alternating sequence of adjacent vertices and edges of $G$

b. A trail from $v$ to $w$ is ____.

a walk from $v$ to $w$ that does not contain a repeated edge

c. A path from $v$ to $w$ is ____.

a trail that does not contain a repeated vertex

d. A closed walk is ____.

a walk that starts and ends at the same vertex

e. A circuit is ____.

a closed walk that contains at least one edge and does not contain a repeated
edge

f. A simple circuit is ____.

a circuit that does not have any other repeated vertex except the first and last

g. A trivial walk is ____.

a walk consisting of a single vertex and no edge

h. Vertices $v$ and $w$ are connected if, and only if, ____.

there is a walk from $v$ to $w$

2. A graph is connected if, and only if, ____.

given any two vertices in the graph, there is a walk from one to the other

3. Removing an edge from a circuit in a graph does not ____.

disconnect the graph

4. An Euler circuit in a graph is ____.

a circuit that contains every vertex and every edge of the graph

5. A graph has a Euler circuit if, and only if, ____.

the graph is connected, and every vertex has a positive, even degree

6. Given vertices $v$ and $w$ in a graph, there is an Euler trail from $v$ to
   $w$ if, and only if, ____.

the graph is connected, $v$ and $w$ have an odd degree, and all other vertices
have a positive even degree

7. A Hamiltonian circuit in a graph is ____.

a simple circuit that includes every vertex of $G$

8. If a graph $G$ has a Hamiltonian circuit, then $G$ has a subgraph $H$ with
   the following properties: ____, ____, ____, and ____.

$H$ contains every vertex of $G$; $H$ is connected; $H$ has the same number of
edges as vertices; every vertex of $H$ has a degree of $2$.

9. A traveling salesman problem involves finding a ____ that minimizes the total
   distance traveled for a graph in which each edge is marked with a distance.

Hamiltonian circuit

---

Page 733

**Test Yourself**

1. In the adjacency matrix for a directed graph, the entry in the $i$th row and
   $j$th column is ____.

the number of arrows from $v_i$ to $v_j$

2. In the adjacency matrix for an undirected graph, the entry in the $i$th row
   and the $j$th column is ____.

the number of edges connecting $v_i$ and $v_j$

3. An $n \times n$ square matrix is called symmetric if, and only if, for all
   integers $i$ and $j$ from $1$ to $n$, the entry in row ____ and column ____
   equals the entry in row ____ and column ____.

$i$; $j$; $j$; $i$

4. The $ij$th entry in the product of two matrices $\mathbf{A}$ and $\mathbf{B}$
   is obtained by multiplying row ____ of $\mathbf{A}$ by the row ____ of
   $\mathbf{B}$.

$i$; $j$

5. In an $n \times n$ identity matrix, the entries on the main diagonal are all
   ____ and the off-diagonal entries are all ____.

$1$; $0$

6. If $G$ is a graph with vertices $v_1, v_2, \dots, v_m$ and $\mathbf{A}$ is
   the adjacency matrix of $G$, then for each positive integer $n$ and for all
   integers $i$ and $j$ with $i, j = 1, 2, \dots, m$, the $ij$th entry of
   $\mathbf{A}^n =$ ____.

the number of walks of length $n$ from $v_i$ to $v_j$

---

Page 741

1. If $G$ and $G'$ are graphs, then $G$ is isomorphic to $G'$ if, and only if,
   there exist a one-to-one correspondence $g$ from the vertex set of $G$ to the
   vertex set of $G'$ and a one-to-one correspondence $h$ from the edge set of
   $G$ to the edge set of $G'$ such that for every vertex $v$ and every edge $e$
   in $G$, $v$ is an endpoint of $e$ if, and only if, ____.

$g(v)$ is an endpoint of $h(e)$

2. A property $P$ is an invariant for graph isomorphism if, and only if, given
   any graphs $G$ and $G'$, if $G$ has property $P$ and $G'$ is isomorphic to
   $G$ then ____.

$G'$ has property $P$

3. Some invariants for graph isomorphisms are ____, ____, ____, ____, ____,
   ____, ____, ____, ____, and ____.

has $n$ vertices; has $m$ edges; has vertex of degree $k$; has $m$ vertices of
degree $k$; has a circuit of length $k$; has a simple circuit of length $k$; has
$m$ simple circuits of length $k$; is connected; has an Euler circuit; has a
Hamiltonian circuit

---

Page 754

**Test Yourself**

1. A circuit-free graph is a graph with ____.

no circuits

2. A forest is a graph that is ____, and a tree is a graph that is ____.

circuit-free and disconnected; circuit-free and connected;

3. A trivial tree is a graph that consist of ____.

a single vertex (and no edges)

4. Any tree with at least two vertices has at least one vertex of degree ____.

$1$

5. If a tree $T$ has at least two vertices, then a terminal vertex (or leaf) in
   $T$ is a vertex of degree ____ and an internal vertex (or branch vertex) in
   $T$ is a vertex of degree ____.

$1$, $2$ or more

6. For any positive integer $n$, any tree with $n$ vertices has ____.

$n - 1$ edges

7. For any positive integer $n$, if $G$ is a connected graph with $n$ vertices
   and $n - 1$ edges then ____.

$G$ is a tree

---

Page 764

**Test Yourself**

1. A rooted tree is a tree in which ____. The level of a vertex in a rooted tree
   is ____. The height of a rooted tree is ____.

there is one vertex that is distinguished from the others and is called the
root; the number of edges along the unique path between it and the root; the
maximum level of any vertex of the tree

2. A binary tree is a rooted tree in which ____.

every parent has at most two children

3. A full binary tree is a rooted tree in which ____.

each parent has exactly two children

4. If $k$ is a positive integer and $T$ is a full binary tree with $k$ internal
   vertices, then $T$ has a total of ____ vertices and has ____ leaves.

$2k + 1$; $k + 1$

5. If $T$ is a binary tree that has $t$ leaves and height $h$, then $t$ and $h$
   are related by the inequality ____.

$t \leq 2^h$, or, equivalently, $\log_2t \leq h$
