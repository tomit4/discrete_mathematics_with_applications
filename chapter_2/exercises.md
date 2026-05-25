**Exercise Set 2.1**

Page 74

In each of 1-4 represent the common form of each argument using letters to stand
for component sentences, and fill in the blanks so that the argument in part (b)
has the same logical form as the argument in part (a).

1.

a.

If all integers are rational, then the number $1$ is rational.

All integers are rational.

Therefore, the number $1$ is rational.

If $p$, then $q$.

$p$

Therefore, $q$

b.

If all algebraic expressions can be written in prefix notation ,then

"$(a^2 + 2b)(a^2 - b)$ can be written in prefix notation.".

"All algebraic expressions can be written in prefix notation".

Therefore, $(a + 2b)(a^2 - b)$ can be written in prefix notation.

2.

a.

If all computer programs contain errors, then this program contains an error.

This program does not contain an error.

Therefore, it is not the case that all computer programs contain errors.

If $p$, then $\neg q$.

$\neg q$.

Therefore $\neg p$.

b.

If ______, then ______.

"2 is odd"

"all prime numbers are odd."

2 is not odd.

Therefore, it is not the case that all prime numbers are odd.

3.

a.

This number is even or this number is odd.

This number is not even.

Therefore, this number is odd.

Either $p$ or $q$.

$\neg p$

Therefore $q$

b.

______ or logic is confusing.

"My mind is shot"

My mind is not shot.

Therefore, ______.

"the logic is confusing."

4.

a.

If the program syntax is faulty, then the computer will generate an error
message.

If the computer generates an error message, then the program will not run.

Therefore, if the program syntax is faulty, then the program will not run.

If $p$, then $q$.

If $q$ then $\neg r$.

Therefore, if $p$, then $\neg r$.

b.

If this simple graph ______, then it is complete.

If this graph ______, then any two of its vertices can be joined by a path.

Therefore, if this simple graph has 4 vertices and 6 edges, then ______.

"has 4 vertices"

"has 6 edges"

"any two of its vertices can be joined by a path."

5. Indicate which of the following sentences are statements.

a. 1,024 is the smallest four-digit number that is a perfect square.

This is a statement (a true one).

b. She is a mathematics major.

This is a statement.

c. $128 = 2^6$

This is a statement.

d. $x = 2^6$

This is not a statement.

Write the statements in 6-9 in symbolic form using the symbols $\neg$, $\wedge$,
$\vee$ and the indicated letters to represent component statements.

6. Let $s = $ "stocks are increasing" and $i = $ "interest rates are steady."

a. Stocks are increasing but interest rates are steady.

$$ s \wedge i $$

b. Neither are stocks increasing nor are interest rates steady.

$$ \neg s \wedge \neg i $$

7. Juan is a math major but not a computer science major. ($m = $ "Juan is a
   math major," $c = $ "Juan is a computer science major")

$$ m \wedge \neg c $$

8. Let $h = $ "John is healthy," $w = $ "John is wealthy," and $s = $ "John is
   wise."

a. John is healthy and wealthy but not wise.

$$ (h \wedge w \wedge) \neg s $$

b. John is not wealthy but he is healthy and wise.

$$ \neg w \wedge (h \wedge s) $$

c. John is neither healthy, wealthy, nor wise.

$$ (\neg h \wedge \neg w) \wedge \neg s $$

d. John is neither wealthy nor wise, but he is healthy.

$$ (\neg w \wedge \neg s) \wedge h $$

e. John is wealthy, but he is not both healthy and wise.

$$ h \wedge (\neg h \neg s) $$

9. Let $p = $ "$x > 5$," $q = $ "$x = 5$," and $r = $ "$10 > x$."

a. $x \geq 5$

$$ p \ vee q $$

b. $10 > x > 5$

$$ r \wedge p $$

c. $10 > x \geq 5$

$$ r \wedge (p \vee q) $$

10. Let $p$ be the statement "DATAENDFLAG is off," $q$ the statement "ERROR
    equals 0," and $r$ the statement "SUM is less than 1,000." Express the
    following sentences in symbolic notation.

a. DATAENDFLAG is off, ERROR equals 0, and SUM is less than 1,000.

$$ p \wedge q \wedge r $$

b. DATAENDFLAG is off but ERROR is not equal to 0.

$$ p \wedge \neg q $$

c. DATAENDFLAG is off; however, ERROR is not 0 or SUM is greater than or equal
to 1,000.

$$ p \wedge (\neg q \vee \neg r) $$

e. Either DATAENDFLAG is on or it is the case that both ERROR equals 0 and SUM
is less than 1,000.

$$ \neg p \vee (q \wedge r) $$

11. In the following sentence, is the word _or_ used in its inclusive or
    exclusive sense? A team wins the playoffs if it wins two games in a row or a
    total of three games.

This is an inclusive or, as it is possible for the team to win two games in a
row and a total of three games.

Write truth tables for the statement forms 12-15.

12. $\neg p \wedge q$

| $p$ | $q$ | $\neg p$ | $\neg p \wedge q$ |
| --- | --- | -------- | ----------------- |
| T   | T   | F        | F                 |
| T   | F   | F        | F                 |
| F   | T   | T        | T                 |
| F   | F   | T        | F                 |

13. $\neg (p \wedge q) \vee (p \vee q)$

| $p$ | $q$ | $(p \wedge q)$ | $\neg (p \wedge q)$ | $(p \vee q)$ | $\neg (p \wedge q) \vee (p \vee q)$ |
| --- | --- | -------------- | ------------------- | ------------ | ----------------------------------- |
| T   | T   | T              | F                   | T            | T                                   |
| T   | F   | F              | T                   | T            | T                                   |
| F   | T   | F              | T                   | T            | T                                   |
| F   | F   | F              | T                   | F            | T                                   |

14. $p \wedge (q \wedge r)$

| $p$ | $q$ | $r$ | $(q \wedge r)$ | $p \wedge (q \wedge r)$ |
| --- | --- | --- | -------------- | ----------------------- |
| T   | T   | T   | T              | T                       |
| T   | T   | F   | F              | F                       |
| T   | F   | T   | F              | F                       |
| T   | F   | F   | F              | F                       |
| F   | T   | T   | T              | F                       |
| F   | T   | F   | F              | F                       |
| F   | F   | T   | F              | F                       |
| F   | F   | F   | F              | F                       |

15. $p \wedge (\neg q \vee r)$

| $p$ | $q$ | $r$ | $(q \vee r)$ | $\neg (q \vee r)$ | $p \wedge (\neg q \vee r)$ |
| --- | --- | --- | ------------ | ----------------- | -------------------------- |
| T   | T   | T   | T            | F                 | F                          |
| T   | T   | F   | T            | F                 | F                          |
| T   | F   | T   | T            | F                 | F                          |
| T   | F   | F   | F            | T                 | T                          |
| F   | T   | T   | T            | F                 | F                          |
| F   | T   | F   | T            | F                 | F                          |
| F   | F   | T   | T            | F                 | F                          |
| F   | F   | F   | F            | T                 | F                          |

Determine whether the statement forms in 16-24 are logically equivalent. In each
case, construct a truth table and include a sentence justifying your answer.
Your sentence should show that you understand the meaning of logical
equivalence.

16. $p \vee (p \wedge q) \text{ and } p$

| $p$ | $q$ | $(p \wedge q)$ | $p \vee (p \wedge q)$ |
| --- | --- | -------------- | --------------------- |
| T   | T   | T              | T                     |
| T   | F   | F              | T                     |
| F   | T   | F              | F                     |
| F   | F   | F              | F                     |

As the columns for both $p$ and $p \vee (p \wedge q)$ have the same truth
values, they can be said to be equivalent. This proves one of the absorption
laws.

17. $\neg (p \wedge q) \text{ and } \neg p \wedge \neg q$

| $p$ | $q$ | $\neg p$ | $\neg q$ | $(p \wedge q)$ | $\neg (p \wedge q)$ | $\neg p \wedge \neg q$ |
| --- | --- | -------- | -------- | -------------- | ------------------- | ---------------------- |
| T   | T   | F        | F        | T              | F                   | F                      |
| T   | F   | F        | T        | F              | T                   | F                      |
| F   | T   | T        | F        | F              | T                   | F                      |
| F   | F   | T        | T        | F              | T                   | T                      |

No $\neg (p \wedge q) \cancel{\equiv} \neg p \wedge \neg q$, as the columns for
both $\neg (p \wedge q)$ and $\neg p \wedge \neg q$ do not have the same truth
values.

18. $p \vee \mathbf{t} \text{ and } \mathbf{t}$

| $p$ | $\mathbf{t}$ | $p \vee \mathbf{t}$ |
| --- | ------------ | ------------------- |
| T   | T            | T                   |
| F   | T            | T                   |

Yes, $p \vee \mathbf{t} \equiv \mathbf{t}$, proving one of the universal bound
laws.

19. $p \wedge \mathbf{t} \text{ and } p$

| $p$ | $\mathbf{t}$ | $p \wedge \mathbf{t}$ |
| --- | ------------ | --------------------- |
| T   | T            | T                     |
| F   | T            | F                     |

Yes, $p \wedge \mathbf{t} \equiv p$, proving one of the identity laws.

20. $p \wedge \mathbf{c} \text{ and } p \vee \mathbf{c}$

| $p$ | $\mathbf{c}$ | $p \wedge \mathbf{c}$ | $p \vee \mathbf{c}$ |
| --- | ------------ | --------------------- | ------------------- |
| T   | F            | F                     | T                   |
| F   | F            | F                     | F                   |

No, $p \wedge \mathbf{c} \cancel{\equiv} p \vee \mathbf{c}$, as their two
column's truth values are not equal.

21. $(p \wedge q) \wedge r \text{ and } p \wedge (q \wedge r)$

| $p$ | $q$ | $r$ | $(p \wedge q)$ | $(q \wedge r)$ | $(p \wedge q) \wedge r$ | $p \wedge (q \wedge r)$ |
| --- | --- | --- | -------------- | -------------- | ----------------------- | ----------------------- |
| T   | T   | T   | T              | T              | T                       | T                       |
| T   | T   | F   | T              | F              | F                       | F                       |
| T   | F   | T   | F              | F              | F                       | F                       |
| T   | F   | F   | F              | F              | F                       | F                       |
| F   | T   | T   | F              | T              | F                       | F                       |
| F   | T   | F   | F              | F              | F                       | F                       |
| F   | F   | T   | F              | F              | F                       | F                       |
| F   | F   | F   | F              | F              | F                       | F                       |

Yes, $(p \wedge q) \wedge r \equiv p \wedge (q \wedge r)$, proving one of the
associative laws.

22. $p \wedge (q \vee r) \text{ and } (p \wedge q) \vee (p \wedge r)$

| $p$ | $q$ | $r$ | $(q \vee r)$ | $(p \wedge q)$ | $(p \wedge r)$ | $p \wedge (q \vee r)$ | $(p \wedge q) \vee (p \wedge r)$ |
| --- | --- | --- | ------------ | -------------- | -------------- | --------------------- | -------------------------------- |
| T   | T   | T   | T            | T              | T              | T                     | T                                |
| T   | T   | F   | T            | T              | F              | T                     | T                                |
| T   | F   | T   | T            | F              | T              | T                     | T                                |
| T   | F   | F   | F            | F              | F              | F                     | F                                |
| F   | T   | T   | T            | F              | F              | F                     | F                                |
| F   | T   | F   | T            | F              | F              | F                     | F                                |
| F   | F   | T   | T            | F              | F              | F                     | F                                |
| F   | F   | F   | F            | F              | F              | F                     | F                                |

Yes, $p \wedge (q \vee r) \equiv (p \wedge q) \vee (p \wedge r)$, proving one of
the distributive laws.

23. $(p \wedge q) \vee r \text{ and } p \wedge (q \vee r)$

| $p$ | $q$ | $r$ | $(p \wedge q)$ | $(q \vee r)$ | $(p \wedge q) \vee r$ | $p \wedge (q \vee r)$ |
| --- | --- | --- | -------------- | ------------ | --------------------- | --------------------- |
| T   | T   | T   | T              | T            | T                     | T                     |
| T   | T   | F   | T              | T            | T                     | T                     |
| T   | F   | T   | F              | T            | T                     | T                     |
| T   | F   | F   | F              | F            | F                     | F                     |
| F   | T   | T   | F              | T            | T                     | F                     |
| F   | T   | F   | F              | T            | F                     | F                     |
| F   | F   | T   | F              | T            | T                     | F                     |
| F   | F   | F   | F              | F            | F                     | F                     |

No, $(p \wedge q) \vee r \cancel{\equiv} p \wedge (q \vee r)$, as their columns
in the truth table do not have the same truth values.

24. $(p \vee q) \vee (p \wedge r) \text{ and } (p \vee q) \wedge r$

| $p$ | $q$ | $r$ | $(p \vee q)$ | $(p \wedge r)$ | $(p \vee q) \vee (p \wedge r)$ | $(p \vee q) \wedge r$ |
| --- | --- | --- | ------------ | -------------- | ------------------------------ | --------------------- |
| T   | T   | T   | T            | T              | T                              | T                     |
| T   | T   | F   | T            | F              | T                              | F                     |
| T   | F   | T   | T            | T              | T                              | T                     |
| T   | F   | F   | T            | F              | T                              | F                     |
| F   | T   | T   | T            | F              | T                              | T                     |
| F   | T   | F   | T            | F              | T                              | F                     |
| F   | F   | T   | F            | F              | F                              | F                     |
| F   | F   | F   | F            | F              | F                              | F                     |

No, $(p \vee q) \vee (p \wedge r) \cancel{\equiv} (p \vee q) \wedge r$, as their
two columns in the truth table do not have the same truth values.

Use De Morgan's laws to write negations for the statements in 25-30.

25. Hal is a math major and Hal's sister is a computer science major.

Hal is not a math major or Hal's sister is not a computer science major.

26. Sam is an orange belt and Kate is a red belt.

Sam is not an orange belt or Kate is not a red belt.

27. The connector is loose or the machine is unplugged.

The connector is not loose and the machine is not unplugged.

28. The train is late or my watch is fast.

The train is not late and my watch is not fast.

29. This computer program has a logical error in the first ten lines or it is
    being run with an incomplete data set.

This computer program does not have a logical error in the first ten lines and
it is not being run with an incomplete data set.

30. The dollar is at an all-time high and the stock market is at a record low.

The dollar is not at an all-time high or the stock market is not at a record
low.

31. Let $s$ be a string of length 2 with characters from $\{0, 1, 2\}$, and
    define statements $a$, $b$, $c$, and $d$ as follows:

$a = $ "the first character of $s$ is 0"

$b = $ "the first character of $s$ is 1"

$c = $ "the second character of $s$ is 1"

$c = $ "the second character of $s$ is 2".

Describe the set of all strings for which each of the following is true.

a. $(a \vee b) \wedge (c \vee d)$

This is the full given set $\{0, 1, 2\}$ as the first letter could be a 0 or 1
and the second letter could be a 1 or 2.

b. $(\neg(a \vee b)) \wedge (c \vee d)$

This is the set $\{1, 2\}$, as the first character is neither 0 nor 1, but the
second character is either 1 or 2.

c. $((\neg a) \vee b) \wedge (c \vee (\neg d))$

This only has the set $\{1\}$, as the first condition says the first character
can either be not 0 or 1, while the second character can be either 1 or not 2.

Assume $x$ is a particular real number and use De Morgan's laws to write
negations for the statements in 32-37.

32. $-2 < x < 7$

$$ -2 \geq x  \text{ or } x \geq 7 $$

33. $-10 < x < 2$

$$ -10 \geq x \text{ or } x \geq 2 $$

34. $x < 2 \text{ or } x > 5$

$$ 2 \leq x \leq 5$$

35. $x \leq -1 \text{ or } x > 1$

$$ -1 < x \leq 1 $$

36. $1 > x \geq -3$

$$ 1 \geq x \text{ or } x < -3 $$

37. $0 > x \geq -7$

$$ 0 \leq x \text{ or } x < -7 $$

In 38 and 39, imagine that _num_orders_ and _num_instock_ are particular values,
such as might occur during execution of a computer program. Write negations for
the following statements.

38. $(\text{num_orders } > 100 \text{ and } \text{num_instock } \leq 500) \text{ or } \text{num_instock } < 200$

$$ (\text{num_orders } \leq 100 \text{ or } \text{num_instock } > 500) \text{ and } \text{num_instock } \geq 200 $$

39. $(\text{num_orders } < 50 \text{ and } \text{num_instock } > 300) \text{ or } (50 \leq \text{ num_orders } < 75 \text{ and } \text{num_instock} > 500)$

$$ (\text{num_orders } \geq 50 \text{ or } \text{num_instock } \leq 300) \text{ and } (50 > \text{ num_orders } \geq 75 \text{ or } \text{num_instock} \leq 500) $$

Use truth tables to establish which of the statement forms in 40-43 are
tautologies and which are contradictions.

40. $(p \wedge q) \vee (\neg p \vee (p \wedge \neg q))$

| $p$ | $q$ | $\neg p$ | $\neg q$ | $(p \wedge q)$ | $(p \wedge \neg q)$ | $(\neg p \vee (p \wedge \neg q))$ | $(p \wedge q) \vee (\neg p \vee (p \wedge \neg q))$ |
| --- | --- | -------- | -------- | -------------- | ------------------- | --------------------------------- | --------------------------------------------------- |
| T   | T   | F        | F        | T              | F                   | F                                 | T                                                   |
| T   | F   | F        | T        | F              | T                   | T                                 | T                                                   |
| F   | T   | T        | F        | F              | F                   | T                                 | T                                                   |
| F   | F   | T        | T        | F              | F                   | T                                 | T                                                   |

So the statement $(p \wedge q) \vee (\neg p \vee (p \wedge \neg q))$ is a
tautology as all of its truth values are true.

41. $(p \wedge \neg q) \wedge (\neg p \vee q)$

| $p$ | $q$ | $\neg p$ | $\neg q$ | $(p \wedge neg q)$ | $(\neg p \vee q)$ | $(p \wedge \neg q) \wedge (\neg p \vee q)$ |
| --- | --- | -------- | -------- | ------------------ | ----------------- | ------------------------------------------ |
| T   | T   | F        | F        | F                  | T                 | F                                          |
| T   | F   | F        | T        | T                  | F                 | F                                          |
| F   | T   | T        | F        | F                  | T                 | F                                          |
| F   | F   | T        | T        | F                  | T                 | F                                          |

So the statement $(p \wedge \neg q) \wedge (\neg p \vee q)$ is a contradiction,
as all of its truth values are false.

42. $((\neg p \wedge q) \wedge (q \wedge r)) \wedge \neg q$

| $p$ | $q$ | $r$ | $\neg p$ | $\neg q$ | (\neg p \wedge q) | $(q \wedge r)$ | $((\neg p \wedge q) \wedge (q \wedge r))$ | $((\neg p \wedge q) \wedge (q \wedge r)) \wedge \neg q$ |
| --- | --- | --- | -------- | -------- | ----------------- | -------------- | ----------------------------------------- | ------------------------------------------------------- |
| T   | T   | T   | F        | F        | F                 | T              | F                                         | F                                                       |
| T   | T   | F   | F        | F        | F                 | F              | F                                         | F                                                       |
| T   | F   | T   | F        | T        | F                 | F              | F                                         | F                                                       |
| T   | F   | F   | F        | T        | F                 | F              | F                                         | F                                                       |
| F   | T   | T   | T        | F        | T                 | T              | T                                         | F                                                       |
| F   | T   | F   | T        | F        | T                 | F              | F                                         | F                                                       |
| F   | F   | T   | T        | T        | F                 | F              | F                                         | F                                                       |
| F   | F   | F   | T        | T        | F                 | F              | F                                         | F                                                       |

So the statement $((\neg p \wedge q) \wedge (q \wedge r)) \wedge \neg q$ is a
contradiction as all of its truth values are false.

43. $(\neg p \vee q) \vee (p \wedge \neg q)$

| $p$ | $q$ | $\neg p$ | $\neg q$ | $(\neg p \vee q)$ | $(p \wedge \neg q)$ | $(\neg p \vee q) \vee (p \wedge \neg q)$ |
| --- | --- | -------- | -------- | ----------------- | ------------------- | ---------------------------------------- |
| T   | T   | F        | F        | T                 | F                   | T                                        |
| T   | F   | F        | T        | F                 | T                   | T                                        |
| F   | T   | T        | F        | T                 | F                   | T                                        |
| F   | F   | T        | T        | T                 | F                   | T                                        |

So the statement $(\neg p \vee q) \vee (p \wedge \neg q)$ is a tautology, as all
of the truth values are true.

44. Recall that $a < x < b$ means that $a < x$ and $x < b$. Also $a \leq b$
    means that $a < b$ or $a = b$. Find all real numbers that satisfy the
    following inequalities.

a. $2 < x \leq 0$

No real numbers satisfy this inequality ($x$ cannot both be greater than $2$ and
less than or equal to $0$).

b. $1 \leq x < -1$

No real numbers satisfy this inequality ($x$ cannot both be greater than or
equal to $1$ and also less than $-1$).

45. Determine whether the statements in (a) and (b) are logically equivalent.

a. Bob is both a math and computer science major and Ann is a math major, but
Ann is not both a math and computer science major.

$$ (p \wedge q \wedge r) \wedge \neg(r \wedge s) $$

$$ (p \wedge q \wedge r) \wedge (\neg r \vee \neg s) $$

$$ p \wedge q \wedge r \wedge \neg s $$

b. It is not the case that both Bob and Ann are both math and computer science
majors, but it is the case that Ann is a math major and Bob is both a math and
computer science major.

$$ \neg((p \wedge r) \wedge (q \wedge s)) \wedge (r \wedge (p \wedge q)) $$

$$ (\neg(p \wedge r) \vee \neg(q \wedge s)) \wedge (r \wedge (p \wedge q)) $$

$$ (\neg p \vee \neg r) \vee (\neg q \vee \neg s) \wedge (r \wedge p \wedge q) $$

$$ \neg s \wedge r \wedge p \wedge q $$

$$ p \wedge q \wedge r \neg s $$

Both parts (a) and (b) are logically equivalent.

46. Let the symbol $\oplus$ denote _exclusive or_; so
    $p \plus q \equiv (p \vee q) \wedge \neg(p \wedge q)$. Hence the truth table
    for $p \plus q$ is as follows:

| $p$ | $q$ | $p \plus q$ |
| --- | --- | ----------- |
| T   | T   | F           |
| T   | F   | T           |
| F   | T   | T           |
| F   | F   | F           |

a. Find simpler statement forms that are logically equivalent to $p \oplus p$
and $(p \oplus p) \oplus p$.

| $p$ | $p$ | $p \oplus p$ | $(p \oplus p) \oplus p$ |
| --- | --- | ------------ | ----------------------- |
| T   | T   | F            | T                       |
| F   | F   | F            | F                       |

$$ p \oplus p \equiv \mathbf{c} $$

$$ (p \oplus p) \oplus p \equiv p $$

b. Is $(p \oplus q) \oplus r \equiv p \oplus (q \oplus r)$? Justify your answer.

| $p$ | $q$ | $r$ | $(p \oplus q)$ | $(q \oplus r)$ | $(p \oplus q) \oplus r$ | $p \oplus (q \oplus r)$ |
| --- | --- | --- | -------------- | -------------- | ----------------------- | ----------------------- |
| T   | T   | T   | F              | F              | T                       | T                       |
| T   | T   | F   | F              | T              | F                       | F                       |
| T   | F   | T   | T              | T              | F                       | F                       |
| T   | F   | F   | T              | F              | T                       | T                       |
| F   | T   | T   | T              | F              | F                       | F                       |
| F   | T   | F   | T              | T              | T                       | T                       |
| F   | F   | T   | F              | T              | T                       | T                       |
| F   | F   | F   | F              | F              | F                       | F                       |

They are equivalent, $(p \oplus q) \oplus r \equiv p \oplus (q \oplus r)$, as
their columns in the truth table show they have the same truth values.

c. Is $(p \oplus q) \wedge r \equiv (p \wedge r) \oplus (q \wedge r)$? Justify
your answer.

| $p$ | $q$ | $r$ | $(p \oplus q)$ | $(p \wedge r)$ | $(q \wedge r)$ | $(p \oplus q) \wedge r$ | $(p \wedge r) \oplus (q \wedge r)$ |
| --- | --- | --- | -------------- | -------------- | -------------- | ----------------------- | ---------------------------------- |
| T   | T   | T   | F              | T              | T              | F                       | F                                  |
| T   | T   | F   | F              | F              | F              | F                       | F                                  |
| T   | F   | T   | T              | T              | F              | T                       | T                                  |
| T   | F   | F   | T              | F              | F              | F                       | F                                  |
| F   | T   | T   | T              | F              | T              | T                       | T                                  |
| F   | T   | F   | T              | F              | F              | F                       | F                                  |
| F   | F   | T   | F              | F              | F              | F                       | F                                  |
| F   | F   | F   | F              | F              | F              | F                       | F                                  |

They are equivalent,
$(p \oplus q) \wedge r \equiv (p \wedge r) \oplus (q \wedge r)$, as their
columns in the truth table show they have the same truth values.

47. In logic and in standard English, a double negative is equivalent to a
    positive. There is one fairly common English usage in which a "double
    positive" is equivalent to a negative. What is it? Can you think of others?

"Yeah, yeah" (see page 902)

In 48 and 49 below, a logical equivalence is derived from Theorem 2.1.1. Supply
a reason for each step.

48.

$$ p \vee \neg q \vee (p \wedge q) \equiv p \wedge (\neg q \vee q) \text{ by (a)} $$

by distributive law

$$ \quad \equiv p \wedge (q \vee \neg q) \text{ by (b)} $$

by commutative law

$$ \quad \equiv p \wedge \mathbf{t} \text{ by (c)} $$

by universal bound law

$$ \quad \equiv p \text{ by (d)} $$

by identity law

Therefore, $(p \wedge \neg q) \vee (p \wedge q) \equiv p$.

49.

$$ (p \vee \neg q) \wedge (\neg p \vee \neg q) $$

$$ \quad \equiv (\neg q \vee p) \wedge (\neg q \vee \neg p) \text{ by (a)} $$

by commutative law

$$ \quad \equiv \neg q \vee (p \wedge \neg p) \text{ by (b)} $$

by distributive law

$$ \quad \equiv q \vee \mathbf{c} \text{ by (c)} $$

by universal bound law

$$ \quad \equiv \neg q \text{ by (d)} $$

by negation law

Therefore, $(p \vee \neg q) \wedge (\neg p \vee \neg q) \equiv \neg q$.

Use Theorem 2.1.1 to verify the logical equivalences in 50-54. Supply a reason
for each step.

50. $(p \wedge \neg q) \vee p \equiv p$

$$ (p \wedge \neg q) \vee p \equiv p $$

$$ p \vee (p \wedge \neg q) \equiv p \text{ by communative law for } \vee $$

$$ \equiv p \text{ by the absorption law for } \vee \text{ with } \neg q \text{ replacing } q $$

51. $p \wedge (\neg q \vee p) \equiv p$

$$ p \wedge (\neg q \vee p) \equiv p $$

$$ (p \wedge \neg q) \vee (p \wedge p) \equiv p \text{ by distributive law for } \wedge $$

$$ (p \wedge \neg q) \vee p \equiv p \text{ by idempotent law for } \wedge $$

$$ p \vee (p \wedge \neg q) \equiv p \text{ by commutative law for } \vee $$

$$ \equiv p \text{ by absorption law for } \vee \text{ with } \neg q \text{ replacing } q $$

52. $\neg(p \vee \neg q) \vee (\neg p \wedge \neg q) \equiv \neg p$

$$ \neg(p \vee \neg q) \vee (\neg p \wedge \neg q) \equiv \neg p $$

$$ (\neg p \wedge q) \vee (\neg p \wedge \neg q) \equiv \neg p \text{ by De Morgan's law for } \vee $$

$$ \neg p \wedge (q \vee \neg q) \equiv \neg p \text{ by distributive law for } \wedge $$

$$ \neg p \wedge \mathbf{t} \equiv \neg p \text{ by negation law for } \vee $$

$$ \neg p \equiv \neg p \text{ by identity law for } \wedge $$

53. $\neg((\neg p \wedge q) \vee (\neg p \wedge \neg q)) \vee (p \wedge q) \equiv p$

$$ \neg((\neg p \wedge q) \vee (\neg p \wedge \neg q)) \vee (p \wedge q) \equiv p $$

$$ (\neg(\neg p \wedge q) \wedge \neg(\neg p \wedge \neg q)) \vee (p \wedge q) \equiv p \text{ by De Morgan's law for } \vee $$

$$ ((p \vee \neg q) \wedge (p \vee q)) \vee (p \wedge q) \equiv p \text{ by De Morgan's law for } \wedge $$

$$ (p \vee (\neg q \wedge q)) \vee (p \wedge q) \equiv p \text{ by distributive law for } \vee $$

$$ (p \vee \mathbf{c}) \vee (p \wedge q) \equiv p \text{ by negation law for } \wedge $$

$$ p \vee (p \wedge q) \equiv p \text{ by identity law for } \vee $$

$$ p \equiv p \text{ by absorption law for } \vee $$

54. $(p \wedge (\neg(\neg p \vee q))) \vee (p \wedge q) \equiv p$

$$ (p \wedge (\neg(\neg p \vee q))) \vee (p \wedge q) \equiv p $$

$$ (p \wedge (p \wedge \neg q)) \vee (p \wedge q) \equiv p \text{ by De Morgan's law for } \vee $$

$$ ((p \wedge p) \wedge \neg q) \vee (p \wedge q) \equiv p \text{ by associative law for } \wedge $$

$$ (p \wedge \neg q) \vee (p \wedge q) \equiv p \text{ by idempotent law for } \wedge $$

$$ p \wedge (\neg q \vee q) \equiv p \text{ by distributive law for } \wedge $$

$$ p \wedge \mathbf{t} \equiv p \text{ by negation law for } \vee $$

$$ p \equiv p \text{ by identity law for } \wedge $$
