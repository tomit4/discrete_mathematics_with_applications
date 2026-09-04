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

---

Page 628

**Pigeonhole Principle**

A function from one finite set to a smaller finite set cannot be one-to-one:
There must be at least two elements in the domain that have the same image in
the co-domain.

---

Page 633

**Generalized Pigeonhole Principle**

For any function $f$ from a finite set $X$ with $n$ elements to a finite set $Y$
with $m$ elements and for any positive integer $k$, if $km < n$, then there is
some $y \in Y$ such that $y$ is the image of at least $k + 1$ distinct elements
in $X$.

---

Page 634

**Generalized Pigeonhole Principle (Contrapositive Form)**

For any function $f$ from a finite set $X$ with $n$ elements to a finite set $Y$
with $m$ elements and for any positive integer $k$, if for each $y \in Y$,
$f^{-1}(y)$ has at most $k$ elements, then $X$ has at most $km$ elements; in
other words, $n \leq km$.

---

Page 636

**Theorem 9.4.1 The Pigeonhole Principle**

For any function $f$ from a finite set $X$ with $n$ elements to a finite set $Y$
with $m$ elements, if $n > m$, then $f$ is not one-to-one.

**Proof:**

Suppose $f$ is any function from a finite set $X$ with $n$ elements to a finite
set $Y$ with $m$ elements where $n > m$. Denote the elements of $Y$ by
$y_1, y_2, \dots, y_m$. Recall that for each $y_i$ in $Y$, the inverse image set
$f^{-1}(y_i) = \{x \in X | f(x) = y_i\}$. Now consider the collection of all the
inverse image sets for all the elements of $Y$:

$$ f^{-1}(y_1), f^{-1}(y_2), \dots, f^{-1}(y_m) $$

By definition of function, each element of $X$ is sent by $f$ to some element of
$Y$. Hence each element of $X$ is in one of the inverse image sets, and so the
union of all these sets equals $X$. But also, by definition of function, no
element of $X$ is sent by $f$ to more than one element of $Y$. Thus each element
of $X$ is in only one of the inverse image sets, and so the inverse image sets
are mutually disjoint. By the addition rule, therefore,

$$ N(X) = N(f^{-1}(y_1)) + N(f^{-1}(y_2)) + \cdots + N(f^{-1}(y_m)) $$

Now suppose that $f$ is one-to-one _[which is the opposite of what we want to
prove]._ Then each set $f^{-1}(y_i)$ has at most one element, and so

$$ N(f^{-1}(y_1)) + N(f^{-1}(y_2)) + \cdots + N(f^{-1}(y_m)) \leq \underbrace{1 + 1 + \cdots + 1}_{m \text{ terms}} = m $$

Putting equations (9.4.1) and (9.4.2) together gives that

$$ n = N(X) \leq m = N(Y) $$

This contradicts the fact that $n > m$, and so the supposition that $f$ is
one-to-one must be false. Hence $f$ is not one-to-one _[as was to be shown]._

---

Page 636

**Theorem 9.4.2 One-to-One and Onto for Finite Sets**

Let $X$ and $Y$ be finite sets with the same number of elements and suppose $f$
is a function from $X$ to $Y$. Then $f$ is one-to-one if, and only if, $f$ is
onto.

**Proof:**

Suppose $f$ is a function from $X$ to $Y$, where $X$ and $Y$ are finite sets
each with $m$ elements. Let $X = \{x_1, x_2, \dots, x_m\}$ and
$Y = \{y_1, y_2, \dots, y_m\}$.

**_If $f$ is one-to-one, then $f$ is onto:_**

Suppose $f$ is one-to-one. Then $f(x_1), f(x_2), \dots, f(x_m)$ are all
distinct. Consider the set $S$ of all elements of $Y$ that are not the image of
any element of $X$.

Then the sets

$$ \{f(x_1)\}, \{f(x_2)\}, \dots, \{f(x_m)\} \quad \text{ and } \quad S $$

are mutually disjoint. By the addition rule,

$$ N(Y) = N(\{f(x_1)\}) + N(\{f(x_2)\}) + \dots + N(\{f(x_m)\}) + N(S) $$

$$ = \underbrace{1 + 1 + \cdots + 1 + N(S)}_{m \text{ terms}} \quad \text{ because each } \{f(x_i)\} \text{ is a singleton set} $$

Thus

$$ m = m + N(S) \quad \text{ because } N(Y) = m $$

and so

$$ N(S) = 0 \quad \text{ by subtracting } m \text{ from both sides} $$

Hence $S$ is empty, and so there is no element of $Y$ that is not the image of
some element of $X$. Consequently, $f$ is onto.

**_If $f$ is onto, then $f$ is one-to-one:_**

Suppose $f$ is onto. Then, for each
$i = 1, 2, \dots, m, f^{-1}(y_i) \neq \emptyset$ and so $N(f^{-1}(y_i)) \geq 1$.
As in the proof of the pigeon-hole principle (Theorem 9.4.1), $X$ is the union
of the mutually disjoint sets $f^{-1}(y_1), f^{-1}(y_2), \dots, f^{-1}(y_m)$. By
the addition principle,

$$ N(X) = \underbrace{N(f^{-1}(y_1)) + N(f^{-1}(y_2)) + \cdots + N(f^{-1}(y_m))}_{m \text{ terms, each } \geq 1} \geq m \quad \text{ 9.4.3} $$

Now if any one of the sets $f^{-1}(y_i)$ has more than one element, then the sum
of the $m$ terms in equation (9.4.3) is greater than $m$. But we know this is
not the case because $N(X) = m$. Hence each set $f^{-1}(y_i)$ has exactly one
element, and thus $f$ is one-to-one _[as was to be shown]._
