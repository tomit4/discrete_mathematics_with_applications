Page 401

**Element Argument: The Basic Method for Proving That One Set is a Subset of
Another**

Let sets $X$ and $Y$ be given. To prove that $X \subseteq Y$,

1. **suppose** that $x$ is a particular but arbitrarily chosen element of $X$,

2. **show** that $x$ is an element of $Y$.

---

Page 402

**Definition**

Given sets $A$ and $B$, $A$ **equals** $B$, written $A = B$, if, and only if,
every element of $A$ is in $B$ and every element of $B$ is in $A$.

Symbolically:

$$ A = B \Leftrightarrow A \subseteq B \text{ and } B \subseteq A $$

---

Page 404

Let $A$ and $B$ be the subsets of a universal set $U$.

1. The **union** of $A$ and $B$, denoted $A \cup B$, is the set of all elements
   that are in at least one of $A$ or $B$.

2. The **intersection of $A$ and $B$, denoted $A \cap B$, is the set of all
   elements that are common to both $A$ and $B$.

3. The **difference** of $B$ minus $A$ (or **relative complement** of $A$ in
   $B$), denoted $B - A$, is the set of all elements that are in $B$ and not
   $A$.

4. The **complement** of $A$, denoted $A^c$, is the set of all elements in $U$
   that are not in $A$.

Symbolically:

$$ A \cup B = \{x \in U | x \in A \text{ or } x \in B\} $$

$$ A \cap B = \{x \in U | x \in A \text{ and } x \in B\} $$

$$ B - A = \{x \in U | x \in B \text{ and } x \notin A\} $$

$$ A^c = \{x \in U | x \notin A\} $$

---

Page 405:

**Interval Notation:**

Given real numbers $a$ and $b$ with $a \leq b$:

$$ (a, b) = \{x \in \mathbb{R} | a < x < b\} $$

$$ [a, b] = \{x \in \mathbb{R} | a \leq x \leq b\} $$

$$ (a, b] = \{x \in \mathbb{R} | a < x \leq b\} $$

$$ [a, b) = \{x \in \mathbb{R} | a \leq x < b\} $$

The symbols $\infty$ and $-\infty$ are used to indicate intervals that are
unbounded either on the right or on the left:

$$ (a, \infty) = \{x \in \mathbb{R} | x > a\} $$

$$ [a, \infty) = \{x \in \mathbb{R} | x \geq a\} $$

$$ (-\infty, b) = \{x \in \mathbb{R} | x < b\} $$

$$ (-\infty, b] = \{x \in \mathbb{R} | x \leq b\} $$

---

Page 406

**Definition**

**Unions and Intersections of an Indexed Collection of Sets**

Given sets $A_0, A_1, A_2, \dots$ that are subsets of a universal set $U$, and
given a nonnegative integer $n$,

$$ \bigcup_{i = 0}^{n}A_i = \{x \in U | x \in A_i \text{ for at least one } i = 0, 1, 2, \dots, n\} $$

$$ \bigcup_{i = 0}^{\infty}A_i = \{x \in U | x \in A_i \text{ for at least one nonnegative integer } i\} $$

$$ \bigcap_{i = 0}^{n}A_i = \{x \in U | x \in A_i \text{ for every } i = 0, 1, 2, \dots, n\} $$

$$ \bigcap_{i = 0}^{\infty}A_i = \{x \in U | x \in A_i \text{ for every nonnegative integer } i\} $$

---

Page 408

**Definition**

Two sets are called **disjoint** if, and only if, they have no elements in
common.

Symbolically:

$$ A \text{ and } B \text{ are disjoint } \Leftrightarrow A \cap B = \emptyset $$

---

Page 408

**Definition**

Sets $A_1, A_2, A_3, \dots$ are **mutually disjoint** (or **pairwise disjoint**
or **nonoverlapping**) if, and only if, no two sets $A_i$ and $A_j$ with
distinct subscripts have any elements in common. More precisely, for all
integers $i$ and $j = 1, 2, 3, \dots$

$$ A_i \cap A_j = \emptyset \text{ whenever } i \neq j $$

---

Page 408

**Definition**

A finite or infinite collection of nonempty sets $\{A_1, A_2, A_3, \dots\}$ is a
**partition** of a set $A$ if, and only if,

1. $A$ is the union of all the $A_i$.

2. the sets $A_1, A_2, A_3, \dots$ are mutually disjoint.

---

Page 409

**Definition**

Given a set $A$, the **power** set of $A$, denoted $\mathscr{P}(A)$, is the set
of all subsets of $A$.

---

Page 410

**Algorithm 6.1.1 Testing whether $A \subseteq B$**

_[The input sets $A$ and $B$ are represented as one-dimensional arrays
$a[1], a[2], \dots, a[m]$ and $b[1], b[2], \dots, b[n]$, respectively. Starting
with $a[1]$ and for each successive $a[i]$ in $A$, a check is made to see
whether $a[i]$ is in $B$. To do this, $a[i]$ is compared to successive elements
of $B$. If $a[i]$ is not equal to any element of $B$, then the output string,
called answer, is given the value "$A \nsubseteq B$." If $a[i]$ equals some
element of $B$, the next successive element in $A$ is checked to see whether it
is in $B$. If every successive element of $A$ is found to be in $B$, then the
answer never changes from its initial value "$A \subseteq B$."]_

**Input:** _$m$ [a positive integer], $a[1], a[2], \dots, a[m]$ [a
one-dimensional array representing the set $A$], $n$ [a positive integer],
$b[1], b[2], \dots, b[n]$ [a one-dimensional array representing the set $B$]_

**Algorithm Body:**

$i := 1, \text{answer} := A \subseteq B\\ \text{\textbf{while}} (i \leq m \text{ and answer } = A \subseteq B )\\ \ \ j := 1, \text{found} := \text{"no"}\\ \ \ \text{\textbf{while }} (j \neq n \text{ and } \text{found}= \text{"no"})\\ \ \ \ \ \text{\textbf{if }} a[i] = b[j] \text{\textbf{ then }} \text{found} := \text{"yes"}\\ \ \ \ \ j := j + 1\\ \ \ \text{\textbf{end while}}\\ \ \ \text{[If found has not been given the value "yes" when execution reaches this point, then } a[i] \neq B\text{ .]}\\ \ \ \text{\textbf{if }} \text{found} = \text{"no"} \text{\textbf{ then }} \text{answer} := A \nsubseteq B\\ \ \  i := i + 1\\ \text{\textbf{end while}}$

**Output:** _answer [a string]_

---

Page 414

**Theorem 6.2.1 Some Subset Relations**

1. _Inclusion of Intersection:_ For all sets $A$ and $B$,

$$ \text{(a) } A \cap B \subseteq A \quad \text{ and } \quad \text{ (b) } A \cap B \subseteq B $$

2. _Inclusion in Union:_ For all sets $A$ and $B$,

$$ \text{(a) } A \subseteq A \cup B \quad \text{ and } \quad \text{ (b) } B \subseteq A \cup B $$

3. _Transitive Property of Subsets:_ For all sets $A$, $B$, $C$,

$$ \text{if } A \subseteq B \text{ and } B \subseteq C \text{, then } A \subseteq C $$

---

Page 415

**Procedural Versions of Set Definitions**

Let $X$ and $Y$ be subsets of a universal set $U$ and suppose $x$ and $y$ are
elements of $U$.

1. $x \in X \cup Y \Leftrightarrow x \in X \text{ or } x \in Y$

2. $x \in X \cap Y \Leftrightarrow x \in X \text{ and } x \in Y$

3. $x \in X - Y \Leftrightarrow x \in X \text{ and } x \notin Y$

4. $x \in X^c \Leftrightarrow x \notin X$

5. $(x, y) \in X \times Y \Leftrightarrow x \in X \text{ and } y \in Y$

---

Page 417

**Theorem 6.2.2 Set Identities**

Let all sets referred to below be subsets of a universal set $U$.

1. _Commutative Laws:_ For all sets $A$ and $B$,

$$ \text{(a) } A \cup B = B \cup A \quad \text{ and } \quad \text{ (b) } A \cap B = B \cap A $$

2. _Associative Laws:_ For all sets $A$, $B$, and $C$,

$$ \text{(a) } (A \cup B) \cup C = A \cup (B \cup C) \quad \text{ and } \quad \text{ (b) } (A \cap B) \cap C = A \cap (B \cap C) $$

3. _Distributive Laws:_ For all sets $A$, $B$, and $C$,

$$ \text{(a) } A \cup (B \cap C) = (A \cup B) \cap (A \cup C) \quad \text{ and } \quad \text{ (b) } A \cap (B \cup C) = (A \cap B) \cup (A \cap C) $$

4. _Identity Laws:_ For every set $A$,

$$ \text{(a) } A \cup \emptyset = A \quad \text{ and } \quad \text{ (b) } A \cap U = A $$

5. _Complement Laws:_ For every set $A$,

$$ \text{(a) } A \cup A^c = U \quad \text{ and } \quad A \cap A^c = \emptyset $$

6. _Double Complement Law:_ For every set $A$,

$$ (A^c)^c = A $$

7. _Idempotent Laws:_ For every set $A$,

$$ \text{(a) } A \cup A = A \quad \text{ and } \quad \text{ (b) } A \cap A = A $$

8. _Universal Bound Laws:_ For every set $A$,

$$ \text{(a) } A \cup U = U \quad \text{ and } \quad \text{ (b) } A \cap \emptyset = \emptyset $$

9. _De Morgan's Laws:_ For all sets $A$ and $B$,

$$ \text{(a) } (A \cup B)^c = A^c \cap B^c \quad \text{ and } \quad \text{ (b) } (A \cap B)^c = A^c \cup B^c $$

10. _Absorption Laws:_ For all sets $A$ and $B$,

$$ \text{(a) } A \cup (A \cap B) = A \quad \text{ and } \quad \text{ (b) } A \cap (A \cup B) = A $$

11. _Complements of $U$ and $\emptyset$:_

$$ \text{(a) } U^c = \emptyset \quad \text{ and } \quad \text{ (b) } \emptyset^c = U $$

12. _Set Difference Law:_ For all sets $A$ and $B$,

$$ A - B = A \cap B^c $$

---

Page 418

**Basic Method for Proving That Sets Are Equal**

Let sets $X$ and $Y$ be given. To prove that $X = Y$:

1. Prove that $X \subseteq Y$.

2. Prove that $Y \subseteq X$.

---

Page 420

**Theorem 6.2.2(3)(a) A Distributive Law for Sets**

(Too lengthy, see page 420)

---

Page 422

**Theorem 6.2.2(9)(a) A De Morgan's Law for Sets**

For all sets $A$ and $B$, $(A \cup B)^c = A^c \cap B^c$.

**Proof:** Suppose $A$ and $B$ are sets.

_Proof that $(A \cup B)^c \subseteq A^c \cap B^c$:_

_[We must show that
$\forall x, \text{ if } x \in (A \cup B)^c \text{ then } x \in A^c \cap B^c$.]_

Suppose $x \in (A \cup B)^c$. _[We must show that $x \in A^c \cap B^c$.]_ By
definition of complement,

$$ x \notin A \cup B $$

Now to say that $x \notin A \cup B$ means that

it is false that ($x$ is in $A$ or $x$ is in $B$).

By De Morgan's laws of logic, this implies that

$x$ is not in $A$ and $x$ is not in $B$,

which can be written

$$ x \notin A \quad \text{ and } \quad x \notin B $$

Hence $x \in A^c$ and $x \in B^c$ by definition of complement. It follows, by
definition of intersection, that $x \in A^c \cap B^c$ _[as was to be shown]._ So
$(A \cup B)^c \subseteq A^c \cap B^c$ by definition of subset.

_Proof that $A^c \cap B^c \subseteq (A \cup B)^c$:_

_[We must show that
$\forall x, \text{ if } x \in A^c \cap B^c \text{ then } x \in (A \cup B)^c$.]_

Suppose $x \in A^c \cap B^c$. _[We must show that $x \in (A \cup B)^c$.]_ By
definition of intersection, $x \in A^c$ and $x \in B^c$, and by definition of
complement,

$$ x \notin A \quad \text{ and } \quad x \notin B $$

In other words,

$x$ is not in $A$ and $x$ is not in $B$.

By De Morgan's laws of logic this implies that

it is false that ($x$ is in $A$ or $x$ is in $B$),

which can be written

$$ x \notin A \cup B $$

by definition of union. Hence, by definition of complement, $x \in (A \cup B)^c$
_[as was to be shown]._ It follows that $A^c \cap B^c \subseteq (A \cup B)^c$ by
definition of subset.

_Conclusion:_ Since both set containments have been proved,
$(A \cup B)^c = A^c \cap B^c$ by definition of set equality.

---

Page 423

**Theorem 6.2.3 Intersection and Union with a Subset**

For any sets $A$ and $B$, if $A \subseteq B$, then

$$ \text{(a) } A \cap B = A \quad \text{ and } \quad \text{ (b) } A \cup B = B $$

**Proof:**

_Part (a):_ Suppose $A$ and $B$ are sets with $A \subseteq B$. To show part (a)
we must show both that $A \cap B \subseteq A$ and that $A \subseteq A \cap B$.
We already know that $A \cap B \subseteq A$ by the inclusion of intersection
property. To show that $A \subseteq A \cap B$, let $x$ be any element in $A$.
_[We must show that $x$ is in $A \cap B$.]_ But, because of the hypothesis that
$A \subseteq B$, we can conclude that $x$ is also in $B$ by definition of
subset. Hence

$$ x \in A \quad \text{ and } x \in B $$

and thus

$$ x \in A \cap B $$

by definition of intersection _[as was to be shown]._

**Proof:**

_Part (b):_ The proof of part (b) is left as an exercise.

---

Page 424

**Theorem 6.2.4 A Set with No Elements Is a Subset of Every Set**

If $E$ is a set with no elements and $A$ is any set, then $E \subseteq A$.

**Proof (by contradiction):**

Suppose not. _[We take the negation of the theorem and suppose it to be true.]_
Suppose there exists a set $E$ with no elements and a set $A$ such that
$E \nsubseteq A$. _[We must deduce a contradiction.]_ Then there would be an
element of $E$ that is not an element of $A$ _[by definition of subset]_. But
there can be no such element since $E$ has no elements. This is a contradiction.
_[Hence the supposition that there are sets $E$ and $A$, where $E$ has no
elements and $E \nsubseteq A$, is false, and so the theorem is true.]_

---

Page 424

**Corollary 6.2.5 Uniqueness of the Empty Set**

There is only one set with no elements.

**Proof:** Suppose $E_1$ and $E_2$ are both sets with no elements. By Theorem
6.2.4, $E_1 \subseteq E_2$ since $E_1$ has no elements. Also $E_2 \subseteq E_1$
since $E_2$ has no elements. Thus $E_1 = E_2$ by definition of set equality.

---

Page 425

**Proposition 6.2.6**

For all sets $A$, $B$, and $C$, if $A \subseteq B$ and $B \subseteq C^c$, then
$A \cap C = \emptyset$.

**Proof:**

Suppose $A$, $B$, and $C$ are sets such that $A \subseteq B$ and
$B \subseteq C^c$. We must show that $A \cap C = \emptyset$. Suppose not. That
is, suppose there is an element $x$ in $A \cap C$. By definition of
intersection, $x \in A$ and $x \in C$. Then, since $A \subseteq B$, $x \in B$ by
definition of subset. Also, since $B \subseteq C^c$, then $x \in C^c$ by
definition of subset again. It follows by definition of complement that
$x \notin C$. Thus $x \in C$ and $x \notin C$, which is a contradiction. So the
supposition that there is an element $x$ in $A \cap C$ is false, and thus
$A \cap C = \emptyset$ _[as was to be shown]_.
