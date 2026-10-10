Page 862

**Exercise Set 12.1**

In 1 and 2, let $\Sigma = \{x, y\}$ be an alphabet.

1.

a. Let $L_1$ be the language consisting of all strings over $\Sigma$ that are
palindromes and have length $\leq 4$. List the elements of $L_1$ between braces.

$$ \{\lambda, x, y, xx, yy, xxx, yyy, xxxx, yyyy, xyx, yxy, xyyx, yxxy \} $$

b. Let $L_2$ be the language consisting of all strings over $\Sigma$ that begin
with an $x$ and have length $\leq 3$. List the elements of $L_2$.

$$ \{x, xx, xy, xxx, xyy, xyx, xxy\} $$

2.

a. Let $L_3$ be the language consisting of all strings over $\Sigma$ of length
$\leq 3$ in which all the $x$'s appear to the left of all the $y$'s. List the
elements of $L_3$ between braces.

$$ \{x, y, xx, xy, xxx, xxy, xyy, yyy\} $$

b. List between braces the elements of $\Sigma^4$, the set of all strings of
length $4$ over $\Sigma$.

$ \{xxxx, xxxy, xxyx, xyxx, xyxy, xxyy, xyyx, xyyy, yxxx, yxxy, yxyx, yyxx,
yxyy, yyxy, yyyx, yyyy\}$

c. Let $A = \Sigma^1 \cup \Sigma^2$ and $B = \Sigma^3 \cup \Sigma^4$. Describe
$A$, $B$, and $A \cup B$ in words.

$A$ is the set of strings over $\Sigma$ of length 1 or 2.

$B$ is the set of strings over $\Sigma$ of length 3 or 4.

$A \cup B$ is the set of strings over $\Sigma$ of length 1 or 2 or 3 or 4.

3.

a. If the expression $ab + cd + \cdot$ in postfix notation is converted to infix
notation, what is the result?

$(a + b) \cdot (c + d)$

b. Let $\Sigma = \{1, 2, *, /\}$ and let $L$ be the set of all strings over
$\Sigma$ obtained by writing first a number ($1$ or $2$), then a second number
($1$ or $2$), which can be the same as the first one, and finally an operation
(denoted $*$ or $/$, where $*$ indicates multiplication and $/$ indicates
division). Then $L$ is a set of postfix, or reverse Polish, expressions. List
all the elements of $L$ between braces, and evaluate the resulting expressions.

$$ L = \{11^*, 11/, 12^*, 12/, 21^*, 21/, 22*, 22/\} $$

$$ 11^* = 1 \cdot 1 = 1 $$

$$ 11/ = \frac{1}{1} = 1 $$

$$ 12^* = 1 \cdot 2 = 2 $$

$$ 12/ = \frac{1}{2} $$

$$ 21^* = 2 \cdot 1 = 2 $$

$$ 21/ = \frac{2}{1} = 2 $$

$$ 22^* = 2 \cdot 2 = 4 $$

$$ 21/ = \frac{2}{1} = 2 $$

In 4-6, describe $L_1L_2, L_1 \cup L_2$, and $(L_1 \cup L_2)^*$ for the given
languages $L_1$ and $L_2$.

4. $L_1$ is the set of all strings of $a$'s and $b$'s that start with an $a$ and
   contain only that one $a$; $L_2$ is the set of all strings of $a$'s and $b$'s
   that contain an even number of $a$'s.

$L_1L_2$ is the set of all strings of $a$ and $b$'s that start with an $a$ and
contain an odd number of $a$'s.

$L_1 \cup L_2$ is the set of all strings that either start with an $a$ and
contain only one $a$ or the strings of $a$'s and $b$'s that contain an even
number of $a$'s.

$(L_1 \cup L_2)^*$ is the set of all strings of $a$'s and $b$'s.

5. $L_1$ is the set of all strings of $a$'s, $b$'s, and $c$'s that contain no
   $c$'s and have the same number of $a$'s as $b$'s; $L_2$ is the set of all
   strings of $a$'s, $b$'s, and $c$'s that contain no $a$'s or $b$'s.

$L_1L_2$ is the set of all strings where there are an equal number of $a$ and
$b$'s and no $c$'s along with all possible combinations of strings where $c$ is
the sole character, as well as the null string $\lambda$.

$L_1 \cup L_2$ is the set of all strings of $a, b, c$ that contain no $c$'s and
have the same number of $a$'s or the set of all strings of $a, b, c$ that
contain no $a$ or $b$'s.

$(L_1 \cup L_2)^*$ is the set of all strings of $a, b, c$ that contain the same
number of $a$'s and $b$'s.

6. $L_1$ is the set of all strings of $0$'s and $1$'s that start with a $0$;
   $L_2$ is the set of all strings of $0$'s and $1$'s that end with a $0$.

$L_1L_2$ is the set of all strings that start with a $0$ and end with a $0$.

$L_1 \cup L_2$ is the set of all strings that either start with a $0$ or end
with a $0$.

$(L_1 \cup L_2)^*$ is the set of all strings of $0$'s and $1's$.

In 7-9, add parentheses to emphasize the order of precedence in the given
expressions.

7. $(a | b^*b)(a^*|ab)$

$$ (a | ((b^*)b))((a^*)|(ab)) $$

8. $0*1 | 0(0^*1)^*$

$$ ((0^*)1) | (0(((0^*)1)^*)) $$

9. $(x | yz^*)^*(yx | (yz)^*z)$

$$ ((x | (y(z^*)))^*) ((yx) | (((yz)^*)(z))) $$

In 10-12, use the rules about the order of precedence to eliminate the
parentheses in the given regular expression.

10. $((a(b^*)) | (c(b^*))) ((ac) | (bc))$

$$ (ab^* | cb^*)(ac | bc) $$

11. $(1(1^*)) | ((1(0^*)) | ((1^*)1))$

$$ 11^* | 10^* | 1^*1 $$

12. $(xy)(((x^*)y)^*) | (((yx) | y)(y^*))$

$$ xy(x^*y)^* | (yx | y)(y^*) $$

In 13-15, use set notation to derive the language defined by the given regular
expression. Assume $\Sigma = \{a, b, c\}$.

13. $\lambda | ab$

$$ \{\lambda\} \cup \{ab\} $$

14. $\emptyset | \lambda$

$$ \emptyset \cup \{\lambda\} $$

15. $(a | b)c$

$$ \{ac\} \cup \{bc\} $$

In 16-18, write five strings that belong to the language defined by the given
regular expression.

16. $0^*1(0^*1^*)^*$

$$ 01, 1, 010, 011, 01001 $$

17. $b^*|b^*ab^*$

$$ b, bb, ba, bba, bab $$

18. $x^*(yxxy|x)^*$

$$ x, xyxxy, xyxxyyxxy, xx, xxx $$

In 19-21, use words to describe the language defined by the given regular
expression.

19. $b^*ab^*ab^*a$

Any number of $b$'s, followed by a single $a$, followed by any number of $b$'s,
followed by a single $a$, followed by any number of $b$'s, followed by a single
$a$.

20. $1(0|1)^*00$

A single $1$, followed by any mixture of $0$'s and/or $1$'s, followed by exactly
two $0$'s.

21. $(x|y)y(x|y)^*$

A single $x$ or a single $y$, followed by one $y$, followed by any mixture of
$x$'s or $y$'s.

In 22-24, indicate whether the given strings belong to the language defined by
the given regular expression. Briefly justify your answers.

22. Expression: $(b|\lambda)a(a|b)^*a(b|\lambda)$, strings: $aaaba$, $baabb$

The expression says start of with a $b$ or no characater (_i.e. $\lambda$),
followed by a single $a$, followed by any mixture of $a$'s or $b$'s, followed by
a single $a$, ending in either a $b$ or $\lambda$.

$aaaba$ works because it starts off with $\lambda, followed by a single $a$,
followed by any number of $a$ or $b$'s, followed by a single $a$, followed by
$\lambda$.

$baabb$ works, because it starts off with $b$, followed by a single $a$,
followed by any number of $a$ or $b$'s (one of each in this case), ending in
$b$.

23. Expression: $(x^*y|zy^*)^*$, strings: $zyyxz$, $zyyzy$

The expression says that any number of repetitions of strings where either:

(a) The string starts off with any number of $x$'s and ends with a $y$.

or

(b) The string starts off with a single $z$ and ends with any number of $y$'s.

$zyyxz$ doesn't works because it starts off with a $z$ followed by a $y$, it is
followed by $0$ $x$'s followed by a two $y$'s, it is then followed by a single
$x$ and $0$ $y$'s (and this is where it breaks as after any amount of $x$'s,
there must be a single $y$).

$zyyzy$ works because it starts off with a $z$ followed by 2 $y$'s, followed by
a $z$ followed by a single $y$.

24. Expression: $(01^*2)^*$, strings: $120$, $01202$

The expression says that any number of repetitions of strings where:

A single $0$ followed by any amount of $1$'s followed by a single $2$.

$120$ doesn't work because it must start off with at least 1 $0$.

$01202$ works because it starts off with a single $0$ followed by a single $1$
followed by a single $2$, then repeated to another repetition that starts off
with a single $0$, has 0 $1$'s and ends with a single $2$.

In 25-27, find a regular expression that defines the given language.

25. The language consisting of all strings of $0$'s and $1$'s with an odd number
    of $1$'s. (Such a string is said to have _odd parity_.)

$$ 0^*10^*(0^*10^*1)^* $$

26. The language consisting of all strings of $a$'s and $b$'s in which the third
    character from the end is a $b$.

$$ (a | b)^*b(a | b)(a | b) $$

27. The language consisting of strings of $x$'s and $y$'s in which the elements
    in every pair of $x$'s are separated by at least one $y$.

$$ y^*(xy^+)^*xy^* | y^* $$

Let $r$, $s$, and $t$ be regular expressions over $\Sigma = \{a, b\}$. In 28-30,
determine whether the two regular expressions define the same language. If they
do, describe the language. If they do not, give an example of a string that is
in one of the languages but not the other.

28. $(r | s)t$ and $rt | st$

Yes,

$$ L((r | s)t) = L(r | s)L(t) $$

$$ = (L(r) \cup L(s))L(t) $$

$$ = \{xy | (x \in L(r) \cup L(s)) \wedge (y \in L(t)) \} $$

$$ = \{xy | (x \in L(r) \vee x \in L(s)) \wedge (y \in L(t))\} $$

$$ = \{xy | (x \in L(r) \wedge y \in L(t)) \vee (x \in L(s) \wedge y \in L(t))\} $$

$$ = \{xy | x^ \in L(rt) \vee xy \in L(st)\} $$

$$ = L(rt) \cup L(st) = L(rt | st) $$

29. $(rs)^*$ and $r^*s^*$

The string represented by $rr$ is in the second language, but not the first
language.

30. $(rs)^*$ and $((rs)^*)^*$

Yes, these two languages are equivalent, as the first language represents any
amount of $r$ followed by $s$, and the second language represents any repeated
amounts of repeated amounts of $r$ followed by $s$.

In 31-39, write a regular expression to define the given set of strings. Use the
shorthand notations given in the section whenever convenient. In most cases,
your expressions will describe other strings in addition to the given ones, but
try to make the answer fit the given strings as closely as possible within
reasonable space limitations.

31. All words that are written in lowercase letters start with the letters $pre$
    but do not consist of $pre$ all by itself.

$$ pre[a - z]^+ $$

32. All words that are written in uppercase letters, and contain the letters
    $BIO$ (as a unit) or $INFO$ (as a unit).

$$ [A - Z]^*(BIO | INFO)[A - Z]^* $$

33. All words that are written in lowercase letters, end in $ly$, and contain at
    least five letters.

$$ [a - z]^3[a - z]^*ly $$

34. All words that are written in lowercase letters and contain at least one of
    the vowels a, e, i, o, or u.

$$ [a - z]^*(a | e | i | o | u)[a - z]^* $$

35. All words that are written in lowercase letters and contain exactly one of
    the vowels a, e, i, o, or u.

$$ [b-d f-h j-n p-t v-z]^*(a | e | i | o | u)[b-d f-h j-n p-t v-z]^* $$

36. All words that are written in uppercase letters and do not start with one of
    the vowels A, E, I, O, or U but contain exactly two of these vowels next to
    each other.

$$ [B-D F-H J-N P-T V-Z]^+(A | E | I | O | U)(A | E | I | O | U)[B-D F-H J-N P-T V-Z]^* $$

37. All United States social security numbers (which consist of three digits, a
    hyphen, two digits, another hyphen, and finally four more digits), where the
    final four digits start with a 3 and end with a 6.

$$ [0-9]^3-[0-9]^2-3[0-9]^26 $$

38. All telephone numbers that have three digits, then a hyphen, then three more
    digits, then a hyphen, and then four digits, where the first three digits
    are either 800 or 888 and the last four digits start and end with a 2.

$$ (800 | 888)-[0-9]^3-2[0-9]^22 $$

39. All signed or unsigned numbers with or without a decimal point. A signed
    number has one of the prefixes $+$ or $-$, and an unsigned number does not
    have a prefix. Represent the decimal point as \\. to distinguish it from the
    single dot symbol for an arbitrary character.

$$ (+ | -)?[0-9]^+(\.[0-9]^+)? $$

40. Write a regular expression to perform a complete check to determine whether
    a given string represents a valid date from 1980 to 2079 written in one of
    the formats of Example 12.1.11 (During this period, leap years occur every
    four years starting in 1980.)

_Hint:_ Leap years from 1980 to 2079 are 1980, 1984, 1988, 1992, 1996, 2000,
2004, and so forth. Note that the fourth digit is 0, 4, or 8 for the years whose
third digit is even and that the fourth digit is 2 or 6 for the years whose
third digit is odd.

Omitted.

41. Write a regular expression to define the set of strings of $0$'s and $1$'s
    with an even number of $0$'s and even number of $1$'s.

Omitted.

---

Page 878

**Exercise Set 12.2**

1. Find the state of the vending machine in Example 12.2.1 after each of the
   following sequences of coins have been input.

a. Quarter, half-dollar, quarter

b. Quarter, half-dollar, half-dollar

c. Half-dollar, quarter, quarter, half-dollar

In 2-7, a finite-state automaton is given by a transition diagram. For each
automaton:

a. Find its states.

b. Find its input symbols.

c. Find its initial state.

d. Find its accepting states.

e. Write its annotated next-state table.

2. (See Page 879 for finite-state automaton diagram.)

3. (See Page 879 for finite-state automaton diagram.)

4. (See Page 879 for finite-state automaton diagram.)

5. (See Page 879 for finite-state automaton diagram.)

6. (See Page 879 for finite-state automaton diagram.)

7. (See Page 879 for finite-state automaton diagram.)

In 8 and 9, a finite-state automaton is given by an annotated next-state table.
For each automaton:

a. Find its states.

b. Find its input symbols.

c. Find its initial state.

d. Find its accepting states.

e. Draw its transition diagram.

8. (See Page 879 for finite-state automaton diagram.)

9. (See Page 879 for finite-state automaton diagram.)

10. A finite-state automaton $A$, given by the transition diagram below, has
    next-state function $N$ and eventual-state function $N^*$.

(See Page 879 for finite-state automaton diagram.)

a. Find $N(s_1, 1)$ and $N(s_0, 1)$.

b. Find $N(s_2, 0)$ and $N(s_1, 0)$.

c. Find $N^*(s_0, 10011)$ and $N^*(s_1, 01001)$.

d. Find $N^*(s_2, 11010)$ and $N^*(s_0, 01000)$.

11. A finite-state automaton $A$, given by the transition diagram on the next
    page, has next-state function $N$ and eventual-state function $N^*$.

(See Page 880 for finite-state automaton diagram.)

a. Find $N(s_3, 0)$ and $N(s_2, 1)$.

b. Find $N(s_0, 0)$ and $N(s_4, 1)$.

c. Find $N^*(s_0, 010011)$ and $N^*(s_3, 01101)$.

d. Find $N^*(s_0, 1111)$ and $N^*(s_2, 00111)$.

12. Consider again the finite-state automaton of exercise 2.

a. To what state does the automaton go when the symbols of the following strings
are input to it in sequence, starting from the initial state?

(i) 1110001

(ii) 0001000

(iii) 11110000

b. Which of the strings in part (a) send the automaton to an accepting state?

c. What is the language accepted by the automaton?

d. Find a regular expression that defines the language.

13. Consider again the finite-state automaton of exercise 3.

a. To what state does the automaton go when the symbols of the following strings
are input to it in sequence, starting from the initial state?

(i) bb

(ii) aabbbaba

(iii) babbbbbabaa

(iv) bbaaaabaa

b. What of the strings in part (a) send the automaton to an accepting state?

c. What is the language accepted by the automaton?

d. Find a regular expression that defines the language.

In each of 14-19, (a) find the language accepted by the automaton in the
referenced exercise, and (b) find a regular expression that defines the same
language.

14. Exercise 4

15. Exercise 5

16. Exercise 6

17. Exercise 7

18. Exercise 8

19. Exercise 9

In each of 20-28, (a) design an automaton with the given input alphabet that
accepts the given set of strings, and (b) find a regular expression that defines
the language accepted by the automaton.

20. Input alphabet $= \{0, 1\}$; Accepts the set of all strings for which the
    final three input symbols are $1$.

21. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that start with
    $01$.

22. Input alphabet $= \{a, b\}$; Accepts the set of all strings of length at
    least $2$ for which the final two input symbols are the same.

23. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that start with
    $01$ or $10$.

24. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that start with
    $101$.

25. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that end in
    $10$.

26. $Input alphabet $= \{a, b\}$$; Accepts the set of all strings that contain
    exactly two $b$'s.

27. Input alphabet $$i= \{0, 1\}; Accepts the set of all strings that start with
    $0$ and contain exactly one $1$.

28. Input alphabet. $= \{0, 1\}$; Accepts the set of all strings that contain
    the pattern $010$.

In 29-47, design a finite-state automaton to accept the language defined by the
regular expression in the referenced exercise from Section 12.1.

29. Exercise 16

30. Exercise 17

31. Exercise 18

32. Exercise 19

33. Exercise 20

34. Exercise 21

35. Exercise 24

36. Exercise 25

37. Exercise 26

38. Exercise 27

39. Exercise 31

40. Exercise 32

41. Exercise 33

42. Exercise 34

43. Exercise 35

44. Exercise 36

45. Exercise 37

46. Exercise 38

47. Exercise 39

48. A simplified telephone switching system allows the following strings as
    legal telephone numbers:

a. A string of seven digits in which neither of the first two digits is a $0$ or
$1$ (_a local call string_).

b. A $1$ is followed by a three-digit _area code string_ (any digit except $0$
or $1$ followed by a $0$ or $1$ followed by any digit) followed by a seven-digit
local call string.

c. A $0$ alone or followed by a three-digit area code string plus a seven-digit
local call string.

d. Design a finite-state automaton to recognize all the legal telephone numbers
in (a), (b), and \(c\). Include an "error state" for invalid telephone numbers.

49. Write a computer algorithm that simulates the action of the finite-state
    automaton of exercise 2 by mimicking the action of the transition diagram.

50. Write a computer algorithm that simulates the action of the finite-state
    automaton of exercise 8 by repeated application of the next-state function.

51. Let $L$ be the language consisting of all strings of the form $a^mb^n$,
    where $m$ and $n$ are positive integers and $m \geq n$. Show that there is
    no finite-state automaton that accepts $L$.

52. Let $L$ be the language consisting of all strings of the form $a^mb^n$,
    where $m$ and $n$ are positive integers and $m \leq n$. Show that there is
    no finite-state automaton that accepts $L$.

53. Let $L$ be the language consisting of all strings of the form $a^n$, where
    $n = m^2$, for some positive integer $m$. Show that there is no finite-state
    automaton that accepts $L$.

54.

a. Let $A$ be a finite-state automaton with input alphabet $\Sigma$, and suppose
$L(A)$ is the language accepted by $A$. The complement of $L(A)$ is the set of
all strings over $\Sigma$ that are not in $L(A)$. Show that the complement of a
regular language is regular by proving the following: If $L(A)$ is the language
accepted by a finite-state automaton $A$, then there is a finite-state automaton
$A'$ that accepts the complement of $L(A)$.

b. Show that the intersection of any two regular languages is regular as
follows: First prove that if $L(A_1)$ and $L(A_2)$ are languages accepted by
automata $A_1$ and $A_2$, respectively, then there is an automaton $A$ that
accepts $(L(A_1))^c \cup (L(A_2))^c$. Then use one of De Morgan's laws for sets,
the double complement law for sets, and the result of part (a) to prove that
there is an automaton that accepts $L(A_2) \cap L(A_2)$.
