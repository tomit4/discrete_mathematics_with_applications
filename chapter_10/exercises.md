Page 716

**Exercise Set 10.1**

1. In the graph below, determine whether the following walks are trails, paths,
   closed walks, circuits, simple circuits, or just walks.

a. $v_0e_1v_1e_{10}v_5e_9v_2e_2v_1$

trail (has a repeated vertex, no repeated edge, not a circuit)

b. $v_4e_7v_2e_9v_5e_{10}v_1e_3v_2e_9v_5$

end point not the same as start -> no -> not a closed walk, circuit, nor simple
circuit

repeated edge -> yes, $e_9$, repeated vertex -> yes, $v_2$, therefore -> walk

c. $v_2$

no edges -> therefore, not circuit/simple circuit

starts and ends at same point -> yes -> therefore, not path

therefore -> both trail, closed walk

d. $v_5v_2v_3v_4v_4v_5$

repeated vertex -> yes, $v_4, v_5$, so not path

first and last only repeated vertex -> no, $v_4$, so not simple circuit.

repeated edges -> yes, $v_2v_3$ and $v_3v_4$ has repeated edge, so not trail.

begin and end the same -> yes -> circuit

so -> circuit

e. $v_2v_3v_4v_5v_2v_4v_3v_2$

repeated vertex -> yes, $v_2$, $v_4$, $v_3$, not first and last only -> not
path, not simple circuit.

repeated edges -> yes, $v_2v_3$ and $v_3v_4$ -> not trail, not path, not
circuit.

-> closed walk

f. $e_5e_8e_{10}e_3$

repeated edge -> no -> ...

repeated vertex -> no -> ...

starts and ends at the same point -> no -> not closed walk, circuit, simple
circuit

-> path

(See Page 716 for image of graph.)

2. In the graph below, determine whether the following walks are trails, paths,
   closed walks, circuits, simple circuits, or just walks.

a. $v_1e_2v_2e_3v_3e_4v_4e_5v_2e_2v_1e_1v_0$

repeated vertices -> yes; not path

repeated edges -> yes; not path; not trail; not circuit

starts and ends same vertex -> no; not closed walk, not circuit, not simple
circuit

-> walk

b. $v_2v_3v_4v_5v_2$

this is: $v_2e_3v_3e_4v_4e_6v_5e_7v_2$

repeated vertices -> yes; first and last only; not path, simple circuit

repeated edges -> no;

starts and ends same vertex -> yes; closed walk, circuit, simple circuit

-> simple circuit

c. $v_4v_2v_3v_4v_5v_2v_4$

$v_4e_5v_2e_3v_3e_4v_4e_6v_5e_7v_2e_5v_4$

repeated vertices -> yes; not path;

repeated edges -> yes; not trail, not circuit;

starts and ends same vertex -> yes;

-> closed walk

d. $v_2v_1v_5v_2v_3v_4v_2$

$v_2e_2v_1e_9v_5e_7v_2e_3v_3e_4v_4e_5v_2$

repeated vertices -> yes; not path;

only repeated vertices start and finish -> no; not simple circuit

repeated edges -> no;

starts and ends same vertex -> yes;

circuit

e. $v_0v_5v_2v_3v_4v_2v_1$

$v_0e_8v_5e_7v_2e_3v_3e_4v_4e_5v_2e_2v_1$

repeated vertices -> yes, $v_2$; not path

repeated edge -> no;

start and finish repeated vertices? -> no, not simple circuit, not closed walk;
not circuit;

trail (repeated vertex + no repeated edge)

f. $v_5v_4v_2v_1$

$v_5e_6v_4e_5v_2e_2v_1$

repeated vertices -> no; not circuit, closed path, simple circuit

repeated edges -> no;

path (no repeated vertex + no repeated edge);

(See Page 716 for image of graph.)

3. Let $G$ be the graph

(See Page 716 for image of graph.)

and consider the walk $v_1e_1v_2e_2v_1$.

a. Can this walk be written unambiguously as $v_1v_2v_1$? Why?

No, because $v_1v_2v_1$ could mean either $v_1e_1v_2e_2v_1$ or
$v_1e_2v_2e_1v_1$, which are different walks.

b. Can this walk be written unambiguously as $e_1e_2$? Why?

Yes, as $e_1e_2$ can only mean the walk $v_1e_1v_2e_2v_1$.

4. Consider the following graph.

(See Page 716 for image of graph.)

a. How many paths are there from $v_1$ to $v_4$?

Recall that a path contains no repeated edges (trail) nor repeated vertexes
(path).

Thus the paths are:

$v_1e_1v_2e_2v_3e_5v_4$, $v_1e_2v_2e_3v_3e_5v_4$, $v_1e_1v_2e_4v_3e_5v_4$

So there are 3 paths.

b. How many trails are there from $v_1$ to $v_4$?

$3! + 3 = 9 $

The $3$ paths from part a are also trails, and there are $3!$ trails with
vertices $v_1, v_2, v_3, v_2, v_3, v_4$. Remember, with a trail you can repeat
visits to each vertex as long as you don't traverse the same edge.

c. How many walks are there from $v_1$ to $v_4$?

Infinite, since on a walk you can repeat as many visits to any vertex and edge
as you like, so one could continually visit $v_2,v_3,v_1$ as many times as you'd
like before arriving at $v_4$.

5. Consider the following graph.

(See Page 716 for image of graph.)

a. How many paths are there from $a$ to $c$?

path -> no repeated edges (trail) + no repeated vertices (path).

There are 4 possible paths: $ae_1be_5c$, $ae_2be_5c$, $ae_3be_5c$, $ae_4be_5c$.

b. How many trails are there from $a$ to $c$?

trail -> no repeated edges

$4! + 4 = 28$, for similar reasons as exercise 4b.

c. How many walks are there from $a$ to $c$?

Infinite, for similar reasons as exercise 4c.

6. An edge whose removal disconnects the graph of which it is a part is called a
   **bridge.** Find all bridges for each of the graphs at the top of the next
   page.

a. (See Page 717 for image of graph.)

$$ \{v_1, v_3\}, \{v_2, v_3\}, \{v_4, v_3\}, \{v_5, v_3\} $$

b. (See Page 717 for image of graph.)

$$ \{v_1, v_2\}, \{v_7, v_8\}, \{v_3, v_4\} $$

c. (See Page 717 for image of graph.)

$$ \{v_9, v_{10}\}, \{v_6, v_7\}, \{v_7, v_8\}, \{v_2, v_3\} $$

7. Given any positive integer $n$, (a) find a connected graph with $n$ edges
   such that removal of just one edge disconnects the graph; (b) find a
   connected graph with $n$ edges that cannot be disconnected by the removal of
   a single edge.

a. Consider a simple line graph with $n$ edges and $n + 1$ vertices,
$v_1e_1v_2e_2v_3 \cdots v_{n}e_{n}v_{n + 1}$, then removing any one edge would
disconnect the graph as it would break the line.

b. Consider a graph in which it is closed loop with $n$ edges and $n$ vertices:
$v_1e_1v_2e_2 \cdots v_ne_nv_1$. Then, removing any one edge would not
disconnect the graph as there would still be at least one other edge connecting
the vertices.

8. Find the number of connected components for each of the following graphs.

a. (See Page 717 for image of graph.)

$$ \{a, b, c, d\}, \{e\}, \{f, g, h\} $$

b. (See Page 717 for image of graph.)

$$ \{u, w, y\}, \{z, v, x\} $$

c. (See Page 717 for image of graph.)

$$ \{a, b, d, e\}, \{c, i, j, h\}, \{f, g\} $$

d. (See Page 717 for image of graph.)

$$ \{v_1, v_3\}, \{v_2, v_4\} $$

9. Each of (a) - \(c\) describes a graph. In each case answer _yes_, _no_, or
   _not necessarily_ to this question: Does the graph have an Euler circuit?
   Justify your answers.

Recall that a graph $G$ has an Euler circuit if, and only if, $G$ is connected
and every vertex of $G$ has a positive even degree.

a. $G$ is a connected graph with five vertices of degrees $2, 2, 3, 3$, and $4$.

No, as vertices with degree $3$ violate the definition of having an Euler
circuit.

b. $G$ is a connected graph with five vertices of degrees $2, 2, 4, 4$, and $6$.

Yes, as it is a connected graph where all vertices have an even degree.

c. $G$ is a graph with five vertices of degrees $2, 2, 4, 4$, and $6$.

Not necessarily, since $G$ is not defined as a connected graph, but has vertices
all of which have an even degree, it cannot be determined if $G$ has an Euler
Circuit or not.

10. The solution for Example 10.1.6 shows a graph for which every vertex has
    even degree but which does not have an Euler circuit. Give another example
    of a graph satisfying these conditions.

Consider a similar example to 10.1.6, but instead of loops two separate
triangles are presented:

$$ v_1e_1v_2e_2v_3e_3v_1, v_4e_4v_5e_5v_6e_6v_4 $$

As you can see, the graph's vertices all have an even degree, but the graph is
disconnected since it is two triangles that have no edge in common. Hence this
graph does not have an Euler circuit.

11. Is it possible for a citizen of Konigsberg to make a tour of the city and
    cross each bridge exactly twice? (See Figure 10.1.1.) Explain.

Yes, as stated in the original Konigsberg problem establishes that the total
number of arrivals and departures from all vertices must be even, and since
every edge (bridge) must be traversed twice, this guarantees that it is possible
to take a tour of the city with crossing each bridge exactly twice, since any
number multiplied by 2 is even. Note that this question is in essence asking us
if there exists an Euler Circuit in the modified graph of the Konisberg map
where each edge is doubled.

Determine which of the graphs in 12-17 have Euler circuits. If the graph does
not have an Euler circuit, explain why not. If it does have an Euler circuit,
describe one.

Recall that a graph $G$ has an Euler circuit if, and only if, $G$ is connected
and every vertex of $G$ has a positive even degree.

12. (See Page 717 for image of graph.)

Yes, this graph is connected and every vertex has an even degree.

One such circuit is:

$v_1e_1v_2e_4v_3e_5v_4e_7v_5e_2v_2e_3v_5e_6v_4e_8v_1$

13. (See Page 717 for image of graph.)

No, this graph is connected, but multiple vertices have an odd degree. These are
$v_1$, with a degree of 5, $v_7$, with a degree of 3, $v_8$, with a degree of 3,
and $v_9$ with a degree of 3.

14. (See Page 717 for image of graph.)

Yes, this graph is connected and every vertex has an even degree.

One such circuit is:

$$ abihbchgcdgfdefia $$

15. (See Page 717 for image of graph.)

Yes, this graph is connected and every vertex has an even degree.

One such circuit is:

$$r zyxwyuzsuwvutsr $$

16. (See Page 717 for image of graph.)

No, this graph is disconnected, $\{v_0, v_2, v_4\}, \{v_1, v_5, v_3\}$.

17. (See Page 717 for image of graph.)

No, this graph is connected, but the degrees of vertices $C$ and $D$ are odd.

18. Is it possible to take a walk around the city whose map is shown below,
    starting and ending at the same point and crossing each bridge exactly once?
    If so, how can this be done?

(See Page 717 for image of city.)

If thought as a graph, each city point being a vertex and each bridge being an
edge, one can see that each vertex has an even number of edges, and also that
the graph is connected, thus there exists an Euler circuit and therefore there
exists such a walk as presented in the problem statement:

$$ BDEACDAB $$

For each of the graphs in 19-21, determine whether there is an Euler trail from
$u$ to $w$. If there is, find such a trail.

Recall Corollary 10.1.5:

Let $G$ be a graph, and let $v$ and $w$ be two distinct vertices of $G$. There
is an Euler trail from $v$ to $w$ if, and only if, $G$ is connected, $v$ and $w$
have odd degree, and all other vertices of $G$ have positive even degree.

19. (See Page 718 for image of graph.)

Yes, there is two points, $u$ with a degree of 3, and $w$ with a degree of 3,
and every other vertex has a positive even degree. Thus, there exists an Euler
trail from $u$ to $w$ (or from $w$ to $u$).

One such trail is:

$$ uv_7v_0v_1uv_2v_3v_4v_2v_6v_4wv_6v_5w $$

20. (See Page 718 for image of graph.)

No, there exists no Euler trail as there are more than 2 vertices that have an
odd degree, all vertices with odd degrees are: $u, f, e, h, w$.

21. (See Page 718 for image of graph.)

Yes, there exists an Euler trail as there are two vertices with odd degree, $u$
and $w$, and every other vertex has an even degree. One such Euler trail is:

$$ uv_0v_7v_6v_3uv_1v_2v_3v_4v_6wv_5v_4w $$

22. The following is a floor plan of a house. Is it possible to enter the house
    in room $A$, travel through every interior doorway of the house exactly
    once, and exit out of room $E$? If so, how can this be done?

(See Page 718 for image.)

Yes, it is possible, each room has an even number of interior doorways (edges)
except for $A$ and $E$ (since their other doorways are not interior, _i.e._ an
entrance for $A$ and an exit for $E$), and all rooms (vertices) are connected by
an even number of interior doorways. Thus an Euler trail does exist.

One such trail/traversal is:

$$ AHGDCBFE $$

23. Find all subgraphs of each of the following graphs.

a. (See Page 718 for image of graph.)

$$ v_1, v_2, v_1v_2, v_1e_1v_2, v_1e_2v_2, v_1e_1v_2e_2v_1 $$

b. (See Page 718 for image of graph.)

$$ v_0, v_1, v_0v_1, v_0v_1 \to v_1, v_0 \to v_1, v_1 \to v_1, v_0 \to v_1 \to v_1, $$

c. (See Page 718 for image of graph.)

$$ v_1, v_2, v_3, v_1v_2, v_2v_3, v_1v_3, v_1 \to v_2, v_2 \to v_3, v_1 \to v_3, v_1 \to v_2 \to v_3, v_2 \to v_3 \to v_1, v_3 \to v_1 \to v_2, v_1 \to v_2 \to v_3 \to v_1 $$

---

Page 718

**Definition**:

If $G$ is a simple graph, the **complement of $G$ denoted $G'$**, is obtained as
follows: The vertex set of $G'$ is identical to the vertex set of $G$. However,
two distinct vertices $v$ and $w$ of $G'$ are connected by an edge if, and only
if, $v$ and $w$ are not connected by an edge in $G$. For example, if $G$ is the
graph

(See Page 718 for image of graph.)

then $G'$ is

(See Page 718 for image of graph.)

---

24. Find the complement of each of the following graphs.

a. (See Page 718 for image of graph.)

(Done by hand.)

b. (See Page 718 for image of graph.)

(Done by hand.)

25.

a. Find the complement of the graph $K_4$, the complete graph on four vertices.

This graph is simply four disconnected vertices.

b. Find the complement of the graph $K_{3, 2}$, the complete bipartite graph on
$(3, 2)$ vertices.

This complement graph is a union of two separate graphs, a triangle $K_3$ and a
line $K_2$.

26. Suppose that in a group of five people $A, B, C, D$, and $E$ the following
    pairs of people are acquainted with each other.

$A$ and $C$, $A$ and $D$, $B$ and $C$, $C$ and $D$, $C$ and $E$.

a. Draw a graph to represent this situation.

(Done by hand.)

b. Draw a graph that illustrates who among these five people are _not_
acquainted. That is, draw an edge between two people if, and only if, they are
not acquainted.

(Done by hand.)

27. Let $G$ be a simple graph with $n$ vertices. What is the relation between
    the number of edges of $G$ and the number of edges of the complement $G'$?

_Hint:_ Consider the graph obtained by taking the vertices and edges of $G$ plus
all the edges of $G'$.

By definition of a graph's complement, $G'$ has all the edges that $G$ does not
between any two vertices. Therefore, if all the edges of $G$ and $G'$ are
plotted together, it should present a graph with all possible edges between any
two vertices, which is a complete graph.

Let $K_n$ be this complete graph on $n$ vertices. By definition of a complete
graph, it is known that $K_n$ has $\dfrac{n(n - 1)}{2}$ edges total. Therefore,
the number of edges of $G$ plus the number of edges of $G'$ equals
$\dfrac{n(n - 1)}{2}$.

28. Show that at a party with at least two people, there are at least two mutual
    acquaintances or at least two mutual strangers.

**Proof:**

Suppose that there is a party with $n$ people present, where $n \geq 2$.

Pick any person $p_i$. There are $n - 1$ remaining people, and $p_i$ either
knows or doesn't know each of them. By the pigeonhole principle, at least
$\left\lceil \dfrac{(n - 1)}{2} \right\rceil$ of them fall into the same
category - call this group $S$.

_Case ($S$ is a group of acquaintances of $p_i$):_

If any two people in $S$ know each other, then they are mutual acquaintances.

If no one in $S$ knows each other, then there are at least two people in $S$
that are mutual strangers.

_Case ($S$ is a group of strangers of $p_i$):_

If any two people in $S$ don't know each other, then they are mutual strangers.
If all people in $S$ do know each other, then there are at least two people in
$S$ that are mutual acquaintances.

In both cases, there exists at least two mutual acquaintances or two mutual
strangers at the party.

Q.E.D.

Find Hamiltonian circuits for each of the graphs in 29 and 30.

29. (See Page 719 for image of graph.)

$v_0v_1v_3v_4v_5v_2v_6v_7v_0$

30. (See Page 719 for image of graph.)

$alkjedcfihgba$

Show that none of the graphs in 31-33 has a Hamiltonian circuit.

Recall that:

If a graph $G$ has a Hamiltonian circuit, then $G$ has a subgraph $H$ with the
following properties:

    1. $H$ contains every vertex of $G$.

    2. $H$ is connected.

    3. $H$ has the same number of edges as vertices.

    4. Every vertex of $H$ has degree $2$.

31. (See Page 719 for image of graph.)

_Hint:_ See the solution to Example 10.1.9.

**Proof (by contradiction):**

Suppose not, that is, suppose there exists some Hamiltonian circuit $H$, a
subgraph of the shown graph, denoted $G$, that fulfills the four properties of a
Hamiltonian circuit (see page 714).

By property 1, $H$ has all 7 vertices of $G$, denoted $(a, b, c, d, e, f, g)$.
By property 2, $H$ is connected. By property 3 $H$ has the same number of edges
as vertices, _i.e._ 7 edges. By property 4, every vertex of $H$ has a degree
of 2.

Since the degree of $c$ in $G$ is 5, 3 edges incident on $c$ must be removed
from $G$ to create $H$. $Edge $\{b, c\}$ cannot be removed, because then $b$
would have a degree of 1. This logic also applies to edges
$\{d, c\}, \{f, c\}, \{g, c\}$. It follows that the degree of $c$ cannot be
reduced to 2, which contradicts property 4 of a Hamiltonian circuit.

Thus it has been shown that the supposition is false, and therefore there does
not exist a Hamiltonian circuit for the shown graph.

Q.E.D.

32. (See Page 719 for image of graph.)

**Proof (by contradiction):**

Suppose not, that is, suppose there exists some Hamiltonian circuit $H$, a
subgraph of the shown graph, denoted $G$, that fulfills the four properties of a
Hamiltonian circuit (see page 714).

By property 1, $H$ has all 10 vertices of $G$, denoted
$(a, b, c, d, e, f, g, h, i, j)$. By property 2, $H$ is connected. By property 3
$H$ has the same number of edges as vertices, _i.e._ 10 edges. By property 4,
every vertex of $H$ has a degree of 2.

Since the degree on $h$ is 4, 2 edges incident on $h$ must be removed from $G$
to create $H$. Edge $\{g, h\}$ cannot be removed because then $g$ would have a
degree of $1$.

It follows that the degree of $h$ cannot be reduced to 2, which contradicts
property 4 of a Hamiltonian circuit.

Thus it has been shown that the supposition is false, and therefore there does
not exist a Hamiltonian circuit for the shown graph.

Q.E.D.

33. (See Page 719 for image of graph.)

**Proof (by contradiction):**

Suppose not, that is, suppose there exists some Hamiltonian circuit $H$, a
subgraph of the shown graph, denoted $G$, that fulfills the four properties of a
Hamiltonian circuit (see page 714).

By property 1, $H$ has all 7 vertices of $G$, denoted $(A, B, C, D, E, F, G)$.
By property 2, $H$ is connected. By property 3 $H$ has the same number of edges
as vertices, _i.e._ 7 edges. By property 4, every vertex of $H$ has a degree
of 2.

Since the degree on $B$ is 5, 3 edges incident on $B$ must be removed from $G$
to create $H$. Edge $\{A, B\}$ cannot be removed because then $A$ would have a
degree of $1$.

It follows that the degree of $B$ cannot be reduced to 2, which contradicts
property 4 of a Hamiltonian circuit.

Thus it has been shown that the supposition is false, and therefore there does
not exist a Hamiltonian circuit for the shown graph.

Q.E.D.

In 34-37, find Hamiltonian circuits for those graphs that have them. Explain why
the other graphs do not.

34. (See Page 719 for image of graph.)

_Hint:_ This graph does not have a Hamiltonian circuit.

This graph does not have a Hamiltonian circuit because it violates property 4 of
a Hamiltonian circuit. Notice $b$ has a degree of 3, but reducing it to 2 to
create a Hamiltonian circuit would result in either $a$ or $c$ or $d$ having a
degree of 1.

35. (See Page 719 for image of graph.)

Yes, this graph has a Hamiltonian circuit. One such circuit is:

$abcdefga$

36. (See Page 719 for image of graph.)

Yes, this graph has a Hamiltonian circuit. One such circuit is:

$v_1v_5v_4v_7v_6v_2v_3v_0v_1$

37. (See Page 719 for image of graph.)

This graph has no Hamiltonian circuit. As the shown graph's vertex $a$ has a
degree 3, which must be reduced to 2. To accomplish this, only edge $\{a, e\}$
can be removed as removing $\{a, b\}$ or $\{a, d\}$ will cause either $b$ or $d$
to have degree 1. Similarly, $c$ has a degree 3, where only $\{c, f\}$ can be
removed, as $\{c, d\}$ and $\{c, b\}$ would cause either $d$ or $b$ to have
degree 1.

Once this is done, one would have a Hamiltonian circuit, but removing $\{a, e\}$
and $\{c, f\}$ causes the resulting graph to be disconnected (into two
disconnected subgraphs, $abcd$ and $efgh$). This violates property 2 of a
Hamiltonian circuit.

Therefore it can be concluded that there is no Hamiltonian circuit in the shown
graph.

38. Give two examples of graphs that have Euler circuits but not Hamiltonian
    circuits.

(Done by hand.)

39. Give two examples of graphs that have Hamiltonian circuits but not Euler
    circuits.

(Done by hand.)

40. Give two examples of graphs that have circuits that are both Euler circuits
    and Hamiltonian circuits.

(Done by hand.)

41. Give two examples of graphs that have Euler circuits and Hamiltonian
    circuits that are not the same.

Omitted.

42. A traveler in Europe wants to visit each of the cities shown on the map
    exactly once, starting and ending in Brussels. The distance (in kilometers)
    between each pair of cities is given in the table. Find a Hamiltonian
    circuit that minimizes the total distance traveled. (Use the map to narrow
    the possible circuits down to just a few. Then use the table to find the
    total distance for each of those.)

(See Page 719 for image of map.)

|            | Berlin | Brussels | Dusseldorf | Luxenbourg | Munich |
| ---------- | ------ | -------- | ---------- | ---------- | ------ |
| Brussels   | 783    |          |            |            |        |
| Dusseldorf | 564    | 223      |            |            |        |
| Luxembourg | 764    | 219      | 224        |            |        |
| Munich     | 585    | 771      | 613        | 517        |        |
| Paris      | 1,057  | 308      | 497        | 375        | 832    |

Some possible Hamiltonian circuits are:

$$ Br \to Lu \to Du \to Be \to Mu \to Pa \to Br = 219 + 224 + 564 + 585 + 832 + 308 = 2732 $$

$$ Br \to Du \to Lu \to Be \to Mu \to Pa \to Br = 223 + 224 + 764 + 585 + 832 + 308 = 2936 $$

$$ Br \to Pa \to Lu \to Du \to Be \to Mu \to Br = 308 + 375 + 224 + 564 + 585 + 771 = 2827 $$

$$ Br \to Pa \to Lu \to Mu \to Be \to Du \to Br = 308 + 375 + 517 + 585 + 564 + 223 = 2572 $$

Thus $Br \to Pa \to Lu \to Mu \to Be \to Du \to Br$ is the shortest Hamiltonian
circuit.

43.

a. Prove that if a walk in a graph contains a repeated edge, then the walk
contains a repeated vertex.

**Proof:**

Suppose $G$ is a graph and $W$ is a walk in $G$ that contains a repeated edge
$e$. Let $v$ and $w$ be the endpoints of $e$. In the case that $v = w$, then $v$
is a repeated vertex of $W$. In the case that $v \neq w$, then one of the
following must occur:

(1) $W$ contains two copies f $vew$ or of $wev$ (for instance, $W$ might contain
a section of the form $vewe'vew$, as illustrated below); (2) $W$ contains
separate sections of the form $vew$ and $wev$ (For instance, $W$ might contain a
section of the form $vewe'wev$ as illustrated below); or (3) $W$ contains a
section of the form $vewev$ or of the form $wevew$ (as illustrated below).

In cases (1) and (2), both vertices $v$ and $w$ are repeated, and in case (3),
one of $v$ or $w$ is repeated.

In all cases, there is at least one vertex in $W$ that is repeated.

Q.E.D.

b. Explain how it follows from part (a) that any walk with no repeated vertex
has no repeated edge.

By part (a), it has been shown that if a walk in a graph contains a repeated
edge, then the walk contains a repeated vertex. It follows, by the laws of
propositional logic, that the contrapositive statement is also true. That is,
that if a walk contains no repeated vertex, then the graph has no repeated edge.

44. Prove Lemma 10.1.1(a): If $G$ is a connected graph, then two distinct
    vertices of $G$ can be connected by a path. (You may use the result stated
    in exercise 43.)

**Proof:**

Suppose $G$ is any graph such that $G$ is connected.

Let $v$ and $w$ be any two distinct vertices of $G$.

It must be shown that $v$ and $w$ can be connected by a path.

In the case that there is only a single edge from $v$ to $w$, then they are
connected by a walk with no repeated vertex, which is a trail.

In the case that there are a series of vertices and edges in between $v$ and
$w$, recursively delete all recurring vertices until only distinct vertices
between $v$ and $w$ remain. Then $v$ and $w$ are connected by a walk with no
repeated vertex, which is a trail.

The resulting trail has no repeating edges by exercise 43(b), and thus the
resulting trail is a path.

This is what was to be shown.

Q.E.D.

45. Prove Lemma 10.1.1(b): If vertices $v$ and $w$ are part of a circuit in a
    graph $G$ and one edge is removed from the circuit, then there still exists
    a trail from $v$ to $w$ in $G$.

**Proof:**

Suppose $G$ is any graph. Let $C$ be a circuit in $G$, where $v$ and $w$ are
part of $C$, and $v \neq w$. Furthermore, let $e$ represent an edge removed from
$C$.

It must be shown that there exists a trail from $v$ to $w$ in $G$.

Since $v$ and $w$ are part of $C$, and $v \neq w$, it follows that there exists
$n$ edges, where $n \geq 2$, such that $C$ can be expressed as
$ve_1v_1e_2v_2 \dots e \dots w \dots v$ or
$ve_1v_1e_2v_2 \dots w \dots e \dots v$.

In either case, once $e$ is removed, the remaining $C$ is expressed as
$ve_1v_1e_2v_2 \dots w \dots v$.

It follows that there exists a trail from $v$ to $w$ in $G$ after $e$ has been
removed from $C$.

This is what was to be shown.

Q.E.D.

46. Draw a picture to illustrate Lemma 10.1.1\(c\): If a graph $G$ is connected
    and $G$ contains a circuit, then an edge of the circuit can be removed
    without disconnecting $G$.

(Done by hand.)

47. Prove that if there is a trail in a graph $G$ from a vertex $v$ to a vertex
    $w$, then there is a trail from $w$ to $v$.

**Proof:**

Suppose $G$ is any graph. Let $T$ be a trail in $G$ that is a walk from $v$ to
$w$.

If $v = w$, then there exists a trail from $w$ to $v$, namely $T$.

If $v \neq w$, then there exist $n$ edges from $v$ to $w$, where $n \geq 1$,
such that $T$ can be expressed as:

$$ ve_1v_1e_2v_2 \dots e_nw $$

By the definition of trail, $T$ has no repeated edges, and thus a reverse trail
from $w$ to $v$ exists, which can be expressed as:

$$ we_n \dots v_2e_2v_1e_1v $$

This is what was to be shown.

Q.E.D.

48. If a graph contains a circuit that starts and ends at a vertex $v$, does the
    graph contain a simple circuit that starts and ends at $v$? Why?

_Hint:_ Look at the answer to exercise 46 and use the fact that all graphs have
finite number of edges.

Suppose a graph $G$ contains a circuit that starts and ends at vertex $v$.

If $v$ is the only vertex in the circuit, then the circuit is a loop, which is a
simple circuit.

In every other case, there exists $n \geq 2$ other vertices. Now remove all
repeated vertices and their incident edges. Note that each time a vertex
repeats, the circuit can be split into a smaller circuit at that vertex.

By the definition of a graph, the amount of edges removed will be finite.

The resulting circuit will be a simple circuit.

Q.E.D.

49. Prove that if there is a circuit in a graph that starts and ends at a vertex
    $v$ and if $w$ is another vertex in the circuit, then there is a circuit in
    the graph that starts and ends at $w$.

**Proof:**

Suppose that there is a circuit in a graph that starts and ends at a vertex $v$.
Furthermore, suppose $w$ is another vertex in the circuit.

It must be shown that there is a circuit in the graph that starts and ends at
$w$.

Since the circuit starts and ends at $v$ and $w$ is a vertex in the same
circuit, the circuit can be expressed as:

$$ ve_1v_1e_2v_2 \dots w \dots v $$

Since all circuits are closed walks, it follows that there exists a circuit that
can be expressed starting and ending at $w$ such that:

$$ w \dots ve_1v_1e_2v_2 \dots w $$

This is what was to be shown.

Q.E.D.

50. Let $G$ be a connected graph, and let $C$ be any circuit in $G$ that does
    not contain every vertex of $G$. Let $G'$ be the subgraph obtained by
    removing all the edges of $C$ from $G$ and also any vertices that become
    isolated when the edges of $C$ are removed. Prove that there exists a vertex
    $v$ such that $v$ is in both $C$ and $G'$.

**Proof:**

Let $G$ be a connected graph and let $C$ be a circuit in $G$. Let $G'$ be the
subgraph obtained by removing all the edges of $C$ from $G$ and also any
vertices that become isolated when the edges of $C$ are removed.

_[We must show that there exits a vertex $v$ such that $v$ is in both $C$ and
$G'$.]_

Pick any vertex $v$ of $C$ and any vertex $w$ of $G'$. Since $G$ is connected,
there is a path from $v$ to $w$ (by Lemma 10.1.1(a)):

$$ \underbrace{v}_{\text{in } C} = v_0e_1v_1e_2v_2 \dots v_{i - 1}\underbrace{e_iv_ie_i}_{\text{in } C} + \underbrace{v_{i + 1}}_{\text{not in } C} \dots v_{n - 1}e_nv_n = \underbrace{w}_{\text{ in } G'} $$

Let $i$ be the largest subscript such that $v_i$ is in $C$.

If $i = n$, then $v_n = w$ is in $C$ and also in $G'$, and we are done.

If $i < n$, then $v_i$ is in $C$ and $v_{i + 1}$ is not in $C$. This implies
that $e_{i + 1}$ is not in $C$ (for if it were, both endpoints would be in $C$
by definition of circuit). Hence when $G'$ is formed by removing the edges and
resulting isolated vertices from $G$, then $e_{i + 1}$ is not removed. That
means that $v_i$ does not become an isolated vertex, so $v_i$ is not removed
either. Hence $v_i$ is in $G'$.

Consequently, $v_i$ is in both $C$ and $G'$ _[as was to be shown]._

Q.E.D.

51. Prove that any graph with an Euler circuit is connected.

**Proof:**

Suppose $G$ is a graph with an Euler circuit.

It must be shown that $G$ is connected.

If $G$ has only one vertex, then $G$ is automatically connected.

Otherwise, let $v$ and $w$ be any two vertices of $G$. By definition of an Euler
circuit, $v$ and $w$ must appear at least once in the Euler circuit that is in
$G$.

The section of the circuit between the first occurrence of one of $v$ or $w$ and
the first occurrence of the other is a walk from one of the two vertices to the
other.

Since the choice of $v$ and $w$ was arbitrary, given any two vertices in $G$
there is a walk from one to the other. This means that $G$ is connected.

Q.E.D.

52. Prove Corollary 10.1.5.

**Corollary 10.1.5**

Let $G$ be a graph, and let $v$ and $w$ be two distinct vertices of $G$. There
is an Euler trail from $v$ to $w$ if, and only if, $G$ is connected, $v$ and $w$
have odd degree, and all other vertices of $G$ have positive even degree.

**Proof:**

Suppose $G$ is any graph, and let $v$ and $w$ be two distinct vertices of $G$.

It must be shown that there is an Euler trail from $v$ to $w$ if, and only if,
$G$ is connected, $v$ and $w$ have odd degree, and all other vertices of $G$
have positive even degree.

_Proof (1<sup>st</sup> proposition):_

Suppose there is an Euler trail from $v$ to $w$.

It must be shown that $G$ is connected, $v$ and $w$ have odd degree, and all
other vertices of $G$ have a positive even degree.

Since there is an Euler trail from $v$ to $w$, this means that there is a series
of $n \geq 1$ edges from $v$ to $w$ such that the trail passes through each edge
of $G$ exactly once. It follows that there exists a walk from $v$ to $w$, and
this means that $G$ is connected.

Each time a trail visits a vertex, it both enters and exits, which means that
there is an even amount of degrees for every vertex.

The exception to this is both $v$ and $w$, which are the vertices that are the
beginning and the end of the trail respectively. $v$ is exited without entering,
meaning that $v$ has an odd number of degrees, and similarly $w$ is entered
without exiting, and also has an odd number of degrees.

Thus $v$ and $w$ have odd degree, and all other vertices of $G$ have a positive
even degree.

This is what was to be shown.

_Proof (2<sup>nd</sup> proposition):_

Suppose that $G$ is connected, $v$ and $w$ have odd degree, and all other
vertices of $G$ have a positive even degree.

It must be shown that there is an Euler trail from $v$ to $w$.

In other words, it must be shown that there exists a trail that starts at $v$
and ends at $w$, passes through every vertex of $G$ at least once, and traverses
every edge of $G$ exactly once (by the definition of Euler trail).

Let $e'$ be an added edge between $v$ and $w$, then the degree of $v$ and $w$ is
even (since an odd integer plus 1 is even). Then, by Theorem 10.1.3, this new
graph has an Euler circuit. That is, this new graph has a circuit that has at
least one edge, starts and ends at the same vertex, uses every vertex of the
graph at least once, and uses every edge of the graph exactly once.

If $e'$ is now removed, then the circuit is broken, then $v$ and $w$ now once
again have an odd degree, and the other two conditions for an Euler circuit
remain, which in turn define a trail that fulfills the properties of an Euler
trail.

This is what was to be shown.

_Conclusion:_

Since both propositions have been shown, it follows that there is an Euler trail
from $v$ to $w$ if, and only if, $G$ is connected, $v$ and $w$ have odd degree,
and all other vertices of $G$ have positive even degree.

Q.E.D.

53. For what values of $n$ does the complete graph $K_n$ with $n$ vertices have
    (a) an Euler circuit? (b) a Hamiltonian circuit? Justify your answers.

a.

Since $K_n$ is a complete graph with $n$ vertices, this means that every vertex
is connected to every other vertex. In other words, ever vertex connects to
$n - 1$ vertices, and thus every vertex has $n - 1$ degrees.

By definition of an Euler circuit, if $K_n$ has an Euler circuit, $K_n$ must be
connected (which is true since $K_n$ is complete).

Additionally, if $K_n$ has an Euler circuit, then every vertex must have an even
degree. Thus every vertex must have $2k$ degrees, for some integer $k$.

Equating $n - 1$ with $2k$ yields this expression:

$$ n - 1 = 2k $$

Then, evaluating for $n$ yields:

$$ n = 2k + 1 $$

This means that $n$ must be an odd positive integer, and therefore all values of
$n$ for $K_n$ such that $K_n$ has an Euler circuit are $n \geq 3$, where $n$ is
an odd integer.

b.

Since $K_n$ is a complete graph with $n$ vertices, this means that every vertex
is connected to every other vertex. In other words, ever vertex connects to
$n - 1$ vertices, and thus every vertex has $n - 1$ degrees.

By property 4 of Proposition 10.1.6, a Hamiltonian circuit must have a degree of
$2$.

Equating the degree of every vertex in $K_n$ to $2$ yields:

$$ n - 1 = 2 $$

Then, solving for $2$:

$$ n = 3 $$

For any $n \geq 3$, a Hamiltonian circuit can always be constructed in $K_n$ by
visiting each vertex exactly once in sequence and returning to the start, since
$K_n$ contains all necessary edges by definition of a complete graph.

54. For what values of $m$ and $n$ does the complete bipartite graph on $(m, n)$
    vertices have (a) an Euler circuit? (b) a Hamiltonian circuit? Justify your
    answers.

Omitted.

55. What is the maximum number of edges a simple disconnected graph with $n$
    vertices can have? Prove your answer.

Omitted.

56.

a. Prove that if $G$ is any bipartite graph, then every circuit in $G$ has an
even number of edges.

Omitted.

b. Prove that if $G$ is any graph with at least two vertices and if $G$ does not
have a circuit with an odd number of edges, then $G$ is bipartite.

Omitted.

57. An alternative proof for Theorem 10.1.3 has the following outline. Suppose
    $g$ is a connected graph in which every vertex has even degree. Suppose the
    path $C: v_1e_1v_2e_2v_3 \dots e_nv_{n + 1}$ has maximum length in $G$. That
    is, $C$ has at least as many vertices and edges as any other path in $G$.
    First derive a contradiction from the assumption that $v_1 \neq v_n$. Next
    let $H$ be the subgraph of $G$ that contains all the vertices and edges in
    $C$. Then derive a contraction from the assumption that $H \neq G$. Show
    that $H$ contains every vertex of $G$, and show that $H$ contains every edge
    of $G$.

---

Page 733

**Exercise Set 10.2**

1. Find real numbers $a$, $b$, and $c$ such that the following are true.

a.

$$
\left[\begin{array}{}
a + b && a - c \\
c && b - a \\
\end{array}\right] =
\left[\begin{array}{}
1 && 0 \\
-1 && 3 \\
\end{array}\right]
$$

The four equalities are:

$$ a + b = 1 $$

$$ a - c = 0 $$

$$ c = -1 $$

$$ b - a = 3 $$

Therefore:

$$ a - c = 0 $$

$$ a - (-1) = 0 $$

$$ a + 1 = 0 $$

$$ a = -1 $$

and:

$$ a + b = 1 $$

$$ (-1) + b = 1 $$

$$ b - 1 = 1 $$

$$ b = 2 $$

Checking other equalities:

$$ b - a = 3 $$

$$ 2 - (-1) = 3 $$

$$ 3 = 3 $$

So the real number values of $a, b, c$ are:

$$ a = -1, b = 2, c = -1 $$

b.

$$
\left[\begin{array}{}
2a && b + c \\
c - a && 2b - a \\
\end{array}\right] =
\left[\begin{array}{}
4 && 3 \\
1 && -2 \\
\end{array}\right]
$$

Four values are:

$$ 2a = 4 $$

$$ b + c = 3 $$

$$ c - a = 1 $$

$$ 2b - a = -2 $$

Evaluating:

$$ 2a = 4 $$

$$ a = 2 $$

then:

$$ c - a = 1 $$

$$ c - (2) = 1 $$

$$ c = 3 $$

then:

$$ b + c = 3 $$

$$ b + 3 = 3 $$

$$ b = 0 $$

Checking:

$$ 2b - a = -2 $$

$$ 2(0) - (2) = -2 $$

$$ 0 - 2 = -2 $$

$$ -2 = -2 $$

Done, so:

$$ a = 2, b = 0, c = 3 $$

2. Find the adjacency matrices for the following directed graphs.

a. (See Page 733 for image of graph.)

$$
\left[\begin{array}{}
0 & 1 & 1 \\
1 & 0 & 0 \\
0 & 0 & 0 \\
\end{array}\right]
$$

b. (See Page 733 for image of graph.)

$$
\left[\begin{array}{}
1 & 0 & 1 & 0 \\
0 & 0 & 1 & 0 \\
1 & 0 & 0 & 1 \\
0 & 0 & 1 & 0 \\
\end{array}\right]
$$

3. Find the directed graphs that have the following adjacency matrices:

a.

$$
\left[\begin{array}{}
1 && 0 && 1 && 2 \\
0 && 0 && 1 && 0 \\
0 && 2 && 1 && 1 \\
0 && 1 && 1 && 0 \\
\end{array}\right]
$$

(Done by hand.)

b.

$$
\left[\begin{array}{}
0 && 1 && 0 && 0 \\
2 && 0 && 1 && 0 \\
1 && 2 && 1 && 0 \\
0 && 0 && 1 && 0 \\
\end{array}\right]
$$

4. Find adjacency matrices for the following (undirected) graphs.

a. (See page 734 for image of graph.)

$$
\left[\begin{array}{}
0 & 0 & 1 & 1 \\
0 & 0 & 2 & 0 \\
1 & 2 & 0 & 0 \\
1 & 0 & 0 & 1 \\
\end{array}\right]
$$

b. (See page 734 for image of graph.)

$$
\left[\begin{array}{}
1 & 0 & 0 & 0 \\
0 & 1 & 1 & 2 \\
0 & 1 & 1 & 0 \\
0 & 2 & 0 & 0 \\
\end{array}\right]
$$

c. $K_4$, the complete graph on four vertices

$$
\left[\begin{array}{}
0 & 1 & 1 & 1 \\
1 & 0 & 1 & 1 \\
1 & 1 & 0 & 1 \\
1 & 1 & 1 & 0 \\
\end{array}\right]
$$

d. $K_{2, 3}$, the complete bipartite graph on $(2, 3)$ vertices

$$
\left[\begin{array}{}
0 & 0 & 1 & 1 & 1 \\
0 & 0 & 1 & 1 & 1 \\
1 & 1 & 0 & 0 & 0 \\
1 & 1 & 0 & 0 & 0 \\
1 & 1 & 0 & 0 & 0 \\
\end{array}\right]
$$

5. Find graphs that have the following adjacency matrices.

a.

$$
\left[\begin{array}{}
1 && 0 && 1 \\
0 && 1 && 2 \\
1 && 2 && 0 \\
\end{array}\right]
$$

b.

$$
\left[\begin{array}{}
0 && 2 && 0 \\
2 && 1 && 0 \\
0 && 0 && 1 \\
\end{array}\right]
$$

6. The following are adjacency matrices for graphs. In each case determine
   whether the graph is connected by analyzing the matrix without drawing the
   graph.

a.

$$
\left[\begin{array}{}
0 && 1 && 1 \\
1 && 1 && 0 \\
1 && 0 && 0 \\
\end{array}\right]
$$

The graph is connected.

b.

$$
\left[\begin{array}{}
0 && 2 && 0 && 0 \\
2 && 0 && 0 && 0 \\
0 && 0 && 1 && 1 \\
0 && 0 && 1 && 1 \\
\end{array}\right]
$$

No, $v_3$ is not connected to either $v_1$ or $v_2$, the same applies to $v_4$.

7. Suppose that for every positive integer $i$, all the entries in the $i$th row
   and the $i$th column of the adjacency matrix of a graph are $0$. What can you
   conclude about the graph?

The $i$th row and $i$th column define the number of edges between $v_i$ and all
other edges. If $v_ii$ is always $0$, this indicates that there are $0$ edges
from $v_ii$ to every other vertex on the graph, and therefore the graph is
disconnected and in fact, has no edges at all.

8. Find each of the following products.

a.

$$
\left[\begin{array}{}
2 && -1 \\
\end{array}\right]
\left[\begin{array}{}
1 \\
3 \\
\end{array}\right] = (2)(1) + (-1)(3) = 2 + (-3) = -1
$$

b.

$$
\left[\begin{array}{}
4 && -1 && 7 \\
\end{array}\right]
\left[\begin{array}{}
1 \\
2 \\
0 \\
\end{array}\right] = (4)(1) + (-1)(2) + (7)(0) = 4 + (-2) + 0 = 4 - 2 = 2
$$

9. Find each of the following products.

a.

$$
\left[\begin{array}{}
3 && 0 \\
1 && -2 \\
\end{array}\right]
\left[\begin{array}{}
1 && -1 && 4 \\
0 && 2 && 1 \\
\end{array}\right] = \left[\begin{array}{} 3 & -3 & 12 \\ 1 & -5 & 2 \end{array}\right]
$$

b.

$$
\left[\begin{array}{}
2 && 0 && 1 \\
0 && -1 && 0 \\
\end{array}\right]
\left[\begin{array}{}
1 && 3 \\
5 && -4 \\
-2 && 2 \\
\end{array}\right] = \left[\begin{array}{} 0 & 8 \\ -5 & 4 \end{array}\right]
$$

c.

$$
\left[\begin{array}{}
-1 \\
2 \\
\end{array}\right]
\left[\begin{array}{}
2 && 3 \\
\end{array}\right] = \left[\begin{array}{} -2 & -3 \\ 4 & 6 \end{array}\right]
$$

d.

$$
\left[\begin{array}{}
1 && 2 \\
3 && -1 \\
\end{array}\right]^2 = \left[\begin{array}{} 7 & 0 \\ 0 & 7 \end{array}\right]
$$

10. Let

$$
\mathbf{A} = \left[\begin{array}{}
1 && 1 && -1 \\
0 && -2 && 1
\end{array}\right]
$$

$$
\mathbf{B} = \left[\begin{array}{}
-2 && 0 \\
1 && 3 \\
\end{array}\right]
$$

and

$$
\mathbf{C} = \left[\begin{array}{}
0 && -2 \\
3 && 1 \\
1 && 0 \\
\end{array}\right]
$$

For each of the following, determine whether the indicated product exists, and
compute it if it does.

a. $\mathbf{AB}$

Recall that in order for a matrix multiplication between two matrices to be
valid, the first matrix's columns must be equal to the second matrix's rows.

$\mathbf{A}$ is a $2 \times 3$ matrix (so 3 columns), and $\mathbf{B}$ is a
$2 \times 2$ matrix (so 2 rows). Thus the indicated product of $\mathbf{AB}$
does not exist.

b. $\mathbf{BA}$

$\mathbf{B}$ has 2 columns, and $\mathbf{A}$ has 2 rows, so the indicated
product exists.

$$
\mathbf{BA} = \left[\begin{array}{}
-2 & -2 & 2 \\
1 & -5 & -2 \\
\end{array}\right]
$$

c. $\mathbf{A}^2$

$\mathbf{A}$ has 3 columns, and $\mathbf{A}$ has rows 2, so the indicated
product does not exist.

d. $\mathbf{BC}$

$\mathbf{B}$ has 2 columns, and $\mathbf{C}$ has 3 rows, so the indicated
product does not exist.

e. $\mathbf{CB}$

$\mathbf{C}$ has 2 columns, and $\mathbf{B}$ has 2 rows, so the indicated
product does exist.

$$
\mathbf{CB} = \left[\begin{array}{}
-2 & -6 \\
-5 & 3 \\
-2 & 0 \\
\end{array}\right]
$$

f. $\mathbf{B}^2$

$\mathbf{B} has 2 columns, and $\mathbf{B}$ has 2 rows, so the indicated product
does exist.

$$
\mathbf{B}^2 = \left[\begin{array}{}
4 & 0 \\
1 & 9 \\
\end{array}\right]
$$

g. $\mathbf{B}^3$

Note that $\mathbf{B}^3 = \mathbf{B}\mathbf{B}^2$.

$\mathbf{B}$ has 2 columns, and $\mathbf{B}^2$ has 2 rows, so the indicated
product exists.

$$
\mathbf{B}^3 = \left[\begin{array}{}
-8 & 0 \\
7 & 27 \\
\end{array}\right]
$$

h. $\mathbf{C}^2$

$\mathbf{C}$ has 2 columns, and $\mathbf{C}$ has 3 rows, so the indicated
product does not exist.

i. $\mathbf{AC}$

$\mathbf{A}$ has 3 columns, and $\mathbf{C}$ has 3 rows, so the indicated
product does exist.

$$
\mathbf{AC} = \left[\begin{array}{}
2 & -1  \\
-5 & -2 \\
\end{array}\right]
$$

j. $\mathbf{CA}$

$\mathbf{C}$ has 2 columns, and $\mathbf{A}$ has 2 rows, so the indicated
product does exist.

$$
\mathbf{CA} = \left[\begin{array}{}
0 & 4 & -2 \\
3 & 1 & -2 \\
1 & 1 & -1 \\
\end{array}\right]
$$

11. Give an example different from that in the text to show that matrix
    multiplication is not commutative. That is, find $2 \times 2$ matrices
    $\mathbf{A}$ and $\mathbf{B}$ such that $\mathbf{AB}$ and $\mathbf{BA}$ both
    exist but $\mathbf{AB} \neq \mathbf{BA}$.

$$
\mathbf{A} = \left[\begin{array}{}
1 & 2 \\
3 & 4 \\
\end{array}\right]
$$

$$
\mathbf{B} = \left[\begin{array}{}
2 & 4 \\
3 & 6 \\
\end{array}\right]
$$

$$
\mathbf{AB} = \left[\begin{array}{}
8 & 16 \\
18 & 36 \\
\end{array}\right]
$$

$$
\mathbf{BA} = \left[\begin{array}{}
14 & 20 \\
21 & 30 \\
\end{array}\right]
$$

So, $\mathbf{AB}$ and $\mathbf{BA}$ exist, but $\mathbf{AB} \neq \mathbf{BA}$.

12. Let $\mathbf{O}$ denote the matrix
    $\left[\begin{array}{} 0 && 0 \\ 0 && 0\\ \end{array}\right]$. Find
    $2 \times 2$ matrices $\mathbf{A}$ and $\mathbf{B}$ such that
    $\mathbf{A} \neq \mathbf{O}$ and $\mathbf{B} \neq \mathbf{O}$ but
    $\mathbf{AB} = \mathbf{O}$.

$$
\mathbf{A} = \left[\begin{array}{}
1 & -1 \\
-1 & 1 \\
\end{array}\right]
$$

$$
\mathbf{B} = \left[\begin{array}{}
1 & 1 \\
1 & 1 \\
\end{array}\right]
$$

$$
\mathbf{AB} = \left[\begin{array}{}
0 & 0 \\
0 & 0 \\
\end{array}\right]
$$

13. Let $\mathbf{O}$ denote the matrix
    $\left[\begin{array}{} 0 && 0 \\ 0 && 0\\ \end{array}\right]$. Find
    $2 \times 2$ matrices $\mathbf{A}$ and $\mathbf{B}$ such that
    $\mathbf{A} \neq \mathbf{B}$, $\mathbf{B} \neq \mathbf{O}$ and
    $\mathbf{AB} \neq \mathbf{O}$, but $\mathbf{BA} = \mathbf{O}$.

$$
\mathbf{A} = \left[\begin{array}{}
1 & 0 \\
0 & 0 \\
\end{array}\right]
$$

$$
\mathbf{B} = \left[\begin{array}{}
0 & 1 \\
0 & 0 \\
\end{array}\right]
$$

$$
\mathbf{AB} = \left[\begin{array}{}
0 & 1 \\
0 & 0 \\
\end{array}\right]
$$

so $\mathbf{AB} \neq \mathbf{O}$.

$$
\mathbf{BA} = \left[\begin{array}{}
0 & 0 \\
0 & 0 \\
\end{array}\right]
$$

so $\mathbf{BA} = \mathbf{O}$.

In 14-18, assume the entries of all matrices are real numbers.

14. Prove that if $\mathbf{I}$ is the $m \times m$ identity matrix and
    $\mathbf{A}$ is any $m \times n$ matrix, then $\mathbf{IA} = \mathbf{A}$.

_Hint:_ If the entries of the $m \times m$ identity matrix are denoted
$\delta_{ik}$, then
$\delta_{ik} = \begin{cases} 0 & \text{if } i \neq k \\ 1 & \text{if } i = k \end{cases}$.
The $ij$th entry of $\mathbf{IA}$ is
$\sum_{k = 1}^{m}{\delta_{ik}\mathbf{A}_{kj}}$.

**Proof:**

Suppose that $\mathbf{I}$ is the $m \times m$ identity matrix, and $\mathbf{A}$
is any $m \times n$ matrix.

It must be shown that $\mathbf{IA} = \mathbf{A}$.

Equivalently, it must be shown that for all $1 \leq i \leq m$ and all
$1 \leq j \leq n$, that $\mathbf{IA}_{ij} = \mathbf{A}_{ij}$.

Denote the entries of $\mathbf{I}$ as $\delta_{ik}$, where each $\delta_{ik}$ is
defined by the following piecewise function:

$$
\delta_{ik} =
\begin{cases}
0 & \text{if } i \neq k \\
1 & \text{if } i = k
\end{cases}
$$

Then, the $ij$th entry of $\mathbf{IA}$ is:

$$ \sum_{k = 1}^{m}{\delta_{ik}\mathbf{A}_{kj}} $$

$$ = \delta_{i1}\mathbf{A}_{1j} + \delta_{i2}\mathbf{A}_{2j} + \cdots + \delta_{im}\mathbf{A}_{mj} $$

Because all the terms in the sum are $0$ except when $i = k$, by multiplication,
it follows that $\mathbf{IA} = \mathbf{A}$.

This is what was to be shown.

Q.E.D.

15. Prove that if $\mathbf{A}$ is an $m \times m$ symmetric matrix, then
    $\mathbf{A}^2$ is symmetric.

**Proof:**

Suppose that $\mathbf{A}$ is an $m \times m$ symmetric matrix.

It must be shown that $\mathbf{A}^2$ is symmetric.

Let $1 \leq i$, and $j \leq m$.

For all $i$, $j$, and $k$:

$$ (\mathbf{A}^2)_{ij} = \sum_{k = 1}^{m}{\mathbf{A}_{ik}\mathbf{A}_{kj}} $$

and

$$ (\mathbf{A}^2)_{ji} = \sum_{k = 1}^{m}{\mathbf{A}_{jk}\mathbf{A}_{ki}} $$

Since $\mathbf{A}$ is symmetric, this means that
$(\mathbf{A}_{ik}) = (\mathbf{A}_{ki})$ and
$(\mathbf{A}_{jk}) = (\mathbf{A}_{kj})$, for some integer $k \geq 1$.

By the commutative law of multiplication, it follows that
$(\mathbf{A})_{ik}(\mathbf{A}_{kj}) = (\mathbf{A}_{jk})(\mathbf{A}_{ki})$.

Hence $(\mathbf{A}^2_{ij}) = (\mathbf{A}^2_{ji})$ for all $i$ and $j$.

Q.E.D.

16. Prove that matrix multiplication is associative: If $\mathbf{A}$,
    $\mathbf{B}$, and $\mathbf{C}$ are any $m \times k$, $k \times r$, and
    $r \times n$ matrices, respectively, then
    $(\mathbf{AB})\mathbf{C} = \mathbf{A}(\mathbf{BC})$. (_Hint:_ Summation
    notation is helpful.)

**Proof:**

Suppose that $\mathbf{A}$ is an $m \times k$ matrix, $\mathbf{B}$ is a
$k \times r$ matrix, and $\mathbf{C}$ is an $r \times n$ matrix.

It must be shown that $(\mathbf{AB})\mathbf{C} = \mathbf{A}(\mathbf{BC})$.

By the definition of matrix multiplication, $\mathbf{AB}$ is an $m \times r$
matrix. Let $1 \leq i \leq m$, and $1 \leq j \leq r$. Thus the $ij$th entry of
$\mathbf{A}\mathbf{B}$ can be expressed as:

$$ (\mathbf{A}\mathbf{B})_{ij} = \sum_{x = 1}^{k}{\mathbf{A}_{ix}\mathbf{B}_{xj}} $$

Similarly, $\mathbf{BC}$: is an $r \times n$ matrix, where $1 \leq i \leq r$,
and $1 \leq j \leq n$. Thus the $ij$th entry of $\mathbf{B}\mathbf{C}$ can be
expressed as:

$$ (\mathbf{B}\mathbf{C})_{ij} = \sum_{y = 1}^{r}{\mathbf{B}_{iy}\mathbf{C}_{yj}} $$

Then, $(\mathbf{AB})\mathbf{C}$ is a $m \times n$ matrix where $1 \leq i \leq m$
and $1 \leq j \leq n$, where the $ij$th entry is:

$$ ((\mathbf{AB})\mathbf{C})_{ij} = \sum_{y = 1}^{r}{(\mathbf{A}\mathbf{B})_{iy}\mathbf{C}_{yj}} $$

$$ = \sum_{y = 1}^{r}{\sum_{x = 1}^{k}{\mathbf{A}_{ix}\mathbf{B}_{xy}\mathbf{C}_{yj}}} $$

By the associative law of multiplication:

$$ = \sum_{x = 1}^{k}{\mathbf{A}_{ix}\left(\sum_{y = 1}^{r}{\mathbf{B}_{xy}\mathbf{C}_{yj}}\right)} $$

Now, $\mathbf{A}(\mathbf{BC})$ is an $m \times n$ matrix where
$1 \leq i \leq m$, and $1 \leq j \leq n$, where the $ij$th entry is:

$$ (\mathbf{A}(\mathbf{BC}))_{ij} = \sum_{x = 1}^{k}{\mathbf{A}_{ix}(\mathbf{BC})_{xj}} $$

$$ = \sum_{x = 1}^{k}{\mathbf{A}_{ix}\left(\sum_{y = 1}^{r}{\mathbf{B}_{xy}\mathbf{C}_{yj}}\right)} $$

And this is equal to $(\mathbf{AB})\mathbf{C}$.

Q.E.D.

17. Use mathematical induction and the result of exercise 16 to prove that if
    $\mathbf{A}$ is any $m \times m$ matrix, then
    $\mathbf{A}^n\mathbf{A} = \mathbf{A}\mathbf{A}^n$ for each integer
    $n \geq 1$.

**Proof (by mathematical induction):**

Suppose that $\mathbf{A}$ is any $m \times m$ matrix.

It must be shown that $\mathbf{A}^n\mathbf{A} = \mathbf{A}\mathbf{A}^n$ for each
integer $n \geq 1$.

Let $P(n)$ be the statement:

If $\mathbf{A}$ is any $m \times m$ matrix, then
$\mathbf{A}^n\mathbf{A} = \mathbf{A}\mathbf{A}^n$.

_Basis Step:_

Prove $P(1)$, that is:

If $\mathbf{A}$ is any $m \times m$ matrix, then
$\mathbf{A}^1\mathbf{A} = \mathbf{A}\mathbf{A}^1$.

Since $\mathbf{A}^1 = \mathbf{A}$ by the laws of exponents,
$\mathbf{A}^1\mathbf{A} = \mathbf{A}\mathbf{A}^1$ can be expressed as:

$$ \mathbf{A}\mathbf{A} = \mathbf{A}\mathbf{A} $$

$$ \mathbf{A}^2 = \mathbf{A}^2 $$

This is trivially true by the laws of equality, therefore $P(1)$ is true.

_Inductive Step:_

Let $k \in \mathbb{Z}$ where $k \geq 1$.

Suppose $P(k)$, that is:

If $\mathbf{A}$ is any $m \times m$ matrix, then
$\mathbf{A}^k\mathbf{A} = \mathbf{A}\mathbf{A}^k$.

This is the inductive hypothesis.

Prove $P(k + 1)$, that is:

If $\mathbf{A}$ is any $m \times m$ matrix, then
$\mathbf{A}^{k + 1}\mathbf{A} = \mathbf{A}\mathbf{A}^{k + 1}$.

By the definition of taking a matrix to a power:

$$ \mathbf{A}^{k + 1} = \mathbf{A}\mathbf{A}^k $$

So:

$$ \mathbf{A}^{k + 1}\mathbf{A}  = (\mathbf{A}\mathbf{A}^k)\mathbf{A} $$

Then, by exercise 16, it is known that this expression is associative, so:

$$ = \mathbf{A}(\mathbf{A}^k\mathbf{A}) $$

Then, by the inductive hypothesis:

$$ = \mathbf{A}(\mathbf{A}\mathbf{A}^k) $$

And once again by the definition of taking a matrix to a power:

$$ = \mathbf{A}(\mathbf{A}^{k + 1}) $$

This is what was to be shown.

_Conclusion:_

Since both the basis and inductive step have been proven, the statement $P(n)$
is true.

Q.E.D.

18. Use mathematical induction to prove that if $\mathbf{A}$ is an $m \times m$
    symmetric matrix, then for any integer $n \geq 1$, $\mathbf{A}^n$ is also
    symmetric.

**Proof (by mathematical induction):**

Suppose $\mathbf{A}$ is an $m \times m$ symmetric matrix.

It must be shown that for any integer $n \geq 1$, $\mathbf{A}^n$ is symmetric.

Let $P(n)$ be the statement:

If $\mathbf{A}$ is an $m \times m$ symmetric matrix, then for any integer
$n \geq 1$, $\mathbf{A}^n$ is also symmetric.

_Basis Step:_

Prove $P(1)$, that is:

If $\mathbf{A}$ is an $m \times m$ symmetric matrix, then $\mathbf{A}^1$ is also
symmetric.

Since $\mathbf{A}^1 = \mathbf{A}$, and since, by the supposition, $\mathbf{A}$
is symmetric, it follows by the laws of equality that $\mathbf{A}^1$ is
symmetric.

Thus $P(1)$ is true.

_Inductive Step:_

Let $k \in \mathbf{Z}$, such that $k \geq 1$.

Suppose $P(k)$, that is:

If $\mathbf{A}$ is an $m \times m$ symmetric matrix, then $\mathbf{A}^k$ is also
symmetric.

This is the inductive hypothesis.

Prove $P(k + 1)$, that is:

If $\mathbf{A}$ is an $m \times m$ symmetric matrix, then $\mathbf{A}^{k + 1}$
is also symmetric.

Now, note that by the laws of exponents on matrices:

$$ \mathbf{A}^{k + 1} = \mathbf{A}\mathbf{A}^k $$

The $ij$th entry of $\mathbf{A}^{k + 1}$ can be expressed as a summation as:

$$ (\mathbf{A}^{k + 1})_{ij} = \sum_{l = 1}^{m}{\mathbf{A}_{il}(\mathbf{A}^{k})_{lj}} $$

For all integers $1 \leq i \leq m$, and $1 \leq j \leq m$.

Similarly, the $ji$th entry is:

$$ (\mathbf{A}^{k + 1})_{ji} = \sum_{l = 1}^{m}{\mathbf{A}_{jl}(\mathbf{A}^{k})_{li}} $$

To show that $\mathbf{A}^{k + 1}$ is symmetric, these two entries must be shown
to be equal.

By the supposition, it is known that $\mathbf{A}$ is symmetric, and by the
inductive hypothesis, it is known that $\mathbf{A}^k$ is symmetric. Thus
$\mathbf{A}_{jl} = \mathbf{A}_{lj}$, and
$(\mathbf{A}^k)_{li} = (\mathbf{A}^k)_{il}$.

Now, by substitution, it can be said that:

$$ (\mathbf{A}^{k + 1})_{ji} = \sum_{l = 1}^{m}{\mathbf{A}_{jl}(\mathbf{A}^{k})_{li}} $$

$$ = \sum_{l = 1}^{m}{\mathbf{A}_{lj}(\mathbf{A}^k)_{il}} $$

By exercise 17, it is known that
$\mathbf{A}\mathbf{A}^k = \mathbf{A}^k\mathbf{A}$, so the last expression
becomes:

$$ = \sum_{l = 1}^{m}{\mathbf{A}_{il}(\mathbf{A}^k)_{lj}} $$

Notice that this is the same as the summation for $(\mathbf{A}^{k + 1})_{ij}$.
Thus $(\mathbf{A}^{k + 1})_{ij} = \mathbf{A}^{k + 1}_{ji}$, and this means that
$\mathbf{A}^{k + 1}$ is symmetric.

This is what was to be shown.

_Conclusion:_

Since both the basis and inductive steps have been shown, it can be concluded
that $P(n)$ is true.

Q.E.D.

19.

a. Let
$\mathbf{A} = \left[\begin{array}{} 1 && 1 && 2 \\ 1 && 0 && 1 \\ 2 && 1 && 0 \\ \end{array}\right]$.
Find $\mathbf{A}^2$ and $\mathbf{A}^3$.

$$
\mathbf{A}^2 = \left[\begin{array}{}
6 & 3 & 3 \\
3 & 2 & 2 \\
3 & 2 & 5 \\
\end{array}\right]
$$

$$
\mathbf{A}^3 = \left[\begin{array}{}
15 & 9 & 15 \\
9 & 5 & 8 \\
15 & 8 & 8 \\
\end{array}\right]
$$

b. Let $G$ be the graph with vertices $v_1$, $v_2$, and $v_3$ and with
$\mathbf{A}$ as its adjacency matrix. Use the answers to part (a) to find the
number of walks of length $2$ from $v_1$ to $v_3$ and the number of walks of
length $3$ from $v_1$ to $v_3$. Do not draw $G$ to solve this problem.

By theorem 10.2.2, the number of walks of length $2$ from $v_1$ to $v_3$ is
$(\mathbf{A}^2)_{13} = 3$.

Similarly, the number of walks of length 3 from $v_1$ to $v_3$ is
$(\mathbf{A}^3)_{13} = 15$.

c. Examine the calculations you performed in answering part (a) to find five
walks of length $2$ from $v_3$ to $v_3$. Then draw $G$ and find the walks by
visual inspection.

By looking at $\mathbf{A}$, it can be seen that $\mathbf{A}_{13} = 2$, call
these two edges $e_2, e_3$. Then note that $\mathbf{A}_{23} = 1$, call this edge
$e_4$. Using these edges, five walks of length 2 from $v_3$ to $v_3$ can be
expressed as:

$$ v_3e_2v_1e_3v_3, v_3e_3v_1e_2v_3, v_3e_2v_1e_2v_3, v_3e_3v_1e_3v_3, v_3e_4v_2e_4v_3 $$

20. The following is an adjacency matrix for a graph:

(See page 735 for matrix.)

Answer the following questions by examining the matrix and its powers only, not
by drawing the graph:

a. How many walks of length 2 are there from $v_2$ to $v_3$?

Omitted.

b. How many walks of length 2 are there from $v_3$ to $v_4$?

Omitted.

c. How many walks of length 3 are there from $v_1$ to $v_4$?

Omitted.

d. How many walks of length 3 are there from $v_2$ to $v_3$?

Omitted.

21. Let $\mathbf{A}$ be the adjacency matrix for $K_3$, the complete graph on
    three vertices. Use mathematical induction to prove that for each positive
    integer $n$, all the entries along the main diagonal of $\mathbf{A}^n$ are
    equal to each other and all the entries that do not lie along the main
    diagonal are equal to each other.

Omitted.

22.

a. Draw a graph that has

$$
\left[\begin{array}{}
0 && 0 && 0 && 1 && 2 \\
0 && 0 && 0 && 1 && 1 \\
0 && 0 && 0 && 2 && 1 \\
1 && 1 && 2 && 0 && 0 \\
2 && 1 && 1 && 0 && 0 \\
\end{array}\right]
$$

as its adjacency matrix. Is this graph bipartite?

Omitted.

---

Page 735

**Definition:**

Given an $m \times n$ matrix $\mathbf{A}$ whose $ij$th entry is denoted
$a_{ij}$, the **transpose of $\mathbf{A}$** is the matrix $\mathbf{A}^t$ whose
$ij$th entry is $a_{ji}$, for each $i = 1, 2, \dots m$ and $j = 1, 2, \dots, n$.

---

Note that the first row of $\mathbf{A}$ becomes the first column of
$\mathbf{A}^t$, the second row of $\mathbf{A}$ becomes the second column of
$\mathbf{A}^t$, and so forth. For instance,

$$ \text{if } \mathbf{A} = \left[\begin{array}{} 0 && 1 && 1 \\ 1 && 2 && 3 \\ \end{array}\right] \text{, then } \mathbf{A}^t = \left[\begin{array}{} 0 && 1 \\ 2 && 2 \\ 1 && 3 \\ \end{array}\right] $$

b. Show that a graph with $n$ vertices is bipartite if, and only if, for some
labeling of its vertices, its adjacency matrix has the form

$$
\left[\begin{array}{}
\mathbf{O} && \mathbf{A} \\
\mathbf{A}^t && \mathbf{O} \\
\end{array}\right]
$$

where $\mathbf{A}$ is a $k \times (n - k)$ matrix for some integer $k$ such that
$0 < k < n$, the top left $\mathbf{O}$ represents a $k \times k$ matrix all of
whose entries are $0$, $\mathbf{A}^t$ is the transpose of $\mathbf{A}$, and the
bottom right $\mathbf{O}$ represents an $(n - k) \times (n - k)$ matrix all of
whose entries are $0$.

Omitted.

23.

a. Let $G$ be a graph with $n$ vertices, and let $v$ and $w$ be distinct
vertices of $G$. Prove that if there is a walk from $v$ to $w$, then there is a
walk from $v$ to $w$ that has length less than or equal to $n - 1$.

Omitted.

b. If $\mathbf{A} = (a_{ij})$ and $\mathbf{B} = (b_{ij})$ are any $m \times n$
matrices, the matrix $\mathbf{A} + \mathbf{B}$ is the $m \times n$ matrix whose
$ij$th entry is $a_{ij} + b_{ij}$ for each $i = 1, 2, \dots, m$ and
$j = 1, 2, \dots, n$. Let $G$ be a graph with $n$ vertices where $n > 1$, and
let $\mathbf{A}$ be the adjacency matrix of $G$. Prove that $G$ is connected if,
and only if, every entry of
$\mathbf{A} + \mathbf{A}^2 + \cdots + \mathbf{A}^{n - 1}$ is positive.

Omitted.
