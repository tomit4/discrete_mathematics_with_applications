Page 516

**Exercise Set 8.1**

1. As in Example 8.1.2, the **congruence modulo $2$** relation $E$ is defined
   from $\mathbb{Z}$ to $\mathbb{Z}$ as follows: For every ordered pair
   $(m, n) \in \mathbb{Z} \times \mathbb{Z}$,

$$ m E n \Leftrightarrow m - n \text{ is even} $$

a. Is $0 E 0$? Is $5 E 2$? Is $(6, 6) \in E$? Is $(-1, 7) \in E$?

_$0 E 0$:_

Yes, $0 - 0 = 0$, and $0$ is even.

_$5 E 2$:_

No, $5 -  2 = 3$, and $3$ is not even.

_$(6, 6) \in E$:_

Yes, $6 - 6 = 0$, and $0$ is even.

_$(-1, 7) \in E$:_

Yes, $-1 - 7 = -8$, and $-8$ is even.

b. Prove that for any even integer $n$, $n E 0$.

**Proof:**

Suppose $n \in 2\mathbb{Z}$, where $2\mathbb{Z}$ is the set of all even
integers.

By the definition for even, this means that $n = 2k$ for some integer $k$.

By the definition for $E$, $n E 0$ if, and only if $n - 0$ is even.

By substitution for $E$:

$$ n - 0 = 2k - 0 $$

$$ = 2k $$

By the definition for even, this means that $n - 0$ is even, and therefore
$n E 0$ is true.

Q.E.D.

2. Prove that for all integers $m$ and $n$, $m - n$ is even if, and only if,
   both $m$ and $n$ are even or both $m$ and $n$ are odd.

_Hint:_ To prove a statement of the form $p \Leftrightarrow (q \vee r)$, you
need to prove both (1)$p \to (q \vee r)$ and (2) $(q \vee r) \to p$. The easiest
way to prove $p \to (q \vee r)$ is to prove the logically equivalent statement
form $(p \wedge \neg q) \to r$. And the easiest way to prove $(q \vee r) \to p$
is to prove the logically equivalent statement form
$(q \to p) \wedge (r \to p)$. In this case, suppose $m$ and $n$ are any
integers, and let $p$ be "$m - n$ is even," let $q$ be "both $m$ and $n$ are
even," and let $r$ be "both $m$ and $n$ are odd."

**Proof:**

Suppose $m$ and $n$ are any integers.

To prove that for all integers $m$ and $n$, $m - n$ is even if, and only if,
both $m$ and $n$ are even or both $m$ and $n$ are odd, it must be shown first
that if $m - n$ is even, then both $m$ and $n$ are even or both $m$ and $n$ are
odd, then it must be shown second that if both $m$ and $n$ are even or both $m$
and $n$ are odd, then $m - n$ is even.

_Proof (first):_

Suppose $m - n$ is even. To prove that both $m$ and $n$ must be even or both $m$
and $n$ must be odd, all cases for where $m$ is even or odd and where $n$ is
even or odd must be considered.

_Case (both $m$ and $n$ are even):_

Since both $m$ and $n$ are even, this means that $m = 2k$ and $n = 2p$ for some
integers $k$ and $p$. Then:

$$ m - n = 2k - 2p $$

$$ = 2(k - p) $$

Now, $k - p$ is an integer by the subtraction of integers. Therefore, by the
definition of even, $m - n$ is even.

_Case (both $m$ and $n$ are odd):_

Since both $m$ and $n$ are odd, this means that $m = 2k + 1$ and $n = 2p + 1$
for some integers $k$ and $p$. Then:

$$ m - n = (2k + 1) - (2p + 1) $$

$$ = 2k + 1 - 2p - 1 $$

$$ = 2k - 2p $$

$$ = 2(k - p) $$

Now, $k - p$ is an integer by the subtraction of integers. Therefore, by the
definition of even, $m - n$ is even.

_Case ($m$ is even and $n$ is odd):_

Since $m$ is even and $n$ is odd, $m = 2k$ and $n = 2p + 1$ for some integers
$k$ and $p$. Then:

$$ m - n = 2k - (2p + 1) $$

$$ = 2k - 2p - 1 $$

$$ = 2(k - p) - 1 $$

Now, $k - p$ is an integer by the subtraction of integers. Thus, by the
definition of odd, $m - n$ is odd, but by the supposition, $m - n$ is even. This
is a contradiction.

_Case ($m$ is odd and $n$ is even):_

Since $m$ is odd and $n$ is even, $m = 2k + 1$ and $n = 2p$ for some integers
$k$ and $p$. Then:

$$ m - n = (2k + 1) - 2p $$

$$ = 2k - 2p + 1 $$

$$ = 2(k - p) + 1 $$

Now, $k - p$ is an integer by the subtraction of integers. Thus, by the
definition of odd, $m - n$ is odd, but by the supposition, $m - n$ is even. This
is a contradiction.

_Conclusion:_

It can be concluded based off of all cases that when both $m$ and $n$ are even
or both $m$ and $n$ are odd, $m - n$ is even.

_Proof (second):_

Suppose both $m$ and $n$ are both even or are both odd.

In order to prove $m - n$ is even, both cases must be considered.

_Case (both $m$ and $n$ are even):_

Since both $m$ and $n$ are even, $m = 2k$ and $n = 2p$ for some integers $k$ and
$p$. Then:

$$ m - n = 2k - 2p $$

$$ = 2(k - p) $$

Now, $k - p$ is an integer by the subtraction of integers. Therefore, by the
definition of even, $m - n$ is even.

_Case (both $m$ and $n$ are odd):_

Since both $m$ and $n$ are odd, $m = 2k + 1$ and $n = 2p + 1$ for some integers
$k$ and $p$. Then:

$$ m - n = (2k + 1) - (2p + 1) $$

$$ = 2k + 1 - 2p - 1 $$

$$ = 2k - 2p $$

$$ = 2(k - p) $$

Now, $k - p$ is an integer by the subtraction of integers. Therefore, by the
definition of even, $m - n$ is even.

_Conclusion:_

In both cases, $m - n$ is even. Therefore it can be concluded that if both $m$
and $n$ are even or if both $m$ and $n$ are odd, then $m - n$ is even.

3. The **congruence modulo $3$** relation, $T$, is defined from $\mathbb{Z}$ to
   $\mathbb{Z}$ as follows: For all integers $m$ and $n$,

$$ m T n \Leftrightarrow 3 | (m - n) $$

a. Is $10 T 1$? Is $1 T 10$? Is $(2, 2) \in T$? Is $(8, 1) \in T$?

_$10 T 1$:_

Yes, since $3 | (10 - 1) = 3 | 9 = 3$

_$1 T 10$:_

Yes, since $3 | (1 - 10) = 3 | -9 = -3$

_$(2, 2) \in T$:_

Yes, since $3 | (2 - 2) = 3 | 0 = 0$

_$(8, 1) \in T$:_

No, since $3 | (8 - 1) = 3 \cancel{|} 7$.

b. List five integers $n$ such that $n T 0$.

$3$; $6$, $9$, $12$, $15$

c. List five integers $n$ such that $n T 1$.

$4$; $7$, $10$, $13$, $16$

d. List five integers $n$ such that $n T 2$.

$$ 3 | (n - 2) $$

$5$, $8$, $11$, $14$, $17$

e. Make and prove a conjecture about which integers are related by $T$ to $0$,
which integers are related to $T$ to $1$, and which integers are related to $T$
to $2$.

_Hint:_ All integers of the form $3k + 1$, for some integer $k$, are related by
$T$ to $1$.

**Conjecture:**

All integers of the form $3k$, for some integer $k$, are related by $T$ to $0$.

All integers of the form $3p + 1$, for some integer $p$, are related by $T$ to
$1$.

All integers of the form $3m + 2$, for some integer $m$, are related to $T$ by
$2$.

4. Define a relation $P$ on $\mathbb{Z}$ as follows: For every ordered pair
   $(m, n) \in \mathbb{Z} \times \mathbb{Z}$,

$$ m P n \Leftrightarrow m \text{ and } n \text{ have a common prime factor} $$

a. Is $15 P 25$?

Yes, because both $15$ and $25$ are divisible by $5$, which is a prime factor.

b. Is $22 P 27$?

No, because $22$ and $27$ have no common divisors.

c. Is $0 P 5$?

Yes, because both $0$ and $5$ are divisible by $5$, which is a prime factor.

d. Is $8 P 8$?

Yes, because both $8$ and $8$ are divisible by $2$, which is a prime factor.

5. Let $X = \{a, b, c\}$. Recall that $\mathscr{P}(X)$ is the power set of $X$.
   Define a relation $\mathbf{S}$ on $\mathscr{P}(X)$ as follows: For all sets
   $A$ and $B$ in $\mathscr{P}(X)$,

$$ A \mathbf{S}B \Leftrightarrow A \text{ has the same number of elements as } B $$

a. Is $\{a, b\} \mathbf{S} \{b, c\}$?

Yes, since both $\{a, b\}$ and $\{b, c}$ have the same number of elements,
namely $2$ elements.

b. Is $\{a\} \mathbf{S} \{a, b\}$?

No, since $\{a\}$ has $1$ element and $\{a, b\}$ has $2$ elements, and
$1 \neq 2$.

c. Is $\{c\} \mathbf{S} \{b\}$?

Yes, since both $\{c\}$ and $\{b\}$ have the same number of elements, namely $1$
element.

6. Let $X = \{a, b, c\}$. Recall that $\mathscr{P}(X)$ as follows: For all sets
   $A$ and $B$ in $\mathscr{P}(X)$,

$$ A \mathbf{J} B \Leftrightarrow A \cap B \neq \emptyset $$

a. Is $\{a\} \mathbf{J} \{c\}$?

No, since $\{a\} \cap \{\c} = \emptyset$.

b. Is $\{a, b\} \mathbf{J} \{b, c\}$?

Yes, since $\{a, b\} \cap \{b, c\} = \{b\} \neq \emptyset$.

c. Is $\{a, b} \mathbf{J} \{a, b, c\}$?

Yes, since $\{a, b\} \cap \{a, b, c\} = \{a, b\} \neq \emptyset$.

7. Define a relation $R$ on $\mathbb{Z}$ as follows: For all integers $m$ and
   $n$,

$$ m R n \Leftrightarrow 5 | (m^2 - n^2) $$

a. Is $1 R (-9)$?

$$ 5 | ((1)^2 - (-9)^2) $$

$$ 5 | (1 - 81) $$

$$ 5 | (-80) = -16 $$

Yes.

b. Is $2 R 13$?

$$ 5 | ((2)^2 - (13)^2) $$

$$ 5 | (4 - 169) $$

$$ 5 | (-165) = -33 $$

Yes.

c. Is $2 R (-8)$?

$$ 5 | ((2)^2 - (-8)^2) $$

$$ 5 | (4 - (64)) $$

$$ 5 | (-60) = -12  $$

Yes.

d. Is $(-8) R 2$?

$$ 5 | (64 - 4) $$

$$ 5 | 60 = 12 $$

Yes.

8. Let $A$ be the set of all strings of _a_'s and _b_'s of length $4$. Define a
   relation $R$ on $A$ as follows: For every $s, t \in A$,

$$ s R t \Leftrightarrow s \text{ has the same first two characters as } t $$

a. Is _abaa_ $R$ _abba_?

Yes, since _ab_ is the same first two characters of both _abaa_ and _abba_.

b. Is _aabb_ $R$ _bbaa_?

No, since _aa_ is the first two characters of _aabb_ and _bb_ is the first same
two characters as _bbaa_, it can be concluded that _aabb_ and _bbaa_ do not have
the same first two characters.

c. Is _aaaa_ $R$ _aaab_?

Yes, since _aa_ is the same first two characters of both _aaaa_ and _aaab_.

d. Is _baaa_ $R$ _abaa_?

No, since _ba_ and _ab_ are the first two characters of _baaa_ and _abaa_
respectively.

9. Let $A$ be the set of all strings of 0's, 1's, and 2's of length $4$. Define
   a relation $R$ on $A$ as follows: For every $s, t \in A$,

$$ s R t \Leftrightarrow \text{ the same of the characters in } s \text{ equals the sum of the characters in } t $$

a. Is 0121 $R$ 2200?

$$ 0 + 1 + 2 + 1 = 4 =  2 + 2 + 0 + 0 $$

Yes.

b. Is 1011 $R$ 2101?

$$ 1 + 0 + 1 + 1 = 3 = \neq 4 = 2 + 1 + 0 + 1 $$

No.

c. Is 2212 $R$ 2121?

$$ 2 + 2 + 1 + 2 = 7 \neq 6 = 2 + 1 + 2 + 1 $$

No.

d. Is 1220 $R$ 2111?

$$ 1 + 2 + 2 + 0 = 5 = 2 + 1 + 1 + 1 $$

Yes.

10. Let $A = \{3, 4, 5\}$ and $B = \{4, 5, 6\}$ and let $R$ be the "less than"
    relation. That is, for every ordered pair $(x, y) \in A \times B$,

$$ x R y \Leftrightarrow x < y $$

State explicitly which ordered pairs are in $R$ and $R^{-1}$.

$$ R = \{(3, 4), (3, 5), (3, 6), (4, 5), (4, 6), (5, 6) \} $$

$$ R^{-1} = \{(4, 3), (5, 3), (6, 3), (5, 4), (6, 4), (6, 5) \} $$

11. Let $A = \{3, 4, 5\}$ and $B = \{4, 5, 6\}$ and let $S$ be the "divides"
    relation. That is, for every ordered pair $(x, y) \in A \times B$,

$$ x S y \Leftrightarrow x | y $$

State explicitly which ordered pairs are in $S$ and $S^{-1}$.

$$ S = \{(3, 6), (4, 4), (5, 5)\} $$

$$ S^{-1} = \{(6, 3), (4, 4), (5, 5)\} $$

12.

a. Suppose a function $F: X \to Y$ is one-to-one but not onto. Is $F^{-1}$ (the
inverse relation for $F$) a function? Explain your answer.

No, if $F: X \to Y$ is one-to-one, but not onto, then its inverse relation
$F^{-1}: Y \to X$ will have some elements in its domain that have not elements
in the co-domain. More formally:

$$ \exists y \in Y | (y, x) \notin F^{-1} $$

which means $F^{-1}$ does not satisfy property 1 for being a function.

b. Suppose a function $F: X \to Y$ is onto but not one-to-one. Is $F^{-1}$ (the
inverse relation for $F$) a function? Explain your answer.

No, if $F: X \to Y$ is onto, but not one-to-one, it follows that its inverse
relation $F^{-1}: Y \to X$ will have at least one
$y \in Y | (y, x_1) \in F^{-1} \wedge (y, x_2) \in F^{-1}$.

This violates property 2 of the definition of a function.

Draw the directed graphs of the relations defined in 13-18.

13. Define a relation $R$ on $A = \{0, 1, 2, 3\}$ by
    $R = \{(0, 0), (1, 2), (2, 2)\}$.

(Done by hand.)

14. Define a relation $S$ on $B = \{a, b, c, d\}$ by
    $S = \{(a, b), (a, c), (b, c), (d, d)\}$.

(Done by hand.)

15. Let $A = \{2, 3, 4, 5, 6, 7, 8\}$ and define a relation $R$ on $A$ as
    follows: For every $x, y \in A$,

$$ x R y \Leftrightarrow x | y $$

(Done by hand.)

16. Let $A = \{5, 6, 7, 8, 9, 10\}$ and define a relation $S$ on $A$ as follows:
    For every $x, y \in A$,

$$ x S y \Leftrightarrow 2 | (x - y) $$

(Done by hand.)

17. Let $A = \{2, 3, 4, 5, 6, 7, 8\}$ and define a relation $T$ on $A$ as
    follows: For every $x, y \in A$,

$$ x T y \Leftrightarrow 3 | (x - y) $$

(Done by hand.)

18. Let $A = \{0, 1, 3, 4, 5, 6\}$ and define a relation $V$ on $A$ as follows:
    For every $x, y \in A$,

$$ x V y \Leftrightarrow 5 | (x^2 - y^2) $$

(Done by hand.)

Exercises 19-20 refer to unions and intersections of relations. Since relations
are subsets of Cartesian products, their unions and intersections can be
calculated as for any subsets. Given two relations $R$ and $S$ from $A$ to $B$,

$$ R \cup S = \{(x, y) \in A \times B | (x, y) \in R \text{ or } (x, y) \in S\} $$

$$ R \cap S = \{(x, y) \in A \times B | (x, y) \in R \text{ and } (x, y) \in S\} $$

19. Let $A = \{2, 4\}$ and $B = \{6, 8, 10\}$ and define relations $R$ and $S$
    from $A$ to $B$ as follows: For every $(x, y) \in A \times B$,

$$ x R y \Leftrightarrow x | y \text{ and } x S y \Leftrightarrow y - 4 = x $$

State explicitly which ordered pairs are in $A \times B$, $R$, $S$, $R \cup S$,
and $R \cap S$.

$$ A \times B = \{(2, 6), (2, 8), (2, 10), (4, 6), (4, 8), (4, 10)\} $$

$$ R = \{(2, 6), (2, 8), (2, 10), (4, 8)\} $$

$$ S = \{(2, 6), (4, 8)\} $$

$$ R \cup S = \{(2, 6), (2, 8), (2, 10), (4, 8)\} = R $$

$$ R \cap S = \{(2, 6), (4, 8)\} = S $$

20. Let $A = \{-1, 1, 2, 4\}$ and $B = \{1, 2\}$ and define relations $R$ and
    $S$ from $A$ to $B$ as follows: For every $(x, y) \in A \times B$,

$$ x R y \Leftrightarrow |x| = |y| \text{ and } x S y \Leftrightarrow x - y \text{ is even} $$

State explicitly which ordered pairs are in $A \times B$, $R$, $S$, $R \cup S$,
and $R \cap S$.

$$ A \times B = \{(-1, 1), (-1, 2), (1, 1), (1, 2), (2, 1), (2, 2), (4, 1), (4, 2)\} $$

$$ R = \{(-1, 1), (1, 1), (2, 2)\} $$

$$ S = \{(-1, 1), (1, 1), (2, 2), (4, 2)\} $$

$$ R \cup S = \{(-1, 1), (1, 1), (2, 2), (4, 2)\} = S $$

$$ R \cap S = \{(-1, 1), (1, 1), (2, 2)\} = R $$

21. Define relations $R$ and $S$ on $\mathbb{R}$ as follows:

$$ R = \{(x, y) \in \mathbb{R} \times \mathbb{R} | x < y\} \text{ and } S = \{(x, y) \in \mathbb{R} \times \mathbb{R} | x = y\}$$

That is, $R$ is the "less than" relation and $S$ is the "equals" relation on
$\mathbb{R}$. Graph $R$, $S$, $R \cup S$, and $R \cap S$ in the Cartesian plane.

Think on this and then see appendix b (Page 975).

22. Define relations $R$ and $S$ on $\mathbb{R}$ as follows:

$$ R = \{(x, y) \in \mathbb{R} \times \mathbb{R} | x^2 + y^2 = 4\} \text{ and } S = \{(x, y) \in \mathbb{R} \times \mathbb{R} | x = y\} $$

Graph $R$, $S$, $R \cup S$, and $R \cap S$ in the Cartesian plane.

23. Define relations $R$ and $S$ on $\mathbb{R}$ as follows:

$$ R = \{(x, y) \in \mathbb{R} \times \mathbb{R} | y = |x|\} \text{ and } S = \{(x, y) \in \mathbb{R} \times \mathbb{R} | y = 1\} $$

Graph $R$, $S$, $R \cup S$, and $R \cap S$ in the Cartesian plane.

$R$ is a circle about the origin (with intersections along the axis along
$(-2, 0), (0, 2), (2, 0), (-2, 0)$). $S$ is a straight diagonal line ascending
from the left to the right, intersecting the origin $(0, 0)$.

$R \cup S$ is just the two graphs drawn together.

$R \cap S$ is only the two points along which the two graphs intersect.

(Done by hand.)

24. In Example 8.1.7 consider the query SELECT Patient_ID#, Name FROM S WHERE
    Primary_Diagnosis = X. The response query is the projection onto the first
    two coordinates of the intersection of the database with the set
    $A_1 \times A_2 \times A_3 \times \{X\}$.

a. Find the result of the query SELECT Patient_ID#, Name FROM S WHERE
Primary_Diagnosis = pneumonia.

(574329, Tak Kurosawa),

(011985, John Schmidt)

b. Find the result of the query SELECT Patient_ID#, Name FROM S WHERE
Primary_Diagnosis = appendicitis.

(466581, Mary Lazars),

(778400, Jamal Baskers)

---

Page 526

**Exercise Set 8.2**

In 1-8, a number of relations are defined on the set $A = \{0, 1, 2, 3\}$. For
each relation:

a. Draw the directed graph.

b. Determine whether the relation is reflexive.

c. Determine whether the relation is symmetric.

d. Determine whether the relation is transitive.

Give a counterexample in each case in which the relation does not satisfy one of
the properties.

1. $R_1 = \{(0, 0), (0, 1), (0, 3), (1, 1), (1, 0), (2, 3), (3, 3)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

No, $2 \cancel{R_1} 2$.

c. Determine whether the relation is symmetric.

No, $0 R_1 3$, but $3 \cancel{R_1} 0$.

d. Determine whether the relation is transitive.

No, $1 R_1 0$ and $0 R_1 3$, but $1 \cancel{R_1} 3$

2. $R_2 = \{(0, 0), (0, 1), (1, 1), (1, 2), (2, 2), (2, 3)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

No, since $3 \cancel{R_2} 3$.

c. Determine whether the relation is symmetric.

No, $0 R_2 1$, but $1 \cancel{R_2} 0$.

d. Determine whether the relation is transitive.

No, $0 R_2 1$ and $1 R_2 2$, but $0 \cancel{R_2} 2$.

3. $R_3 = \{(2, 3), (3, 2)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

No, $2 \cancel{R_3} 2$.

c. Determine whether the relation is symmetric.

Yes, $2 R_3 3$ and $3 R_3 2$.

d. Determine whether the relation is transitive.

No, $2 R_3 3$ and $3 R_3 2$, but $2 \cancel{R_3} 2$.

4. $R_4 = \{(1, 2), (2, 1), (1, 3), (3, 1)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

No, $1 \cancel{R_4} 1$.

c. Determine whether the relation is symmetric.

Yes, $1 R_4 2$ and $2 R_4 1$ and $1 R_4 3$ and $3 R_4 1$.

d. Determine whether the relation is transitive.

No, $1 R_4 2$ and $2 R_4 1$, but $1 \cancel{R_4} 1$.

5. $R_5 = \{(0, 0), (0, 1), (0, 2), (1, 2)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

No, $1 \cancel{R_5} 1$.

c. Determine whether the relation is symmetric.

No, $0 R_5 1$, but $1 \cancel{R_5} 0$.

d. Determine whether the relation is transitive.

Yes, $0 R_5 1$ and $1 R_5 2$, and $0 R_5 2$.

6. $R_6 = \{(0, 1), (0, 2)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

No, $0 \cancel{R_6} 0$.

c. Determine whether the relation is symmetric.

No, $0 R_6 1$, but $1 \cancel{R_6} 0$.

d. Determine whether the relation is transitive.

Yes, vacuously.

7. $R_7 = \{(0, 3), (2, 3)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

No, $0 \cancel{R_7} 0$.

c. Determine whether the relation is symmetric.

No, $0 R_7 3$, but $3 \cancel{R_7} 0$.

d. Determine whether the relation is transitive.

Yes, vacuously.

8. $R_8 = \{(0, 0), (1, 1)\}$

a. Draw the directed graph.

(Done by hand.)

b. Determine whether the relation is reflexive.

Yes, both $0 R_8 0$ and $1 R_8 1$.

c. Determine whether the relation is symmetric.

Yes, since $0 R_8 0$ and $0 R_8 0$, and also $1 R_8 1$ and $1 R_8 1$.

d. Determine whether the relation is transitive.

Yes, vacuously.

In 9-33, determine whether the given relation is reflexive, symmetric,
transitive, or none of these. Justify your answers.

9. $R$ is the "greater than or equal to" relation on the set of real numbers:
   For every $x, y \in \mathbb{R}$, $x R y \Leftrightarrow x \geq y$.

a. Is $R$ reflexive?

Yes, since $\forall x \in \mathbb{R}, x = x$, it follows that
$\forall x \in \mathbb{R}, x \geq x$.

b. Is $R$ symmetric?

No, since $\forall x, y \in \mathbb{R}, x \geq y \to y \geq x$ cannot be true.
Consider the example that $x = 5$ and $y = 4$, then $x \geq y$, but
$y \cancel{\geq} x$.

c. Is $R$ transitive?

Yes, since
$\forall x, y, z \in \mathbb{R}, (x \geq y \wedge y \geq z) \to x \geq z$ is
true by the transitive law of greatness (See appendix A, T18).

10. $C$ is the circle relation on the set of real numbers: For every
    $x, y \in \mathbb{R}, x C y \Leftrightarrow x^2 + y^2 = 1$.

a. Is $C$ reflexive?

No, $C$ is not reflexive. The statement claims that
$\forall x \in \mathbb{R}, x C x \Leftrightarrow x^2 + x^2 = 1$, but consider
$x = 0$, then $0^2 + 0^2 = 1$, but $0 \neq 1$, this is a contradiction.

b. Is $C$ symmetric?

Yes, $C$ is symmetric. The statement claims that
$x, y \in \mathbb{R}, (x^2 + y^2 = 1) \to (y^2 + x^2 = 1)$. This is true by the
commutative laws of addition.

c. Is $C$ transitive?

No, $C$ is not transitive. The statement claims that
$x, y, z \in \mathbb{R}, [(x^2 + y^2 = 1) \wedge (y^2 + z^2 = 1)] \to x^2 + z^2 = 1$.
Consider $x = 1$, $y = 0$, and $z = 1$, then $x^2 + y^2 = (1)^2 + (0)^2 = 1$ and
$y^2 + z^2 = (0)^2 + (1)^2 = 1$, but $x^2 + z^2 = (1)^2 + (1)^2 = 2 \neq 1$.

11. $D$ is the relation defined on $\mathbb{R}$ as follows: For every
    $x, y \in \mathbb{R}, x D y \Leftrightarrow xy \geq 0$.

a. Is $D$ reflexive?

Yes, $D$ is reflexive. $\forall x \in \mathbb{R} x \cdot x \geq 0$ is a true
statement, as even if $x$ is negative, any negative number times itself will
always be positive, and so $x \geq 0$ is true. If $x = 0$, then $x \geq 0$ is a
true statement. If $x$ is positive, then any positive number times itself will
be positive, and so $x \geq 0$ is true.

b. Is $D$ symmetric?

Yes, $D$ is symmetric,
$\forall x, y \in \mathbb{R}, (xy \geq 0) \to (yx \geq 0)$ is true by the
commutative laws of multiplication since $xy = yx$.

c. Is $D$ transitive?

No, $D$ is not transitive. The statement claims
$\forall x, y, z \in \mathbb{R}, [(xy \geq 0) \wedge (yz \geq 0)] \to (xz \geq 0)$.
This is not true, consider $x = 1$, $y = 0$, and $z = -1$, then
$xy = (1)(0) = 0 \geq 0$, and $yz = (0)(-1) = 0 \geq 0$, but
$xz = (1)(-1) = -1 \cancel{\geq} 0$.

12. $E$ is the congruence modulo $4$ relation on $\mathbb{Z}$: For every
    $m, n \in \mathbb{Z}, m E n \Leftrightarrow 4 | (m - n)$.

a. Is $E$ reflexive?

Yes, $E$ is reflexive. The statement claims
$\forall m \in \mathbb{Z}, 4 | (m - m)$. Since any integer subtracted from
itself is $0$, this means that:

$$ 4 | (m - m) = 4 | 0 $$

Which is true since $4 = 4 \cdot 0$.

b. Is $E$ symmetric?

Yes, $E$ is symmetric. The statement claims
$\forall m, n \in \mathbb{Z}, [4 | (m - n)] \to [4 | (n - m)]$.

Since $4 | (m - n)$, this means that $m - n = 4k$ for some integer $k$. It
follows then that:

$$ n - m = -1(m - n) $$

$$ = -1(4k) $$

$$ = 4(-k) $$

Now, $-k$ is an integer by the multiplication of integers. It follows then that
$4 | (n - m)$. This is what was to be shown.

c. Is $E$ transitive?

Yes, $E$ is transitive. The statement claims that
$\forall m, n, p \in \mathbb{Z}, [(4 | (m - n)) \wedge (4 | (n - p))] \to (4 | (m - p))$.

Since $4 | (m - n)$ and $4 | (n - p)$, it can be said that $m - n = 4r$ and
$n - p = 4s$ for some integers $r$ and $s$. It follows by addition of these two
terms, and substitution, that:

$$ (m - n) + (n - p) = 4r + 4s $$

and also that:

$$ (m - n) + (n - p) = m - p $$

Then, setting the substitution equal to the evaluation/simplification:

$$ 4r + 4s = m - p $$

Then, by algebra:

$$ 4(r + s) = m - p $$

Now, $r + s$ is an integer by the sum of integers. It follows that
$4 | (m - p)$. This is what was to be shown.

13. $F$ is the congruence modulo $5$ relation on $\mathbb{Z}$: For every
    $m, n \in \mathbb{Z}, m F n \Leftrightarrow 5 | (m - n)$.

a. Is $F$ reflexive?

Yes, $F$ is reflexive. The statement claims that
$\forall m \in \mathbb{Z}, 5 | (m - m)$. This is true since $m - m = 0$, and
$5 | 0$ is true since $5 = 5 \cdot 0$.

b. Is $F$ symmetric?

Yes, $F$ is symmetric. The statement claims that
$\forall m, n \in \mathbb{Z}, (5 | (m - n)) \to (5 | (n - m))$.

Since $5 | m - n$, it can be said that $m - n = 5k$ for some integer $k$. Then,
consider:

$$ m - n = -1(n - m) $$

By substitution then:

$$ 5k = -1(5k) $$

$$ 5k = 5(-k) $$

Now, $-k$ is an integer by the multiplication of integers. It follows that
$5 | (n - m)$. This is what was to be shown.

c. Is $F$ transitive?

Yes, $F$ is transitive. The statement claims that
$\forall m, n, p \in \mathbb{Z}, [(5 | (m - n)) \wedge (5 | (n - p))] \to [5 | (m - p)]$.

Since $5 | (m - n)$ and $5 | (n - p)$, it can be said that $m - n = 5r$ and
$n - p = 5s$ for some integers $r$ and $s$. Adding $m - n$ and $n - p$ gives
$m - p$:

$$ (m - n) + (n - p) = m - p $$

Then, by substitution:

$$ 5r + 5s = m - p $$

Then, by algebra:

$$ 5(r + s) = m - p $$

Now, $r + s$ is an integer by the sum of integers. It follows that
$5 | (m - p)$. This is what was to be shown.

14. $O$ is the relation defined on $\mathbb{Z}$ as follows: For every
    $m, n \in \mathbb{Z}, m O n \Leftrightarrow m - n \text{ is odd}$.

a. Is $O$ reflexive?

No, $O$ is not reflexive. The statement claims that
$\forall m \in \mathbb{Z}, m - m \text{ is odd}$. Since $m - m = 0$, and $0$ is
even (since $0 = 2(0)$), by the definition of even, $m - m$ cannot be odd.
Therefore $O$ is not reflexive.

b. Is $O$ symmetric?

Yes, $O$ is symmetric. The statement claims that
$\forall m, n \in \mathbb{Z}, (m - n \text{ is odd}) \to (n - m \text{ is odd})$.

Since $m - n$ is odd, it can be said that $m - n = 2k + 1$ for some integer $k$.
Consider that:

$$ m - n = -1(n - m) $$

Then, by substitution:

$$ 2k + 1 = -1(n - m) $$

By algebra:

$$ -1(2k + 1) = n - m $$

$$ -2k - 1 = n - m $$

$$ 2(-k - 1) + 1 = n - m $$

Now, $-k - 1$ is an integer by the multiplication and sum of integers. Therefore
$n - m$ is odd. This is what was to be shown.

c. Is $O$ transitive?

No, $O$ is not transitive. The statement claims that
$\forall m, n, p \in \mathbb{Z} [(m - n \text{ is odd}) \wedge (n - p \text{ is odd})] \to [m - p \text{ is odd}]$.
This is not true for all integers. Consider $m = 2$, $n = 1$, and $p = 0$. Then
$m - n = 2 - 1 = 1 \text{ is odd}$, and $n - p = 1 - 0 = 1 \text{ is odd}$, but
$m - p = 2 - 0 = 2 \text{ is even}$. Therefore $0$ is not transitive.

15. $D$ is the "divides" relation on $\mathbb{Z}^+$: For all positive integers
    $m$ and $n$, $m D n \Leftrightarrow m | n$.

a. Is $D$ reflexive?

Yes, $D$ is reflexive. The statement claims $\forall m \in \mathbb{Z}^+, m | m$.
This is true since any integer divides itself by the definition of divisibility.

b. Is $D$ symmetric?

No, $D$ is not symmetric. The statement claims
$\forall m, n \in \mathbb{Z}^+, (m | n) \to (n | m)$, but this is not true for
all positive integers. Consider $m = 2$ and $n = 4$, then $2 | 4$ is true since
$2 = 2 \cdot 2 = 4$, but $4 \cancel{|} 2$ since $4 \neq 4k = 2$ for some integer
$k$.

c. Is $D$ transitive?

Yes, $D$ is transitive. The statement claims
$\forall m, n, p \in \mathbb{Z}^+, [(m | n) \wedge (n | p)] \to [m | p]$. This
is true by the transitivity of divisibility (see Theorem 4.4.3).

16. $A$ is the "absolute value" relation on $\mathbb{R}$: For all real numbers
    $x$ and $y$, $x A y \Leftrightarrow |x| = |y|$.

a. Is $A$ reflexive?

Yes, $A$ is reflexive. The statement claims
$\forall x \in \mathbb{R}, |x| = |x|$. This is trivially true.

b. Is $A$ symmetric?

Yes, $A$ is symmetric. The statement claims that
$\forall x, y \in \mathbb{R}, (|x| = |y|) \to (|y| = |x|)$. This is true by the
definition of equality.

c. Is $A$ transitive?

Yes, $A$ is transitive. The statement claims that
$\forall x, y, z \in \mathbb{R}, [(|x| = |y|) \wedge (|y| = |z|)] \to |x| = |z|$

This is true by the transitivity of equality (since $|x| = |y| = |z|$).

17. Recall that a prime number is an integer that is greater than $1$ and has no
    positive integer divisors other than $1$ and itself. (In particular, $1$ is
    not prime.) A relation $P$ is defined on $\mathbb{Z}$ as follows: For every
    $m, n \in \mathbb{Z}, m P n \Leftrightarrow \exists \text{ a prime number } p \text{ such that } p | m \text{ and } p | n$.

a. Is $P$ reflexive?

No, $P$ is not reflexive. The statement claims
$\forall m \in \mathbb{Z}, \exists \text{ a prime number } p \text{ such that } p | m$.
Consider $m = 1$ (note that $1 \in \mathbb{Z}$), then there is no such prime
number $p$ that divides $m$.

b. Is $P$ symmetric?

Yes, $P$ is symmetric. The statement claims
$\forall m, n \in \mathbb{Z}, \exists \text{ some prime number } p \text{ such that } p | m \wedge p | n \to p | n \wedge p | m$.

Since there is a prime number $p$ that divides $m$ and $n$, it is trivially true
that $p$ divides $n$ and $m$.

c. Is $P$ transitive?

No, $P$ is not transitive. The statement claims that:

$$ \forall m, n, o \in \mathbb{Z}, [\exists \text{ some prime } p_1, p_1 | m \wedge p_1 | n] \wedge [\exists \text{ some prime } p_2, p_2 | n \wedge p_2 | o] \to [\exists \text{ some prime } p_3, p_3 | m \wedge p_3 | o] $$

But this is not true for all integers $m$, $n$, and $o$.

Consider $m = 6$, $n = 15$, $o = 35$.

Then there exists the prime number $p_1 = 3$ such that $3 | m$ since $3 | 6$
since $6 = 3 \cdot 2$. Additionally, $3 | n$ since $3 | 15$ since
$15 = 3 \cdot 5$, so the first term of the supposition is true.

Next, there exists the prime number $p_2 = 5$ such that $5 | n$ since $5 | 15$
since $15 = 5 \cdot 3$. Additionally $5 | o$ since $5 | 35$ since
$35 = 5 \cdot 7$, so the second term of the supposition is true.

Then, the conclusion claims that there exists some prime $p_3$ such $p_3 | m$
and $p_3 | o$, but the only prime numbers that divide $m$ are $3$ and $2$ since
$m = 6$, and the only prime numbers that divide $o$ are $7$ and $5$ since
$o = 35$. None of these primes are equal to each other, and so $p_3$ does not
exist. Therefore $P$ is not transitive.

18. Define a relation $Q$ on $\mathbb{R}$ as follows: For all real numbers $x$
    and $y$, $x Q y \Leftrightarrow x - y$ is rational.

_Hint:_ $Q$ is reflexive, symmetric, and transitive.

a. Is $Q$ reflexive?

Yes, $Q$ is reflexive. The statement claims that
$\forall x \in \mathbb{R}, x - x \text{ is rational}$. This is true since
$x - x = 0$, and $0$ is rational since $0 = \dfrac{0}{1}$.

b. Is $Q$ symmetric?

Yes, $Q$ is symmetric. The statement claims that
$\forall x, y \in \mathbb{R}, (x - y \text{ is rational }) \to (y - x \text{ is rational})$.

Since $x - y$ is rational, it can be said that $x - y = \dfrac{a}{b}$, where $a$
is some integer and $b$ is some integer with $b \neq 0$. Now, consider that:

$$ x - y = -1(y - x) $$

$$ -1(x - y) = y - x $$

Then, by substitution:

$$ -1\left(\frac{a}{b}\right) = y - x $$

Now, $-1\left(\dfrac{a}{b}\right)$ is a rational number (since $-1$ multiplied
by a rational number is a rational number). Therefore $y - x$ is rational. This
is what was to be shown.

c. Is $Q$ transitive?

Yes, $Q$ is transitive. The statement claims that
$\forall x, y, z \in \mathbb{R}, [(x - y \text{ is rational}) \wedge (y - z \text{ is rational})] \to x - z \text{ is rational}$.

Since $x - y$ is rational and $y - z$ is rational, it can be said that
$x - y = \dfrac{a}{b}$ and $y - z = \dfrac{c}{d}$, where
$a, b, c, d \in \mathbb{Z}$ with $b \neq 0$ and $d \neq 0$.

Then, consider the addition of $x - y$ and $y - z$:

$$ (x - y) + (y - z) = x - z $$

Then, by substitution:

$$ x - z = \frac{a}{b} + \frac{c}{d} $$

$$ = \frac{ad + cb}{bd}$$

Now, $ad + cb$ is an integer by the product and sum of integers, and $bd$ is an
integer by the product of integers and $bd \neq 0$ (since $b \neq 0$ and
$d \neq 0$). Thus $\dfrac{ad + cb}{bd}$ is a rational number, and therefore
$x - z$ is rational. This is what was to be shown.

19. Define a relation $I$ on $\mathbb{R}$ as follows: For all real numbers $x$
    and $y$, $x I y \Leftrightarrow x - y$ is irrational.

a. Is $I$ reflexive?

No, $I$ is not reflexive. The statement claims that
$\forall x \in \mathbb{R}, x - x \text{ is irrational}$. Since $x - x = 0$, and
$0 = \dfrac{0}{1}$, it follows that $x - x$ is rational. Therefore $I$ is not
reflexive.

b. Is $I$ symmetric?

Yes, $I$ is symmetric. The statement claims
$\forall x, y \in \mathbb{R}, (x - y \text{ is irrational}) \to (y - x \text{ is irrational})$.

Consider that:

$$ x - y = -1(y - x) $$

$$ -1(x - y) = y - x $$

Now, the product of $-1$ and an irrational number ($x - y$) is irrational. It
follows that $y - x$ is irrational. This is what was to be shown.

c. Is $I$ transitive?

The statement claims that
$\forall x, y, z \in \mathbb{R}, [(x - y \text{ is irrational}) \wedge (y - z \text{ is irrational})] \to x - z \text{ is irrational}$.
But this is not true for all integers $x$, $y$, and $z$.

Consider $x = \sqrt{2}$, $y = 0$, and $z = \sqrt{2}$.

Then $x - y = \sqrt{2} - 0 = \sqrt{2}$, which is irrational. Additionally,
$y - z = 0 - \sqrt{2} = -\sqrt{2}$, which is irrational. Thus the supposition is
true.

Then $x - z = \sqrt{2} - \sqrt{2} = 0$, which is rational (since
$0 = \dfrac{0}{1}$). Therefore $I$ is not transitive.

20. Let $X = \{a, b, c\}$ and $\mathscr{P}(X)$ be the power set of $X$ (the set
    of all subsets of $X$). A relation $\mathbf{E}$ is defined on
    $\mathscr{P}(X)$ as follows: For every
    $A, B \in \mathscr{P}(X), A \mathbf{E} B \Leftrightarrow \text{ the number of elements in } A \text{ equals the number of elements in } B$.

a. Is $E$ reflexive?

Yes, $E$ is reflexive. The statement claims that
$\forall A \in \mathscr{P}(X), \text{ the number of elements in } A \text{ equals the number of elements in } A$.

This is trivially true.

b. Is $E$ symmetric?

Yes, $E$ is symmetric. The statement claims that
$\forall A, B \in \mathscr{P}(X), (\text{the number of elements in } A \text{ equals the number of elements in } B) \to (\text{the number of elements in } B \text{ equals the number of elements in } A)$.

This is trivially true (by the commutative laws of equality).

c. Is $E$ transitive?

Yes, $E$ is transitive. The statement claims that
$\forall A, B, C \in \mathscr{P}(X), [(\text{ the
number of elements in } A \text{ equals the number of elements in } B) \wedge
(\text{ the number of elements in } B \text{ equals the number of elements in }
C)] \to \text{the number of elements in } A \text{ equals the number of elements
in } C$.

This is trivially true (by the transitivity of equality).

21. Let $X = \{a, b, c\}$ and $\mathscr{P}(X)$ be the power set of $X$. A
    relation $\mathbf{L}$ is defined on $\mathscr{P}(X)$ as follows: For every
    $A, B \in \mathscr{P}(X), A \mathbf{L} B \Leftrightarrow \text{ the number of elements in } A \text{ is less than the number of elements in } B$.

a. Is $L$ reflexive?

No, $L$ is not reflexive. The statement claims
$\forall A \in \mathscr{P}(X), \text{ the number of elements in } A \text{ is less than the number of elements in } A$.

This cannot be true, since the number of elements in $A$ will always equal the
number of elements in $A$.

b. Is $L$ symmetric?

No, $L$ is not symmetric. The statement claims that
$\forall A, B \in \mathscr{P}(X), (\text{the number of elements in } A \text{ is less than the number of elements in } B) \to (\text{the number of elements in } B \text{ is less than the number of elements in } A)$.

Let $x= \text{ the number of elements in } A$ and
$y = \text{ the number of elements in } B$. Then, by the supposition, $x < y$.
By the definition of inequality, this means that $y \cancel{<} x$. Therefore $L$
is not symmetric.

c. Is $L$ transitive?

Yes, $L$ is transitive. The statement claims that
$\forall A, B, C \in \mathscr{P}(X), [(\text{the number of elements in } A \text{ is less than the number of elements in } B) \wedge (\text{the number of elements in } B \text{ is less than the number of elements in } C)] \to \text{ the number of elements in } A \text{ is less than the number of elements in } C$.

Let $x = \text{ the number of elements in } A$,
$y = \text{ the number of elements in } B$, and
$z = \text{ the number of elements in } C$.

Then, by the supposition, $x < y$ and $y < z$. Since $x < y < z$ (by the
transitivity of inequality), it follows that $x < z$. This is what was to be
shown. Therefore $L$ is transitive.

22. Let $X = \{a, b, c\}$ and $\mathscr{P}(X)$ be the power set of $X$. A
    relation $\mathbf{N}$ is defined on $\mathscr{P}(X)$ as follows: For every
    $A, B \in \mathscr{P}(X), A \mathbf{N} B \Leftrightarrow \text{ the number of elements in } A \text{ is not equal to the number of elements in } B$.

a. Is $\mathbf{N}$ reflexive?

No, $\mathbf{N}$ is not reflexive. The statement claims
$\forall A \in \mathscr{P}(X), \text{ the number of elements in } A \text{ is not equal to the number of elements in } A$.

This is trivially false.

b. Is $\mathbf{N}$ symmetric?

Yes, $\mathbf{N}$ is symmetric. The statement claims
$\forall A, B \in \mathscr{P}(X), (\text{the number of elements in } A \text{ is not equal to the number of elements in } B) \to (\text{ the number of elements in } B \text{ is not equal to the number of elements in } A)$.

This is true.

Let $x = \text{ the number of elements in } A$,
$y = \text{ the number of elements in } B$. Then, by the supposition,
$x \neq y$. It follows by the definition of inequality that $y \neq x$.

Therefore $\mathbf{N}$ is symmetric.

c. Is $\mathbf{N}$ transitive?

No, $\mathbf{N}$ is not transitive. The statement claims
$\forall A, B, C \in \mathscr{P}(X), [(\text{the number of elements in } A \text{ is not equal to the number of elements in } B) \wedge (\text{the number of elements in } B \text{ is not equal to the number of elements in } C)] \to \text{the number of elements in } A \text{ is not equal to the number of elements in } C$.
But this is not true for all subsets $A$, $B$, and $C$.

Consider $A = \{a\}$, $B = \{a, b\}$, and $C = \{c\}$.

Then, by the supposition, the number of elements in $A$ does not equal the
number of elements in $B$, and the number of elements in $B$ does not equal the
number of elements in $C$, but the number of elements in $A$ is equal to the
number of elements in $C$.

Therefore, $\mathbf{N}$ is not transitive.

23. Let $X$ be a nonempty set and $\mathscr{P}(X)$ the power set of $X$. Define
    the "subset" relation $\mathbf{S}$ on $\mathscr{P}(X)$ as follows: For every
    $A, B \in \mathscr{P}(X), A \mathbf{S} B \Leftrightarrow A \subseteq B$.

a. Is $\mathbf{S}$ reflexive?

Yes, $\mathbf{S}$ is reflexive. The statement claims
$\forall A \in \mathscr{P}(X), A \subseteq A$. By the definition of subset, this
is true.

b. Is $\mathbf{S}$ symmetric?

No, $\mathbf{S}$ is not symmetric. The statement claims
$\forall A, B \in \mathscr{P}(X), (A \subseteq B) \to (B \subseteq A)$.

Consider $X = \{1, 2, 3\}$, $A = \{1\}$, $B = \{1, 2\}$. Then, by the
supposition $A, B \in \mathscr{P}(X)$, and $A \subseteq B$, but
$B \nsubseteq A$. Therefore $\mathbf{S}$ is not symmetric.

c. Is $\mathbf{S}$ transitive?

Yes, $\mathbf{S}$ is transitive. The statement claims that
$\forall A, B, C \in \mathscr{P}(X), [(A \subseteq B) \wedge (B \subseteq C)] \to [A \subseteq C]$.

By the supposition $A \subseteq B$ and $B \subseteq C$, it follows by the
transitivity property of subset that $A \subseteq B \subseteq C$, and thus
$A \subseteq C$. Therefore $\mathbf{S}$ is transitive.

24. Let $X$ be a nonempty set and $\mathscr{P}(X)$ the power set of $X$. Define
    the "not equal to" relation $\mathbf{U}$ on $\mathscr{P}(X)$ as follows: For
    every $A, B \in \mathscr{P}(X), A \mathbf{U} B \Leftrightarrow A \neq B$.

a. Is $\mathbf{U}$ reflexive?

No, $\mathbf{U}$ is not reflexive. The statement claims
$\forall A \in \mathscr{P}(X), A \neq A$. This is trivially false.

b. Is $\mathbf{U}$ symmetric?

Yes, $\mathbf{U}$ is symmetric. The statement claims
$\forall A, B \in \mathscr{P}, (A \neq B) \to (B \neq A)$. This is true by the
definition of inequality.

c. Is $\mathbf{U}$ transitive?

No, $\mathbf{U}$ is not transitive. The statement claims
$\forall A, B, C \in \mathscr{P}, [(A \neq B) \wedge (B \neq C)] \to [A \neq C]$.

Let $X = \{1, 2, 3\}$, $A = \{1\}$, $B = \{2\}$, and $C = \{1\}$. Then, by the
supposition, $A, B, C \in \mathscr{P}(X)$, $A \neq B$ and $B \neq C$, but
$A = C$.

Therefore $\mathbf{U}$ is not transitive.

25. Let $A$ be the set of all strings of _a_'s and _b_'s of length $4$. Define a
    relation $R$ on $A$ as follows: For every
    $s, t \in A, s R t \Leftrightarrow s \text{ has the same first two characters as } t$.

a. Is $R$ reflexive?

Yes, $R$ is reflexive. The statement claims
$\forall s \in A, s \text{ has the same first two characters as } s$. This is
trivially true.

b. Is $R$ symmetric?

Yes, $R$ is symmetric. The statement claims
$\forall s, t \in A, (s \text{ has the same first two characters as } t) \to (t \text{ has the same first two characters as} s)$.

This is trivially true.

c. Is $R$ transitive?

Yes, $R$ is transitive. The statement claims
$\forall s, t, u \in A, [(s \text{ has the same first two characters as } t) \wedge (t \text{ has the same first two characters as } u)] \to s \text{ has the same first two characters as } u$.

This is true by the transitivity of equality, since $s$ and $t$ have the same
first two characters, and $t$ and $u$ have the same first two characters, it
follows that $s$ and $u$ have the same first two characters. Therefore $R$ is
transitive.

26. Let $A$ be the set of all strings of 0's, 1's, and 2's that have length 4
    and for which the sum of the characters in the string is less than or equal
    to 2. Define a relation $R$ on $A$ as follows: For every
    $s, t \in A, s R t \Leftrightarrow \text{ the sum of the characters of } s \text{ equals the sum of the characters of } t$.

a. Is $R$ reflexive?

Yes, $R$ is reflexive. The statement claims
$\forall s \in A, \text{ the sum of the characters of } s \text{ equals the sum of the characters of } s$.
This is trivially true.

b. Is $R$ symmetric?

Yes, $R$ is symmetric. The statement claims
$\forall s, t \in A, (\text{ the sum of the characters of} s \text{ equals the sum of the characters of } t) \to (\text{ the sum of the characters of } t \text{ equals the sum of the characters of } s)$.

Let $x = \text{ the sum of the characters of } s$ and
$y = \text{ the sum of the characters of } t$. Then, by the supposition,
$x = y$. It follows by symmetry of equality that $y = x$. This is what was to be
shown. Therefore $R$ is symmetric.

c. Is $R$ transitive?

Yes, $R$ is transitive. The statement claims
$\forall s, t, u \in A, [(\text{ the sum of the characters of } s \text{ equals the sum of the characters of } t) \wedge (\text{ the sum of the characters of } t \text{ equals the sum of the characters of } u)] \to \text{ the sum of the characters of } s \text{ equals the sum of the characters of } u$.

Let $x = \text{ the sum of the characters of } s$,
$y = \text{ the sum of the characters of } t$, and
$z = \text{ the sum of the characters of } u$.

By the supposition $x = y$ and $y = z$. By the transitivity of equality,
$x = y = z$, and it follows that $x = z$. This is what was to be shown.
Therefore $R$ is transitive.

27. Let $A$ be the set of all English statements. A relation $\mathbf{I}$ is
    defined on $A$ as follows: For every $p, q \in A$,

$$ p \mathbf{I} q \Leftrightarrow p \to q \text{ is true} $$

a. Is $\mathbf{I}$ reflexive?

Yes $\mathbf{I}$ is reflexive. The statement claims
$\forall p \in A, p \to p \text{ is true}$. This is true by the law of identity
(tautology).

b. Is $\mathbf{I}$ symmetric?

No, $\mathbf{I}$ is not symmetric. The statement claims
$\forall p, q \in A, (p \to q) \to (q \to p)$.

Consider $p$ is the statement "All pigs can fly", and $q$ is the statement "The
sky is blue". Then, by the supposition $p, q \in A$, and $p \to q$ is vacuously
true. But, $q \to p$ is false, since $q$ is true and $p$ is false.

Therefore $\mathbf{I}$ is not symmetric.

c. Is $\mathbf{I}$ transitive?

Yes, $\mathbf{I}$ is transitive. The statement claims
$\forall p, q, r \in A, [(p \to q) \wedge (q \to r)] \to (p \to r)$.

This is true, since $p \to q$ and $q \to r$ is true, it follows that
$p \to q \to r$, and that $p \to r$ is true.

28. Let $A = \mathbb{R} \times \mathbb{R}$. A relation $\mathbf{F}$ is defined
    on $A$ as follows: For every $(x_1, y_1)$ and $(x_2, y_2)$ in $A$,

$$ (x_1, y_2) \mathbf{F} (x_2, y_2) \Leftrightarrow x_1 = x_2 $$

a. Is $\mathbf{F}$ reflexive?

Yes, $\mathbf{F}$ is reflexive. The statement claims
$\forall (x_1, y_1) \in A, x_1 = x_1$. This is trivially true.

b. Is $\mathbf{F}$ symmetric?

Yes, $\mathbf{F}$ is symmetric. The statement claims
$\forall (x_1, y_1), (x_2, y_2) \in A, (x_1 = x_2) \to (x_2 = x_1)$.

This is true by the symmetry of equality.

c. Is $\mathbf{F}$ transitive?

The statement claims
$\forall (x_1, y_1), (x_2, y_2), (x_3, y_3) \in A, [(x_1 = x_2) \wedge (x_2 = x_3)] \to x_1 = x_3$.

This is true by the transitivity of equality.

29. Let $A = \mathbb{R} \times \mathbb{R}$. A relation $\mathbf{S}$ is defined
    on $A$ as follows: For every $(x_1, y_1)$ and $(x_2, y_2)$ in $A$,

$$ (x_1, y_2) \mathbf{S} (x_2, y_2) \Leftrightarrow y_1 = y_2 $$

a. Is $\mathbf{S}$ reflexive?

Yes, $\mathbf{S}$ is reflexive. The statement claims
$\forall (x_1, y_1) \in A, y_1 = y_1$. This is trivially true.

b. Is $\mathbf{S}$ symmetric?

Yes, $\mathbf{S}$ is symmetric. The statement claims
$\forall (x_1, y_1), (x_2, y_2) \in A, (y_1 = y_2) \to (y_2 = y_1)$.

This is true by the symmetry of equality.

c. Is $\mathbf{S}$ transitive?

Yes, $\mathbf{S}$ is transitive. The statement claims
$\forall (x_1, y_1), (x_2, y_2), (x_3, y_3) \in A, [(y_1 = y_2) \wedge (y_2 = y_3)] \to y_1 = y_3$.

This is true by the transitivity of equality.

30. Let $A$ be the "punctured plane"; that is, $A$ is the set of all points in
    the Cartesian plane except the origin $(0, 0)$. A relation $R$ is defined on
    $A$ as follows: For every $p_1$ and $p_2$ in $A$,
    $p_1 R p_2 \Leftrightarrow p_1 \text{ and } p_2 \text{ lie on the same half line emanating from the origin}$.

a. Is $$ reflexive?

b. Is $$ symmetric?

c. Is $$ transitive?

31. Let $A$ be the set of people living in the world today. A relation $R$ is
    defined on $A$ as follows: For all people $p$ and $q$ in $A$,

$$ p R q \Leftrightarrow p \text{ lives within 100 miles of } q $$

a. Is $$ reflexive?

Omitted.

b. Is $$ symmetric?

Omitted.

c. Is $$ transitive?

Omitted.

32. Let $A$ be the set of all lines in the plane. A relation $R$ is defined on
    $A$ as follows: For every $l_1$ and $l_2$ in $A$,
    $l_1 R l_2 \Leftrightarrow l_1 \text{ is parallel to } l_2$. (Assume that a
    line is parallel to itself.)

a. Is $$ reflexive?

Omitted.

b. Is $$ symmetric?

Omitted.

c. Is $$ transitive?

Omitted.

33. Let $A$ be the set of all lines in the plane. A relation $R$ is defined on
    $A$ as follows: For every $l_1$ and $l_2$ in $A$,

$$ l_1 R l_2 \Leftrightarrow l_1 \text{ is perpendicular to } l_2 $$

a. Is $$ reflexive?

Omitted.

b. Is $$ symmetric?

Omitted.

c. Is $$ transitive?

Omitted.

In 34-36, assume that $R$ is a relation on a set $A$. Prove or disprove each
statement.

34. If $R$ is reflexive, then $R^{-1}$ is reflexive.

**Proof:**

Suppose $R$ is any relation on a set $A$, such that $R$ is reflexive.

By the definition of reflexive, this means that $\forall x \in A, (x, x) \in R$,
or $\forall x \in A, x R x$. Then, by definition of an inverse relation, it
follows that $(x, x) \in R^{-1}$, or $x R^{-1} x$.

Therefore, $R^{-1}$ is reflexive.

Q.E.D.

35. If $R$ is symmetric, then $R^{-1}$ is symmetric.

**Proof:**

Suppose $R$ is any relation on a set $A$, such that $R$ is symmetric.

By the definition of symmetric, this means that
$\forall (x, y) \in A, (x, y) \in R \to (y, x) \in R$. Since $(y, x) \in R$, it
follows, by definition of inverse relation, that $(x, y) \in R^{-1}$.
Furthermore, since $(x, y) \in R$, it follows that $(y, x) \in R^{-1}$.

Therefore $R^{-1}$ is symmetric.

Q.E.D.

36. If $R$ is transitive, then $R^{-1}$ is transitive.

**Proof:**

Suppose $R$ is any relation on a set $A$ such that $R$ is transitive.

By the definition of transitive, this means that
$\forall x, y, z \in A, [(x, y) \in R \wedge (y, z) \in R] \to (x, z) \in R$.

Since $(x, y), (y, z), (x, z) \in R$, it follows by the definition of inverse
that $(y, x), (z, y), (z, x) \in R^{-1}$. This means that
$\forall x, y, z \in A, [(z, y) \in R^{-1} \wedge (y, x) \in R^{-1}] \to (z, x) \in R^{-1}$.

Therefore $R^{-1}$ is transitive.

Q.E.D.

In 37-42, assume that $R$ and $S$ are relations on a set $A$. Prove or disprove
each statement.

37. If $R$ and $S$ are reflexive, is $R \cap S$ reflexive? Why?

$R \cap S$ is reflexive.

**Proof:**

Suppose $R$ and $S$ are any relations on some set $A$ such that $R$ and $S$ are
reflexive.

By the definition of reflexive, this means that $\forall x \in A, (x, x) \in R$,
and $\forall x \in A, (x, x) \in S$.

Since $(x, x) \in R$ and $(x, x) \in S$, it follows (by the definition of
intersection), that $(x, x) \in R \cap S$.

Therefore $R \cap S$ is reflexive.

Q.E.D.

38. If $R$ and $S$ are symmetric, is $R \cap S$ symmetric? Why?

$R \cap S$ is symmetric.

**Proof:**

Suppose $R$ and $S$ are any relations on a set $A$ such that $R$ and $S$ are
symmetric.

By the definition of symmetric, this means that
$\forall x, y \in A, (x, y) \in R \to (y, x) \in R$. Similarly,
$\forall x, y \in A, (x, y) \in S \to (y, x) \in S$.

Since $(x, y) \in R$, $(y, x) \in R$, $(x, y) \in S$, $(y, x) \in S$, it follows
by the definition of intersection that $(x, y) \in R \cap S$ and
$(y, x) \in R \cap S$.

Therefore $R \cap S$ is symmetric.

Q.E.D.

39. If $R$ and $S$ are transitive, is $R \cap S$ transitive? Why?

$R \cap S$ is transitive.

**Proof:**

Suppose $R$ and $S$ are any relations on a set $A$ such that $R$ and $S$ are
transitive.

By the definition of transitive, this means that
$\forall x, y, z \in A, [(x, y) \in R \wedge (y, z) \in R] \to (x, z) \in R$.
Similarly,
$\forall x, y, z \in A, [(x, y) \in S \wedge (y, z) \in S] \to (x, z) \in S$.

Since $(x, y), (y, z), (x, z) \in R$ and $(x, y), (y, z), (x, z) \in S$, it
follows by the definition of intersection that
$(x, y), (y, z), (x, z) \in (R \cap S)$. Furthermore, this means that
$\forall x, y, z \in A, [(x, y) \in (R \cap S) \wedge (y, z) \in (R \cap S)] \to (x, z) \in (R \cap S)$.

Therefore, by the definition of transitive, $R \cap S$ is transitive.

Q.E.D.

40. If $R$ and $S$ are reflexive, is $R \cup S$ reflexive? Why?

$R \cup S$ is reflexive.

**Proof:**

Suppose $R$ and $S$ are any relations on some set $A$ such that $R$ and $S$ are
reflexive.

By the definition of reflexive, this means that $\forall x \in A, (x, x) \in R$,
and $\forall x \in A, (x, x) \in S$.

Since $(x, x) \in R$ and $(x, x) \in S$, it follows (by the definition of
union), that $(x, x) \in R \cup S$ (since in order to satisfy the definition of
union, $(x, x) \in R$ _or_ $(x, x) \in S$).

Therefore $R \cup S$ is reflexive.

Q.E.D.

41. If $R$ and $S$ are symmetric, is $R \cup S$ symmetric? Why?

$R \cup S$ is symmetric.

**Proof:**

Suppose $R$ and $S$ are any relations on a set $A$ such that $R$ and $S$ are
symmetric.

By the definition of symmetric, this means that
$\forall x, y \in A, (x, y) \in R \to (y, x) \in R$. Similarly,
$\forall x, y \in A, (x, y) \in S \to (y, x) \in S$.

Since $(x, y) \in R$, $(y, x) \in R$, $(x, y) \in S$, $(y, x) \in S$, it follows
by the definition of union that $(x, y) \in R \cup S$ and $(y, x) \in R \cup S$
(since in order to satisfy the definition of union, $(x, y) \in R$ and
$(y, x) \in R$ _or_ $(x, y ) \in S$ and $(y, x) \in S$).

Therefore $R \cup S$ is symmetric.

Q.E.D.

42. If $R$ and $S$ are transitive, is $R \cup S$ transitive? Why?

**Disproof (by counterexample):**

Let $A = \{a, b, c, d\}$, $R = {(a, b), (b, c), (a, c)}$, and
$S = \{(b, c), (c, d), (b, d)\}$. Note that $R$ and $S$ are transitive. However,
when we take the union, $R \cup S$:

$$ (R \cup S) = \{(a, b), (b, c), (a, c), (c, d), (b, d)\} $$

Note that $(a, b), (b, d) \in (R \cup S)$, but $(a, d) \notin (R \cup S)$. By
the definition of transitive, it follows that $R \cup S$ is not transitive.

Q.E.D.

In 43-50, the following definitions are used: A relation on a set $A$ is defined
to be

irreflexive if, and only if, for every $x \in A, x \cancel{R} x$;

asymmetric if, and only if, for every $x, y \in A$ if $x R y$ then
$y \cancel{R} x$;

intransitive if, and only if, for every $x, y, z \in A$, if $x R y$ and $y R z$
then $x \cancel{R} z$.

For each of the relations in the referenced exercise, determine whether the
relation is irreflexive, asymmetric, intransitive, or none of these.

43. Exercise 1

$R_1 = \{(0, 0), (0, 1), (0, 3), (1, 1), (1, 0), (2, 3), (3, 3)\}$

a. Irreflexive?:

No, since $0 R_1 0$, $R_1$ is not irreflexive.

b. Asymmetric?:

No, since $(0, 1) \in R_1$ and $(1, 0) \in R_1$, $R_1$ is not asymmetric.

c. Intransitive?:

No, since $(0, 1), (1, 0), (0, 0) \in R_1$, $R_1$ is not intransitive.

44. Exercise 2

$R_2 = \{(0, 0), (0, 1), (1, 1), (1, 2), (2, 2), (2, 3)\}$

a. Irreflexive?:

No, since $0 R_2 0$, $R_2$ is not irreflexive.

b. Asymmetric?:

No, since $(0, 0) \in R_2$ and $(0, 0) \in R_2$, $R_2$ is not asymmetric.

c. Intransitive?:

No, since $(1, 1), (1, 2), (2, 2) \in R_2$, $R_2$ is not intransitive.

45. Exercise 3

$R_3 = \{(2, 3), (3, 2)\}$

a. Irreflexive?:

Yes, $R_3$ is irreflexive.

b. Asymmetric?:

No, since $(2, 3), (3, 2) \in R_3$, $R_3$ is not asymmetric.

c. Intransitive?:

Yes, since $(2, 3), (3, 2) \in R_3$, but $(2, 2) \notin R_3$, $R_3$ is
intransitive.

46. Exercise 4

$R_4 = \{(1, 2), (2, 1), (1, 3), (3, 1)\}$

a. Irreflexive?:

Yes, $R_4$ is irreflexive.

b. Asymmetric?:

No, since $(1, 2), (2, 1) \in R_4$, $R_4$ is not asymmetric.

c. Intransitive?:

Yes, $R_4$ is intransitive.

$$ (1, 2), (2, 1) \in R_4, \text{ but } (1, 1) \notin R_4 $$

$$ (2, 1), (1, 3) \in R_4, \text{ but } (2, 3) \notin R_4 $$

$$ (1, 3), (3, 1) \in R_4 , \text{ but } (1, 1) \notin R_4 $$

etc. (note that a more rigorous proof would check all examples.)

47. Exercise 5

$R_5 = \{(0, 0), (0, 1), (0, 2), (1, 2)\}$

a. Irreflexive?:

No, since $(0, 0) \in R_5$

b. Asymmetric?:

No, since $(0, 0) \in R_5$ and $(0, 0) \in R_5$.

c. Intransitive?:

No, since $(0, 1), (1, 2), (0, 2) \in R_5$.

48. Exercise 6

$R_6 = \{(0, 1), (0, 2)\}$

a. Irreflexive?:

Yes.

b. Asymmetric?:

Yes.

c. Intransitive?:

Yes, since there is no $(1, x)$ for some element $x$, nor is there $(2, y)$ for
some element $y$, the supposition is always false, and is therefore the if/then
proposition is vacuously true.

49. Exercise 7

$R_7 = \{(0, 3), (2, 3)\}$

a. Irreflexive?:

Yes.

b. Asymmetric?:

Yes.

c. Intransitive?:

Yes (see Exercise 48 for vacuous truth explanation, which applies here as well.)

50. Exercise 8

$R_8 = \{(0, 0), (1, 1)\}$

a. Irreflexive?:

No, since $(0, 0) \in R_8$.

b. Asymmetric?:

No, since $(0, 0) \in R_8$.

c. Intransitive?:

No, since $(0, 0), (0, 0), (0, 0) \in R_8$.

In 51-53, $R$, $S$, and $T$ are relations defined on $A = \{0, 1, 2, 3\}$.

51. Let $R = \{(0, 1), (0, 2), (1, 1), (1, 3), (2, 2), (3, 0)\}$.

Find $R^t$, the transitive closure of $R$.

First, by definition of the transitive closure, $R \subseteq R^t$, so (building
$R^t$, _i.e._ not finished):

$$ R^t = \{(0, 1), (0, 2) (1, 1), (1, 3), (2, 2), (3, 0)\} $$

Since $R^t$ must be transitive, every ordered pair triple must have a transitive
"third":

$$ (0, 1), (1, 1) \to (0, 1) $$

$$ (0, 1), (1, 3) \to (0, 3) $$

$$ (0, 2), (2, 2) \to (0, 2) $$

$$ (1, 1), (1, 3) \to (1, 3) $$

$$ (1, 3), (3, 0) \to (1, 0) $$

$$ (3, 0), (0, 1) \to (3, 1) $$

$$ (3, 0), (0, 2) \to (3, 2) $$

Now, add all missing ordered pairs to $R^t$:

$$ R^t = \{(0, 1), (0, 2), (0, 3), (1, 0), (1, 1), (1, 3), (2, 2), (3, 0), (3, 1), (3, 2)\} $$

Now, check to be sure all ordered triples yields:

$$ (3, 1), (1, 3) \to (3, 3) $$

$$ \boxed{R^t = \{(0, 1), (0, 2), (0, 3), (1, 0), (1, 1), (1, 3), (2, 2), (3, 0), (3, 1), (3, 2), (3, 3)\}} $$

52. Let $S = \{(0, 0), (0, 3), (1, 0), (1, 2), (2, 0), (3, 2)\}$.

Find $S^t$, the transitive closure of $S$.

$$ S^t = \{(0, 0), (0, 3), (1, 0), (1, 2), (2, 0), (3, 2)\} $$

Then:

$$ (0, 0), (0, 3) \to (0, 3) $$

$$ (0, 3), (3, 2) \to (0, 2) $$

$$ (1, 0), (0, 0) \to (1, 0) $$

$$ (1, 0), (0, 3) \to (1, 3) $$

$$ (1, 2), (2, 0) \to (1, 0) $$

$$ (2, 0), (0, 0) \to (2, 0) $$

$$ (2, 0), (0, 3) \to (2, 3) $$

$$ (3, 2), (2, 0) \to (3, 0) $$

New:

$$ S^t = \{(0, 0), (0, 2), (0, 3), (1, 0), (1, 2), (1, 3), (2, 0), (2, 3), (3, 0), (3, 2)\} $$

Check again:

$$ (2, 0), (0, 2) \to (2, 2) $$

$$ (3, 0), (0, 3) \to (3, 3) $$

Finally:

$$ S^t = \{(0, 0), (0, 2), (0, 3), (1, 0), (1, 2), (1, 3), (2, 0), (2, 2), (2, 3), (3, 0), (3, 2), (3, 3)\} $$

53. Let $T = \{(0, 2), (1, 0), (2, 3), (3, 1)\}$.

Find $T^t$, the transitive closure of $T$.

$$ $T^t = \{(0, 2), (1, 0), (2, 3), (3, 1)\}. $$

$$ (0, 2), (2, 3) \to (0, 3) $$

$$ (1, 0), (0, 2) \to (1, 2) $$

$$ (2, 3), (3, 1) \to (2, 1) $$

$$ (3, 1), (1, 0) \to (3, 0) $$

Now:

$$ $T^t = \{(0, 2), (0, 3), (1, 0), (1, 2), (2, 1), (2, 3), (3, 0), (3, 1)\}. $$

Furthermore:

$$ (0, 2), (2, 1) \to (0, 1) $$

$$ (0, 3), (3, 0) \to (0, 0) $$

$$ (1, 0), (0, 3) \to (1, 3) $$

$$ (1, 2), (2, 1) \to (1, 1) $$

$$ (2, 3), (3, 0) \to (2, 0) $$

Now:

$$ $T^t = \{(0, 0), (0, 1), (0, 2), (0, 3), (1, 0), (1, 1), (1, 2), (1, 3), (2,
0), (2, 1), (2, 3), (3, 0), (3, 1)\}. $$

And:

$$ (2, 1), (1, 2) \to (2, 2) $$

$$ (3, 1), (1, 2) \to (3, 2) $$

$$ (3, 1), (1, 3) \to (3, 3) $$

So:

$$ $T^t = \{(0, 0), (0, 1), (0, 2), (0, 3), (1, 0), (1, 1), (1, 2), (1, 3), (2,
0), (2, 1), (2, 2), (2, 3), (3, 0), (3, 1), (3, 2), (3, 3)\}. $$

54. Write a computer algorithm to test whether a relation $R$ defined on a
    finite set $A$ is reflexive, where

$$ A = \{a[1], a[2], \dots, a[n]\} $$

Omitted.

55. Write a computer algorithm to test whether a relation $R$ defined on a
    finite set $A$ is symmetric, where

$$ A = \{a[1], a[2], \dots, a[n]\} $$

Omitted.

56. Write a computer algorithm to test whether a relation $R$ defined on a
    finite set $A$ is transitive, where

$$ A = \{a[1], a[2], \dots, a[n]\} $$

Omitted.

---

Page 543

**Exercise Set 8.3**

1. Suppose that $S = \{a, b, c, d, e\}$ and $R$ is a relation on $S$ such that
   $a R b$, $b R c$, and $d R e$. List all of the following that must be true if
   $R$ is (a) reflexive (but not symmetric or transitive), (b) symmetric (but
   not reflexive or ransitive), \(c\) transitive (but not reflexive or
   symmetric), and (d) an equivalence relation.

$$ c R b \quad c R c  \quad a R c \quad b R a $$

$$ a R d \quad e R a \quad e R d \quad c R a $$

a. reflexive

$c R c$

b. symmetric

$b R a$, $c R b$, $e R d$

c. transitive

$a R c$

d. equivalence relation

$c R c$, $b R a$, $c R b$, $e R d$, $a R c$, $c R a$

2. Each of the following partitions of $\{0, 1, 2, 3, 4\}$ induces a relation
   $R$ on $\{0, 1, 2, 3, 4\}$. In each case, find the ordered pairs in $R$.

a. $\{0, 2\}, \{1\}, \{3, 4\}$

$$ R = \{(0, 0), (0, 2), (2, 0), (2, 2), (1, 1), (3, 3), (3, 4), (4, 3) , (4, 4)\} $$

b. $\{0\}, \{1, 3, 4\}, \{2\}$

$$ R = \{(0, 0), (1, 1), (1, 3), (1, 4), (2, 2), (3, 1), (3, 3), (3, 4), (4, 1), (4, 3), (4, 4)\} $$

c. $\{0\}$, $\{1, 2, 3, 4\}$

$$ R = \{(0, 0), (1, 1), (1, 2), (1, 3), (1, 4), (2, 1), (2, 2), (2, 3), (2, 4), (3, 1), (3, 2), (3, 3), (3, 4), (4, 1), (4, 2), (4, 3), (4, 4)\} $$

In each of 3-6, the relation $R$ is an equivalence relation on $A$. As in
example 8.3.5, first find the specified equivalence classes. Then state the
number of distinct equivalence classes for $R$ and list them.

3.

$$ A = \{0, 1, 2, 3, 4\} $$

$$ R = \{(0, 0), (0, 4), (1, 1), (1, 3), (2, 2), (3, 1), (3, 3), (4, 0), (4, 4)\} $$

equivalence classes: $[0], [1], [2], [3]$

$$ [0] = \{x \in A | x R 0\} = \{0, 4\} $$

$$ [1] = \{x \in A | x R 1\} = \{1, 3\} $$

$$ [2] = \{x \in A | x R 2\} = \{2\} $$

$$ [3] = \{x \in A | x R 3\} = \{1, 3\} $$

The distinct number of classes is $3$. List:

$$ [0] = \{0, 4\}, [1] = \{1, 3\} = [3], [2] = \{2\} $$

4.

$$ A = \{a, b, c, d\} $$

$$ R = \{(a, a), (b, b), (b, d), (c, c), (d, b), (d, d)\} $$

equivalence classes: $[a], [b], [c], [d]$

$$ [a] = \{x \in A | x R a\} = \{a\} $$

$$ [b] = \{x \in A | x R b\} = \{b, d\} $$

$$ [c] = \{x \in A | x R c\} = \{c\} $$

$$ [d] = \{x \in A | x R d\} = \{b, d\} $$

The number of distinct classes is 3. List:

$$ [a] = \{a\}, [b] = \{b, d\} = [d], [c] = \{c\} $$

5.

$$ A = \{1, 2, 3, 4, \dots, 20\} $$

$R$ is defined on $A$ as follows:

$$ \text{For all } x, y \in A, x R y \Leftrightarrow 4 | (x - y) $$

equivalence classes: $[1], [2], [3], [4], [5]$

$$ [1] = \{1, 5, 9, 13, 17\} $$

$$ [2] = \{2, 6, 10, 14, 18\} $$

$$ [3] = \{3, 7, 11, 15, 19\} $$

$$ [4] = \{4, 8, 12, 16, 20\} $$

$$ [5] = \{1, 5, 9, 13, 17\} $$

There are 4 distinct classes:

$$ [1] = \{1, 5, 9, 13, 17\} = [5], [2] = \{2, 6, 10, 14, 18\}, [3] = \{3, 7, 11, 15, 19\}, [4] = \{4, 8, 12, 16, 20\} $$

6.

$$ A = \{-4, -3, -2, -1, 0, 1, 2, 3, 4, 5\} $$

$R$ is defined on $A$ as follows:

$$ \text{For all } x, y \in A, x R y \Leftrightarrow 3 | (x - y) $$

equivalence classes: $[0], [1], [2], [3]$

$$ [0] = \{-3, 0, 3\} $$

$$ [1] = \{-2, 1, 4\} $$

$$ [2] = \{-4, -1, 2, 5\} $$

$$ [3] = \{-3, 0, 3\} $$

There are 3 distinct equivalence classes:

$$ [0] = \{-3, 0, 3\} = [3], [1] = \{-2, 1, 4\}, [2] = \{-4, -1, 2, 5\} $$

In each of 7-14, the relation $R$ is an equivalence relation on the set $A$.
Find the distinct equivalence classes of $R$.

7. $A = \{(1, 3), (2, 4), (-4, -8), (3, 9), (1, 5), (3, 6)\}$. $R$ is defined on
   $A$ as follows: For every $(a, b), (c, d) \in A$,

$$ (a, b) R (c, d) \Leftrightarrow ad = bc $$

$$ \{(1, 3), (3, 9)\}, \{(2, 4), (-4, -8), (3, 6)\}, \{(1, 5)\} $$

8. $X = \{a, b, c\}$ and $A = \mathscr{P}(X)$. $R$ is defined on $A$ as follows:
   For all sets $u$ and $v$ in $\mathscr{P}(X)$,

$$ u R v \Leftrightarrow N(u) = N(v) $$

(That is, the number of elements in $u$ equals the number of elements in $v$.)

$$ \mathscr{P}(X) = \{\emptyset, \{a\}, \{b\}, \{c\}, \{a, b\}, \{a, c\}, \{b, c\}, \{a, b, c\}\} $$

$$ \{\emptyset\}, \{\{a\}, \{b\}, \{c\}\}, \{\{a, b\}, \{a, c\}, \{b, c\}\}, \{\{a, b, c\}\} $$

9. $X = \{-1, 0, 1\}$ and $A = \mathscr{P}(X)$. $R$ is defined on
   $\mathscr{P}(X)$ as follows: For all sets $s$ and $t$ in $\mathscr{P}(X)$,

$$ s R t \Leftrightarrow \text{ the sum of the elements in } s \text{ equals the sum of the elements in } t $$

$$ \mathscr{P}(X) = \{\emptyset, \{-1\}, \{0\}, \{1\}, \{-1, 0\}, \{-1, 1\}, \{0, 1\}, \{-1, 0, 1\}\} $$

$$ \{\{\emptyset\}, \{-1\}, \{-1, 0\}\}, \{\{0\}, \{-1, 1\}, \{-1, 0, 1\}\}, \{\{1\}, \{0, 1\}\} $$

10. $A = \{-5, -4, -3, -2, -1, 0, 1, 2, 3, 4, 5\}$. $R$ is defined on $A$ as
    follows: For all $m, n \in \mathbb{Z}$,

$$ m R n \Leftrightarrow 3 |(m^2 - n^2) $$

$$ \{-5, -4, -2, -1, 1, 2, 4, 5\}, \{-3, 0, 3\} $$

11. $A = \{-4, -3, -2< -1, 0, 1, 2, 3, 4\}$. $R$ is defined on $A$ as follows:
    For every $(m, n) \in A$,

$$ m R n \Leftrightarrow 4 | (m^2 - n^2) $$

$$ [0] = \{x \in A | 4 | (x^2 - 0^2)\} = \{x \in A | 4 | x^2\} $$

$$ = \{-4, -2, 0, 2, 4\} $$

$$ [1] = \{x \in A | 4 | (x^2 - 1^2) = \{x \in A | 4 | (x^2 - 1)\}\} $$

$$ = \{-3, -1, 1, 3\} $$

12. $A = \{-4, -3, -2, -1, 0, 1, 2, 3, 4\}$. $R$ is defined on $A$ as follows:
    For all $(m, n) \in A$,

$$ m R n \Leftrightarrow 5 | (m^2 - n^2) $$

$$ [0] = \{x \in A | 5 | (x^2 - 0^2)\} = \{x \in A | 5 | x^2\} $$

$$ = \{0\} $$

$$ [1] = \{x \in A | 5 | (x^2 - 1^2)\} = \{x \in A | 5 | (x^2 - 1) \} $$

$$ = \{-4, -1, 1, 4\} $$

$$ [2] = \{x \in A | 5 | (x^2 - 2^2)\} = \{x \in A | 5 | (x^2 - 4)\} $$

$$ = \{-3, -2, 2, 3\} $$

13. $A$ is the set of all strings of length 4 in _a_'s and _b_'s. $R$ is defined
    on $A$ as follows: For all strings $s$ and $t$ in $A$,

$$ s R t \Leftrightarrow s \text{ has the same first two characters as } t $$

$$ A = \{aaaa, aaab, aabb, aaba, abbb, abba, abaa, abab, bbbb, bbba, bbaa, bbab, baaa, baab, babb, baba\} $$

$$ \{aaaa, aaab, aabb, aaba\}, \{abbb, abba, abaa, abab\}, \{bbbb, bbba, bbaa, bbab\}, \{baaa, baab, babb, baba\} $$

14. $A$ is the set of all strings of 0's, 1's, and 2's that have length 4 and
    for which the sum of the characters in the string is less than or equal
    to 2. $R$ is defined on $A$ as follows: For every $s, t \in A$,

$$ s R t \Leftrightarrow \text{ the sum of the characters of } s \text{ equals the sum of the characters of } t $$

$$ \{0000\}, \{0001, 0010, 0100, 1000\}, \{0011, 0101, 1001, 1010, 1100, 0002, 0020, 0200, 2000\}$$

15. Determine which of the following congruence relations are true and which are
    false.

$$ m \equiv n (\mod d) \Leftrightarrow d | (m - n) $$

a. $17 \equiv 2 (\mod 5)$

$$ 5 | 17 - 2 $$

$$ 5 | 15 $$

Yes, this congruence relation is true, because $15 = 5 \cdot 3$, therefore
$5 | 15$.

b. $4 \equiv -5 (\mod 7)$

$$ 7 | 4 - (-5) $$

$$ 7 | 9 $$

No, this congruence relation is not true, since $7 \cancel{|} 9$.

c. $-2 \equiv -8 (\mod 3)$

$$ 3 | -2 - (-8) $$

$$ 3 | 6 $$

Yes, this congruence relation is true, since $6 = 3 \dot 2$, therefore $3 | 6$.

d. $-6 \equiv 22 (\mod 2)$

$$ 2 | -6 - 22 $$

$$ 2 | -28 $$

Yes, this congruence relation is true, since $-28 = 2 \cdot -14$, therefore
$2 | -28$.

16.

a. Let $R$ be the relation of congruence modulo 3. Which of the following
equivalence classes are equal?

$$ [7], [-4], [-6], [17], [4], [27], [19] $$

$$ 7 \mod 3 = 1, -4 \mod 3 = 2, -6 \mod 3 = 0, 17 \mod 3 = 2, 4 \mod 3 = 1, 27 \mod 3 = 0, 19 \mod 3 = 1 $$

$$ [7] = [4] = [19], [-4] = [17], [-6] = [27] $$

b. Let $R$ be the relation of congruence modulo 7. Which of the following
equivalence classes are equal?

$$ [35], [3], [-7], [12], [0], [-2], [17] $$

$$ 35 \mod 7 = 0, 3 \mod 7 = 3, -7 \mod 7 = 0, 12 \mod 7 = 5, 0 \mod 7 = 0, -2 \mod 7 = 5, 17 \mod 7 = 3 $$

$$ [35] = [-7] = [0], [12] = [-2], [3] = [17] $$

17.

a. Prove that for all integers $m$ and $n$, $m \equiv n (\mod 3)$ if, and only
if, $m \mod 3 = n \mod 3$.

**Proof:**

To prove that $m \equiv n (\mod 3) \Leftrightarrow m \mod 3 = n \mod 3$, it must
be shown that $m \equiv n (\mod 3) \to m \mod 3 = n \mod 3$, and it must also be
shown that $m \mod 3 = n \mod 3 \to m \equiv n (\mod 3)$.

_Proof ($m \equiv n (\mod 3)\to m \mod 3 = n \mod 3$):_

Suppose $m \in \mathbb{Z}$ and $n \in \mathbb{Z}$, such that
$m \equiv n (\mod 3)$.

It is to be shown that $m \mod 3 = n \mod 3$.

Since $m \equiv n (\mod 3)$, by the definition of congruence, this means that:

$$ 3 | (m - n) $$

By the definition of divisiblity:

$$ m - n = 3a $$

For some integer $a$.

Let $r = m \mod 3$.

Then, by the definition of modulo:

$$ m = 3b + r $$

for some integer $b$.

Since $m - n = 3a$, it follows by substitution that:

$$ m - n = (3b + r) - n = 3a $$

Equivalently (by algebra):

$$ (3b + r) - n = 3a $$

$$ -n = 3a - (3b + r) $$

$$ n = (3b + r) - 3a $$

$$ n = 3b + r - 3a $$

$$ n = 3b - 3a + r $$

$$ n = 3(b - a) + r $$

Now, $b - a$ is an integer (by the difference of integers), and $0 \leq r < 3$.
So, by definition of $\mod$, $n \mod 3 = r$, which equals $m \mod 3$.

This is what was to be shown.

Q.E.D.

_Proof ($m \mod 3 = n \mod 3 \to m \equiv n (\mod 3)$):_

Suppose $m \in \mathbb{Z}$ and $n \in \mathbb{Z}$ such that
$m \mod 3 = n \mod 3$.

It must be shown that $m \equiv n (\mod 3)$.

Let $r = m \mod 3 = n \mod 3$.

Then, by definition of $\mod$, $m = 3p + r$ and $n = 3q + r$ for some integers
$p$ and $q$.

By substitution:

$$ m - n = (3p + r) - (3q + r) $$

$$ = 3p + r - 3q - r $$

$$ = 3p - 3q $$

$$ = 3(p - q) $$

Now, $p - q$ is an integer (by the difference of integers). It follows by the
definition of divisibility, that $3 | (m - n)$. Therefore, by the definition of
congruence, $m \equiv n (\mod 3)$.

This is what was to be shown.

Q.E.D.

_Conclusion:_

Since it has been shown that $m \equiv n (\mod 3) \to m \mod 3 = n \mod 3$ and
it has also been shown that $m \mod 3 = n \mod 3 \to m \equiv n (\mod 3)$, it
can be concluded that $m \equiv n (\mod 3) \Leftrightarrow m \mod 3 = n \mod 3$.

b. Prove that for all integers $m$ and $n$ and any positive integer $d$,
$m \equiv n (\mod d)$ if, and only if, $m \mod d = n \mod d$.

**Proof:**

To prove that $m \equiv n (\mod d) \Leftrightarrow m \mod d = n \mod d$, it must
be shown that $m \equiv n (\mod d) \to m \mod d = n \mod d$, and it must also be
shown that $m \mod d = n \mod d \to m \equiv n (\mod d)$.

_Proof ($m \equiv n (\mod d)\to m \mod d = n \mod d$):_

Suppose $m \in \mathbb{Z}$, $n \in \mathbb{Z}$, and $d \in \mathbb{Z}^+$ such
that $m \equiv n (\mod d)$.

It is to be shown that $m \mod d = n \mod d$.

Since $m \equiv n (\mod d)$, by the definition of congruence, this means that:

$$ d | (m - n) $$

By the definition of divisiblity:

$$ m - n = da $$

For some integer $a$.

Let $r = m \mod d$.

Then, by the definition of modulo:

$$ m = db + r $$

for some integer $b$.

Since $m - n = da$, it follows by substitution that:

$$ m - n = (db + r) - n = da $$

Equivalently (by algebra):

$$ (db + r) - n = da $$

$$ -n = da - (db + r) $$

$$ n = (db + r) - da $$

$$ n = db + r - da $$

$$ n = db - da + r $$

$$ n = d(b - a) + r $$

Now, $b - a$ is an integer (by the difference of integers), and $0 \leq r < d$.
So, by definition of $\mod$, $n \mod d = r$, which equals $m \mod d$.

This is what was to be shown.

Q.E.D.

_Proof ($m \mod d = n \mod d \to m \equiv n (\mod d)$):_

Suppose $m \in \mathbb{Z}$, $n \in \mathbb{Z}$, $d \in \mathbb{Z}^+$ such that
$m \mod d = n \mod d$.

It must be shown that $m \equiv n (\mod d)$.

Let $r = m \mod d = n \mod d$.

Then, by definition of $\mod$, $m = dp + r$ and $n = dq + r$ for some integers
$p$ and $q$.

By substitution:

$$ m - n = (dp + r) - (dq + r) $$

$$ = dp + r - dq - r $$

$$ = dp - dq $$

$$ = d(p - q) $$

Now, $p - q$ is an integer (by the difference of integers). It follows by the
definition of divisibility, that $d | (m - n)$. Therefore, by the definition of
congruence, $m \equiv n (\mod d)$.

This is what was to be shown.

Q.E.D.

_Conclusion:_

Since it has been shown that $m \equiv n (\mod d) \to m \mod d = n \mod d$ and
it has also been shown that $m \mod d = n \mod d \to m \equiv n (\mod d)$, it
can be concluded that $m \equiv n (\mod d) \Leftrightarrow m \mod d = n \mod d$.

18.

a. Give an example of two sets that are distinct but not disjoint.

Consider $\{1, 2, 3\}$, $\{2\}$, then they are distinct since
$\{1, 2, 3\} \neq \{2\}$, but they are not disjoint since
$\{1, 2, 3\} \cap \{2\} = \{2\}$.

b. Find sets $A_1$ and $A_2$ and elements $x$, $y$, and $z$ such that $x$ and
$y$ are in $A_1$ and $y$ and $z$ are in $A_2$ but $x$ and $z$ are not both in
either of the sets $A_1$ or $A_2$.

$$ A_1 = \{x, y\} $$

$$ A_2 = \{y, z\} $$

In 19-31, (1) prove that the relation is an equivalence relation, and (2)
describe the distinct equivalence classes of each relation.

19. $A$ is the set of all students at your college.

a. $R$ is the relation defined on $A$ a follows: For every $x$ and $y$ in $A$,

$$ x R y \Leftrightarrow x \text{ has the same major (or double major) as } y $$

(Assume "undeclared" is a major.)

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $A$ is the set of all students at my college, and $R$ is a relation
defined on $A$ defined as follows:

$$ \forall x, y \in A, x R y \Leftrightarrow x \text{ has the same major (or
double major) as } y $$

It must be shown that $R$ is an equivalence relation.

To prove that $R$ is an equivalence relation, it must be shown that $R$ is
reflexive, symmetric, and transitive.

_Proof (that $R$ is reflexive):_

Let $x \in A$.

To prove that $R$ is reflexive, it must be shown that $x R x$. It is true that
$x$ has the same major as $x$. Therefore $R$ is reflexive. This is what was to
be shown.

_Proof (that $R$ is symmetric):_

Let $x, y \in A$.

To prove that $R$ is symmetric, it must be shown that
$(x, y) \in R \to (y, x) \in R$.

Suppose $(x, y) \in R$. Then, by definition of $R$, this means that $x$ has the
same major as $y$. By symmetric property of equality, this means that $y$ has
the same major as $x$. Therefore $(y, x) \in R$.

This is what was to be shown.

_Proof (that $R$ is transitive):_

Let $x, y, z \in A$.

To prove that $R$ is transitive, it must be shown that
$(x, y) \in R \wedge (y, z) \in R \to (x, z) \in R$.

Suppose $(x, y) \in R$ and $(y, z) \in R$. Then, by definition of $R$, this
means that $x$ has the same major as $y$, and $y$ has the same major as $z$. By
the transitive property of equality, it follows that $x$ has the same major as
$z$.

Therefore $(x, z) \in R$, and it can be concluded that $R$ is transitive.

This is what was to be shown.

_Conclusion:_

Since it has been shown that $R$ is reflexive, symmetric, and transitive, it can
be concluded that $R$ is an equivalence relation.

This is what was to be shown.

Q.E.D.

(2) Describe the distinct equivalence classes of each relation.

There is one equivalence class for each major and double major at the college.
Each class consists of all students with that major (or double major).

b. $S$ is the relation defined on $A$ as follows: For every $x, y \in A$,

$$ x S y \Leftrightarrow x \text{ is the same age as } y $$

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $A$ is the set of all students at my college, with $S$ being a relation
defined on $A$ as follows:

$$ \forall x, y \in A, x S y \Leftrightarrow x \text{ is the same age as } y $$

To prove that $S$ is an equivalence relation, it must be shown that $S$ is
reflexive, symmetric, and transitive.

_Proof (that $S$ is reflexive):_

Let $x \in A$.

To prove that $S$ is reflexive, it must be shown that $x S x$. It is true that
$x$ is the same age as $x$. Thus $x S x$, and therefore $S$ is reflexive.

This is what was to be shown.

_Proof (that $S$ is symmetric):_

Let $x, y \in A$.

To prove that $S$ is symmetric, it must be shown that
$(x, y) \in S \to (y, x) \in S$.

Suppose $x S y$. By the definition of $S$, this means that $x$ is the same age
as $y$. By the symmetric property of equality, this means that $y$ is the same
age as $x$. It follows that $y R x$, and therefore $S$ is symmetric.

This is what was to be shown.

_Proof (that $S$ is transitive):_

Let $x, y, z \in A$.

To prove that $S$ is transitive, it must be shown that
$(x, y) \in S \wedge (y, z) \in S \to (x, z) \in S$.

Suppose $x S y$ and $y S z$. Then, by the definition of $S$, this means that $x$
is the same age as $y$ and $y$ is the same age as $z$. By the transitive
property of equality, this means that $x$ is the same age as $z$.

It follows that $(x, z) \in S$, and therefore $S$ is transitive.

This is what was to be shown.

_Conclusion:_

Since $S$ has been shown to be reflexive, symmetric, and transitive, it can be
concluded that $S$ is an equivalence relation.

This is what was to be shown.

Q.E.D.

(2) Describe the distinct equivalence classes of each relation.

There is one equivalence class for each student age (by year) at the college.
Each class consists of all students with that age.

20. $E$ is the relation defined on $\mathbb{Z}$ as follows:

$$ \text{For every } m, n \in \mathbb{Z}, m E n \Leftrightarrow 4 | (m - n) $$

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $m \in \mathbb{Z}$ and $n \in \mathbb{Z}$. Let $E$ be a relation defined
on $\mathbb{Z}$ as follows:

$$ \forall m, n \in \mathbb{Z}, m E n \Leftrightarrow 4 | (m - n) $$

To prove that $E$ is an equivalence relation, it must be shown that $E$ is
reflexive, symmetric, and transitive.

_Proof ($E$ is reflexive):_

Let $m \in \mathbb{Z}$.

To prove that $E$ is reflexive, it must be shown that $(m, m) \in E$.

By the definition for $E$, this means that:

$$ 4 | (m - m) $$

Since $m - m = 0$, this means that:

$$ 4 | 0 $$

This is true, since $0 = 4 \cdot 0$. It follows that $(m, m) \in E$, and
therefore $E$ is reflexive.

_Proof ($E$ is symmetric):_

Let $m \in \mathbb{Z}$ and $n \in \mathbb{Z}$.

To prove that $E$ is symmetric, it must be shown that
$(m, n) \in E \to (n, m) \in E$.

Since $(m, n) \in E$, this means that:

$$ 4 | (m - n) $$

By the definition of divisibility, this means that:

$$ m - n = 4k $$

for some integer $k$.

Now, consider:

$$ -1(m - n) = -1(4k) $$

$$ n - m = 4(-k) $$

Now, $-k$ is an integer (by the product of integers). It follows (by the
definition of divisibility), that:

$$ 4 | (n - m) $$

This means that $(n, m) \in E$, and therefore $E$ is symmetric.

_Proof ($E$ is transitive):_

Let $m \in \mathbb{Z}$, $n \in \mathbb{Z}$, and $p \in \mathbb{Z}$.

To prove that $E$ is transitive, it must be shown that
$(m, n) \in E \wedge (n, p) \in E \to (m, p) \in E$.

Suppose $(m, n) \in E$ and $(n, p) \in E$. By definition of $E$, this means
that:

$$ 4 | (m - n) $$

and

$$ 4 | (n - p) $$

By the definition of divisibility, this means that:

$$ m - n = 4k $$

$$ n - p = 4q $$

for some integers $k$ and $q$.

Subtracting the two yields:

$$ (m - n) - (n - p) = m - p $$

And then by substitution this is:

$$ m - p = 4k - 4q $$

By algebra:

$$ = 4(k - q) $$

Now, $k - q$ is an integer (by the difference of integers). It follows that
$4 | (m - p)$, and thus $(m, p) \in E$. Therefore, it can be concluded that $E$
is transitive.

_Conclusion:_

Since it has been shown that $E$ is reflexive, symmetric, and transitive, it can
be concluded that $E$ is an equivalence relation. This is what was to be shown.

Q.E.D.

(2) Describe the distinct equivalence classes of each relation.

Observe that for any $a \in \mathbb{Z}$, the equivalence class of $a$, ($[a]$),
is:

$$ [a] = \{x \in \mathbb{Z} | x E a\} = \{x \in \mathbb{Z} | 4 | x - a\} $$

By definition of divisiblity:

$$ = \{x \in \mathbb{Z} | x - a = 4k \text{ for some integer } k\} $$

By algebra:

$$ = \{x \in \mathbb{Z} | x = 4k + a \} $$

So, our equivalence classes are defined as follows:

$$ \{x \in \mathbb{Z} | x = 4k \}, \{x \in \mathbb{Z} | x = 4k + 1 \}, \{x \in \mathbb{Z} | x = 4k + 2 \}, \{x \in \mathbb{Z} | x = 4k + 3 \} $$

21. $R$ is the relation defined on $\mathbb{Z}$ as follows:

$$ \text{For every } m, n \in \mathbb{Z}, m R n \Leftrightarrow 7m - 5n \text{ is even} $$

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $m \in \mathbb{Z}$ and $n \in \mathbb{Z}$, such that $R$ is a relation
on $\mathbb{Z}$ defined as follows:

$$ \forall m, n \in \mathbb{Z}, m R n \Leftrightarrow 7m - 5n \text{ is even} $$

It must be shown that $R$ is an equivalence relation.

To show that $R$ is an equivalence relation, it must be shown that $R$ is
reflexive, symmetric, and transitive.

_Proof ($R$ is reflexive):_

Let $m \in \mathbb{Z}$.

To prove that $R$ is reflexive, it must be shown that $(m, m) \in R$. By the
definition of $R$, it then must be shown that:

$$ 7m - 5m \text{ is even} $$

Consider that:

$$ 7m - 5m = 2m $$

Since $m$ is an integer (by the supposition), it follows that $7m - 5m$ is even
(by the definition of even, since $7m - 5m = 2m$).

It follows that $(m, m) \in R$, and therefore $R$ is reflexive.

_Proof ($R$ is symmetric):_

Let $m, n \in \mathbb{Z}$.

To prove that $R$ is symmetric, it must be shown that
$(m, n) \in R \to (n, m) \in R$.

Suppose $(m, n) \in R$. By definition of $R$, this means that:

$$ 7m - 5n \text{ is even} $$

By definition of even, this means that:

$$ 7m - 5n = 2k $$

for some integer $k$.

Then, consider:

$$ 7n - 5m = (12 - 5)n - (12 - 7)m $$

$$ = 12n - 5n - 12m + 7m $$

$$ = 12n - 12m + (7m - 5n) $$

$$ = 12n - 12m + 2k $$

$$ = 2(6n - 6m + k) $$

Now, $6n - 6m + k$ is an integer (by the product, sum, and difference of
integers). It follows that $7n - 5m$ is even (by the definition of even).
Therefore $(n, m) \in R$, and therefore $R$ is symmetric.

_Proof ($R$ is transitive):_

Let $m, n, p \in \mathbb{Z}$.

To prove that $R$ is transitive, it must be shown that
$(m, n) \in R \wedge (n, p) \in R \to (m, p) \in R$.

Suppose $(m, n) \in R$ and $(n, p) \in R$. By definition of $R$, this means
that:

$$ 7m - 5n \text{ is even} $$

and

$$ 7n - 5p \text{ is even}  $$

By the definition of even, this means that:

$$ 7m - 5n = 2r  $$

and

$$ 7n - 5p = 2s $$

for some integers $r$ and $s$.

It must be shown that $7m - 5p \text{ is even}$. Consider:

$$ 7m - 5p = (7m - 5n + 5n) + (7n - 7n - 5p) $$

$$ = ((7m - 5n) + 5n) + (7n - (7n - 5p)) $$

$$ = (2r + 5n) + (7n - 2s) $$

$$ = 2r + 5n + 7n - 2s $$

$$ = 2r + 12n - 2s $$

$$ = 2(r + 6n - s) $$

Now, $r + 6n - s$ is an integer (by the product, sum, and difference of
integers). By the definition of even, this means that $7m - 5p$ is even. It
follows that $(m, p) \in R$, and therefore $R$ is transitive.

_Conclusion:_

Since it has been shown that $R$ is reflexive, symmetric, and transitive, it can
be concluded that $R$ is an equivalence relation.

This is what was to be shown.

Q.E.D.

(2) Describe the distinct equivalence classes of each relation.

$$ \forall m, n \in \mathbb{Z}, m R n \Leftrightarrow 7m - 5n \text{ is even} $$

Consider $a \in \mathbb{Z}, then, by the definition of $r$, this means that:

$$ \{x \in \mathbb{Z} | x R a \} $$

By the definition of $R$:

$$ \{x \in \mathbb{Z} | 7x - 5a \text{ is even} \} $$

Since $7x - 5a$ is even, this means that both $7x$ and $5a$ are even, or both
$7x$ and $5a$ are odd. Since $7$ and $5$ are both odd (and odd times odd is odd,
and odd times even is even), this means that $7x$ and $5a$ have the same parity.

Thus there are two equivalency cases, one the set of all even integers, and the
other the set of all odd integers.

22. Let $A$ be the set of all statement forms in three variables $p$, $q$, and
    $r$. $\mathbf{R}$ is the relation defined on $A$ as follows: For all $P$ and
    $Q$ in $A$,

$$ P \mathbf{R} Q \Leftrightarrow P \text{ and } Q \text{ have the same truth table} $$

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $A$ is the set of all statement forms in three variables $p$, $q$, and
$r$. Let $\mathbf{R}$ be a relation on the set $A$ defined as follows:

$$ P \mathbf{R} Q \Leftrightarrow P \text{ and } Q \text{ have the same truth table} $$

To prove that $\mathbf{R}$ is an equivalence relation, it must be shown that
$\mathbf{R}$ is reflexive, symmetric, and transitive.

_Proof ($\mathbf{R}$ is reflexive):_

Let $P \in A$.

To prove that $\mathbf{R}$ is reflexive, it must be shown that
$(P, P) \in \mathbf{R}$. By the definition of $\mathbf{R}$, this means that $P$
and $P$ have the same truth table.

It is true that $P$ has the same truth table as itself.

It follows that $(P, P) \in \mathbf{R}$, and therefore $\mathbf{R}$ is
reflexive.

_Proof ($\mathbf{R}$ is symmetric):_

Let $P, Q \in A$.

To prove that $\mathbf{R}$ is symmetric, it must be shown that
$(P, Q) \in \mathbf{R} \to (Q, P) \in \mathbf{R}$.

Suppose $(P, Q) \in \mathbf{R}$, by the definition for $\mathbf{R}$, this means
that $P$ and $Q$ have the same truth tables.

It follows by the symmetric property of equality that $Q$ and $P$ have the same
truth tables.

Thus $(Q, P) \in \mathbf{R}$, and therefore $\mathbf{R}$ is symmetric.

_Proof ($\mathbf{R}$ is transitive):_

Let $P, Q, S \in A$.

To prove that $\mathbf{R}$ is transitive, it must be shown that
$(P, Q) \in \mathbf{R} \wedge (Q, S) \in \mathbf{R} \to (P, S) \in \mathbf{R}$.

Suppose $(P, Q) \in \mathbf{R}$ and $(Q, S) \in \mathbf{R}$. By the definition
of $\mathbf{R}$, this means that $P$ and $Q$ have the same truth tables, and
that $Q$ and $S$ have the same truth tables.

It follows, by the transitive property of equality, that $P$ and $S$ have the
same truth tables.

Thus $(P, S) \in \mathbf{R}$, and therefore $\mathbf{R}$ is transitive.

_Conclusion:_

Since it has been shown that $\mathbf{R}$ is reflexive, symmetric, and
transitive, it can be concluded that $\mathbf{R}$ is an equivalence relation.

Q.E.D.

(2) Describe the distinct equivalence classes of each relation.

There is an equivalence class corresponding to every possible truth table in 3
variables, $p, q, r$. There are 8 lines in every truth table, and each line has
2 options (true or false), so there are $2^8$ equivalence classes.

23. Let $P$ be a set of parts shipped to a company from various suppliers. $S$
    is the relation defined on $P$ as follows: For every $x, y \in P$,

$$ x S y \Leftrightarrow  x \text{ has the same part number and is shipped from the same supplier as } y $$

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $P$ is the set of all parts shipped to a company from various suppliers.
Let $S$ be a relation defined on $P$ as follows:

$$ \forall x, y \in P, x S y \Leftrightarrow x \text{ has the same part number and is shipped from the same supplier as } y $$

To prove that $S$ is an equivalence relation, it must be shown that $S$ is
reflexive, symmetric, and transitive.

_Proof ($S$ is reflexive):_

Let $x \in P$.

To prove that $S$ is reflexive, it must be shown that $(x, x) \in S$. By the
definition for $S$, this means it must be shown that $x$ has the same part
number and is shipped from the same supplier as $x$.

It is true that $x$ has the same part number as $x$ and that $x$ is shipped from
the same supplier as $x$.

Thus $(x, x) \in S$, and therefore $S$ is reflexive.

_Proof ($S$ is symmetric):_

Let $x, y \in P$.

To prove that $S$ is symmetric, it must be shown that
$(x, y) \in S \to (y, x) \in S$.

Suppose $(x, y) \in S$. By the definition for $S$, this means that $x$ has the
same part number as $y$ and $x$ is shipped from the same supplier as $y$.

It follows by the symmetry of equality that $y$ has the same part number as $x$
and $y$ is shipped from the same supplier as $x$.

Thus $(y, x) \in S$, and therefore $S$ is symmetric.

_Proof ($S$ is transitive):_

Let $x, y, z \in P$.

To prove that $S$ is transitive, it must be shown that
$(x, y) \in S \wedge (y, z) \in S \to (x, z) \in S$.

Suppose $(x, y) \in S$ and $(y, z) \in S$. By the definition for $S$, this means
that:

$x$ has the same part number and is shipped from the same supplier as $y$.

and that:

$y$ has the same part number and is shipped from the same supplier as $z$.

By the definition of the transitivity of equality, this means that $x$ has the
same part number and is shipped from the same supplier as $z$.

Thus $(x, z) \in S$, and therefore $S$ is transitive.

_Conclusion:_

Since it has been shown that $S$ is reflexive, symmetric, and transitive, it can
be concluded that $S$ is an equivalence relation. This is what was to be shown.

Q.E.D.

(2) Describe the distinct equivalence classes of each relation.

The number of distinct equivalence classes is grouped based off of parts that
all have the same part number and are shipped from the same supplier (_i.e._ the
equivalence classes are sets of all parts with the same part number and
supplier.)

24. Let $A$ be the set of identifiers in a computer program. It is common for
    identifiers to be used for only a short part of the execution time of a
    program and not to be used again to execute other parts of the program. In
    such cases, arranging for identifiers to share memory locations makes
    efficient use of a computer's memory capacity. Define a relation $R$ on $A$
    as follows: For all identifiers $x$ and $y$,

$$ x R y \Leftrightarrow \text{ the values of } x \text{ and } y \text{ are stored in the same memory location during execution of the program} $$

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $A$ is the set of identifiers in a computer program. Let $R$ be a
relation on the set $A$ such that it is defined as follows:

$$ \forall x, y \in A, x R y \Leftrightarrow \text{ the values of } x \text{ and } y \text{ are stored in the same memory location during execution of the program} $$

To prove that $R$ is an equivalence relation, it must be shown that $R$ is
reflexive, symmetric, and transitive.

_Proof ($R$ is reflexive):_

Let $x \in A$.

To prove that $R$ is reflexive, it must be shown that $(x, x) \in R$.

By definition of $R$, this means that it must be shown that the values of $x$
and $x$ are stored in the same memory location during execution of the program.

It is true that $x$ and $x$ are stored in the same memory location during
execution of the program (since $x$ is the same identifier as $x$.)

Thus $(x, x) \in R$ and therefore $R$ is reflexive.

_Proof ($R$ is symmetric):_

Let $x, y \in A$.

To prove that $R$ is symmetric, it must be shown that
$(x, y) \in R \to (y, x) \in R$.

Suppose $(x, y) \in R$. Then, by definition of $R$, this means that the values
of $x$ and $y$ are stored in the same memory location during the execution of
the program.

By the symmetric property of equality, this means that the values of $y$ and $x$
are stored in the same memory location during the execution of the program.

Thus, $(y, x) \in R$, and therefore $R$ is symmetric.

_Proof ($R$ is transitive):_

Let $x, y, z \in A$.

To prove that $R$ is transitive, it must be shown that
$(x, y) \in R \wedge (y, z) \in R \to (x, z) \in R$.

Suppose $(x, y) \in R$ and $(y, z) \in R$. By the definition for $R$, this means
that:

The values of $x$ and $y$ are stored in the same memory location during
execution of the program.

and that:

The values of $y$ and $z$ are stored in the same memory location during
execution of the program.

By the transitive property of equality, this means that the values of $x$ and
$z$ are stored in the same memory location during execution of the program.

Thus $(x, z) \in R$, and therefore $R$ is transitive.

_Conclusion:_

Since it has been shown that $R$ is reflexive, symmetric, and transitive, it can
be concluded that $R$ is an equivalence relation.

(2) Describe the distinct equivalence classes of each relation.

The number of equivalence classes is based off the number of identifiers in a
computer program that are stored in the same memory location during execution of
the program.

25. $A$ is the "absolute value" relation defined on $\mathbb{R}$ as follows:

$$ \text{For every } x, y \in \mathbb{R}, x A y \Leftrightarrow |x| = |y| $$

(1) Prove that the relation is an equivalence relation.

**Proof:**

Suppose $A$ is the "absolute value" relation on $\mathbb{R}$, defined as
follows:

$$ \forall x, y \in \mathbb{R}, x A y \Leftrightarrow |x| = |y| $$

To prove that $A$ is an equivalence relation, it must be shown that $A$ is
reflexive, symmetric, and transitive.

_Proof ($A$ is reflexive):_

Let $x \in \mathbb{R}$.

To prove that $A$ is reflexive, it must be shown that $(x, x) \in A$.

By definition for $A$, this means that it must be proved that:

$$ |x| = |x| $$

It is trivially true that $|x| = |x|$.

Thus $(x, x) \in A$, and therefore $A$ is reflexive.

_Proof ($A$ is symmetric):_

Let $x, y \in \mathbb{R}$.

To prove that $A$ is symmetric, it must be shown that
$(x, y) \in A \to (y, x) \in A$.

Suppose $(x, y) \in A$. By the definition for $A$, this means that:

$$ |x| = |y| $$

By the symmetric property of equality, it follows that:

$$ |y| = |x| $$

Thus $(y, x) \in A$, and therefore $A$ is symmetric.

_Proof ($A$ is transitive):_

Let $x, y, z \in \mathbb{R}$.

To prove that $A$ is transitive, it must be shown that
$(x, y) \in A \wedge (y, z) \in A \to (x, z) \in A$.

Suppose $(x, y) \in A$ and $(y, z) \in A$. By the definition for $A$, this means
that:

$$ |x| = |y| $$

and that:

$$ |y| = |z| $$

It follows, by the transitive property of equality that $|x| = |z|$.

Thus $(x, z) \in A$, and therefore $A$ is transitive.

_Conclusion:_

Since it has been shown that $A$ is reflexive, symmetric, and transitive, it can
be concluded that $A$ is an equivalence relation. This is what was to be shown.

Q.E.D.

(2) Describe the distinct equivalence classes of each relation.

Let $a \in \mathbf{R}$, then by the definition of absolute value:

$$ |-a| = |a| $$

with the exception of $0$, since $0 \in \mathbb{R}$, but there is no $-0$.

Thus the equivalence classes are all sets of all real numbers and their
corresponding negative counterpart, and also the set $\{0\}$.

26. $D$ is the relation defined on $\mathbb{Z}$ as follows: For every
    $m, n \in \mathbb{Z}$,

$$ m D n \Leftrightarrow 3 | (m^2 - n^2) $$

(1) Prove that the relation is an equivalence relation.

(2) Describe the distinct equivalence classes of each relation.

27. $R$ is the relation defined on $\mathbb{Z}$ as follows: For every
    $(m, n) \in \mathbb{Z}$,

$$ m R n \Leftrightarrow 4 | (m^2 - n^2) $$

(1) Prove that the relation is an equivalence relation.

(2) Describe the distinct equivalence classes of each relation.

28. $I$ is the relation defined on $\mathbb{R}$ as follows:

$$ \text{For every } x, y \in \mathbb{R}, m I n \Leftrightarrow x - y \text{ is an integer} $$

(1) Prove that the relation is an equivalence relation.

(2) Describe the distinct equivalence classes of each relation.

29. Define $P$ on the set $\mathbb{R} \times \mathbb{R}$ of ordered pairs of
    real numbers as follows: For every
    $(w, x), (y, z) \in \mathbb{R} \times \mathbb{R}$,

$$ (w, x) P (y, z) \Leftrightarrow w = y $$

(1) Prove that the relation is an equivalence relation.

(2) Describe the distinct equivalence classes of each relation.

30. Define $Q$ on the set $\mathbb{R} \times \mathbb{R}$ as follows: For every
    $(w, x), (y, z) \in \mathbb{R} \times \mathbb{R}$,

$$ (w, x) Q (y, z) \Leftrightarrow x = z $$

(1) Prove that the relation is an equivalence relation.

(2) Describe the distinct equivalence classes of each relation.

31. Let $P$ be the set of all points in the Cartesian plane except the origin.
    $R$ is the relation defined on $P$ as follows: For every $p_1$ and $p_2$ in
    $P$,

$$ p_1 R p_2 \Leftrightarrow p_1 \text{ and } p_2 \text{ lie on the same half-line emanating from the origin} $$

(1) Prove that the relation is an equivalence relation.

(2) Describe the distinct equivalence classes of each relation.

32. Let $A$ be the set of all straight lines in the Cartesian plane. Define a
    relation $\mid \mid$ on $A$ as follows: For every $l_1$ and $l_2$ in $A$,

$$ l_1 \mid \mid l_2 \Leftrightarrow l_1 \text{ is parallel to } l_2 $$

Then $\mid \mid$ is an equivalence relation on $A$. Describe the equivalence
classes of this relation.

33. Let $A$ be the set of points in the rectangle with $x$ and $y$ coordinates
    between $0$ and $1$. That is,

$$ A = \{(x, y) \in \mathbb{R} \times \mathbb{R} | 0 \leq x \leq 1 \text{ and } 0 \leq y \leq 1\} $$

Define a relation $R$ on $A$ as follows: For all $(x_1, y_1) and $(x_2, y_2)$ in
$A$,

$$ (x_1, y_1) R (x_2, y_2) \Leftrightarrow (x_1, y_1) = (x_2, y_2) $$

or

$$ x_1 = 0 \text{ and } x_2 = 1 \text{ and } y_1 = y_2 $$

or

$$ x_1 = 1 \text{ and } x_2 = 0 \text{ and } y_1 = y_2 $$

or

$$ y_1 = 0 \text{ and } y_2 = 1 \text{ and } x_1 = x_2 $$

or

$$ y_1 = 1 \text{ and } y_2 = 0 \text{ and } x_1 = x_2 $$

In other words, all points along the top edge of the rectangle are related to
the points along the bottom edge directly beneath them, and all points directly
opposite each other along the left and right edges are related to each other.
The points in the interior of the rectangle are not related to anything other
than themselves. Then $R$ is an equivalence relation on $A$. Imagine gluing
together all the points that are in the same equivalence class. Describe the
resulting figure.

34. The documentation for the computer language Java recommends that when an
    "equals method" is defined for an object, it be an equivalence relation.
    That is, if $R$ is defined as follows:

$$ x R y \Leftrightarrow \text{x.equals}(y) \text{ for all objects in the class} $$

then $R$ should be an equivalence relation. Suppose that in trying to optimize
some of the mathematics of a graphics application, a programmer creates an
object called a point, consisting of two coordinates in the plane. The
programmer defines an equals method as follows: If $p$ and $q$ are any points,
then

$$ \text{p.equals}(q) \Leftrightarrow \text{ the distance from } p \text{ to } q \text{ is less than or equal to } c $$

where $c$ is a small positive number that depends on the resolution of the
computer display. Is the programmer's equals method an equivalence relation?
Justify your answer.

35. Find an additional representative circuit for the input/output table of
    Example 8.3.9.

Let $R$ be an equivalence relation on a set $A$. Prove each of the statements in
36-41 directly from the definitions of equivalence relation and equivalence
class without using the results of Lemma 8.3.2, Lemma 8.3.3, or Theorem 8.3.4.

36. For every $a$ in $a$, $a \in [a]$.

37. For every $a$ and $b$ in $A$, if $b \in [a]$ then $a R b$.

38. For every $a$, $b$, and $c$ in $A$, if $b R c$ and $c \in [a]$ then
    $b \in [a]$.

39. For every $a$ and $b$ in $A$, if $[a] = [b]$ then $a R b$.

40. For every $a$, $b$, and $x$ in $A$, if $a R b$ and $x \in [a]$ then
    $x \in [b]$.

41. For every $a$ and $b$ in $A$, if $a \in [b]$ then $[a] = [b]$.

42. Let $R$ be the relation defined in Example 8.3.12.

a. Prove that $R$ is reflexive.

b. Prove that $R$ is symmetric.

c. List four distinct elements in $[(1, 3)]$.

d. List four distinct elements in $[(2, 5)]$.

43. In Example 8.3.12, define operations of addition $(+)$ and multiplication
    $(\cdot)$ as follows: For every $(a, b), (c, d) \in A$,

$$ [(a, b)] + [(c, d)] = [(ad + bc, bd)] $$

$$ [(a, b)] \cdot [(c, d)] = [(ac, bd)] $$

a. Prove that this addition is well defined. That is, show that if
$[(a, b)] = [(a', b')]$ and $[(c, d)] = [(c', d')]$, then
$[(ad + bc), bd] = [(a'd' + b'c', b'd')]$.

b. Prove that this multiplication is well defined. That is, show that if
$[(a, b)] = [(a', b')]$ and $[(c, d)] = [(c', d')]$, then
$[(ac, bd)] = [(a'c', b'd')]$.

c. Show that $[(0, 1)]$ is an identity element for addition. That is, show that
for any $(a, b) \in A$,

$$ [(a, b)] + [(0, 1)] = [(0, 1)] + [(a, b)] = [(a, b)] $$

d. Find an identity element for multiplication. That is, find $(i, j)$ in $A$ so
that for every $(a, b)$ in $A$,
$[(a, b)] \cdot [(i, j)] = [(i, j)] \cdot [(a, b)] = [(a, b)]$.

e. For any $(a, b) \in A$, show that $[(-a, b)]$ is an inverse for $[(a, b)]$
for addition. That is, show that
$[(-a, b)] + [(a, b)] = [(a, b)] + [(-a, b)] = [(0, 1)]$.

f. Given any $(a, b) \in A$ with $a \neq 0$, find an inverse for $[(a, b)]$ for
multiplication. That is, find $(c, d)$ in $A$ so that
$[(a, b)] \cdot [(c, d)] = [(c, d)] \cdot [(a, b)] = [(i, j)]$, where $[(i, j)]$
is the identity element you found in part (d).

44. Let $A = \mathbb{Z}^+ \times \mathbb{Z}^+$. Define a relation $R$ on $A$ as
    follows: For every $(a, b)$ and $(c, d)$ in $A$,

$$ (a, b) R (c, d) \Leftrightarrow a + d = c + b $$

a. Prove that $R$ is reflexive.

b. Prove that $R$ is symmetric.

c. Prove that $R$ is transitive.

d. List five elements in $[(1, 1)]$.

e. List five elements in $[(3, 1)]$.

f. List five elements in $[(1, 2)]$.

g. Describe the distinct equivalence classes of $R$.

45. The following argument claims to prove that the requirement that an
    equivalence relation be reflexive is redundant. In other words, it claims to
    show that if a relation is symmetric and transitive, then it is reflexive.
    Find the mistake in the argument.

"**Proof:** Let $R$ be a relation on a set $A$ and suppose $R$ is symmetric and
transitive. For any two elements $x$ and $y$ in $A$, if $x R y$ then $y R x$
since $R$ is symmetric. Thus it follows by transitivity that $x R x$, and hence
$R$ is reflexive."

46. Let $R$ be a relation on a set $A$ and suppose $R$ is symmetric and
    transitive. Prove the following: If for every $x$ in $A$ there is a $y$ in
    $A$ such that $x R y$, then $R$ is an equivalence relation.

47. Refer to the quote at the beginning of this section to answer the following
    questions.

a. What is the name of the Knight's song called?

b. What is the name of the Knight's song?

c. What is the Knight's song called?

d. What _is_ the Knight's song?

e. What is your (full, legal) name?

f. What are you called?

g. What _are_ you? (Do not answer this on paper; just think about it.)
