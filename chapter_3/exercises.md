**Exercise Set 3.1**

Page 142

1. A menagerie consists of seven brown dogs, two black dogs, six gray cats, ten
   black cats, five blue birds, six yellow birds, and one black bird. Determine
   which of the following statements are true and which are false.

a. There is an animal in the menagerie that is red.

False

b. Every animal in the menagerie is a bird or a mammal.

True

c. Every animal in the menagerie is brown or gray or black.

False

d. There is an animal in the menagerie that is neither a cat nor a dog.

True

e. No animal in the menagerie is blue.

False

f. There are in the menagerie a dog, a cat, and a bird that all have the same
color.

True

2. Indicate which of the following statements are true and which are false.
   Justify your answers as best you can.

a. Every integer is a real number.

True, because the set of all integers, $\mathbb{Z}$ is a subset of the set of
all real numbers, $\mathbb{R}$. $\mathbb{Z} \in \mathbb{R}$.

b. $0$ is a positive real number.

False, $0$ is neither positive nor negative.

c. For every real number $r$, $-r$ is a negative real number.

False, if $r$ is negative, then $-r$ is positive.

d. Every real number is an integer.

False, $\dfrac{1}{2}$ is not an integer, but is a real number.

3. Let $R(m, n)$ be the predicate "If $m$ is a factor of $n^2$ then $m$ is a
   factor of $n$," with domain for both $m$ and $n$ being $\mathbb{Z}$ the set
   of integers.

a. Explain why $R(m, n)$ is false if $m = 25$ and $n = 10$.

The statement "If 25 is a factor of 100" is a true hypothesis, but the
conclusion "then 25 is a factor of 10" is false because 10 is not a product of
25 times any integer. Thus the hypothesis is true, but the conclusion is false,
making this predicate a false statement.

b. Give values different from those in part (a) for which $R(m, n)$ is false.

$m = 9$, $n = 3$

c. Explain why $R(m, n)$ is true if $m = 5$ and $n = 10$.

Because 5 is a factor of 100, which is the hypothesis, and the conclusion is
that 5 is a factor of 10, which is also true. Thus the hypothesis and conclusion
are both true, so the statement as a whole is true.

d. Give values different from those in part \(c\) for which $R(m, n)$ is true.

$m = 4$, $n = 8$

4. Let $Q(x, y)$ be the predicate "If $x < y$ then $x^2 < y^2$" with the domain
   for both $x$ and $y$ being $\mathbb{R}$ the set of real numbers.

a. Explain why $Q(x, y)$ is false if $x = -2$ and $y = 1$.

The hypothesis becomes "If $-2 < 1$", which is true, the conclusion becomes
"then $4 < 1$", which is a false conclusion. Thus the hypothesis is true, but
the conclusion is false, making $Q(-2, 1)$ a false statement.

b. Give values different from those in part (a) for which $Q(x, y)$ is false.

$x = -5$, $y = 2$

c. Explain why $Q(x, y)$ is true if $x = 3$ and $y = 8$.

The hypothesis becomes "If $3 < 8$", which is true, and the conclusion becomes
"then $9 < 64$", which is also true. This shows that the hypothesis and
conclusion true, making $Q(3, 8)$ a true statement.

d. Give values different from those in part \(c\) for which $Q(x, y)$ is true.

$x = 3$, $y = 4$

5. Find the truth set of each predicate.

a. Predicate: $\dfrac{6}{d}$ is an integer, domain: $\mathbb{Z}$

$$ \{-6, -3, -2, -1, 1, 2, 3, 6\} $$

b. Predicate: $\dfrac{6}{d}$ is an integer, domain: $\mathbb{Z}^+$

$$ \{1, 2, 3, 6\} $$

c. Predicate: $1 \leq x^2 \leq 4$, domain: $\mathbb{R}$

$$ \{x \in \mathbb{R} | -1 \leq x \leq -2 \text{ or } 1 \leq x \leq 2\} $$

d. Predicate: $1 \leq x^2 \leq 4$, domain: $\mathbb{Z}$

$$ \{-2, -1, 1, 2\} $$

6. Let $B(x)$ be "$-10 < x < 10$." Find the truth set of $B(x)$ for each of the
   following domains.

a. $\mathbb{Z}$

$$ \{-9, -8, -7, -6, -5, -4, -3, -2, -1, 1, 2, 3, 4, 5, 6, 7, 8, 9\} $$

b. $\mathbb{Z}^+$

$$ \{1, 2, 3, 4, 5, 6, 7, 8, 9\} $$

c. The set of all even integers

$$ \{-8, -6, -4, -2, 2, 4, 6, 8\} $$

7. Let $S$ be the set of all strings of length 3 consisting of _a_'s, _b_'s, and
   _c_'s. List all the strings in $S$ that satisfy the following conditions:

   1. Every string in $S$ begins with _b_.

   baa, bab, bac, bba, bbb, bbc, bca, bcb, bcc

   2. No string in $S$ has more than one _c_.

   aaa, aab, aac, aba, abb, abc, aca, acb, baa, bab, bac, bba, bbb, bbc, bca,
   bcb, caa, cab, cba, cbb

8. Let $T$ be the set of all strings of length 3 consisting of 0's and 1's. List
   all the strings in $T$ that satisfy the following conditions:

   1. For every string $s$ in $T$, the second character of $s$ is 1 or the first
      two characters of $s$ are the same.

   000, 001, 010, 110, 111

   2. No string in $T$ has all three characters the same.

   001, 010, 100, 101, 110

Find counterexamples to show that the statements in 9-12 are false.

9. $\forall x \in \mathbb{R}, x \geq \dfrac{1}{x}$.

$x = \dfrac{1}{2}$, so $\dfrac{1}{2} \geq \dfrac{1}{\dfrac{1}{2}}$ is false as:

$$ \frac{1}{2} < 2 $$

10. $\forall a \in \mathbb{Z}, \dfrac{(a - 1)}{a}$ is not an integer.

$$ a = -1 $$

$$ \frac{((-1) - 1)}{-1} = \frac{-2}{-1} = 2 $$

Since $2 \in \mathbb{Z}$, this statement is false.

11. $\forall$ positive integers $m$ and $n$, $m \cdot n \geq m + n$.

$m = 1$, $n = 2$

$$ 1 \cdot 2 = 2 \geq 3 = 1 + 2 $$

But $2$ is not greater than or equal to $3$, so this statement is false.

12. $\forall$ real numbers $x$ and $y$, $\sqrt{x + y} = \sqrt{x} + \sqrt{y}$.

$x = 4$, $y = 9$

$$ \sqrt{4 + 9} = \sqrt{13} \approx 3.605551275 $$

$$ \sqrt{4} + \sqrt{9} = 2 + 3 = 5 $$

Since $\sqrt{13} \neq 5$, this statement is false.

13. Consider the following statement:

$\forall$ basketball player $x$, $x$ is tall.

Which of the following are equivalent ways of expressing the statement?

a. Every basketball player is tall.

Yes.

b. Among all the basketball players, some are tall.

No.

c. Some of all the tall people are basketball players.

No.

d. Anyone who is tall is a basketball player.

No.

e. All people who are basketball players are tall.

Yes.

f. Anyone who is a basketball player is a tall person.

Yes.

14. Consider the following statement:

$\exists x \in \mathbb{R}$ such that $x^2 = 2$.

Which of the following are equivalent ways of expressing this statement

a. The square of each real number is 2.

No.

b. Some real numbers have square 2.

Yes.

c. The number $x$ has square 2, for some real number $x$.

Yes.

d. If $x$ is a real number, then $x^2 = 2$.

No.

e. Some real number has square 2.

Yes.

f. There is at least one real number whose square is 2.

Yes.

15. Rewrite the following statements informally in at least two different ways
    without using variables or quantifiers.

a. $\forall$ rectangle $x$, $x$ is a quadrilateral.

If a shape is a rectangle, then the shape is a quadrilateral.

For any given rectangle, that rectangle is a quadrilateral.

b. $\exists$ a set $A$ such that $A$ has 16 subsets.

There must be a set that has 16 subsets.

At least one set has 16 subsets.

16. Rewrite each of the following statements in the form "$\forall$ ______ $x$,
    ______."

a. All dinosaurs are extinct.

$\forall$ dinosaurs, $x$, $x$ is extinct.

b. Every real number is positive, negative, or zero.

$\forall$ real numbers $x$, $x$ is positive, negative, or zero.

c. No irrational numbers are integers.

$\forall$ irrational numbers $x$, $x$ is not an integer.

d. No logicians are lazy.

$\forall$ logicians $x$, $x$ is not lazy.

e. The number 2,147,581,953 is not equal to the square of any integer.

$\forall$ integer $x$, $x^2$ does not equal 2,147,581,953.

f. The number $-1$ is not equal to the square of any real number.

$\forall$ real numbers $x$, $x^2$ does not equal -1.

17. Rewrite each of the following in the form "$\exists$ ______ $x$ such that
    ______."

a. Some exercises have answers.

$\exists$ some exercise, $x$, such that $x$ has an answer.

b. Some real numbers are rational.

$\exists$ some real number $x$, such that $x$ is rational.

18. Let $D$ be the set of all students at your school, and let $M(s)$ be "$s$ is
    a math major," let $C(s)$ be "$s$ is a computer science student," and let
    $E(s)$ be "$s$ is an engineering student." Express each of the following
    statements using quantifiers, variables, and the predicates $M(s)$, $C(s)$,
    and $E(s)$.

a. There is an engineering student who is a math major.

$\exists s$ such that $E(s)$ and $M(s)$.

b. Every computer science student is an engineering student.

$\forall s \in D, C(s) \to E(s)$

c. No computer science students are engineering students.

$\forall s \in D, C(s) \to \neg E(s)$

d. Some computer science students are also math majors.

$\exists s$ such that $C(s) \wedge M(s)$

e. Some computer science students are engineering students and some are not.

$\exists s$ such that $C(s) \wedge E(s)$ or $\exists$ such that
$C(s) \wedge \neg E(s)$

19. Consider the following statement:

$\forall$ integer $n$, if $n^2$ is even then $n$ is even.

Which of the following are equivalent ways of expressing this statement?

a. All integers have even squares and are even.

No

b. Given any integer whose square is even, that integer is itself even.

Yes

c. For all integers, there are some whose square is even.

No

d. Any integer with an even square is even.

Yes

e. If the square of an integer is even, then that integer is even.

Yes

f. All even integers have even squares.

No

20. Rewrite the following statement informally in at least two different ways
    without using variables of the symbol $\forall$ or the words "for all."

$\forall$ real numbers $x$, if $x$ is positive then the square root of $x$ is
positive.

If a number is a positive real number, then the square root of that number is
positive.

Any positive real number's square root is positive.

21. Rewrite the following statements so that the quantifier trails the rest of
    the sentence.

a. For any graph $G$, the total degree of $G$ is even.

The total degree of $G$ is even, for any graph $G$.

b. For any isosceles triangle $T$, the base angles of $T$ are equal.

The base angles of $T$ are equal, for any isosceles triangle $T$.

c. There exists a prime number $p$ such that $p$ is even.

$p$ is even for some prime number $p$.

d. There exists a continuous function $f$ such that $f$ is not differentiable.

$f$ is not differentiable for some continuous function $f$.

22. Rewrite each of the following statements in the form "$\forall$ ______ $x$,
    if ______ then ______."

a. All Java programs have at least 5 lines.

$\forall$ programs $x$, if $x$ is a Java program, then it has at least 5 lines.

b. Any valid argument with true premises has a true conclusion.

$\forall$ arguments $x$, if $x$ is a valid argument with a true premise, then it
has a true conclusion.

23. Rewrite each of the following statements in the two forms "$\forall x$, if
    ______ then ______" and "$\forall x$, ______" (without an if-then).

a. All equilateral triangles are isosceles.

$\forall x$, if $x$ is equilateral, then $x$ is isosceles.

$\forall$ equilateral triangles $x$, $x$ is isosceles.

b. Every computer science student needs to take data structures.

$\forall x$ if $x$ is a computer science student, then $x$ needs to take data
structures.

$\forall$ computer science students $x$, $x$ needs to take data structures.

24. Rewrite the following statements in the two forms "$\exists$ ______ $x$ such
    that ______" and "$\exists x$ such that ______ and ______."

a. Some hatters are mad.

$\exists$ a hatter $x$ such that $x$ is mad.

$\exists x$ such that $x$ is a hatter and $x$ is mad.

b. Some questions are easy.

$\exists$ a question $x$ such that $x$ is easy.

$\exists x$ such that $x$ is a question and $x$ is easy.

25. The statement "The square of any rational number is rational" can be
    rewritten formally as "For all rational numbers $x$, $x^2$ is rational" or
    as "For all $x$, if $x$ is rational then $x^2$ is rational." Rewrite each of
    the following statements in the two forms "$\forall$ ______ $x$, ______" and
    "$\forall x$, if ______, then ______" or in the two forms "$\forall$ ______
    $x$ and $y$, ______" and "$\forall x$ and $y$, if ______, then ______."

a. The reciprocal of any nonzero function is a fraction.

$\forall$ nonzero function $x$, the reciprocal of $x$ is a fraction.

$\forall x$, if $x$ is a nonzero fraction, then the reciprocal of $x$ is a
fraction.

b. The derivative of any polynomial function is a polynomial function.

$\forall$ derivatives of any polynomial function $x$, $x$ is a polynomial
function.

$\forall x$, if $x$ is a derivative of any polynomial function, then $x$ is a
polynomial function.

c. The sum of the angles of any triangle is $180\degree$.

$\forall$ triangles $x$, the sum of the angles of $x$ is $180\degree$.

$\forall x$ if $x$ is a triangle, then the sum of the angles of $x$ is
$180\degree$.

d. The negative of any irrational number is irrational.

$\forall$ negative of any irrational number, $x$, $x$ is irrational.

$\forall x$ if $x$ is a negative of any irrational number, then $x$ is
irrational.

e. The sum of any two even integers is even.

$\forall$ even integers $x$, and $y$, the sum of $x$ and $y$ is even.

$\forall x, y$ if $x$ and $y$ are even integers, then the sum of $x$ and $y$ is
even.

f. The product of any two fractions is a fraction.

$\forall$ fractions $x$ and $y$, the product of $x$ and $y$ is a fraction.

$\forall x, y$ if $x$ and $y$ are fractions, then the product of $x$ and $y$ is
a fraction.

26. Consider the statement "All integers are rational numbers but some rational
    numbers are not integers."

a. Write this statement in the form "$\forall x$, if ______ then ______, but
$\exists$ ______ $x$, such that ______."

$\forall x$, if $x$ is an integer, then $x$ is a rational number, but $\exists$
a rational number $x$, such that $x$ is not an integer.

b. Let $\text{Ratl}(x)$ be "$x$ is a rational number" and $\text{Int}(x)$ be
"$x$ is an integer." Write the given statement formally using only the symbols
$\text{Ratl}(x)$, $\text{Int}(x)$, $\forall$, $\exists$, $\wedge$, $\vee$,
$\neg$, and $\to$.

$$ \forall x (\text{Int}(x) \to \text{Ratl}(x)) \wedge \exists x (\text{Ratl(x)} \wedge \neg \text{Int}(x))$$

27. Refer to the picture of Tarski's world given in Example 3.1.1.3. Let
    $\text{Above}(x, y)$ mean that $x$ is above $y$ (but possibly in a different
    column). Determine the truth or falsity of each of the following statements.
    Give reasons for your answers.

a. $\forall u, \text{Circle}(u) \to \text{Gray(u)}$.

This is false, b is a circle and is black.

b. $\forall u, \text{Gray}(u) \to \text{Circle}(u)$.

This is true, all gray shapes are circles.

c. $\exists y$ such that $\text{Square}(y) \wedge \text{Above}(y, d)$.

This is false, there is no shape that is a square and is above shape d.

d. $\exists z$ such that $\text{Triangle}(z) \wedge \text{Above}(f, z)$.

This is true, shape g is a triangle where shape f is above shape g.

In 28-30, rewrite each statement without using quantifiers or variables.
Indicate which are true and which are false, and justify your answers as best as
you can.

28. Let the domain of $x$ be the set $D$ of objects discussed in mathematics
    courses, and let $\text{Real}(x)$ be "$x$ is a real number," $\text{Pos}(x)$
    be "$x$ is a positive real number," $\text{Neg}(x)$ be "$x$ is a negative
    real number," and $\text{Int}(x)$ be "$x$ is an integer."

a. $\text{Pos}(0)$

"0 is a positive real number."

This is a false statement, as 0 is neither positive nor negative.

b. $\forall x, \text{Real}(x) \wedge \text{Neg}(x) \to \text{Pos}(-x)$

"For any number, if that number is both real and negative, then the negative of
that number is positive.""

This is true, if you take the negative of a negative of any real number, then it
is positive.

c. $\forall x, \text{Int}(x) \to \text{Real}(x)$

"For any number, if that number is an integer, then that number is a real
number."

This is true, the set of all integers is a subset of all real numbers.

d. $\exists x$ such that $\text{Real}(x) \wedge \neg \text{Int}(x)$

"There is at least one number that is both a real number and not an integer."

This is true, an example would be $\dfrac{1}{2}$, which is a real number but not
an integer.

29. Let the domain of $x$ be the set of geometric figures in the plane, and let
    $\text{Square}(x)$ be "$x$ is a square" and $\text{Rect}(x)$ be "$x$ is a
    rectangle."

a. $\exists x$ such that $\text{Rect}(x) \wedge \text{Square}(x)$

"There exists a shape that is both a rectangle and a square."

This is true since any shape that is a square is also a rectangle.

b. $\exists x$ such that $\text{Rect}(x) \wedge \neg \text{Square}(x)$

"There exists a shape that is both a rectangle and not a square."

This is true, as any shape that is a rectangle that has unequal length and width
is not a square.

c. $\forall x, \text{Square}(x) \to \text{Rect}(x)$

"For any shape, if that shape is a square, then that shape is a rectangle."

This is true, for all shapes, any shape that is a square, that shape is then a
rectangle.

30. Let the domain of $x$ be $\mathbb{Z}$, the set of integers, and let
    $\text{Odd}(x)$ be "$x$ is odd," $\text{Prime}(x)$ be "$x$ is prime," and
    $\text{Square}(x)$ be "$x$ is a perfect square." (An integer $n$ is said to
    be a **perfect square** if, and only if, it equals the square of some
    integer. For example, $25$ is a perfect square because $25 = 5^2$.)

a. $\exists x$ such that $\text{Prime}(x) \wedge \neg \text{Odd}(x)$

"There exists some number that is both prime and not odd."

This is true, for example $2$ is a prime number (cannot be divided except by 1
and itself), but $2$ is also not odd.

b. $\forall x, \text{Prime}(x) \to \neg \text{Square}(x)$

"For any number, if that number is prime, then that number is not a perfect
square."

This is true, since a prime number is only divisible by 1 and itself, it cannot
equal the square of some integer, since that square would also be the product of
two smaller positive integers.

c. $\exists x$ such that $\text{Odd}(x) \wedge \text{Square}(x)$

"There exists some number that is both odd and is a perfect square."

This is true, take $9$ as an example, $9$ is an odd number, but is also a
perfect square as $9 = 3^2$.

31. In any mathematics or computer science text other than this book, find an
    example of a statement that is universal but is implicitly quantified. Copy
    the statement as it appears and rewrite it making the quantification
    explicit. Give a complete citation for your example, including title,
    author, publisher, year, and page number.

Omitted.

32. Let $\mathbb{R}$ be the domain of the predicate variable $x$. Which of the
    following are true and which are false? Give counter examples for the
    statements that are false.

a. $x > 2 \Rightarrow x > 1$

This is true, for any real number that is greater than 2, that same real number
is greater than 1.

b. $x > 2 \Rightarrow x^2 > 4$

This is true, for any real number that is greater than 2, that same real number
squared is greater than 4.

c. $x^2 > 4 \Rightarrow x > 2$

This is false, as $x = -3$ would mean $(-3)^2 > 4$, which is true as that is
$9 > 4$, but then $(-3) > 2$ is false. Since the hypothesis is true, but the
conclusion is false for at least one example, this predicate is therefore false.

d. $x^2 > 4 \Leftrightarrow |x| > 2$

This is true. For all numbers $x$, if $x^2 > 4$, then $|x| > 2$ is true.

Additionally, for all numbers $x$, if $|x| > 2$, then $x^2 > 4$ is true.

Since both directions of this universal "if and only if" statement are true,
this is a true statement.

33. Let $\mathbb{R}$ be the domain of the predicate variables $a$, $b$, $c$, and
    $d$. Which of the following are true and which are false? Give
    counterexamples for the statements that are false.

a. $a > 0 \text{ and } b > 0 \Rightarrow ab > 0$

This is true. If both $a$ and $b$ are positive, then their product is also
positive.

b. $a < 0 \text{ and } b < 0 \Rightarrow ab < 0$

This is false, If both $a$ and $b$ are negative, then their product is positive,
not negative. Take $-1$ and $-2$ for example, whose product is $2$.

c. $ab = 0 \Rightarrow a = 0 \text{ or } b = 0$

This is true, for all real numbers $a$ and $b$, if their product, $ab$ is equal
to $0$, then either $a$ or $b$ must be $0$.

d. $a < b \text{ and } c < d \Rightarrow ac < bd$

This is false. Say $a = -1$, $b = 2$, $c =  -8$ and $d = 3$. This would make
$-1 < 2$ and $-8 < 3$, which is true, but then $(-1)(-8) < (2)(3)$ would be
$8 < 6$, which is false.
