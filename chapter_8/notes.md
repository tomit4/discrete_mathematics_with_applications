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

---

Page 549

**Theorem 8.4.1 Modular Equivalences**

Let $a$, $b$, and $n$ be any integers and suppose $n > 1$. The following
statements are all equivalent:

1. $n | (a - b)$

2. $a \equiv b (\mod n)$

3. $a = b + kn$ for some integer $k$

4. $a$ and $b$ have the same (nonnegative) remainder when divided by $n$

5. $a \mod n = b \mod n$

**Proof:**

We will show that
$(1) \Rightarrow (2) \Rightarrow (3) \Rightarrow (4) \Rightarrow (5) \Rightarrow (1)$.
It will follow by the transitivity of if-then that all five statements are
equivalent.

So let $a$, $b$, and $n$ be any integers with $n > 1$.

_Proof that $(1) \Rightarrow (2)$:_

Suppose that $n | (a - b)$. By definition of congruence module $n$, we can
immediately conclude that $a \equiv b (\mod n)$.

_Proof that $(2) \Rightarrow (3)$:_

Suppose $a \equiv b (\mod n)$. By definition of congruence modulo $n$,
$n | (a - b)$. Thus, by definition of divisibility, $a - b = kn$, for some
integer $k$. Adding $b$ to both sides gives that $a = b + kn$.

_Proof that $(3) \Rightarrow (4)$:_

Suppose that $a = b + kn$, for some integer $k$. Use the quotient-remainder
theorem to divide $a$ by $n$ to obtain

$$ a = qn + r \text{ where } q \text{ and } r \text{ are integers and } 0 \leq r < n $$

So $r$ is the remainder obtained when $a$ is divided by $n$. Substituting
$b + kn$ for $a$ in the equation $a = qn + r$ gives that

$$ b + kn = qn + r $$

and subtracting $kn$ from both sides and factoring out $n$ yields

$$ b = (q - k)n + r $$

Now since $0 \leq r < n$, the uniqueness property of the quotient-remainder
theorem guarantees that $r$ is also the remainder obtained when $b$ is divided
by $n$. Thus $a$ and $b$ have the same remainder when divided by $n$.

_Proof that $(4) \Rightarrow (5)$:_

Suppose that $a$ and $b$ have the same remainder when divided by $n$. It follows
immediately from the definition of the $\mod$ function that
$a \mod n = b \mod n$.

_Proof that $(5) \Rightarrow (1)$:_

Suppose that $a \mod n = b \mod n$. By definition of the $\mod$ function, $a$
and $b$ have the same remainder when divided by $n$. Thus, by the
quotient-remainder theorem, we can write

$$ a = q_1n + r \text{ and } b = q_2n + r \text{ where } q_1, q_2 \text{ and } r \text{ are integers and } 0 \leq r < n $$

It follows that

$$ a - b = (q_1n + r) - (q_2n + r) = (q_1 - q_2)n $$

Therefore, since $q_1 - q_2$ is an integer, $n | (a - b)$.

---

Page 550

**Definition**

Given integers $a$ and $n$ with $n > 1$, **the residue of $a$ modulo $n$** is
$a \mod n$, the nonnegative remainder obtained when $a$ is divided by $n$. The
numbers $0, 1, 2, \dots, n - 1$ are called a **complete set of residues modulo
$n$**. To **reduce a number modulo $n$** means to set it equal to its residue
modulo $n$. If a modulus $n > 1$ is fixed throughout a discussion and an integer
$a$ is given, the words "modulo $n$" are often dropped and we simply speak of
**the residue of $a$**.

---

Page 550

**Theorem 8.4.2 Congruence Modulo $n$ Is an Equivalence Relation**

If $n$ is any integer with $n > 1$, congruence modulo $n$ is an equivalence
relation on the set of all integers. The distinct equivalence classes of the
relation are the sets $[0], [1], [2], \dots, [n - 1]$, where for each
$a = 0, 1, 2, \dots, n - 1$,

$$ [a] = \{m \in \mathbb{Z} | m \equiv a (\mod n)\} $$

or, equivalently,

$$ [a] = \{m \in \mathbb{Z} | m = a + kn \text{ for some integer } k\} $$

**Proof:**

Suppose $n$ is any integer with $n > 1$. We must show that congruence modulo $n$
is reflexive, symmetric, and transitive.

_Proof of reflexivity:_

Suppose $a$ is any integer. To show that $a \equiv a (\mod n)$, we must show
that $n | (a - a)$. Now $a - a = 0$, and $n | 0$ because $0 = n \cdot 0$.
Therefore $a \equiv a (\mod n)$.

_Proof of symmetry:_

Suppose $a$ and $b$ are any integers such that $a \equiv b(\mod n)$. We must
show that $b \equiv a (\mod n)$. Now since $a \equiv b(\mod n)$, then
$n | (a - b)$. Thus, by definition of divisibility, $a - b = nk$, for some
integer $k$. Multiplying both sides of this equation by $-1$ to obtain

$$ -(a - b) = -nk $$

or, equivalently,

$$ b - a = n(-k) $$

Thus, by definition of divisibility $n | (b - a)$, and so, by definition of
congruence modulo $n$, $b \equiv a (\mod n)$.

_Proof of transitivity:_

This is left as exercise 5 at the end of the section.

_Proof that the distinct equivalence classes are
$[0], [1], [2], \dots, [n - 1]$:_

This is left as exercise 6 at the end of the section.

---

Page 551

**Theorem 8.4.3 Modular Arithmetic**

Let $a$, $b$, $c$, $d$, and $n$ be integers with $n > 1$, and suppose

$$ a \equiv c (\mod n) \text{ and } b \equiv d(\mod n) $$

Then

1. $(a + b) \equiv (c + d)(\mod n)$

2. $(a - b) \equiv (c - d)(\mod n)$

3. $ab \equiv cd(\mod n)$

4. $a^m \equiv c^m(\mod n)$ for every positive integer $m$

**Proof:**

Because we will make greatest use of part 3 of this theorem, we prove it here
and leave the proofs of the remaining parts of the theorem to exercises 9-11 at
the end of the section.

_Proof of Part 3:_Proof Suppose $a$, $b$, $c$, $d$, and $n$ are integers with
$n > 1$, and suppose $a \equiv b(\mod n)$ and $c \equiv d(\mod n)$. By Theorem
8.4.1, there exists integers $s$ and $t$ such that

$$ a = c + sn \text{ and } b = d + tn $$

Then

$$ ab = (c + sn)(d + tn) $$

$$ = cd + ctn + snd + sntn $$

$$ = cd + n(ct + sd + stn) $$

Let $k = ct + sd + stn$. Then $k$ is an integer because it is a sum of products
of integers, and $ab = cd + nk$. Thus by Theorem 8.4.1, $ab \equiv cd(\mod n)$.

---

Page 552

**Corollary 8.4.4**

Let $a$, $b$, and $n$ be integers with $n > 1$. Then

$$ ab \equiv [(a \mod n)(b \mod n)](\mod n) $$

or, equivalently,

$$ ab \mod n = [(a \mod n)(b \mod n)]\mod n $$

In particular, if $m$ is a positive integer, then

$$ a^m \equiv [(a \mod n)^m](\mod n) $$

---

Page 554

**Example 8.4.4 Computing $a^k \mod n$ When $k$ is a Power of $2$**

Find $144^4 \mod 713$.

**Solution**

Use property (8.4.1) to write $144^4 = (144^2)^2$. Then

$$ 144^4 \mod 713 = (144^2)^2 \mod 713 $$

$$ = (144^2 \mod 713)^2 \mod 713 $$

$$ = (20736 \mod 713)^2 \mod 713 \text{ because } 144^2 = 20736 $$

$$ = 59^2 \mod 713 \text{ because } 20736 \mod 713 =  59 $$

$$ = 3481 \mod 713 \text{ because } 59^2 = 3481 $$

$$ = 629 \text{ because } 3481 \mod 713 = 629 $$

---

Page 554

**Example 8.4.5 Computing $a^k \mod n$ When $k$ is Not a Power of $2$**

Find $12^{43} \mod 713$.

**Solution**

First write the exponent as a sum of powers of $2$:

$$ 43 = 2^5 + 2^3 + 2 + 1 = 32 + 8 + 2 + 1 $$

Next compute $12^{2^k}$ for $k = 0, 1, 2, 3, 4, \text { and } 5$.

$$ 12 \mod 713 = 12 $$

$$ 12^2 \mod 713 = 144 $$

$$ 12^4 \mod 713 = 144^2 \mod 713 = 59 \text{ by Example 8.4.4} $$

$$ 12^8 \mod 713 = 59^2 \mod 713 = 629 \text{ by Example 8.4.4} $$

$$ 12^{16} \mod 713 = 629^2 \mod 713 = 639 \text{ by the method of Example 8.4.4} $$

$$ 12^{32} \mod 713 = 639^2 \mod 713 = 485 \text{ by the method of Example 8.4.4} $$

By property (8.4.2),

$$ 12^{43} = 12^{32 + 8 + 2 + 1} = 12^{32} \cdot 12^8 \cdot 12^2 \cdot 12^1 $$

Thus, by Corollary 8.4.4,

$$ 12^{43} \mod 713 = \{(12^{32} \mod 713) \cdot (12^8 \mod 713) \cdot (12^2 \mod 713) \cdot (12 \mod 713)\} \mod 713 $$

By substitution,

$$ 12^{43} \mod 713 = (485 \cdot 629 \cdot 144 \cdot 12) \mod 713 $$

$$ = 527152320 \mod 713 $$

$$ = 48 $$

---

Page 555

**Definition**

An integer $d$ is said to be a **linear combination of integers** $a$ and $b$
if, and only if, there exist integers $s$ and $t$ such that $as + bt = d$.

---

Page 555

**Theorem 8.4.5 Writing a Greatest Common Divisor as a Linear Combination**

For all integers $a$ and $b$, not both zero, if $d = \text{gcd}(a, b)$, then
there exist integers $s$ and $t$ such that $as + bt = d$.

**Proof:**

Given integers $a$ and $b$, not both zero, and given $d = \text{gcd}(a, b)$, let

$$ S = \{x | x \text{ is a positive integer and } x = as + bt \text{ for some integers } s \text{ and } t\} $$

Note that $S$ is a nonempty set because (1) if $a > 0$ then
$1 \cdot a + 0 \cdot b \in S$, (2) if $a < 0$ then
$(-1) \cdot a + 0 \cdot b \in S$, and (3) if $a = 0$ then, by assumption,
$b \neq 0$, and hence $0 \cdot a + 1 \cdot b \in S$ or
$0 \cdot a + (-1) \cdot b \in S$. Thus, because $S$ is a nonempty subset of
positive integers, by the well-ordering principle for the integers there is a
least element $c$ in $S$. By definition of $S$,

$$ c = as + bt \text{ for some integers } s \text{ and } t $$

We will show that (1) $c \geq d$, and (2) $c \leq d$, and we will therefore be
able to conclude that $c = d = \text{gcd}(a, b)$.

_(1) Proof that $c \geq d$:_

_[In this part of the proof, we show that $d$ is a divisor of $c$ and thus that
$d \leq c$.]_ Because $d = \text{gcd}(a, b)$, by definition of greatest common
divisor, $d | a$ and $d | b$. Hence $a = dx$ and $b = dy$ for some integers $x$
and $y$. Then

$$ c = as + bt $$

$$ = (dx)s + (dy)t $$

$$ = d(xs + y) $$

Now $xs + yt$ is an integer because it is a sum of products of integers. Thus,
by definition of divisibility, $d | c$. Both $c$ and $d$ are positive, and
hence, by Theorem 4.4.1, $c \geq d$.

_(2) Proof that $c \leq d$:_

_[In this part of the proof, we show that $c$ is a divisor of both $a$ and $b$
and therefore that $c$ is less than or equal to the greatest common divisor of
$a$ and $b$, which is $d$.]_ Apply the quotient-remainder theorem to the
division of $a$ by $c$ to obtain

$$ a = cq + r \text{ for some integers } q \text{ and } r \text{ with } 0 \leq r < c $$

Thus for some integers $q$ and $r$ with $0 \leq r < c$,

$$ r = a - cq $$

Now $c = as + bt$. Therefore, for some integers $q$ and $r$ with $0 \leq r < c$,

$$ r = a - (as + bt)q $$

$$ = a(1 - sq) - btq $$

Thus $r$ is a linear combination of $a$ and $b$. If $r > 0$, then $r$ would be
in $S$, and so $r$ would be a smaller element of $S$ than $c$, which would
contradict the fact that $c$ is the least element of $S$. Hence $r = 0$. By
substitution into (8.4.4),

$$ a = cq $$

and therefore $c | a$.

An almost identical argument establishes that $c | b$ and is left as exercise 30
at the end of the section.

Because $c | a$ and $c | b$, $c$ is a common divisor of $a$ and $b$. Hence $c$
is less than or equal to the greatest common divisor of $a$ and $b$. In other
words, $c \leq d$.

From (1) and (2), we conclude that $c = d$. It follows that $d$, the greatest
common divisor of $a$ and $b$, is equal to $as + bt$.

---

Page 557

**Definition**

Given any integer $a$ and any positive integer $n$, if there exists an integer
$s$ such that $as \equiv 1(\mod n)$, then $s$ is called **an inverse for $a$
modulo $n$.**

---

Page 557

**Definition**

Integers $a$ and $b$ are **relatively prime** if, and only if,
$\text{gcd}(a, b) = 1$. Integers $a_1, a_2, a_3, \dots, a_n$ are **pairwise
relatively prime** if, and only if, $\text{gcd}(a_i, a_j) = 1$ for all integers
$i$ and $j$ with $1 \leq i$, $j \leq n$, and $i \neq j$.

---

Page 557

**Corollary 8.4.6**

If $a$ and $b$ are relatively prime integers, then there exist integers $s$ and
$t$ such that $as + bt = 1$.

---

Page 558

**Corollary 8.4.7 Existence of Inverses Modulo $n$**

For all integers $a$ and $n$, if $\text{gcd}(a, n) = 1$, then there exists an
integer $s$ such that $as \equiv 1(\mod n)$, and so $s$ is an inverse for $a$
modulo $n$.

**Proof:**

Suppose $a$ and $n$ are integers and $\text{gcd}(a, n) = 1$. By Corollary 8.4.6,
there exist integers $s$ and $t$ such that

$$ as + nt = 1 $$

Subtracting $nt$ from both sides gives that

$$ as = 1 - nt = 1 + (-t)n $$

Thus, by definition of congruence modulo $n$,

$$ as \equiv 1(\mod n) $$

---

Page 562

**Theorem 8.4.8 Euclid's Lemma**

For all integers $a$, $b$, and $c$, if $\text{gcd}(a, c) = 1$ and $a | bc$, then
$a | b$.

**Proof:**

Suppose $a$, $b$, and $c$ are integers, $\text{gcd}(a, c) = 1$, and $a | bc$.
_[We must show that $a | b$.]_ By Theorem 8.4.5, there exist integers $s$ and
$t$ so that

$$ as + ct = 1 $$

Multiply both sides of this equation by $b$ to obtain

$$ bas + bct = b $$

Since $a | bc$, by definition of divisibility there exists an integer $k$ such
that

$$ bc = ak $$

Substituting (8.4.8) into (8.4.7), rewriting, and factoring out an $a$ gives
that

$$ b = bas + (ak)t = a(bs + kt) $$

Let $r = bs + kt$. Then $r$ is an integer (because $b$, $s$, $k$, and $t$ are
all integers), and $b = ar$. Thus $a | b$ by definition of divisibility.

Page 562

**Theorem 8.4.9 Cancellation Theorem for Modular Congruence**

For all integers $a$, $b$, and $c$, and $n$ with $n > 1$, if
$\text{gcd}(c, n) = 1$ and $ac = bc(\mod n)$, then $a \equiv b(\mod n)$.

**Proof:**

Suppose $a$, $b$, $c$, and $n$ are integers, $\text{gcd}(c, n) = 1$, and
$ac \equiv bc(\mod n)$. _[We must show that $a \equiv b(\mod n)$.]_ By
definition of congruence modulo $n$,

$$ n | (ac - bc) $$

and so, since

$$ ac - bc = (a - b)c $$

then

$$ n | (a - b)c $$

Because $\text{gcd}(c, n) = 1$, we may apply Euclid's lemma to obtain

$$ n | (a - b) $$

and so, by definition of congruence modulo $n$,

$$ a \equiv b(\mod n) $$

---

Page 563

**Theorem 8.4.10 Fermat's Little Theorem**

If $p$ is any prime number and $a$ is any integer such that $p \cancel{|} a$,
then $a^{p - 1} \equiv 1(\mod p)$.

**Proof:**

Suppose $p$ is any prime number and $a$ is any integer such that
$p \cancel{|} a$. Note that $a \neq 0$ because otherwise $p$ would divide $a$.
Consider the set of integers

$$ S = \{a, 2a, 3a, \dots, (p - 1)a\} $$

We claim that no two elements of $S$ are congruent modulo $p$. For suppose
$sa \equiv ra(\mod p)$ for some integers $s$ and $r$ with
$1 \leq r < s \leq p - 1$. Then, by definition of congruence modulo $p$,

$$ p | (sa - ra) \text{ or, equivalently, } p | (s - r)a $$

Now $p \cancel{|} a$ by hypothesis, and because $p$ is prime,
$\text{gcd}(a, p) = 1$. Thus, by Euclid's lemma, $p | (s - r)$, But this is
impossible because $0 < s - r < p$.

Consider the function $F$ from $S$ to the set $T = \{1, 2, 3, \dots, (p - 1)\}$
that sends each element of $S$ to its residue modulo $p$. Then $F$ is one-to-one
because no two elements of $S$ are congruent modulo $p$. In Section 9.4 we prove
that if a function from one finite set to another is one-to-one, then it is also
onto. Hence $F$ is onto, and so $p - 1$ residues of the $p - 1$ elements of $S$
are exactly the numbers $1, 2, 3 \dots, (p - 1)$.

It follows by Theorem 8.4.3(3) that

$$ a \cdot 2a \cdot 3a \cdots (p - 1)a \equiv [1 \cdot 2 \cdot 3 \cdots (p - 1)](\mod p) $$

or, equivalently,

$$ a^{p - 1}(p - 1)! \equiv (p - 1)!(\mod p) $$

Now because $p$ is prime, $p$ and $(p - 1)!$ are relatively prime. Thus, by the
cancellation theorem for modular congruence (Theorem 8.4.9),

$$ a^{p - 1} \equiv 1(\mod p) $$
