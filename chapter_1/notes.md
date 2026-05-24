Page 25

A **universal statement** says that a certain property is true for all elements
in a set. (For example: _All positive numbers are greater than zero_.)

A **conditional statement** says that if one thing is true then some other thing
also has to be true. (For example: _If 378 is divisible by 18, then 378 is
divisible by 6_.)

Given a property that may or may not be true, an **existential statement** says
that there is at least one thing for which the property is true. (For example:
_There is a prime number that is even_.)

---

Page 30

**Set Roster Notation**

If $S$ is a set, the notation $x \in S$ means that $x$ is an element of $S$. The
notation $x \notin S$ means that $x$ is not an element of $S$. A set may be
specified using the **set-roster notation** by writing all of its elements
between braces. For example, $\{1, 2, 3\}$ denotes the set whose elements are
$1$, $2$, and $3$. A variation of the notation is sometimes used to describe a
very large set, as when we write $\{1, 2, 3, \dots, 100\}$ to refer to the set
of all integers from $1$ to $100$. A similar notation can also describe an
infinite set, as when we write $\{1, 2, 3, \dots\}$ to refer to the set of all
positive integers. (The symbol $\dots$ is called an **ellipsis** and is read
"and so forth.")

The **axiom of extension** says that a set is completely determined by what its
elements are - not the order in which they might be listed or the fact that some
elements might be listed more than once.

---

Page 30

| Symbol     | Set                                                       |
| ---------- | --------------------------------------------------------- |
| \mathbb{R} | the set of all real numbers                               |
| \mathbb{Z} | the set of all integers                                   |
| \mathbb{Q} | the set of all rational numbers, or quotients of integers |

---

Page 31

**Set-Builder Notation**

Let $S$ denote a set and let $P(x)$ be a property that elements of $S$ may or
may not satisfy. We may define a new set to be **the set of all elements $x$ in
$S$ such that $P(x)$ is true**. We denote this set as follows:

$$ \{x \in S | P(x)\} $$

Where $x$ is "the set of all" and $|$ is "such that."

---

Page 32

**Definition**

If $A$ and $B$ are sets, then $A$ is called a **subset** of $B$, written
$A \subseteq B$, if and only if, every element of $A$ is also an element of $B$.

Symbolically:

$A \subseteq B$ means that for every element $x$, if $x \in A$ then $x \in B$.

The phrases $A$ _is contained in_ $B$ and $B$ _contains_ $A$ are alternative
ways of saying that $A$ is a subset of $B$.

It follows from the definition of subset that for a set $A$ not to be a subset
of a set $B$ means that there is at least one element of $A$ that is not an
element of $B$. Symbolically:

$A \nsubseteq B$ means that there is at least one element $x$ such that
$x \in A$ and $x \notin B$.

**Definition**

Let $A$ and $B$ be sets. $A$ is a **proper subset** of $B$ if, and only if,
every element of $A$ is in $B$ but there is at least one element of $B$ that is
not in $A$.

---

Page 33

**Notation**

Given elements $a$ and $b$, the symbol $(a, b)$ denotes the **ordered pair**
consisting of $a$ and $b$ together with the specification that $a$ is the first
element of the pair and $b$ is the second element. Two ordered pairs $(a, b)$
and $(c, d)$ are equal if, and only if, $a = c$ and $b = d$. Symbolically:

$(a, b) = (c, d)$ means that $a = c$ and $b = d$.

---

Page 34

**Definition**

Let $n$ be a positive integer and let $x_1, x_2, \dots, x_n$ be (not necessarily
distinct) elements. The **ordered $n$-tuple, $(x_1, x_2, \dots, x_n)$**,
consists of $x_1$, $x_2$, $\dots$, $x_n$ together with the ordering: first
$x_1$, then $x_2$, and so forth up to $x_n$. An ordered 2-tuple is called an
**ordered pair**, and an ordered 3-tuple is called an **ordered triple.**

Two ordered $n$-tuples $(x_1, x_2, \dots, x_n)$ and $(y_1, y_2, \dots, y_n)$ are
**equal** if, and only if, $x_1 = y^1$, $x^2 = y^2$, $\dots$, and $x_n = y_n$.

Symbolically:

$$ (x_1, x_2, \dots x_n) = (y_1, y_2, \dots, y_n) \leftrightarrow x_1 = y_1, x^2 = y_2, \dots , x_n = y_n $$

---

Page 35

**Definition**

Given sets $A_1, A_2, \dots, A_n$, the **Cartesian product** of
$A_1, A_2, \dots, A_n$ denoted $A_1 \times A_2 \times \dots \times A_n$, is the
set of all ordered $n$-tuples $(a_1, a_2, \dots, a_n)$ where
$a_1 \in A_1, a_2 \in A_2, \dots , a_n \in A_n$.

Symbolically:

$$ A_1 \times A_2 \times \dots \times A_n = \{(a_1, a_2, \dots, a_n) | a_1 \in A_1, a_2 \in A_2, \dots , a_n \in A_n\} $$

In particular,

$$ A_1 \times A_2 = \{(a_1, a_2) | a_1 \in A_1 \text{ and } a_2 \in A_2\} $$

is the Cartesian product of $A_1$ and $A_2$.

---

Page 36

**Definition**

Let $n$ be a positive integer. Given a finite set $A$, a **string of length $n$
over $A$** is an ordered $n$-tuple of elements of $A$ written without
parentheses or commas. The elements of $A$ are called the **characters** of the
string. The **null string** over $A$ is defined to be the "string" with no
characters. It is often denoted $\lambda$ and is said to have length $0$. If
$A = \{0, 1\}$, then a string over $A$ is called a **bit string**.
