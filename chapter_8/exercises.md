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
