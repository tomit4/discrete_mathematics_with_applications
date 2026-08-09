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
