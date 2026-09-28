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

---

Page 742

**Exercise Set 10.3**

For each pair of graphs $G$ and $G'$ in 1-5, determine whether $G$ and $G'$ are
isomorphic. If they are, give functions $g: V(G) \to V(G')$ and
$h: E(G) \to E(G')$ that define isomorphism. If they are not, given an invariant
for graph isomorphism that they do not share.

1. (See page 742 for graph image.)

Yes, isomorphic, functions defined by hand.

2. (See page 742 for graph image.)

Not isomorphic, $G$ has 5 vertices, while $G'$ has 6 vertices.

3. (See page 742 for graph image.)

Isomorphic, done by hand.

4. (See page 742 for graph image.)

Not isomorphic, $G'$ has vertex $w_5$ of degree 5, and $G$ has no vertex of
degree 5.

5. (See page 742 for graph image.)

Not isomorphic, $G$ has vertex $v_5$ which has degree 5, but no vertex in $G'$
has a vertex of degree 5.

For each pair of simple graphs $G$ and $G'$ in 6-13, determine whether $G$ and
$G'$ are isomorphic. If they are, give a function $g: V(G) \to V(G')$ that
defines the isomorphism. If they do not, give an invariant for graph isomorphism
that they do not share.

6. (See page 742 for graph image.)

Isomorphic, done by hand.

7. (See page 742 for graph image.)

Isomorphic, done by hand.

8. (See page 742 for graph image.)

Not Isomorphic, $G$ has a simple circuit of length $3$ and $G'$ does not.

9. (See page 742 for graph image.)

Isomorphic, done by hand.

10. (See page 742 for graph image.)

Isomorphic, done by hand.

11. (See page 742 for graph image.)

Not isomorphic, graph $G$ is not connected, while $G'$ is.

12. (See page 742 for graph image.)

Isomorphic, done by hand.

13. (See page 743 for graph image.)

Not isomorphic, $G$ has 4 circuits of length 4, while $G'$ has 6 circuits of
length 4.

14. Draw all nonisomorphic simple graphs with three vertices.

(Done by hand.)

15. Draw all nonisomorphic simple graphs with four vertices.

(Done by hand.)

16. Draw all nonisomorphic graphs with three vertices and no more than two
    edges.

(Done by hand.)

17. Draw all nonisomorphic graphs with four vertices and no more than two edges.

(Done by hand.)

18. Draw all nonisomorphic graphs with four vertices and three edges.

(Done by hand.)

19. Draw all nonisomorphic graphs with six vertices, all having degree 2.

Omitted.

20. Draw four nonisomorphic graphs with six vertices, two of degree 4 and four
    of degree 3.

Omitted.

Prove that each of the properties in 21-29 is an invariant for graph
isomorphism. Assume that $n$, $m$, and $k$ are all nonnegative integers.

21. Has $n$ vertices

Prove that if $G$ is a graph that has $n$ vertices, and $G'$ is isomorphic to
$G$, then $G'$ has $n$ vertices.

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs, and $G$ has $n$ vertices (where
$n \in \mathbb{Z}$, and $n \geq 1$).

It must be shown that $G'$ has $n$ vertices.

Since $G$ and $G'$ are isomorphic, it follows, by the definition of isomorphism,
that there exists a one-to-one, onto function $g$ from the vertices of $G$ to
the vertices of $G'$ that preserve the edge function. In other words, for all
vertices $u$ of $G$, there exists a vertex $g(u)$ in $G'$.

Since $g$ is one-to-one, this ensures that every vertex, $g(u)$ in $G'$ is
distinct, and since $g$ is onto, this ensures that every vertex, $g(u)$ in $G'$,
is mapped to a vertex $u$ in $G$.

Thus it follows that if $G$ has $n$ vertices, then $G'$ also has $n$ vertices.

This is what was to be shown.

Q.E.D.

22. Has $m$ edges

Prove that if $G$ is a graph that has $m$ edges, and $G'$ is isomorphic to $G$,
then $G'$ has $m$ edges.

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs, and $G$ has $m$ edges (where
$m \in \mathbb{Z}$, and $m \geq 0$).

It must be shown that $G'$ has $m$ edges.

Since $G$ and $G'$ are isomorphic, it follows, by the definition of isomorphism,
that there exists a one-to-one, onto function $h$ from the edges of $G$ to the
edges of $G'$ that preserve the endpoint function. In other words, for all edges
$e$ of $G$, there exists an edge $h(e)$ in $G'$.

Since $h$ is one-to-one, this ensures that every edge, $h(e)$ in $G'$ is
distinct, and since $h$ is onto, this ensures that every edge, $h(e)$ in $G'$,
is mapped to a edge $e$ in $G$.

Thus it follows that if $G$ has $m$ edges, then $G'$ also has $m$ edges.

This is what was to be shown.

Q.E.D.

23. Has a circuit of length $k$

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs and suppose $G$ has a circuit C$ of
length $k$, where $k \in \mathbb{Z}$ and $k \geq 0$.

It must be shown that $G'$ has a circuit of length $k$.

Let $C$ be $v_0e_1v_1e_2 \dots e_kv_k(=v_0)$. By definition of graph
isomorphism, there are one-to-one correspondences $g: V(G) \to V(G')$ and
$h: E(G) \to E(G')$ that preserve the edge-endpoint functions in the sense that
for each $v$ in $V(G)$ and each $e$ in $E(G)$, $v$ is an endpoint of
$e \Leftrightarrow g(v)$ is an endpoint of $h(e)$.

Let $C'$ be $g(v_0)h(e_1)g(v_1)h(e_2) \dots h(e_k)g(v_k)(=g(v_0))$. Then $C'$ is
a circuit of length $k$ in $G'$.

The reasons for this are that:

(1) Because $g$ and $h$ preserve the edge-endpoint functions, both $g(v_i)$ and
$g(v_i + 1)$ are incident on $h(e_i + 1)$ for each $i = 0, 1, \dots, k - 1$, and
so $C'$ is a walk from $g(v_0)$ to $g(v_0)$.

(2) Since $C$ is a circuit, then $e_1, e_2, \dots, e_k$ are distinct, and since
$h$ is a one-to-one correspondence, $h(e_1), h(e_2), \dots, h(e_k)$ are also
distinct, which implies that $C'$ has $k$ distinct edges.

Therefore $G'$ has a circuit $C'$ of length $k$.

Q.E.D.

24. Has a simple circuit of length $k$

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs and suppose $G$ has a simple circuit
C$ of length $k$, where $k \in \mathbb{Z}$ and $k \geq 0$.

It must be shown that $G'$ has a simple circuit of length $k$.

Let $C$ be a circuit of distinct edges and vertices (except for the first and
the last vertices) $v_0e_1v_1e_2 \dots e_kv_k(=v_0)$. By definition of graph
isomorphism, there are one-to-one correspondences $g: V(G) \to V(G')$ and
$h: E(G) \to E(G')$ that preserve the edge-endpoint functions in the sense that
for each $v$ in $V(G)$ and each $e$ in $E(G)$, $v$ is an endpoint of
$e \Leftrightarrow g(v)$ is an endpoint of $h(e)$.

Similarly, let $C'$ be a circuit of distinct edges and vertices (except for the
first and the last vertices)
$g(v_0)h(e_1)g(v_1)h(e_2) \dots h(e_k)g(v_k)(=g(v_0))$. Then $C'$ is a simple
circuit of length $k$ in $G'$.

The reasons for this are that:

(1) Because $g$ and $h$ preserve the edge-endpoint functions, both $g(v_i)$ and
$g(v_i + 1)$ are incident on $h(e_i + 1)$ for each $i = 0, 1, \dots, k - 1$, and
so $C'$ is a walk from $g(v_0)$ to $g(v_0)$.

(2) Since $C$ is a circuit, then $e_1, e_2, \dots, e_k$ are distinct, and since
$h$ is a one-to-one correspondence, $h(e_1), h(e_2), \dots, h(e_k)$ are also
distinct, which implies that $C'$ has $k$ distinct edges.

(3) Since $C$ is a simple circuit, then $v_0, v_1, v_2, \dots, v_k$ are distinct
except for $v_0$ and $v_k$, and since $g$ is a one-to-one correspondence,
$g(v_0), g(v_1), g(v_2) \dots, g(v_k)(=g(v_0))$ are also distinct except for
$g(v_0)$ and $g(v_k)$, which implies that $C'$ is a simple circuit.

Therefore $G'$ has a simple circuit $C'$ of length $k$.

Q.E.D.

25. Has $m$ vertices of degree $k$

_Hint:_ Suppose $G$ and $G'$ are isomorphic and $G$ has $m$ vertices of degree
$k$; call them $v_1, v_2, \dots, v_m$. Since $G$ and $G'$ are isomorphic, there
are one-to-one correspondences $g: V(G) \to V(G')$ and $h: E(G) \to E(G')$. Show
that $g(v_1), g(v_2), \dots, g(v_m)$ are $m$ distinct vertices of $G'$, each of
which has degree $k$.

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs and suppose $G$ has $m$ vertices of
degree $k$ (where $m, k \in \mathbb{Z}$ and $m \geq 1$, and $k \geq 0$).

Let these vertices be $v_1, v_2, \dots, v_m$.

Since $G$ and $G'$ are isomorphic to each other, there exists one-to-one
correspondences $g : V(G) \to V(G')$ and $h: E(G) \to E(G')$.

It must be shown that $g(v_1), g(v_2), \dots, g(v_m)$ are $m$ distinct vertices
of $G'$, each of which has degree $k$.

Consider any arbitrarily chosen vertex in $G$, say $v_i$ in $G$ (for every
$i = 1, 2, \dots m$), and let $v_i$ have degree $k$. This means that there
exists $k$ edges incident on $v_i$, call them $e_1, e_2, \dots e_k$.

Then, since $g$ and $h$ are one-to-one correspondences, it follows that there
exists edges $h(e_1), h(e_2), \dots h(e_k)$ in $G'$ that are incident on
$g(v_i)$. Since $v_i$ has $k$ degree edges, it follows that $g(v_i)$ also has
$k$ degree edges.

Additionally, since $g$ and $h$ are one-to-one and onto, it is implied that each
$g(v_i)$ are distinct.

Therefore it has been shown that there are $m$ distinct vertices of $G'$, each
of which has degree $k$.

This is what was to be shown.

Q.E.D.

26. Has $m$ simple circuits of length $k$

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs, with $G$ having $m$ simple circuits
of length $k$ (where $m, k \geq 1$).

It must be shown that $G'$ has $m$ simple circuits of length $k$.

Let the $m$ simple circuits of $G$ be $C_1, C_2, \dots, C_m$. By exercise 24,
each simple circuit of length $k$ in $G$ maps to a simple circuit of length $k$
in $G'$, call them $C_1', C_2', \dots, C_m'$.

Since $G$ and $G'$ are isomorphic, there exists one-to-one correspondences,
$g: V(G) \to V(G')$ and $h: E(G) \to E(G')$. By exercise 25, it is known that
these images are distinct, and therefore the $C_1', C_2', \dots, C_m'$ are
distinct.

Therefore $G'$ has $m$ simple circuits of length $k$, which is what was to be
shown.

Q.E.D.

27. Is connected

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs, where $G$ is connected.

It must be shown that $G'$ is connected.

Since $G$ and $G'$ are isomorphic, there exists one-to-one correspondences
$g: V(G) \to V(G')$ and $h: E(G) \to E(G')$.

Since $G$ is connected, there is a walk that exists between every pair of
vertices in $G$. So, for every pair of vertices that are endpoints of a walk,
call them $u, v \in G$, there must exist a corresponding $g(u), g(v) \in G'$
(since $G$ and $G'$ are isomorphic) that are also endpoints of a walk.

This implies that $G'$ is connected, which is what was to be shown.

Q.E.D.

28. Has an Euler circuit

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs, where $G$ has an Euler circuit.

It must be shown that $G'$ has an Euler circuit.

Since $G$ and $G'$ are isomorphic, there exists one-to-one correspondences
$g: V(G) \to V(G')$ and $h: E(G) \to E(G')$.

Since $G$ has an Euler circuit, this means that $G$ has a circuit that contains
every vertex and every edge of $G$, and traverses each vertex of $G$ at least
once, and traverses every edge of $G$ exactly once.

By exercise 21, it is known that if $G$ has $n$ vertices, then $G'$ has $n$
vertices.

By exercise 22, it is known that if $G$ has $m$ edges, then $G'$ has $m$ edges.

By exercise 23, it is known that if $G$ has a circuit of length $k$, then $G'$
has a circuit of length $k$.

Since $h$ maps the edges of the Euler circuit in $G$ to distinct edges in $G'$,
and, by exercise 22, $G'$ has exactly $m$ edges, it follows that the image
circuit covers all edges of $G'$.

Q.E.D.

29. Has a Hamiltonian circuit

**Proof:**

Suppose $G$ and $G'$ are isomorphic graphs, where $G$ has an Hamiltonian
circuit.

It must be shown that $G'$ has an Hamiltonian circuit.

Since $G$ and $G'$ are isomorphic, there exists one-to-one correspondences
$g: V(G) \to V(G')$ and $h: E(G) \to E(G')$.

Since $G$ has a Hamiltonian circuit, this means that $G$ has a simple circuit
that includes every vertex of $G$. In other words, in $G$ there exists a
sequence of adjacent vertices and distinct edges in which every vertex of $G$
appears exactly once, except for the first and the last, which are the same.

By exercise 21, it is known that if $G$ has $n$ vertices, then $G'$ has $n$
vertices.

By exercise 22, it is known that if $G$ has $m$ edges, then $G'$ has $m$ edges.

By exercise 24, it is known that if $G$ has a simple circuit of length $k$, then
$G'$ has a simple circuit of length $k$.

Since $g$ maps the vertices of the Hamiltonian circuit in $G$ to distinct
vertices in $G'$, and, by exercise 21, $G'$ has exactly $n$ vertices, it follows
that the image circuit covers all vertices of $G'$.

Q.E.D.

30. Show that the following two graphs are not isomorphic by supposing they are
    isomorphic and deriving a contradiction.

(See page 743 for graph image.)

(See page 743 for graph image.)

Omitted.

---

Page 754

**Exercise Set 10.4**

1. Read the tree in Example 10.4.2 from left to right to answer the following
   questions.

a. A student scored 12 on part I and 4 on part II. What course should the
student take?

Math 110

b. A student scored 8 on part I and 9 on part II. What course should the student
take?

Math 110

2. Draw trees to show the derivations of the following sentences from the rules
   given in Example 10.4.3.

a. The young ball caught the man.

(Done by hand.)

b. The man caught the young ball.

(Done by hand.)

3. What is the total degree of a tree with $n$ vertices? Why?

_Hint:_ The answer is $2n - 2$. To obtain this result, use the relationship
between the total degree of a graph and the number of edges of the graph.

By the definition of a graph, the total degree of a graph is $2$ times the
number of edges in the graph. By the definition of a tree, a tree of $n$
vertices has $n - 1$ edges, and therefore a tree of $n$ vertices has
$2(n - 1) = 2n - 2$ degrees.

4. Let $G$ be the graph of a hydrocarbon molecule with the maximum number of
   hydrogen atoms for the number of its carbon atoms.

Recall that a hydrocarbon molecule is composed of carbon and hydrogen, where
each carbon atom can form up to four chemical bonds with other atoms, and each
hydrogen atom can form one bond with another atom.

a. Draw the graph of $G$ if $G$ has three carbon atoms and eight hydrogen atoms.

(Done by hand.)

b. Draw the graphs of three isomers of **C<sub>5</sub>H<sub>12</sub>**.

c. Use Example 10.4.4 and exercise 3 to prove that if the vertices of $G$
consist of $k$ carbon atoms and $m$ hydrogen atoms, then $G$ has a total degree
of $2k + 2m - 2$.

The number of vertices of $G$ is $k + m$, and the number of degree of $G$ is $2$
times the amount of edges in $G$. By the definition of tree, $G$ has
$(k + m) - 1$ edges, and so $G$ has $2(k + m - 1) = 2k + 2m - 2$ degrees.

d. Prove that if the vertices of $G$ consist of $k$ carbon atoms and $m$
hydrogen atoms, then $G$ has a total degree of $4k + m$.

**Proof:**

Let $G$ be the graph of a hydrocarbon molecule with the maximum number of
hydrogen atoms for the number of its carbon atoms.

Recall that a hydrocarbon molecule is composed of carbon and hydrogen, where
each carbon atom can form up to four chemical bonds with other atoms, and each
hydrogen atom can form one bond with another atom.

Then, suppose $G$ consists of $k$ carbon atoms and $m$ hydrogen atoms.

It must be shown that $G$ has a total degree of $4k + m$.

Since $G$ has the maximum number of hydrogen atoms for the number of its carbon
atoms, and since $G$ has $k$ carbon atoms, it follows that each carbon atom
vertex has $4$ degrees, since $G$ has the maximum number of hydrogen atoms for
the number of carbon atoms, and thus there are $4k$ total degrees for $k$ carbon
atoms.

Additionally, since $G$ has the maximum number of hydrogen atoms for the number
of its carbon atoms, and since $G$ has $m$ hydrogen atoms, it follows that each
hydrogen atom vertex has $1$ degree. Thus there are a total of $m$ degrees for
$m$ hydrogen atoms.

Adding this together yields $4k + m$ total degrees in $G$, which is what was to
be shown.

Q.E.D.

e. Equate the results of \(c\) and (d) to prove Cayley's result that a saturated
hydrocarbon molecule with $k$ carbon atoms and a maximum number of hydrogen
atoms has $2k + 2$ hydrogen atoms.

**Proof:**

Suppose $G$ is a saturated hydrocarbon molecule with $k$ carbon atoms and a
maximum number of hydrogen atoms, where $m$ is the number of hydrogen atoms.

It must be shown that $G$ has $2k + 2$ hydrogen atoms.

By part \(c\), it is known that if $G$ has $k$ carbon atoms, $m$ hydrogen atoms,
and $G$ is saturated, then there is a total degree of $2k + 2m - 2$ degrees in
$G$.

By part (d), it is known that if $G$ has $k$ carbon atoms, $m$ hydrogen atoms,
and $G$ is saturated, then there is a total degree of $4k + m$ degrees in $G$.

Equating these two values yields:

$$ 2k + 2m - 2 = 4k + m $$

Then, solving for $m$:

$$ 2m - m = 4k - 2k + 2 $$

$$ m = 2k + 2 $$

Thus $m$, which is the number of hydrogen atoms, is equal to $2k + 2$.

This is what was to be shown.

Q.E.D.

5. Extend the argument given in the proof of Lemma 10.4.1 to show that a tree
   with more than one vertex has at least two vertices of degree 1.

_Hint:_ Revise the algorithm given in the proof of Lemma 10.4.1 to keep track of
which vertex and edge were chosen in step 1 (by, say, labeling them $v_0$ and
$e_0$). Then after one vertex of degree 1 is found, return to $v_0$ and search
for another vertex of degree 1 by moving along a path outward from $v_0$
starting with another edge incident on $v_0$. such an edge exists because $v_0$
has degree at least $2$.

The hint is essentially the answer here.

6. If graphs are allowed to have an infinite number of vertices and edges, then
   Lemma 10.4.1 is false. Give a counterexample that shows this. In other words,
   give an example of an "infinite tree" (a connected, circuit-free graph with
   an infinite number of vertices and edges) that has no vertex of degree 1.

Consider an infinite chain that grows in both directions, then such a chain is a
tree since it is connected and circuit-free. Notice that each vertex has a
degree of $2$, and there is no vertex of degree $1$ since the chain never ends.

7. Find all leaves (or terminal vertices) and all internal (or branch) vertices
   for the following tree.

a. (See page 754 for image of tree.)

Leaves: $v_1, v_5, v_7$

Branches: $v_2, v_3, v_4, v_6$

b. (See page 754 for image of tree.)

Leaves: $v_1, v_2, v_5, v_6, v_8$

Branches: $v_3, v_4, v_7$

In each of 8-21, either draw a graph with the given specifications or explain
why no such graph exists.

8. Tree, nine vertices, nine edges

No such graph exists, by definition of tree, a tree with $9$ vertices would have
$8$ edges.

9. Graph, connected, nine vertices, nine edges

(Done by hand.)

10. Graph, circuit-free, nine vertices, six edges

(Done by hand.)

11. Tree, six vertices, total degree 14

No such graph exists, by definition of tree, if tree has 6 vertices, then must
have 5 edges. By definition of graph, total degree of graph is 2 times edges, so
must proposed tree would have to have to have total degree of 10 for tree of six
vertices to exist.

12. Tree, five vertices, total degree 8

(Done by hand.)

13. Graph, connected, six vertices, five edges, has a circuit

No such graph exists, since this connected graph has six vertices and five
edges, such a graph is a tree and thus cannot have a circuit.

14. Graph, two vertices, one edge, not a tree

(Done by hand.)

15. Graph, circuit-free, seven vertices, four edges

(Done by hand.)

16. Tree, twelve vertices, fifteen edges

Nope, must have 11 edges.

17. Graph, six vertices, five edges, not a tree

Not connected, so is possible, done by hand.

18. Tree, five vertices, total degree 10

Nope, degree must equal $2(5 - 1) = 8$.

19. Graph, connected, ten vertices, nine edges, has a circuit

Nope, connected, ten vertices, nine edges, is a tree, cannot have circuit.

20. Simple graph, connected, six vertices, six edges

(Done by hand.)

21. Tree, ten vertices, total degree 24

Nope, total degree must be $2(10 - 1) = 18$

22. A connected graph has twelve vertices and eleven edges. Does it have a
    vertex of degree 1? Why?

Yes, since the graph is connected, has $12$ vertices and has $12 - 1 = 11$
edges, this graph is a tree, and by 10.4.1, must have at least one vertex of
degree 1.

23. A connected graph has nine vertices and twelve edges. Does it have a
    circuit? Why?

Suppose the graph does not have a circuit, since the graph is connected and has
no circuit, it is a tree, but then since the graph has nine vertices and twelve
edges, and thus the graph is not a tree. This is a contradiction, therefore the
graph does have a circuit.

24. Suppose that $v$ is a vertex of degree 1 in a connected graph $G$ and that
    $e$ is the edge incident on $v$. Let $G'$ be the subgraph of $G$ obtained by
    removing $v$ and $e$ from $G$. Must $G'$ be connected? Why?

**Proof:**

Suppose that $G$ is any connected graph where $v$ is a vertex of degree 1, with
$e$ being an edge incident on $v$.

Let $G'$ be the subgraph of $G$ obtained by removing $v$ and $e$ from $G$.

It must be shown that $G'$ is connected.

Since $G$ is connected, there exists a walk between every pair of vertices, thus
let $V(G) = \{v, v_1, \dots, v_n\}$ where $n$ is the number of vertices in $G$.

To show that $G'$ is connected, it must be shown that there is a walk between
every pair of vertices in $G'$, such that $V(G') = \{v_1, \dots, v_n\}$.

Consider any two vertices $v_i$ and $v_j$ in $G'$ where $1 \leq i, j \leq n$.
There is a walk from $v_i$ to $v_j$ in $G$. If this walk contains the edge $e$,
then it must visit $v$, then traverse $e$ again and come back to $v_1$, because
$v$ is only adjacent to $v_1$ and no other vertex (since $v$ has a degree of 1).

Once $v$ and $e$ are removed to obtain $G'$, then $v$ and the two occurrences of
$e$ are removed from this walk, and a walk in $G'$ is obtained.

This is what was to be shown.

Q.E.D.

25. A graph has eight vertices and six edges. Is it connected? Why?

**Disproof (by contradiction):**

Suppose there is such a graph that is connected and has eight vertices and six
edges, then either the graph is a tree or edges could be eliminated from its
circuits to obtain a tree. In either case, there would be a tree with eight
vertices and six edges, but by definition of a tree, such a tree with eight
vertices would have seven edges, not six or fewer.

This is a contradiction, therefore the supposition is false and there exists no
such connected graph with eight vertices and six edges.

Q.E.D.

26. If a graph has $n$ vertices and $n - 2$ or fewer edges, can it be connected?
    Why?

_Hint:_ See the answer to exercise 25.

No, by exercise 25, a connected graph either must be a tree or can have edges
removed such that no circuits remain and thus a tree is obtained, but then such
a tree of $n$ vertices must have $n - 1$ edges, not $n - 2$ or fewer.

27. A circuit-free graph has ten vertices and nine edges. Is it connected? Why?

Yes. Suppose $G$ is a circuit-free graph with ten vertices and nine edges. Let
$G_1, G_2, \dots, G_k$ be the connected components of $G$. _[To show that $G$ is
connected, we will show that $k = 1$.]_ Each $G_i$ is a tree since $G_i$ is
connected and circuit-free. For each $i = 1, 2, \dots, k$, let $G_i$ have $n_i$
vertices. Note that since $G$ has ten vertices in all,

$$ n_1 + n_2 + \cdots + n_k = 10 $$

By Theorem 10.4.2,

$$ G_1 \text{ has } n_1 - 1 \text{edges,} $$

$$ G_2 \text{ has } n_2 - 1 \text{edges,} $$

$$ \vdots $$

$$ G_k \text{ has } n_k - 1 \text{edges,} $$

So the number of edges of $G$ equals

$$ (n_1 - 1) + (n_2 - 1) + \cdots + (n_k - 1) $$

$$ = (n_1 + n_2 + \cdots n_k) - \underbrace{(1 + 1 + \cdots + 1)}_{k \text{1's}} $$

$$ = 10 - k $$

But we are given that $G$ has nine edges. Hence $10 - k = 9$, and so $k = 1$.
Thus $G$ has just one connected component, $G_1$, and so $G$ is connected.

28. Is a circuit-free graph with $n$ vertices and at least $n - 1$ edges
    connected? Why?

_Hint:_ See the answer to exercise 27 and the proof of Corollary 10.4.5.

Yes, simply repeat the proof of exercise 27 with $n$ instead of 10 and $n - 1$
instead of 9.

29. Prove that every nontrivial tree has at least two vertices of degree 1 by
    filling in the details and completing the following argument: Let $T$ be a
    nontrivial tree and let $S$ be the set of all paths from one vertex to
    another in $T$. Among all the paths in $S$, choose a path $P$ with a maximum
    number of edges. (Why is it possible to find such a $P$?) What can you say
    about the initial and final vertices of $P$? Why?

Omitted.

30. Find all nonisomorphic trees with five vertices.

Omitted.

31.

a. Prove that the following is an invariant for graph isomorphism: A vertex of
degree $i$ is adjacent to a vertex of degree $j$.

Omitted.

b. Find all nonisomorphic trees with six vertices.

Omitted.

---

Page 764

**Exercise Set 10.5**

1. Consider the tree shown below with root $a$.

a. What is the level of $n$?

3

b. What is the level of $a$?

0

c. What is the height of this rooted tree?

5

d. What are the children of $n$?

$u, v$

e. What is the parent of $g$?

$d$

f. What are the siblings of $j$?

$k, l$

g. What are the descendants of $f$?

$m, s, t, x, y$

h. How many leaves (terminal vertices) are on the tree?

12 (don't forget the root)

(See page 764 for image of tree.)

2. Consider the tree shown below with root $v_0$.

a. What is the level of $v_8$?

3

b. What is the level of $v_0$?

0

c. What is the height of this rooted tree?

5

d. What are the children of $v_{10}$?

$v_{14}, v_{15}, v_{16}$

e. What is the parent of $v_5$?

$v_1$

f. What are the siblings of $v_1$?

$v_2$

g. What are the descendants of $v_{12}$?

$v_{17}, v_{18}, v_{19}$

h. How many leaves (terminal vertices) are on the tree?

10

(See page 764 for image of tree.)

3. Draw binary trees to represent the following expressions:

a. $a \cdot - \left(\dfrac{c}{(d + e)}\right)$

(Done by hand.)

b. $\dfrac{a}{(b - c \cdot d)}$

(Done by hand.)

In each of 4-20, either draw a graph with the given specifications or explain
why no such graph exists.

4. Full binary tree, five internal vertices

(Done by hand.)

5. Full binary tree, five internal vertices, seven leaves

No such tree exists, since a full binary tree with five internal vertices must
have six leaves, not seven.

6. Full binary tree, seven vertices, of which four are internal vertices

Any full binary tree with four internal vertices must have five leaves for a
total of nine vertices, not seven, thus such a tree does not exist.

7. Full binary tree, twelve vertices

Any full binary tree must have $2k + 1$ vertices, where $k$ is the number of
internal vertices, but $2k + 1$ is an odd number and twelve is even, and thus
such a tree does not exist.

8. Full binary tree, nine vertices

(Done by hand.)

9. Binary tree, height 3, seven leaves

(Done by hand.)

10. Full binary tree, height 3, six leaves

(Done by hand.)

11. Binary tree, height 3, nine leaves

The number of leaves in a binary tree can be expressed by the inequality
$t \leq 2^k$, where $t$ is the number of leaves and $k$ is the height of the
tree, since $9 \cancel{\leq} 2^3 = 8$, this tree does not exist.

12. Full binary tree, eight internal vertices, seven leaves

A full binary tree of eight internal vertices has $2(8) + 1 = 17$ total
vertices, with $17 - 8 = 9$ leaves, and since $9 \neq 7$, this tree cannot
exist.

13. Binary tree, height 4, eight leaves

(Done by hand.)

14. Full binary tree, seven vertices

(Done by hand.)

15. Full binary tree, nine vertices, five internal vertices

A full binary tree of nine vertices must have $2k + 1 = 9, k = 4$ internal
vertices, and since $4 \neq 5$, this tree cannot exist.

16. Full binary tree, four internal vertices

(Done by hand.)

17. Binary tree, height 4, eighteen leaves

This tree cannot exist, since it must be true that $18 \leq 2^4$, but
$18 \cancel{\leq} 16$.

18. Full binary tree, sixteen vertices

In order for this tree to exist, the total of vertices must be expressed as
$2k + 1$, but $2k + 1 = 16$, $2k = 15$, since $k$ must be an integer, this tree
cannot exist.

19. Full binary tree, height 3, seven leaves

(Done by hand.)

20. What can you deduce about the height of a binary tree if you know that it
    has the following properties?

a. Twenty-five leaves

Let $t$ represent the amount of leaves and $k$ represent the height of the
binary tree, then:

$$ t \leq 2^k $$

So:

$$ 25 \leq 2^k $$

Or, equivalently:

$$ \log_2(25) \leq k $$

$$ \approx 4.6449 \leq k $$

Since $k$ must be an integer, we can deduce that $k \geq 5$.

b. Forty leaves

Similar to part (a):

$$ \log_2(40) \leq k $$

$$ \approx 5.3219 \leq k $$

So $k \geq 6$

c. Sixty leaves

Again, similar to parts (a) and (b):

$$ \log_2(60) \leq k $$

$$ \approx 5.9069 \leq k $$

So $k \geq 6$.

In 21-25, use the steps of Algorithm 10.5.1 to build binary search trees. Use
numerical order in 21 and alphabetical order in 22-25. In parts (a) and (b) of
21 and 22, the elements in the list are the same, but the trees are different
because the lists are ordered differently.

21.

a. $16, 24, 21, 3, 18, 9, 7$

(Done by hand.)

b. $16, 7, 3, 21, 18, 24, 9$

(Done by hand.)

22.

a. Asia, Africa, Australia, Antarctica, Europe, North America, South America

(Done by hand.)

b. Australia, Antarctica, Africa, North America, Asia, South America, Europe

(Done by hand.)

23. Carpe diem. Seize the day. Make your lives extraordinary.

(Done by hand.)

24. May the force be with you.

(Done by hand.)

25. All good things which exist are the fruits of originality.

(Done by hand.)

---

Page 780

**Exercise Set 10.6**

Find all possible spanning trees for each of the graphs in 1 and 2.

1. (See page 780 for image.)

(Done by hand.)

2. (See page 780 for image.)

(Done by hand.)

Find a spanning tree for each of the graphs in 3 and 4.

3. (See page 780 for image.)

(Done by hand.)

4. (See page 780 for image.)

(Done by hand.)

Use Kruskal's algorithm to find a minimum spanning tree for each of the graphs
in 5 and 6. Indicate the order in which edges are added to form each tree.

5. (See page 780 for image.)

(Tree drawn by hand.)

Order in which edges are added:

$$ \{a, b\}, \{e, f\}, \{e, d\}, \{d, c\}, \{g, f\}, \{b, c\} $$

6. (See page 780 for image.)

(Tree drawn by hand.)

Order in which edges are added:

$$ \{v_3, v_4\}, \{v_0, v_5\}, \{v_3, v_1\}, \{v_5, v_6\}, \{v_5, v_4\}, \{v_6, v_7\}, \{v_7, v_2\} $$

Use Prim's algorithm starting with vertex $a$ or $v_0$ to find a minimum
spanning tree for each of the graphs in 7 and 8. Indicate the order in which
edges are added to form each tree.

7. The graph of exercise 5.

Same graph as exercise 5.

Order in which edges are added:

$$ \{a, b\}, \{b, c\}, \{c, d\}, \{d, e\}, \{e, f\}, \{f, g\} $$

8. The graph of exercise 6.

Same graph as exercise 6.

Order in which edges are added (can differ from teacher's):

$$ \{v_3, v_4\}, \{v_3, v_1\}, \{v_4, v_5\}, \{v_5, v_0\}, \{v_5, v_6\}, \{v_6, v_7\}, \{v_7, v_2\} $$

For each of the graphs in 9 and 10, find all minimum spanning trees that can be
obtained using (a) Kruskal's algorithm and (b) Prim's algorithm starting with
vertex $a$ or $t$. Indicate the order in which edges are added to form each
tree.

9. (See page 780 for image.)

(done by hand.)

10. (See page 780 for image.)

(done by hand.)

11. A pipeline is to be built that will link six cities. The cost (in hundreds
    of millions of dollars) of constructing each potential link depends on
    distance and terrain and is shown in the weighted graph below. Find a system
    of pipelines to connect all the cities and yet minimize the total cost.

(See page 781 for image.)

Using Kruskal's algorithm, define the given graph as $G$, Denote the cities
_Sa_, _Ch_, _De_, _Am_, _Al_, __Ph_ based off their initial two letters. Let $E$
be the set of all edges in $G$.

Let $T$ represent the minimum spanning tree for $G$ and initialize it at the
vertex that is an endpoint for the least weighted edge. Denote this least
weighted edge $e$. Connect $e$ in $T$, then delete $e$ from $E$. Next, look for
the next least weighted edge and add that respective edge to $T$, while deleting
it from $E$ as long as it does not create a circuit in $T$. Continue in this
fashion until all vertices in $G$ are in $T$ and $E$ is empty.

The order in which this tree is constructed is:

$$ \{Ch, De\}, \{Al, Am\}, \{Al, Ph\}, \{Ch, Sa\}, \{De, Am\} $$

12. Use Dijkstra's algorithm for the airline route system of Figure 10.6.3 to
    find the shortest distance from Nashville to Minneapolis. Make a table
    similar to Table 10.6.1 to show the action of the algorithm.

Let _N_ be Nashville, _S_ be St. Louis, _Lv_ be Louisville, _Ch_ be Chicago,
_Cn_ be Cincinatti, _D_ be Detroit, _Mw_ be Milwaukee, and _Mn_ be Minneapolis

| Step | $V(T)$                            | $E(T)$                                                                               | $F$                        |
| ---- | --------------------------------- | ------------------------------------------------------------------------------------ | -------------------------- |
| 0    | $\{N\}$                           | $\emptyset$                                                                          | $\{N\}$                    |
| 1    | $\{N\}$                           | $\emptyset$                                                                          | $\{Lv, Mn\}$               |
| 2    | $\{N, Lv\}$                       | $\{\{N, Lv\}\}$                                                                      | $\{Mn, Cn, Ch, D, Mw, S\}$ |
| 3    | $\{N, Lv, Cn\}$                   | $\{\{N, Lv\}, \{Lv, Cn\}\}$                                                          | $\{Mn, Ch, D, Mw, S \}$    |
| 4    | $\{N, Lv, Cn, S\}$                | $\{\{N, Lv\}, \{Lv, Cn\}, \{Lv, S\}\}$                                               | $\{Mn, Ch, D, Mw \}$       |
| 5    | $\{N, Lv, Cn, S, Ch\}$            | $\{\{N, Lv\}, \{Lv, Cn\}, \{Lv, S\}, \{Lv, Ch\}\}$                                   | $\{Mn, D, Mw \}$           |
| 6    | $\{N, Lv, Cn, S, Ch, D\}$         | $\{\{N, Lv\}, \{Lv, Cn\}, \{Lv, S\}, \{Lv, Ch\}, \{Lv, D\}\}$                        | $\{Mn, Mw \}$              |
| 7    | $\{N, Lv, Cn, S, Ch, D, Mw\}$     | $\{\{N, Lv\}, \{Lv, Cn\}, \{Lv, S\}, \{Lv, Ch\}, \{Lv, D\}, \{Ch, Mw\}\}$            | $\{Mn\}$                   |
| 8    | $\{N, Lv, Cn, S, Ch, D, Mw, Mn\}$ | $\{\{N, Lv\}, \{Lv, Cn\}, \{Lv, S\}, \{Lv, Ch\}, \{Lv, D\}, \{Ch, Mw\}, \{N, Mn\}\}$ | $\emptyset$                |

| Step | $L(N)$ | $L(S)$         | $L(Lv)$        | $L(Cn)$        | $L(Ch)$        | $L(D)$         | $L(Mw)$        | $L(Mn)$        |
| ---- | ------ | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- | -------------- |
| 0    | $0$    | $\infty$       | $\infty$       | $\infty$       | $\infty$       | $\infty$       | $\infty$       | $\infty$       |
| 1    | $0$    | $\infty$       | $\textbf{151}$ | $\infty$       | $\infty$       | $\infty$       | $\infty$       | $695$          |
| 2    | $0$    | $393$          | $151$          | $\textbf{234}$ | $420$          | $457$          | $499$          | $695$          |
| 3    | $0$    | $393$          | $151$          | $234$          | $420$          | $457$          | $499$          | $695$          |
| 4    | $0$    | $\textbf{393}$ | $151$          | $234$          | $\textbf{420}$ | $457$          | $499$          | $695$          |
| 5    | $0$    | $393$          | $151$          | $234$          | $420$          | $\textbf{457}$ | $494$          | $695$          |
| 6    | $0$    | $393$          | $151$          | $234$          | $420$          | $457$          | $\textbf{494}$ | $695$          |
| 7    | $0$    | $393$          | $151$          | $234$          | $420$          | $457$          | $494$          | $\textbf{695}$ |

Use Dijkstra's algorithm to find the shortest path from $a$ to $z$ for each of
the graphs in 13-16. In each case make tables similar to Table 10.6.1 to show
the action of the algorithm.

13. (See page 781 for image.)

| Step | $V(T)$                 | $E(T)$                                                 | $F$           | $L(a)$       | $L(b)$       | $L(c)$       | $L(d)$       | $L(e)$       | $L(z)$       |
| ---- | ---------------------- | ------------------------------------------------------ | ------------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 0    | $\{a\}$                | $\emptyset$                                            | $\{a\}$       | $\textbf{0}$ | $\infty$     | $\infty$     | $\infty$     | $\infty$     | $\infty$     |
| 1    | $\{a\}$                | $\emptyset$                                            | $\{b, d\}$    | $0$          | $\textbf{2}$ | $\infty$     | $\textbf{1}$ | $\infty$     | $\infty$     |
| 2    | $\{a, d\}$             | $\{\{a, d\}\}$                                         | $\{b, c, e\}$ | $0$          | $\textbf{2}$ | $6$          | $1$          | $11$         | $\infty$     |
| 3    | $\{a, b, d\}$          | $\{\{a, d\}, \{a, b\}\}$                               | $\{c, e\}$    | $0$          | $2$          | $\textbf{5}$ | $1$          | $6$          | $\infty$     |
| 4    | $\{a, b, c, d\}$       | $\{\{a, d\}, \{a, b\}, \{b, c\}\}$                     | $\{e, z\}$    | $0$          | $2$          | $5$          | $1$          | $\textbf{6}$ | $13$         |
| 5    | $\{a, b, c, d, e\}$    | $\{\{a, d\}, \{a, b\}, \{b, c\}, \{c, e\}\}$           | $\{z\}$       | $0$          | $2$          | $5$          | $1$          | $6$          | $\textbf{8}$ |
| 6    | $\{a, b, c, d, e, z\}$ | $\{\{a, d\}, \{a, b\}, \{b, c\}, \{c, e\}, \{e, z\}\}$ |               |              |              |              |              |              |              |

14. (See page 781 for image.)

| Step | $V(T)$                       | $E(T)$                                                                     | $F$              | $L(a)$       | $L(b)$   | $L(c)$   | $L(d)$   | $L(e)$   | $L(f)$       | $L(g)$       | $L(z)$       |
| ---- | ---------------------------- | -------------------------------------------------------------------------- | ---------------- | ------------ | -------- | -------- | -------- | -------- | ------------ | ------------ | ------------ |
| 0    | $\{a\}$                      | $\emptyset$                                                                | $\{a\}$          | $\textbf{0}$ | $\infty$ | $\infty$ | $\infty$ | $\infty$ | $\infty$     | $\infty$     | $\infty$     |
| 1    | $\{a\}$                      | $\emptyset$                                                                | $\{b, e\}$       | $0$          | $1$      | $\infty$ | $\infty$ | $4$      | $\infty$     | $\infty$     | $\infty$     |
| 2    | $\{a, b\}$                   | $\{\{a, b\}\}$                                                             | $\{e, c, f\}$    | $0$          | $1$      | $2$      | $\infty$ | $4$      | $8$          | $\infty$     | $\infty$     |
| 3    | $\{a, b, c\}$                | $\{\{a, b\}, \{b, c\}\}$                                                   | $\{e, f, d, g\}$ | $0$          | $1$      | $2$      | $3$      | $4$      | $8$          | $10$         | $\infty$     |
| 4    | $\{a, b, c, d\}$             | $\{\{a, b\}, \{b, c\}, \{c, d\}\}$                                         | $\{e, f, g, z\}$ | $0$          | $1$      | $2$      | $3$      | $4$      | $8$          | $10$         | $23$         |
| 5    | $\{a, b, c, d, e\}$          | $\{\{a, b\}, \{b, c\}, \{c, d\}, \{a, e\}\}$                               | $\{f, g, z\}$    | $0$          | $1$      | $2$      | $3$      | $4$      | $\mathbf{5}$ | $10$         | $23$         |
| 6    | $\{a, b, c, d, e, f\}$       | $\{\{a, b\}, \{b, c\}, \{c, d\}, \{a, e\}, \{e, f\}\}$                     | $\{g, z\}$       | $0$          | $1$      | $2$      | $3$      | $4$      | $5$          | $\mathbf{6}$ | $23$         |
| 7    | $\{a, b, c, d, e, f, g\}$    | $\{\{a, b\}, \{b, c\}, \{c, d\}, \{a, e\}, \{e, f\}, \{f, g\}\}$           | $\{z\}$          | $0$          | $1$      | $2$      | $3$      | $4$      | $5$          | $6$          | $\mathbf{7}$ |
| 7    | $\{a, b, c, d, e, f, g, z\}$ | $\{\{a, b\}, \{b, c\}, \{c, d\}, \{a, e\}, \{e, f\}, \{f, g\}, \{g, z\}\}$ |                  |              |          |          |          |          |              |              |              |

15. The graph of exercise 9 with $a = a$ and $z = f$

| Step | $V(T)$                                   | $E(T)$                                       | $F$              | $L(a)$       | $L(b)$   | $L(c)$   | $L(d)$   | $L(e)$   | $L(g)$   | $L(f)$       |
| ---- | ---------------------------------------- | -------------------------------------------- | ---------------- | ------------ | -------- | -------- | -------- | -------- | -------- | ------------ |
| 0    | $\{a\}$                                  | $\emptyset$                                  | $\{a\}$          | $\textbf{0}$ | $\infty$ | $\infty$ | $\infty$ | $\infty$ | $\infty$ | $\infty$     |
| 1    | $\{a\}$                                  | $\emptyset$                                  | $\{b, g, e\}$    | $0$          | $3$      | $\infty$ | $\infty$ | $3$      | $4$      | $\infty$     |
| 2    | $\{a, b\}$                               | $\{\{a, b\}\}$                               | $\{g, e, c\}$    | $0$          | $3$      | $10$     | $\infty$ | $3$      | $4$      | $\infty$     |
| 3    | $\{a, b\}, \{a, e\}$                     | $\{\{a, b\}, \{a, e\}\}$                     | $\{g, c, d, f\}$ | $0$          | $3$      | $10$     | $14$     | $3$      | $4$      | $7$          |
| 4    | $\{a, b\}, \{a, e\}, \{a, g\}$           | $\{\{a, b\}, \{a, e\}, \{a, g\}\}$           | $\{c, d, f\}$    | $0$          | $3$      | $10$     | $14$     | $3$      | $4$      | $\textbf{5}$ |
| 5    | $\{a, b\}, \{a, e\}, \{a, g\}, \{g, f\}$ | $\{\{a, b\}, \{a, e\}, \{a, g\}, \{g, f\}\}$ | $\{c, d\}$       |              |          |          |          |          |          |              |

16. The graph of exercise 10 with $a = u$ and $z = w$

| Step | $V(T)$              | $E(T)$                                       | $F$              | $L(u)$       | $L(t)$   | $L(v)$   | $L(x)$   | $L(y)$       | $L(z)$       | $L(w)$   |
| ---- | ------------------- | -------------------------------------------- | ---------------- | ------------ | -------- | -------- | -------- | ------------ | ------------ | -------- |
| 0    | $\{u\}$             | $\emptyset$                                  | $\{u\}$          | $\textbf{0}$ | $\infty$ | $\infty$ | $\infty$ | $\infty$     | $\infty$     | $\infty$ |
| 1    | $\{u\}$             | $\emptyset$                                  | $\{t, v, x, y\}$ | $0$          | $7$      | $2$      | $1$      | $8$          | $\infty$     | $\infty$ |
| 2    | $\{u, x\}$          | $\{\{u, x\}\}$                               | $\{t, v, y, w\}$ | $0$          | $7$      | $2$      | $1$      | $\mathbf{3}$ | $\infty$     | $6$      |
| 3    | $\{u, x, v\}$       | $\{\{u, x\}, \{u, v\}\}$                     | $\{t, y, w, z\}$ | $0$          | $7$      | $2$      | $1$      | $3$          | $9$          | $6$      |
| 4    | $\{u, x, v, y\}$    | $\{\{u, x\}, \{u, v\}, \{x, y\}\}$           | $\{t, w, z\}$    | $0$          | $7$      | $2$      | $1$      | $3$          | $\textbf{8}$ | $6$      |
| 5    | $\{u, x, v, y, w\}$ | $\{\{u, x\}, \{u, v\}, \{x, y\}, \{x, w\}\}$ | $\{t, z\}$       |              |          |          |          |              |              |          |

17. Prove part (2) of Proposition 10.6.1: Any two spanning trees for a graph
    have the same number of edges.

18. Given any two distinct vertices of a tree, there exists a unique path from
    one to the other.

a. Give an informal justification for the above statement.

b. Write a formal proof of the above statement.

19. Prove that if $G$ is a graph with a spanning tree $T$ and $e$ is an edge of
    $G$ that is not in $T$, then the graph obtained by adding $e$ to $T$
    contains one and only one set of edges that form a circuit.

20. Suppose $G$ is a connected graph and $T$ is a circuit-free subgraph of $G$.
    Suppose also that if any edge $e$ of $G$ not in $T$ is added to $T$, the
    resulting graph contains a circuit. Prove that $T$ is a spanning tree for
    $G$.

21.

a. Suppose $T_1$ and $T_2$ are two different spanning trees for a graph $G$.
Must $T_1$ and $T_2$ have an edge in common? Prove or give a counterexample.

b. Suppose that the graph $G$ in part (a) is simple. Must $T_1$ and $T_2$ have
an edge in common? Prove or give a counterexample.

22. Prove that an edge $e$ is contained in every spanning tree for a connected
    graph $G$ if, and only if, removal of $e$ disconnects $G$.

23. Consider the spanning trees $T_1$ and $T_2$ in the proof of Theorem 10.6.3.
    Prove that $w(T_2) \leq w(TS_1)$.

24. Suppose that $T$ is a minimum spanning tree for a connected, weighted graph
    $G$ and that $G$ contains an edge $e$ (not a loop) that is not in $T$. Let
    $v$ and $w$ be the endpoints of $e$. By exercise 18 there is a unique path
    in $T$ from $v$ to $w$. Let $e'$ be any edge of this path. Prove that
    $w(e') \leq w(e)$.

25. Prove that if $G$ is a connected, weighted graph and $e$ is an edge of $G$
    (not a loop) that has smaller weight than any other edge of $G$, then $e$ is
    in every minimum spanning tree for $G$.

26. If $G$ is a connected, weighted graph and no two edges of $G$ have the same
    weight, does there exist a unique minimum spanning tree for $G$? Use the
    result of exercise 19 to help justify your answer.

27. Prove that if $G$ is a connected, weighted graph and $e$ is an edge of $G$
    that (1) has greater weight than any other edge of $G$ and (2) is in a
    circuit of $G$, then there is no minimum spanning tree $T$ for $G$ such that
    $e$ is in $T$.

28. Suppose a disconnected graph is input to Kruskal's algorithm. What will be
    the output?

29. Suppose a disconnected graph is input to Prim's algorithm. What will be the
    output?

30. Modify Algorithm 10.6.3 so that the output consists of the sequences of
    edges in the shortest path from $a$ to $z$.

31. Prove that if a connected, weighted graph $G$ is input to Algorithm 10.6.4
    (shown below), the output is a minimum spanning tree for $G$.

---

**Algorithm 10.6.4**

**Input:** $G$ _[a connected graph]_

**Algorithm Body:**

1. $T := G$.

2. $E :=$ the set of all edges of $G$, $m :=$ the number of edges of $G$.

3. $\textbf{while } (m > 0)$

3a. Find an edge $e$ in $E$ that has maximal weight.

3b. Remove $e$ from $E$ and set $m := m - 1$.

3c. $\textbf{if}$ the subgraph obtained when $e$ is removed from the edge set of
$T$ is connected $\textbf{then}$ remove $e$ from the edge set of $T$

$\textbf{end while}$

**Output:** $T$ _[a minimum spanning tree for $G$]_
