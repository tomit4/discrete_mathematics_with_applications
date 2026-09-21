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

An $n \times n$ square matrix $\mathbf{A} = (a_{ij})$ is called **symetric** if,
and only if, for every $i$ and $j = 1, 2, \dots, n$,

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
