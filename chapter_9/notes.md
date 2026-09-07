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

**Example 9.4.6 Using the Contrapositive Form of the Generalized Pigeonhole
Principle**

There are 42 students who are to share 12 computers. Each student uses exactly 1
computer, and no computer is used by more than 6 students. Show that at least 5
computers are used by 3 or more students.

**Solution**

a. _Using an Argument by Contradiction:_

Suppose not. Suppose that 4 or fewer computers are used by 3 or more students.
_[A contradiction will be derived.]_ Then $12 - 4 = 8$ or more computers are
used by 2 or fewer students. Divide the set of computers into two subsets: $C_1$
and $C_2$. Into $C_1$ place $8$ of the computers used by 2 or fewer students;
into $C_2$ place the computers used by 3 or more students plus any remaining
computers (to make a total of 4 computers in $C_2$.) (See Figure 9.4.3)

(see page 635 for Figure 9.4.3)

Since at most 6 students are served by any one computer, by the contrapositive
form of the generalized pigeonhole principle, the computers in set $C_2$ serve
at most $6 \cdot 4 = 24$ students. Since at most 2 students are served by any
one computer in $C_1$, by the generalized pigeonhole principle (contrapositive
form), the computers in set $C_1$ serve at most $2 \cdot 8 = 16$ students. Hence
the total number of students served by the computers is $24 + 16 = 40$. But this
contradicts the fact that each of the 42 students is served by a computer.
Therefore, the supposition is false: At least 5 computers are used by 3 or more
students.

b. _Using a Direct Argument:_

Let $k$ be the number of computers used by 3 or more students _[We must show
that $k \geq 5$.]_ Because each computer is used by at most 6 students, these
computers are used by at most $6k$ students (by the contrapositive form of the
generalized pigeonhole principle). Each of the remaining $12 - k$ computers is
used by at most 2 students. Hence, taken together, they are used by at most
$2(12 - k) = 24 - 2k$ students (again, by the contrapositive form of the
generalized pigeonhole principle). Thus the maximum number of students served by
the computers is $6k + (24 - 2k) = 4k + 24$. Because 42 students are served by
the computers, $4k + 24 \geq 42$. Solving for $k$ gives that $k > 4.5$, and
since $k$ is an integer, this implies that $k \geq 5$ _[as was to be shown]._

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

---

Page 640

**Definition $r$-combination**

Let $n$ and $r$ be nonnegative integers with $r \leq n$. An _$r$-combination_ of
a set of $n$ elements is a subset of $r$ of the $n$ elements.

---

Page 640

**Notation $\dbinom{n}{r}$**

The symbol $\dbinom{n}{r}$, read "$n$ choose $r$," denotes the number of subsets
of size $r$ (or $r$-combinations) that can be formed from a set of $n$ elements.

---

Page 643

**Theorem 9.5.1 Computational Formula for $\binom{n}{r}$**

The number of subsets of size $r$ (or $r$-combinations) that can be chosen from
a set of $n$ elements, $\dbinom{n}{r}$, is given by the formula

$$ \binom{n}{r} = \frac{P(n, r)}{r!} \quad \text{ first version} $$

or, equivalently

$$ \binom{n}{r} = \frac{n!}{r!(n - r)!} \quad \text{ second version} $$

where $n$ and $r$ are nonnegative integers with $r \leq n$.

---

Page 652

**Theorem 9.5.2 Permutations with Sets of Indistinguishable Objects**

Suppose a collection consists of $n$ objects of which

$$ n_1 \text{ are of type } 1 \text{ and are indistinguishable from each other} $$

$$ n_2 \text{ are of type } 2 \text{ and are indistinguishable from each other} $$

$$ \vdots $$

$$ n_k \text{ are of type } k \text{ and are indistinguishable from each other} $$

and suppose that $n_1 + n_1 + \cdots + n_k = n$. Then the number of
distinguishable permutations of the $n$ objects is

$$ \binom{n}{n_1}\binom{n - n_1}{n_2}\binom{n - n_1 - n_2}{n_3} \cdots \binom{n - n_1 - n_2 - \cdots - n_{k - 1}}{n_k} $$

---

Page 657

**Definition and Notation**

An _$r$-combination with repetition allowed_, or _multiset of size $r$_, chosen
from a set $X$ of $n$ elements is an unordered selection of elements taken from
$X$ with repetition allowed. If $X = \{x_1, x_2, \dots, x_n\}$, we write an
$r$-combination with repetition allowed, or multiset of size $r$, as
$[x_{i_1}, x_{i_2}, \dots, x_{i_r}]$ where $x_{i_j}$ is in $X$ and some of the
$x_{i_j}$ may equal each other.

---

Page 659

**Theorem 9.6.1**

The number of $r$-combinations with repetition allowed (or multisets of size
$r$) that can be selected from a set of $n$ elements is

$$ \binom{r + n - 1}{r} $$

This equals the number of ways $r$ objects can be selected from $n$ categories
of objects with repetition allowed.

---

Page 668

**Theorem 9.7.1 Pascal's Formula**

Let $n$ and $r$ be positive integers with $r \leq n$. Then

$$ \binom{n + 1}{r} = \binom{n}{r - 1} + \binom{n}{r} $$

**Proof (algebraic version):**

Let $n$ and $r$ be positive integers with $r \leq n$. We will show that the
right-hand side of Pascal's formula equals its left-hand side. By Theorem 9.5.1,

$$ \binom{n}{r - 1} + \binom{n}{r} = \frac{n!}{(r - 1)!(n - (r - 1))!} + \frac{n!}{r!(n - r)!} $$

$$ = \frac{n!}{(r - 1)!(n - r + 1)!} + \frac{n!}{r!(n - r)!} $$

To add these fractions, a common denominator is needed, so multiply the
numerator and denominator of the left-hand fraction by $r$ and multiply the
numerator and denominator of the right-hand fraction by $(n - r + 1)$. Then

$$ \binom{n}{r - 1} + \binom{n}{r} = \frac{n!}{(r - 1)!(n - r + 1)!} \cdot \frac{r}{r} + \frac{n!}{r!(n - r)!} \cdot \frac{(n - r + 1)}{(n - r + 1)} $$

$$ = \frac{n! \cdot r}{(n - r + 1)! \cdot r(r - 1)!} + \frac{n \cdot n! - n! \cdot r + n!}{(n - r + 1)(n - r)! \cdot r!} $$

$$ = \frac{\cancel{n! \cdot r} + n! \cdot n - \cancel{n! \cdot r} + n!}{(n - r + 1)!r!} = \frac{n!(n + 1)}{(n + 1 - r)!r!} $$

$$ = \frac{(n + 1)!}{((n + 1) - r)!r!} = \binom{n + 1}{r} $$

This is what was to be shown.

**Proof (combinatorial version):**

Let $n$ and $r$ be positive integers with $r \leq n$. Suppose $S$ is a set with
$n + 1$ elements. The number of subsets of $S$ of size $r$ can be calculated by
thinking of $S$ as consisting of two pieces: one with $n$ elements
$\{x_1, x_2, \dots, x_n\}$ and the other with one element $\{x_{n + 1}\}$.

Any subset of $S$ with $r$ elements either contains $x_{n + 1}$ or it does not.
If it contains $x_{n + 1}$, then it contains $r - 1$ elements from the set
$\{x_1, x_2, \dots, x_n\}$. If it does not contain $x_{n + 1}$, then it contains
$r$ elements from the set $\{x_1, x_2, \dots, x_n\}$.

(see page 669 for image)

By the addition rule,

the number of subsets of $\{x_1, x_2, \dots, x_n, x_{n + 1}\}$ of size $r$ = the
number of subsets of $\{x_1, x_2, \dots, x_n\}$ of size $r - 1$ + the number of
subsets of $\{x_1, x_2, \dots, x_n\}$ of size $r$

By Theorem 9.5.1, the set $\{x_1, x_2, \dots, x_n, x_{n + 1}\}$ has
$\dbinom{n + 1}{r}$ subsets of size $r$, the set $\{x_1, x_2, \dots, x_n\}$ has
$\dbinom{n}{r - 1}$ subsets of size $r - 1$, and the set
$\{x_1, x_2, \dots, x_n\}$ has $\dbinom{n}{r}$ subsets of size $r$. Thus

$$ \binom{n + 1}{r} = \binom{n}{r - 1} + \binom{n}{r} $$

as was to be shown.

---

Page 671

**Theorem 9.7.2 Binomial Theorem**

Given any real numbers $a$ and $b$ and any nonnegative integer $n$,

$$ (a + b)^n = \sum_{k = 0}^{n}{\binom{n}{k}a^{n - k}b^k} $$

$$ = a^n + \binom{n}{1}a^{n - 1}b^1 + \binom{n}{2}a^{n - 2}b^2 + \cdots + \binom{n}{n - 1}a^1b^{n - 1} + b^n $$

---

Page 671

**Definition**

For any real number $a$ and any nonnegative integer $n$, the **nonnegative
integer powers of $a$** are defined as follows:

$$
a^n =
\begin{cases}
1 & \text{if } n = 0 \\
a \cdot a^{n - 1} & \text{if } n > 0
\end{cases}
$$

---

Page 671

**Proof of the Binomial Theorem (algebraic version):**

Suppose $a$ and $b$ are real numbers. We use mathematical induction and let the
property $P(n)$ be the equation

$$ (a + b)^n = \sum_{k = 0}^{n}{\binom{n}{k}a^{n - k}b^k} $$

_Show that $P(0)$ is true:_

When $n = 0$, the binomial theorem states that:

$$ (a + b)^0 = \sum_{k = 0}^{0}{\binom{0}{k}a^{0 - k}b^k} $$

Now the left-hand side is $(a + b)^0 = 1$ _[by definition of power],_ and the
right-hand side is

$$ \sum_{k = 0}^{0}{\binom{0}{k}a^{0 - k}b^k} = \binom{0}{0}a^{0 - 0}b^0 $$

$$ = \frac{0!}{0! \cdot (0 - 0)!} \cdot 1 \cdot 1 = \frac{1}{1 \cdot 1} = 1 $$

also _[since $0! = 1$, $a^0 = 1$, and $b^0 = 1$]._ Hence $P(0)$ is true.

_Show that for each integer $m \geq 0$, if $P(m)$ is true then $P(m + 1)$ is
true:_

Let $m$ be any integer with $m \geq 0$, and suppose $P(m)$ is true. That is,
suppose

$$ (a + b)^m = \sum_{k = 0}^{m}{\binom{m}{k}a^{m - k}b^k} \quad P(m) \text{ inductive hypothesis} $$

We need to show that $P(m + 1)$ is true:

$$ (a + b)^{m + 1} = \sum_{k = 0}^{m + 1}{\binom{m + 1}{k}a^{(m + 1) - k}b^k} $$

Now, by definition of the $m + 1$st power,

$$ (a + b)^{m + 1} = (a + b) \cdot (a + b)^m $$

so by substitution from the inductive hypothesis,

$$ (a + b)^{m + 1} = (a + b) \cdot \sum_{k = 0}^{m}{\binom{m}{k}a^{m - k}b^k} $$

$$ = a \cdot \sum_{k = 0}^{m}{\binom{m}{k}}a^{m - k}b^k + b \cdot \sum_{k = 0}^{m}{\binom{m}{k}a^{m - k}b^k} $$

$$ = \sum_{k = 0}^{m}{\binom{m}{k}a^{m + 1 - k}b^k} + \sum_{k = 0}^{m}{\binom{m}{k}a^{m - k}b^{k + 1}} $$

by the generalized distribute law and the facts that
$a \cdot a^{m - k} = a^{1 + m - k} = a^{m + 1 - k}$ and
$b \cdot b^k = b^{1 + k} = b^{k + 1}$

We transform the second summation on the right-hand side by making the change of
variable $j = k + 1$. When $k = 0$, then $j = 1$. When $k = m$, then
$j = m + 1$. And since $k = j - 1$, the general term is

$$ \binom{m}{k}a^{m - k}b^{k + 1} = \binom{m}{j - 1}a^{m - (j - 1)}b^j = \binom{m}{j - 1}a^{m + 1 - j}b^j $$

Hence the second summation on the right-hand side above is

$$ \sum_{j = 1}^{m + 1}{\binom{m}{j - 1}a^{m + 1 - j}b^j} $$

But the $j$ in this summation is a dummy variable; it can be replaced by the
letter $k$, as long as the replacement is made everywhere the $j$ occurs:

$$ \sum_{j = 1}^{m + 1}{\binom{m}{j - 1}a^{m + 1 - j}b^j} = \sum_{k = 1}^{m + 1}{\binom{m}{k - 1}a^{m + 1 - k}b^k} $$

Substituting back, we get

$$ (a + b)^{m + 1} = \sum_{k = 0}^{m}{\binom{m}{k}a^{m + 1 - k}b^k} + \sum_{k = 1}^{m + 1}{\binom{m}{k - 1}a^{m + 1 - k}b^k} $$

_[The reason for the above maneuvers was to make the powers of $a$ and $b$ agree
so that we can add the summations together term by term, except for the first
and the last terms, which we must write separately.]_

Thus

$$ (a + b)^{m + 1} = \binom{m}{0}a^{m + 1 - 0}b^0 + \sum_{k = 1}^{m}{\left[\binom{m}{k} + \binom{m}{k - 1}\right]a^{m + 1 - k}b^k + \binom{m}{(m + 1) - 1}a^{m + 1 - (m + 1)}b^{m + 1}} $$

$$ = a^{m + 1} + \sum_{k = 1}^{m}{\left[\binom{m}{k} + \binom{m}{k - 1}\right]a^{m + 1 - k}b^k + b^{m + 1}} $$

since $a^0 = b^0 = 1$ and $\dbinom{m}{0} = \binom{m}{m} = 1$.

But

$$ \left[\binom{m}{k} + \binom{m}{k - 1}\right] = \binom{m + 1}{k} $$

by Pascal's formula.

Hence

$$ (a + b)^{m + 1} = a^{m + 1} + \sum_{k = 1}^{m}{\binom{m + 1}{k}a^{(m + 1) - k}b^k + b^{m + 1}} $$

$$ = \sum_{k = 0}^{m + 1}{\binom{m + 1}{k}a^{(m + 1) - k}b^k} $$

because $\dbinom{m + 1}{0} = \dbinom{m + 1}{m + 1} = 1$

This is what was to be shown.

---

Page 673

**Proof of Binomial Theorem (combinatorial version):**

_[The combinatorial argument used here to prove the binomial theorem works only
for $n \geq 1$. If we were giving this combinatorial proof, we would have to
prove the case $n = 0$ separately. Since we have already given a complete
algebraic proof that includes the case $n = 0$, we do not prove it again here.]_

Let $a$ and $b$ be real numbers and $n$ an integer that is at least $1$. The
expression $(a + b)^n$ can be expanded into products of $n$ letters, where each
letter is either $a$ or $b$.

For each $k = 0, 1, 2, \dots, n$, the product

$$ a^{n - k}b^k = \underbrace{a \cdot a \cdot a \cdot \cdots a}_{n - k \text{ factors}} \cdot \underbrace{b \cdot b \cdot b \cdots b}_{k \text{ factors}} $$

occurs as a term in the sum the same number of times as there are orderings of
$(n - k)$ $a$'s and $k$ $b$'s. But this number equals $\dbinom{n}{k}$, the
number of ways to choose $k$ positions into which to place the $b$'s. _[The
other $n - k$ positions will be filled by $a$'s.]_ Hence, when like terms are
combined, the coefficient of $a^{n - k}b^k$ in the sum is $\dbinom{n}{k}$. Thus

$$ (a + b)^n = \sum_{k = 0}^{n}{\binom{n}{k}a^{n - k}b^k} $$

as was to be shown.
