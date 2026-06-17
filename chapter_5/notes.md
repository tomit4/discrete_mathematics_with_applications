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
