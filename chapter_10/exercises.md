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

$$ uv0v_7v_6v_3uv_1v_2v_3v_4v_6wv_5v_4w $$

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

b. Draw a graph that illustrates who among these five people are _not_
acquainted. That is, draw an edge between two people if, and only if, they are
not acquainted.

27. Let $G$ be a simple graph with $n$ vertices. What is the relation between
    the number of edges of $G$ and the number of edges of the complement $G'$?

28. Show that at a party with at least two people, there are at least two mutual
    acquaintences or at least two mutual strangers.

Find Hamiltonian circuits for each of the graphs in 29 and 30.

29. (See Page 719 for image of graph.)

30. (See Page 719 for image of graph.)

Show that none of the graphs in 31-33 has a Hamiltonian circuit.

31. (See Page 719 for image of graph.)

32. (See Page 719 for image of graph.)

33. (See Page 719 for image of graph.)

In 34-37, find Hamiltonian circuits for those graphs that have them. Explain why
the other graphs do not.

34. (See Page 719 for image of graph.)

35. (See Page 719 for image of graph.)

36. (See Page 719 for image of graph.)

37. (See Page 719 for image of graph.)

38. Give two examples of graphs that have Euler circuits but not Hamiltonian
    circuits.

39. Give two examples of graphs that have Hamiltonian circuits but not Euler
    circuits.

40. Give two examples of graphs that have circuits that are both Euler circuits
    and Hamiltonian circuits.

41. Give two examples of graphs that have Euler circuits and Hamiltonian
    circuits that are not the same.

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

43.

a. Prove that if a walk in a graph contains a repeated edge, then the walk
contains a repeated vertex.

b. Explain how it follows from part (a) that any walk with no repeated vertex
has no repeated edge.

44. Prove Lemma 10.1.1(a): If $G$ is a connected graph, then two distinct
    vertices of $G$ can be connected by a path. (You may use the result stated
    in exercise 43.)

45. Prove Lemma 10.1.1(b): If vertices $v$ and $w$ are part of a circuit in a
    graph $G$ and one edge is removed from the circuit, then there still exists
    a trail from $v$ to $w$ in $G$.

46. Draw a picture to illustrate Lemma 10.1.1\(c\): If a graph $G$ is connected
    and $G$ contains a circuit, then an edge of the circuit can be removed
    without disconnecting $G$.

47. Prove that if there is a trail in a graph $G$ from a vertex $v$ to a vertex
    $w$, then there is a trail from $w$ to $v$.

48. If a graph contains a circuit that starts and ends at a vertex $v$, does the
    graph contain a simple circuit that starts and ends at $v$? Why?

49. Prove that if there is a circuit in a graph that starts and ends at a vertex
    $v$ and if $w$ is another vertex in the circuit, then there is a circuit in
    the graph that starts and ends at $w$.

50. Let $G$ be a connected graph, and let $c$ be any circuit in $G$ that does
    not contain every vertex of $C$. Let $G'$ be the subgraph obtained by
    removing all the edges of $C$ from $G$ and also any vertices that become
    isolated when the edges of $C$ are removed. Prove that there exists a vertex
    $v$ such that $v$ is in both $C$ and $G'$.

51. Prove that any graph with an Euler circuit is connected.

52. Prove Corollary 10.1.5.

53. For what values of $n$ does the complete graph $K_n$ with $n$ vertices have
    (a) an Euler circuit? (b) a Hamiltonian circuit? Justify your answers.

54. For what values of $m$ and $n$ does the complete bipartite graph on $(m, n)$
    vertices have (a) an Euler circuit? (b) a Hamiltonian circuit? Justify your
    answers.

55. What is the maximum number of edges a simple disconnected graph with $n$
    vertices can have? Prove your answer.

56.

a. Prove that if $G$ is any bipartite graph, then every circuit in $G$ has an
even number of edges.

b. Prove that if $G$ is any graph with at least two vertices and if $G$ does not
have a circuit with an odd number of edges, then $G$ is bipartite.

57. An alternative proof for Theorem 10.1.3 has the following outline. Suppose
    $g$ is a connected graph in which every vertex has even degree. Suppose the
    path $C: v_1e_1v_2e_2v_3 \dots e_nv_{n + 1}$ has maximum length in $G$. That
    is, $C$ has at least as many vertices and edges as any other path in $G$.
    First derive a contradiction from the assumption that $v_1 \neq v_n$. Next
    let $H$ be the subgraph of $G$ that contains all the vertices and edges in
    $C$. Then derive a contraction from the assumption that $H \neq G$. Show
    that $H$ contains every vertex of $G$, and show that $H$ contains every edge
    of $G$.
