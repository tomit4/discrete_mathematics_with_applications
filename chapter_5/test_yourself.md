**Test Yourself**

Page 296

1. The notation $\sum_{k = m}^{n}{a_k}$ is read "_____."

The summation from $k$ equals $m$ to $n$ of $a$ sub $k$.

2. The expanded form of $\sum_{k = m}^{n}{a_k}$ is _____.

$$ a_m + a_{m + 1} + a_{m + 2} + \dots + a_n $$

3. The value of $a_1 + a_2 + a_3 + \dots + a_n$ when $n = 2$ is "_____."

$$ a_1 + a_2 $$

4. The notation $\prod_{k = m}^{n}{a_k}$ is read "_____."

The product from $k$ equals $m$ to $n$ of $a$ sub $k$.

5. If $n$ is a positive integer, then $n! =$ _____.

$$ n \cdot (n - 1) \dots \cdot 3 \cdot 2 \cdot 1 $$

6. $\sum_{k = m}^{n}{a_k} + c\sum_{k = m}^{n}{b_k} =$ _____.

$$ \sum_{k = m}^{n}{a_k + cb_k} $$

7. $\left(\prod_{k = m}^{n}{a_k}\right)\left(\prod_{k = m}^{n}{b_k}\right) =$
   _____.

$$ \prod_{k = m}^{n}{a_kb_k} $$

---

**Test Yourself**

Page 309

1. Mathematical induction is a method for proving that a property defined for
   integers $n$ is true for all values of $n$ that are _____.

greater than or equal to some initial value.

2. Let $P(n)$ be a property defined for integers $n$ and consider constructing a
   proof by mathematical induction for the statement "P(n) is true for all
   $n \geq a$."

a. In the basis step one must show _____.

that $P(a)$ is true.

b. In the inductive step one supposes that _____ for a particular but
arbitrarily chosen value of an integer $k \geq a$. This supposition is called
the _____. One then has to show that _____.

$P(k)$ is true; inductive hypothesis; $P(k + 1)$ is true.

---

**Test Yourself**

Page 320

1. Mathematical induction differs from the kind of induction used in the natural
   sciences because it is actually a form of _____ reasoning.

deductive

2. Mathematical induction can be used to _____ conjectures that have been made
   using inductive reasoning.

prove

---

**Test Yourself**

Page 333

1. In a proof by strong mathematical induction the basis step may require
   checking a property $P(n)$ for more _____ value of $n$.

than one

2. Suppose that in the basis step for a proof by strong mathematical induction
   the property $P(n)$ was checked for every integer $n$ from $a$ through $b$.
   Then in the inductive step one assumes that for any integer $k \geq b$, the
   property $P(n)$ is true for all values of $i$ from _____ through _____ and
   one shows that _____ is true.

$a$; $k$; $P(k + 1)$

3. According to the well-ordering principle for the integers, if a set $S$ of
   integers contains at least _____ and if there is some integer that is less
   than or equal to every _____, then _____.

one integer; integer in $S$; $S$ contains a least element.

---

**Test Yourself**

Page 346

1. A pre-condition for an algorithm is _____ and a post-condition for an
   algorithm is _____.

a predicate that describes the initial state of the input variables of the
algorithm; a predicate that describes the final state of the output variables
for the algorithm

2. A loop is defined as correct with respect to its pre- and post-conditions if,
   and only if, whenever the algorithm variables satisfy the pre-condition for
   the loop and the loop terminates after a finite number of steps, then _____.

the algorithm variables satisfy the post-condition for the loop

3. For each iteration of a loop, if a loop invariant is true before iteration of
   the loop, then _____.

it is true after iteration of the loop

4. Given a **while** loop with guard $G$ and a predicate $I(n)$ if the following
   four properties are true, then the loop is correct with respect to its pre-
   and post-conditions:

(a) The pre-condition for the loop implies that _____ before the first iteration
of the loop.

$I(0)$ is true

(b) For every integer $k \geq 0$, if the guard $G$ and the predicate $I(k)$ are
both true before an iteration of the loop, then _____.

$I(k + 1)$ is true after the iteration of the loop

\(c\) After a finite number of iterations of the loop, _____.

the guard $G$ becomes false

(d) If $N$ is the least number of iterations after which $G$ is false and $I(N)$
is true, then the values of the algorithm variables will be as specified _____.

in the post-condition of the loop.

---

**Test Yourself**

Page 359

1. A recursive definition for a sequence consists of a _____ and _____.

recurrence relation; initial conditions

2. A recurrence relation is an equation that defines each later term of a
   sequence by reference to _____ in the sequence.

earlier terms

3. Initial conditions for a recursive definition of a sequence consist of one or
   more of the _____ of the sequence.

values of the first few terms

4. To solve a problem recursively means to divide the problem into smaller
   subproblems of the same type as the initial problem, to suppose _____, and to
   figure out how to use the supposition to _____.

that the smaller subproblems have already been solved; solve the initial problem

5. A crucial step for solving a problem recursively is to define a _____ in
   terms of which the recurrence relation and initial conditions can be
   specified.

sequence

---

Page 372

**Test Yourself**

1. To use iteration to find an explicit formula for a recursively defined
   sequence, start with the _____ and use successive substitution into the _____
   to look for a numerical pattern.

initial conditions; recurrence relation

2. At every step of the iteration process, it is important to eliminate _____.

parentheses

3. If a single number, say $a$, is added to itself $k$ times in one of the steps
   of the iteration, replace the sum by the expression _____.

$k \cdot a$

4. If a single number, say $a$, is multiplied by itself $k$ times in one of the
   steps of the iteration, replace the product by the expression _____.

$a^k$

5. A general arithmetic sequence $a_0, a_1, a_2, \dots$ with initial value $a_0$
   and fixed constant summand $d$ satisfies the recurrence relation _____ and
   has the explicit formula _____.

$a_k = a_{k - 1} + d$; $a_n = a_0 + dn$

6. A general geometric sequence $a_0, a_1, a_2, \dots$ with initial value $a_0$
   and fixed constant multiplier $r$ satisfies the recurrence relation _____ and
   has the explicit formula _____.

$a_k = ra_{k - 1}$; $a_n = r^na_0$

7. When an explicit formula for a recursively defined sequence has been obtained
   by iteration, its correctness can be checked by _____.

mathematical induction

---

Page 385

**Test Yourself**

1. A second-order linear homogeneous recurrence relation with constant
   coefficients is a recurrence relation of the form _____ for every integer
   $k \geq$ _____, where _____.

$a_k = Aa_{k - 1} + Ba_{k - }$; 2; $A$ and $B$ are fixed real numbers with
$B \neq 0$.

2. Given a recurrence relation of the form $a_k = Aa_{k - 1} + Ba_{k - 2}$ for
   every integer $k \geq 2$, the characteristic equation of the relation is
   _____.

$t^2 - At - B = 0$

3. If a sequence $a_1, a_2, a_3, \dots$ is defined by a second-order linear
   homogeneous recurrence relation with constant coefficients and the
   characteristic equation for the relation has two distinct roots $r$ and $s$
   (which could be complex numbers), then the sequence is given by an explicit
   formula of the form _____.

$a_n = Cr_n + Ds_n$ for every integer $n \geq 0$ where $C$ and $D$ are real or
complex numbers.

4. If a sequence $a_1, a_2, a_3, \dots$ is defined by a second-order linear
   homogeneous recurrence relation with constant coefficients and the
   characteristic equation for the relation has only a single root $r$, then the
   sequence is given by an explicit formula of the form _____.

$a_n = Cr^n + Dnr^n$ where $C$ and $D$ are real numbers.
