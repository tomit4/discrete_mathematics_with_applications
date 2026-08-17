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

2. $R_2$ = \{(0, 0), (0, 1), (1, 1), (1, 2), (2, 2), (2, 3)\}

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

35. If $R$ is symmetric, then $R^{-1}$ is symmetric.

36. If $R$ is transitive, then $R^{-1}$ is transitive.

In 37-42, assume that $R$ and $S$ are relations on a set $A$. Prove or disprove
each statement.

37. If $R$ and $S$ are reflexive, is $R \cap S$ reflexive? Why?

38. If $R$ and $S$ are symmetric, is $R \cap S$ symmetric? Why?

39. If $R$ and $S$ are transitive, is $R \cap S$ transitive? Why?

40. If $R$ and $S$ are reflexive, is $R \cup S$ reflexive? Why?

41. If $R$ and $S$ are symmetric, is $R \cup S$ symmetric? Why?

42. If $R$ and $S$ are transitive, is $R \cup S$ transitive? Why?

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

44. Exercise 2

45. Exercise 3

46. Exercise 4

47. Exercise 5

48. Exercise 6

49. Exercise 7

50. Exercise 8

In 51-53, $R$, $S$, and $T$ are relations defined on $A = \{0, 1, 2, 3\}$.

51. Let $R = \{(0, 1), (0, 2), (1, 1), (1, 3), (2, 2), (3, 0)\}$.

Find $R^t$, the transitive closure of $R$.

52. Let $S = \{(0, 0), (0, 3), (1, 0), (1, 2), (2, 0), (3, 2)\}$.

Find $S^t$, the transitive closure of $S$.

53. Let $T = \{(0, 2), (1, 0), (2, 3), (3, 1)\}$.

Find $T^t$, the transitive closure of $T$.

54. Write a computer algorithm to test whether a relation $R$ defined on a
    finite set $A$ is reflexive, where

$$ A = \{a[1], a[2], \dots, a[n]\} $$

55. Write a computer algorithm to test whether a relation $R$ defined on a
    finite set $A$ is symmetric, where

$$ A = \{a[1], a[2], \dots, a[n]\} $$

56. Write a computer algorithm to test whether a relation $R$ defined on a
    finite set $A$ is transitive, where

$$ A = \{a[1], a[2], \dots, a[n]\} $$
