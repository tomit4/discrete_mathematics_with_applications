Page 512

**Definition**

Let $R$ be a relation from $A$ to $B$. Define the inverse relation $R^{-1}$ from
$B$ to $A$ as follows:

$$ R^{-1} = \{(y, x) \in B \times A | (x, y) \in R\} $$

---

Page 513

**Definition**

A **relation on a set** A is a relation from $A$ to $A$.

---

Page 514

**Definition**

Given sets $A_1, A_2, \dots, A_n$ an **$n$-ary relation** $R$ on
$A_1 \times A_2 \times \cdots \times A_n$ is a subset of
$A_1 \times A_2 \times \cdots \times A_n$. The special cases of $2$-ary,
$3$-ary, and $4$-ary relations are called **binary**, **ternary**, and
**quarternary relations**, respectively.

---

Page 518

**Definition**

Let $R$ be a relation on a set $A$.

1. $R$ is **reflexive** if, and only if, for every $x \in A, x R x$.

2. $R$ is **symmetric** if, and only if, for every
   $x, y \in A, \text{ if } x R y \text{ then } y R x$.

3. $R$ is **transitive** if, and only if, for every
   $x, y, z \in A, \text{ if } x R y \text{ and } y R z \text{ then } x R z$.

---

Page 523

**Proof of Reflexivity:**

Suppose $m$ is a particular but arbitrarily chosen integer. _[We must show that
$m T m$.]_ Now $m - m = 0$. But $3 | 0$ since $0 = 3 \cdot 0$. Hence
$3 | (m - m)$. Thus, by definition of $T$, $m T m$ _[as was to be shown]_.

---

Page 524

**Proof of Symmetry:**

Suppose $m$ and $n$ are particular but arbitrarily chosen integers that satisfy
the condition $m T n$. _[We must show that $n T m$.]_ By definition of $T$,
since $m T n$ then $3 | (m - n)$. By definition of "divides", this means that
$m - n = 3k$, for some integer $k$. Multiplying both sides by $-1$ gives
$n - m = 3(-k)$. Since $-k$ is an integer, this equation shows that
$3 | (n - m)$. Hence, by definition of $T$, $n T m$ _[as was to be shown]_.

---

Page 524

**Proof of Transitivity:**

Suppose $m$, $n$, and $p$ are particular but arbitrarily chosen integers that
satisfy the condition $m T n$ and $n T p$. _[We must show that $m T p$.]_ By
definition of $T$, since $m T n$ and $n T p$, then $3 | (m - n)$ and
$3 | (n - p)$. By definition of "divides", this means that $m - n = 3r$ and
$n - p = 3s$, for some integers $r$ and $s$. Adding the two equations gives
$(m - n) + (n - p) = 3r + 3s$, and simplifying gives that $m - p = 3(r + s)$.
Since $r + s$ is an integer, this equation shows that $3 | (m - p)$. Hence, by
definition of $T$, $m T p$ _[as was to be shown]_.

---

Page 525

**Definition**

Let $A$ be a set and $R$ a relation on $A$. The **transitive closure** of $R$ is
the relation $R^t$ on $A$ that satisfies the following three properties:

1. $R^t$ is transitive.

2. $R \subseteq R^t$.

3. If $S$ is any other transitive relation that contains $R$, then
   $R^t \subseteq S$.

---

Page 529

**Definition**

Given a partition of a set $A$, the **relation induced by the partition**, $R$,
is defined on $A$ as follows: For every $x, y \in A$,

$$ x R y \Leftrightarrow \text{ there is a subset } A_i \text{ of the partition such that both } x \text{ and } y \text{ are in } A_i $$

---

Page 530

**Theorem 8.3.1**

Let $A$ be a set with a partition and let $R$ be the relation induced by the
partition. Then $R$ is reflexive, symmetric, and transitive.

**Proof:**

Suppose $A$ is a set with a partition. In order to simplify notation, we assume
that the partition consists of only a finite number of sets. The proof for an
infinite partition is identical except for notation. Denote the partition
subsets by

$$ A_1, A_2, \dots, A_n $$

Then $A_i \cap A_j = \emptyset$ whenever $i \neq j$, and
$A_1 \cup A_2 \cup A_3 \cdots \cup A_n = A$. The relation $R$ induced by the
partition is defined as follows: For every $x, y \in A$,

$$ x R y \Leftrightarrow \text{ there is a set } A_i \text{ of the partition such that } x \in A_i \text{ and } y \in A_i $$

_[**Idea for the proof of reflexivity:** For $R$ to be reflexive means that each
element of $a$ is related by $R$ to itself. But by definition of $R$, for an
element $x$ to be related to itself means that $x$ is in the same subset of the
partition itself. Well, if $x$ is in some subset of the partition, then it is
certainly in the same subset as itself. And $x$ is in some subset of the
partition because the union of the subsets of the partition is all of $A$. This
reasoning is formalized as follows.]_

**Proof that $R$ is reflexive:**

Suppose $x \in A$. Since $A_1, A_2, \dots A_n$ is a partition of $A$, it follows
that $x \in A_i$, for for some $i$, and so the statement

there is a set $A_i$ of the partition such that $x \in A_i$ and $x \in A_i$

is true. Thus by definition of $R$, $x R x$.

_[**Idea for the proof of symmetry:** For $R$ to be symmetric means that any
time one element is related to a second, then the second is related to the
first. Now for one element $x$ to be related to a second element $y$ means that
$x$ and $y$ are in the same subset of the partition. But if this is the case,
then $y$ is in the same subset of the partition as $x$, so $y$ is related to $x$
by definition of $R$. This reasoning is formalized as follows.]_

**Proof that $R$ is symmetric:**

Suppose $x$ and $y$ are elements of $A$ such that $x R y$. Then there is a
subset $A_i$ of the partition such that $x \in A_i$ and $y \in A_i$ by
definition of $R$. It follows that the statement

there is a subset $A_i$ of the partition such that $y \in A_i$ and $x \in A_i$

is also true. Hence, by definition of $R$, $y R x$.

_[**Idea for the proof of transitivity:** For $R$ to be transitive means that
any time one element of $A$ is related by $R$ to a second and that second is
related to a third, then the first element is related to the third. But for one
element to be related to another means that there is a subset of the partition
that contains both. So suppose $x$, $y$, and $z$ are elements such that $x$ is
in the same subset as $y$ and $y$ is in the same subset as $z$. Must $x$ be in
the same subset as $z$? Yes, because the subsets 9f the partition are mutually
disjoint. Since the subset that contains $x$ and $y$ has an element in common
with the subset that contains $y$ and $z$ (namely, $y$), the two subsets are
equal. But this means that $x$, $y$, and $z$ are all in the same subset, and so,
in particular, $x$ and $z$ are in the same subset. Hence $x$ is related by $R$
to $z$. This reasoning is formalized as follows.]_

**Proof that $R$ is transitive:**

Suppose $x$, $y$, and $z$ are in $A$ and $x R y$ and $y R z$. By definition of
$R$, there are subsets $A_i$ and $A_j$ of the partition such that

$$ x \text{ and } y  \text{ are in } A_i \quad \text{ and } \quad y \text{ and } z \text{ are in } A_j $$

Suppose $A_i \neq A_j$. _[We will deduce a contradiction.]_ Then
$A_i \cap A_j = \emptyset$ since $\{A_1, A_2, A_3, \dots, A_n\}$ is a partition
of $A$. But $y$ is in $A_i$ and $y$ is in $A_j$ also. Hence
$A_i \cap A_j \neq \emptyset$. _[This contradicts the statement that
$A_i \cap A_j = \emptyset$.]_ Thus $A_i = A_j$. It follows that $x$, $y$, and
$z$ are all in $A_i$, and so, in particular,

$$ x \text{ and } z \text{ are in } A_i $$

Thus $x R z$ by definition of $R$.

---

Page 531

**Definition**

Let $A$ be a set and $R$ a relation on $A$. $R$ is an **equivalence relation**
if, and only if, $R$ is reflexive, symmetric, and transitive.

---

Page 533

**Definition**

Suppose $A$ is a set and $R$ is an equivalence relation on $A$. For each element
$a$ in $A$, the **equivalence class of $a$**, denoted $[a]$ and called the
**class of $a$** for short, is the set of all elements $x$ in $A$ such that $x$
is related to $a$ by $R$.

In symbols:

$$ [a] = \{x \in A | x R a\} $$

---

Page 536

**Lemma 8.3.2**

Suppose $A$ is a set, $R$ is an equivalence relation on $A$, and $a$ and $b$ are
elements of $A$. If $a R b$, then $[a] = [b]$.

---

Page 536

**Proof of Lemma 8.3.2**

Let $A$ be a set, let $R$ be an equivalence relation on $A$, and suppose

$$ a \text{ and } b \text{ are elements of } A \text{ such that } a R b $$

_[We must show that $[a] = [b]$.]_

**Proof that $[a] \subseteq [b]$:**

Let $x \in [a]$. _[We must show that $x \in [b]$.]_

Since

$$ x \in [a] $$

then

$$ x R a $$

by definition of class. But

$$ a R b $$

by hypothesis. Thus, by transitivity of $R$,

$$ x R b $$

Hence

$$ x \in [b] $$

by definition of class. _[This is what was to be shown.]_

**Proof that $[b] \subseteq [a]$.

Let $x \in [b]$. _[We must show that $x \in [a]$.]_

Since

$$ x \in [b] $$

then

$$ x R b $$

by definition of class. Now

$$ a R b $$

by hypothesis. Thus, since $R$ is symmetric,

$$ b R a $$

also. Then, since $R$ is transitive and $x R b$ and $b R a$,

$$ x R a $$

Hence,

$$ x \in [a] $$

by definition of class. _[This is what was to be shown.]_

Since $[a] \subseteq [b]$ and $[b] \subseteq [a]$, it follows that $[a] = [b]$
by definition of set equality.

---

Page 537

**Lemma 8.3.3**

If $A$ is a set, $R$ is an equivalence relation on $A$, and $a$ and $b$ are
elements of $A$, then

$$ \text{either } [a] \cap [b] = \emptyset \quad \text{ or } \quad [a] = [b] $$

---

Page 537

**Proof of Lemma 8.3.3**

Suppose $A$ is a set, $R$ is an equivalence relation on $A$, $a$ and $b$ are
elements of $A$, and

$$ [a] \cap [b] \neq \emptyset $$

_[We must show that $[a] = [b]$.]_

Since $[a] \cap [b] \neq \emptyset$, there exists an element $x$ in $A$ such
that $x \in [a] \cap [b]$. By definition of intersection,

$$ x \in [a] \quad \text{ and } \quad x \in [b]$$

and so

$$ x R a \quad \text{ and } \quad x R b $$

by definition of class. Since $R$ is symmetric _[being an equivalence relation]_
and $x R a$, then $a R x$. But $R$ is also transitive _[since it is an
equivalence relation]_, and so, since $a R x$ and $x R b$,

$$ a R b $$

Now $A$ and $b$ satisfy the hypothesis of Lemma 8.3.2. Hence, by that lemma,

$$ [a] = [b] $$

_[as was to be shown]._

---

Page 537

**Theorem 8.3.4 The Partition Induced by an Equivalence Relation**

If $A$ is a set and $R$ is an equivalence relation on $A$, then the distinct
equivalence classes of $R$ form a partition of $A$; that is, the union of the
equivalence classes is all of $A$, and the intersection of any two distinct
classes is empty.

---

Page 538

**Proof of Theorem 8.3.4**

Suppose $A$ is a set and $R$ is an equivalence relation on $A$. For notational
simplicity, we assume that $R$ has only a finite number of distinct equivalence
classes, which we denote

$$ A_1, A_2, \dots, A_n $$

where $n$ is a positive integer. (When the number of classes is infinite, the
proof is identical except for notation.)

**Proof that $A = A_1 \cup A_2 \cup \cdots \cup A_n$:**

_[We must show that $A \subseteq A_1 \cup A_2 \cup \cdots \cup A_n$ and that
$A_1 \cup A_2 \cup \cdots \cup A_n \subseteq A$.]_

To show that $A \subseteq A_1 \cup A_2 \cup \cdots \cup A_n$, suppose $x$ is any
element of $A$. _[We must show that $x \in A_1 \cup A_2 \cup \cdots A_n$.]_ By
reflexivity of $R$, $x R x$. And this implies that $x \in [x]$ by definition of
class. Since $x$ is in _some_ equivalence class, it must be in one of the
distinct equivalence classes $A_1, A_2, \dots$, or $A_n$. Thus $x \in A_i$ for
some index $i$, and hence $x \in A_1 \cup A_2 \cup \cdots \cup A_n$ by
definition of union _[as was to be shown]_.

To show that $A_1 \cup A_2 \cup \cdots \cup A_n \subseteq A$, suppose
$x \in A_1 \cup A_2 \cup \cdots \cup A_n$. _[We must show that $x \in A$.]_ Then
$x \in A_i$ for some $i = 1, 2, \dots, n$, by definition of union. Now each
$A_i$ is an equivalence class of $R$, and equivalence classes are subsets of
$A$. Hence $A_i \subseteq A$ and so $x \in A$ _[as was to be shown]._

Since $A \subseteq A_1 \cup A_2 \cup \cdots A_n$ and
$A_1 \cup A_2 \cup \cdots \cup A_n \subseteq A$, then by definition of set
equality, $A = A_1 \cup A_2 \cup \cdots \cup A_n$.

**Proof that the distinct classes of $R$ are mutually disjoint:**

Suppose that $A_i$ and $A_j$ are any two distinct equivalence classes of $R$.
_[We must show that $A_i$ and $A_j$ are disjoint.]_ Since $A_i$ and $A_j$ are
distinct, then $A_i \neq A_j$. And since $A_i$ and $A_j$ are equivalence classes
of $R$, there must exist elements $a$ and $b$ in $A$ such that $A_i = [a]$ and
$A_j = [b]$.

By Lemma 8.3.3,

$$ \text{either } [a] \cap [b] = \emptyset \quad \text{ or } \quad [a] = [b]$$

Now $[a] \neq [b]$ because $A_i \neq A_j$, and hence $[a] \cap [b] = \emptyset$.
Thus $A_i \cap A_j = \emptyset$, and so $A_i$ and $A_j$ are disjoint _[as was to
be shown]._

---

Page 540

**Definition**

Suppose $R$ is an equivalence relation on a set $A$ and $S$ is an equivalence
class of $R$. A **representative** of the class $S$ is any element $a$ such that
$[a] = S$.

--

Page 541

**Definition**

Let $m$ and $n$ be integers and let $d$ be a positive integer. We say that **$m$
is congruent to $n$ modulo $d$** and write

$$ m = n (\mod d) $$

if, and only if,

$$ d | (m - n) $$

Symbolically:

$$ m \equiv n(\mod d) \Leftrightarrow d | (m - n) $$

---

Page 542

**Example 8.3.12**

_Rational Numbers are Really Equivalence Classes

Let $A$ be the set of all ordered pairs of integers for which the second element
of the pair is nonzero. Symbolically:

$$ A = \mathbb{Z} \times (\mathbb{Z} - \{0\}) $$

Define a relation $R$ on $A$ as follows: For all pairs $(a, b)$ and $(c, d)$ in
$A$,

$$ (a, b) R (c, d) \Leftrightarrow ad = bc $$

The fact is that $R$ is an equivalence relation.
