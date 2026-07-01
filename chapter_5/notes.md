Page 284

**Definition**

If $m$ and $n$ are integers and $m \leq n$, the symbol $\sum_{k=m}^{n}{a_k}$,
read the **summation from $k$ equals $m$ to $n$ of $a$-sub-$k$**, is the sum of
all the terms $a_m, a_{m + 1}, a_{m + 2}, \dots, a_n$. We say that
$a_m + a_{m + 1} + a_{m + 2} + \dots + a_n$ is the **expanded form** of the sum,
and we write

$$ \sum_{k=m}^{n}{a_k} = a_m + a_{m + 1} + a_{m + 2} + \dots + a_n $$

We call $k$ the **index** of the summation, $m$ the **lower limit** of the
summation, and $n$ the **upper limit** of the summation.

---

Page 287

**Definition**

If $m$ and $n$ are integers and $m \leq n$, the symbol $\prod_{k = m}^{n}{a_k}$
read the **product from $k$ equals $m$ to $n$ of $a$-sub-$k$**, is the product
of all the terms $a_m, a_{m + 1}, a_{m + 2}, \dots, a_n$.

We write

$$ \prod_{k = m}^{n}{a_k} = a_m \cdot a_{m + 1} \cdot a_{m + 1} \dots a_n $$

---

Page 288

**Theorem 5.1.1**

If $a_m, a_{m + 1}, a_{m + 1}, \dots$ and $b_m, b_{m + 1}, b_{m + 1}, \dots$ are
sequences of real numbers and $c$ is any real number, then the following
equations hold for any integer $n \geq m$:

1. $\sum_{k = m}^{n}{a_k} + \sum_{k = m}^{n}{b_k} = \sum_{k = m}^{n}{(a_k + b_k)}$

2. $c \cdot \sum_{k = m}^{n}{a_k} = \sum_{k = m}^{n}{c \cdot a_k} \quad \text{generalized distributive law}$

3. $\left(\prod_{k = m}^{n}{a_k}\right) \cdot \left(\prod_{k = m}^{n}{b_k}\right) = \prod_{k = m}^{n}{(a_k \cdot b_k)}$

---

Page 291

**Definition**

For each positive integer $n$, the quantity **$n$ factorial** denoted $n!$, is
defined to be the product of all the integers from $1$ to $n$:

$$ n! = n \cdot (n - 1) \dots 3 \cdot 2 \cdot 1 $$

**Zero factorial**, denoted $0!$, is defined to be $1$:

$$ 0! = 1 $$

---

Page 292

**Definition**

Let $n$ and $r$ be integers with $0 \leq r \leq n$. The symbol

$$ \binom{n}{r} $$

is read "**$n$ choose $r$**" and represents the number of subsets of size $r$
that can be chosen from a set with $n$ elements.

---

Page 292

**Formula for Computing $\dbinom{n}{r}$**

For all integers $n$ and $r$ with $0 \leq r \leq n$,

$$ \binom{n}{r} = \frac{n!}{r!(n - r)!} $$

---

Page 295

**Algorithm 5.1.1 Decimal to Binary Conversion Using Repeated Division by $2$**

_[In Algorithm 5.1.1 the input is a nonnegative integer $a$. The aim of the
algorithm is to produce a sequence of binary digits $r[0], r[1], r[2], \dots
r[k] so that the binary representation of $n$ is_

$$ \left(r[k]r[k - 1] \dots r[2]r[1]r[0]\right)_2 $$

_That is,_

$$ a = 2^k \cdot r[k] + 2^{k - 1} \cdot r[k - 1] + \dots + 2^3 \cdot r[2] + 2^1 \cdot r[1] + 2^0 \cdot r[0] $$

_.]_

**Input:** $a$ _[a nonegative integer]_

**Algorithm Body:**

$q := a, i := 0$

_[Repeatedly perform the integer division of $q$ by $2$ until $q$ becomes $0$.
Store successive remainders in a one-dimensional array
$r[0], r[1], r[2], \dots r[k]$. Even if the initial-value of $q$ equals $0$, the
loop should execute one time (so that $r[0]$ is computed). Thus the guard
condition for the **while** loop is $i = 0$ or $q \neq 0$.]_

$\text{\textbf{while }}(i = 0 \text{ or } q \neq 0)\\ \ \ r[i] := q \mod 2\\ \ \ q := q \text{ div } 2\\ \ \ \text{[r[i] and q can be obtained by calling the division algorithm.]}\\ \ \ i := i + 1\\ \text{\textbf{end while}}$

_[After execution of this step, the values of $r[0], r[1], \dots, r[i - 1]$ are
all $0$'s and $1$'s, and
$a = \left(r[i - 1]r[i - 2] \dots r[2]r[1]r[0]\right)_2$.]_

**Output:** $r[0], r[1], r[2], \dots, r[i - 1]$ _[a sequence of integers]_

---

Page 300

**Principle of Mathematical Induction**

Let $P(n)$ be a property that is defined for integers $n$, and let $a$ be a
fixed integer. Suppose the following two statements are true:

1. $P(a)$ is true.

2. For every integer $k \geq a$, if $P(k)$ is true then $P(k + 1)$ is true.

Then the statement

$$ \text{for every integer } n \geq a, P(a) $$

is true.

---

Page 301

**Method of Proof by Mathematical Induction**

Consider the statement of the form, "For every integer $n \geq a$, a property
$P(n)$ is true." To prove such a statement, perform the following two steps:

**Step 1 (basis step):**

    Show that $P(a)$ is true.

**Step 2 (inductive step):**

Show that for every integer $k \geq a$, if $P(k)$ is true then $P(k + 1)$ is
true. To perform this step,

**suppose** that $P(k)$ is true, where $k$ is any particular but arbitrarily
chosen integer with $k \geq a$. _[This supposition is called the **inductive
hypothesis**.]_

Then **show** that $P(k + 1)$ is true.

---

Page 303

**Theorem 5.2.1 Sum of the First $n$ Integers**

For every integer $n \geq 1$,

$$ 1 + 2 + \dots + n = \frac{n(n + 1)}{2} $$

**Proof (by mathematical induction):**

Let the property $P(n)$ be the equation

$$ 1 + 2 + 3 + \dots + n = \frac{n(n + 1)}{2} $$

_Show that $P(1)$ is true:_

To establish $P(1)$, we must show that

$$ 1 = \frac{1(1 + 1)}{2} $$

But the left-hand side of this equation is $1$ and the right-hand side is

$$ \frac{1(1 + 1)}{2} = \frac{2}{2} = 1 $$

also. Hence $P(1)$ is true.

_Show that for every integer $k \geq 1$, if $P(k)$ is true then $P(k + 1)$ is
also true:_

_[Suppose that $P(k)$ is true for a particular but arbitrarily chosen integer
$k \geq 1$. That is:]_

Suppose that $k$ is any integer with $k \geq 1$ such that

$$ 1 + 2 + 3 + \dots + k = \frac{k(k + 1)}{2} $$

_[We must show that $P(k + 1)$ is true. That is:]_ We must show that

$$ 1 + 2 + 3 + \dots + (k + 1) = \frac{(k + 1)[(k + 1) + 1]}{2} $$

or, equivalently, that

$$ 1 + 2 + 3 + \dots + (k + 1) = \frac{(k + 1)(k + 2)}{2} $$

_[We will show that the left-hand side and the right-hand side of $P(k + 1)$ are
equal to the same quantity and thus are equal to each other.]_

The left-hand side of $P(k + 1)$ is

$$ 1 + 2 + 3 + \dots + (k + 1) $$

$$ = 1 + 2 + 3 + \dots + k + (k + 1) $$

$$ = \frac{k(k + 1)}{2} + (k + 1) $$

$$ = \frac{k(k + 1)}{2} + \frac{2(k + 1)}{2} $$

$$ = \frac{k^2 + k}{2} + \frac{2k + 2}{2} $$

$$ = \frac{k^2 + 3k + 2}{2} $$

And the right-hand side of $P(k + 1)$ is

$$ \frac{(k + 1)(k + 2)}{2} = \frac{k^2 + 3k + 2}{2} $$

Thus the two sides of $P(k + 1)$ are equal to the same quantity and so they are
equal to each other. Therefore, the equation $P(k + 1)$ is true _[as was to be
shown]_.

_[Since we have proved both the basis step and the inductive step, we conclude
that the theorem is true.]_

---

Page 304

**Definition**

If a sum with a variable number of terms is shown to equal an expression that
does not contain an ellipsis or a summation symbol, we say that the sum is
written **in closed form.**

---

Page 306

**Theorem 5.2.2 Sum of a Geometric Sequence**

For any real number $r$ except $1$, and any integer $n \geq 0$,

$$ \sum_{i = 0}^{n}{r^i} = \frac{r^{n + 1} - 1}{r - 1} $$

**Proof (by mathematical induction):**

Suppose $r$ is a particular but arbitrarily chosen real number that is not equal
to $1$, and let the property $P(n)$ be the equation

$$ \sum_{i = 0}^{n}{r^i} = \frac{r^{n + 1} - 1}{r - 1} $$

We must show that $P(n)$ is true for every integer $n \geq 0$. We do this by
mathematical induction on $n$.

_Show that $P(0)$ is true:_

To establish $P(0)$, we must show that

$$ \sum_{i = 0}^{0}{r^i} = \frac{r^{0 + 1} - 1}{r - 1} $$

The left-hand side of this equation is $r^0 = 1$ and the right-hand side is

$$ \frac{r^{0 + 1} - 1}{r - 1} = \frac{r - 1}{r - 1} = 1 $$

also because $r^1 = r$ and, since $r \neq 1$, $r - 1 \neq 0$. Hence $P(0)$ is
true.

_Show that for every integer $k \geq 0$, if $P(k)$ is true then $P(k + 1)$ is
also true:_

_[Suppose that $P(k)$ is true for a particular but arbitrarily chosen integer
$k \geq 0$. That is:]_

Let $k$ be any integer with $k \geq 0$, and suppose that

$$ \sum_{i = 0}^{k}{r^j} = \frac{r^{k + 1} - 1}{r - 1} $$

_[We must show that $P(k + 1)$ is true. That is:]_ We must show that

$$ \sum_{i = 0}^{k + 1}{r^j} = \frac{r^{(k + 1) + 1} - 1}{r - 1} $$

or, equivalently, that

$$ \sum_{i = 0}^{k + 1}{r^j} = \frac{r^{k + 2} - 1}{r - 1} $$

_[We will show that the left-hand side of $P(k + 1)$ equals the right-hand
side.]_

The left-hand side of $P(k + 1)$ is

$$ \sum_{i = 0}^{k + 1}{r^j} = \sum_{i = 0}^{k}{r^i + r^{k + 1}} $$

$$ = \frac{r^{k + 1} - 1}{r - 1} + r^{k + 1} $$

$$ = \frac{r^{k + 1} - 1}{r - 1} + \frac{r^{k + 1}(r - 1)}{r - 1} $$

$$ = \frac{(r^{k + 1} - 1) + r^{k + 1}(r - 1)}{r - 1} $$

$$ = \frac{r^{k + 1} - 1 + r^{k + 2} - r^{k + 1}}{r - 1} $$

$$ = \frac{r^{k + 2} - 1}{r - 1} $$

which is the right-hand side of $P(k + 1)$ _[as was to be shown]._

_[Since we have proved the basis step and the inductive step, we conclude that
the theorem is true.]_

---

Page 314

**Proposition 5.3.1**

For every integer $n \geq 8$, $n$¢ can be obtained using $3$¢ and $5$¢ coins.

**Proof (by mathematical induction):**

Let the property $P(n)$ be the sentence

$n$¢ can be obtained using $3$¢ and $5$¢ coins.

Show that $P(8)$ is true:

$P(8)$ is true because $8$¢ can be obtained using one $3$¢ coin and one $5$¢
coin.

_[Suppose that $P(k)$ is true for a particular but arbitrarily chosen integer
$k \geq 8$. That is:]_

Suppose that $k$ is any integer with $k \geq 8$ such that

$k$¢ can be obtained using $3$¢ and $5$¢ coins.

_[We must show that $P(k + 1)$ is true. That is:]_ We must show that

$(k + 1)$¢ can be obtained using $3$¢ and $5$¢ coins.

_Case 1 (There is a $5$¢ coin among those that used to make up the $k$¢.):_

In this case replace the $5$¢ coin by two $3$¢ coins; the result will be
$(k + 1)$¢.

_Case 2 (There is not a $5$¢ coin among those used to make up the $k$¢.):_

In this case, because $k \geq 8$, at least three $3$¢ coins must have been used.
So remove three $3$¢ coins and replace them by two $5$¢ coins; the result will
be $(k + 1)$¢.

Thus in either case $(k + 1)$¢ can be obtained using $3$¢ and $5$¢ coins _[as
was to be shown]._

_[Since we have proved the basis step and the inductive step, we conclude that
the proposition is true.]_

---

Page 315

**Proposition 5.3.2**

For each integer $n \geq 0$, $2^{2n} - 1$ is divisible by $3$.

**Proof (by mathematical induction):**

Let the property $P(n)$ be the sentence "$2^{2n} - 1$ is divisible by $3$."

$$ 2^{2n} - 1 \text{ is divisible by } 3 $$

_Show that $P(0)$ is true:_

To establish $P(0)$, we must show that

$$ 2^{2 \cdot 0} - 1 \text{ is divisible by 3.} $$

But

$$ 2^{2 \cdot 0} - 1 = 2^0 - 1 = 1 - 1 = 0 $$

and $0$ is divisible by $3$ because $0$ = 3 \cdot 0. Hence $P(0)$ is true.

_Show that for any integer $k \geq 0$, if $P(k)$ is true then $P(k + 1)$ is also
true:_

_[Suppose that $P(k)$ is true for a particular but arbitrarily chosen integer
$k \geq 0$. That is:]_

Let $k$ be any integer with $k \geq 0$, and suppose that

$$ 2^{2k} - 1 \text{ is divisible by } 3 $$

By definition of divisibility, this means that

$$ 2^{2k} - 1 = 3r \text{ for some integer } r $$

_[We must show that $P(k + 1)$ is true. That is:]_ We must show that

$$ 2^{2(k + 1)} - 1 \text{ is divisible by } 3 $$

Now

$$ 2^{2(k + 1)} - 1 = 2^{2k + 2} - 1 $$

$$ = 2^{2k} \cdot 2^2 - 1 $$

$$ = 2^{2k} \cdot 4 - 1 $$

$$ = 2^{2k}(3 + 1) - 1 $$

$$ = 2^{2k} \cdot 3 + (2^{2k} - 1) $$

$$ = 2^{2=} \cdot 3 + 3r $$

$$ = 3(2^{2k} + r) $$

But $2^{2k} + r$ is an integer because it is a sum of products of integers, and
so, by definition of divisibility, $2^{2(k + 1)} - 1$ is divisible by $3$ _[as
was to be shown]_.

_[Since we have proved the basis step and the inductive step, we conclude that
the proposition is true.]_

---

Page 317

**Proposition 5.3.3**

For every integer $n \geq 3$, $2n + 1 < 2^n$.

**Proof (by mathematical induction):**

Let the property $P(n)$ be the inequality

$$ 2n + 1 < 2^n $$

_Show that $P(3)$ is true:_

To establish $P(3)$, we must show that

$$ 2 \cdot 3 + 1 < 2^3 $$

Now

$$ 2 \cdot 3 + 1 = 7 \quad \text{ and } \quad 2^3 = 8 \quad \text{ and } \quad 7 < 8 $$

Hence $P(3)$ is true.

_Show that for every integer $k \geq 3$, if $P(k)$ is true then $P(k + 1)$ is
also true:_

_[Suppose that $P(k)$ is true for a particular but arbitrarily chosen integer
$k \geq 3$. That is:]_

Suppose that $k$ is any integer with $k \geq 3$ such that

$$ 2k + 1 < 2^k $$

_[We must show that $P(k + 1)$ is true. That is:]_

We must show that

$$ 2(k + 1) + 1 < 2^{(k + 1)} $$

Now

$$ 2(k + 1) + 1 = 2k + 1 + 2 $$

$$ < 2^k + 2 $$

$$ < 2^k + 2^k $$

$$ = 2 \cdot 2^k $$

$$ = 2^{k + 1} $$

Thus by transitivity of order $2(k + 1) + 1 < 2^{k + 1}$ _[as was to be shown]_.

_[Since we have proved the basis step and the inductive step, we conclude that
the proposition is true.]_

---

Page 319

**Theorem 5.3.4 Covering a Board with Trominoes**

For any integer $n \geq 1$, if one square is removed from a $2^n \times 2^n$
checkerboard, the remaining squares can be completely covered by L-shaped
trominoes.

The main insight leading to a proof of this theorem is the observation that
because $2^{k + 1} = 2 \cdot 2^k$, when a $2^{k + 1} \times 2^{k + 1}$ board is
split in half both vertically and horizontally, each half side will have length
$2^k$ and so each resulting quadrant will be a $2^k \times 2^k$ checkerboard.

**Proof (by mathematical induction):**

Let the property $P(n)$ be the sentence

If any square is removed from a $2^n \times 2^n$ checkerboard, then the
remaining squares can be completely covered by L-shaped trominoes.

_Show that $P(1)$ is true:_

A $2^1 \times 2^1$ checkerboard just consists of four squares. If one square is
removed, the remaining squares form an L, which can be covered by a single
L-shaped tromino, as illustrated in the figure to the left. Hence $P(1)$ is
true.

_Show that for every integer $k \geq 1$, if $P(k)$ is true then $P(k + 1)$ is
also true:_

_[Suppose that $P(k)$ is true for a particular but arbitrarily chosen integer
$k \geq 3$. That is:]_

Let $k$ be any integer such that $k \geq 1$, and suppose that

If any square is removed from a $2^k \times 2^k$ checkerboard, then the
remaining squares can be completely covered by L-shaped trominoes.

$P(k)$ is the inductive hypothesis.

_[We must show that $P(k + 1)$ is true. That is:]_

We must show that

If any square is removed from a $2^{k + 1} \times 2^{k + 1}$ checkerboard, then
the remaining squares can be completely covered by L-shaped trominoes.

Consider a $2^{2k + 1} \times 2^{k + 1}$ checkerboard with one square removed.
Divide it into four equal quadrants: Each will consist of a $2^k \times 2^k$
checkerboard. In one of the quadrants, one square will have been removed, and
so, by inductive hypothesis, all the remaining squares in this quadrant can be
completely covered by L-shaped trominoes.

The other three quadrants meet at the center of the checkerboard, and the center
of the checkerboard serves as a corner of a square from each of those quadrants.
An L-shaped tromino can, therefore, be placed on those three central squares.
This situation is illustrated in the figure to the left (see page 320).

By inductive hypothesis, the remaining squares in each of the three quadrants
can be completely covered by L-shaped trominoes. Thus every square in the
$2^{k + 1} \times 2^{k + 1}$ checkerboard except the one that was removed can be
completely covered by L-shaped trominoes _[as was to be shown]_.

---

Page 324

**Principle of Strong Mathematical Induction**

Let $P(n)$ be a property that is defined for integers $n$, and let $a$ and $b$
be fixed integers with $a \leq b$. Suppose the following two statements are
true:

1. $P(a), P(a + 1), \dots$, and $P(b)$ are all true. **(basis step)**

2. For every integer $k \geq b$, if $P(i)$ is true for each integer $i$ from $a$
   through $k$, then $P(k + 1)$ is true. **(inductive step)**

Then the statement

$$ \text{for every integer } n \geq a, P(n) $$

is true. (The supposition that $P(i)$ is true for each integer $i$ from $a$
through $k$ is called the **inductive hypothesis**. Another way to state the
inductive hypothesis is to say that $P(a), P(a + 1), \dots, P(k)$ are all true.)

---

Page 325

**Proof (by strong mathematical induction):**

Let the property $P(n)$ be the sentence

$n$ is divisible by a prime number.

_Show that $P(2)$ is true:_

To establish $P(2)$, we must show that

$2$ is divisible by a prime number.

But this is true because $2$ is divisible by $2$ and $2$ is a prime number.

_Show that for every integer $k \geq 2$, if $P(i)$ is true for each integer from
$2$ through $k$, then $P(k + 1)$ is also true:_

Let $k$ be any integer with $k \geq 2$ and suppose that

$i$ is divisible by a prime number for each integer $i$ from $2$ through $k$.

We must show that

$k + 1$ is divisible by a prime number.

_Case 1($k + 1$ is prime):_

In this case $k + 1$ is divisible by a prime number, namely, itself.

_Case 2($k + 1$ is not prime):_

In this case $k + 1 = ab$ where $a$ and $b$ are integers with $1 < a< k + 1$ and
$1 < b < k + 1$. Thus, in particular, $2 \leq a \leq k$, and so by inductive
hypothesis, $a$ is divisible by a prime number $p$. In addition because
$k + 1 = ab$, we have that $k + 1$ is divisible by $a$. Hence, since $k + 1$ is
divisible by $a$ and $a$ is divisible by $p$, by transitivity of divisibility,
$k + 1$ is divisible by the prime number $p$.

Therefore, regardless of whether $k + 1$ is prime or not, it is divisible by a
prime number. _[as was to be shown.]_

_[Since we have proved both the basis and the inductive step of the strong
mathematical induction, we conclude that the given statement is true.]_

---

Page 326

**Proof:**

Let $s_0, s_1, s_2, \dots$ be the sequence defined by specifying that
$s_0 = 0, s_1 = 4$, and $s_k = 6a_{k - 1} - 5a_{k - 2}$ for every integer
$k \geq 2$, and let the property $P(n)$ be the formula

$$ s_n = 5^n - 1 $$

We will use strong mathematical induction to prove that for every integer
$n \geq 0$, $P(n)$ is true.

_Show that $P(0)$ and $P(1)$ are true:_

To establish $P(0)$ and $P(1)$, we must show that

$$ s_0 = 5^0 - 1 \text{ and } s_1= 5^1 - 1 $$

But, by definition of $s_0, s_1, s_2, \dots$, we have that $s_0 = 0$ and
$s_1 = 4$. Since $5^0 - 1 = 1 - 1 = 0$ and $5^1 - 1 = 5 - 1 = 4$, the values of
$s_0$ and $s_1$ agree with the values given by the formula.

_Show that for every integer $k \geq 1$, if $P(i)$ is true for each integer $i$
from $0$ through $k$, then $P(k + 1)$ is also true:_

Let $k$ be any integer with $k \geq 1$ and suppose that

$$ s_i = 5^i - 1 \text{ for each integer } i \text{ with } 0 \leq i \leq k $$

We must show that

$$ s_{k + 1} = 5^{k + 1} - 1 $$

But since $k \geq 1$, we have that $k + 1 \geq 2$, and so

$$ s_{k + 1} = 6s_k - 5s_{k - 1} $$

$$ = 6(5^k - 1) - 5(5^{k - 1} - 1) $$

$$ = 6 \cdot 5^k - 6 - 5^k + 5 $$

$$ = (6 - 1)5^k - 1 $$

$$ = 5 \cdot 5^k - 1 $$

$$ = 5^{k + 1} - 1 $$

_[as was to be shown]._

_[Since we have proved both the basis and the inductive step of the strong
mathematical induction, we conclude that the given statement is true.]_

---

Page 328

**Convention**

Let us agree to say that a single number $x_1$ is a product with one factor and
can be computed with zero multiplications.

---

Page 329

**Proof (by strong mathematical induction):**

Let the property $P(n)$ be the sentence

If $x_1, x_2, \dots, x_n$ are $n$ numbers, then no matter how parentheses are
inserted into their product, the number of multiplications used to compute the
product is $n - 1$.

_Show that $P(1)$ is true:_

To establish $P(1)$, we must show that

The number 9f multiplications needed to compute the product of $x_1$ is $1 - 1$.

This is true because, by convention, $x_1$ is a product that can be computed
with $0$ multiplications and $0 = 1 - 1$.

_Show that for every integer $k \geq 1$, if $P(i)$ is true for each integer $i$
from $1$ through $k$, then $P(k + 1)$ is also true:_

Let $k$ be any integer with $k \geq 1$ and suppose that

For each integer $i$ from $1$ through $k$, if $x_1, x_2, \dots, x_i$ are
numbers, then no matter how parentheses are inserted into their product, the
number of multiplications used to compute the product is $i - 1$.

We must show that

If $x_1, x_2, \dots, x_{k + 1}$ are $k + 1$ numbers, then no matter how
parentheses are inserted into their product, the number of multiplications used
to compute the product is $(k + 1) - 1 = k$.

Consider a product of $k +  1$ factors: $x_1, x_2, \dots, x_{k + 1}$. When
parentheses are inserted in order to compute the product, some multiplication is
the final one and each of the two factors making up the final multiplication is
a product of fewer than $k + 1$ factors. Let $L$ be the product of the left-hand
factors and $R$ be the product of the right-hand factors, and suppose that $L$
is composed of $l$ factors and $R$ is composed of $r$ factors. Then
$l + r = k + 1$, the total number of factors in the product, and

$$ 1 \leq l \leq k \text{ and } 1 \leq r \leq k $$

By inductive hypothesis, evaluating $L$ takes $l - 1$ multiplications and
evaluating $R$ takes $r - 1$ multiplications. Because one final multiplication
is needed to evaluate $L \cdot  R$, the number of multiplications needed to
evaluate the product of all $k + 1$ factors is

$$ (l - 1) + (r - 1) + 1 = (l + r) - 1 = (k + 1) - 1 = k $$

_[as was to be shown]._

_[Since we have proved both the basis and the inductive step of the strong
mathematical induction, we conclude that the given statement is true.]_

---

Page 330

**Theorem 5.4.1 Existence and Uniqueness of Binary Integer Representations**

Given any positive integer $n$, $n$ has a unique representation in the form

$$ n = c_r \cdot 2^r + c_{r - 1} \cdot 2^{r - 1} + \dots + c_2 \cdot 2^2 + c_1 \cdot 2 + c_0 $$

where $r$ is a nonnegative integer, $c_r = 1$, and $c_j = 1$ or $0$ for each
$j = 0, 1, 2, \dots, r - 1$.

**Proof:**

We give separate proofs by strong mathematical induction to show first the
existence and second the uniqueness of the binary representation.

_Existence (proof by strong mathematical induction):_

Let the property $P(n)$ be the equation

$$ n = c_r \cdot 2^r + c_{r - 1} \cdot 2^{r - 1} + \dots + c_2 \cdot 2^2 + c_1 \cdot 2 + c_0 $$

where $r$ is a nonnegative integer, $c_r = 1$, and $c_j = 1$ or $0$ for each
$j = 0, 1, 2, \dots, r - 1$.

_Show that $P(1)$ is true:_

Let $r = 0$ and $c_0 = 1$. Then $1 = c_r \cdot 2^r$, and so $n = 1$ can be
written in the required form.

_Show that for every integer $k \geq 1$, if $P(i)$ is true for each integer $i$
from $1$ through $k$, then $P(k + 1)$ is also true:_

Let $k$ be an integer with $k \geq 1$. Suppose that for each integer $i$ from
$1$ through $k$,

$$  = c_r \cdot 2^r + c_{r - 1} \cdot 2^{r - 1} + \dots + c_2 \cdot 2^2 + c_1 \cdot 2 + c_0 $$

where $r$ is a nonnegative integer, $c_r = 1$, and $c_j = 1$ or $0$ for each
$j = 0, 1, 2, \dots, r - 1$ . We must show that $k + 1$ can be written as a sum
of powers of $2$ in the required form.

_Case 1 ($k + 1$ is even):_

In this case $\dfrac{(k + 1)}{2}$ is an integer, and by inductive hypothesis,
since $1 \leq \dfrac{(k + 1)}{2} \leq k$, then

$$ \frac{k + 1}{2} = c_r \cdot 2^r + c_{r - 1} \cdot 2^{r - 1} + \dots + c_2 \cdot 2^2 + c_1 \cdot 2 + c_0 $$

where $r$ is a nonnegative integer, $c_r = 1$, and $c_j = 1$ or $0$ for each
$j = 0, 1, 2, \dots, r - 1$. Multiplying both sides of the equation by $2$ gives

$$ k + 1= c_r \cdot 2^{r + 1} + c_{r - 1} \cdot 2^r + \dots + c_2 \cdot 2^3 + c_1 \cdot 2^2 + c_0 \cdot 2 $$

which is the sum of powers of $2$ of the required form.

_Case 2 ($k + 1$ is odd):_

In this case $\dfrac{k}{2}$ is an integer, and by inductive hypothesis, since
$1 \leq \dfrac{k}{2} = k$, then

$$ \frac{k}{2} = c_r \cdot 2^r + c_{r - 1} \cdot 2^{r - 1} + \dots + c_2 \cdot 2^2 + c_1 \cdot 2 + c_0 $$

where $r$ is a nonnegative integer, $c_r = 1$, and $c_j = 1$ or $0$ for each
$j = 0, 1, 2, \dots r - 1$. Multiplying both sides of the equation by $2$ and
adding $1$ gives

$$ k + 1 = c_r \cdot 2^{r + 1} + c_{r - 1} \cdot 2^r + \dots + c_2 \cdot 2^3 + c_1 \cdot 2^2 + c_0 \cdot 2 + 1 $$

which is also a sum of powers of $2$ of the required form.

The preceding arguments show that regardless 9f whether $k + 1$ is even or odd,
$k + 1$ has a representation of the required form. _[Or, in other words,
$P(k + 1)$ is true as was to be shown.]_

_[Since we have proved the basis step and the inductive step of the strong
mathematical induction, the existence half of the theorem is true.]_

_Uniqueness:_

To prove uniqueness, suppose that there is an integer $n$ with two different
representations as a sum of nonnegative integer powers of $2$. Equating the two
representations and canceling all identical terms gives

$$ 2^r + c{r - 1} \cdot 2^{4 - 1} + \dots + c_1 \cdot 2 + c_0 = 2^s + d_{s - 1} \cdot 2^{s - 1} + \dots + d_1 \cdot 2 + d_0 $$

where $r$ and $s$ are nonnegative integers and each $c_i$ and each $d_i$ equal
$0$ or $1$. Without loss of generality, we may assume that $r < s$. Now by the
formula for the sum of a geomatric sequence (Theorem 5.2.2) and because $r < s$
(which implies that $r + 1 \leq s$),

$$ 2^r + c_{r - 1} \cdot 2^{r - 1} + \dots + c_1 \cdot 2 + \c_0 \leq 2^r + 2^{r - 1} + \dots + 2 + 1 = 2^{r + 1} - 1 < 2^s $$

Thus

$$ 2^r + c_{r - 1} \cdot 2^{r - 1} + \dots + c_1 \cdot 2 + c_0 < 2^s + d_{s - 1} \cdot 2^{s - 1} + \dots + d_1 \cdot 2 + d_0 $$

which contradicts equation (5.4.1). Hence the supposition is false, so any
integer $n$ has only one representation as a sum of nonnegative integer powers
9f $2$.

---

Page 331

**Well-Ordering Principle for the Integers**

Let $S$ be a set of integers containing one or more integers all of which are
greater than some fixed integer. Then $S$ has a least element.

---

Page 332

**Quotient-Remainder Theorem (Existence Part)**

**Proof:**

Let $s$ be the set of all nonnegative integers of the form

$$ n - dk $$

where $k$ is an integer. This set has at least one element. _[For if $n$ is
nonnegative, then_

$$ n - 0 \cdot d = n \geq 0 $$

_and so $n - 0 \cdot d$ is in $S$. And if $n$ is negative then_

$$ n - nd = \underbrace{n}_{< 0}\underbrace{(1 - d)}_{\leq 0 \text{ since } d \text{ is a positive integer}} \geq 0 $$

_and so $n - nd$ is in $S$.]_

It follows by the well-ordering principle for the integers that $S$ contains a
least element $r$. Then, for some specific integer value of $k$, say $q$,

$$ n - dq = r $$

_[because every integer in $S$ can be written in this form]._ Adding $dq$ to
both sides gives

$$ n = dq + r $$

Furthermore, $r < d$. _[For suppose $r \geq d$. Then_

$$ n - d(q + 1) = n - dq - d = r - d \geq 0 $$

_and so $n - d(q + 1)$ would be a nonnegative integer in $S$ that would be
smaller than $r$. But $r$ is the smallest integer in $S$. This contradiction
shows that the supposition $r \geq d$ must be false.]_

The preceding arguments prove that there exists integers $r$ and $q$ for which

$$ n = dq + r \text{ and } 0 \leq r < d $$

_[as was to be shown.]_

---

Page 339

**Definition**

A loop is defined as **correct with respect to its pre- and post-conditions**
if, and only if, whenever the algorithm variables satisfy the pre-condition for
the loop and the loop terminates after a finite number of steps, the algorithm
variables satisfy the post-condition for the loop.

---

Page 340

**Theorem 5.5.1 Loop Invariant Theorem**

Let a **while** loop with guard $G$ be given, together with pre- and
post-conditions that are predicates in the algorithm variables. Also let a
predicate $I(n)$, called the **loop invariant**, be given. If the following four
properties are true, then the loop is correct with respect to its pre- and
post-conditions.

**I. Basis Property:** The pre-condition for the loop implies that $I(0)$ is
true before the first iteration of the loop.

**II. Inductive Property:** For every integer $k \geq 0$, if the guard $G$ and
the loop invariant $I(k)$ are both true before an iteration of the loop, then
$I(k + 1)$ is true after an iteration of the loop.

**III. Eventual Falsity of Guard:** After a finite number of iterations of the
loop, the guard $G$ becomes false.

**IV. Correctness of the Post-Condition:** If $N$ is the least number of
iterations after which $G$ is false and $I(N)$ is true, then the values of the
algorithm variables will be as specified in the post-condition of the loop.

**Proof:**

The loop invariant theorem follows easily from the principle of mathematical
induction. Assume that $I(n)$ is a predicate that satisfies properties I-IV of
the loop invariant theorem. _[We will prove that the loop is correct with
respect to its pre- and post-conditions.]_ Properties I and II are the basis and
inductive steps needed to prove the truth of the following statement:

For every integer $n \geq 0$, if the **while** loop iterates $n$ times, then
$I(n)$ is true.

Thus, by the principle of mathematical induction, since both I and II are true,
statement (5.5.1) is also true.

Property III says that the guard $G$ eventually becomes false. At that point the
loop will have been iterated some number, say $N$, of times. Since $I(n)$ is
true after the $n$th iteration for every $n \geq 0$, then $I(n)$ is true after
the $N$th iteration. That is, after the $N$th iteration the guard is false and
$I(N)$ is true. But this is the hypothesis of property IV, which is an if-then
statement. Since statement IV is true (by assumption) and its hypothesis is true
(by the argument just given), it follows (by modus ponens) that its conclusion
is also true. That is, the values of all algorithm variables after execution of
the loop are as specified in the post-condition for the loop.

---

Page 348

**Definition**

A **recurrence relation** for a sequence $a_0, a_1, a_2, \dots$ is a formula
that relates each term $a_k$ to certain of its predecessors
$a_{k - 1}, a_{k - 2}, \dots, a_{k - i}$, where $i$ is an integer with
$k - i \geq 0$. If $i$ is a fixed integer, the **initial conditions** for such a
recurrence relation specify the values of $a_0, a_1, a_2, \dots, a_{i - 1}$. If
$i$ depends on $k$, the initial conditions specify the values of
$a_0, a_1, \dots, a_m$, where $m$ is an integer with $m \geq 0$.

---

Page 358

**Definition**

Given numbers $a_1, a_2, \dots a_n$, where $n$ is a positive integer, the
**summation from $i = 1$ to $n$ of the $a_i$**, denoted $\sum_{i = 1}^{n}{a_i}$,
is defined as follows:

$$ \sum_{i = 1}^{1}{a_i} = a_1 \quad \text{ and } \quad \sum_{i = 1}^{n}{a_i} = \left(\sum_{i = 1}^{n - 1}{a_i}\right) + a_n, \quad \text{ if } n > 1 $$

The **product from $i = 1$ to $n$ of the $a_i$**, denoted
$\prod_{i = 1}^{n}{a_i}$, is defined by

$$ \prod_{i = 1}^{1}{a_i} = a_1 \quad \text{ and } \quad \prod_{i = 1}^{n}{a_i} = \left(\prod_{i = 1}^{n - 1}{a_i}\right) \cdot a_n, \quad \text{ if } \quad n > 1 $$
