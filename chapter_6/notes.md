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
