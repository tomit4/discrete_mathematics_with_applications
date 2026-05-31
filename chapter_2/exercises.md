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

$$ p \vee (p \wedge \neg q) \equiv p \text{ by commutative law for } \vee $$

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

---

**Exercise Set 2.2**

Page 86

Rewrite the statements in 1-4 in if-then form.

1. This loop will repeat exactly $n$ times if it does not contain a **stop** or
   a **go to**.

"If this lop does not contain a **stop** or a **go to**, then it will repeat
exactly $N$ times."

2. I am on time for work if I catch the 8:05 bus.

"If I catch the 8:05 bus, then I am on time for work."

3. Freeze or I'll shoot.

"If you do not freeze, then I'll shoot."

4. Fix my ceiling or I won't pay my rent.

"If you do not fix my ceiling, then I won't pay my rent."

Construct truth tables for the statements forms in 5-11.

5. $\neg p \vee q \to \neg q$

| $p$ | $q$ | $\neg p$ | $\neg q$ | $\neg p \vee q$ | $\neg p \vee q \to \neg q$ |
| --- | --- | -------- | -------- | --------------- | -------------------------- |
| T   | T   | F        | F        | T               | F                          |
| T   | F   | F        | T        | F               | T                          |
| F   | T   | T        | F        | T               | F                          |
| F   | F   | T        | T        | T               | T                          |

6. $(p \vee q) \vee (\neg p \wedge q) \to q$

| $p$ | $q$ | $\neg p$ | $(p \vee q)$ | $(\neg p \wedge q)$ | $(p \vee q) \vee (\neg p \wedge q)$ | $(p \vee q) \vee (\neg p \wedge q) \to q$ |
| --- | --- | -------- | ------------ | ------------------- | ----------------------------------- | ----------------------------------------- |
| T   | T   | F        | T            | F                   | T                                   | T                                         |
| T   | F   | F        | T            | F                   | T                                   | F                                         |
| F   | T   | T        | T            | T                   | T                                   | T                                         |
| F   | F   | T        | F            | F                   | F                                   | T                                         |

7. $p \wedge \neg q \to r$

| $p$ | $q$ | $r$ | $\neg q$ | $p \wedge \neg q$ | $p \wedge \neg q \to r$ |
| --- | --- | --- | -------- | ----------------- | ----------------------- |
| T   | T   | T   | F        | F                 | T                       |
| T   | T   | F   | F        | F                 | T                       |
| T   | F   | T   | T        | T                 | T                       |
| T   | F   | F   | T        | T                 | F                       |
| F   | T   | T   | F        | F                 | T                       |
| F   | T   | F   | F        | F                 | T                       |
| F   | F   | T   | T        | F                 | T                       |
| F   | F   | F   | T        | F                 | T                       |

8. $\neg p \vee q \to r$

| $p$ | $q$ | $r$ | $\neg p$ | $\neg p \vee q$ | $\neg p \vee q \to r$ |
| --- | --- | --- | -------- | --------------- | --------------------- |
| T   | T   | T   | F        | T               | T                     |
| T   | T   | F   | F        | T               | F                     |
| T   | F   | T   | F        | F               | T                     |
| T   | F   | F   | F        | F               | T                     |
| F   | T   | T   | T        | T               | T                     |
| F   | T   | F   | T        | T               | F                     |
| F   | F   | T   | T        | T               | T                     |
| F   | F   | F   | T        | T               | F                     |

9. $p \wedge \neg r \leftrightarrow q \vee r$

| $p$ | $q$ | $r$ | $\neg r$ | $p \wedge \neg r$ | $q \vee r$ | $p \wedge \neg r \leftrightarrow q \vee r$ |
| --- | --- | --- | -------- | ----------------- | ---------- | ------------------------------------------ |
| T   | T   | T   | F        | F                 | T          | F                                          |
| T   | T   | F   | T        | T                 | T          | T                                          |
| T   | F   | T   | F        | F                 | T          | F                                          |
| T   | F   | F   | T        | T                 | F          | F                                          |
| F   | T   | T   | F        | F                 | T          | F                                          |
| F   | T   | F   | T        | F                 | T          | F                                          |
| F   | F   | T   | F        | F                 | T          | F                                          |
| F   | F   | F   | T        | F                 | F          | T                                          |

10. $(p \to r) \leftrightarrow (q \to r)$

| $p$ | $q$ | $r$ | $(p \to r)$ | $(q \to r)$ | $(p \to r) \leftrightarrow (q \to r)$ |
| --- | --- | --- | ----------- | ----------- | ------------------------------------- |
| T   | T   | T   | T           | T           | T                                     |
| T   | T   | F   | F           | F           | T                                     |
| T   | F   | T   | T           | T           | T                                     |
| T   | F   | F   | F           | T           | F                                     |
| F   | T   | T   | T           | T           | T                                     |
| F   | T   | F   | T           | F           | F                                     |
| F   | F   | T   | T           | T           | T                                     |
| F   | F   | F   | T           | T           | T                                     |

11. $(p \to (q \to r)) \leftrightarrow ((p \wedge q) \to r)$

| $p$ | $q$ | $r$ | $(q \to r)$ | $(p \wedge q)$ | $(p \to (q \to r))$ | $((p \wedge q) \to r)$ | $(p \to (q \to r)) \leftrightarrow ((p \wedge q) \to r)$ |
| --- | --- | --- | ----------- | -------------- | ------------------- | ---------------------- | -------------------------------------------------------- |
| T   | T   | T   | T           | T              | T                   | T                      | T                                                        |
| T   | T   | F   | F           | T              | F                   | F                      | T                                                        |
| T   | F   | T   | T           | F              | T                   | T                      | T                                                        |
| T   | F   | F   | T           | F              | T                   | T                      | T                                                        |
| F   | T   | T   | T           | F              | T                   | T                      | T                                                        |
| F   | T   | F   | F           | F              | T                   | T                      | T                                                        |
| F   | F   | T   | T           | F              | T                   | T                      | T                                                        |
| F   | F   | F   | T           | F              | T                   | T                      | T                                                        |

12. Use the logical equivalence established in Example 2.2.3,
    $p \vee q \to r \equiv (p \to r) \wedge (q \to r)$, to rewrite the following
    statement. (Assume that $x$ represents a fixed real number.)

If $x > 2 $ or $x < -2$, then $x^2 > 4$.

If $x > 2$, then $x^2 > 4$ and if $x < -2$, then $x^2 > 4$.

13. Use truth tables to verify the following logical equivalences. Include a few
    words of explanation with your answers.

a. $p \to q \equiv \neg p \vee q$

| $p$ | $q$ | $\neg p$ | $p \to q$ | $\neg p \vee q$ |
| --- | --- | -------- | --------- | --------------- |
| T   | T   | F        | T         | T               |
| T   | F   | F        | F         | F               |
| F   | T   | T        | T         | T               |
| F   | F   | T        | T         | T               |

Both columns for $p \to q$ and $\neg p \vee q$ have the same truth values, so
they are logically equivalent.

b. $\neg(p \to q) \equiv p \wedge \neg q$

| $p$ | $q$ | $\neg q$ | $(p \to q)$ | $\neg(p \to q)$ | $p \wedge \neg q$ |
| --- | --- | -------- | ----------- | --------------- | ----------------- |
| T   | T   | F        | T           | F               | F                 |
| T   | F   | T        | F           | T               | T                 |
| F   | T   | F        | T           | F               | F                 |
| F   | F   | T        | T           | F               | F                 |

Both columns for $\neg(p \to q)$ and $p \wedge \neg q$ have the same truth
values, so they are logically equivalent.

14.

a. Show that the following statement forms are all logically equivalent:

$p \to (q \vee r)$, $(p \wedge \neg q) \to r$, and $(p \wedge \neg r) \to q$

| $p$ | $q$ | $r$ | $\neg q$ | $\neg r$ | $(q \vee r)$ | $(p \wedge \neg q)$ | $(p \wedge \neg r)$ | $p \to (q \vee r)$ | $(p \wedge \neg q) \to r$ | $(p \wedge \neg r) \to q$ |
| --- | --- | --- | -------- | -------- | ------------ | ------------------- | ------------------- | ------------------ | ------------------------- | ------------------------- |
| T   | T   | T   | F        | F        | T            | F                   | F                   | T                  | T                         | T                         |
| T   | T   | F   | F        | T        | T            | F                   | T                   | T                  | T                         | T                         |
| T   | F   | T   | T        | F        | T            | T                   | F                   | T                  | T                         | T                         |
| T   | F   | F   | T        | T        | F            | T                   | T                   | F                  | F                         | F                         |
| F   | T   | T   | F        | F        | T            | F                   | F                   | T                  | T                         | T                         |
| F   | T   | F   | F        | T        | T            | F                   | F                   | T                  | T                         | T                         |
| F   | F   | T   | T        | F        | T            | F                   | F                   | T                  | T                         | T                         |
| F   | F   | F   | T        | T        | F            | F                   | F                   | T                  | T                         | T                         |

b. Use the logical equivalences established in part (a) to rewrite the following
sentence in two different ways. (Assume that $n$ represents a fixed integer.)

If $n$ is prime, then $n$ is odd or $n$ is $2$.

"If $n$ is prime and $n$ is not odd then $n$ is $2$"

"If $n$ is prime and $n$ is not $2$, then $n$ is odd."

15. Determine whether the following statement forms are logically equivalent:

$p \to (q \to r)$ and $(p \to q) \to r$

| $p$ | $q$ | $r$ | $(q \to r)$ | $(p \to q)$ | $p \to (q \to r)$ | $(p \to q) \to r$ |
| --- | --- | --- | ----------- | ----------- | ----------------- | ----------------- |
| T   | T   | T   | T           | T           | T                 | T                 |
| T   | T   | F   | F           | F           | F                 | T                 |
| T   | F   | T   | T           | T           | T                 | T                 |
| T   | F   | F   | T           | F           | T                 | T                 |
| F   | T   | T   | T           | T           | T                 | T                 |
| F   | T   | F   | F           | T           | T                 | F                 |
| F   | F   | T   | T           | T           | T                 | T                 |
| F   | F   | F   | T           | T           | T                 | F                 |

No, they are not equivalent, $p \to (q \to r) \cancel{\equiv} (p \to q) \to r$
as their truth values are not the same.

In 16 and 17, write each of the two statements in symbolic form and determine
whether they are logically equivalent. Include a truth table and a few words of
explanation to show that you understand what it means for statements to be
logically equivalent.

16. If you paid full price, you didn't buy it at Crown Books. You didn't buy it
    at Crown Books or you paid full price.

$p$ is "You paid full price"

$q$ is "You bought it at Crown Books"

$$ p \to \neg q \text{ and } \neg q \vee p $$

| $p$ | $q$ | $\neg q$ | $p \to \neg q$ | $\neg q \vee p$ |
| --- | --- | -------- | -------------- | --------------- |
| T   | T   | F        | F              | T               |
| T   | F   | T        | T              | T               |
| F   | T   | F        | T              | F               |
| F   | F   | T        | T              | T               |

No, these two statements are not logically equivalent as their truth tables do
not have the same truth values.

$$ p \to \neg q \cancel{\equiv} \neg q \vee p $$

One could not buy it at Crown Books, and not paid full price, and also one could
have paid full price and have also bought it at Crown books.

17. If $2$ is a factor of $n$ and $3$ is a factor of $n$, then $6$ is a factor
    of $n$. $2$ is not a factor of $n$ or $3$ is not a factor of $n$ or $6$ is a
    factor of $n$.

$p$ is "$2$ is a factor of $n$"

$q$ is "$3$ is a factor of $n$"

$r$ is "$6$ is a factor of $n$"

$$ p \wedge q \to r\text{ and } \neg p \vee \neg q \vee r $$

| $p$ | $q$ | $r$ | $\neg p$ | $\neg q$ | $p \wedge q$ | $\neg p \vee \neg q$ | $p \wedge q \to r$ | $\neg p \vee \neg q \vee r$ |
| --- | --- | --- | -------- | -------- | ------------ | -------------------- | ------------------ | --------------------------- |
| T   | T   | T   | F        | F        | T            | F                    | T                  | T                           |
| T   | T   | F   | F        | F        | T            | F                    | F                  | F                           |
| T   | F   | T   | F        | T        | F            | T                    | T                  | T                           |
| T   | F   | F   | F        | T        | F            | T                    | T                  | T                           |
| F   | T   | T   | T        | F        | F            | T                    | T                  | T                           |
| F   | T   | F   | T        | F        | F            | T                    | T                  | T                           |
| F   | F   | T   | T        | T        | F            | T                    | T                  | T                           |
| F   | F   | F   | T        | T        | F            | T                    | T                  | T                           |

Yes, they are equivalent, as their truth tables show the same truth values.

$$ p \wedge q \to r \equiv \neg p \vee \neg q \vee r $$

18. Write each of the following three statements in symbolic form and determine
    which pairs are logically equivalent. Include truth tables and a few words
    of explanation.

$p$ = "It walks like a duck"

$q$ = "It talks like a duck"

$r$ = "It is a duck"

If it walks like a duck and it talks like a duck, then it is a duck.

$$ p \wedge q \to r $$

Either it does not walk like a duck or it does not talk like a duck, or it is a
duck.

$$ p \vee \neg q \vee r $$

If it does not walk like a duck and it does not talk like a duck, then it is not
a duck.

$$ \neg p \wedge \neg q \to \neg r $$

| $p$ | $q$ | $r$ | $\neg p$ | $\neg q$ | $\neg r$ | $p \wedge q$ | $p \vee \neg q$ | $\neg p \wedge \neg q$ | $p \wedge q \to r$ | $p \vee \neg q \vee r$ | $\neg p \wedge \neg q \to \neg r$ |
| --- | --- | --- | -------- | -------- | -------- | ------------ | --------------- | ---------------------- | ------------------ | ---------------------- | --------------------------------- |
| T   | T   | T   | F        | F        | F        | T            | T               | F                      | T                  | T                      | T                                 |
| T   | T   | F   | F        | F        | T        | T            | T               | F                      | F                  | T                      | T                                 |
| T   | F   | T   | F        | T        | F        | F            | T               | F                      | T                  | T                      | T                                 |
| T   | F   | F   | F        | T        | T        | F            | T               | F                      | T                  | T                      | T                                 |
| F   | T   | T   | T        | F        | F        | F            | F               | F                      | T                  | T                      | T                                 |
| F   | T   | F   | T        | F        | T        | F            | F               | F                      | T                  | F                      | T                                 |
| F   | F   | T   | T        | T        | F        | F            | T               | T                      | T                  | T                      | F                                 |
| F   | F   | F   | T        | T        | T        | F            | T               | T                      | T                  | T                      | T                                 |

No, none of these statements are equivalent, as you can see in their
corresponding truth table's truth values.

$$ p \wedge q \to r \cancel{\equiv} p \vee \neg q \vee r \cancel{\equiv} \neg p \wedge \neg q \to \neg r $$

19. True or false? The negation of "If Sue is Luiz's mother, then Ali is his
    cousin" is "If Sue is Luiz's mother, then Ali is not his cousin."

$p$ = "Sue is Luiz's mother"

$q$ = "Ali is his cousin"

Firs statement is:

$$ p \to q $$

Negation is:

$$ p \wedge \neg q $$

"Sue is Luiz's mother and Ali is not his cousin."

Second statement is:

$$ p \to \neg q $$

Negation is:

$$ p \to q $$

"If Sue is Luiz's mother, then Ali is his cousin."

So no, they are not equivalent:

$$ p \wedge \neg q \cancel{\equiv} p \wedge q $$

20. Write negations for each of the following statements. (Assume that all
    variables represent fixed quantities or entities, as appropriate.)

a. If $P$ is a square, then $P$ is a rectangle.

$$ p \to q $$

Negation:

$$ p \wedge \neg q $$

"P is a square and P is not a rectangle."

b. If today is New Year's Eve, then tomorrow is January.

$$ p \to q $$

$$ p \wedge \neg q $$

"Today is New Year's Eve and tomorrow is not January."

c. If the decimal expansion of $r$ is terminating, then $r$ is rational.

"The decimal expansion of $r$ is terminating and $r$ is not rational."

d. If $n$ is prime, then $n$ is odd or $n$ is $2$.

$n$ is prime and $n$ is not odd and $n$ is not $2$.

e. If $x$ is nonnegative, then $x$ is positive or $x$ is $0$.

$x$ is nonnegative and $x$ is both negative and not $0$.

f. If Tom is Ann's father, then Jim is her uncle and Sue is her aunt.

Tom is Ann's father and either Jim is not her uncle or Sue is not her aunt.

g. If $n$ is divisible by $6$, then $n$ is divisible by $2$ and $n$ is divisible
by $3$.

$n$ is divisible by $6$ and either $n$ is not divisible by $2$ or $n$ is not
divisible by $3$.

21. Suppose that $p$ and $q$ are statements so that $p \to q$ is false. Find the
    truth values of each of the following.

| $p$ | $q$ | $p \to q$ |
| --- | --- | --------- |
| T   | T   | T         |
| T   | F   | F         |
| F   | T   | T         |
| F   | F   | T         |

This means that $p = T$ and $q = F$.

a. $\neg p \to q$

$$ F \to F = T $$

b. $p \vee q$

$$ T \vee F = T $$

c. $q \to p$

$$ F \to T = T $$

22. Write contrapositives for the statements of exercise 20.

a. $\neg p \to q$

$$ \neg q \to p $$

b. $p \vee q$

$$ \neg q \to p $$

c. $q \to p$

$$ \neg p \to \neg q $$

23. Write the converse and inverse for each statement of exercise 20.

a. $\neg p \to q$

Converse:

$$ q \to \neg p $$

Inverse:

$$ p \to \neg q $$

b. $p \vee q$

Because the contrapositive is equivalent, we can take:

$$ \neg q \to p $$

Converse:

$$ p \to \neg q $$

Inverse:

$$ q \to \neg p $$

c. $q \to p$

Converse:

$$ p \to q $$

Inverse:

$$ \neg q \to \neg p $$

Use truth tables to establish the truth of each statement in 24-27.

24. A conditional statement is not logically equivalent to its converse.

| $p$ | $q$ | $p \to q$ | $q \to p$ |
| --- | --- | --------- | --------- |
| T   | T   | T         | T         |
| T   | F   | F         | T         |
| F   | T   | T         | F         |
| F   | F   | T         | T         |

As you can see $p \to q \cancel{\equiv} q \to p$, so a conditional statement is
not equivalent to its converse.

25. A conditional statement is not logically equivalent to its inverse.

| $p$ | $q$ | $\neg p$ | $\neg q$ | $p \to q$ | $\neg p \to \neg q$ |
| --- | --- | -------- | -------- | --------- | ------------------- |
| T   | T   | F        | F        | T         | T                   |
| T   | F   | F        | T        | F         | T                   |
| F   | T   | T        | F        | T         | F                   |
| F   | F   | T        | T        | T         | T                   |

As you can see $p \to q \cancel{\equiv} \neg p \to \neg q$, so a conditional
statement is not equivalent to its inverse.

26. A conditional statement and its contrapositive are logically equivalent to
    each other.

| $p$ | $q$ | $\neg q$ | $\neg p$ | $p \to q$ | $\neg q \to \neg p$ |
| --- | --- | -------- | -------- | --------- | ------------------- |
| T   | T   | F        | F        | T         | T                   |
| T   | F   | T        | F        | F         | F                   |
| F   | T   | F        | T        | T         | T                   |
| F   | F   | T        | T        | T         | T                   |

As you can see $p \to q \equiv \neg q \to \neg p$, so a conditional statement is
logically equivalent to it's contrapositive.

27. The converse and inverse of a conditional statement are logically equivalent
    to each other.

| $p$ | $q$ | $p \to q$ | $q \to p$ | $\neg p \to \neg q$ |
| --- | --- | --------- | --------- | ------------------- |
| T   | T   | T         | T         | T                   |
| T   | F   | F         | T         | T                   |
| F   | T   | T         | F         | F                   |
| F   | F   | T         | T         | T                   |

As you can see, $q \to p \equiv \neg p \to \neg q$, so the converse and the
inverse of a conditional statement are logically equivalent to each other.

28. "Do you mean that you think you can find out the answer to it?" said the
    March Hare.

"Exactly so," said Alice.

"Then you should say what you mean," the March Hare went on.

"I do," Alice hastily replied; "at least-at least I mean what I say-that's the
same thing, you know."

"Not the same thing a bit!" said the Hatter.

"Why, you might just as well say that 'I see what I eat' is the same thing as 'I
eat what I see'!"

-from "A Mad Tea-Party" in _Alice in Wonderland_, by Lewis Carroll

The Hatter is right. "I say what I mean" is not the same thing as "I mean what I
say." Rewrite each of these two sentences in if-then form and explain the
logical relation between them. (This exercise is referred to in the introduction
to Chapter 4.)

$$ p \to q $$

$$ q \to p $$

| $p$ | $q$ | $p \to q$ | $q \to p$ |
| --- | --- | --------- | --------- |
| T   | T   | T         | T         |
| T   | F   | F         | T         |
| F   | T   | T         | F         |
| F   | F   | T         | T         |

You can also rewrite this as "If I say something, I mean it." and "If I mean it,
I say something." Even from a linguistic standpoint these are not the same
statements. One can "mean it" (be sincere) and never say something, for example.

If statement forms $P$ and $Q$ are logically equivalent, then
$P \leftrightarrow Q$ is a tautology. Conversely, if $P \leftrightarrow Q$ is a
tautology, then $P$ and $Q$ are logically equivalent. Use $\leftrightarrow$ to
convert each of the logical equivalences in 29-31 to a tautology. Then use a
truth table to verify each tautology.

29. $p \to (q \vee r) \equiv (p \wedge \neg q) \to r$

$$ (p \to (q \vee r)) \leftrightarrow (p \wedge \neg q \to r) $$

| $p$ | $q$ | $r$ | $\neg q$ | $(q \vee r)$ | $(p \wedge \neg q)$ | $p \to (q \vee r)$ | $(p \wedge \neg q) \to r$ |
| --- | --- | --- | -------- | ------------ | ------------------- | ------------------ | ------------------------- |
| T   | T   | T   | F        | T            | F                   | T                  | T                         |
| T   | T   | F   | F        | T            | F                   | T                  | T                         |
| T   | F   | T   | T        | T            | T                   | T                  | T                         |
| T   | F   | F   | T        | F            | T                   | F                  | F                         |
| F   | T   | T   | F        | T            | F                   | T                  | T                         |
| F   | T   | F   | F        | T            | F                   | T                  | T                         |
| F   | F   | T   | T        | T            | F                   | T                  | T                         |
| F   | F   | F   | T        | F            | F                   | T                  | T                         |

30. $p \wedge (q \vee r) \equiv (p \wedge q) \vee (p \wedge r)$

$$ (p \wedge (q \vee r)) \leftrightarrow ((p \wedge q) \vee (p \wedge r)) $$

| $p$ | $q$ | $r$ | $(q \vee r)$ | $(p \wedge q)$ | $(p \wedge r)$ | $(p \wedge (q \vee r))$ | $((p \wedge q) \vee (p \wedge r) \)$ |
| --- | --- | --- | ------------ | -------------- | -------------- | ----------------------- | ------------------------------------ |
| T   | T   | T   | T            | T              | T              | T                       | T                                    |
| T   | T   | F   | T            | T              | F              | T                       | T                                    |
| T   | F   | T   | T            | F              | T              | T                       | T                                    |
| T   | F   | F   | F            | F              | F              | F                       | F                                    |
| F   | T   | T   | T            | F              | F              | F                       | F                                    |
| F   | T   | F   | T            | F              | F              | F                       | F                                    |
| F   | F   | T   | T            | F              | F              | F                       | F                                    |
| F   | F   | F   | F            | F              | F              | F                       | F                                    |

31. $p \to (q \to r) \equiv (p \wedge q) \to r$

$$ p \to (q \to r) \leftrightarrow (p \wedge q) \to r $$

| $p$ | $q$ | $r$ | $(q \to r)$ | $(p \wedge q)$ | $p \to (q \to r)$ | $(p \wedge q) \to r$ |
| --- | --- | --- | ----------- | -------------- | ----------------- | -------------------- |
| T   | T   | T   | T           | T              | T                 | T                    |
| T   | T   | F   | F           | T              | F                 | F                    |
| T   | F   | T   | T           | F              | T                 | T                    |
| T   | F   | F   | T           | F              | T                 | T                    |
| F   | T   | T   | T           | F              | T                 | T                    |
| F   | T   | F   | F           | F              | T                 | T                    |
| F   | F   | T   | T           | F              | T                 | T                    |
| F   | F   | F   | T           | F              | T                 | T                    |

Rewrite each of the statements in 32 and 33 as a conjunction of two if-then
statements.

32. This quadratic equation has two distinct real roots if, and only if, its
    discriminant is greater than zero.

"If this quadratic equation has two distinct real roots, then it's discriminant
is greater than zero and if this quadratic equation's discriminant is greater
than zero, then it has two distinct real roots."

33. This integer is even if, and only if, it equals twice some integer.

"If this integer is even, then it equals twice some integer and if this integer
is equal to twice some integer, then it is even."

Rewrite the statements in 34 and 35 in if-then form in two ways, one of which is
the contrapositive of the other. Use the formal definition of "only if."

34. The Cubs will win the pennant only if they win tomorrow's game.

Contrapositive:

"If the Cubs have not won tomorrow's game, then they will not win the pennant."

Only-if:

"If the Cub's won the pennant, then they will have won tomorrow's game."

35. Sam will be allowed on Signe's racing boat only if he is an expert sailor.

Contrapositive:

"If Sam is not an expert sailor, then he will not be allowed on Sign'es racing
boat."

Only-if:

"If Sam was allowed on Signe's racing boat, then he was an expert sailor."

36. Taking the long view on your education, you go to the Prestige Corporation
    and ask what you should do in college to be hired when you graduate. The
    personnel director replies that you will be hired _only if_ you major in
    mathematics or computer science, get a B average or better, and take
    accounting. You do, in fact, become a math major, get a B+ average, and take
    accounting. You return to Prestige Corporation, make a formal application,
    and are turned down. Did the personnel director lie to you?

No, because "only if" means that the conditions have already been met, not
conditions that have yet to be met. Because you "become a math major", "get a B+
average", and "take accounting", you have not fulfilled the director's
requirements, which is that "You _have_ majored in mathematics or computer
science, you have a B average or better, and you have taken accounting."

Some programming languages use statements of the form "$r$ unless $s$" to mean
that as long as $s$ does not happen, then $r$ will happen. More formally:

**Definition:**

If $r$ and $s$ are statements,

**$r$ unless $s$** means if $\neg s$ then $r$.

In 37-39 rewrite the statements in if-then form.

37. Payment will be made on fifth unless a new hearing is granted.

"If a new hearing is not granted, then payment will be made on the fifth."

38. Ann will go unless it rains.

"If it does not rain, then Ann will go."

39. This door will not open unless a security code is entered.

"If a security code is not entered, then this door will not open."

Rewrite the statements in 40 and 41 in if-then form.

40. Catching the 8:05 bus is a sufficient condition for my being on time for
    work.

"If I catch the 8:05 bus, then I am on time for work."

41. Having two $45\degree$ angles is a sufficient condition for this triangle to
    be a right triangle.

"If I have two $45\degree$ angles, then this triangle is a right triangle."

Use the contrapositive to rewrite the statements in 42 and 43 in if-then form in
two ways.

42. Being divisible by $3$ is a necessary condition for this number to be
    divisible by $9$.

The statement is:

"If this number is not divisible by $3$, then this number is not divisible by
$9$."

The contrapositive is:

"If this number is divisible by $9$, then this number is divisible by $3$."

43. Doing homework regularly is a necessary condition for Jim to pass the
    course.

The statement is:

"If Jim does not do homework regularly, then Jim does not pass the course."

The contrapositive is:

"If Jim passed the course, then Jim did the homework."

Note that "a sufficient condition for $s$ is $r$" means $r$ is a sufficient
condition for $s$ and that "a necessary condition for $s$ is $r$" means $r$ is a
necessary condition for $s$. Rewrite the statements in 44 and 45 in if-then
form.

44. A sufficient condition for Jon's team to win the championship is that it win
    the rest of its games.

"If Jon's team wins the rest of its games, then it will win the championship."

45. A necessary condition for this computer program to be correct is that it not
    produce error messages during translation.

"If this computer program produces error messages during translation, then this
computer program is not correct."

46. "If compound X is boiling, then its temperature must be at least
    $150\degree$C." Assuming that this statement is true, which of the following
    must also be true?

$p$ = "Compound X is boiling"

$q$ = "Compound X's temperature is at least $150\degree$C"

a. If the temperature of compound X is at least $150\degree$C, then compound X
is boiling.

$$ q \to p $$

This is not equivalent to $p \to q$, so this is not necessarily true.

b. If the temperature of compound X is less than $150\degree$C, then compound X
is not boiling.

$$ \neg q \to \neg p $$

This is the contrapositive statement, and is logically equivalent to the
original statement. This is therefore true.

c. Compound X will boil only if its temperature is at least $150\degree$C.

"If Compound X is boiling, then its temperature is at least $150\degree$C."

This is the same statement as the original $p \to q$, so this is true.

d. If compound X is not boiling, then its temperature is less than
$150\degree$C.

$$ \neg p \to q $$

This is not related to the original statement be it by contrapositive, converse,
inverse, only-if, etc. So this is not true.

e. A necessary condition for compound X to boil is that its temperature be at
least $150\degree$C.

"If Compound X is not at a boil, then its temperature is not at least
$150\degree$C."

$$ \neg p \to \neg c $$

This is the inverse of the statement, and therefore not equivalent to the
original statement.

f. A sufficient condition for compound X to boil is that its temperature be at
least $150\degree$C.

"If Compound X is at a boil, then its temperature is at least $150\degree$C"

This statement is equivalent to the original, and so therefore is true.

In 47-50(a) use the logical equivalences $p \to q \equiv \neg p \vee q$ and
$p \leftrightarrow q \equiv (\neg p \vee q) \wedge (\neg q \vee p)$ to rewrite
the given statement forms without using the symbol $\to$ or $\leftrightarrow$,
and (b) use the logical equivalence $p \vee q \equiv \neg(\neg p \wedge \neg q)$
to rewrite each statement form using only $\wedge$ and $\neg$.

a.

$$ p \to q \equiv \neg p \vee q $$

$$ p \leftrightarrow q \equiv (\neg p \vee q) \wedge (\neg q \vee p) $$

Avoid $\to$ and $\leftrightarrow$.

b.

$$ p \vee q \equiv \neg(\neg p \wedge \neg q) $$

Only use $\wedge$ and $\neg$.

47. $p \wedge \neg q \to r$

a.

$$ (p \wedge \neg q) \to r \equiv \neg(p \wedge \neg q) \vee r $$

b.

$$ (p \wedge \neg q) \to r \equiv \neg(p \wedge \neg q) \vee r $$

$$ \neg\left[(p \wedge \neg q) \wedge \neg r \right] $$

48. $p \vee \neg q \to r \vee q$

a.

$$ p \vee \neg q \to r \vee q \equiv \neg(p \vee \neg q) \vee (r \vee q) $$

b.

$$ \neg(p \vee \neg q) \vee (r \vee q) $$

$$ \neg\left[\neg\neg(p \vee \neg q) \wedge \neg(r \vee q)\right] $$

$$ \neg\left[(p \vee \neg q) \wedge \neg(r \vee q)\right] $$

$$ \neg\left[(p \vee \neg q) \wedge (\neg r \wedge \neg q)\right] $$

$$ \neg\left[(\neg p \wedge  q) \wedge (\neg r \wedge \neg q)\right] $$

49. $(p \to r) \leftrightarrow (q \to r)$

a.

$$ (\neg(p \to r) \vee (q \to r)) \wedge (\neg(q \to r) \vee (p \to r)) $$

b.

$$ \neg(\neg\neg(p \to r) \wedge \neg(q \to r)) \wedge \neg(\neg\neg(q \to r) \wedge \neg(p \to r)) $$

$$ \neg((p \to r) \wedge \neg(q \to r)) \wedge \neg((q \to r) \wedge \neg(p \to r)) $$

50. $(p \to (q \to r)) \leftrightarrow ((p \wedge q) \to r)$

a.

$$ (\neg(p \to (q \to r)) \vee ((p \wedge q) \to r)) \wedge (\neg((p \wedge q) \to r) \vee (p \to (q \to r))) $$

$$ (\neg(\neg p \vee (q \to r)) \vee (\neg(p \wedge q) \vee r)) \wedge (\neg(\neg(p \wedge q) \vee r) \vee (\neg p \vee (q \to r))) $$

$$ (\neg(\neg p \vee (\neg q \vee r)) \vee (\neg(p \wedge q) \vee r)) \wedge (\neg(\neg(p \wedge q) \vee r) \vee (\neg p \vee (\neg q \vee r))) $$

b.

Stolen from Gemini (everything else done by hand so far, lol):

$$ \neg\left(\neg(p \wedge q \wedge \neg r) \wedge (p \wedge q \wedge \neg r)\right) \wedge \neg\left(\neg(p \wedge q \wedge \neg r) \wedge (p \wedge q \wedge \neg r)\right) $$

51. Given any statement form, is it possible to find a logically equivalent form
    that uses only $\neg$ and $\wedge$? Justify your answer.

Yes, we can always convert any statement form into a logically equivalent form
using other equivalency identities and De Morgan's laws. Consider:

$$ p \to q \equiv \neg p \vee q $$

Using De Morgan's Law we can then:

$$ p \to q \equiv \neg(\neg(\neg p) \wedge \neg q) $$

$$ p \to q \equiv \neg(p \wedge \neg q) $$

Now let's consider:

$$ p \leftrightarrow q \equiv (p \to q) \wedge (q \to p) $$

$$ p \leftrightarrow q \equiv \neg(p \wedge \neg q) \wedge \neg(q \wedge \neg p) $$

---

**Exercise Set 2.3**

Page 99

Use modus ponens or modus tollens to fill in the blanks in the arguments of 1-5
so as to produce valid inferences.

1.

If $\sqrt{2}$ is rational, then $\sqrt{2} = \dfrac{a}{b}$ for some integers $a$
and $b$.

It is not true that $\sqrt{2} = \dfrac{a}{b}$ for some integers $a$ and $b$.

$\therefore$ ______.

"$\sqrt{2}$ is not rational." (modus tollens)

2.

If $1 - 0.99999 \dots$ is less than every positive real number, then it equals
zero.

______.

"The number $1 - 0.99999 \dots$ is less than every positive real number." (modus
ponens)

$\therefore$ The number $1 - 0.99999 \dots$ equals zero.

3.

If logic is easy, then I am a monkey's uncle.

I am not a monkey's uncle.

$\therefore$ ______.

"Logic is not easy." (modus tollens)

4.

If this graph can be colored with three colors, then it can be colored with four
colors.

This graph cannot be colored with four colors.

$\therefore$ ______.

"This graph cannot be colored with three colors." (modus tollens)

5.

If they were unsure about the address, then they would have telephoned.

______.

$\therefore$ They were sure of the address.

"They did not telephone." (modus tollens)

Use truth tables to determine whether the argument forms in 6-11 are valid.
Indicate which columns represent the premises and which represent the
conclusion, and include a sentence explaining how the truth table supports your
answer. Your explanation should show that you understand what it means for a
form of argument to be valid or invalid.

6.

$$
p \to q \\
q \to p \\
\therefore p \vee q
$$

| $p$ | $q$ | $p \to q$ | $q \to p$ | $p \vee q$ |
| --- | --- | --------- | --------- | ---------- |
| T   | T   | T         | T         | T          |
| T   | F   | F         | T         | T          |
| F   | T   | T         | F         | T          |
| F   | F   | T         | T         | **F**      |

The last row shows that while it is possible to have all true premises, it is
also possible to have these premises arrive at a false conclusion, therefore
this argument form is invalid.

7.

$$
p \\
p \to q \\
\neg q \vee r \\
\therefore r
$$

| $p$ | $q$ | $r$ | $\neg q$ | $p \to q$ | $\neg q \vee r$ | $p$ | $r$   |
| --- | --- | --- | -------- | --------- | --------------- | --- | ----- |
| T   | T   | T   | F        | T         | T               | T   | **T** |
| T   | T   | F   | F        | T         | F               | T   | F     |
| T   | F   | T   | T        | F         | T               | T   | T     |
| T   | F   | F   | T        | F         | T               | T   | F     |
| F   | T   | T   | F        | T         | T               | F   | T     |
| F   | T   | F   | F        | T         | F               | F   | F     |
| F   | F   | T   | T        | T         | T               | F   | T     |
| F   | F   | F   | T        | T         | T               | F   | F     |

Here the only row where all the premises are true concludes with a true
consequent, therefore this argument form is valid.

8.

$$
p \vee q \\
p \to \neg q \\
p \to r \\
\therefore r
$$

| $p$ | $q$ | $r$ | $\neg q$ | $p \vee q$ | $p \to \neg q$ | $p \to r$ | $r$   |
| --- | --- | --- | -------- | ---------- | -------------- | --------- | ----- |
| T   | T   | T   | F        | T          | F              | T         | T     |
| T   | T   | F   | F        | T          | F              | F         | F     |
| T   | F   | T   | T        | T          | T              | T         | **T** |
| T   | F   | F   | T        | T          | T              | F         | F     |
| F   | T   | T   | F        | T          | T              | T         | **T** |
| F   | T   | F   | F        | T          | T              | T         | **F** |
| F   | F   | T   | T        | F          | T              | T         | T     |
| F   | F   | F   | T        | F          | T              | T         | F     |

On row 6, we see that we have all true premises that lead to a false conclusion,
therefore this argument form is invalid.

9.

$$
p \wedge q \to \neg r \\
p \vee \neg q \\
\neg q \to p \\
\therefore \neg r
$$

| $p$ | $q$ | $r$ | $\neg q$ | $\neg r$ | $p \wedge q$ | $p \wedge q \to \neg r$ | $p \vee \neg q$ | $\neg q \to p$ | $\neg r$ |
| --- | --- | --- | -------- | -------- | ------------ | ----------------------- | --------------- | -------------- | -------- |
| T   | T   | T   | F        | F        | T            | F                       | T               | T              | F        |
| T   | T   | F   | F        | T        | T            | T                       | T               | T              | **T**    |
| T   | F   | T   | T        | F        | F            | T                       | T               | T              | **F**    |
| T   | F   | F   | T        | T        | F            | T                       | T               | T              | **T**    |
| F   | T   | T   | F        | F        | F            | T                       | F               | T              | F        |
| F   | T   | F   | F        | T        | F            | T                       | F               | T              | T        |
| F   | F   | T   | T        | F        | F            | T                       | T               | F              | F        |
| F   | F   | F   | T        | T        | F            | T                       | T               | F              | T        |

On the third row, we see that we have all true premises that lead to a false
conclusion, therefore this argument form is invalid.

10.

$$
p \vee q \to r \\
\therefore \neg r \to \neg p \wedge \neg q
$$

(This is the form of argument shown on pages 37 and 38.)

| $p$ | $q$ | $r$ | $\neg p$ | $\neg q$ | $\neg r$ | $p \vee q$ | $\p \vee q \to r$ | $\neg p \wedge \neg q$ | $\neg r \to \neg p \wedge \neg q$ |
| --- | --- | --- | -------- | -------- | -------- | ---------- | ----------------- | ---------------------- | --------------------------------- |
| T   | T   | T   | F        | F        | F        | T          | T                 | F                      | **T**                             |
| T   | T   | F   | F        | F        | T        | T          | F                 | F                      | F                                 |
| T   | F   | T   | F        | T        | F        | T          | T                 | F                      | **T**                             |
| T   | F   | F   | F        | T        | T        | T          | F                 | F                      | F                                 |
| F   | T   | T   | T        | F        | F        | T          | T                 | F                      | **T**                             |
| F   | T   | F   | T        | F        | T        | T          | F                 | F                      | F                                 |
| F   | F   | T   | T        | T        | F        | F          | T                 | T                      | **T**                             |
| F   | F   | F   | T        | T        | T        | F          | T                 | T                      | **T**                             |

All rows where the argument $p \vee q \to r$ are true have true conclusions,
therefore this argument form is valid.

11.

$$
p \to q \vee r \\
\neg q \vee \neg r \\
\therefore \neg p \vee \neg r
$$

| $p$ | $q$ | $r$ | $\neg p$ | $\neg q$ | $\neg r$ | $q \vee r$ | $p \to q \vee r$ | $\neg q \vee \neg r$ | $\neg p \vee \neg r$ |
| --- | --- | --- | -------- | -------- | -------- | ---------- | ---------------- | -------------------- | -------------------- |
| T   | T   | T   | F        | F        | F        | T          | T                | F                    | F                    |
| T   | T   | F   | F        | F        | T        | T          | T                | T                    | **T**                |
| T   | F   | T   | F        | T        | F        | T          | T                | T                    | **F**                |
| T   | F   | F   | F        | T        | T        | F          | F                | T                    | T                    |
| F   | T   | T   | T        | F        | F        | T          | T                | F                    | T                    |
| F   | T   | F   | T        | F        | T        | T          | T                | T                    | **T**                |
| F   | F   | T   | T        | T        | F        | T          | T                | T                    | **T**                |
| F   | F   | F   | T        | T        | T        | F          | T                | T                    | **T**                |

On row three, we can see that there is a case where both precedents are true,
but the consequent is false, therefore this argument form is invalid.

12. Use truth tables to show that the following forms of argument are invalid.

a.

$$
p \to q \\
q \\
\therefore p \\
\text{converse error}
$$

| $p$ | $q$ | $p \to q$ | $q$ | $p$   |
| --- | --- | --------- | --- | ----- |
| T   | T   | T         | T   | **T** |
| T   | F   | F         | F   | T     |
| F   | T   | T         | T   | **F** |
| F   | F   | T         | F   | F     |

As you can see on row three, we have two hypotheses that are true, but the
conclusion is false, therefore this argument form is invalid.

b.

$$
p \to q \\
\neg p \\
\therefore \neg q \\
\text{inverse error}
$$

| $p$ | $q$ | $p \to q$ | $\neg p$ | $\neg q$ |
| --- | --- | --------- | -------- | -------- |
| T   | T   | T         | F        | F        |
| T   | F   | F         | F        | T        |
| F   | T   | T         | T        | **F**    |
| F   | F   | T         | T        | **T**    |

As you can see on row three, we have two hypotheses that are true, but the
conclusion is false, therefore this argument form is invalid.

Use truth tables to show that the argument forms referred to in 13-21 are valid.
Indicate which columns represent the premises and which represent the
conclusion, and include a sentence explaining how the truth table supports your
answer. Your explanation should show that you understand what it means for a
form of argument to be valid.

13. Modus tollens:

$$
p \to q \\
\neg q
\therefore \neg p
$$

| $p$ | $q$ | $p \to q$ | $\neg q$ | $\neg p$ |
| --- | --- | --------- | -------- | -------- |
| T   | T   | T         | F        | F        |
| T   | F   | F         | T        | F        |
| F   | T   | T         | F        | T        |
| F   | F   | T         | T        | **T**    |

The third column $p \to q$, and fourth column $\neg q$ are the premises. And the
final column $\neg p$ is the conclusion. Because all premises and the conclusion
are true, and there are no rows where all premises are true and the conclusion
is false, this argument form is valid.

14. Example 2.3.3(a)

$$
p \\
\therefore p \vee q
$$

| $p$ | $q$ | $p$ | $p \vee q$ |
| --- | --- | --- | ---------- |
| T   | T   | T   | **T**      |
| T   | F   | T   | **T**      |
| F   | T   | F   | T          |
| F   | F   | F   | F          |

The third column (copied from the first) is the first and only premise, $p$. The
fourth and final column is the consequent, $p \vee q$. Because both rows where
the premise is true (rows 1 and 2) return true conclusions, this argument form
is valid.

15. Example 2.3.3(b)

$$
q \\
\therefore p \vee q
$$

| $p$ | $q$ | $p \vee q$ |
| --- | --- | ---------- |
| T   | T   | **T**      |
| T   | F   | T          |
| F   | T   | **T**      |
| F   | F   | F          |

The second column is the first and only premise, $q$. The third and final column
is the consequent, $p \vee q$. Because both rows where the premise is true (rows
1 and 3) return true conclusions, this argument form is valid.

16. Example 2.3.4(a)

$$
p \wedge q \\
\therefore p
$$

| $p$ | $q$ | $p \wedge q$ | $p$   |
| --- | --- | ------------ | ----- |
| T   | T   | T            | **T** |
| T   | F   | F            | T     |
| F   | T   | F            | F     |
| F   | F   | F            | F     |

The third column is the only premise, $p \wedge q$. The fourth column is the
consequent $p$. The only row (row 1) where the premise is true, the conclusion
is also true, therefore this argument form is valid.

17. Example 2.3.4(b)

$$
p \wedge q \\
\therefore q
$$

| $p$ | $q$ | $p \wedge q$ | $q$   |
| --- | --- | ------------ | ----- |
| T   | T   | T            | **T** |
| T   | F   | F            | F     |
| F   | T   | F            | T     |
| F   | F   | F            | F     |

The third column is the only premise, $p \wedge q$. The fourth column is the
consequent $q$. The only row (row 1) where the premise is true, the conclusion
is also true, therefore this argument form is valid.

18. Example 2.3.5(a)

$$
p \vee q \\
\neg q \\
\therefore p
$$

| $p$ | $q$ | $p \vee q$ | $\neg q$ | $p$   |
| --- | --- | ---------- | -------- | ----- |
| T   | T   | T          | F        | T     |
| T   | F   | T          | T        | **T** |
| F   | T   | T          | F        | F     |
| F   | F   | F          | T        | F     |

The third and fourth rows are the premises, $p \vee q$ and $\neg q$
respectively. And the fifth row is the conclusion $p$. The only row where all
premises are true (row 2) returns a true conclusion, and therefore this argument
form is valid.

19. Example 2.3.5(b)

$$
p \vee q \\
\neg p \\
\therefore q
$$

| $p$ | $q$ | $p \vee q$ | $\neg q$ | $q$   |
| --- | --- | ---------- | -------- | ----- |
| T   | T   | T          | F        | T     |
| T   | F   | T          | F        | F     |
| F   | T   | T          | T        | **T** |
| F   | F   | F          | T        | F     |

The third and fourth rows are the premises, $p \vee q$ and $\neg p$
respectively. And the fifth row is the conclusion $q$. The only row where all
premises are true (row 3) returns a true conclusion, and therefore this argument
form is valid.

20. Example 2.3.6

$$
p \to q \\
q \to r \\
\therefore p \to r
$$

| $p$ | $q$ | $r$ | $p \to q$ | $q \to r$ | $p \to r$ |
| --- | --- | --- | --------- | --------- | --------- |
| T   | T   | T   | T         | T         | **T**     |
| T   | T   | F   | T         | F         | F         |
| T   | F   | T   | F         | T         | T         |
| T   | F   | F   | F         | T         | F         |
| F   | T   | T   | T         | T         | **T**     |
| F   | T   | F   | T         | F         | T         |
| F   | F   | T   | T         | T         | **T**     |
| F   | F   | F   | T         | T         | **T**     |

The fourth and fifth columns are the premises, $p \to q$ and $q \to r$
respectively. The sixth column is the conclusion, $p \to r$. The rows where both
premises are true (rows 1, 5, 7, 8) all have true conclusions, therefore this
argument form is valid.

21 Example 2.3.7

$$
p \vee q \\
p \to r \\
q \to r \\
\therefore r
$$

| $p$ | $q$ | $r$ | $p \vee q$ | $p \to r$ | $q \to r$ | $r$   |
| --- | --- | --- | ---------- | --------- | --------- | ----- |
| T   | T   | T   | T          | T         | T         | **T** |
| T   | T   | F   | T          | F         | F         | F     |
| T   | F   | T   | T          | T         | T         | **T** |
| T   | F   | F   | T          | F         | T         | F     |
| F   | T   | T   | T          | T         | T         | **T** |
| F   | T   | F   | T          | T         | F         | F     |
| F   | F   | T   | F          | T         | T         | T     |
| F   | F   | F   | F          | T         | T         | F     |

The fourth, fifth, and sixth columns are the precedents, $p \vee q$, $p \to r$,
and $q \to r$ respectively. The seventh column is the conclusion, $r$. The rows
where all three precedents are true (1, 3, 5) also have true conclusions, and
therefore this argument form is valid.

Use symbols to write the logical form of each argument in 22 and 23, and then
use a truth table to test the argument for validity. Indicate which columns
represent the premises and which represent the conclusion, and include a few
words of explanation showing that you understand the meaning of validity.

22.

If Tom is not on team $A$, then Hua is on team $B$.

If Hua is not on team $B$, then Tom is on team $A$.

$\therefore$ Tom is not on team $a$ or Hua is not on team $B$.

Let $p$ be "Tom is on team $A$."

Let $q$ "Hua is on team $B$."

Symbolically, the given statement is:

$$
\neg p \to q \\
\neg q \to p \\
\therefore \neg p \vee \neg q
$$

| $p$ | $q$ | $\neg p$ | $\neg q$ | $\neg p \to q$ | $\neg q \to p$ | $\neg p \vee \neg q$ |
| --- | --- | -------- | -------- | -------------- | -------------- | -------------------- |
| T   | T   | F        | F        | T              | T              | **F**                |
| T   | F   | F        | T        | T              | T              | **T**                |
| F   | T   | T        | F        | T              | T              | **T**                |
| F   | F   | T        | T        | F              | F              | T                    |

Rows 5 and 6 are the premises, $\neg p \to q$ and $\neg q \to p$ respectively.
The conclusion is the 7th column, $\neg p \vee \neg q$. In the first row, both
premises are true, but the conclusion is false, therefore this argument form is
invalid.

23.

Oleg is a math major or Oleg is an economics major.

If Oleg is a math major, then Oleg is required to take Math 362.

$\therefore$ Oleg is an economics major or Oleg is not required to take
Math 362.

Let $p$ be "Oleg is a math major."

Let $q$ be "Oleg is an economics major."

Let $r$ be "Oleg is required to take Math 362."

Symbolically, the given statement is:

$$
p \vee q \\
p \to r \\
\therefore q \vee \neg r
$$

| $p$ | $q$ | $r$ | $\neg r$ | $p \vee q$ | $p \to r$ | $q \vee \neg r$ |
| --- | --- | --- | -------- | ---------- | --------- | --------------- |
| T   | T   | T   | F        | T          | T         | **T**           |
| T   | T   | F   | T        | T          | F         | T               |
| T   | F   | T   | F        | T          | T         | **F**           |
| T   | F   | F   | T        | T          | F         | T               |
| F   | T   | T   | F        | T          | T         | **T**           |
| F   | T   | F   | T        | T          | T         | **T**           |
| F   | F   | T   | F        | F          | T         | F               |
| F   | F   | F   | T        | F          | T         | T               |

The 5th and 6th columns are the premises, $p \vee q$ and $p \to r$ respectively.
The 7th column is the conclusion, $q \vee \neg r$. On row 3, the two premises
are true but the conclusion is false, therefore this argument form is invalid.

Some of the arguments in 24-32 are valid, whereas others exhibit the converse or
the inverse error. Use symbols to write the logical form of each argument. If
the argument is valid, identify the rule of inference that guarantees its
validity. Otherwise, state whether the converse or the inverse error is made.

24.

If Jules solved this problem correctly, then Jules obtained the answer $2$.

Jules obtained the answer $2$.

$\therefore$ Jules solved this problem correctly.

Let $p$ be "Jules solved this problem correctly."

Let $q$ be "Jules obtained answer $2$."

Symbolically, the given statement is:

$$
p \to q \\
q \\
\therefore p
$$

Symbolically, this is exactly the converse error, and therefore is an invalid
argument form.

25.

This real number is rational or it is irrational.

This real number is not rational.

$\therefore$ This real number is irrational.

Let $p$ be "This real number is rational."

Let $q$ be "This real number is irrational."

Symbolically, our given statement is:

$$
p \vee q \\
\neg p \\
\therefore q
$$

This argument's form is valid by the rule of elimination.

26.

If I go to the movies, I won't finish my homework.

If i don't finish my homework, I won't do well on the exam tomorrow.

$\therefore$ If I go to the movies, I won't do well on the exam tomorrow.

Let $p$ be "I go to the movies."

Let $q$ be "I finish my homework."

Let $r$ be "I do well on the exam tomorrow."

Symbolically, the given statement is:

$$
p \to \neg q \\
\neg q \to \neg r \\
\therefore p \to \neg r
$$

This argument's form is valid by the rule of transitivity.

27.

If this number is larger than $2$, then its square is larger than $4$.

This number is not larger than $2$.

$\therefore$ The square of this number is not larger than $4$.

Let $p$ be "This number is larger than $2$a"

Let $q$ be "This number's square is larger than $4$."

Symbolically, the given statement is:

$$
p \to q \\
\neg p \\
\therefore \neg q
$$

This argument's form is invalid, as it demonstrates the inverse error.

28.

If there are as many rational numbers as there are irrational numbers, then the
set of all irrational numbers is infinite.

The set of all irrational numbers is infinite.

$\therefore$ There are as many rational numbers as there are irrational numbers.

Let $p$ be "There are as many rational numbers as there are irrational numbers."

Let $q$ be "The set of all irrational numbers is infinite."

Symbolically, the given statement is:

$$
p \to q \\
q \\
\therefore p
$$

This argument's form is invalid as it demonstrates a converse error.

29.

If at least one of these two numbers is divisible by $6$, then the product of
these two numbers is divisible by $6$.

Neither of these two numbers is divisible by $6$.

$\therefore$ The product of these two numbers is not divisible by $6$.

Let $p$ be "At least one of these two numbers is divisible by $6$."

Let $q$ be "The product of these two numbers is divisible by $6$."

Symbolically, this statement is:

$$
p \to q \\
\neg p \\
\therefore \neg q
$$

This argument's form is invalid as it demonstrates an inverse error.

30.

If this computer program is correct, then it produces the correct output when
run with the test data my teacher gave me.

This computer program produces the correct output when run with the test data my
teacher gave me.

$\therefore$ This computer program is correct.

Let $p$ be "This computer program is correct."

Let $q$ be "This computer program produces the correct output when run with the
test data my teacher gave me."

Symbolically, the given statement is:

$$
p \to q \\
q \\
\therefore p
$$

This argument form is invalid by the converse error.

31.

Sandra knows Java and Sandra knows C++.

$\therefore$ Sandra knows C++.

Let $p$ be "Sandra knows Java."

Let $q$ be "Sandra knows C++."

Symbolically, the given statement is:

$$
p \wedge q \\
\therefore q
$$

This argument's form is valid by the rule of specialization.

32.

If I get a Christmas bonus, I'll buy a stereo.

If I sell my motorcycle, I'll buy a stereo.

$\therefore$ If I get a Christmas bonus or I sell my motorcycle, then I'll buy a
stereo.

Let $p$ be "I get a Christmas bonus."

Let $r$ be "I buy a stereo."

Let $q$ be "I sell my motorcycle."

Symbolically, the given statement is:

$$
p \to r \\
q \to r \\
\therefore p \vee q \to r
$$

This argument form is valid by rule of transitivity.

33. Give an example (other than Example 2.3.11) of a valid argument with a false
    conclusion.

"If the sky is blue, then the ground is purple."

"The sky is blue."

$\therefore$ "The ground is purple."

34. Give an example (other than Example 2.3.12) of an invalid argument with a
    true conclusion.

"If the sky is blue, then the ground is purple."

"The ground is purple."

$\therefore$ "The sky is blue."

35. Explain in your own words what distinguishes a valid form of argument from
    an invalid one.

An argument is any statement or series of statements that are asserted to be
true, these statement(s) are known as the premises of the argument, while the
final statement of the argument is the conclusion. A valid argument is any
argument in which all instances where the premises are all true and the
conclusion is also true.

An invalid argument is any argument in which all instances where the premises
are true, there is one or more instances where the conclusion is false.

36. Given the following information about a computer program, find the mistake
    in the program.

a. There is an undeclared variable or there is a syntax error in the first five
lines.

b. If there is a syntax error in the first five lines, then there is a missing
semicolon or a variable name misspelled.

c. There is not a missing semicolon.

d. There is not a misspelled variable name.

Let $p$ be "There is an undeclared variable."

Let $q$ be "There is a syntax error in the first five lines."

Let $r$ be "There is a missing semicolon."

Let $s$ be "There is a variable name that is misspelled."

Symbolically:

$$
p \vee q \\
q \to r \vee s \\
\neg r \\
\neg s \\
\therefore p
$$

If we break this down logically, we can work backwards:

1.

$$
\neg s \\
\neg p \\
\therefore \neg r \wedge \neg s
$$

This is true by c and d, the definition of $\vee$, and De Morgan's laws.

2. Therefore $q$ cannot be true:

$$
q \to r \vee s \\
\neg r \wedge \neg s
\therefore \neg q
$$

This is true by b and the rule of modus tollens.

3. Therefore $p$ is true:

$$
p \vee q \\
\neg q \\
\therefore p
$$

This is true by a and thee rule of elimination. This leaves us to conclude that
"There is an undeclared variable."

37. In the back of an old cupboard you discover a note signed by a pirate famous
    for his bizarre sense of humor and love of logical puzzles. In the note he
    wrote that he had hidden treasure somewhere on the property. He listed five
    true statements (a-e below) and challenged the reader to use them to figure
    out the location of the treasure.

a. If this house is next to a lake, then the treasure is not in the kitchen.

b. If the tree in the front yard is an elm, then the treasure is in the kitchen.

c. This house is next to a lake.

d. The tree in the front yard is an elm or the treasure is buried under the
flagpole.

e. If the tree in the back yard is an oak, then the treasure is in the garage.

Where is the treasure hidden?

Let $p$ be "This house is next to a lake."

Let $q$ be "The treasure is in the kitchen."

Let $r$ be "The tree in the front yard is an elm."

Let $s$ be "The treasure is buried under the flagpole."

Let $t$ be "The tree in the back yard is an oak."

Let $u$ be "The treasure is in the garage."

Symbolically:

$$
p \to \neg q \\
r \to q \\
p \\
r \vee s \\
t \to u \\
\therefore \text{ ?}
$$

1. We can work this one through as soon as we have our first true assertion,
   which is our third assertion $p$. This is true by c.

$$ p $$

2.

$$
p \to \neg q \\
p
\therefore \neg q
$$

This is true by modus ponens.

3.

$$
r \to q \\
\neg q \\
\therefore \neg r
$$

This is true by modus tollens.

4.

$$
r \vee s \\
\neg r \\
\therefore s
$$

This is true by the rule of elimination. And we can actually stop here, as $s$
is "The treasure is buried under the flagpole."

Note however that if we were to go further and evaluate $t \to u$, we actually
cannot know if $t$ is true or not, as $\neg r \cancel{\to} t$, meaning that just
because the tree in the back yard is not an elm, it doesn't mean that the tree
in the back yard is an oak, that statement is never given to us in the problem
statement.

So once again, the answer is "The treasure is buried under the flagpole."

38. You are visiting the island described in Example 2.3.14 and have the
    following encounters with natives.

a. Two natives _A_ and _B_ address you as follows:

_A_ says: Both of us are knights.

_B_ says: _A_ is a knave.

What are _A_ and _B_?

Suppose that _A_ is a knight:

_A_ is a knight.

$\therefore$ Both _A_ and _B_ are knights.

Then _B_'s statement also is true:

_B_ is a knight.

$\therefore$ _A_ is a knave.

This is a contradiction, as "_A_ is a knave" contradicts "Both _A_ and _B_ are
knights."

Therefore _A_ must be a knave.

_A_ is a knave.

$\therefore$ Either _A_ or _B_ or both are knaves.

Then we test _B_'s statement:

_B_ is a knight.

$\therefore$ _A_ is a knave.

Which satisfies the conclusion from our evaluation of _A_'s statement, so
therefore _B_ is a knight.

_A_ is a knave, and _B_ is a knight.

b. Another two natives _C_ and _D_ approach you but only _C_ speaks.

_C_ says: Both of us are knaves.

What are _C_ and _D_?

Suppose _C_ is a knight.

_C_ is a knight

$\therefore$ Both _C_ and _D_ are knaves.

This is a contradiction as _C_ is assumed to be a knight, but claims both _C_
and _D_ are a knaves.

_C_ is a knave (by contradiction)

This means that either _C_ or _D_ or both are knaves (by negation of the
supposition and De Morgan's laws).

But, if both are knaves, then this validates _C_'s supposition, so it must be
that _D_ is a knight.

_D_ is a knight and _C_ is a knave.

c. You then encounter natives _E_ and _F_.

_E_ says: _F_ is a knave.

_F_ says: _E_ is a knave.

How many knaves are there?

Let's suppose _E_ is a knight:

_E_ is a knight.

$\therefore$ _F_ is a knave.

We then assert that _F_ is a knave by _E_'s supposition.

_F_ is a knave.

$\therefore$ _E_ is a knight by negation of _F_'s supposition.

Which validates our initial hypothesis.

Let's now hypothesize that _E_ is a knave:

_E_ is a knave.

$\therefore$ _F_ is a knight.

We then assert that _F_ is a knight by negation of _E_'s supposition.

_F_ is a knight.

$\therefore$ _E_ is a knave.

Which validates our secondary hypothesis.

This means we cannot conclude who is a knight and who is a knave, just that
there is a knave and a knight in this pair.

This is one knave.

d. Finally, you meet a group of six natives, _U_, _V_, _W_, _X_, _Y_, and _Z_,
who speak to you as follows:

_U_ says: None of us is a knight.

_V_ says: At least three of us are knights.

_W_ Says: At most three of us are knights.

_X_ says: Exactly five of us are knights.

_Y_ says: Exactly two of us are knights.

_Z_ says: Exactly one of us is a knight.

Which are knights and which are knaves?

Let's assume _U_ is a knight:

_U_ is a knight.

$\therefore$ None of us are knaves.

But this is a contradiction, because _U_ would also be a knave by his
supposition and that would contradict our assumption.

Therefore _U_ is a knave. That's one knave. Moving on...

Let's assume _V_ is a knight:

_V_ is a knight.

$\therefore$ At least three of us are knights.

We can move on and assume this so far.

Then we assume _W_ is a knight:

_W_ is a knight.

$\therefore$ At most three of us are knights.

Both _V_ and _W_ can only be knights if there are exactly three knights, which
the remaining statements by _X_, _Y_, and _Z_ all would contradict, and we know
_U_ is a knave, so either _V_ or _W_ is a knave or both of them are knaves.

Let's move on and assume that _X_ is a knight:

_X_ is a knight.

$\therefore$ Exactly five of us are knights.

But we already know that can't be true, because we have a total of 6 natives
here, and we know at least two of them are knaves (_U_ and either _V_ or _W_ or
both are knaves so far). So _X_ is a knave.

Moving on, let's assume _Y_ is a knight.

_Y_ is a knight.

$\therefore$ Exactly two of us are knights.

Nothing thus far contradicts this except for _V_'s supposition, therefore either
_V_ or _Y_ are knaves, but not both (one of them must be a knight).

Let's assume _Z_ is a knight.

_Z_ is a knight.

$\therefore$ Exactly one of us is a knight.

But we just established that either _V_ or _Y_ is a knave, but not both, this
contradicts _Z_'s supposition. _Z_ is a knave.

The only candidates left as knights or knaves are _V_, _W_, and _Y_.

Let's suppose that both _V_ and _W_ are knaves. This would mean that there would
be exactly three knights, which would work as that would make all _V_, _W_, and
_Y_ as knights...except that _Y_ claims there is exactly two knights, and that
would contradict our assumption.

Therefore either _V_ or _W_ is a knave, but not both.

If that's the case, then there are exactly two knights, and _Y_ is correct, _Y_
is a knight.

And for _Y_ to be a knight, _V_ must be a knave, as _V_'s suppositions
contradicts _Y_'s confirmed supposition, while _W_'s supposition does not
contradict _Y_'s supposition.

So here's our final tally of knight's and knaves:

Knaves: _U_, _V_, _X_, _Z_

Knights: _W_, _Y_

39. The famous detective Percule Hoirot was called in to solve a baffling murder
    mystery. He determined the following facts:

a. Lord Hazelton, the murdered man, was killed by a blow on the head with a
brass candlestick.

b. Either Lady Hazelton or a maid, Sara, was in the dining room at the time of
the murder.

c. If the cook was in the kitchen at the time of the murder, then the butler
killed Lord Hazelton with a false dose of strychnine.

d. If Lady Hazelton was in the dining room at the time of the murder, then the
chauffeur killed Lord Hazelton.

e. If the cook was not in the kitchen at the time of the murder, then Sara was
not in the dining room when the murder was committed.

f. If Sara was in the dining room at the time the murder was committed, then the
wine steward killed Lord Hazelton.

Is it possible for the detective to deduce the identity of the murderer from
these facts? If so, who did murder Lord Hazelton? (Assume there was only one
cause of death.)

Let's use some assumptions and then provide their corresponding conclusions.

The cook was in the kitchen at the time of the murder $\therefore$ The butler
killed Lord Hazelton with a fatal dose of strychnine (by c).

This contradicts a, so this is not true. This also extends to e:

The cook was not in the kitchen at the time of the murder $\therefore$ Sara was
not in the dining room when the murder was committed. Which then contradicts f,
and relates to b.

Ether Lady Hazelton or a maid, Sara, was in the dining room at the time of the
murder.

But we know that Sara was not in the dining room by e. So Lady Hazelton was in
the dining room at the time of the murder, which leads us to d.

Lady Hazelton was in the dining room at the time of the murder. $\therefore$ The
chauffeur killed Lord Hazelton.

40 Sharky, a leader of the underworld, was killed by one of his own band of four
henchmen. Detective Sharp interviewed the men and determined that all were lying
except for one. He deduced who killed Sharky on the basis of the following
statements:

a. Socko: Lefty killed Sharky.

b. Fats: Muscles didn't kill Sharky.

c. Lefty: Muscles was shooting craps with Socko when Sharky was knocked off.

d. Muscles: Lefty didn't kill Sharky.

Who did kill Sharky?

Let's assume Socko is lying. This leads us to:

Lefty didn't kill Sharky. This means that Muscles is telling the truth. This
means that both Fats and Lefty are lying. Which means Muscles killed Sharky and
that Muscles wasn't shooting craps with Sock when Sharky was knocked off. This
means Muscles killed Sharky.

In 41-44 a set of premises and a conclusion are given. Use the valid argument
forms listed in Table 2.3.1 to deduce the conclusion from the premises, giving a
reason for each step as in Example 2.3.8. Assume all variables are statement
variables.

41.

a. $\neg p \vee q \to r$

b. $s \vee \neg q$

c. $\neg t$

d. $p \to t$

e. $\neg p \wedge r \to \neg s$

f. $\therefore \neg q$

$$
p \to t \\
\neg t \\
\therefore \neg p
$$

By d, c, and moduls tollens.

$$
\neg p \\
\therefore \neg p \vee q
$$

By generalization.

$$
\neg p \vee q \to r \\
\neg p \vee q \\
\therefore r
$$

By previous step and a.

$$
\neg p \wedge r \to \neg s \\
\therefore \neg s
$$

By previous step and e.

$$
s \vee \neg q \\
\neg s \\
\therefore \neg q
$$

By previous step and b, and we have concluded at f.

42.

a. $p \vee q$

b. $q \to r$

c. $p \wedge s \to t$

d. $\neg r$

e. $\neg q \to u \wedge s$

f. $\therefore t$

$$
q \to r \\
\neg r \\
\therefore \neg q
$$

By b and d and modus tollens.

$$
p \vee q \\
\neg q \\
\therefore p
$$

By a, the previous step, and elimination.

$$
\neg q \to u \wedge s \\
\neg q \\
\therefore u \wedge s
$$

By e and previous step.

$$
u \wedge s \\
\therefore s
$$

By previous step and specialization.

$$
p \\
s \\
\therefore p \wedge s
$$

By previous steps and conjunction.

$$
p \wedge s \to t \\
p \wedge s \\
\therefore t
$$

By c and previous step, and we have arrived at f.

43.

a. $\neg p \to r \wedge \neg s$

b. $t \to s$

c. $u \to \neg p$

d. $\neg w$

e. $u \vee w$

f. $\therefore \neg t$

$$
\neg w \\
u \vee w \\
\therefore u
$$

By d, e, and elimination.

$$
u \to \neg p \\
u \\
\therefore \neg p
$$

By previous step, c, and modus ponens.

$$
\neg p \to r \wedge \neg s \\
\neg p \\
\therefore r \wedge \neg s
$$

By previous step, a, and modus ponens.

$$
r \wedge \neg s \\
\therefore \neg s
$$

By previous step and specialization.

$$
t \to s \\
\neg s \\
\therefore \neg t
$$

By t, previous step, and modus tollens, and we have arrived at f.

44.

a. $p \to q$

b. $r \vee s$

c. $\neg s \to \neg t$

d. $\neg q \vee s$

e. $\neg s$

f. $\neg p \wedge r \to u$

g. $w \vee t$

h. $\therefore u \wedge w$

1.

$$
\neg s \to \neg t \\
\neg s \\
\therefore \neg t
$$

By e, c, and modus ponens.

2.

$$
w \vee t \\
\neg t \\
\therefore w
$$

By g, 2, and elimination.

3.

$$
r \vee s \\
\neg s \\
\therefore r
$$

By b, e, and elimination.

4.

$$
\neg q \vee s \\
\neg s \\
\therefore \neg q
$$

By d, e, and elimination.

5.

$$
p \to q \\
\neg q \\
\therefore \neg p
$$

By a, 4, and modus tollens.

6.

$$
\neg p \wedge r \to u \\
\neg p \\
r \\
\therefore u
$$

By f, 5, 3, and modus ponens.

7.

$$
u \\
w \\
\therefore u \wedge w
$$

By 2, 6, and conjunction, and we have arrived at h.

---

**Exercise Set 2.4**

Page 114

Give the output signals for the circuits in 1-4 if the input signals are as
indicated.

(for 1 - 4, see page 114)

1. 1

2. 1

3. 1

4. 1

In 5-8, write an input/output table for the circuit in the referenced exercise.

5. Exercise 1

| $P$ | $Q$ | $R |
| --- | --- | -- |
| 1   | 1   | 1  |
| 1   | 0   | 1  |
| 0   | 1   | 0  |
| 0   | 0   | 1  |

6. Exercise 2

| $P$ | $Q$ | $R |
| --- | --- | -- |
| 1   | 1   | 0  |
| 1   | 0   | 1  |
| 0   | 1   | 0  |
| 0   | 0   | 0  |

7. Exercise 3

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 1   |
| 1   | 1   | 0   | 0   |
| 1   | 0   | 1   | 1   |
| 1   | 0   | 0   | 1   |
| 0   | 1   | 1   | 1   |
| 0   | 1   | 0   | 0   |
| 0   | 0   | 1   | 1   |
| 0   | 0   | 0   | 0   |

8. Exercise 4

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 1   |
| 1   | 1   | 0   | 1   |
| 1   | 0   | 1   | 1   |
| 1   | 0   | 0   | 1   |
| 0   | 1   | 1   | 1   |
| 0   | 1   | 0   | 1   |
| 0   | 0   | 1   | 1   |
| 0   | 0   | 0   | 1   |

In 9-12, find the Boolean expression that corresponds to the circuit in the
referenced exercise.

9. Exercise 1

$$ P \vee \neg Q $$

10. Exercise 2

$$ (P \vee Q) \wedge \neg Q $$

11. Exercise 3

$$ (P \wedge \neg Q) \vee R $$

12. Exercise 4

$$ (P \vee Q) \vee \neg(Q \wedge R) $$

Construct circuits for the Boolean expressions in 13-17.

(drawn out on paper)

13. $\neg P \vee Q$

14. $\neg (P \vee Q)$

15. $P \vee (\neg P \wedge \neg Q)$

16. $(P \wedge Q) \vee \neg R$

17. $(P \wedge \neg Q) \vee (\neg P \wedge R)$

For each of the tables in 18-21, construct (a) a Boolean expression for having
the given table as its truth table and (b) a circuit having the given table as
its input.output table.

18.

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 0   |
| 1   | 1   | 0   | 1   |
| 1   | 0   | 1   | 0   |
| 1   | 0   | 0   | 0   |
| 0   | 1   | 1   | 1   |
| 0   | 1   | 0   | 0   |
| 0   | 0   | 1   | 0   |
| 0   | 0   | 0   | 0   |

$$ (P \wedge Q \wedge \neg R) \vee (\neg P \wedge Q \wedge R) $$

Drawn in person.

19.

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 0   |
| 1   | 1   | 0   | 1   |
| 1   | 0   | 1   | 0   |
| 1   | 0   | 0   | 1   |
| 0   | 1   | 1   | 0   |
| 0   | 1   | 0   | 1   |
| 0   | 0   | 1   | 0   |
| 0   | 0   | 0   | 0   |

$$ (P \wedge Q \wedge \neg R) \vee (P \wedge \neg Q \wedge \neg R) \vee (\neg P \wedge Q \wedge \neg R) $$

20.

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 1   |
| 1   | 1   | 0   | 0   |
| 1   | 0   | 1   | 1   |
| 1   | 0   | 0   | 0   |
| 0   | 1   | 1   | 0   |
| 0   | 1   | 0   | 0   |
| 0   | 0   | 1   | 0   |
| 0   | 0   | 0   | 1   |

$$ (P \wedge Q \wedge R) \vee (P \wedge \neg Q \wedge R) \vee (\neg P \wedge \neg Q \wedge \neg R) $$

21.

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 0   |
| 1   | 1   | 0   | 1   |
| 1   | 0   | 1   | 0   |
| 1   | 0   | 0   | 0   |
| 0   | 1   | 1   | 1   |
| 0   | 1   | 0   | 1   |
| 0   | 0   | 1   | 0   |
| 0   | 0   | 0   | 0   |

$$ (P \wedge Q \wedge \neg R) \vee (\neg P \wedge Q \wedge R) \vee (\neg P \wedge Q \wedge \neg R) $$

22. Design a circuit to take input signals $P$, $Q$, $R$ and output a 1 if, and
    only if, $P$ and $Q$ have the same value and $Q$ and $R$ have opposite
    values.

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 0   |
| 1   | 1   | 0   | 1   |
| 1   | 0   | 1   | 0   |
| 1   | 0   | 0   | 0   |
| 0   | 1   | 1   | 0   |
| 0   | 1   | 0   | 0   |
| 0   | 0   | 1   | 1   |
| 0   | 0   | 0   | 0   |

$$ (P \wedge Q \wedge \neg R) \vee (\neg P \wedge \neg Q \wedge R)$$

23. Design a circuit to take input signals $P$, $Q$, and $R$ and output a 1 if,
    and only if, all three of $P$, $Q$, and $R$ have the same value.

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 1   |
| 1   | 1   | 0   | 0   |
| 1   | 0   | 1   | 0   |
| 1   | 0   | 0   | 0   |
| 0   | 1   | 1   | 0   |
| 0   | 1   | 0   | 0   |
| 0   | 0   | 1   | 0   |
| 0   | 0   | 0   | 1   |

$$ (P \wedge Q \wedge R) \vee (\neg P \wedge \neg Q \wedge \neg R) $$

24. The lights in a classroom are controlled by two switches: one at the back of
    the room and one at the front. Moving either switch to the opposite position
    turns the lights off if they are on and on if they are off. Assume the
    lights have been installed so that when both switches are in the down
    position, the lights are off. Design a circuit to control the switches.

Let $P$ and $Q$ represent the switches in the classroom, with $0$ being "down"
and $1$ being "up." Let $R$ represent the condition of the light, with $0$ being
"off" and $1$ being "on." Initially, $P = Q = 0$ and $R = 0.$ If either $P$ or
$Q$ (but not both) is changed to $1$, the light turns on. SO when $P = 1$ and
$Q = 0$, then $R = 1$, and when $P = 0$ and $Q = 1$, then $R = 1$. Thus when one
switch is up and the other is down the light is on, and hence moving the switch
that is down to the up position turns the light off. So when $P = 1$ and
$Q = 1$, then $R = 0$. It follows that the input/output table has the following
appearance:

| $P$ | $Q$ | $R$ |
| --- | --- | --- |
| 1   | 1   | 0   |
| 1   | 0   | 1   |
| 0   | 1   | 1   |
| 0   | 0   | 0   |

$$ (P \wedge \neg Q) \vee (\neg P \wedge Q) $$

25. An alarm system has three different control panels in three different
    locations. To enable the system, switches in at least two of the panels must
    be in the on position. If fewer than two are in the on position, the system
    is disabled. Design a circuit to control the switches.

Let $P$, $Q$, and $R$ represent the switches in the panels. Let 1 be "on" and 0
be "off" for these switches. Let $S$ represent the system, with 1 being
"enabled" and 0 being "disabled." The input/output table has the following
appearance:

| $P$ | $Q$ | $R$ | $S$ |
| --- | --- | --- | --- |
| 1   | 1   | 1   | 1   |
| 1   | 1   | 0   | 1   |
| 1   | 0   | 1   | 1   |
| 1   | 0   | 0   | 0   |
| 0   | 1   | 1   | 1   |
| 0   | 1   | 0   | 0   |
| 0   | 0   | 1   | 0   |
| 0   | 0   | 0   | 0   |

$$ (P \wedge Q \wedge R) \vee (P \wedge Q \wedge \neg R) \vee (P \wedge \neg Q \wedge R) \vee (\neg P \wedge Q \wedge R) $$

Use the properties listed in Theorem 2.1.1 to show that each pair of circuits in
26-29 have the same input/output table. (Find the Boolean expressions for the
circuits and show that they are logically equivalent when regarded as statement
forms.)

(See Page 115 for circuit diagrams.)

26.

a. $(P \wedge Q) \vee Q$

b. $(P \vee Q) \wedge Q$

Show:

$$ (P \wedge Q) \vee Q \equiv (P \vee Q) \wedge Q $$

$$ (P \wedge Q) \vee Q \equiv Q \equiv (P \vee Q) \wedge Q $$

This is true by the absorption laws.

27.

a. $\neg P \wedge \neg(\neg P \wedge Q)$

b. $\neg(P \vee Q)$

Show:

$$ \neg P \wedge \neg(\neg P \wedge Q) \equiv \neg(P \vee Q) $$

$$ \neg P \wedge \neg(\neg P \wedge Q) $$

$$ \neg P \wedge (\neg\neg P \vee \neg Q) $$

By De Morgan's law

$$ \neg P \wedge (P \vee \neg Q) $$

By double negative law.

$$ (\neg P \wedge P) \vee (\neg P \wedge \neg Q) $$

By distribution law.

$$ \mathbf{c} \vee (\neg P \wedge \neg Q) $$

By universal bounds law.

$$ \neg P \wedge \neg Q $$

By identity law.

$$ \neg(P \vee Q) $$

By De Morgan's law. Which is equivalent to our second statement.

28.

a. $(P \wedge Q) \vee (P \wedge \neg Q) \vee (\neg P \wedge \neg Q)$

b. $P \vee \neg Q$

Show that:

$$ (P \wedge Q) \vee (P \wedge \neg Q) \vee (\neg P \wedge \neg Q) \equiv P \vee \neg Q $$

$$ (P \wedge Q) \vee (P \wedge \neg Q) \vee (\neg P \wedge \neg Q) $$

$$ (P \wedge (Q \vee \neg Q)) \vee (\neg P \wedge \neg Q) $$

By distributive law.

$$ (P \wedge \mathbf{t}) \vee (\neg P \wedge \neg Q) $$

By universal bound law.

$$ P \vee (\neg P \wedge \neg Q) $$

By identity law.

$$ (P \vee \neg P) \wedge (P \vee \neg Q) $$

By distributive law.

$$ \mathbf{t} \wedge (P \vee \neg Q) $$

By negation law.

$$ P \vee \neg Q $$

By identity law. And we have arrived at our second statement.

29.

a. $(P \wedge Q) \vee (\neg P \wedge Q) \vee (P \wedge \neg Q)$

b. $P \vee Q$

Show:

$$ (P \wedge Q) \vee (\neg P \wedge Q) \vee (P \wedge \neg Q) \equiv P \vee Q $$

$$ (P \wedge Q) \vee (\neg P \wedge Q) \vee (P \wedge \neg Q) $$

$$ ((Q \wedge P) \vee (Q \wedge \neg P)) \vee (P \wedge \neg Q) $$

By commutative law.

$$ (Q \wedge (P \vee \neg P)) \vee (P \wedge \neg Q) $$

By distributive law.

$$ (Q \wedge \mathbf{t}) \vee (P \wedge \neg Q) $$

By negation law.

$$ Q \vee (P \wedge \neg Q) $$

By identity law.

$$ (Q \vee P) \wedge (Q \vee \neg Q) $$

By distributive law.

$$ (Q \vee P) \wedge (\mathbf{t}) $$

By negation law.

$$ Q \vee P $$

By identity law.

$$ P \vee Q $$

By commutative law. And we have arrived at our second expression.

For the circuits corresponding to the Boolean expressions in each of 30 and 31
there is an equivalent circuit with at most two logic gates. Find such a
circuit.

30. $(P \wedge Q) \vee (\neg P \wedge Q) \vee (\neg P \wedge \neg Q)$

Basically, just find an equivalent circuit where there is only one expression of
$P$ and $Q$.

$$ (P \wedge Q) \vee (\neg P \wedge Q) \vee (\neg P \wedge \neg Q) $$

$$ ((Q \wedge P) \vee (Q \wedge \neg P)) \vee (\neg P \wedge \neg Q) $$

By commutative law.

$$ (Q \wedge (P \vee \neg P)) \vee (\neg P \wedge \neg Q) $$

By distributive law.

$$ (Q \wedge \mathbf{t}) \vee (\neg P \wedge \neg Q) $$

By negation law.

$$ Q \vee (\neg P \wedge \neg Q) $$

By identity law.

$$ (Q \vee \neg P) \wedge (Q \vee \neg Q) $$

By distributive law.

$$ (Q \vee \neg P) \wedge \mathbf{t} $$

By negation law.

$$ Q \vee \neg P $$

By identity law.

$$ \neg P \vee Q $$

By commutative law.

31. $(\neg P \wedge \neg Q) \vee (\neg P \wedge Q) \vee (P \wedge \neg Q)$

$$ (\neg P \wedge \neg Q) \vee (\neg P \wedge Q) \vee (P \wedge \neg Q) $$

$$ (\neg P \wedge (\neg Q \vee Q)) \vee (P \wedge \neg Q) $$

By distributive law.

$$ (\neg P \wedge \mathbf{t}) \vee (P \wedge \neg Q) $$

By negation law.

$$ \neg P \vee (P \wedge \neg Q) $$

By identity law.

$$ (\neg P \vee P) \wedge (\neg P \vee \neg Q) $$

By distributive law.

$$ \mathbf{t} \wedge (\neg P \vee \neg Q) $$

By negation law.

$$ \neg P \vee \neg Q $$

By identity law.

32. The Boolean expression for the circuit in Example 2.4.5 is

$$ (P \wedge Q \wedge R)  \vee (P \wedge \neg Q \wedge R) \vee (P \wedge \neg Q \wedge \neg R)$$

(a disjunctive normal form). Find a circuit with at most three logic gates that
is equivalent to this circuit.

$$ (P \wedge Q \wedge R)  \vee (P \wedge \neg Q \wedge R) \vee (P \wedge \neg Q \wedge \neg R)$$

$$ P \wedge ((Q \wedge R) \vee (\neg Q \wedge R) \vee (\neg Q \wedge \neg R)) $$

By distributive law.

$$ P \wedge (((R \wedge Q) \vee (R \wedge \neg Q)) \vee (\neg Q \wedge \neg R)) $$

By commutative law.

$$ P \wedge ((R \wedge (Q \vee \neg Q)) \vee (\neg Q \wedge \neg R)) $$

By distributive law.

$$ P \wedge ((R \wedge \mathbf{t}) \vee (\neg Q \wedge \neg R)) $$

By negation law.

$$ P \wedge (R \vee (\neg Q \wedge \neg R)) $$

By identity law.

$$ P \wedge ((R \vee \neg Q) \wedge (R \vee \neg R)) $$

By distributive law.

$$ P \wedge ((R \vee \neg Q) \wedge \mathbf{t}) $$

By negation law.

$$ P \wedge (R \vee \neg Q) $$

By identity law. And we have found an equivalent expression from which we could
draw a much more simple circuit diagram.

33.

a. Show that for the Sheffer stroke $|$,

$$ P \wedge Q \equiv (P|Q)|(P|Q) $$

NAND simply means:

$$ (P|Q) \equiv \neg(P \wedge Q) $$

So this means:

$$ (P|Q)|(P|Q) \equiv \neg(\neg(P \wedge Q) \wedge \neg(P \wedge Q)) $$

$$ (P|Q)|(P|Q) \equiv \neg(\neg(P \wedge Q)) $$

By the idempotent law.

$$ (P|Q)|(P|Q) \equiv P \wedge Q $$

By double negative law. And we have proven our equivalency.

b. Use the results of Example 2.4.7 and part (a) above to write
$P \wedge (\neg Q \vee R)$ using only Sheffer strokes.

$$ \neg Q = (Q|Q) $$

$$ P \wedge (Q|Q \vee R) $$

$$ A \vee B \equiv (A|A)|(B|B) $$

So:

$$ P \wedge (((Q|Q)|(Q|Q))|(R|R)) $$

$$ P \wedge X \equiv (P|X)|(P|X) $$

So:

$$ (P|(((Q|Q)|(Q|Q))|(R|R)))|(P|(((Q|Q)|(Q|Q))|(R|R))) $$

34. Show that the following logical equivalences hold for the Peirce arrow
    $\downarrow$, where $P \downarrow Q \equiv \neg(P \vee Q)$.

a. $\neg P \equiv P \downarrow P$

Recall that $P \downarrow Q \equiv \neg(P \vee Q)$

So $P \downarrow P \equiv \neg(P \vee P)$.

$$ P \downarrow P \equiv \neg P $$

By idempotent law.

b. $P \vee Q \equiv (P \downarrow Q) \downarrow (P \downarrow Q)$

$$ (P \downarrow Q) \downarrow (P \downarrow Q) $$

$$ \neg(P \vee Q) \downarrow \neg(P \vee Q) $$

$$ \neg(\neg(P \vee Q) \vee \neg(P \vee Q)) $$

$$ \neg(\neg(P \vee Q)) $$

By idempotent law.

$$ P \vee Q $$

By double negation law.

c. $P \wedge Q \equiv (P \downarrow P) \downarrow (Q \downarrow Q)$

$$ (P \downarrow P) \downarrow (Q \downarrow Q) $$

$$ \neg(P \vee P) \downarrow \neg(Q \vee Q) $$

$$ \neg(\neg(P \vee P) \vee \neg(Q \vee Q)) $$

$$ \neg(\neg P \vee \neg Q) $$

By idempotent law.

$$ P \wedge Q $$

By De Morgan's law.

d. Write $P \to Q$ using Peirce arrows only.

$$ P \to Q \equiv \neg P \vee Q $$

$$ \neg P \vee Q $$

$$ (P \downarrow P) \vee Q $$

$$ ((P \downarrow P)\downarrow Q) \downarrow ((P \downarrow P)\downarrow Q) $$

e. Write $P \leftrightarrow Q$ using Peirce arrows only.

$$ P \leftrightarrow Q \equiv (P \to Q) \wedge (Q \to P) $$

Using part d, we can then simplify this a bit further to:

$$ (((P \downarrow P)\downarrow Q) \downarrow ((P \downarrow P)\downarrow Q)) \wedge (((Q \downarrow Q)\downarrow P) \downarrow ((Q \downarrow Q)\downarrow P)) $$

$$ A \wedge B \equiv (A \downarrow A)\downarrow(B \downarrow B) $$

So:

$$ (((P \downarrow P)\downarrow Q) \downarrow ((P \downarrow P)\downarrow Q)\downarrow ((P \downarrow P)\downarrow Q)) \downarrow (((Q \downarrow Q)\downarrow P) \downarrow ((Q \downarrow Q)\downarrow P) \downarrow (Q \downarrow Q)) $$

---

**Exercise Set 2.5**

Page 129

Represent the decimal integers in 1-6 in binary notation.

1. $19$

2. $55$

3. $287$

4. $458$

5. $1609$

6. $1424$

Represent the integers in 7-12 in decimal notation.

7. $1110_2$

8. $10111_2$

9. $110110_2$

10. $1100101_2$

11. $1000111_2$

12. $1011011_2$

Perform the arithmetic in 13-20 using binary notation.

13.

$$
1011_2 \\
\underline{+ 101_2}
$$

14.

$$
1001_2 \\
\underline{+ 1011_2}
$$

15.

$$
101101_2 \\
\underline{+ 11101_2}
$$

16.

$$
110111011_2 \\
\underline{+ 1001011010_2}
$$

17.

$$
10100_2 \\
\underline{+ 1101_2}
$$

18.

$$
11010_2 \\
\underline{- 1101_2}
$$

19.

$$
101101_2 \\
\underline{- 10011_2}
$$

20.

$$
1010100_2 \\
\underline{- 10111_2}
$$

21. Give the output signals $S$ and $T$ for the circuit shown below if the input
    signals $P$, $Q$, and $R$ are as specified. Note that this is _not_ the
    circuit for a full-adder.

a. $P = 1$, $Q = 1$, $R = 1$

b. $P = 0$, $Q = 1$, $R = 0$

c. $P = 1$, $Q = 0$, $R = 1$

(See Page 130)

22. Add $11111111_2 + 1_2$ and convert the result to decimal notation, to verify
    that $11111111_2 = (2^8 - 1)_10$.

Find the 8-bit two's complements for the integers in 23-26.

23. $-23$

24. $-67$

25. $-4$

26. $-115$

Find the decimal representations for the integers with the 8-bit two's
complements given in 27-30.

27. $11010011$

28. $10011001$

29. $11110010$

30. $10111010$

Use 8-bit two's complements to compute the sums in 31-36.

31. $57 + (-118)$

32. $62 + (-18)$

33. $(-6) + (-73)$

34. $89 + (-55)$

35. $(-15) + (-46)$

36. $123 + (-94)$

37.

a. Show that when you apply the 8-bit two's complement procedure to the 8-bit
two's complement for $-128$, you get the 8-bit two's complement for $-128$.

b. Show that if $a$, $b$, and $a + b$ are integers in the range $1$ through
$128$, then

$$ (2^8 - a) + (2^8 - b) = (2^8 - (a + b)) + 2^8 \geq 2^8 + 2^7 $$

Explain why it follows that if integers $a$, $b$, and $a + b$ are all in the
range $1$ through $128$, then the 8-bit two's complement of $(-a) + (-b)$ is a
negative number.

Convert the integers in 38-40 from hexadecimal to decimal notation.

38. $A2BC_{16}$

39. $E0D_{16}$

40. $39EB_{16}$

Convert the integers in 41-43 from hexadecimal to binary notation.

41. $1C0ABE_{16}$

42. $B53DF8_{16}$

43. $4ADF83_{16}$

Convert the integers in 44-46 from binary to hexadecimal notation.

44. $00101110_2$

45. $1011011111000101_2$

46. $11001001011100_2$

47. **Octal Notation:** IN addition to binary and hexadecimal, computer
    scientists also use _octal notation_ (base 8) to represent numbers. Octal
    notation is based on the fact that any integer can be uniquely represented
    as a sum of numbers of the form $d \cdot 8^n$, where each $n$ is a
    nonnegative integer and each $d$ is one of the integers from $0$ to $7$.
    Thus, for example,
    $5073_8 = 5 \cdot 8^3 + 0 \cdot 8^2 + 7 \cdot 8^1 + 3 \cdot 8^0 = 2619_{10}$.

a. Convert $61502_8$ to decimal notation.

b. Convert $20763_8$ to decimal notation.

c. Describe methods for converting integers from octal to binary notation and
the reverse that are similar to the methods used in Examples 2.5.9 and 2.5.10
for converting back and forth from hexadecimal to binary notation. Give examples
showing that these methods result in correct answers.
