Page 702

**Definition**

Let $G$ be a graph, and let $v$ and $w$ be vertices in $G$.

A **walk from $v$ to $w$** is a finite alternating sequence of adjacent vertices
and edges of $G$. Thus a walk has the form

$$ v_0e_1v_1e_2 \cdots v_{n - 1}e_nv_n $$

where the $v$'s represent vertices, the $e$'s represent edges,
$v_0 = v, v_n = w$, and for each $i = 1, 2, \dots n, v_{i - 1}$ and $v_i$ are
the endpoints of $e_i$. The **trivial walk from $v$ to $v$** consists of the
single vertex $v$.

A **trail from $v$ to $w$** is a walk from $v$ to $w$ that does not contain a
repeated edge.

A **path from $v$ to $w$** is a trail that does not contain a repeated vertex.

A **closed walk** is a walk that starts and ends at the same vertex.

A **circuit** is a closed walk that contains at least one edge and does not
contain a repeated edge.

A **simple circuit** is a circuit that does not have any other repeated vertex
except the first and last.

---

Page 704

**Definition**

A graph $H$ is said to be a **subgraph** of a graph $G$ if, and only if, every
vertex in $H$ is also a vertex in $G$, every edge in $H$ is also an edge in $G$,
and every edge in $H$ has the same endpoints as it has in $G$.

---

Page 705

**Definition**

Let $G$ be a graph. Two **vertices $v$ and $w$ of $G$ are connected** if, and
only if, there is a walk from $v$ to $w$. The **graph $G$ is connected** if, and
only if, given any two vertices $v$ and $w$ in $G$, there is a walk from $v$ to
$w$. Symbolically:

$$ G \text{ is connected } \Leftrightarrow \forall \text{ vertices } v \text{ and } w \text{ in } G, \exists \text{ a walk from } v \text{ to } w $$

---

Page 706

**Lemma 10.1.1**

Let $G$ be a graph.

a. If $G$ is connected, then any two distinct vertices of $G$ can be connected
by a path.

b. If vertices $v$ and $w$ are part of a circuit in $G$ and one edge is removed
from the circuit, then there still exists a trail from $v$ to $w$ in $G$.

c. If $G$ is connected and $G$ contains a circuit, then an edge of the circuit
can be removed without disconnecting $G$.

---

Page 706

**Definition**

A graph $H$ is a **connected component** of a graph $G$ if, and only if,

1. $H$ is a subgraph of $G$;

2. $H$ is connected; and

3. no connected subgraph of $G$ has $H$ as a subgraph and contains vertices or
   edges that are not in $H$.

---

Page 707

**Definition**

Let $G$ be a graph. An **Euler circuit** for $G$ is a circuit that contains
every vertex and every edge of $G$. That is, an Euler circuit for $G$ is a
sequence of adjacent vertices and edges in $G$ that has at least one edge,
starts and ends at the same vertex, uses every vertex of $G$ at least once, and
uses every edge of $G$ exactly once.

---

Page 707

**Theorem 10.1.2**

If a graph has an Euler circuit, then every vertex of the graph has a positive
even degree.

**Proof:**

Suppose $G$ is a graph that has en Euler circuit. _[We must show that given any
vertex $v$ of $G$, the degree of $v$ is even.]_ Let $v$ be any particular but
arbitrarily chosen vertex of $G$. Since the Euler circuit contains every edge of
$G$, it contains all edges incident on $v$. Now imagine taking a journey that
begins in the middle of one of the edges adjacent to the start of the Euler
circuit and continues around the Euler circuit to end in the middle of the
starting edge. (See Figure 10.1.4. There is such a starting edge because the
Euler circuit has at least one edge.) Each time $v$ is entered by traveling
along one edge, it is immediately exited by traveling along another edge (since
the journey ends in the _middle_ of an edge).

(See Page 707 for Figure 10.1.4)

Because the Euler circuit uses every edge of $G$ exactly once, every edge
incident on $v$ is traversed exactly once in this process. Hence the edges
incident on $v$ occur in entry/exit pairs, and consequently the degree of $v$$
must be a positive multiple of $2$. But that means that $v$ has positive even
degree _[as was to be shown]_.

---

Page 707

**Contrapositive Version of Theorem 10.1.2**

If some vertex of a graph has odd degree, then the graph does not have an Euler
circuit.

---

Page 708

**Theorem 10.1.3**

If a graph $G$ is connected and the degree of every vertex of $G$ is a positive
even integer, then $G$ has an Euler circuit.

**Proof:**

Suppose that $G$ is any connected graph and suppose that every vertex of $G$ is
a positive even integer. _[We must find an Euler circuit for $G$.]_ Construct a
circuit $C$ by the following algorithm:

**Step 1:** Pick any vertex $v$ of $G$ at which to start.

_[This step can be accomplished because the vertex set of $G$ is nonempty by
assumption.]_

**Step 2:** Pick any sequence of adjacent vertices and edges, starting and
ending at $v$ and never repeating an edge. Call the resulting circuit $C$.

_[This step can be performed for the following reasons: Since the degree of each
vertex of $G$ is a positive even integer, as each vertex of $G$ is entered by
traveling on one edge, either the vertex is $v$ itself and there is no other
unused edge adjacent to $v$, or the vertex can be exited by traveling on another
previously unused edge. Since the number of edges of the graph is finite (by
definition of graph), the sequence of distinct edges cannot go on forever. The
sequence eventually returns to $v$ because the degree of $v$ is a positive even
integer, and so each time an edge leads out from $v$ to another vertex, there
must be a different edge that connects back to $v$.]_

**Step 3:** Check whether $C$ contains every edge and vertex of $G$. If so, $C$
is an Euler circuit, and we are finished. IF not, perform the following steps.

**Step 3a:** Remove all edges of $C$ from $G$ and also any vertices that become
isolated when the edges of $C$ are removed. Call the resulting subgraph $G'$.

_[Note that $G'$ may not be connected (as illustrated in Figure 10.1.5), but
every vertex of $G'$ has positive, even degree (since removing the edges of $C$
removes an even number of edges from each vertex, the difference of two even
integers is even, and isolated vertices with degree $0$ were removed).]_

(See Page 709 for Figure 10.1.5)

**Step 3b:** Pick any vertex $w$ common to both $C$ and $G'$.

_[There must be at least one such vertex since $G$ is connected. (See exercise
50.) (In Figure 10.1.5 there are two such vertices: $u$ and $w$.)]_

**Step 3c:** Pick any sequence of adjacent vertices and edges of $G'$, starting
and ending at $w$ and never repeating an edge. Call the resulting circuit $C'$.

_[This can be done since each vertex of $G'$ has positive, even degree and $G'$
is finite. See the justification for step 2.]_

**Step 3d:** Patch $C$ and $C'$ together to create a new circuit $C^n$ as
follows: Start at $v$ and follow $C$ all the way to $w$. Then follow $C'$ all
the way back to $w$. After that, continue along the untraveled portion of $C$ to
return to $v$.

_[The effect of executing steps 3c and 3d for the graph of Figure 10.1.5 is
shown in Figure 10.1.6.]_

(See Page 710 for Figure 10.1.6)

**Step 3e:** Let $C = C^n$ and go back to step 3.

Since the graph $G$ is finite, execution of the steps outlined in this algorithm
must eventually terminate. At that point an Euler circuit for $G$ will have been
constructed. (Note that because of the element of choice in steps 1, 2, 3b, and
3c, a variety of different Euler circuits can be produced using this algorithm.)

---

Page 711

**Theorem 10.1.4**

A graph $G$ has an Euler circuit if, and only if, $G$ is connected and every
vertex of $G$ has a positive even degree.

---

Page 711

**Definition**

Let $G$ be a graph, and let $v$ and $w$ be two distinct vertices of $G$. An
**Euler trail from $v$ to $w$** is a sequence of adjacent edges and vertices
that start at $v$, ends at $w$, passes through every vertex of $G$ at least
once, and traverses every edge of $G$ exactly once.

---

Page 712

**Corollary 10.1.5**

Let $G$ be a graph, and let $v$ and $w$ be two distinct vertices of $G$. There
is an Euler trail from $v$ to $w$ if, and only if, $G$ is connected, $v$ and $w$
have odd degree, and all other vertices of $G$ have positive even degree.

---

Page 713

**Definition**

Given a graph $G$, a **Hamiltonian circuit** for $G$ is a simple circuit that
includes every vertex of $G$. That is, a Hamiltonian circuit for $G$ is a
sequence of adjacent vertices and distinct edges in which every vertex of $G$
appears exactly once, except for the first and the last, which are the same.

---

Page 714

**Proposition 10.1.6**

If a graph $G$ has a Hamiltonian circuit, then $G$ has a subgraph $H$ with the
following properties:

1. $H$ contains every vertex of $G$.

2. $H$ is connected.

3. $H$ has the same number of edges as vertices.

4. Every vertex of $H$ has degree $2$.

---

Page 721

**Definition**

An $m \times n$ (read "$m$ by $n$") **matrix $A$ over a set $S$** is a
rectangular array of elements of $S$ arranged into $m$ rows and $n$ columns:

$$
\mathbf{A} = \left[\begin{array}{}
a_{11} && a_{12} && \cdots && a_{1j} && \cdots a_{1n} \\
a_{21} && a_{22} && \cdots && a_{2j} && \cdots a_{2n} \\
\vdots && \vdots && && \vdots && && \vdots \\
a_{i1} && a_{i2} && \cdots && a_{ij} && \cdots && a_{in} \\
\vdots && \vdots && && \vdots && && \vdots \\
a_{m1} && a_{m2} && \cdots && a_{mj} && \cdots && a_{mn} \\
\end{array}\right]
$$

We write $\mathbf{A} = (a_{ij})$

---

Page 722

**Definition**

Let $G$ be a directed graph with ordered vertices $v_1, v_2, \dots, v_n$. The
**adjacency matrix of $G$** is the $n \times n$ matrix $\mathbf{A} = (a_{ij})$
over the set of nonnegative integers such that

$$ a_{ij} = \text{ the number of arrows from } v_i \text{ to } v_j \text{ for all } i, j = 1, 2, \dots, n $$

---

Page 724

**Definition**

Let $G$ be an undirected graph with ordered vertices $v_1, v_2, \dots, v_n$. The
**adjacency matrix of $G$** is the $n \times n$ matrix $\mathbf{A} = (a_{ij})$
over the set of nonnegative integers such that

$$ a_{ij} = \text{ the number of edges connecting } v_i \text{ and } v_j $$

---

Page 724

**Definition**

An $n \times n$ square matrix $\mathbf{A} = (a_{ij})$ is called **symmetric**
if, and only if, for every $i$ and $j = 1, 2, \dots, n$,

$$ a_{ij} = a_{ji} $$

---

Page 726

**Theorem 10.2.1**

Let $G$ be a graph with connected components $G_1, G_2, \dots, G_k$. If there
are $n_i$ vertices in each connected component $G_i$ and these vertices are
numbered consecutively, then the adjacency matrix of $G$ has the form

$$
\left[\begin{array}{}
A_1 && \mathbf{O} && \mathbf{O} && \cdots && \mathbf{O} && \mathbf{O} \\
\mathbf{O} && A_2 && \mathbf{O} && \cdots && \mathbf{O} && \mathbf{O} \\
\mathbf{O} && \mathbf{O} && A_3 && \cdots && \mathbf{O} && \mathbf{O} \\
\vdots && \vdots && \vdots && && \vdots && \vdots \\
\mathbf{O} && \mathbf{O} && \mathbf{O} && \cdots && \mathbf{O} && A_k \\
\end{array}\right]
$$

where each $A_i$ is the $n_i \times n_i$ adjacency matrix of $G_i$, for every
$i = 1, 2, \dots, k$, and the $\mathbf{O}$'s represent matrices whose entries
are all $0$.

---

Page 726

**Definition**

Suppose that all entrices in matrices $\mathbf{A}$ and $\mathbf{B}$ are real
numbers. If the number of element, $n$, in the $i$th row of $\mathbf{A}$ equals
the number of elements in the $j$th column of $\mathbf{B}$, then the **scalar
product** or **dot product** of the $i$th row of $\mathbf{A}$ and the $j$th
column of $\mathbf{B}$ is the real number obtained as follows:

$$
\left[\begin{array}{}
a_{i1} && a_{i2} && \cdots && a_{in} \\
\end{array}\right]
\left[\begin{array}{}
b_{1j} \\
b_{2j} \\
\vdots \\
b_{nj}
\end{array}\right] =  a_{i1}b_{1j} + a_{i2}b_{2j} + \cdots + a_{in}b_{nj}
$$

---

Page 727

**Definition**

Let $\mathbf{A} = (a_{ij})$ be an $m \times k$ matrix and
$\mathbf{B} = (b_{ij})$ a $k \times n$ matrix with real entries. The (matrix)
product of $\mathbf{A}$ times $\mathbf{B}$, denoted $\mathbf{AB}$, is the matrix
$(c_{ij})$ defined as follows:

$$
\left[\begin{array}{}
a_{11} && a{12} && \cdots && a_{1k} \\
a_{21} && a{22} && \cdots && a_{2k} \\
\vdots && \vdots && && \vdots \\
a_{i1} && a{i2} && \cdots && a_{ik} \\
\vdots && \vdots && && \vdots \\
a_{m1} && a{m2} && \cdots && a_{mk} \\
\end{array}\right]
\left[\begin{array}{}
b_{11} && b{12} && \cdots && b_{1j} && \cdots && b_{1n} \\
b_{21} && b{22} && \cdots && b_{2j} && \cdots && b_{2n} \\
&& \cdot && && \cdot && && \cdot \\
&& \cdot && && \cdot && && \cdot \\
&& \cdot && && \cdot && && \cdot \\
b_{k1} && b{k2} && \cdots && b_{kj} && \cdots && b_{kn} \\
\end{array}\right] = \left[\begin{array}{}
c_{11} && c_{12} && \cdots && c_{1j} && \cdots && c_{1n} \\
c_{21} && c_{22} && \cdots && c_{2j} && \cdots && c_{2n} \\
\vdots && \vdots && && \vdots && && \vdots \\
c_{i1} && c_{i2} && \cdots && c_{ij} && \cdots && c_{in} \\
\vdots && \vdots && && \vdots && && \vdots \\
c_{m1} && c_{m2} && \cdots && c_{mj} && \cdots && c_{mn} \\
\end{array}\right]
$$

where

$$ c_{ij} = a_{i1}b_{1j} + a_{i2}b_{2j} + \cdots + a_{ik}b_{kj} = \sum_{r = 1}^{k}{a_{ir}b_{rj}} $$

for each $i = 1, 2, \dots, m$ and $j = 1, 2, \dots, n$.

---

Page 729

**Definition**

For each positive integer $n$, the $n \times n$ **identity matrix**, denoted
$\mathbf{I}_n = (\delta_{ij})$ or just $\mathbf{I}$ (if the size of the matrix
is obvious from context), is the $n \times n$ matrix in which all entries in the
main diagonal are $1$'s and all other entries are $0$'s. In other words,

$$
\delta_{ij} =
\begin{cases}
1 & \text{ if } i = j \\
0 & \text{ if } i \neq j
\end{cases}
\text{, for every } i, j = 1, 2, \dots, n
$$

---

Page 730

**Definition**

For any $n \times n$ matrix $\mathbf{A}$, the powers of $\mathbf{A}$ are defined
as follows:

$$ \mathbf{A}^0 = \mathbf{I} \quad \text{ where } \mathbf{I} \text{ is the } n \times n \text{ identity matrix} $$

$$ \mathbf{A}^n = \mathbf{A}\mathbf{A}^{n - 1} \quad \text{ for every integer } n \geq 1 $$

---

Page 732

**Theorem 10.2.2**

If $G$ is a graph with vertices $v_1, v_2, \dots, v_m$ and $\mathbf{A}$ is the
adjacency matrix of $G$, then for each positive integer $n$ and for all integers
$i, j = 1, 2, \dots, m$,

the $ij$th enter of $\mathbf{A}^n =$ the number of walks of length $n$ from
$v_i$ to $v_j$.

**Proof (by mathematical induction):**

Suppose $G$ is a graph with vertices $v_1, v_2, \dots, v_m$ and $\mathbf{A}$ is
the adjacency matrix of $G$. Let $P(n)$ be the sentence

For all integers $i, j = 1, 2, \dots, m$, the $ij$th entry of $\mathbf{A}^n =$
the number of walks of length $n$ from $v_i$ to $v_j$.

We will show that $P(n)$ is true for every integer $n \geq 1$.

_Show that $P(1)$ is true:_

The $ij$th entry of
$\mathbf{A}^1 = \text{ the } ij \text{th entry of } \mathbf{A}$

$$ \quad = \text{ the number of edges connecting } v_i \text{ to } v_j $$

$$ \quad = \text{ the number of walks of length } 1 \text{ from } v_i \text{ to } v_j $$

_Show that for every integer $k$ with $k \geq 1$, if $P(k)$ is true then
$P(k + 1)$ is true:_

Let $k$ be any integer with $k \geq 1$, and suppose that

For all integers $i, j = 1, 2, \dots m$, the $ij$th entry of $\mathbf{A}^k =$
the number of walks of length $k$ from $v_i$ to $v_j$

We must show that

For all integers $i, j = 1, 2, \dots, m$,

the $ij$the entry of $\mathbf{A}^{k + 1} =$ the number of walks of length
$k + 1$ from $v_i$ to $v_j$.

Let $\mathbf{A} = (a_{ij})$ and $\mathbf{A}^k = (b_{ij})$. Since
$\mathbf{A}^{k + 1} = \mathbf{A}\mathbf{A}^k$, the $ij$th entry of
$\mathbf{A}^{k + 1}$ is obtained by multiplying the $i$th row of $\mathbf{A}$ by
the $j$th column of $\mathbf{A}^k$:

the $ij$th entry of
$\mathbf{A}^{k +  1} = a_{i1}b_{1j} + a_{i2}b_{2j} + \cdots + a_{im}b_{mj}$

for every $i, j = 1, 2, \dots, m$. Now consider the individual term of this sum:
$a_{i1}$ is the number of edges from $v_i$ to $v_1$; and, by the inductive
hypothesis, $b_{1j}$ is the number of walks of length $k$ from $v_1$ to $v_j$.
Now any edge from $v_i$ to $v_1$ can be joined with any walk of length $k$ from
$v_1$ to $v_j$ to create a walk of length $k + 1$ from $v_i$ to $v_j$ with $v_1$
as its second vertex. Thus, by the multiplication rule,

$$ a_{i1}b_{1j} = \left[\text{ the number of walks of length } k + 1 \text{ from } v_i \text{ to } v_j \text{ that have } v_1 \text{ as their second vertex}\right] $$

$$ a_{ir}b_{rj} = \left[\text{ the number of walks of length } k + 1 \text{ from } v_i \text{ to } v_j \text{ that have } v_r \text{ as their second vertex}\right] $$

Because every walk of length $k + 1$ from $v_i$ to $v_j$ must have one of the
vertices $v_1, v_2, \dots, v_m$ as its second vertex, the total number of walks
of length $k + 1$ from $v_i$ to $v_j$ equals the sum in (10.2.1), which equals
the $ij$th entry of $\mathbf{A}^{k + 1}$. Hence

the $ij$th entry of $\mathbf{A}^{k + 1} =$ the number of walks of length $k + 1$
from $v_i$ to $v_j$ _[as was to be shown]._

_[Since both the basis step and the inductive step have been proved, the
sentence $P(n)$ is true for every integer $n \geq 1$.]_

---

Page 736

**Definition**

Let $G$ and $G'$ be graphs with vertex sets $V(G)$ and $V(G')$ and edge sets
$E(G)$ and $E(G')$, respectively. **$G$ is isomorphic to $G'$** if, and only if,
there exists one-to-one correspondences $g: V(G) \to V(G')$ and
$h: E(G) \to E(G')$ that preserve the edge-endpoint functions of $G$ and $G'$ in
the sense that for each $v \in V(G)$ and $e \in E(G)$,

$$ v \text{ is an endpoint of } e \Leftrightarrow g(v) \text{ is an endpoint of } h(e) $$

---

Page 738

**Theorem 10.3.1 Graph Isomorphism Is an Equivalence Relation**

Let $S$ be a set of graphs and let $R$ be the relation of graph isomorphism on
$S$. Then $R$ is an equivalence relation on $S$.

**Proof:**

_$R$ is reflexive:_

Given any graph $G$ in $S$, define a graph isomorphism from $G$ to $G$ by using
the identity functions on the set of vertices and on the set of edges of $G$.

_$R$ is symmetric:_

Given any graphs $G$ and $G'$ in $S$ such that $G$ is isomorphic to $G'$, we
must show that $G'$ is isomorphic to $G$.

This is true because if $g$ and $h$ are vertex and edge correspondences from $G$
to $G'$ that preserve the edge-endpoint functions, then $g^{-1}$ and $h^{-1}$
are vertex and edge correspondences from $G'$ to $G$ that preserve the
edge-endpoint functions.

_$R$ is transitive:_

Given any graphs $G$, $G'$, and $G''$ in $S$ such that $G$ is isomorphic to $G'$
and $G'$ is isomorphic to $G''$, we must show that $G$ is isomorphic to $G''$.

This follows from the fact that if $g_1$ and $h_1$ are vertex and edge
correspondences from $G$ to $G'$ that preserve the edge-endpoint functions of
$G$ and $G'$ and if $g_2$ and $h_2$ are vertex and edge correspondences from
$G'$ to $G''$ that preserve the edge-endpoint functions of $G'$ and $G''$, then
$g_2 \circ g_1$ and $h_2 \circ h_2$ are vertex and edge correspondences from $G$
to $G''$ that preserve the edge-endpoint functions of $G$ and $G''$.

---

Page 739

**Definition**

A property $P$ is called an **invariant for graph isomorphism** if, and only if,
given any graphs $G$ and $G'$, if $G$ has property $P$ and $G'$ is isomorphic to
$G$, then $G'$ has property $P$.

---

Page 739

**Theorem 10.3.2**

Each of the following properties is an invariant for graph isomorphism, where
$n$, $m$, and $k$ are all nonnegative integers:

1. has $n$ vertices

2. has $m$ edges

3. has a vertex of degree $k$

4. has $m$ vertices of degree $k$

5. has a circuit of length $k$

6. has a simple circuit of length $k$

7. has $m$ simple circuits of length $k$

8. is connected

9. has an Euler circuit

10. has a Hamiltonian circuit

---

Page 741

**Definition**

If $G$ and $G'$ are simple graphs, then **$G$ is isomorphic to $G'$** if, and
only if, there exists a one-to-one correspondence $g$ from the vertex set $V(G)$
of $G$ to the vertex set $V(G')$ of $G'$ that preserves the edge-endpoint
functions of $G$ and $G'$ in the sense that for all vertices $u$ and $v$ of $G$,

$$ \{u, v\} \text{ is an edge in } G \Leftrightarrow \{g(u), g(v)\} \text{ is an edge in } G' $$

---

Page 743

**Definition**

A graph is said to be *_circuit-free_ if, and only if, it has no circuits. A
graph is called a **tree** if, and only if, it is circuit-free and connected. A
**trivial tree** is a graph that consists of a single vertex. A graph is called
a **forest** if, and only if, it is circuit-free and not connected.

---

Page 747

**Lemma 10.4.1**

Any tree that has more than one vertex has at least one vertex of degree 1.

---

Page 747

**Proof (of Lemma 10.4.1)**

Let $T$ be a particular but arbitrarily chosen tree that has more than one
vertex, and consider the following algorithm:

**Step 1:** Pick a vertex $v$ of $T$ and let $e$ be an edge incident on $v$.

_[If there were no edge incident on $v$, then $v$ would be an isolated vertex.
But this would contradict the assumption that $T$ is connected (since it is a
tree) and has at least two vertices.]_

**Step 2:** While $\text{deg}(v) > 1$, repeat steps 2a, 2b, and 2c:

**Step 2a:** Choose $e'$ to be an edge incident on $v$ such that $e' \neq e$.
_[Since an edge exists because $\text{deg}(v) > 1$ and so there are at least two
edges incident on $v$.]_

**Step 2b:** Let $v'$ be the vertex at the other end of $e'$ from $v$. _[Since
$T$ is a tree, $e'$ cannot be a loop and therefore $e'$ has two distinct
endpoints.]_

**Step 2c:** Let $e = e'$ and $v = v'$. _[This is just a renaming process in
preparation for repeating step 2.]_

The algorithm just described must eventually terminate because the set of
vertices of the tree $T$ is finite and $T$ is circuit-free. When it does, a
vertex $v$ of degree 1 will have been found.

---

Page 748

**Definition**

Let $T$ be a tree. If $T$ has at least two vertices, then a vertex of degree 1
in $T$ is called a **leaf** (or a **terminal vertex**), and a vertex of degree
greater than 1 in $T$ is called an **internal vertex** (or a **branch vertex**).
The unique vertex in a trivial tree is also called a **leaf** or **terminal
vertex**.

---

Page 748

**Theorem 10.4.2**

For any positive integer $n$, any tree with $n$ vertices has $n - 1$ edges.

---

Page 749

**Proof (of Theorem 10.4.2) (by mathematical induction):**

Let the Property $P(n)$ be the sentence

Any tree with $n$ vertices has $n - 1$ edges.

We use mathematical induction to show that this property is true for every
integer $n \geq 1$.

_Show that $P(1)$ is true:_

Let $T$ be any tree with one vertex. Then $T$ has zero edges (since it contains
no loops.) Since $0 = 1 - 1$, then $P(1)$ is true.

_Show that for every integer $k \geq 1$, if $P(K)$ is true then $P(k + 1)$ is
true:_

Suppose $k$ is any positive integer for which $P(k)$ is true. In other words,
suppose that

Any tree with $k$ vertices has $k - 1$ edges.

This is the inductive hypothesis.

We must show that $P(k + 1)$ is true. In other words, we must show that

Any tree with $k + 1$ vertices has $(k + 1) - 1 = k$ edges.

Let $T$ be a particular but arbitrarily chosen tree with $k + 1$ vertices. _[We
must show that $T$ has $k$ edges.]_

Since $k$ is a positive integer, $(k + 1) \geq 2$, and so $T$ has more than one
vertex. Hence by Lemma 10.4.1, $T$ has a vertex $v$ of degree 1. Also, since $T$
has more than one vertex, there is at least one other vertex in $T$ besides $v$.
Thus there is an edge $e$ connecting $v$ to the rest of $T$. Define a subgraph
$T'$ of $T$ so that

$$ V(T') = V(T) - \{v\} \quad \text{ and } \quad E(T') = E(T) - \{e\} $$

Then

1. The number of vertices of $T'$ is $(k + 1) - 1 = k$.

2. $T'$ is circuit-free (since $T$ is circuit-free, and removing an edge and a
   vertex cannot create a circuit).

3. $T'$ is connected (see exercise 24 at the end of this section).

Hence, by the definition of tree, $T'$ is a tree. Since $T'$ has $k$ vertices,
by the inductive hypothesis

$$ \text{the number of edges of } T' = (\text{the number of vertices of } T') - 1 $$

$$  = k - 1 $$

It follows that

$$ \text{the number of edges of } T = (\text{the number of edges of } T') + 1 $$

$$ (k - 1) + 1 $$

$$ = k $$

_[This is what was to be shown.]_

---

Page 750

**Lemma 10.4.3**

If $G$ is any connected graph, $C$ is any circuit in $G$, and any one of the
edges of $C$ is removed from $G$, then the graph that remains is connected.

---

Page 751

**Proof (of Lemma 10.4.3):**

Suppose $G$ is a connected graph, $C$ is a circuit in $G$, and $e$ is an edge of
$C$. Form a subgraph $G'$ of $G$ by removing $e$ from $G$. Thus

$$ V(G') = V(G) $$

$$ E(G') = E(G) - \{e\} $$

We must show that $G'$ is connected. _[To show a graph is connected, we must
show that if $u$ and $w$ are any vertices of the graph, then there exists a walk
in $G'$ from $u$ to $w$.]_

Suppose $u$ and $w$ are any two vertices of $G'$. _[We must find a walk from $u$
to $w$.]_ Since the vertex sets of $G$ and $G'$ are the same, because $u$ and
$w$ are both vertices of $G$, and since $G$ is connected, there is a walk $W$ in
$G$ from $u$ to $w$.

_Case 1($e$ is not an edge of $W$):_ The only edge in $G$ that is not in $G'$ is
$e$, so in this case $W$ is also a walk in $G'$. Hence $u$ is connected to $w$
by a walk in $G'$.

_Case 2($e$ is an edge of $W$):_ In this case the walk $W$ from $u$ to $w$
includes a section of the circuit $C$ that contains $e$. Let $C$ be denoted as
follows:

$$ C: v_0e_1v_1e_2v_2 \cdots e_nv_n(=v_0) $$

Now $e$ is one of the edges of $C$, so, to be specific, let $e = e_k$. Then the
walk $W$ contains either the sequence

$$ v_{k - 1}e_kv_k \quad \text{ or } \quad v_ke_kv_{k - 1} $$

If $W$ contains $v_{k - 1}e_kv_k$, connect $v_{k - 1}$ to $v_k$ by taking the
"counterclockwise" walk $W'$ defined as follows:

$$ W': v_{k - 1}e_{k - 1}v_{k - 1} \cdots v_0e_nv_{n - 1} \cdots e_{k + 1}v_k \text{ where } v_n = 0 $$

An example showing how to go from $u$ to $w$ while avoiding $e_k$ is given in
Figure 10.4.4.

(See Page 752 for Figure 10.4.4)

If $W$ contains $v_ke_kv_{k - 1}$, connect $v_k$ to $v_{k - 1}$ by taking the
"clockwise" walk $W''$ defined as follows:

$$ W'': v_ke_{k + 1}v_{k + 1} \cdots v_ne_1v_1e_2 \cdots e_{k - 1}v_{k - 1} \text{ where } v_n = v_0 $$

Now patch either $W'$ or $W''$ into $W$ to form a new walk from $u$ to $w$. For
instance, to patch $W'$ into $W$, start with the section of $W$ from $u$ to
$v_{k - 1}$, then take $W'$ from $v_{k - 1}$ to $v_k$, and finally take the
section of $W$ from $v_k$ to $w$. If this new walk still contains an occurrence
of $e$, just repeat the process described previously until all occurrences are
eliminated. _[This must happen eventually since the number of occurrences of $e$
in $C$ is finite.]_ The result is a walk from $u$ to $w$ that does not contain
$e$ and hence is a walk in $G'$.

The previous arguments show that both in case 1 and in case 2 there is a walk in
$G'$ from $u$ to $w$. Since the choice of $u$ and $w$ was arbitrary, $G'$ is
connected.

---

Page 752

**Theorem 10.4.4**

For any positive integer $n$, if $G$ is a connected graph with $n$ vertices and
$n - 1$ edges, then $G$ is a tree.

**Proof:**

Let $n$ be a positive integer and suppose $G$ is a particular but arbitrarily
chosen graph that is connected and has $n$ vertices and $n - 1$ edges. _[We must
show that $G$ is a tree. Now a tree is a connected, circuit-free graph. Since we
already know $G$ is connected, it suffices to show that $G$ is circuit-free.]_

Suppose $G$ is not circuit-free. That is, suppose $G$ has a circuit $C$. _[We
must derive a contradiction.]_ By Lemma 10.4.3, an edge of $C$ can be removed
from $G$ to obtain a graph $G'$ that is connected. If $G'$ has a circuit, then
repeat this process:

Remove an edge of the circuit from $G'$ to form a new connected graph.

Continue repeating the process of removing edges from circuits until eventually
a graph $G''$ is obtained that is connected and is circuit-free.

By definition, $G''$ is a tree. Since no vertices were removed from $G$ to form
$G''$, $G''$ has $n$ vertices just as $G$ does.

Thus, by Theorem 10.4.2, $G''$ has $n - 1$ edges. But the supposition that $G$
has a circuit implies that at least one edge of $G$ is removed to form $G''$.
Hence $G''$ has no more than $(n - 1) - 1 = n - 2$ edges, which contradicts its
having $n - 1$ edges. So the supposition is false.

Hence $G$ is circuit-free, and therefore $G$ is a tree _[as was to be shown]_.

---

Page 753

**Corollary 10.4.5**

If $G$ is any graph with $n$ vertices and $m$ edges, where $m$ and $n$ are
positive integers and $m \geq n$, then $G$ has a circuit.

**Proof (by contradiction):**

Suppose not. That is, suppose there is a graph $G$ with $n$ vertices and $m$
edges, where $m$ and $n$ are positive integers and $m \geq n$, and suppose $G$
does not have a circuit. Let $G_1, G_2, \dots, G_k$ be the connected components
of $G$, and let $n_1, n_2, \dots, n_k$ be the number of vertices of
$G_1, G_2, \dots, G_k,$ respectively. Because $G_1, G_2, \dots, G_k$ are the
connected components of $G$,

$$ \sum_{i = 1}^{k}{n_i} = n $$

Since $G$ does not have a circuit, none of $G_1, G_2, \dots, G_k$ have circuits
either. So, since each is connected, each is a tree. By Theorem 10.4.4, the
number of edges of each $G_i$ is $n_{i - 1}$. Now because $G$ is composed of its
connected components,

$$ \text{the number of edges of } G = \sum_{i = 1}^{k}{(\text{the number of edges of } G_i)} $$

$$ = (n_1 - 1) + (n_1 - 1) + \cdots + (n_k  - 1) $$

$$ = (n_1 + n_2 + \cdots + n_k) - \underbrace{(1 + 1 + 1 + \cdots + 1)}_{k \text{ 1's}} $$

$$ = n - k $$

$$ < n $$

Thus the number of edges of $G$ is less than $n$, which contradicts the
hypothesis that the number of edges of $G$, namely, $m$, is greater than or
equal to $n$. Hence the supposition is false and $G$ has a circuit.

---

Page 756

**Definition**

A **rooted tree** is a tree in which there is one vertex that is distinguished
from the others and is called the **root**. The **level** of a vertex is the
number of edges along the unique path between it and the root. The **height** of
a rooted tree is the maximum level of any vertex of the tree. Given the root or
any internal vertex $v$ of a rooted tree, the **children** of $v$ are all those
vertices that are adjacent to $v$ and are one level farther away from the root
than $v$. If $w$ is a child of $v$, then $v$ is called the **parent** of $w$,
and two distinct vertices that are both children of the same parent are called
**siblings**. Given two distinct vertices $v$ and $w$, if $v$ lies on the unique
path between $w$ and the root, then $v$ is an **ancestor** of $w$ and $w$ is a
**descendant** of $v$.

---

Page 757

**Definition**

A **binary tree** is a rooted tree in which every parent has at most two
children. Each child in a binary tree is a designated either a **left child** or
a **right child** (but not both), and every parent has at most one left child
and one right child. A **full binary tree** is a binary tree in which each
parent has exactly two children.

Given any parent $v$ in a binary tree $T$, if $v$ has a left child, then the
**left subtree** of $v$ is the binary tree whose root is the left child of $v$,
whose vertices consist of the left child of $v$ and all its descendants, and
whose edges consist of all those edges of $T$ that connect the vertices of the
left subtree. The **right subtree** of $v$ is defined analogously.

---

Page 758

**Theorem 10.5.1**

If $k$ is a positive integer and $T$ is a full binary tree with $k$ internal
vertices, then (1) $T$ has a total of $2k + 1$ vertices, and (2) $T$ has $k + 1$
leaves.

**Proof:**

Suppose $k$ is a positive integer and $T$ is a full binary tree with $k$
internal vertices. (1) Observe that the set of all vertices of $T$ can be
partitioned into two disjoint subsets: the set of all vertices that have a
parent and the set of all vertices that do not have a parent. Now there is just
one vertex that does not have a parent, namely the root. Also, since every
internal vertex of a full binary tree has exactly two children, the number of
vertices that have a parent is twice the number of parents, or $2k$, since each
parent is an internal vertex. Hence

$$ \left[\text{the total number of vertices of } T\right] = \left[\text{the number of vertices that have a parent}\right] + \left[\text{the number of vertices that do not have a parent}\right] $$

(2) Because it is also true that the total number of vertices of $T$ equals the
number of internal vertices plus the number of leaves,

$$ \left[\text{the total number of vertices of } T\right] = \left[\text{the number of internal vertices}\right] + \left[\text{the number of leaves}\right] $$

$$  \quad = k + \left[\text{the number of leaves}\right] $$

Now equate the two expressions for the total number of vertices of $T$:

$$ 2k + 1 = k + \left[\text{the number of leaves}\right] $$

Solving this equation gives

$$ \left[\text{the number of leaves}\right] = (2k + 1) - k = k + 1 $$

Thus the total number of vertices is $2k + 1$ and the number of leaves is
$k + 1$ _[as was to be shown]_.

---

Page 759

**Theorem 10.5.2**

For every integer $h \geq 0$, if $T$ is any binary tree with height $h$ and $t$
leaves, then

$$ t \leq 2^h $$

Equivalently:

$$ \log_2t \leq h $$

**Proof (by strong mathematical induction):**

Let $P(h)$ be the sentence

If $T$ is any binary tree of height $h$, then $T$ has at most $2^h$ leaves.

_Show that $P(0)$ is true:_

We must show that if $T$ is any binary tree of height $0$, then $T$ has at most
$2^0$ leaves. Suppose $T$ is a tree of height $0$. Then $T$ consists of a single
vertex, the root. By definition this is also a leaf, and so the number of leaves
is $t = 1 = 2^0 = 2^h$. Hence $t \leq 2^h$ _[as was to be shown]_.

_Show that for every integer $k \geq 0$, if $P(i)$ is true for each integer $i$
from $0$ through $k$, then it is true for $k + 1$:_

Let $k$ be any integer with $k \geq 0$, and suppose that

For each integer $i$ from $0$ through $k$, if $T$ is any binary tree of height
$i$, then $T$ has at most $2^i$ leaves.

This is the inductive hypothesis.

We must show that

If $T$ is any binary tree of height $k + 1$, then $T$ has at most $2^{k + 1}$
leaves.

Let $T$ be a binary tree of height $k + 1$, root $v$ and $t$ leaves. Because
$k \geq 0$, we have that $k + 1 \geq 1$ and so $v$ has at least one child.

_Case 1 ($v$ has only one child):_

In this case, we may assume without loss of generality that $v$'s child is a
left child $v_L$, and that $v_L$ is the root of the subtree $T_L$ of $v$. (This
situation is illustrated in Figure 10.5.3.) Let $t_L$ be the number of leaves in
$T_L$. By inductive hypothesis, $t_L \leq 2^k$ because the height of $T_L$ is
one less than the height of $T$, which is $k + 1$. Also since the root $v$ has
only one child, $v$ is also a leaf, and hence the total number of leaves in $T$
is one more than the number of leaves in $T_L$. Finally $2^k \geq 2^0 = 1$
because $k \geq 0$.

Therefore,

$$ t = t_L + 1 \leq 2^k + 1 \leq 2^k + 2^k = 2 \cdot 2^k = 2^{(k + 1)} $$

(See page 750 for figure 10.5.3)

_Case 2 ($v$ has two children):_

In this case, $v$ has both a left child, $v_L$, and a right child, $v_R$, and
$v_L$ and $v_R$ are roots of a left subtree $T_L$ and a right subtree $T_R$.
Note that $T_L$ and $T_R$ are binary trees because $T$ is a binary tree. (This
situation is illustrated in Figure 10.5.4.)

(See page 750 for figure 10.5.4)

Let $t_L$ and $t_R$ be the numbers of leaves in $T_L$ and $T_R$, respectively,
and let $h_L$ and $h_R$ be the heights of $T_L$ and $T_R$, respectively. Because
$T$ has height $k + 1$, then $h_L \leq k$ and $h_R \leq k$, and so, by inductive
hypothesis,

$$ t_L \leq 2^{h_L} \quad \text{ and } \quad t_R \leq 2^{h_R} $$

Now the leaves of $T$ consist exactly of the leaves of $T_L$ together with the
leaves of $T_R$. Therefore,

$$ t = t_L + t_R \leq 2^{h_L} + 2^{h_R} $$

by the inductive hypothesis since $h_L \leq k$ and $h_R \leq k$.

Hence,

$$ t \leq 2^k + 2^k = 2 \cdot 2^k = 2^{k + 1} $$

by basic algebra.

Thus the number of leaves is at most $2^{kn + 1}$ _[as was to be shown]_.

Since both the basis step and the inductive step have been proved, we conclude
that for every integer $h \geq 0$, if $T$ is a binary tree with height $h$ and
$t$ leaves, then $t \leq 2^h$.

The equivalent inequality $\log_2t \leq h$ follows from the fact that the
logarithmic function with base $2$ is increasing. In other words, for all
positive real numbers $x$ and $y$,

$$ \text{if } x < y \text{ then } \log_2x < \log_2y $$

Thus if we apply the logarithmic function with base $2$ to both sides of

$$ t \leq 2^h $$

we obtain

$$ \log_2t \leq \log_2\left(2^h\right) $$

Now by definition of logarithm, $\log_2\left(2^h\right) = h$ _[because
$\log_2\left(2^h\right)$ is the exponent to which $2$ must be raised to obtain
$2^h$]_. Hence

$$ \log_2t \leq h $$

_[as was to be shown]_.

---

Page 761

**Corollary 10.5.3**

A full binary tree of height $h$ has $2^h$ leaves.

---

Page 762

**Algorithm 10.5.1 Building a Binary Search Tree**

**Input:** A totally ordered, nonempty set $K$ of keys

**Algorithm Body:**

Initialize $T$ to have one vertex, the root, and no edges. Choose a key from $K$
to insert into the root.

$\textbf{while} \text{ (there are still keys to be added)}\\ \ \ \text{Choose a key, } \textit{newkey} \text{, from } K \text{ to add. Let the root be called } v \text{, let } \textit{key(v) } \text{be} \\ \ \ \text{the key at the root, and let } \textit{success } = 0\text{.}\\ \ \ \ \ \textbf{while (} \textit{success } = 0\text{)}\\ \ \ \ \ \ \ \ \ \textbf{if (} \textit{newkey } < \textit{ key(v)}\text{)}\\ \ \ \ \ \ \ \ \ \ \ \textbf{then if } \text{(} v \text{ has a left child), call the left child } v_L \text{ and let } v := v_L\\ \ \ \ \ \ \ \ \ \ \ \textbf{else do } \text{1. add a vertex } v_L \text{ to } T \text{ as the left child for } v\\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \text{2. add an edge to } T \text{ to join } v \text{ to } v_L\\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \text{3. insert } \textit{newkey } \text{ as the key for } v_L\\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \text{4. let } \textit{success } := 1 \textbf{ end do}\\ \ \ \ \ \ \ \ \ \textbf{if (} \textit{newkey} > \textit{key(v)}\\ \ \ \ \ \ \ \ \ \ \ \textbf{then if } v \text{ has a right child}\\ \ \ \ \ \ \ \ \ \ \ \ \ \textbf{then } \text{call the right child } v_R \text{, and let } v := v_R\\ \ \ \ \ \ \ \ \ \ \ \ \ \textbf{else do } \text{1. add a vertex } v_R \text{ to } T \text{ as the right child for } v\\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \text{2. add an edge to } T \text{ to join } v \text{ to } v_R\\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \text{3. insert } \textit{newkey } \text{ as the key for } v_R\\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \text{4. let } \textit{success } := 1 \textbf{ end do}\\ \ \ \ \ \textbf{end while}\\ \ \textbf{end while}$

**Output:** A binary search tree $T$ for the set $K$ of keys

---

Page 766

**Definition**

A **spanning tree** for a graph $G$ is a subgraph of $G$ that contains every
vertex of $G$ and is a tree.

---

Page 766

**Proposition 10.6.1**

1. Every connected graph has a spanning tree.

2. Any two spanning trees for a graph have the same number of edges.

**Proof of part (1) of Proposition 10.6.1:**

Suppose $G$ is a connected graph. If $G$ is circuit-free, then $G$ is its own
spanning tree and we are done. If not, then $G$ has at least one circuit $C_1$.
By Lemma 10.4.3, the subgraph of $G$ obtained by removing an edge from $C_1$ is
connected. If this subgraph is circuit-free, then it is a spanning tree and we
are done. If not, then it has at least one circuit $C_2$, and, as above, an edge
can be removed from $C_2$ to obtain a connected subgraph. Continuing in this
way, we can remove successive edges from circuits, until eventually we obtain a
connected, circuit-free subgraph $T$ of $G$. _[This must happen at some point
because the number of edges of $G$ is finite, and at no stage does removal of an
edge disconnect the subgraph.]_ Also, $T$ contains every edge of $G$ because no
vertices of $G$ were removed in constructing it. Thus $T$ is a spanning tree for
$G$.

---

Page 768

**Definition and Notation**

A **weighted graph** is a graph for which each edge has an associated positive
real number **weight**. The sum of the weights of all the edges is the **total
weight** of the graph. A **minimum spanning tree** for a connected, weighted
graph is a spanning tree that has the least possible total weight compared to
all other spanning trees for the graph.

If $g$ is a weighted graph and $e$ is an edge of $G$, then $w(e)$ denotes the
weight of $e$ and $w(G)$ denotes the total weight of $G$.

---

Page 768

**Algorithm 10.6.1 Kruskal**

**Input:** $G$ _[a connected, weighted graph with $n$ vertices, where $n$ is a
positive integer]_

**Algorithm Body:**

_[Build a subgraph $T$ of $G$ to consist of all the vertices of $G$ with edges
added in order of increasing weight. At each stage, let $m$ be the number of
edges of $T$.]_

1. Initialize $T$ to have all the vertices of $G$ and no edges.

2. Let $E$ be the set of all edges of $G$, and let $m := 0$.

3. $\textbf{while } (m < n - 1)$

3a. Find an edge $e$ in $E$ of least weight.

3b. Delete $e$ from $E$.

3c. $\textbf{if }$ addition of $e$ to the edge set of $T$ does not produce a
circuit $\textbf{then }$ add $e$ to the edge set of $T$ and set $m := m + 1$

$\textbf{end while}$

**Output:** $T$ _[$T$ is a minimum spanning tree for $G$]_

---

Page 770

**Theorem 10.6.2 Correctness of Kruskal's Algorithm**

When a connected, weighted graph is input to Kruska's algorithm the output is a
minimum spanning tree.

**Proof:**

Suppose that $G$ is a connected, weighted graph with $n$ vertices and that $T$
is a subgraph of $G$ produced when $G$ is input to Kruskal's algorithm. Clearly
$T$ is circuit-free _[since no edge that completes a circuit is ever added to
$T$]_. Also, $T$ is connected. For as long as $T$ has more than one connected
component, the set of edges of $G$ that can be added to $T$ without creating a
circuit is nonempty. _[The reason is that since $G$ is connected, given any
vertex $v_1$ in one connected component $C_1$ of $T$ and any vertex $v_2$ in
another connected component $C_2$, there is a path in $G$ from $v_1$ to $v_2$.
Since $C_1$ and $C_2$ are distinct, there is an edge $e$ of this path that is
not in $T$. Adding $e$ to $T$ does not create a circuit in $T$, because deletion
of an edge from a circuit does not disconnect a graph and deletion of $e$
would.]_ The preceding arguments show that $T$ is circuit-free and connected.
Since by construction $T$ contains every vertex of $G$, $T$ is a spanning tree
for $G$.

Next we show that $T$ has minimum weight. Let $T_1$ be any minimum spanning tree
for $G$ such that the number of edges $T_1$ and $T$ have in common is a maximum.
Suppose that $T \neq T_1$. Then there is an edge $e$ in $T$ that is not an edge
of $T_1$. _[Since trees $T$ and $T_1$ both have the same vertex set, if they
differ at all, they must have different, but same-size, edge sets.]_ Now adding
$e$ to $T_1$ produces a graph with a unique circuit (see exercise 19 at the end
of this section). Let $e'$ be an edge of this circuit such that $e'$ is not in
$T$. _[Such an edge must exist because $T$ is a tree and hence circuit-free.]_
Let $T_2$ be the graph obtained from $T_1$ by removing $e'$ and adding $e$. This
situation is illustrated below.

(See Page 771 for image of graph.)

Note that $T_2$ has $n - 1$ edges and $n$ vertices and that $T_2$ is connected
_[since by Lemma 10.4.3 the subgraph obtained by removing an edge from a circuit
in a connected graph is connected]_. Consequently, $T_2$ is a spanning tree for
$G$. In addition,

$$ w(T_2) = w(T_1) - w(e') + w(e) $$

Now $w(e) \leq w(e')$ because at the stage in Kruskal's algorithm when $e$ was
added to $T$, $e'$ was available to be added _[since it was not already in $T$,
and at that stage its addition could not produce a circuit since $e$ was not in
$T$]_, and $e'$ would have been added had its weight been less than that of $e$.
Thus

$$ w(T_2) = w(T_1) - \underbrace{[w(e') - w(e)]}_{\geq 0} $$

$$ \quad \leq w(T_1) $$

But $T_1$ is a minimum spanning tree. So since $T_2$ is a spanning tree with
weight less than or equal to the weight of $T_1$, $T_2$ is also a minimum
spanning tree for $G$.

Finally, note that by construction, $T_2$ has one more edge in common with $T$
than $T_1$ does, which contradicts the choice of $T_1$ as a minimum spanning
tree for $G$ with a maximum number of edges in common with $T$. Thus the
supposition that $T \neq T_1$ is false, and hence $T$ itself is a minimum
spanning tree for $G$.

---

Page 771

**Algorithm 10.6.2**

**Input:** $G$ _[a connected, weighted graph with $n$ vertices where $n$ is a
positive integer]_

**Algorithm Body:**

_[Build a subgraph $T$ of $G$ by starting with any vertex $v$ of $G$ and
attaching edges (with endpoints) one by one to an as-yet-unconnected vertex of
$G$, each time choosing an edge of least weight that is adjacent to a vertex of
$T$.]_

1. Pick a vertex $v$ of $G$ and let $T$ be the graph with one vertex, $v$, and
   no edges.

2. Let $V$ be the set of all vertices of $G$ except $v$.

3. $\textbf{for } i := 1 \textbf{ to } n - 1$

3a. Find an edge $e$ of $G$ such that (1) $e$ connects $T$ to one of the
vertices in $V$ and, (2) $e$ has the least weight of all edges connecting $T$ to
a vertex in $V$. Let $w$ be the endpoint of $e$ that is in $V$.

3b. Add $e$ and $w$ to the edge and vertex sets of $T$, and delete $w$ from $V$.

$\textbf{next } i$

**Output:** $T$ _[$T$ is a minimum spanning tree for $G$.]_

---

Page 773

**Theorem 10.6.3 Correctness of Prim's Algorithm**

When a connected, weighted graph $G$ is input to Prim's algorithm, the output is
a minimum spanning tree for $G$.

**Proof:**

Let $G$ be a connected, weighted graph, and suppose $G$ is input to Prim's
algorithm. At each stage of execution of the algorithm, an edge must be found
that connects a vertex in a subgraph to a vertex outside the subgraph. As long
as there are vertices outside the subgraph, the connectedness of $G$ ensures
that such an edge can always be found. _[For if one vertex in the subgraph and
one vertex outside it are chosen, then by the connectednedss of $G$ there is a
walk in $G$ linking the two. As one travels along this walk, at some point one
moves along ane dge from a vertex inside the subgraph to a vertex outside the
subgraph.]_

Now it is clear that the output $T$ of Prim's algorithm is a tree because the
edge and vertex added to $T$ at each stage are connected to other edges and
vertices of $T$ and because at no stage is a circuit created since each edge
added connects vertices in two disconnected sets. _[Consequently, removal of a
newly added edge produces a disconnected graph, whereas by Lemma 10.4.3, removal
of an edge from a circuit produces a connected graph.]_ Also, $T$ includes every
vertex of $G$ because $T$, being a tree with $n - 1$ edges, has $n$ vertices
_[and that is all $G$ has]_. Thus $T$ is a spanning tree for $G$.

Next we show that $T$ has minimum weight. Suppose there is a minimum spanning
tree for $G$, $T_1$, such that the number of edges $T_1$ and $T$ have in common
is a maximum, but $T \neq T_1$. Then there is an edge $e$ in $T$ that is not an
edge of $T_1$. _[Since trees $T$ and $T_1$ both have the same vertex set if they
differ at all, they must have different, same-sized edge sets.]_ Of all such
edges, let $e$ be the last that was added when $T$ was constructed using Prim's
algorithm. Let $S$ be the set of vertices of $T$ just before the addition of
$e$. Then one endpoint, say $v$ of $e$, is in $S$ and the other, say $w$, is
not. Since $T_1$ is a spanning tree, there is a path in $T_1$ joining $v$ to
$w$. And since $v \in S$ and $w \notin S$,, as one travels along this path, one
must encounter an edge $e'$ that joins a vertex in $S$ to one that is not in $S$
and that therefore is not in $T$ because $e$ was the last edge added to $T$. Now
at the stage when $e$ was added to $T$, $e'$ could have been added and it
_would_ have been added instead of $e$ had its weight been less than that of
$e$. Since $e'$ was not added at that stage, we conclude that

$$ w(e') \geq w(e) $$

Let $T_2$ be the graph obtained from $T_1$ by removing $e'$ and adding $e$.
_[Thus $T_2$ has one more edge in common with $T$ than $T_2$ does.]_ Note that
$T_2$ is a tree. The reason is that since $e'$ is a part of a path in $T_1$ from
$v$ to $w$, and $e$ connects $v$ and $w$, adding $e$ to $T_1$ creates a circuit.
When $e'$ is removed from this circuit, the resulting subgraph remains connected
and has the same number of edges as $T$. In fact, $T_2$ is a spanning tree for
$G$ since no vertices were removed in forming $T_2$ from $T_1$. The argument
showing that $w(T_2) \leq w(T_1)$ is left as an exercise. _[It is virtually
identical to part of the proof of Theorem 10.6.2.]_ It follows that $T_2$ is a
minimum spanning tree for $G$.

By construction, $T_2$ has one more edge in common with $T$ than $T_1$ does,
which contradicts the choice of $T_1$ as a minimum spanning tree for $G$, not
equal to $T$, with a maximum number of edges in common with $T$. It follows that
$T = T_1$, and hence $T$ itself is a minimum spanning tree for $G$.

---

Page 775

**Algorithm 10.6.3 Dijkstra**

**Input:** $G$ _[a connected simple graph with a positive weight for every
edge]_, $\infty$ _[a number greater than the sum of the weights of all the edges
in the graph]_, $w(u, v)$ _[the weight of edge $\{u, v\}$]_, $a$ _[the starting
vertex]_, $z$ _[the ending verte]_

**Algorithm Body:**

1. Initialize $T$ to be the graph with vertex $a$ and no edges. Let $V(T)$ be
   the set of vertices of $T$, and let $E(T)$ be the set of edges of $T$.

2. Let $L(a) = 0$, and for all vertices in $G$ except $a$, let $L(u) = \infty$.
   _[The number $L(x)$ is called the label of $x$.]_

3. Initialize $v$ to equal $a$ and $F$ to be $\{a\}$. _[The symbol $v$ is used
   to denote the vertex most recently added to $T$.]_

4. $\textbf{while } (z \notin V(T))$

4a.
$F : = (F - \{v\}) \cup \{\text{vertices that are adjacent to } v \text{ and are not in } V(T)\}$
_[The set $F$ is called the fringe. Each time a vertex is added to $T$, it is
removed from the fringe and the vertices adjacent to it are added to the fringe
if they are not already in the fringe or the tree $T$.]_

4b. For each vertex $u$ that is adjacent to $v$ and is not in $V(T)$,

$\textbf{if } L(v) + w(v, u) < L(u) \textbf{ then}$

$$ L(u) := L(v) + w(v, u) $$

$$ D(u) := v $$

_[Note that adding $v$ to $T$ does not affect the labels of any vertices in the
fringe $F$ except those adjacent to $v$. Also, when $L(u)$ is changed to a
smaller value, the notation $D(u)$ is introduced to keep track of which vertex
in $T$ gave rise to the smaller value.]_

4c. Find a vertex $x$ in $F$ with the smallest label

Add vertex $x$ to $V(T)$, and add edge $\{D(x), x\}$ to $E(T)$

$v := x$ _[This statement sets up the notation for the next iteration of the
loop.]_

$\textbf{end while}$

**Output:** $L(z)$ _[$L(z)$, a nonnegative integer, is the length of the
shortest path from $a$ to $z$.]_

---

Page 778

**Theorem 10.6.4 Correctness of Dijkstra's Algorithm**

When a connected, simple graph with a positive weight for every edge is input to
Dijkstra's algorithm, with starting vertex $a$ and ending vertex $z$, the output
is the length of a shortest path from $a$ to $z$.

**Proof:**

Let $G$ be a connected, weighted graph with no loops or parallel edges and with
a positive weight for every edge. Let $T$ be the graph built up by Dijkstra's
algorithm, and for each vertex $u$ in $G$, let $L(u)$ be the label given by the
algorithm to vertex $u$. For each integer $n \geq 0$, let the property $P(n)$ be
the sentence

After the $n$th iteration of the while loop in Dijkstra's algorithm, (1) $T$ is
a tree, and (2) for every vertex $v$ in $T$, $L(v)$ is the length of a shortest
path in $G$ from $a$ to $v$.

We will show by mathematical induction that $P(n)$ is true for each integer $n$
from $0$ through the termination of the algorithm.

_Show that $P(0)$ is true:_ When $n = 0$, the graph $T$ is a tree because it is
defined to consist only of the vertex $a$ and no edges. In addition, $L(a)$ is
the length of the shortest path from $a$ to $a$ because the initial value of
$L(a)$ is $0$.

_Show that for every integer $k \geq 0$, if $P(k)$ is true then $P(k + 1)$ is
also true:_

Let $k$ be any integer with $k \geq 0$ and suppose that

After the $k$th iteration of the while loop in Dijkstra's algorithm, (1) $T$ is
a tree, and (2) for every vertex $v$ in $T$, $L(v)$ is the length of the
shortest path in $G$ from $a$ to $v$.

This is the inductive hypothesis.

We must show that

After the $(k + 1)$st iteration of the **while** loop in Dijkstra's algorithm,
(1) $T$ is a tree, and (2) for every vertex $v$ in $T$, $L(v)$ is the length of
the shortest path in $G$ from $a$ to $v$.

Suppose that after the $(k + 1)$st iteration of the **while** loop in Dijkstra's
algorithm, the vertex $v$ and edge $\{x, v\}$ have been added to $T$, where $x$
is in $V(T)$. Clearly the new value of $T$ is a tree because adding a new vertex
to a tree along with the edge leading to it neither creates a circuit nor
disconnects the tree. By inductive hypothesis, for each vertex $y$ that is in
the tree before the addition of $v$, $L(y)$ is the length of a shortest path
from $a$ to $y$. So it remains only to show that $L(v)$ is the length of a
shortest path from $a$ to $v$.

Now, according to the algorithm, the final value of $L(v) = L(x) + w(x, v)$.
Consider _any_ shortest path from $a$ to $v$, and let $\{s, t\}$ be the first
edge in the path to leave $T$, where $s \in V(T)$ and $t \notin V(T)$. This
situation is illustrated below.

(See page 779 for image.)

Let $\text{LSP}(a, v)$ be the length of a shortest path from $a$ to $v$, and let
$\text{LSP}(a, s)$ be the length of the shortest path from $a$ to $s$. Observe
that

$$ \text{LSP}(a, v) \geq \text{LSP}(a, s) + w(s, t) $$

because the path from $t$ to $v$ has length $\geq 0$

$$ \quad \geq L(s) + w(s, t) $$

by inductive hypothesis because $s$ is a vertex in $T$

$$ \quad \geq L(x) + w(x, v) $$

$t$ is in the fringe of the tree, and so if $L(s) + w(s, t)$ were less than
$L(x) + w(x, v)$ then $t$ would have been added to $T$ instead of $r$.

On the other hand,

$$ L(x) + w(x, v) \geq \text{LSP}(a, v) $$

because $L(x) + w(x, v)$ is the length of a path from $a$ to $v$ and so it is
greater than or equal to the length of the shortest path from $a$ to $v$.

Because both $\text{LSP}(a, v) \geq L(x) + w(x, v)$ and
$L(x) + w(x, v) \geq \text{LSP}(a, v)$, we have that

$$ \text{LSP}(a, v) = L(x) + w(x, v) $$

And since it is also the case that

$$ L(v) = L(x) + w(x, v) $$

we conclude that

$$ L(v) = \text{LSP}(a, v) $$

Therefore, $L(v)$ is the length of a shortest path from $a$ to $v$, which
completes the proof by mathematical induction.

The algorithm terminates as soon as $z$ is in $T$, and, since we have proved
that the label of every vertex in the tree gives the length of the shortest path
to it from $a$, then, in particular, $L(z)$ is the length of a shortest path
from $a$ to $z$.
