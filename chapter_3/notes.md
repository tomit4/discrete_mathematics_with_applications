Page 132

**Definition**

A **predicate** is a sentence that contains a finite number of variables and
becomes a statement when specific values are substituted for the variables. The
**domain** of a predicate variable is the set of all values that may be
substituted in place of the variable.

---

Page 132

**Definition**

If $P(x)$ is a predicate and $x$ has domain $D$, the **truth set** of $P(x)$ is
the set of all elements of $D$ that make $P(x)$ true when they are substituted
for $x$. The truth set of $P(x)$ is denoted

$$ \{x \in D | P(x)\} $$

---

Page 133

**Definition**

Let $Q(x)$ be a predicate and $D$ the domain of $x$. A **universal statement**
is a statement of the form "$\forall x \in D, Q(x)$." It is defined to be true
if, and only if, $Q(x)$ is true for each individual $x$ in $D$. It is defined to
be false if, and only if, $Q(x)$ is false for at least one $x$ in $D$. A value
for $x$ for which $Q(x)$ is false is called a **counterexample** to the
universal statement.

---

Page 134

**Definition**

Let $Q(x)$ be a predicate and $D$ the domain of $x$. An **existential
statement** is a statement of the form "$\exists x \in D$ such that $Q(x)$." It
is defined to be true if, and only if, $Q(x)$ is true for at least one $x$ in
$D$. It is false if, and only if, $Q(x)$ is false for all $x$ in $D$.

---

Page 140

**Notation**

Let $P(x)$ and $Q(x)$ be predicates and suppose the domain of $x$ is $D$.

- The notation $P(x) \Rightarrow Q(x)$ means that every element in the truth set
  of $P(x)$ is in the truth set of $Q(x)$, or, equivalently,
  $\forall x, P(x) \to Q(x)$.

- The notation $P(x) \Leftrightarrow Q(x)$ means that $P(x)$ and $Q(x)$ have
  identical truth sets, or, equivalently,
  $\forall x, P(x) \leftrightarrow Q(x)$.

---

Page 145

**Theorem 3.2.1 Negation of a Universal Statement**

The negation of a statement of the form

$$ \forall \text{ in } D, Q(x) $$

is logically equivalent to a statement of the form

$$ \exists \text{ in } D \text{ such that } \neg Q(x) $$

Symbolically,

$$ \neg(\forall x \in D, Q(x)) \equiv \exists x \in D \text{ such that } \neg Q(x) $$

---

Page 146

**Theorem 3.2.2 Negation of an Existential Statement**

The negation of a statement of the form

$$ \exists \text{ in } D \text{ such that } Q(x) $$

is logically equivalent to a statement of the form

$$ \forall x \text{ in } D, \neg Q(x) $$

Symbolically,

$$ \neg(\exists x \in D \text{ such that } Q(x)) \equiv \forall x \in D, \neg Q(x) $$

---

Page 148

**Negation of a Universal Conditional Statement**

$$ \neg(\forall x, \text{ if } P(x) \text{ then } Q(x)) \equiv \exists x \text{ such that } P(x) \text{ and } \neg Q(x) $$

$$ \neg(\forall x, P(x) \to Q(x)) \equiv \exists x, (P(x) \wedge \neg Q(x)) $$

---

Page 150

**Definition**

Consider a statement of the form
$\forall x \in D, \text{ if } P(x) \text{ then } Q(x)$.

1. Its **contrapositive** is the statement
   $\forall x \in D, \text{ if } \neg Q(x) \text{ then } \neg P(x)$.

2. Its **converse** is the statement
   $\forall x \in D, \text{ if } Q(x) \text{ then } P(x)$.

3. Its **inverse** is the statement
   $\forall x \in D, \text{ if } \neg P(x) \text{ then } \neg Q(x)$.

---

Page 151

**Definition**

- "$\forall x, r(x)$ is a **sufficient condition** for $s(x)$" means
  "$\forall x, \text{ if } r(x) \text{ then } s(x)$."

- "$\forall x, r(x)$ is a **necessary condition** for $s(x)$" means
  "$\forall x, \text{ if } \neg r(x) \text{ then } \neg s(x)$" or, equivalently,
  "$\forall x, \text{ if } s(x) \text{ then } r(x)$."

- "$\forall x, r(x)$ **only if** $s(x)$" means
  "$\forall x, \text{ if } \neg s(x) \text{ then } \neg r(x)$" or, equivalently,
  "$\forall x, \text{ if } r(x) \text{ then } s(x)$."

---

Page 156

**Interpreting Statements with Two Different Quantifiers**

If you want to establish the truth of a statement of the form

$$ \forall x \text{ in } D, \exists y \text{ in } E \text{ such that } P(x, y) $$

your challenge is to allow someone else to pick whatever element $x$ in $D$ they
wish and then you must find an element $y$ in $E$ that "works" for that
particular $x$.

If you want to establish the truth of a statement of the form

$$ \exists x \text{ in } D \text{ such that } \forall y \text{ in } E, P(x, y) $$

your job is to find one particular $x$ in $D$ that will "work" no matter what
$y$ in $E$ anyone might choose to challenge you with.

---

**Negations of Statements with Two Different Quantifiers**

$\neg(\forall x \text{ in } d, \exists y \text{ in } E \text{ such that } P(x, y)) \equiv \exists x \text{ in } D \text{ such that } \forall y \text{ in } E, \neg P(x, y)$

$\neg(\exists x \text{ in } D \text{ such that } \forall y \text{ in } E, P(x, y)) \equiv \forall x \text{ in } D, \exists y \text{ in } E \text{ such that } \neg P(x, y)$
