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
