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
