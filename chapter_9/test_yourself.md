Page 593

**Test Yourself**

1. A sample space of a random process or experiment is ____.

the set of all possible outcomes of a random process or experiment.

2. An event in a sample space is ____.

a subset of the sample space.

3. To compute the probability of an event using the equally likely probability
   formula, you take the ratio of the ____ to the ____.

number of outcomes in the event space; total number of outcomes in the sample
space

4. If $m \leq n$, the number of integers from $m$ to $n$ inclusive is ____.

$n - m + 1$

---

Page 607

**Test Yourself**

1. The multiplication rule says that if an operation can be performed in $k$
   steps and, for each $i$ with $1 \leq i \leq k$, the $i$th step can be
   performed in $n_i$ ways (regardless of how previous steps were performed),
   then the operation as a whole can be performed in ____.

$n_1 \cdot n_2 \cdots n_k$ ways.

2. A permutation of a set of elements is ____.

an ordering of the elements of the set in a row

3. The number of permutations of a set of $n$ elements equals ____.

$n!$

4. An $r$-permutation of a set of $n$ elements is ____.

an ordered selection of $r$ of the elements of the set

5. The number of $r$-permutations of a set of $n$ elements is denoted ____.

$P(n, r)$

6. One formula for the number of $r$-permutations of a set of $n$ elements is
   ____ and another formula is ____.

$n(n - 1)(n - 2) \cdots (n - r + 1)$; $\dfrac{n!}{(n - r)!}$

---

Page 622

**Test Yourself**

1. The addition rule says that if a finite set $A$ equals the union of $k$
   distinct mutually disjoint subsets $A_1, A_2, \dots, A_k$, then ____.

the number of elements in $A$ denoted $N(A)$ is
$N(A) = N(A_1) + N(A_2) + \dots + N(A_k)$

2. The difference rule says that if $A$ is a finite set and $B$ is a subset of
   $A$, then ____.

$N(A - B) = N(A) - N(B)$

3. If $S$ is a finite sample space and $A$ is an event in $S$, then the
   probability of $A^c$ equals ____.

$1 - P(A)$

4. The inclusion/exclusion rule for two sets says that if $A$ and $B$ are any
   finite sets, then ____.

$N(A \cup B) = N(A) + N(B) - N(A \cap B)$

5. The inclusion/exclusion rule for three sets says that if $A$, $B$, and $C$
   are any finite sets, then ____.

$N(A \cup B \cup C) = N(A) + N(B) + N(C) - N(A \cap B) - N(A \cap C) - N(B \cap C) + N(A \cap B \cap C)$

---

Page 637

**Test Yourself**

1. The pigeonhole principle states that ____.

a function from one finite set to a smaller finite set cannot be one-to-one.
There must be at least two elements in the domain that have the same image in
the co-domain.

2. The generalized pigeonhole principle states that ____.

For any function $f$ from a finite set $X$ with $n$ elements to a finite set $Y$
with $m$ elements and for any positive integer $k$, if $km < n$, then there is
some $y \in Y$ such that $y$ is the image of at least $k + 1$ distinct elements
in $X$.

3. If $X$ and $Y$ are finite sets and $f$ is a function from $X$ to $Y$ then $f$
   is one-to-one if, and only if, ____.

$f$ is onto

---

Page 653

**Test Yourself**

1. The number of subsets of size $r$ that can be formed from a set with $n$
   elements is denoted ____, which is read as " ____ ."

$\dbinom{n}{r}$; $n$ choose $r$

2. The number of $r$-combinations of a set of $n$ elements is ____.

$\dbinom{n}{r}$

3. Two unordered selections are said to be the same if the elements chosen are
   the same, regardless of ____.

the order in which they are chosen

4. A formula relating $\dbinom{n}{r}$ and $p(n, r)$ is ____.

$\dbinom{n}{r} =\dfrac{P(n, r)}{r!} $

5. The phrase "at least $n$" means ____, and the phrase "at most $n$" means
   ____.

$n$ or more, $n$ or fewer

---

Page 662

**Test Yourself**

1. Given a set $X = \{x_1, x_2, \dots, x_n\}$, an $r$-combination with
   repetition allowed, or a multiset of size $r$, chosen from $X$ is ____, which
   is denoted ____.

an unordered selection of elements taken from $X$ with repetition allowed;
$[x_{i_1}, x_{i_2}, \dots, x_{i_r}]$ where each $x_{i_j}$ is in $X$ and some of
the $x_{i_j}$ may equal each other

2. If $X = \{x_1, x_2, \dots, x_n\}$, the number of $r$-combinations with
   repetition allowed (or multisets of size $r$) chosen from $X$ is ____.

$\dbinom{r + n - 1}{r}$

3. When choosing $k$ elements from a set of $n$ elements, order may or may not
   matter and repetition may or may not be allowed.

- The number of ways to choose the $k$ elements when repetition is allowed and
  order matters is ____.

$n^k$

- The number of ways to choose the $k$ elements when repetition is not allowed
  and order matters is ____.

$P(n, k)$

- The number of ways to choose the $k$ elements when repetition is not allowed
  and order does not matter is ____.

$\dbinom{n}{k}$

- The number of ways to choose the $k$ elements when repetition is allowed and
  order does not matter is ____.

$\dbinom{k + n - 1}{k}$

---

Page 676

**Test Yourself**

1. If $n$ and $r$ are nonnegative integers with $r \leq n$, then the relation
   between $\dbinom{n}{r}$ and $\dbinom{n}{n - r}$ is ____.

$\dbinom{n}{r} = \dbinom{n}{n - r}$

2. Pascal's formula says that if $n$ and $r$ are positive integers with
   $r \leq n$, then ____.

$\dbinom{n + 1}{r} = \dbinom{n}{r - 1} + \dbinom{n}{r}$

3. The crux of the algebraic proof of Pascal's formula is that to add two
   fractions you need to express both of them with a ____.

common denominator

4. The crux of the combinatorial proof of Pascal's formula is that the set of
   subsets of size $r$ of a set $\{x_1, x_2, \dots, x_{n + 1}\}$ can be
   partitioned into the set of subsets of size $r$ that contain ____ and the set
   of subsets of size $r$ that ____.

$x_{n + 1}$; do not contain $x_{n + 1}$

5. The binomial theorem says that given any real numbers $a$ and $b$ and any
   nonnegative integer, $n$, ____.

$(a + b)^n = \sum_{k = 0}^{n}{\dbinom{n}{k}a^{n - k}b^k}$

6. The crux of the algebraic proof of the binomial theorem is that, after making
   a change of variable so that the two summations have the same lower and upper
   limits and the exponents of $a$ and $b$ are the same, you use the fact that
   $\dbinom{m}{k} + \dbinom{m}{k - 1} =$ ____.

$\dbinom{m + 1}{k}$

7. The crux of the combinatorial proof of the binomial theorem is that the
   number of ways to arrange $k$ $b$'s and $(n - k)$ $a$'s in a row is ____.

$\dbinom{n}{k}$

---

Page 683

**Test Yourself**

1. If $A$ is an event in a sample space $S$, $P(A)$ can take values between ____
   and ____. Moreover, $P(S) =$ ____ and $P(\emptyset) =$ ____.

2. If $A$ and $B$ are disjoint events in a sample space $S$, $P(A \cup B) =$
   ____.

3. If $A$ is an event in a sample space $S$, $P(A^c) =$ ____.

4. If $A$ and $B$ are any events in a sample space $S$, $P(A \cup B) =$ ____.

5. If the possible outcomes of a random process or experiment are real numbers
   $a_1, a_2, \dots, a_n$, which occur with probabilities
   $p_1, p_2, \dots, p_n$, then the expected value of the process is ____.
