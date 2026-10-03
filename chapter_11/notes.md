Page 783

**Definition**

A **real-valued function of a real variable** is a function from one set of real
numbers to another. If $f$ is a real-valued function of a real variable, then
for each real number $x$ in the domain of $f$ there is a unique corresponding
real number $f(x)$. The **graph of $f$** is the set of all points $(x, y)$ in
the Cartesian coordinate plane with the property that $x$ is in the domain of
$f$ and $y = f(x)$.

---

Page 784

**Definition**

Let $a$ be any nonnegative real number. Define $p_a$, the **power function with
exponent $a$**, as follows:

$$ p_a(x) = x^a \quad \text{ for each nonnegative real number } x $$

---

Page 787

**Definition**

Let $f$ be a real-valued function of a real variable and let $M$ be any real
number. The function $Mf$, called the **multiple of $f$ by $M$ times $f$**, is
the real-valued function with the same domain as $f$ that is defined by the rule

$$ (Mf)(x) = M \cdot (f(x)) \quad \text{ for each } x \in \text{ domain of } f $$

---

Page 788

**Definition**

Let $f$ be a real-valued function defined on a set of real numbers, and suppose
the domain of $f$ contains a set $S$. We say that $f$ is **increasing on the set
$S$** if, and only if,

$$ \text{for all real numbers } x_1 \text{ and } x_2 \text{ in } S \text{, if } x_1 < x_2 \text{ then } f(x_1) < f(x_2) $$

We say that $f$ is **decreasing on the set $S$** if, and only if,

$$ \text{for all real numbers } x_1 \text{ and } x_2 \text{ in } S \text{, if } x_1 < x_2 \text{ then } f(x_1) > f(x_2) $$

We say that $f$ is an **increasing** (or **decreasing**) **function** if, and
only if, $f$ is increasing (or decreasing) on its entire domain.

---

Page 794

**Definition**

Let $f$ and $g$ be real-valued functions defined on the same set of nonnegative
integers, with $g(n) \geq 0$ for every integer $n \geq r$, where $r$ is a
positive real number. Then

1. $f$ is of order at least $g$, written **$f(n)$ is $\Omega(g(n))$** ($f$ of
   $n$ is big-Omega of $g$ of $n$), if, and only if, there exist positive real
   numbers $A$ and $a \geq r$ such that

$$ Ag(n) \leq f(n) \quad \text{ for every integer } n \geq a $$

2. $f$ is of order at most $g$, written **$f(n)$ is $O(g(n))$** ($f$ of $n$ is
   big-_O_ of $g$ of $n$), if, and only if, there exist positive real numbers
   $B$ and $b \geq r$ such that

$$ 0 \leq f(n) \leq Bg(n) \quad \text{ for every integer } n \geq b $$

3. $f$ is of order $g$, written **$f(n)$ is $\Theta(g(n))$** ($f$ of $n$ is
   big-Theta of $g$ of $n$), if, and only if, there exist positive real numbers
   $A$, $B$, and $k \geq r$ such that

$$ Ag(n) \leq f(n) \leq Bg(n) \quad \text{ for every integer } n \geq k $$

---

Page 796

**Theorem 11.2.1 Relation among $O$-, $\Omega$-, and $\Theta$- Notations**

If $f$ and $g$ are real-valued functions defined on the same set of nonnegative
integers, and if $f(n) \geq 0$ and $g(n) \geq 0$ for every integer $n \geq r$,
where $r$ is a positive real number,

then $f(n)$ is $\Theta(g(n))$ if, and only if, $f(n)$ is $\Omega(g(n))$ and
$f(n)$ is $O(g(n))$.

---

Page 796

**Theorem 11.2.2 For any positive rational numbers $r$ and $s$ and any integer
$n \geq 1$,**

$$ \text{if } $r \leq s$ \text{, then } $n^r \leq n^s $$

---

Page 799

**Method 2 (Using a general procedure) (Finding a Big-Omega and a Big-O for a
Polynomial Function with Some Negative Coefficients):**

Let $m$ be a nonnegative integer, let $P(n)$ be a polynomial of degree $m$, and
suppose the coefficient $a_m$ of $n^m$ is positive.

To find big-Omega for $P(n)$: Let $A = \dfrac{1}{2}a_m$, and let $a$ be the
number obtained as follows:

1. Find the sum of the absolute values of all the coefficients of $P(n)$ except
   for $a_m$.

2. Multiply the result of step 1 by $\dfrac{2}{a_m}$.

3. Let $a$ be the larger of the number 1 and the result of step 2.

Show that $An^m \leq P(n)$ for every integer $n \geq a$.

---

Page 800

**Theorem 11.2.3 A Limit on What Can Be Inferred from Big-_O_**

For any function $f$ and positive real numbers $r$ and $s$ with $r < s$,

$$ \text{if } f(n) \text{ is } O(n^r) \text{ then } f(n) \text{ is } O(n^s) $$

**Proof:**

Suppose $r$ and $s$ are real numbers with $r < s$ and $f$ is a function such
that $f(n)$ is $O(n^r)$. By definition of _O_-notation, there exist positive
real numbers $B$ and $b$ such that

$$ 0 \leq f(n) \leq Bn^r \quad \text{ for every integer } n \geq b $$

Now by Theorem 11.2.2,

$$ Bn^r \leq Bn^s \quad \text{ for every integer } n \geq 1 $$

Let $b_1$ be the larger of $b$ and $1$. Then

$$ 0 \leq f(n) \leq Bn^s \quad \text{ for every integer } n \geq b_1 $$

and thus $f(n)$ is $O(n^s)$.

---

Page 803

**Theorem 11.2.4 Showing that a Big-_O_ Relationship Does Not Hold**

If $f$ is a real-valued function defined on a set of nonnegative integers and
$f(n)$ is $\Omega(n^m)$, where $m$ is a positive integer, then $f(n)$ is not
$O(n^p)$ for any positive real number $p < m$.

---

Page 803

**Theorem 11.2.5 On Polynomial Orders**

If $m$ is any integer with $m \geq 0$ and $a_0, a_1, a_2, \dots, a_m$ are real
numbers with $a_m > 0$, then $a_mn^m + a_{m - 1}n^{m - 1} + \cdots + a_1n + a_0$
is $\Theta(n^m)$.

**Proof (using limits):**

Suppose $m$ is an integer with $m \geq 0$ and suppose
$a_0, a_1, a_2, \dots, a_m$ are real numbers with $a_m > 0$. Because
$\lim\limits_{n \to \infty}\left(\dfrac{1}{n^i}\right) = 0$ for every integer
$i \geq 1$,

$$ \lim\limits_{n \to \infty}\left(\frac{a_mn^m + a_{m - 1}n^{m - 1} + a_{m - 2}n^{m -2} + \cdots + a^1n + a_0}{n^m}\right) $$

$$ = \lim\limits_{n \to \infty}\left(a_m + \frac{a_{m - 1}}{n} + \frac{a_{m - 2}}{n^2} + \cdots + \frac{a_1}{n^{m - 1}} + \frac{a_0}{n^m}\right) $$

$$ = a_m $$

By definition of limit, this implies that for any real number $\varepsilon > 0$,
there exists an integer $K$ such that

$$ a_m - \varepsilon < a_m + \frac{a_{m - 1}}{n} + \frac{a_{m - 2}}{n^2} + \cdots + \frac{a_1}{n^{m - 1}} + \frac{a_0}{n^m} < a_m + \varepsilon \quad \text{ for every integer } n > K $$

In particular, when $\varepsilon = \dfrac{a_m}{2}$, there is an integer $k$ such
that

$$ a_m - \frac{a_m}{2} < a_m + \frac{a_{m - 1}}{n} + \frac{a_{m - 2}}{n^2} + \cdots + \frac{a_1}{n^{m - 1}} + \frac{a_0}{n^m} < a_m + \frac{a_m}{2} \quad \text{ for every integer } n > k $$

Combining like terms and multiplying all parts of the inequality by $n^m$ gives
that

$$ \left(\frac{a_m}{2}\right)n^m < a_mn^m + a_{m - 1}n^{m - 1} + \cdots + a_1n + a_0 < \left(\frac{3a_m}{2}\right)n^m \quad \text{ for every integer } n > k $$

Let $A = \dfrac{a_m}{2}$ and $B = \dfrac{3a_m}{2}$. Then

$$ An^m < a_mn^m + a_{m - 1}n^{m - 1} + \cdots + a_1, n + a_0 < Bn^m \quad \text{ for every integer } n > k $$

Therefore, by definition of $\Theta$-notation,

$$ a_mn^m + a_{m - 1}n^{m - 1} + \cdots + a_1n + a_0 $$

is $\Theta(n^m)$.

---

Page 805

**Theorem 11.2.6 Reciprocal Relationship between $\Omega$- and $O$-notations

Let $f$ and $g$ be real-valued functions defined on the same set of nonnegative
integers, and suppose there is a positive real number $r$ such that
$f(n) \geq 0$ and $g(n) \geq 0$ for every integer $n \geq r$. Then:

a. If $f(n)$ is $\Omega(g(n))$, then $g(n)$ is $O(f(n))$.

b. If $g(n)$ is $O(f(n))$, then $f(n)$ is $\Omega(g(n))$.

---

Page 805

**Theorem 11.2.7 Reflexive, Symmetric, and Transitive Properties of
$\Theta$-notation**

Let $f$, $g$, and $h$ be real-valued functions defined on the same set of
nonnegative integers, and suppose there is a positive real number $r$ such that
$f(n) \geq 0$, $g(n) \geq 0$ and $h(n) \geq 0$, for every integer $n \geq r$.
Then:

a. $f(n)$ is $\Theta(f(n))$.

b. If $f(n)$ is $\Theta(g(n))$, then $g(n)$ is $\Theta(f(n))$.

c. If $f(n)$ is $\Theta(g(n))$ and $g(n)$ is $\Theta(h(n))$, then $f(n)$ is
$\Theta(h(n))$.

---

Page 805

**Theorem 11.2.8 Effect of Constants on Order Notations**

Let $f$ and $g$ be real-valued functions defined on the same set of nonnegative
integers, and suppose there is a positive real number $r$ such that
$f(n) \geq 0$ and $g(n) \geq 0$ for every integer $n \geq r$.

Then for every positive real number $c$:

a. If $f(n)$ is $\Omega(g(n))$, then $cf(n)$ is $\Omega(g(n))$.

b. If $f(n)$ is $O(g(n))$, then $cf(n)$ is $O(g(n))$.

c. If $f(n)$ is $\Theta(g(n))$, then $cf(n)$ is $\Theta(g(n))$.

---

Page 805

**Theorem 11.2.9 Orders of Sums and Products of Functions**

Let $f_1$, $f_2$, $g_1$, and $g_2$ be real-valued functions defined on the same
set of nonnegative integers, and suppose there is a positive real number $r$
such that $f_1(n) \geq 0$, $f_2(n) \geq 0$, $g_1(n) \geq 0$, and $g_2(n) \geq 0$
for every integer $n \geq r$. Then:

a. If $f_1(n)$ is $\Theta(g(n))$ and $f_2(n)$ is $\Theta(g(n))$, then
$(f_1(n) + f_2(n))$ is $\Theta(g(n))$.

b. If $f_1(n)$ is $\Theta(g_1(n))$ and $f_2(n)$ is $\Theta(g_2(n))$, then
$(f_1(n)f_2(n))$ is $\Theta(g_1(n)g_2(n))$.

c. If $f_1(n)$ is $\Theta(g_1(n))$ and $f_2(n)$ is $\Theta(g_2(n))$ and if there
is a real number $s$ so that $g_1(n) \leq g_2(n)$ for every integer $n \geq s$,
then $(f_1(n) + f_2(n))$ is $\Theta(g_2(n))$.

---

Page 805

**Proof of Theorem 11.2.6(a)**

Let $f$ and $g$ be real-valued functions defined on the same set of nonnegative
integers and suppose there is a positive real number $r$ such that $g(n) \geq 0$
for every integer $n \geq r$. Suppose also that $f(n)$ is $\Omega(g(n))$. We
will show that $g(n)$ is $O(f(n))$. By definition of $\Omega$-notation, there
are positive real numbers $A$ and $a$ such that $a \geq r$, and

$$ Ag(n) \leq f(n) \quad \text{ for every integer } n \geq a $$

Divide both sides by $A$ to obtain

$$ g(n) \leq \frac{1}{A}f(n) $$

for every integer $n \geq a$.

In addition, since $a \geq r$,

$$ 0 \leq g(n) $$

for every integer $n \geq a$.

Let $B = \dfrac{1}{A}$ and $b = a$. Then $B$ and $b$ are positive real numbers
and

$$ 0 \leq g(n) \leq Bf(n) $$

for every integer $n \geq b$.

and so $g(n)$ is $O(f(n))$ by definition of $O$-notation _[as was to be shown]_.

---

Page 806

**Proof of Theorem 11.2.7\(c\)**

Suppose $f$, $g$, and $h$ are real-valued functions defined on the same set of
nonnegative integers, and suppose there is a positive real number $r$ such that
$f(n) \geq 0$, $g(n) \geq 0$, and $h(n) \geq 0$, for every integer $n \geq r$.
Suppose also that $f(n)$ is $\Theta(g(n))$ and $g(n)$ is $\Theta(h(n))$. We will
show that $f(n)$ is $\Theta(h(n))$. By definition of $\Theta$-notation, there
exist positive real numbers $A_1, B_1, k, A_2, B_2$, and $k_2$ with $k_1 \geq r$
and $k_2 \geq r$, and

$$ A_1g(n) \leq f(n) \leq B_1g(n) $$

for every integer $n \geq k_1$

and

$$  A_2h(n) \leq g(n) \leq B_2h(n)$$

for every integer $n \geq k_2$

Let $A = A_1A_2, B = B_1B_2$, and $k = \text{max}(k_1, k_2)$. Then, by
transitivity of order and equality, for every integer $n \geq k$,

$$ Ah(n) = A_1(A_2h(n)) \leq A_1g(n) \leq f(n) \leq B_1g(n) \leq B_1(B_2h(n)) = Bh(n) $$

and so, by definition of $\Theta$-notation, $f(n)$ is $\Theta(h(n))$ _[as was to
be shown]_.
