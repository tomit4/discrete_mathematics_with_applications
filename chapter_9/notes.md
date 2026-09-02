Page 589

**Definition**

A **sample space** is the set of all possible outcomes of a random process or
experiment. An **event** is a subset of a sample space.

---

Page 589

**Notation** For any finite set $A$, $N(A)$ denotes the number of elements in
$A$.

---

Page 592

**Theorem 9.1.1 The Number of Elements in a List**

If $m$ and $n$ are integers and $m \leq n$, then there are $n -m + 1$ integers
from $m$ to $n$ inclusive.

---

Page 598

**Theorem 9.2.1 The Multiplication Rule**

If an operation consists of $k$ steps and

the first step can be performed in $n_1$ ways,

the second step can be performed in $n_2$ ways _[regardless of how the first
step was performed]_,

$$ \vdots $$

the $k$th step can be performed in $n_k$ ways _[regardless of how the preceding
steps were performed]_,

then the entire operation can be performed in $n_1n_2 \cdots n_k$ ways.

---

Page 603

**Theorem 9.2.2**

For any integer $n$ with $n \geq 1$, the number of permutations of a set with
$n$ elements is $n!$.

---

Page 604

**Definition**

An **$r$-permutation** of a set of $n$ elements is an ordered selection of $r$
elements taken from the set of $n$ elements. The number of $r$-permutations of a
set of $n$ elements is denoted $P(n, r)$.

---

Page 604

**Theorem 9.2.3**

If $n$ and $r$ are integers and $1 \leq r \leq n$, then the number of
$r$-permutations of a set of $n$ elements is given by the formula

$$ P(n, r) = n(n - 1)(n - 2) \cdots (n - r + 1) \text{ first version} $$

or, equivalently,

$$ P(n, r) = \frac{n!}{(n - r)!} \text{ second version} $$

---

Page 612

**Theorem 9.3.1 The Addition Rule**

Suppose a finite set $A$ equals the union of $k$ distinct mutually disjoint
subsets $A_1, A_2, \dots, A_k$. Then

$$ N(A) = N(A_1) + N(A_2) + \cdots + N(A_k) $$

---

Page 613

**Theorem 9.3.2 The Difference Rule**

If $A$ is a finite set and $B$ is a subset of $A$, then

$$ N(A - B) = N(A) - N(B) $$

---

Page 614

**Formula for the Probability of the Complement of an Event**

If $S$ is a finite sample space and $A$ is an event in $S$, then

$$ P(A^c) = 1 - P(A) $$

where $A^c = S - A$, the complement of $A$ in $S$.

---

Page 619

**Theorem 9.3.3 The Inclusion/Exclusion Rule for Two or Three Sets**

If $A$, $B$, and $C$ are any finite sets, then

$$ N(A \cup B) = N(A) + N(B) - N(A \cap B) $$

and

$$ N(A \cup B \cup C) = N(A) + N(B) + N(C) - N(A \cap B) - N(A \cap C) - N(B \cap C) + N(A \cap B \cap C) $$
