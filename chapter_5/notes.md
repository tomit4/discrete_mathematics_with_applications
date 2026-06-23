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
