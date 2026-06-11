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
