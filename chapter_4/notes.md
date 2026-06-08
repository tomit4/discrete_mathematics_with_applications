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

---

Page 206

**Definition**

A real number $r$ is **rational** if, and only if, it can be expressed as a
quotient of two integers with a nonzero denominator. A real number that is not
rational is **irrational**. More formally, if $r$ is a real number, then

$$ r \text{ is rational } \Leftrightarrow \exists \text{ integers } a \text{ and } b \text{ such that } r = \frac{a}{b} \text{ and } b \neq 0 $$

---

Page 207

**Zero Product Property**

If neither of two real numbers is zero, then their product is also not zero.

---

Page 208

**Theorem 4.3.1**

Every integer is a rational number.

---

Page 209

**Theorem 4.3.2**

The sum of any two rational numbers is rational.

**Proof:**

Suppose $r$ and $s$ are any rational numbers. _[We must show that $r + s$ is
rational.]_ Then, by definition of rational, $r = \dfrac{a}{b}$ and
$s = \dfrac{c}{d}$ for some integers $a$, $b$, $c$, and $d$ with $b \neq 0$ and
$d \neq 0$. Thus

$$ r + s = \frac{a}{b} + \frac{c}{d} \quad \text{ by substitution} $$

$$ \quad = \frac{ad + bc}{bd} \quad \text{ by basic algebra} $$

Let $p = ad + bc$ and $q = bd$. Then $p$ and $q$ are integers because products
and sums of integers are integers and because $a$, $b$, $c$, and $d$ are
integers. Also $q \neq 0$ by the zero product property. Thus

$$ r + s = \frac{p}{q} \text{ where } p \text{ and } q \text{ are integers and } q \neq 0 $$

Therefore, $r + s$ is rational by the definition of a rational number _[as was
to be shown]_.

---

Page 210

**Corollary 4.2.3**

The double of a rational number is rational.

---

Page 213

**Definition**

If $n$ and $d$ are integers then

$n$ is **divisible by** $d$ if, and only if, $n$ equals $d$ times some integer
and $d \neq 0$.

Instead of "$n$ is divisible by $d$," we can say that

$n$ **is a multiple of** $d$, or

$d$ **is a factor of** $n$, or

$d$ **is a divisor of** $n$, or

$d$ **divides** $n$.

The notation $d \mid n$ is read "$d$ divides $n$." Symbolically, if $n$ and $d$
are integers:

$$ d \mid n \Leftrightarrow \exists \text{ an integer, say } k, \text{ such that } n = dk \text{ and } d \neq 0 $$

The notation $d \nmid n$ is read "$d$ does not divide $n$."

---

Page 214

**Theorem 4.4.1 A Positive Divisor of a Positive Integer**

For all integers $a$ and $b$, if $a$ and $b$ are positive and $a$ divides $b$
then $a \leq b$.

**Proof:**

Suppose $a$ and $b$ are positive integers such that $a$ divides $b$. _[We must
show that $a \leq b$.]_ By definition of divisibility, there exists an integer
$k$ so that $b = ak$. By property T25 of Appendix A, $k$ must be positive
because both $a$ and $b$ are positive. It follows that

$$ 1 \leq k $$

because every positive integer is greater than or equal to $1$. Multiplying both
sides by $a$ gives

$$ a \leq ka = b $$

because multiplying both sides of an inequality by a positive number preserves
the inequality by property T20 of Appendix A. Thus $a \leq b$ _[as was to be
shown]._

---

Page 214

**Theorem 4.4.2 Divisors of 1**

The only divisors of $1$ are $1$ and $-1$.

**Proof:**

Since $1 \cdot 1 = 1$ and $(-1)(-1) = 1$, both $1$ and $-1$ are divisors of $1$.
Now suppose $m$ is any integer that divides $1$. Then there exists an integer
$n$ such that $1 = mn$. By Theorem T25 in Appendix A, either both $m$ and $n$
are positive or both $m$ and $n$ are negative. If both $m$ and $n$ are positive,
then $m$ is a positive integer divisor of $1$. By Theorem 4.4.1, $m \leq 1$,
and, since the only positive integer that is less than or equal to $1$ is $1$
itself, it follows that $m = 1$. On the other hand, if both $m$ and $n$ are
negative, then by Theorem T12 in Appendix A, $(-m)(-n) = mn = 1$. In this case
$-m$ is a positive integer divisor of $1$, and so, by the same reasoning,
$-m = 1$ and thus $m = -1$. Therefore there are only two possibilities: either
$m = 1$ or $m = -1$. So the only divisors of $1$ are $1$ and $-1$.

---

Page 215

For all integers $n$ and $d$, $d \nmid n \Leftrightarrow \frac{n}{d}$ is not an
integer.

---

Page 216

**Theorem 4.4.3 Transitivity of Divisibility**

For all integers $a$, $b$, and $c$, if $a$ divides $b$ and $b$ divides $c$, then
$a$ divides $c$.

**Proof:**

Suppose $a$, $b$, and $c$ are any _[particular but arbitrarily chosen]_ integers
such that $a$ divides $b$ and $b$ divides $c$. _[We must show that $a$ divides
$c$.]_ By definition of divisibility,

$$ b = ar \text{ and } c = bs \quad \text{ for some integers } r \text{ and } s $$

By substitution

$$ c = bs $$

$$ \quad = (ar)s $$

$$ \quad = a(rs) \quad \text{ by basic algebra} $$

Let $k = rs$. Then $k$ is an integer since it is a product of integers, and
therefore

$$ c = ak \quad \text{ where } k \text{ is an integer} $$

Thus $a$ divides $c$ by definition of divisibility. _[This is what was to be
shown.]_

---

Page 217

**Theorem 4.4.4 Divisibility by a Prime**

Any integer $n > 1$ is divisible by a prime number.

**Proof:**

Suppose $n$ is a _[particular but _arbitrarily chosen]_ integer that is greater
than $1$. _[We must show that there is a prime number that divides $n$.]_ If $n$
is prime, then $n$ is divisible by a prime number (namely itself), and we are
done. If $n$ is not prime, the as discussed in Example 4.1.2b,

$n = r_0s_0$ where $r_0$ and $s_0$ are integers and $1 < r_0 < n$ and
$1 < s_0 < n$.

It follows by definition of divisibility that $r_0 \mid n$.

If $r_0$ is prime, then $r_0$ is a prime number that divides $n$, and we are
done. If $r_0$ is not prime, then

$r_0 = r_1s_1$ where $r_1$ and $s_1$ are integers and $1 < r_1 < r_0$ and
$1 < s_1 < r_0$.

It follows by the definition of divisibility that $r_q \mid r_0$. But we already
know that $r_0 \mid n$. Consequently, by transitivity of divisibility,
$r_1 \mid n$.

If $r_1$ is prime, then $r_1$ is a prime number that divides $n$, and we are
done. If $r_1$ is not prime, then

$r_1 = r_2s_2$ where $r_2$ and $s_2$ are integers and $1 < r_2 < r_1$ and
$1 < s_2 < r_1$.

It follows by the definition of divisibility that $r_2 \mid r_1$. But we already
know that $r_1 \mid n$. Consequently, by transitivity of divisibility,
$r_2 \mid n$.

If $r_2$ is prime, then $r_2$ is a prime number that divides $n$, and we are
done. If $r_2$ is not prime, then we may repeat the previous process by
factoring $r_2$ as $r_3s_3$.

We may continue in this way, factoring successive factors of $n$ until we find a
prime factor. We must succeed in a finite number of steps because each new
factor is both less than the previous one (which is less than $n$) and greater
than $1$, and there are fewer than $n$ integers strictly between $1$ and $n$.
Thus we obtain a sequence

$$ r_0, r_1, r_2, \dots, r_k $$

where $k \geq 0$, $1 < r_k < r_{k - 1} < \dots < r_2 < r_1 < r_0 < n$, and
$r_i \mid n$ for each $i = 0, 1, 2, \dots, k$. The condition for termination is
that $r_k$ should be prime. Hence $r_k$ is a prime number that divides $n$.
_[This is what we were to show.]_

---

Page 218

**Proposed Divisibility Property:** For all integers $a$ and $b$, if $a \mid b$
and $b \mid a$ then $a = b$.

**Counterexample:** Let $a = 2$ and $b = -2$. Then $-2 = (-1) \cdot 2$ and
$2 = (-1) \cdot (-2)$, and thus

$$ a \mid b \text{ and } b \mid a, \text{ but } a \neq b \text{ because } 2 \neq -2 $$

Therefore, the statement is false.

---

Page 219

**Theorem 4.4.5 Unique Factorization of Integers Theorem (Fundamental Theorem of
Arithmetic)**

Given any integer $n > 1$, there exist a positive integer $k$, distinct prime
numbers $p_1, p_2, \dots, p_k$, and positive integers $e_1, e_2, \dots, e_k$
such that

$$ n = p_1^{e_1}p_2^{e^2}p_3^{e^3}\dots p_k^{e_k} $$

and any other expression for $n$ as a product of prime numbers is identical to
this except, perhaps, for the order in which the factors are written.

---

Page 219

**Definition**

Given any integer $n > 1$, the **standard factored form** of $n$ is an
expression of the form

$$ n = p_1^{e_1}p_2^{e^2}p_3^{e^3}\dots p_k^{e_k} $$

where $n$ is a positive integer, $p_1,p_2,\dots , p_k$ are prime numbers,
$e_1,e_2,\dots ,e_k$ are positive integers, and $p_1 < p_2 < \dots < p_k$.
