Page 449

**Definition**

A **function $f$ from a set $X$ to a set $Y$**, denoted: $f: X \to Y$, is a
relation from $X$, the **domain** of $f$, to $Y$, the **co-domain** of $f$, that
satisfies two properties: (1) every element in $X$ is related to some element in
$Y$, and (2) no element in $X$ is related to more than one element in $Y$. Thus,
given any element $x$ in $X$, there is a unique element in $Y$ that is related
to $x$ by $f$. If we call this element $y$, then we say that "$f$ sends $x$ to
$y$" or "$f$ maps $x$ to $y$" and write $x \xrightarrow{f} y$ or $f: x \to y$.
The unique element to which $f$ sends $x$ is denoted

$f(x)$ and is called $f$ of $x$, or the output of $f$ for the input $x$, or the
value of $f$ at $x$, or the image of $x$ under $f$.

The set of all values of $f$ taken together is called the _range of $f$_ or the
_image of $X$ under $f$_. Symbolically:

$$ \text{range of } f = \text{ image of } X \text{ under } f = \{y \in Y | y = f(x), \text{ for some } x \text{ in } X\} $$

Given an element $y$ in $Y$, there may exist elements in $X$ with $y$ as their
image. When $x$ is an element such that $f(x) = y$, then $x$ is called **a
preimage of $y$** or **an inverse image of $y$**. The set of all inverse images
of $y$ is called _the inverse image of $y$_. Symbolically:

$$ \text{ the inverse image of } y = \{x \in X | f(x) = y\} $$

---

Page 451

**Theorem 7.1.1 A Test for Function Equality**

If $F: X \to Y$ and $G: X \to Y$ are functions, then $F = G$ if, and only if,
$F(x) = G(x)$ for every $x \in X$.

**Proof:**

Suppose $F: X \to Y$ and $G: X \to Y$ are functions; that is, $F$ and $G$ are
relations from $X$ to $Y$ that satisfy the two additional function properties.
Then $F$ and $G$ are subsets of $X \times Y$, and for $(x, y)$ to be in $F$
means that $y$ is the unique element related to $x$ by $F$, which we denote as
$F(x)$. Similarly, for $(x, y)$ to be in $G$ means that $y$ is the unique
element related to $x$ by $G$, which we denote as $G(x)$.

Now suppose that $F(x) = G(x)$ for every $x \in X$. Then if $x$ is any element
of $X$,

$$ (x, y) \in F \Leftrightarrow y = F(x) \Leftrightarrow y = G(x) \Leftrightarrow (x, y) \in G $$

because $F(x) = G(x)$.

So $F$ and $G$ consist of exactly the same elements and hence $F = G$.

Conversely, if $F = G$, then for every $x \in X$,

$$ y = F(x) \Leftrightarrow (x, y) \in F \Leftrightarrow (x, y) \in G \Leftrightarrow y = G(x) $$

because $F$ and $G$ consist of exactly the same elements.

Thus, since both $F(x)$ and $G(x)$ equal $y$, we have that

$$ F(x) = G(x) $$

---

Page 453

**Definition Logarithms and Logarithmic Functions**

Let $b$ be a positive real number with $b \neq 1$. For each positive real number
$x$, the **logarithm with base $b$ of $x$**, written $\log_bx$, is the exponent
to which $b$ must be raised to obtain $x$. Symbolically:

$$ \log_bx = y \Leftrightarrow b^y = x $$

The **logarithmic function with base $b$** is the function from $\mathbb{R}^+$
to $\mathbb{R}$ that takes each positive real number $x$ to $\log_bx$.

---

Page 455

**Definition**

An **($n$-place) Boolean function** $f$ is a function whose domain is the set of
all ordered $n$-tuples of $0$'s and $1$'s and whose co-domain is the set
$\{0, 1\}$. More formally, the domain of a Boolean function can be described as
the Cartesian product of $n$ copies of the set $\{0, 1\}$, which is denoted
$\{0, 1\^n}$. Thus $f: \{0, 1\}^n \to \{0, 1\}$.

---

Page 457

**Definition**

If $f: X \to Y$ is a function and $A \subseteq X$ and $C \subseteq Y$, then

$$ f(A) = \{y \in Y | y = f(x) \text{ for some } x \text{ in } A\} $$

and

$$ f^{-1}(C) = \{x \in X | f(x) \in C\} $$

$f(A)$ is called the **image of $A$**, and $f^{-1}(C)$ is called the **inverse
image of $C$**.

---

Page 463

**Definition**

Let $F$ be a function from a set $X$ to a set $Y$. $F$ is **one-to-one** (or
**injective**) if, and only if, for all elements $x_1$ and $x_2$ in $X$,

$$ \text{if } F(x_1) = F(x_2) \text{, then } x_1 = x_2 $$

or, equivalently,

$$ \text{if } x_1 \neq x_2 \text{, then } F(x_1) \neq F(x_2) $$

Symbolically:

$$ F: X \to Y \text{ is one-to-one } \Leftrightarrow \forall x_1, x_2 \in X \text{, if } F(x_1) = F(x_2) \text{ then } x_1 = x_2 $$

---

Page 466

**Definition: Hash Function**

A **hash function** is a function defined from a larger, possibly infinite, set
of data to a smaller fixed-size set of integers.

---

Page 469

**Definition**

Let $F$ be a function from a set $X$ to a set $Y$. $F$ is **onto** (or
**surjective**) if, and only if, given any element $y$ in $Y$, it is possible to
find an element $x$ in $X$ with the property that $y = F(x)$.

Symbolically:

$$ F:X \to Y \text{ is onto } \Leftrightarrow \forall y \in Y, \exists x \in X \text{ such that } F(x) = y $$

---

Page 472

**Laws of Exponents**

If $b$ and $c$ are any positive real numbers and $u$ and $v$ are any real
numbers, the following laws of exponents hold true:

7.2.1

$$ b^ub^v = b^{u + v} $$

7.2.2

$$ (b^u)^v = b^{uv} $$

7.2.3

$$ \frac{b^u}{b^v} = b^{u - v} $$

7.2.4

$$ (bc)^u = b^uc^u $$

---

Page 473

**Theorem 7.2.1 Properties of Logarithms**

For any positive real numbers $b$, $c$, $x$ and $y$ with $b \neq 1$ and
$c \neq 1$ and for every real number $a$:

a. $\log_b(xy) = \log_bx + \log_by$

b. $\log_b\left(\dfrac{x}{y}\right) = \log_bx - \log_by$

c. $\log_b(x^a) = a\log_bx$

d. $\log_cx = \dfrac{\log_bx}{\log_bc}$

---

Page 475

**Definition**

A **one-to-one correspondence** (or **bijection**) from a set $X$ to a set $Y$
is a function $F: X \to Y$ that is both one-to-one and onto.

---

Page 478

**Theorem 7.2.2**

Suppose $F: X \to Y$ is a one-to-one correspondence; in other words, suppose $F$
is one-to-one and onto. Then there is a function $F^{-1}: Y \to X$ that is
defined as follows:

Given any element $y$ in $Y$,

$$ F^{-1}(y) = \text{ that unique element } x \text{ in } X \text{ such that } F(x) \text{ equals } y $$

Or, equivalently,

$$ F^{-1}(y) = x \Leftrightarrow y = F(x) $$

---

Page 478

**Definition**

The function $F^{-1}$ of Theorem 7.2.2 is called the **inverse function** for
$F$.

---

Page 479

**Theorem 7.2.3**

If $X$ and $Y$ are sets and $F: X \to Y$ is one-to-one and onto, then
$F^{-1}:Y \to X$ is also one-to-one and onto.

**Proof:**

**$F^{-1}$ is one-to-one:**

Suppose $y_1$ and $y_2$ are elements of $Y$ such that
$F^{-1}(y_1) = F^{-1}(y_2)$. _[We must show that $y_1 = y_2$.]_ Let
$x = F^{-1}(y_1) = F^{-1}(y_2)$. Then $x \in X$, and by definition of $F^{-1}$,

$$ F(x) = y_1 \text{ since } x = F^{-1}(y_1) $$

and

$$ F(x) = y^2 \text{ since } x = F^{-1}(y_2) $$

Consequently, $y_1 = y_2$ because each is equal to $F(x)$. _[This is what was to
be shown.]_

**$F^{-1}$ is onto:**

Suppose $x \in X$. _[We must show that there exists an element $y$ in $Y$ such
that $F^{-1}(y) = x$.]_ Let $y = F(x)$. Then $y \in Y$, and by definition of
$F^{-1}$, $F^{-1}(y) = x$ _[as was to be shown.]_

---

Page 485

**Definition**

Let $f: X \to Y$ and $g: Y' \to Z$ be functions with the property that the range
of $f$ is a subset of the domain of $g$. Define a new function
$g \circ f: X \to Z$ as follows:

$$ (g \circ f)(x) = g(f(x)) \quad \text{ for each } x \in X $$

where $g \circ f$ is read "$g$ circle $f$" and $g(f(x))$ is read "$g$ of $f$ of
$x$." The function $g \circ f$ is called the **composition of $f$ and $g$**.

---

Page 487

**Theorem 7.3.1 Composition with an Identity Function**

If $f$ is a function from a set $X$ to a set $Y$, and $I_x$ is the identity
function on $X$, and $I_y$ is the identity function on $Y$, then

$$ \text{(a) } f \circ I_x = f \quad \text{ and } \quad \text{(b) } I_y \circ f = f $$

**Proof:**

_Part (a):_

Suppose $f$ is a function from a set $X$ to a set $Y$ and $I_x$ is the identity
function on $X$. Then, for each $x$ in $X$,

$$ (f \circ I_x)(x) = f(I_x(x)) = f(x) $$

Hence, by the definition of equality of functions, $f \circ I_x = f$, as was to
be shown.

_Part (b):_

This is exercise 16 at the end of this section.

---

Page 488

**Theorem 7.3.2 Composition of a Function with Its Inverse**

If $f: X \to Y$ is a one-to-one and onto function with inverse function
$f^{-1}: Y \to X$, then

$$ \text{(a) } f^{-1} \circ f = I_x \quad \text{ and } \quad \text{(b) } f \circ f^{-1} = I_y $$

**Proof:**

_Part (a):_

Suppose $f: X \to Y$ is a one-to-one and onto function with inverse function
$f^{-1}: Y \to X$. _[To show that $f^{-1} \circ f = I_x$, we must show that for
each $x \in X$, $(f^{-1} \circ f)(x) = x$.]_ Let $x$ be any element in $X$.
Then, by definition of composition of functions,

$$ (f^{-1} \circ f)(x) = f^{-1}(f(x)) $$

Let

$$ z = f^{-1}(f(x)) $$

By the definition of inverse function,

$$ f(z) = f(x) $$

and, because $f$ is one-to-one, this implies that

$$ z = x $$

Now $z = f^{-1}(f(x))$ also, and so, by substitution,

$$ f^{-1}(f(x)) = x $$

Or, equivalently,

$$ (f^{-1} \circ f)(x) = x $$

_[as was to be shown]._

Since $x$ is any element of $X$ and since $I_x(x) = x$, this proves that
$f^{-1} \circ f = I_x$.

_Part (b):_

This is exercise 17 at the end of this section.

---

Page 490

**Theorem 7.3.3**

If $f: X \to Y$ and $g: Y \to Z$ are both one-to-one functions, then $g \circ f$
is one-to-one.

---

Page 491

**Proof of Theorem 7.3.3:**

Suppose $f: X \to Y$ and $g: Y \to Z$ are both one-to-one functions. _[We must
show that $g \circ f$ is one-to-one.]_ Suppose $x_1$ and $x_2$ are elements of
$X$ such that

$$ (g \circ f)(x_1) = (g \circ f)(x_2) $$

_[We must show that $x_1 = x_2$.]_ By definition of composition of functions,

$$ g(f(x_1)) = g(f(x_2)) $$

Since $g$ is one-to-one,

$$ f(x_1) = f(x_2) $$

And since $f$ is one-to-one,

$$ x_1 = x_2 $$

_[as was to be shown]._ Hence $g \circ f$ is one-to-one.

---

Page 491

**Theorem 7.3.4**

If $f: X \to Y$ and $g: Y \to Z$ are both onto functions, then $g \circ f$ is
onto.

---

Page 493

**Proof of Theorem 7.3.4**

Suppose $f: X \to Y$ and $g: Y \to Z$ are both onto functions. _[We must show
that $g \circ f$ is onto.]_ Let $z$ be any _[particular but arbitrarily chosen]_
element of $Z$. _[We must show the existence of an element in $X$ such that
$g \circ f$ of that element equals $z$.]_ Since $g$ is onto, there is an
element, say $y$, in $Y$ such that $g(y) = z$. And since $f$ is onto, there is
an element, say $x$, in $X$ such that $f(x) = y$. Hence there is an element $x$
in $X$ such that

$$ (g \circ f)(x) = g(f(x)) = g(y) = z $$

_[as was to be shown]._ It follows that $g \circ f$ is onto.

---

Page 496

**Definition**

Let $A$ and $B$ be any sets. **$A$ has the same cardinality as $B$** if, and
only if, there is a one-to-one correspondence from $A$ to $B$. In other words,
$A$ has the same cardinality as $B$ if, and only if, there is a function $f$
from $A$ to $B$ that is one-to-one and onto.

---

**Theorem 7.4.1 Properties of Cardinality**

For all sets $A$, $B$, and $C$:

a. **Reflexive property of cardinality:** $A$ has the same cardinality as $A$.

b. **Symmetric property of cardinality:** If $A$ has the same cardinality as
$B$, then $B$ has the same cardinality as $A$.

c. **Transitive property of cardinality:** If $A$ has the same cardinality as
$B$ and $B$ has the same cardinality as $C$, then $A$ has the same cardinality
as $C$.

**Proof:**

_Part (a), Reflexivity:_

Suppose $A$ is any set. _[To show that $A$ has the same cardinality as $A$, we
must show there is a one-to-one correspondence from $A$ to $A$.]_ Consider the
identity function $I_A$ from $A$ to $A$. This function is one-to-one because if
$x_1$ and $x_2$ are any elements in $A$ with $I_A(x_1) = I_A(x_2)$, then, by
definition of $I_A$, $x_1 = x_2$. The identity function is also onto because if
$y$ is any element of $A$, then $y = I_A(y)$ by definition of $I_A$. Hence $I_A$
is a one-to-one correspondence from $A$ to $A$. _[So there exists a one-to-one
correspondence from $A$ to $A$, as was to be shown.]_

_Part (b), Symmetry:_

Suppose $A$ and $B$ are any sets and $A$ has the same cardinality as $B$. _[We
must show that $B$ has the same cardinality as $A$.]_ Since $A$ has the same
cardinality as $B$, there is a function $f$ from $A$ to $B$ that is one-to-one
and onto. But then, by Theorems 7.2.2 and 7.2.3, there is a function $f^{-1}$
from $B$ to $A$ that is also one-to-one and onto. Hence $B$ has the same
cardinality as $A$ _[as was to be shown]._

_Part \(c\), Transitivity:_

Suppose $A$, $B$, and $C$ are any sets and $A$ has the same cardinality as $B$
and $B$ has the same cardinality as $C$. _[We must show that $A$ has the same
cardinality as $C$.]_ Since $A$ has the same cardinality as $B$, there is a
function $f$ from $A$ to $B$ that is one-to-one and onto, and since $B$ has the
same cardinality as $C$, there is a function $g$ from $B$ to $C$ that is
one-to-one and onto. But then, by Theorems 7.3.3 and 7.3.4, $g \circ f$ is a
function from $A$ to $C$ that is one-to-one and onto. Hence $A$ has the same
cardinality as $C$ _[as was to be shown]._

---

Page 497

**Definition**

$A$ and $B$ **have the same cardinality** if, and only if, $A$ has the same
cardinality as $B$ or $B$ has the same cardinality as $A$.

---

Page 499

**Definition**

A set is **finite** if, and only if, it is the empty set or can be put into
one-to-one correspondence with a set of the form $\{1, 2, \dots, n\}$ for some
positive integer $n$. A set is **countably infinite** if, and only if, it has
the same cardinality as the set of positive integers $\mathbb{Z}^+$. A set is
**countable** if, and only if, it is finite or countably infinite. A set that is
not countable is called **uncountable**.

---

Page 502

**Theorem 7.4.2 (Cantor)**

The set of all real numbers between $0$ and $1$ is uncountable.

**Proof (by contradiction):**

Suppose the set of all real numbers between $0$ and $1$ is countable. Then the
decimal representations of these numbers can be written in a list as follows:

$$ 0.a_{11}a_{12}a_{13}\cdots a_{1n}\cdots $$

$$ 0.a_{21}a_{22}a_{23}\cdots a_{2n}\cdots $$

$$ 0.a_{31}a_{32}a_{33}\cdots a_{3n}\cdots $$

$$ \vdots $$

$$ 0.a_{n1}a_{n2}a_{n3}\cdots a_{nn}\cdots $$

$$ \vdots $$

_[We will derive a contradiction by showing that there is a number between $0$
and $1$ that does not appear on this list.]_

For each pair of positive integers $i$ and $j$, the $j$th decimal digit of the
$i$th number on the list is $a_{ij}$. In particular, the first decimal digit of
the first number on the list is $a_{11}$, the second decimal digit of the second
number on the list is $a_{22}$, and so forth. As an example, suppose the list of
real numbers between $0$ and $1$ starts out as follows:

$$
0. \ \boxed{2} \ 0 \ 1 \ 4 \ 8 \ 8 \ 0 \ 2 \ \dots \\
0. \ 1 \ \boxed{1} \ 6 \ 6 \ 6 \ 0 \ 2 \ 1 \ \dots \\
0. \ 0 \ 3 \ \boxed{3} \ 5 \ 3 \ 3 \ 2 \ 0 \ \dots \\
0. \ 9 \ 6 \ 7 \ \boxed{7} \ 6 \ 8 \ 0 \ 9 \ \dots \\
0. \ 0 \ 0 \ 0 \ 3 \ \boxed{1} \ 0 \ 0 \ 2 \ \dots
$$

The diagonal elements are boxed: $a_{11}$ is $2$, $a_{22}$ is $1$, $a_{33}$ is
$3$, $a_{44}$ is $7$, $a_{55}$ is $1$, and so forth.

Construct a new decimal number $d = 0.d_1d_2d_3\cdots d_n \cdots$ as follows:

$$
d_n =
\begin{cases}
1 & \text{if } a_{nn} \neq 1 \\
2 & \text{if } a_{nn} = 1
\end{cases}
$$

In the previous example,

$$
d_1 \text{ is } 1 \text{ because } a_{11} = 2 \neq 1,\\
d_2 \text{ is } 2 \text{ because } a_{22} = 1,\\
d_3 \text{ is } 1 \text{ because } a_{33} = 3 \neq 1,\\
d_4 \text{ is } 1 \text{ because } a_{44} = 7 \neq 1,\\
d_5 \text{ is } 2 \text{ because } a_{55} = 1,
$$

and so forth. Hence $d$ would equal $0.12112\dots$.

The crucial observation is that for _each integer $n$, $d$ differs in the $n$th
decimal position from the $n$th number on the list._ But this implies that $d$
is not on the list! In other words, $d$ is a real number between $0$ and $1$
that is not on the list of _all_ real numbers between $0$ and $1$. This
contradiction shows the falseness of the supposition that the set of all numbers
between $0$ and $1$ is countable. Hence the set of all real numbers between $0$
and $1$ is uncountable _[as was to be shown]._

---

Page 503

**Theorem 7.4.3**

Any subset of any countable set is countable.

**Proof:**

Let $A$ be a particular but arbitrarily chosen countable set and let $B$ be any
subset of $A$. _[We must show that $B$ is countable.]_ Either $B$ is finite or
it is infinite. If $B$ is finite, then $B$ is countable by the definition of
countable, and we are done. So suppose $B$ is infinite. Since $A$ is countable,
the distinct elements of $A$ can be represented as a sequence

$$ a_1, a_2, a_3, \dots $$

Define a function $g: \mathbb{Z}^+ \to B$ inductively as follows:

1. Search sequentially through elements of $a_1, a_2, a_3, \dots$ until an
   element of $B$ is found _[This must happen eventually since $B \subseteq A$
   and $B \neq \emptyset$.]_ Call that element $g(1)$.

2. For each integer $k \geq 2$, suppose $g(k - 1)$ has been defined. Then
   $g(k - 1) = a_i$ form some $a_i$ in $\{a_1, a_2, a_3, \dots\}$. Starting with
   $a_i + 1$, search sequentially through $a_i + 1, a_i + 2, a_i + 3, \dots$
   trying to find an element of $B$. One must be found eventually because $B$ is
   infinite, and $\{g(1), g(2), \dots, g(k - 1)\}$ is a finite set. When an
   element of $B$ is found, define it to be $g(k)$.

By (1) and (2) above, the function $g$ is defined for each positive integer.

Since the elements of $a_1, a_2, a_3, \dots$ are all distinct, $g$ is
one-to-one. Furthermore, the searches for elements of $B$ are sequential: Each
picks up where the previous one left off. Thus every element of $A$ is reached
during some search. Moreover, all the elements of $B$ are located somewhere in
the sequence $a_1, a_2, a_3, \dots$, and so every element of $B$ is eventually
found and made the image of some integer. Hence $g$ is onto. These remarks show
that $g$ is a one-to-one correspondence from $\mathbb{Z}^+$ to $B$. So $B$ is
countably infinite and thus countable _[as was to be shown]._

---

Page 504

**Corollary 7.4.4**

Any set with an uncountable subset is uncountable.

**Proof:**

Consider the following equivalent phrasing of Theorem 7.4.3: For every set $S$
and for every subset $A$ of $S$, if $S$ is countable, then $A$ is countable. The
contrapositive of this statement is logically equivalent to it and states: For
every set $S$ and for every subset $A$ of $S$, if $A$ is uncountable then $S$ is
uncountable. Since this is an equivalent phrasing for the corollary, the
corollary is proved.
