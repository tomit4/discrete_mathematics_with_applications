Page 184

**Assumptions**

- In this text we assume familiarity with the laws of basic algebra, which are
  listed in Appendix A.

- We also use the three properties of equality: For all objects $A$, $B$, and
  $C$, (1) $A = A$, (2) if $A = B$, then $B = 1$, and (3) if $A = B$ and
  $B = C$, then $A = C$.

- And we use the principle of substitution: For all objects $A$ and $B$, if
  $A = B$, then we may substitute $B$ whenever we have $A$.

- In addition, we assume that there is no integer between $0$ and $1$ and that
  the set of all integers is closed under addition, subtraction, and
  multiplication. This means that sums, differences, and products of integers
  are integers.

---

Page 185

**Definitions**

An integer $n$ is **even** if, and only if, $n$ equals twice some integer. An
integer $n$ is **odd** if, and only if, $n$ equals twice some integer plus $1$.

Symbolically, for any integer $n$

$$ n \text{ is even} \Leftrightarrow n = 2k \text{ for some integer } k $$

$$ n \text{ is odd} \Leftrightarrow n = 2k + 1 \text{ for some integer } k $$

---

Page 186

**Definition**

An integer $n$ is **prime** if, and only if, $n > 1$ and for all positive
integers $r$ and $s$, if $n = rs$, then either $r$ or $s$ equals $n$. An integer
$n$ is **composite** if, and only if, $n > 1$ and $n = rs$ for some integers $r$
and $s$ with $1 < r < n$ and $1 < s < n$.

In symbols: For each integer $n$ with $n > 1$,

$$ n \text{ is prime} \Leftrightarrow \forall \text{ positive integers } r \text{ and } s, \text{ if } n = rs \text{ then either } r = 1 \text{ and } s = n \text{ or } r = n \text{ and } s = 1 $$

$$ n \text{ is composite} \Leftrightarrow \exists \text{ positive integers } r \text{ and } s \text{ such that } n = rs \text{ and } 1 < r < n \text{ and } 1 < s < n $$

---

Page 188

**Disproof by Counterexample**

To disprove a statement of the form
"$\forall x \in D, \text{ if } P(x) \text{ then } Q(x)$," find a value of $x$ in
$D$ for which the hypothesis $P(x)$ is true and the conclusion $Q(x)$ is false.
Such an $x$ is called a **counterexample**.

---

Page 189

**Generalizing from the Generic Particular**

To show that _every_ element of a set satisfies a certain property, suppose $x$
is a _particular_ but _arbitrarily chosen_ element of the set, and show that $x$
satisfies the property.

---

Page 191

**Existential Instantiation**

If the existence of a certain kind of object is assumed or has been deduce, then
it can be given a name, as long as that name is not currently being used to
refer to something else in the same discussion.

---

Page 192

**Theorem 4.1.1**

The sum of any two even integers is even.

**Proof:** Suppose $m$ and $n$ are any _[particular but arbitrarily chosen]_
even integers. _[We must show that $m + n$ is even.]_ By definition of even,
$m = 2r$ and $n = 2s$ for some integers $r$ and $s$. Then

$$ m + n = 2r + 2s \quad \text{ by substitution} $$

$$ \quad = 2(r + s) \quad \text{ by factoring out a 2} $$

Let $t = r + s$. Note that $t$ is an integer because it is a sum of integers.
Hence

$$ m + n = 2r \quad \text{where } t \text{ is an integer} $$

It follows by definition of even that $m + n$ is even. _[This is what we needed
to show.]_

---

Page 196

Personal Note: The entirety of 4.2 is extremely helpful in breaking down in
exactly how to write proofs (for beginners). I'd advise revisiting this entire
section frequently.
