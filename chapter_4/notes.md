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

---

Page 223

**Theorem 4.5.1 The Quotient Remainder Theorem**

Given any integer $n$ and positive integer $d$, there exists unique integers $q$
and $r$ such that

$$ n = dq + r \quad \text{ and } \quad 0 \leq r < d $$

---

Page 224

**Definition**

Given an integer $n$ and a positive integer $d$,

$$ n\ div\ d = \text{ the integer quotient obtained when } n \text{ is divided by } d \text{ and } $$

$$ n \mod d = \text{ the nonnegative integer remainder obtained when } n \text{ is divided by } d $$

Symbolically, if $n$ and $d$ are integers and $d > 0$ then

$$ n\ div\ d = \quad \text{ and } \quad n \mod d = r \Leftrightarrow n = dq + r $$

where $q$ and $r$ are integers and $0 \leq r < d$.

---

**Theorem 4.5.2 The Parity Property**

Any two consecutive integers have opposite parity.

**Proof:**

Suppose that two _[particular but arbitrarily chosen]_ consecutive integers are
given; call them $m$ and $m + 1$. _[We must show that one of $m$ and $m + 1$ is
even and that the other is odd.]_ By the parity property, either $m$ is even or
$m$ is odd. _[We break the proof into two cases depending on whether $m$ is even
or odd.]_

_Case 1 ($m$ is even):_ In this case, $m = 2k$ for some integer $k$, and so
$m + 1 = 2k + 1$, which is odd _[by the definition of odd.]_ Hence in this case,
one of $m$ and $m + 1$ is even and the other is odd.

_Case 2 ($m$ is odd):_ In this case, $m = 2k + 1$ for some integer $k$, and so
$m + 1 = (2k + 1) + 1 = 2k + 2 = 2(k + 1)$. But $k + 1$ is an integer because it
is a sum of two integers. Therefore, $m + 1$ equals twice some integer, and thus
$m + 1$ is even. Hence in this case also, one of $m$ and $m + 1$ is even and the
other is odd.

It follows that regardless of which case actually occurs for the particular $m$
and $m + 1$ is even and the other is odd. _[This is what was to be shown.]_

---

Page 227

**Method of Proof by Division into Cases**

To prove a statement of the form "If $A_1$ or $A_2$ or $\dots$ or $A_n$, then
$C$," prove all of the following:

$$
\text{If } A_1, \text{ then } C \\
\text{If } A_2, \text{ then } C \\
\vdots \\
\text{If } A_n, \text{ then } C \\
$$

This process shows that $C$ is true regardless of which of $A_1$, $A_2$,
$\dots$, $A_n$ happens to be the case.

---

Page 229

**Theorem 4.5.3**

The square of any odd integer has the form $8m + 1$ for some integer $m$.

**Proof:** Suppose $n$ is a _[particular but arbitrarily chosen]_ odd integer.
By the quotient-remainder theorem with the divisor equal to $4$, $n$ can be
written in one of the forms

$$ 4q \quad \text{ or } \quad 4q + 1 \quad \text{ or } \quad 4q + 2 \quad \text{ or } \quad 4q + 3 $$

for some integer $q$. In fact, since $n$ is odd and $4q$ and $4q + 2$ are even,
$n$ must have one of the forms

$$ 4q + 1 \quad \text{ or } \quad 4q + 3 $$

_Case 1($n = 4q + 1$ for some integer $q$)_ _[We must find an integer $m$ such
that $n^2 = 8m + 1$.]_ Since $n = 4q + 1$,

$$ n^2 = (4q + 1)^2 \quad \text{ by substitution} $$

$$ \quad = (4q + 1)(4q + 1) \quad \text{ by definition of square} $$

$$ \quad = 16q^2 + 8q + 1 $$

$$ \quad = 8(2q^2 + 1) + 1 \quad \text{ by the laws of algebra} $$

Let $m = 2q^2 + q$. Then $m$ is an integer since $2$ and $q$ are integers and
sums and products of integers are integers. Thus, substituting,

$$ n^2 = 8m + 1 \quad \text{ where } m \text{ is an integer} $$

_Case 2 ($n = 4q + 3$ for some integer $q$):_ _[We must find an integer $m$ such
that $n^2 = 8m + 1$.]_ Since $n = 4q + 3$,

$$ n^2 = (4q + 3)^2 \quad \text{ by substitution} $$

$$ \quad = (4q + 3)(4q + 3) \quad \text{ by definition of square} $$

$$ \quad = 16q^2 + 24q + 9 $$

$$ \quad = 16q^2 + 24q + (8 + 1) $$

$$ \quad = 8(2q^2 + 3q + 1) + 1 \quad \text{ by the laws of algebra} $$

_[The motivation for the choice of algebra steps was the desire to write the
expression in the form $8 \cdot \text{ some integer } + 1$.]_

Let $m = 2q^2 + 3q + 1$. Then $m$ is an integer since $1$, $2$, $3$, and $q$ are
integers and sums and products of integers are integers. Thus, substituting,

$$ n^2 = 8m + 1 \quad \text{ where } m \text{ is an integer} $$

Cases 1 and 2 show that given any odd integer, whether of the form $4q + 1$ or
$4q + 3$, $n^2 = 8m + 1$ for some integer $m$. _[This is what we needed to
show.]_

---

Page 231

**Definition**

For any real number $x$, the **absolute value of** $x$, denoted $|x|$, is
defined as follows:

$$
|x| =
\begin{cases}
x & \text{if } x \geq 0 \\
-x & \text{if } x < 0
\end{cases}
$$

---

Page 231

**Lemma 4.5.4**

For every real number, $r$, $-|r| \leq r \leq |r|$

**Proof:** Suppose $r$ is any real number. We divide into cases according to
whether $r = 0$, $r > 0$, or $r < 0$.

_Case 1($r = 0$):_ In this case, by definition of absolute value, $|r| = r = 0$
since $0 = -0$, we have that $-0 = -|r| = 0 = r = |r|$, and so it is true that

$$ -|r| \leq r \leq |r| $$

_Case 2 ($r > 0$):_ In this case, by definition of absolute value,
[$\&|\text{pipe}|r|\text{pipe}||=|r\&$]. Also, since $r$ is positive and $-|r|$
is negative, $-|r| < r$. Thus it is true that

$$ -|r| \leq r \leq |r| $$

_Case 3 ($r < 0$):_ In this case, by definition of absolute value, $|r| = -r$.
Multiplying both sides by $-1$ gives that $-|r| = r$. Also, since $r$ is
negative and $|r|$ is positive, $r < |r|$. Thus it is also true in this case
that

$$ -|r| \leq r \leq |r| $$

Hence, in every case,

$$ -|r| \leq r \leq |r| $$

_[as was to be shown]._

---

Page 231

**Lemma 4.5.5**

For ever real number $r$, $|-r| = |r|$.

**Proof:** Suppose $r$ is any real number. By Theorem T23 in Appendix A, if
$r > 0$, then $-r < 0$, and if $r < 0$, then $-r > 0$. Thus

$$
|-r| =
\begin{cases}
-r & \text{if } -r > 0 \\
0 & \text{if } -r = 0 \\
-(-r) & \text{if } -r < 0
\end{cases}
$$

$$
\quad =
\begin{cases}
-r & \text{if } -r > 0 \\
0 & \text{if } r = 0 \\
r & \text{if } -r < 0
\end{cases}
$$

$$
\quad =
\begin{cases}
-r & \text{if } r < 0 \\
0 & \text{if } r = 0 \\
r & \text{if } r > 0
\end{cases}
$$

$$
\quad =
\begin{cases}
r & \text{if } r \geq 0 \\
-r & \text{if } r < 0 \\
\end{cases}
$$

$$ \quad = |r| $$

---

Page 231

**Theorem 4.5.6 The Triangle Inequality**

For all real numbers $x$ and $y$, $|x + y| \leq |x| + |y|$.

**Proof:** Suppose $x$ and $y$ are real numbers.

_Case 1 ($x + y \geq 0$):_ In this case, $|x + y| = x + y$, and so, by Lemma
4.5.4,

$$ x \leq |x| \quad \text{ and } y \leq |y| $$

Hence, by Theorem T26 of Appendix A,

$$ |x + y| = x + y \leq |x| + |y| $$

_Case 2 ($x + y < 0$):_ In this case, $|x + y| = -(x + y) = (-x) + (-y)$, and
so, by Lemmas 4.5.4 and 4.5.5,

$$ -x \leq |-x| = |x| \quad \text{ and } \quad -y \leq |-y| = |y| $$

It follows, by Theorem T26 of Appendix A, that

$$ |x + y| = (-x) + (-y) \leq |x| + |y| $$

Hence in both cases $|x + y| = |x| + |y|$ _[as was to be shown]._

---

Page 234

**Definition**

Given any real number $x$, the **floor of** $x$, denoted $\lfloor x \rfloor$, is
defined as follows:

$\lfloor x \rfloor =$ that unique integer $n$ such that $n \leq x < n + 1$.

Symbolically, if $x$ is a real number and $n$ is an integer, then

$$ \lfloor x \rfloor = n \Leftrightarrow n \leq x < n + 1 $$

---

Page 235

**Definition**

Given any real number $x$, the **ceiling of** $x$, denoted $\lceil x \rceil$, is
defined as follows:

$\lceil x \rceil =$ that unique integer $n$ such that $n - 1 < x \leq n$.

Symbolically, if $x$ is a real number and $n$ is an integer, then

$$ \lceil x \rceil = n \Leftrightarrow n - 1 < x \leq n $$

---

Page 237

**Theorem 4.6.1**

For every real number $x$ and every integer $m$,
$\lfloor x + m \rfloor = \lfloor x \rfloor + m$.

**Proof:**

Suppose any real number $x$ and any integer $m$ are given. _[We must show that
$\lfloor x + m \rfloor = \lfloor x \rfloor + m$.]_ Let $n = \lfloor x \rfloor$.
By definition of floor, $n$ is an integer and

$$ n \leq x < n + 1 $$

Add $m$ to all three parts to obtain

$$ n + m \leq x + m < n + m + 1 $$

_[since adding a number to both sides of an inequality does not change the
direction of the inequality]._

Now $n + m$ is an integer _[since $n$ and $m$ are integers and a sum of integers
is an integer]_, and so, by definition of floor, the left-hand side of the
equation to be shown is

$$ \lfloor x + m \rfloor = n + m $$

But $n = \lfloor x \rfloor$. Hence, by substitution,

$$ n + m = \lfloor x \rfloor + m $$

which is the right-hand side of the equation to be shown. Thus
$\lfloor x + m \rfloor = \lfloor x \rfloor + m$ _[as was to be shown]._

---

Page 238

**Theorem 4.6.2 The Floor of $\dfrac{n}{2}$**

For any integer $n$,

$$
\left\lfloor \frac{n}{2} \right\rfloor =
\begin{cases}
\dfrac{n}{2} & \text{if } n \text{ is even} \\
\dfrac{n - 1}{2} & \text{if } n \text{ is odd} \\
\end{cases}
$$

**Proof:**

Suppose $n$ is a _[particular but arbitrarily chosen]_ integer. By the quotient
remainder theorem, either $n$ is odd or $n$ is even.

_Case 1 ($n$ is odd):_

In this case, $n = 2k + 1$ for some integer $k$. _[We must show that
$\left\lfloor \dfrac{n}{2} \right\rfloor = \dfrac{(n - 1)}{2}$.]_ But the
left-hand side of the equation to be shown is

$$ \left\lfloor \frac{n}{2} \right\rfloor = \left\lfloor \frac{2k + 1}{2} \right\rfloor = \left\lfloor \frac{2k}{2} + \frac{1}{2} \right\rfloor = \left\lfloor k + \frac{1}{2} \right\rfloor = k $$

because $k$ is an integer and $k \leq k + \dfrac{1}{2} < k + 1$. And the
right-hand side of the equation to be shown is

$$ \frac{n - 1}{2} = \frac{(2k + 1) - 1}{2} = \frac{2k}{2} = k $$

also. So since both the left-hand and right-hand sides equal $k$, they are equal
to each other. That is,
$\left\lfloor \dfrac{n}{2} \right\rfloor = \dfrac{n - 1}{2}$ _[as was to be
shown]._

_Case 2 ($n$ is even):_

In this case, $n = 2k$ for some integer $k$. _[We must show that
$\left\lfloor \dfrac{n}{2} \right\rfloor$]_ The rest of the proof of this case
is left as an exercise.

---

Page 239

**Theorem 4.6.3**

If $n$ is any integer and $d$ is a positive integer, and if
$q = \left\lfloor \frac{n}{d} \right\rfloor$ and
$r = n - d \cdot \left\lfloor \frac{n}{d} \right\rfloor$, then

$$ n = dq + r \quad \text{ and } \quad 0 \leq r < d $$

**Proof:**

Suppose $n$ is any integer, $d$ is a positive integer,
$q = \left\lfloor \dfrac{n}{d} \right\rfloor$, and
$r = n - d \cdot \left\lfloor \frac{n}{d} \right\rfloor$. _[We must show that
$n = dq + r$ and $0 \leq r < d$.]_ By substitution,

$$ dq + r = d \cdot \left\lfloor \frac{n}{d} \right\rfloor + \left(n - d \cdot \left\lfloor \frac{n}{d} \right\rfloor\right) = n $$

So it remains only to show that $0 \leq r < d$. But
$q = \left\lfloor \frac{n}{d} \right\rfloor$. Thus, by definition of floor,

$$ q \leq \frac{n}{d} < q + 1 $$

Then

$$ dq \leq n < dq + d \quad \text{ by multiplying all parts by } d $$

and so

$$ 0 \leq n - dq < d \quad \text{ by subtracting } dq \text{ from all parts.} $$

But

$$ r = n - d\left\lfloor \frac{n}{d} \right\rfloor = n - dq $$

Hence

$$ 0 \leq r < d \quad \text{ by substitution} $$

_[This is what was to be shown.]_

---

Page 241

**Method of Proof by Contradiction**

1. Suppose the statement to be proved is false. That is, suppose the negation of
   the statement is true.

2. Show that this supposition leads logically to a contradiction.

3. Conclude that the statement to be proved is true.

---

Page 242

**Theorem 4.7.1**

There is no greatest integer.

**Proof:**

_[We take the negation of the theorem and suppose it to be true.]_ Suppose not.
That is, suppose there is a greatest integer $N$. _[We must deduce a
contradiction.]_ Then $N \geq n$ for every integer $n$. Let $M = N + 1$. Now $M$
is an integer since it is a sum of integers. Also $M > N$ since $M = N + 1$.
Thus $M$ is an integer that is greater than $N$. So $N$ is the greatest integer
and $N$ is not the greatest integer, which is a contradiction. _[This
contradiction shows that the supposition is false and hence, that the theorem is
true.]_

---

**Theorem 4.7.2**

There is no integer that is both even and odd.

**Proof:**

_[We take the negation of the theorem and suppose it to be true.]_ Suppose not.
That is, suppose that there is at least one integer $n$ that is both even and
odd. _[We must deduce a contradiction.]_ By definition of even, $n = 2a$ for
some integer $a$, and by definition of odd, $n = 2b + 1$ for some integer $b$.
Consequently,

$$ 2a = 2b + 1 \quad \text{ by equating the two expressions for } n $$

and so

$$
2a - 2b = 1 \\
2(a - b) = 1 \\
a j b = \frac{1}{2} \quad \text{ by algebra}
$$

Now since $a$ and $b$ are integers, the difference $a - b$ must also be an
integer. But $a - b = \dfrac{1}{2}$, and $\dfrac{1}{2}$ is not an integer. Thus
$a - b$ is an integer and $a - b$ is not an integer, which is a contradiction.
_[This contradiction shows that the supposition is false and, hence, that the
theorem is true.]_

---

Page 244

**Theorem 4.7.3**

The sum of any rational number and any irrational number is irrational.

**Proof:**

_[We take the negation of the theorem and suppose it to be true.]_ Suppose not.
That is, suppose there is a rational number $r$ and an irrational number $s$
such that $r + s$ is rational. _[We must deduce a contradiction.]_ By definition
of rational, $r = \dfrac{a}{b}$ and $r + s = \dfrac{c}{d}$ for some integers
$a$, $b$, $c$, and $d$ with $b \neq 0$ and $d \neq 0$. By substitution,

$$ \frac{a}{b} + s = \frac{c}{d} $$

and so,

$$ s = \frac{c}{d} - \frac{a}{b} \quad \text{ by subtracting } \frac{a}{b} \text{ from both sides} $$

$$ = \frac{bc - ad}{bd} $$

Now $bc - ad$ and $bd$ are both integers _[since $a$, $b$, $c$, and $d$ are
integers and since products and differences of integers are integers]_, and
$bd \neq 0$ _[by the zero product property.]_ Hence $s$ is a quotient of the two
integers $bc - ad$ and $bd$ with $bd \neq 0$. Thus, by definition of rational,
$s$ is rational, which contradicts the supposition that $s$ is irrational.
_[Hence the supposition is false and the theorem is true.]_

---

Page 245

**Method of Proof by Contraposition**

1. Express the statement to be proved in the form

$$ \forall x \text{ in } D, \text{ if } P(x) \text{ then } Q(x) $$

(This step may be done mentally.)

2. Rewrite this statement in the contrapositive form

$$ \forall x \text{ in } D, \text{ if } Q(x) \text{ is false then } P(x) \text{ is false} $$

(This step may be done mentally.)

3. Prove the contrapositive by a direct proof.

a. Suppose $x$ is a (particular but arbitrarily chosen) element of $D$ such that
$Q(x)$ is false.

b. Show that $P(x)$ is false.

---

Page 245

**Proposition 4.7.4**

For every integer $n$, if $n^2$ is even then $n$ is even.

**Proof (by contraposition):**

Suppose $n$ is any odd integer. _[We must show that $n^2$ is odd.]_ By
definition of odd, $n = 2k + 1$ for some integer $k$. By substitution and
algebra,

$$ n^2 =(2k + 1)^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1 $$

Now $2k^2 + 2k$ is an integer because products and sums of integers are
integers. So $n^2 = 2 \cdot (\text{an integer}) + 1$, and thus, by definition of
odd, $n^2$ is odd _[as was to be shown]._

---

Page 246

**Proposition 4.7.4**

For every integer $n$, if $n^2$ is even then $n$ is even.

**Proof (by contradiction):**

_[We take the negation of the theorem and suppose it to be true.]_ Suppose not.
That is, suppose there is an integer $n$ such that $n^2$ is even and $n$ is not
even. _[We must deduce a contradiction.]_ By the quotient-remainder theorem with
divisor equal to $2$, any integer is even or odd. Hence, since $n$ is not even
it is odd, and thus, by definition of odd, $n = 2k + 1$ for some integer $k$. By
substitution and algebra,

$$ n^2 = (2k + 1)^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1 $$

Now $2k^2 + 2k$ is an integer because products and sums of integers are
integers. So $n^2 = 2 \cdot (\text{an integer}) + 1$, and thus, by definition of
odd, $n^2$ is odd. Therefore, $n^2$ is both even and odd. This contradicts
Theorem 4.7.2, which states that no integer can be both even and odd. _[This
contradiction shows that the supposition is false and, hence, that the
proposition is true.]_

---

Page 252

**Theorem 4.8.1 Irrationality of $\sqrt{2}$**

$\sqrt{2}$ is irrational.

**Proof (by contradiction):**

_[We take the negation and suppose it to be true.]_ Suppose not. That is,
suppose $\sqrt{2}$ is rational. Then there are integers $m$ and $n$ with no
common factors such that

$$ \sqrt{2} = \frac{m}{n} $$

_[by dividing $m$ and $n$ by any common factors if necessary]._ _[We must derive
a contradiction.]_ Squaring both sides of equation (4.8.1) gives

$$ 2 = \frac{m^2}{n^2} $$

Or, equivalently,

$$ m^2 = 2n^2 $$

Note that equation (4.8.2) implies that $m^2$ is even (by definition of even).
It follows that $m$ is even (by Proposition 4.7.4). We file this fact away for
future reference and also deduce (by definition of even) that

$$ m = 2k \quad \text{ for some integer } k $$

Substituting equation (4.8.3) into equation (4.8.2), we see that

$$ m^2 = (2k)^2 = 4k^2 = 2n^2 $$

Dividing both sides of the right-most equation by $2$ gives

$$ n^2 = 2k^2 $$

Consequently, $n^2$ is even, and so $n$ is even (by Proposition 4.7.4). But we
also know that $m$ is even. _[This is the fact we filed away.]_ Hence both $m$
and $n$ have a common factor of $2$. But this contradicts the supposition that
$m$ and $n$ have no common factors. _[Hence the supposition is false and so the
theorem is true.]_

---

Page 253

**Proposition 4.8.2**

$1 + 3\sqrt{2}$ is irrational.

**Proof (by contradiction):**

Suppose not. Suppose $1 + 3\sqrt{2}$ is rational. _[We must derive a
contradiction.]_ Then by definition of rational,

$$ 1 + 3\sqrt{2} = \frac{a}{b} \quad \text{ for some integers } a \text{ and } b \text{ with } b \neq 0 $$

It follows that

$$ 3\sqrt{2} = \frac{a}{b} - 1 \quad \text{ by subtracting } 1 \text{ from both sides} $$

$$ = \frac{a}{b} - \frac{b}{b} \quad \text{ by substitution} $$

$$ = \frac{a - b}{b} $$

Hence

$$ \sqrt{2} = \frac{a - b}{3b} $$

But $a - b$ and $3b$ are integers (since $a$ and $b$ are integers and
differences and products of integers are integers), and $3b \neq 0$ by the zero
product property. Hence $\sqrt{2}$ is a quotient of the two integers $a - b$ and
$3b$ with $3b \neq 0$, and so $\sqrt{2}$ is rational (by definition of
rational). This contradicts the fact that $\sqrt{2}$ is irrational. _[The
contradiction shows that the supposition is false.]_ Hence $1 + 3\sqrt{2}$ is
irrational.

---

Page 254

**Proposition 4.8.3**

For any integer $a$ and any prime number $p$, if $p \mid a$ then
$p \cancel{\mid} (a + 1)$.

**Proof (by contradiction):**

Suppose not. That is, suppose there exists an integer $a$ and a prime number $p$
such that $p \mid a$ and $p \mid (a + 1)$. Then, by definition of divisibility,
there exists integers $r$ and $s$ such that $a = pr$ and $a + 1 = ps$. It
follows that

$$ 1 = (a + 1) - a = ps - pr = p(s - r) $$

and so (since $s - r$ is an integer) $p \mid 1$. But, by Theorem 4.4.2, the only
integer divisors of $1$ are $1$ and $-1$, and $p > 1$ because $p$ is prime. Thus
$p \leq 1$ and $p > 1$, which is a contradiction. _[Hence the supposition is
false, and the proposition is true.]_

---

Page 254

**Theorem 4.8.4 Infinitude of the Primes**

The set of prime numbers is infinite.

**Proof (by contradiction):**

Suppose not. That is, suppose the set of prime numbers is finite. _[WE must
deduce a contradiction.]_ Then some prime number $p$ is the largest of all the
prime numbers, and hence we can list the prime numbers in ascending order.

$$ 2, 3< 5, 7, 11, \dots, p $$

Let $N$ be the product of all the prime numbers plus $1$:

$$ N = (2 \cdot 3 \cdot 5 \cdot 7 \cdot 11 \dots p) + 1 $$

Then $N > 1$, and so, by Theorem 4.4.4, $N$ is divisible by some prime number
$q$. Because $q$ is prime, $q$ must equal one of the prime numbers
$2, 3, 5< 7, 11, \dots, p$. Thus, by definition of divisibility, $q$ divides
$2 \cdot 3 \cdot 5 \cdot 7 \cdot 11 \dots p$, and so, by Proposition 4.8.3, $q$
does not divide $(2 \cdot 3 \cdot 5 \cdot 7 \cdot 11 \dots p) + 1$, which equals
$N$. Hence $N$ is divisible by $q$ and $N$ is not divisible by $q$, and we have
reached a contradiction. _[Therefore, the supposition is false and the theorem
is true.]_

---

Page 258

**Definition**

The total degree of a graph is the sum of the degrees of all the vertices of the
graph.

---

Page 259

**Theorem 4.9.1 The Handshake Theorem**

If $G$ is any graph, then the sum of the degrees of all the vertices of $G$
equals twice the number of edges of $G$. Specifically, if the vertices of $G$
are $v_1, v^2, \dots v_n$, where $n$ is a nonnegative integer, then

$$ \text{the total degree of } G = \text{deg}(v_1) + \text{deg}(v_2) + \dots + \text{deg}(v_n) $$

$$ = 2 \cdot (\text{the number of edges of } G) $$

**Proof:**

Let $G$ be a particular but arbitrarily chosen graph, and suppose that $G$ has
$n$ vertices $v_1, v_2, \dots v_n$ and $m$ edges, where $n$ is a positive
integer and $m$ is a nonnegative integer. We claim that each edge of $G$
contributes $2$ to the total degree of $G$. For suppose $e$ is an arbitrarily
chosen edge with endpoints $v_i$ and $v_j$. This edge contributes $1$ to the
degree of $v_i$ and $1$ to the degree of $v_j$. As shown below, this is true
even if $i = j$, because an edge that is a loop is counted twice in computing
the degree of the vertex on which it is incident.

(see Page 259)

Therefore, $e$ contributes $2$ to the total degree of $G$. Since $e$ was
arbitrarily chosen, this shows that _each_ edge of $G$ contributes $2$ to the
total degree of $G$. Thus

$$ \text{the total degree of } G = 2 \cdot (\text{the number of edges of } G) $$

---

Page 259

**Corollary 4.9.2**

The total degree of a graph is even.

**Proof:** By Theorem 4.9.1 the total degree of $G$ equals $2$ times the number
of edges of $G$, which is an integer, and so the total degree of $G$ is even.

---

Page 260

**Proposition 4.9.3**

In any graph there is an even number of vertices of odd degree.

**Proof:** Suppose $G$ is any graph, and suppose $G$ has $n$ vertices of odd
degree and $m$ vertices of even degree, where $n$ is a positive integer and $m$
is a nonnegative integer. _[We must show that $n$ is even.]_ Let $E$ be the sum
of the degrees of all the vertices of even degree, $O$ the sum of the degrees of
all the vertices of odd degree, and $T$ the total degree of $G$. If
$u_1, u_2, \dots, u_m$ are the vertices of even degree and
$v_1, v_2, \dots, v_n$ are the vertices of odd degree, then

$$ E = \text{deg}(u_1) + \text{deg}(u_2) + \dots + \text{deg}(u_m), $$

$$ O = \text{deg}(v_1) + \text{deg}(v_2) + \dots + \text{deg}(v_m), \text{ and} $$

$$ T = \text{deg}(u_1) + \dots + \text{deg}(u_m) + \text{deg}(v_1) + \dots + \text{deg}(v_n) = E + 0 $$

Now $T$, the total degree of $G$, is an even integer by Corollary 4.9.2. Also
$E$ is even since either $E$ is zero, which is even, or $E$ is a sum of even
numbers. Now since

$$ T = E + O $$

then

$$ O = T - E $$

Hence $O$ is a difference of two even integers, and so $O$ is even.

By assumption, $\text{deg}(v_i)$ is odd for every integer $i = 1, 2, \dots, n$.
Thus $O$, an even integer, is a sum of the $n$ odd integers
$\text{deg}(v_1), \text{deg}(v_2), \dots, \text{deg}(v_n)$. But if a sum of $n$
odd integers is even, then $n$ is even. Therefore, $n$ is even _[as was to be
shown]._

---

Page 262

**Definition and Notation**

A **simple graph** is a graph that does not have any loops or parallel edges. In
a simple graph, an edge with endpoints $v$ and $w$ is denoted $\{v, w\}$.

---

Page 263

**Definition**

Let $n$ be a positive integer. A **complete graph on $n$ vertices**, denoted
$K_n$, is a simple graph with $n$ vertices and exactly one edge connecting each
pair of distinct vertices.

---

Page 264

**Definition**

Let $m$ and $n$ be positive integers. A **complete bipartite graph on $(m, n)$
vertices**, denoted $K_{m, n}$, is a simple graph whose vertices are divided
into two distinct subsets, $V$ with $m$ vertices and $W$ with $n$ vertices, in
such a way that

1. every vertex of $K_{m, n}$ belongs to one of $V$ or $W$, but no vertex
   belongs to both $V$ and $W$;

2. there is exactly one edge from each vertex of $V$ to each vertex of $W$;

3. there is no edge from any one vertex of $V$ to any other vertex of $V$;

4. there is no edge from any one vertex of $W$ to any other vertex of $W$.

---

Page 268

Execution of an **if-then-else** statement occurs as follows:

1. The _condition_ is evaluated by substituting the current values of all
   algorithm variables appearing in it and evaluating the truth or falsity of
   the resulting statement.

2. If _condition_ is true, then $s_1$ is executed and execution moves to the
   next algorithm statement following the **if-then-else** statement.

3. If _condition_ is false, then $s_2$ is executed and execution moves to the
   next algorithm statement following the **if-then-else** statement.

---

Page 269

Execution of a **while** loop occurs as follows:

1. The _condition_ is evaluated by substituting the current values of all the
   algorithm variables and evaluating the truth or falsity of the resulting
   statement.

2. If _condition_ is true, all the statements in the body of the loop are
   executed in order. Then execution moves back to the beginning of the loop and
   the process repeats.

3. If _condition_ is false, execution passes to the next algorithm statement
   following the loop.

---

Page 270

A **for-next** loop is executed as follows:

1. The **for-next** loop _variable_ is set equal to the value of _initial
   expression_.

2. A check is made to determine whether the value of _variable_ is less than or
   equal to the value of _final expression_.

3. If the value of _variable_ is less than or equal to the value of _final
   expression_, then the statements in the body of the loop are executed in
   order, _variable_ is increased by $1$, and execution returns back to step 2.

4. If the value of _variable_ is greater than the value of _final expression_,
   then execution passes to the next algorithm statement following the loop.

---

Page 272

**Algorithm 4.10.1 Division Algorithm**

_[Given a nonnegative integer $a$ and a positive integer $d$, the aim of the
algorithm is to find integers $q$ and $r$ that satisfy the conditions
$a = dq + r$ and $0 \leq r < d$. This is done by subtracting $d$ repeatedly from
$a$ until the result is less than $d$ but is still nonnegative._

$$ 0 \leq a - d - d - d - \dots - d = a - dq < d$$

_The total number of $d$'s that are subtracted is the quotient $q$. The quantity
$a - dq$ equals the remainder $r$.]_

**Input:** _$a$ [a nonnegative integer], $d$ [a positive integer]_

**Algorithm Body:**

$$ r:= a, q := 0 $$

_[Repeatedly subtract $d$ from $r$ until a number less than $d$ is obtained. Add
$1$ to $q$ each time $d$ is subtracted.]_

$\text{\textbf{while}} (r \geq d)\\ \ \ \ \ r := r- d\\ \ \ \ \ q:= q + 1\\ \text{\textbf{end while}}$

_[After execution of the $\text{\textbf{while}}$ loop, $a = dq + r$.]_

**Output:** $q$, $r$ _[nonnegative integers]_

---

Page 273

**Definition**

Let $a$ and $b$ be integers that are not both zero. The **greatest common
divisor** of $a$ and $b$, denoted $\text{\textbf{gcd}}(a, b)$, is that integer
$d$ with the following properties:

1. $d$ is a common divisor of both $a$ and $b$. In other words,

$$ d \mid a \quad \text{ and } \quad d \mid b $$

2. For every integer $c$, if $c$ is a common divisor of both $a$ and $b$, then
   $c$ is less than or equal to $d$. In other words,

$$ \text{for every integer } c, \text{ if } c \mid a \text{ and } c \mid b \text{ then } c \leq d$$

---

Page 274

**Lemma 4.10.1**

If $r$ is a positive integer, then $\text{gcd}(r, 0) = r$.

**Proof:** Suppose $r$ is a positive integer. _[We must show that the greatest
common divisor of both $r$ and $0$ is $r$.]_ Certainly, $r$ is a common divisor
of both $r$ and $0$ because $r$ divides itself and also $r$ divides $0$ (since
every positive integer divides $0$). Also no integer larger than $r$ can be a
common divisor of $r$ and $0$ (since no integer larger than $r$ can divide $r$).
Hence $r$ is the greatest common divisor of $r$ and $0$.

---

Page 274

**Lemma 4.10.2**

If $a$ and $b$ are any integers not both zero, and if $q$ and $r$ are any
integers such that

$$ a = bq + r $$

then

$$ \text{gcd}(a, b) = \text{gcd}(b, r) $$

**Proof:** _[The proof is divided into two sections: (1) proof that
$\text{gcd}(a, b) \leq \text{gcd}(b, r)$, and (2) proof that
$\text{gcd}(b, r) \leq \text{gcd}(a, b)$. Since each $\text{gcd}$ is less than
or equal to the other, the two must be equal.]_

1. $\text{\textbf{gcd}}(a, b) \leq \text{\textbf{gcd}}(b, r)$:

a. _[We will first show that any common divisor of $a$ and $b$ is also a common
divisor of $b$ and $r$.]_

Let $a$ and $b$ be integers, not both zero, and let $c$ be a common divisor of
$a$ and $b$. Then $c \mid a$ and $c \mid b$, and so, by definition of
divisibility, $a = nc$ and $b = mc$, for some integers $n$ and $m$. Substitute
into the equation

$$ a = bq + r $$

to obtain

$$ nc = (mc)q + r $$

Then solve for $r$:

$$ r = nc - (mc)q = (n - mq)c $$

Now $n - mq$ is an integer, and so, by definition of divisibility, $c \mid r$.
Because we already know that $c \mid b$, we can conclude that $c$ is a common
divisor of $b$ and $r$ _[as was to be shown]_.

b. _[Next we show that $\text{gcd}(a, b) \leq \text{gcd}(b, r)$.]_

Now the greatest common divisor of $a$ and $b$ defined because $a$ and $b$ are
not both zero. Also, by part (a), every common divisor of $a$ and $b$ is a
common divisor of $b$ and $r$, and so the greatest common divisor of $a$ and $b$
is a common divisor of $b$ and $r$. But then $\text{gcd}(a, b)$ (being one of
the common divisors of $b$ and $r$) is less than or equal to the greatest common
divisor of $b$ and $r$:

$$ \text{gcd}(a, b) \leq \text{gcd}(b, r) $$

2. $\text{\textbf{gcd}}(b, r) \leq \text{\textbf{gcd}}(a, b)$:

The second part of the proof is very similar to the first part. It is left as an
exercise.

---

Page 275

**Euclidean Algorithm Description**

1. Let $A$ and $B$ be integers with $A > B \geq 0$.

2. To find the greatest common divisor of $A$ and $B$, first check whether
   $B = 0$. If it is, then $\text{gcd}(A, B) = A$ by Lemma 4.10.1. If it isn't,
   then $B > 0$ and the quotient-remainder theorem can be used to divide $A$ by
   $B$ to obtain a quotient $q$ and a remainder $r$:

$$ A = Bq + r \quad \text{ where } \quad 0 \leq r < B $$

By Lemma 4.10.2, $\text{gcd}(A, B) = \text{gcd}(B, r)$. Thus the problem of
finding the greatest common divisor of $A$ and $B$ is reduced to the problem of
finding the greatest common divisor of $B$ and $r$.

_[What makes this information useful is the fact that the larger number of the
pair $(B, r)$ is smaller than the larger number of the pair $(A, B)$. The reason
is that the value of $r$ found by the quotient-remainder theorem satisfies_

$$ 0 \leq r < B $$

_And, since by assumption $B < A$, we have that_

$$ 0 \leq r < B < A $$

_]_.

3. Now just repeat the process, starting again at (2), but use $B$ instead of
   $A$ and $r$ instead of $B$. The repetitions are guaranteed to terminate
   eventually with $r = 0$ because each new remainder is less than the preceding
   one and all are nonnegative.

---

Page 277

**Algorithm 4.10.2 Euclidean Algorithm**

_[Given two integers $A$ and $B$ with $A > B \geq 0$, this algorithm computes
$\text{gcd}(A, B)$. It is based on two facts:_

1. $\text{gcd}(a, b) = \text{gcd}(b, r)$ _if $a$, $b$, $q$, and $r$ are integers
   with $b = b \cdot q + r$ and $0 \leq r < b$._

2. $\text{gcd}(a, 0) = a$._]_

**Input:** $A, B$ _[integers with $A > B \geq 0$]_

**Algorithm Body:**

$a := A, b := B, r:= B$

_[If $b \neq 0$, compute $a \mod b$, the remainder of the integer division of
$a$ by $b$, and set $r$ equal to this value. Then repeat the process using $b$
in place of $a$ and $r$ in place of $b$.]_

$\text{\textbf{while }} (b \neq 0)\\ \ \ \ \ r := a \mod b$

_[The value of $a \mod b$ can be obtained by calling the division algorithm.]_

$\ \ \ \ a := b\\ \ \ \ \ b := r\\ \text{\textbf{end while}}$

_[After execution of the $\text{\textbf{while}}$ loop, $\text{gcd}(A, B) = a$.]_

$\text{gcd} := a$

**Output:** $\text{gcd}$ _[a positive integer]_
