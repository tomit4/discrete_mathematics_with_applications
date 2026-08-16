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
