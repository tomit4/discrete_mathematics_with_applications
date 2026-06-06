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

---

**Exercise Set 3.2**

Page 152

1. Which of the following is a negation for "All discrete mathematics students
   are athletic"? More than one answer may be correct.

a. There is a discrete mathematics student who is nonathletic.

Yes.

b. All discrete mathematics students are nonathletic.

No.

c. There is an athletic person who is not a discrete mathematics student.

No.

d. No discrete mathematics students are athletic.

No.

e. Some discrete mathematics students are nonathletic.

Yes.

f. No athletic people are discrete mathematics students.

No.

2. Which of the following is a negation for "All dogs are loyal"? More than one
   answer may be correct.

a. All dogs are disloyal.

No.

b. No dogs are loyal.

No.

c. Some dogs are disloyal.

Yes.

d. Some dogs are loyal.

No.

e. There is a disloyal animal that is not a dog.

No.

f. There is a dog that is disloyal.

Yes.

g. No animals that are not dogs are loyal.

No.

h. Some animals that are not dogs are loyal.

No.

3. Write the formal negation for each of the following statements.

a. $\forall$ string $s$, $s$ has at least one character.

$\exists$ a string $s$, such that $s$ does not have any characters.

b. $\forall$ computer $c$, $c$ has a CPU.

$\exists$ a computer $c$, such that $c$ does not have a CPU.

c. $\exists$ a movie $m$ such that $m$ is over 6 hours long.

$\forall$ movies $m$, $m$ is no longer than 6 hours long.

d. $\exists$ a band $b$ such that $b$ has won at least 10 Grammy awards.

$\forall$ bands $b$, $b$ has won at most 9 Grammy awards.

4. Write an informal negation for each of the following statements. Be careful
   to avoid negations that are ambiguous.

a. All dogs are friendly.

There is at least one dog that is not friendly.

b. All graphs are connected.

There is at least one graph that is not connected.

c. Some suspicions were substantiated.

All suspicions were unsubstantiated.

d. Some estimates are accurate.

No estimates are accurate.

5. Write a negation for each of the following statements.

a. Every valid argument has a true conclusion.

There exists at least one valid argument that has a false conclusion.

b. All real numbers are positive, negative, or zero.

There exists at least one real number that is neither positive, negative, nor
zero.

Write a negation for each statement in 6 and 7.

6.

a. Sets $A$ and $B$ do not have any points in common.

Sets $A$ and $B$ have at least one point in common.

b. Towns $P$ and $Q$ are not connected by any road on the map.

There exists at least one road on the map that connects towns $P$ and $Q$.

7.

a. This vertex is not connected to any other vertex in the graph.

All vertexes are connected to at least one other vertex in the graph.

b. This number is not related to any even number.

All numbers are related to at least one even number.

8. Consider the statement "There are no simple solutions to life's problems."
   Write an informal negation for the statement, and then write the statement
   formally using quantifiers and variables.

"There is at least one of life's problems for which there is a simple solution."

$\exists$ some life problem $x$, for which there is a simple solution.

Write a negation for each statement in 9 and 10.

9. $\forall$ real number $x$, if $x > 3$ then $x^2 > 9$.

$\exists$ a real number $x$, such that $x > 3$ and $x^2 \leq 9$.

10. $\forall$ computer program $P$, if $P$ compiles without error messages, then
    $P$ is correct.

$\exists$ a computer program $P$, such that $P$ compiles without error messages
and $P$ is incorrect.

In each of 11-14 determine whether the proposed negation is correct. If it is
not, write a correct negation.

11.

_Statement:_ The sum of any two irrational numbers is irrational.

_Proposed negation:_ The sum of any two irrational numbers is rational.

No.

_Corrected negation:_ There are at least two irrational numbers whose sum is
rational.

12.

_Statement:_ The product of any irrational number and any rational number is
irrational.

_Proposed negation:_ The product of any irrational number and any rational
number is rational.

No.

_Corrected negation:_ There is at least one irrational number and at least one
rational number whose product is rational.

13.

_Statement:_ For every integer $n$, if $n^2$ is even then $n$ is even.

_Proposed negation:_ For every integer $n$, if $n^2$ is even then $n$ is not
even.

No.

_Corrected negation:_ There exists an integer $n$ such that $n^2$ is even and
$n$ is not even.

14.

_Statement:_ For all real numbers $x_1$ and $x_2$, if $x_1^2 = x_2^2$ then
$x_1 = x_2$.

_Proposed negation:_ For all real numbers $x_1$ and $x_2$, if $x_1^2 = x_2^2$
then $x_1 \neq x_2$.

No.

_Corrected negation:_ There exists two real numbers $x_1$ and $x_2$ such that
$x_1^2 = x_2^2$ and $x_1 \neq x_2$.

15. Let $D = \{-48, -14, -8, 0, 1, 3, 16, 23, 26, 32, 36\}$. Determine which of
    the following statements are true and which are false. Provide
    counterexamples for the statements that are false.

a. $\forall x \in D, \text{ if } x \text{ is odd then } x > 0$.

True. All odd numbers in $D$ are positive.

b.
$\forall x \in D, \text{ if } x \text{ is less than } 0 \text{ then } x \text{ is even}$.

True. All negative numbers in $D$ are even.

c. $\forall x \in D, \text{ if } x \text{ is even then } x \leq 0$.

False. There are some numbers in $D$ that are even and greater than 0.

$$ \exists x \in D, x \text{ is even } \wedge x > 0 $$

The numbers 16, 26, 32, and 36 are counterexamples that show that this statement
is false.

d.
$\forall x \in D, \text{ if the ones digit of } x \text{ is } 2, \text{ then the tens digit is } 3 \text{ or } 4$.

This is true. There is only one number that satisfies the hypothesis "the ones
digit of $x$ is 2", which is 32. The conclusion is "the tens digit is 3 or 4",
and that is true of the number 32, so this is a true statement.

e.
$\forall x \in D, \text{ if the ones digit of } x \text{ is } 6, \text{ then the tens digit is } 1 \text{ or } 2$.

This is false. Consider the negation statement:

$$ \exists x \in D, \text{ such that the one's digit of } x \text{ is } 6 \wedge \text{ the tens digit of } x \text{ is not } 1 \text{ or } 2  $$

The number 36 satisfies the negation statement, and so therefore the given
statement is false.

In 16-23, write a negation for each statement.

16. $\forall$ real number $x$, if $x^2 \geq 1$ then $x > 0$.

$\exists$ a real number $x$, such that $x^2 \geq 1$ and $x \leq 0$.

17. $\forall$ integer $d$, if $\dfrac{6}{d}$ is an integer then $d = 3$.

$\exists$ an integer $d$ such that $\dfrac{6}{d}$ is an integer and $d \neq 3$.

18. $\forall x \in \mathbb{R}$, if $x(x + 1) > 0$ then $x > 0$ or $x < -1$.

$\exists x \in \mathbb{R}$ such that $x(x + 1) > 0$ and both $x \leq 0$ and
$x \geq -1$.

19. $\forall x \in \mathbb{Z}$, if $n$ is prime then $n$ is odd or $n = 2$.

$\exists x \in \mathbb{Z}$ such that $n$ is prime and both $n$ is even and
$n \neq 2$.

20. $\forall$ integers $a$, $b$, and $c$, if $a - b$ is even and $b - c$ is
    even, then $a - c$ is even.

$\exists$ integers $a$, $b$, and $c$ such that $a - b$ is even and $b - c$ is
even and $a - c$ is not even.

21. $\forall$ integer $n$, if $n$ is divisible by $6$, then $n$ is divisible by
    $2$ and $n$ is divisible by $3$.

$\exists$ an integer $n$ such that $n$ is divisible by $6$ and either $n$ is not
divisible by $2$ or $n$ is not divisible by $3$.

22. If the square of an integer is odd, then the integer is odd.

$\exists$ an integer with the property that the square of the integer is odd but
the integer itself is not odd.

23. If a function is differentiable then it is continuous.

$\exists$ a function that is differentiable but is not continuous.

24. Rewrite the statements in each pair in if-then form and indicate the logical
    relationship between them.

a.

All the children in Tom's family are female.

If the person is a child in Tom's family, then the person is female.

All the females in Tom's family are children.

If the person is a female in Tom's family, then the person is a child.

The second statement is the converse of the first.

b.

All the integers that are greater than 5 and end in 1, 3, 7, or 9 are prime.

If the integer is greater than 5 and ends in 1, 3, 7, or 9, then the integer is
prime.

All the integers that are greater than 5 and are prime end in 1, 3, 7, or 9.

If the integer is greater than 5 and is prime, then the integer ends in 1, 3, 7,
or 9.

The second statement is the converse of the first.

25. Each of the following statements is true. In each case write the converse
    statement, and give a counterexample showing that the converse is false.

a. If $n$ is any prime number that is greater than $2$, then $n + 1$ is even.

If $n + 1$ is even, then $n$ is any prime number that is greater than $2$.

Counterexample: Let $n = 15$, $n + 1 = 16$, which is not a prime number.

b. If $m$ is an odd integer, then $2m$ is even.

If $2m$ is even, then $m$ is an odd integer.

Counterexample: Let $m = 2$, $2(2) = 4$, and $4$ is not an odd integer.

c. If two circles intersect in exactly two points, then they do not have a
common center.

If two circles do not have a common center, then the two circles intersect in
exactly two points.

Counterexample: Consider two circles that simply do not touch or overlap at all,
both circles do not have a common center and they do not intersect at exactly
two points.

In 26-33, for each statement in the referenced exercise write the
contrapositive, converse, and inverse. Indicate as best as you can which of
these statements are true and which are false. Give a counterexample for each
that is false.

26. Exercise 16

Original Statement:

$\forall$ real number $x$, if $x^2 \geq 1$ then $x > 0$.

This is false. Consider $x = -2$, then the hypothesis $4 \geq 1$ is true, but
the conclusion $-2 > 0$ is false. Therefore this statement is false.

Contrapositive:

$\forall$ real number $x$, if $x \leq 0$ then $x^2 < 1$.

This is false. Consider $x = -2$, then the hypothesis $-2 \leq 0$ is true, but
the conclusion $4 < 1$ is false. Therefore this statement is false.

Converse:

$\forall$ real number $x$, if $x > 0$ then $x^2 \geq 1$.

This is false. Consider $x = \dfrac{1}{2}$, then the hypothesis
$\dfrac{1}{2} > 0$ is true, but the conclusion $\dfrac{1}{4} \geq 1$ is false.
Therefore this statement is false.

Inverse:

$\forall$ real number $x$, if $x^2 < 1$ then $x \leq 0$.

This is false. Consider $x = \dfrac{1}{2}$, then the hypothesis
$\dfrac{1}{4} < 1$ is true, but then the conclusion $\dfrac{1}{2} \leq 0$ is
false. Therefore this statement is false.

27. Exercise 17

Original Statement:

$\forall$ integer $d$, if $\dfrac{6}{d}$ is an integer then $d = 3$.

This is false, consider $d = 1$ (6 would also work). The hypothesis
$\dfrac{6}{1} = 6$ is an integer is true, but then the conclusion $1 = 3$ is
false. Therefore this statement is false.

Contrapositive:

$\forall$ integer $d$, if $d \neq 3$ then $\dfrac{6}{d}$ is not an integer.

This is false. Consider $d = 6$. The hypothesis $d \neq 6$ is true, but the
conclusion $\dfrac{6}{6} = 1$ is not an integer is not true. Therefore this
statement is false.

Converse:

$\forall$ integer $d$, if $d = 3$ then $\dfrac{6}{d}$ is an integer.

This is true, if $d = 3$, then $\dfrac{6}{3} = 2$ is an integer is true.
Therefore this is a true statement.

Inverse:

$\forall$ integer $d$, if $\dfrac{6}{d}$ is not an integer then $d \neq 3$.

This is true, if $\dfrac{6}{d}$ is not an integer, than $d$ cannot be $3$ as
then $\dfrac{6}{3} = 2$ which is an integer. Therefore $d \neq 3$ is a true
conclusion and this is a true statement.

28. Exercise 18

Original Statement:

$\forall x \in \mathbb{R}$, if $x(x + 1) > 0$ then $x > 0$ or $x < -1$.

This is true, the hypothesis can be true, and its conclusion cannot be false.

Contrapositive:

$\forall x \in \mathbb{R}$, if $x \leq 0$ and $x \geq -1$ then
$x(x + 1) \leq 0$.

This is true, $x$ must lie in between $0$ and $1$ or be $0$ or $1$, and that
will always cause $x(x + 1) \leq 0$ to be either negative or $0$. This is a true
statement.

Converse:

$\forall x \in \mathbb{R}$, if $x > 0$ or $x < -1$ then $x(x + 1) > 0$.

This is true, this essentially means that $x(x + 1)$ will always be positive, as
$x$ is either always positive, or $x$ is always negative, but the multiplication
in the conclusion causes $x(x + 1) > 0$ to always be true. This statement is
true.

Inverse:

$\forall x \in \mathbb{R}$, if $x(x + 1) \leq 0$ then $x \leq 0$ and
$x \geq -1$.

Yes this is true, if $x(x + 1)$ is either negative or $0$, then $x$ must be
between $0$ and $-1$ inclusive. This statement is true.

29. Exercise 19

Original Statement:

$\forall x \in \mathbb{Z}$, if $n$ is prime then $n$ is odd or $n = 2$.

This is a true statement, all prime numbers except for $2$ are odd.

Contrapositive:

$\forall x \in \mathbb{Z}$, if $n$ is not odd and $n \neq 2$ then $n$ is not
prime.

This is a true statement, if $n$ is even and not $2$, then $n$ is not a prime
number.

Converse:

$\forall x \in \mathbb{Z}$, if $n$ is odd or $n = 2$, then $n$ is prime.

This is false, consider $n = 9$, the hypothesis that $n$ is odd or $n = 2$ is
true, but the conclusion $n$ is prime is false as $9$ is divisible by $3$. This
is a false statement.

Inverse:

$\forall x \in \mathbb{Z}$, if $n$ is not prime then both $n$ is not odd and
$n \neq 2$.

This is false, consider $n = 9$, the hypothesis $n$ is not prime is true, but
the hypothesis $n$ is not odd and $n \neq 2$ is false as $9$ is an odd number.
This statement is false.

30. Exercise 20

Original Statement:

$\forall$ integers $a$, $b$, and $c$, if $a - b$ is even and $b - c$ is even,
then $a - c$ is even.

This statement is true, as an even difference between any two numbers means that
the two numbers themselves are even, so therefore $a$, $b$, and $c$ are even,
and $a - c$ is even. This statement is true.

Contrapositive:

$\forall$ integers $a$, $b$, and $c$, if $a - c$ is not even, then either
$a - b$ is not even or $b - c$ is not even.

This statement is true. An odd difference means that at least one of the two
integers is odd, but necessarily both, so there for if $a - c$ is odd, then
either $a$ or $c$ is odd (but not both). This means that the conclusion is true
because it allows for either $a - b$ or $b - c$ to be odd, which must be true if
either $a$ or $c$ must be odd. This statement is true.

Converse:

$\forall$ integers $a$, $b$, and $c$, if $a - c$ is even, then $a - b$ is even
and $b - c$ is even.

This is false, consider $a = 13$, $b = 10$, and $c = 11$. This means the
hypothesis $a - c = 13 - 11 = 2$ is even is true, but then the conclusion
$a - b = 13 - 10 = 3$ is even and $10 - 11 = -1$ is even is false. This
statement is false.

Inverse:

$\forall$ integers $a$, $b$, and $c$, if $a - b$ is not even or $b - c$ is not
even, then $a - c$ is not even.

This is false, consider $a = 13$, $b = 10$, and $c = 11$. This means the
hypothesis $a - b = 13 - 10 = 3$ is not even or $b - c = 10 - 11 = -1$ is not
even is true, but then the conclusion $13 - 11 = 2$ is not even is false. This
statement is false.

31. Exercise 21

Original Statement:

$\forall$ integer $n$, if $n$ is divisible by $6$, then $n$ is divisible by $2$
and $n$ is divisible by $3$.

This is true, any integer divisible by a non-prime number is divisible by those
integer's prime factors.

Contrapositive:

$\forall$ integer $n$, if $n$ is not divisible by $2$ or $n$ is not divisible by
$3$, then $n$ is not divisible by $6$.

This is true. If $n$ is not divisible by the prime numbers $2$ or $3$, then it
is not divisible by $6$.

Converse:

$\forall$ integer $n$, if $n$ is divisible by $2$ and $n$ is divisible by $3$,
then $n$ is divisible by $6$.

This is true, for the same reasons given by the original statement.

Inverse:

$\forall$ integer $n$, if $n$ is not divisible by $6$, then $n$ is not divisible
by $2$ or $n$ is not divisible by $3$.

This is true, for the same reasons given in the contrapositive.

32. Exercise 22

Original Statement:

If the square of an integer is odd, then the integer is odd.

This is a true statement, if the square of an integer returns an odd integer
then that integer is odd.

Contrapositive:

If an integer is not odd, then the square of the integer is not odd.

This is a true statement, if an integer is not odd, it's square is not odd
(even).

Converse:

If an integer is odd, then the square of the integer is odd.

This is a true statement, squaring any odd integer returns an odd integer.

Inverse:

If the square of an integer is not odd, then the integer is not odd.

This is a true statement, if squaring an integer returns a not odd integer, then
that integer is not odd.

33. Exercise 23

Original Statement:

If a function is differentiable then it is continuous.

This is true, as a function that is differentiable means that the function has a
limit that does not approach $\infty$/$-\infty$, and a continuous function is
any function without any breaks in it's graph along the standard Cartesian
plane.

Contrapositive:

If a function is not continuous then it is not differentiable.

This is true. If a function has any breaks, it's slope cannot be calculated, and
therefore the function is not differentiable.

Converse:

If a function is continuous, then it is differentiable.

This is false. A function can be continuous, but it's limit can approach
$-\infty$/$\infty$, so therefore it could be not differentiable. This statement
is false.

Inverse:

If a function is not differentiable then it is not continuous.

This is not true. Just because a function's limit can approach
$\infty$/$-\infty$, meaning it is not differentiable, does not necessarily mean
that it is not continuous, as its limit could still approach some fixed number.
This statement is false.

34. Write the contrapositive for each of the following statements.

a. If $n$ is prime, then $n$ is not divisible by any prime number from $2$
through $\sqrt{n}$. (Assume that $n$ is a fixed integer.)

If $n$ is divisible by any prime number from $2$ through $\sqrt{n}$ inclusive,
then $n$ is prime.

b. If $A$ and $B$ do not have any elements in common, then they are disjoint.
(Assume that $A$ and $B$ are fixed sets.)

If $A$ and $B$ are not disjoint, then $A$ and $B$ have some elements in common.

35. Give an example to show that a universal conditional statement is not
    logically equivalent to its inverse.

Consider the statement "If a student studies math, then they wear glasses." This
is a universal conditional statement. Consider the inverse statement. "If a
student does not study math, then they do not wear glasses." These two
statements are not logically equivalent. The original statement claims that all
students who study math wear glasses, where the second statement claims that all
students who don't study math do not wear glasses.

Consider two students, Alice and Bob. Alice studies math and wears glasses,
while Bob does not study math, but wears glasses. For the original statement,
these two cases would be true, Alice does study math and wears glasses, whereas
Bob does not study math, so the conclusion that he doesn't wear glasses still is
a true conclusion. Juxtapose this with the inverse statement, where Bob not
studying math is true (a true hypothesis), but he does wear glasses, which
negates the inverse statement's conclusion (it is false). This is a false
statement, and therefore the original statement and the inverse statement are
not logically equivalent.

36. If $P(x)$ is a predicate and the domain of $x$ is the set of all real
    numbers, let $R$ be "$\forall x \in \mathbb{Z}, P(x)$" let $S$ be
    "$\forall x \in \mathbb{Q}, P(x)$", and let $T$ be
    "$\forall x \in \mathbb{R}, P(x)$."

a. Find a definition for $P(x)$ (but do not use "$x \in \mathbb{Z}$") so that
$R$ is true and both $S$ and $T$ are false.

Consider $P(x) = 3x \neq 1$. This is true of $R$, as there is no integer $x$
where $3x = 1$, but is not false for $S$ and $T$ where $x = \dfrac{1}{3}$.

b. Find a definition for $P(x)$ (but do not use "$x \in \mathbb{Q}$") so that
both $R$ and $S$ are true and $T$ is false.

This isn't possible, it might be possible for $P(n, x)$, but with just a single
variable $P(x)$, this is not possible.

37. Consider the following sequence of digits: 0204. A person claims that all
    the 1's in the sequence are to the left of all the 0's in the sequence. Is
    this true? Justify your answer. (_Hint:_ Write the claim formally and write
    a formal negation of it. Is the negation true or false?)

Formal claim:

In the sequence of digits 0204, all digits that are 1's are to the left of all
the 0's.

Negation:

In the sequence of digits 0204, there exists at least one 1 that is not to the
left of all 0's.

The negation claim is false because there is no 1 in the sequence, so the
original claim is vacuously true.

38. True or false? All occurrences of the letter _u_ in _Discrete Mathematics_
    are lowercase. Justify your answer.

Formal claim:

$\forall$ letters $x$ in the string _Discrete Mathematics_, if $x$ is the letter
_u_, then $x$ is lowercase.

Negation:

$\exists$ some letter $x$ in the string _Discrete Mathematics_ such that $x$ is
the letter _u_ and $x$ is not lowercase.

The negation statement is false, as there is no letter _u_ in _Discrete
Mathematics_, and so the original statement is vacuously true.

Rewrite each statement of 39-44 in if-then form.

39. Earning a grade of C- in this course is a sufficient condition for it to
    count toward graduation.

If a person earns a grade of C- in this course, then the course counts towards
graduation.

40. Being divisible by 8 is a sufficient condition for being divisible by 4.

If a number is divisible by 8, then it is divisible by 4.

41. Being on time each day is a necessary condition for keeping this job.

If a person is not on time each day, then this person will not keep this job.

42. Passing a comprehensive exam is a necessary condition for obtaining a
    master's degree.

If a person does not pass a comprehensive exam, then they will not obtain a
master's degree.

43. A number is prime only if it is greater than 1.

If a number is prime, then it is greater than 1.

44. A polygon is square only if it has four sides.

If a polygon is square, then it has four sides.

Use the fact that the negation of a $\forall$ statement is a $\exists$ statement
and that the negation of an if-then statement is an _and_ statement to rewrite
each of the statements 45-48 without using the word _necessary_ or _sufficient_.

45. Being divisible by 8 is not a necessary condition for being divisible by 4.

Original without not is:

Being divisible by 8 is a necessary condition for being divisible by 4.

As if-then:

If a number is not divisible by 8, then it is not divisible by 4.

Negation:

There is a number that is not divisible by 8 and is divisible by 4.

46. Having a large income is not a necessary condition for a person to be happy.

Original without not:

Having a large income is a necessary condition for a person to be happy.

If-then (necessary condition):

If a person does not have a large income, then they are not happy.

Negation:

There is a person that does not have a large income and is happy.

47. Having a large income is not a sufficient condition for a person to be
    happy.

Original without not:

Having a large income is a sufficient condition for a person to be happy.

If-not(sufficient):

If a person has a large income, then they are happy.

Negation:

There is a person with a large income that is not happy.

48. Being a polynomial is not a sufficient condition for a function to have a
    real root.

Original without not:

Being a polynomial is a sufficient condition for a function to have a real root.

If-then(sufficient):

If a function is a polynomial, then it has a real root.

Negation:

There is a function that is a polynomial and does not have a real root.

49. The computer scientists Richard Conway and David Gries once wrote:

> The absence of error messages during translation of a computer program is only
> a necessary and not a sufficient condition for reasonable [program]
> correctness.

Rewrite this statement without using the words _necessary_ or _sufficient_.

Divide it up into two statements:

The absence of error messages during translation of a computer program is a
necessary condition for reasonable [program] correctness.

The absence of error messages during translation of a computer program is not a
sufficient condition for reasonable [program] correctness.

Now rewrite the first statement as an if-then (necessary):

If a computer program does have error messages during translation, then the
program does not have reasonable correctness.

Now rewrite the second statement first without the not:

The absence of error messages during translation of a computer program is a
sufficient condition for reasonable [program] correctness.

And rewrite as if-then(sufficient):

If a computer program does not have error messages during translation, then the
program does have reasonable correctness.

And now take the negation:

There is a computer program that does not have error messages during translation
and does not have reasonable correctness.

Now combine them:

If a computer program does have error messages during translation, then the
program does not have reasonable correctness, and there is a computer program
that does not have error messages during translation but still does not have
reasonable correctness.

50. A frequent-flyer club brochure states, "You may select among carriers only
    if they offer the same lowest fare." Assuming that "only if" has its formal,
    logical meaning, does this statement guarantee that if two carriers offer
    the same lowest fare, the customer will be free to choose between them?
    Explain.

Take the original statement:

"You may select among carriers only if they offer the same lowest fare."

Translate to if-then (only if):

If you select among carriers, then they offer the same lowest fare.

$$ S \to F $$

Original statement.

Or equivalently:

If the carrier does not offer the same lowest fare, then you did not select
among carriers.

$$ \neg F \to \neg S $$

The contrapositive.

Now compare to the comparison statement:

"If two carriers offer the same lowest fare, the customer will be free to choose
between them."

This is:

$$ F \to S $$

This is the converse statement, and is not logically equivalent to the original.

---

**Exercise Set 3.3**

Page 166

1. Let $C$ be the set of cities in the world, let $N$ be the set of nations in
   the world, and let $P(c, n)$ be "$c$ is the capital city of $n$." Determine
   the truth values of the following statements.

a. $P(\text{Tokyo}, \text{Japan})$

b. $P(\text{Athens}, \text{Egypt})$

c. $P(\text{Paris}, \text{France})$

d. $P(\text{Miami}, \text{Brazil})$

2. Let $G(x, y)$ be "$x^2 > y$." Indicate which of the following statements are
   true and which are false.

a. $G(2, 3)$

b. $G(1, 1)$

c. $G(\dfrac{1}{2}, \dfrac{1}{2})$

d. $G(-2, 2)$

3. The following statement is true: "$\forall$ nonzero number $x$, $\exists$ a
   real number $y$ such that $xy = 1$." For each $x$ given below, find a $y$ to
   make the predicate "$xy = 1$" true.

a. $x = 2$

b. $x = -1$

c. $x = \dfrac{3}{4}$

4. The following statement is true: "$\forall$ real number $x$, $\exists$ an
   integer $n$ such that $n > x$.". For each $x$ given below, find an $n$ to
   make the predicate $n > x$ true.

a. $x = 15.83$

b. $x = 10^8$

c. $x = 10^{10^{10}}$

The statements in exercises 5-8 refer to the Tarski world given in Figure 3.3.1.
Explain why each is true.

5. For every circle $x$ there is a square $y$ such that $x$ and $y$ have the
   same color.

6. For every square $x$ there is a circle $y$ such that $x$ and $y$ have
   different colors and $y$ is above $x$.

7. There is a triangle $x$ such that for every square $y$, $x$ is above $y$.

8. There is a triangle $x$ such that for every circle $y$, $y$ is above $x$.

9. Let $D = E = \{-2, -1, 0, 1, 2\}$. Explain why the following statements are
   true.

a. $\forall x$ in $D$, $\exists y$ such that $x + y = 0$.

b. $\exists x$ in $D$ such that $\forall y$ in $E$, $x + y = y$.

10. This exercise refers to Example 3.3.3. Determine whether each of the
    following statements is true or false.

a. $\forall$ student $S$, $\exists$ a dessert $D$ such that $S$ chose $D$.

b. $\forall$ student $S$, $\exists$ a salad $T$ such that $S$ chose $T$.

c. $\exists$ a dessert $D$ such that $\forall$ student $S$, $S$ chose $D$.

d. $\exists$ a beverage $B$ such that $\forall$ student $D$, $D$ chose $B$.

e. $\exists$ an item $I$ such that $\forall$ student $S$, $S$ did not choose
$I$.

f. $\exists$ a station $Z$ such that $\forall$ student $S$, $\exists$ an item
$I$ such that $S$ chose $I$ from $Z$.

11. Let $S$ be the set of students at your school, let $M$ be the set of movies
    that have ever been released, and let $V(s, m)$ be "student $s$ has seen
    movie $m$." Rewrite each of the following statements without using the
    symbol $\forall$, the symbol $\exists$, or variables.

a. $\exists s \in S$ such that $V(s, \text{Casablanca})$.

b. $\forall s \in S, V(s, \text{Star Wars})$.

c. $\forall s \in S, \exists m \in M \text{ such that } V(s, m)$.

d. $\exists m \in M \text{ such that } \forall s \in S, V(s, m)$.

e.
$\exists s \in S, \exists t \in S, \text{ and } \exists m \in M \text{ such that } s \neq t \text{ and } V(s, m) \wedge V(t, m)$.

f.
$\exists s \in S \text{ and } \exists t \in S \text{ such that } s \neq t \text{ and } \forall m \in M, V(s, m) \to V(t, m)$.

12. Let $D = E = \{-2, -1, 0, 1, 2\}$. Write negations for each of the following
    statements and determine which is true, the given statement or its negation.

a. $\forall x$ in $D$, $\exists y$ such that $x + y = 1$.

b. $\exists x$ in $D$ such that $\forall y$ in $E$, $x + y = -y$.

c. $\forall x$ in $D$, $\exists y$ in $E$ such that $xy \geq y$.

d. $\exists x$ in $D$ such that $\forall y$ in $E$, $x \leq y$.

In each of 13-19, (a) rewrite the statement in English without using the symbol
$\forall$ or $\exists$ or variables and expressing your answer as simply as
possible, and (b) write a negation for the statement.

13. $\forall$ color $C$, $\exists$ an animal $A$ such that $A$ is colored $C$.

14. $\exists$ a book $b$ such that $\forall$ person $p$, $p$ has read $b$.

15. $\forall$ odd integer $n$, $\exists$ an integer $k$ such that $n = 2k + 1$.

16. $\exists$ a real number $u$ such that $\forall$ real number $v$, $uv = v$.

17. $\forall r \in \mathbb{Q}$, $\exists$ integers $a$ and $b$ such that
    $r = \dfrac{a}{b}$.

18. $\forall x \in \mathbb{R}$, $\exists$ a real number $y$ such that
    $x + y = 0$.

19. $\exists x \in \mathbb{R}$ such that for every real number $y$, $x + y = 0$.

20. Recall that reversing the order of the quantifiers in a statement with two
    different quantifiers may change the truth value of the statement - but it
    does not necessarily do so. All the statements in the pairs below refer to
    the Tarski world of Figure 3.3.1. In each pair, the order of the quantifiers
    is reversed but everything else is the same. For each pair, determine
    whether the statements have the same or opposite truth values. Justify your
    answers.

a.

(1) For every square $y$ there is a triangle $x$ such that $x$ and $y$ have
different colors.

(2) There is a triangle $x$ such that for every square $y$, $x$, and $y$ have
different colors.

b.

(1) For every circle $y$ there is a square $x$ such that $x$ and $y$ have the
same color.

(2) There is a square $x$ such that for every circle $y$, $x$ and $y$ have the
same color.

21. For each of the following equations, determine which of the following
    statements are true:

(1) For every real number $x$, there exists a real number $y$ such that the
equation is true.

(2) There exists a real number $x$, such that for every real number $y$, the
equation is true.

Note that it is possible for both statements to be true or for both to be false.

a. $2x + y = 7$

b. $y + x = x + y$

c. $x^2 - 2xy + y^2 = 0$

d. $(x - 5)(y - 1) = 0$

e. $x^2 + y^2 = -1$

In 22 and 23, rewrite each statement without using variables or the symbol
$\forall$ or $\exists$. Indicate whether the statement is true or false.

22.

a. $\forall$ real number $x$, $\exists$ a real number $y$ such that $x + y = 0$.

b. $\exists$ a real number $y$ such that $\forall$ real number $x$, $x + y = 0$.

23.

a. $\forall$ nonzero real number $r$, $\exists$ a real number $s$ such that
$rs = 1$.

b. $\exists$ a real number $r$ such that $\forall$ nonzero real number $s$,
$rs = 1$.

24. Use the laws for negating universal and existential statements to derive the
    following rules:

a.
$\neg(\forall x \in D(\forall y \in E(P(x, y)))) \equiv \exists x \in D(\exists y \in E(\neg P(x, y)))$

b.
$\neg(\exists x \in D(\exists y \in E(P(x, y)))) \equiv \forall x \in D(\forall y \in E(\neg P(x, y)))$

Each statement in 25-28 refers to the Tarski world of Figure 3.3.1. For each,
(a) determine whether the statement is true or false and justify your answer,
and (b) write a negation for the statement (referring, if you wish, to the
result in exercise 24).

25. $\forall$ circle $x$ and $\forall$ square $y$, $x$ is above $y$.

26. $\forall$ circle $x$ and $\forall$ triangle $y$, $x$ is above $y$.

27. $\exists$ a circle $x$ and $\exists$ a square $y$ such that $x$ is above $y$
    and $x$ and $y$ have different colors.

28. $\exists$ a triangle $x$ and $\exists$ a square $y$ such that $x$ is above
    $y$ and $x$ and $y$ have the same color.

For each of the statements in 29 and 30, (a) write a new statement by
interchanging the symbols $\forall$ and $\exists$, and (b) state which is true:
the given statement, the version with interchanged quantifiers, neither or both.

29. $\forall x \in \mathbb{R}, \exists y \in \mathhbb{R}$ such that $x < y$.

30. $\exists x \in \mathbb{R}$ such that $\forall y \in \mathbb{R}^{-}$ (the set
    of negative real numbers), $x > y$.

31. Consider the statement "Everybody is older than somebody." Rewrite this
    statement in the form "$\forall$ people $x$, $\exists$ ______."

32. Consider the statement "Somebody is older than everybody." Rewrite this
    statement in the form "$\exists$ a person $x$ such that $\forall$ ______."

In 33-39, (a) rewrite the statement formally using quantifiers and variables,
and (b) write a negation for the statement.

33. Everybody loves somebody.

34. Somebody loves everybody.

35. Everybody trusts somebody.

36. Somebody trusts everybody.

37. Any even integer equals twice some integer.

38. Every action has an equal and opposite reaction.

39. There is a program that gives the correct answer to every question that is
    posed to it.

40. In informal speech most sentences of the form "There is ______ every ______"
    are intended to be understood as meaning "$\forall$ ______ $\exists$
    ______," even though the existential quantifier _there is_ comes before the
    universal quantifier _every_. Note that this interpretation applies to the
    following well-known sentences. Rewrite them using quantifiers and
    variables.

a. There is a sucker born every minute.

b. There is a time for every purpose under heaven.

41. Indicate which of the following statements are true and which are false.
    Justify your answers as best you can.

a. $\forall x \in \mathbb{Z}^{+}, \exists y \in \mathbb{Z}^{+}$ such that
$x = y + 1$.

b. $\forall x \in \mathbb{Z}, \exists y \in \mathbb{Z}$ such that $x = y + 1$.

c. $\exists x \in \mathbb{R}$ such that $\forall y \in \mathbb{R}, x = y + 1$ .

d. $\forall x \in \mathbb{R}^{+}, \exists y \in \mathbb{R}^{+}$ such that
$xy = 1$.

e. $\forall x \in \mathbb{R}, \exists y \in \mathbb{R}$ such that $xy = 1$.

f. $\exists x \in \mathbb{R}$ such that $\forall y \in \mathbb{R}, x + y = y$.

g. $\forall x \in \mathbb{R}^{+}, \exists y \in \mathbb{R}^{+}$ such that
$y < x$.

h. $\exists x \in \mathbb{R}^{+}$ such that
$\forall y \in \mathbb{R}^{+}, x \leq y$.

42. Write the negation of the definition of limit of a sequence given in Example
    3.3.7.

43. The following is the definition for $\lim\limits_{x \to a}f(x) = L$:

For every real number $\varepsilon > 0$, there exists a real number $\delta > 0$
such that for every real number $x$, if $a - \delta < x < a + \delta$ and
$x \neq a$ then

$$ L - \varepsilon < f(x) < L + \varepsilon $$

Write what it means for $\lim\limits_{x \to a}f(x) \neq L$. In other words,
write the negation of the definition.

44. The notation $\exists !$ stands for the words "there exists a unique." Thus,
    for instance, "$\exists ! x$ such that $x$ is prime and $x$ is even" means
    that there is one and only one even prime number. Which of the following
    statements are true and which are false?

a. $\exists !$ real number $x$ such that $\forall$ real number $y$, $xy = y$.

b. $\exists !$ integer $x$ such that $\dfrac{1}{x}$ is an integer.

c. $\forall$ real number $x$, $\exists !$ real number $y$ such that $x + y = 0$.

45. Suppose that $P(x)$ is a predicate and $D$ is the domain of $x$. Rewrite the
    statement "$\exists ! x \in D \text{ such that } P(x)$" without using the
    symbol $\exists !$. (See exercise 44 for the meaning of $\exists !$.)

In 46-54, refer to the Tarski world given in Figure 3.1.1, which is shown again
here for reference. The domains of all variables consist of all the objects in
the Tarski world. For each statement, (a) indicate whether the statement is true
or false and justify your answer, (b) write the given statement using the formal
logical notation illustrated in Example 3.3.10, and (c) write a negation for the
given statement using the formal logical notation of Example 3.3.10.

46. There is a triangle $x$ such that for every square $y$, $x$ is above $y$.

47. There is a triangle $x$ such that for every circle $y$, $x$ is above $y$.

48. For every circle $x$, there is a square $y$ such that $y$ is to the right of
    $x$.

49. For every object $x$, if $x$ is a circle then there is a square $y$ such
    that $y$ has the same color as $x$.

50. For every object $x$, if $x$ is a triangle then there is a square $y$ such
    that $y$ is below $x$.

51. There is a square $x$ such that for every triangle $y$, if $y$ is above $x$
    then $y$ has the same color as $x$.

52. For every circle $x$ and for every triangle $y$, $x$ is to the right of $y$.

53. There is a circle $x$ and there is a square $y$ such that $x$ and $y$ have
    the same color.

54. There is a circle $x$ and there is a triangle $y$ such that $x$ has the same
    color as $y$.

Let $P(x)$ and $Q(x)$ be predicates and suppose $D$ is the domain of $x$. In
55-58, for the statement forms in each pair, determine whether (a) they have the
same truth value for every choice of $P(x)$, $Q(x)$ and $D$, or (b) there is a
choice of $P(x)$, $Q(x)$, and $D$ for which they have opposite truth values.

55. $\forall x \in D, (P(x) \wedge Q(x)) \text{ and } (\forall x \in D, P(x)) \wedge (\forall x \in D, Q(x))$

56. $\exists x \in D, (P(x) \wedge Q(x)) \text{ and } (\exists x \in D, P(x)) \wedge (\exists x \in D, Q(x))$

57. $\forall x \in D, (P(x) \vee Q(x)) \text{ and } (\forall x \in D, P(x)) \vee (\forall x \in D, Q(x))$

58. $\exists x \in D, (P(x) \vee Q(x)) \text{ and } (\exists x \in D, P(x)) \vee (\exists x \in D, Q(x))$

In 59-61, find the answers Prolog would give if the following questions were
added to the program given in Example 3.3.11.

59.

a. $?\text{isabove}(b_1, w_1)$

b. $?\text{color}(X, white)$

c. $?\text{isabove}(X, b_3)$

60.

a. $?\text{isabove}(w_1, g)$

b. $?\text{color}(w_2, blue)$

c. $?\text{isabove}(X, b_1)$

61.

a. $?\text{isabove}(w_2, b_3)$

b. $?\text{color}(X, gray)$

c. $?\text{isabove}(g, X)$
