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

Ends in accepted state "$1 or more deposited"

b. Quarter, half-dollar, half-dollar

Ends in accepted state "$1 or more deposited"

c. Half-dollar, quarter, quarter, half-dollar

Ends in state "50 cents deposited"

In 2-7, a finite-state automaton is given by a transition diagram. For each
automaton:

a. Find its states.

b. Find its input symbols.

c. Find its initial state.

d. Find its accepting states.

e. Write its annotated next-state table.

2. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

$$ s_0, s_1, s_2 $$

b. Find its input symbols.

$$ 0, 1 $$

c. Find its initial state.

$$ s_0 $$

d. Find its accepting states.

$$ s_2 $$

e. Write its annotated next-state table.

|                |       | $0$   | $1$   |
| -------------- | ----- | ----- | ----- |
| $\rightarrow$  | $s_0$ | $s_1$ | $s_0$ |
|                | $s_1$ | $s_1$ | $s_2$ |
| $\circledcirc$ | $s_2$ | $s_2$ | $s_2$ |

3. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

$$ U_0, U_1, U_2, U_3 $$

b. Find its input symbols.

$$ a, b $$

c. Find its initial state.

$$ U_0 $$

d. Find its accepting states.

$$ U_3 $$

e. Write its annotated next-state table.

|                |       | $a$   | $b$   |
| -------------- | ----- | ----- | ----- |
| $\rightarrow$  | $U_0$ | $U_2$ | $U_1$ |
|                | $U_1$ | $U_2$ | $U_3$ |
|                | $U_2$ | $U_2$ | $U_2$ |
| $\circledcirc$ | $U_3$ | $U_3$ | $U_3$ |

4. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

$$ s_0, s_1, s_2 $$

b. Find its input symbols.

$$ 0, 1 $$

c. Find its initial state.

$$ s_0 $$

d. Find its accepting states.

$$ s_2 $$

e. Write its annotated next-state table.

|                |       | $0$   | $1$   |
| -------------- | ----- | ----- | ----- |
| $\rightarrow$  | $s_0$ | $s_1$ | $s_0$ |
|                | $s_1$ | $s_2$ | $s_0$ |
| $\circledcirc$ | $s_2$ | $s_2$ | $s_0$ |

5. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

$$ A, B, C, D, E, F $$

b. Find its input symbols.

$$ x, y $$

c. Find its initial state.

$$ A $$

d. Find its accepting states.

$$ D, E $$

e. Write its annotated next-state table.

|                |     | $x$ | $y$ |
| -------------- | --- | --- | --- |
| $\rightarrow$  | $A$ | $C$ | $B$ |
|                | $B$ | $F$ | $D$ |
|                | $C$ | $E$ | $F$ |
|                | $F$ | $F$ | $F$ |
| $\circledcirc$ | $D$ | $F$ | $D$ |
| $\circledcirc$ | $E$ | $E$ | $F$ |

6. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

$$ s_0, s_1, s_2, s_3 $$

b. Find its input symbols.

$$ 0, 1 $$

c. Find its initial state.

$$ s_0 $$

d. Find its accepting states.

$$ s_0 $$

e. Write its annotated next-state table.

|                             |       | $0$   | $1$   |
| --------------------------- | ----- | ----- | ----- |
| $\rightarrow, \circledcirc$ | $s_0$ | $s_0$ | $s_1$ |
|                             | $s_1$ | $s_1$ | $s_2$ |
|                             | $s_2$ | $s_2$ | $s_3$ |
|                             | $s_3$ | $s_3$ | $s_0$ |

7. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

$$ s_0, s_1, s_2, s_3 $$

b. Find its input symbols.

$$ 0, 1 $$

c. Find its initial state.

$$ s_0 $$

d. Find its accepting states.

$$ s_0, s_2 $$

e. Write its annotated next-state table.

|                             |       | $0$   | $1$   |
| --------------------------- | ----- | ----- | ----- |
| $\rightarrow, \circledcirc$ | $s_0$ | $s_0$ | $s_1$ |
|                             | $s_1$ | $s_1$ | $s_2$ |
|                             | $s_3$ | $s_3$ | $s_0$ |
| $\circledcirc$              | $s_2$ | $s_2$ | $s_3$ |

In 8 and 9, a finite-state automaton is given by an annotated next-state table.
For each automaton:

a. Find its states.

$$ s_0, s_1, s_2 $$

b. Find its input symbols.

$$ 0, 1 $$

c. Find its initial state.

$$ s_0 $$

d. Find its accepting states.

$$ s_2 $$

e. Draw its transition diagram.

(Done by hand.)

8. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

$$ s_0, s_1, s_2, s_3 $$

b. Find its input symbols.

$$ 0, 1 $$

c. Find its initial state.

$$ s_0 $$

d. Find its accepting states.

$$ s_1 $$

e. Draw its transition diagram.

(Done by hand.)

9. (See Page 879 for finite-state automaton diagram.)

a. Find its states.

b. Find its input symbols.

c. Find its initial state.

d. Find its accepting states.

e. Draw its transition diagram.

10. A finite-state automaton $A$, given by the transition diagram below, has
    next-state function $N$ and eventual-state function $N^*$.

(See Page 879 for finite-state automaton diagram.)

a. Find $N(s_1, 1)$ and $N(s_0, 1)$.

$$ N(s_1, 1) = s_2 $$

$$ N(s_0, 1) = s_3 $$

b. Find $N(s_2, 0)$ and $N(s_1, 0)$.

$$ N(s_2, 0) = s_3 $$

$$ N(s_1, 0) = s_3 $$

c. Find $N^*(s_0, 10011)$ and $N^*(s_1, 01001)$.

$$ N^*(s_0, 10011) = s_2 $$

$$ N^*(s_1, 01001) = s_2 $$

d. Find $N^*(s_2, 11010)$ and $N^*(s_0, 01000)$.

$$ N^*(s_2, 11010) = s_3 $$

$$ N^*(s_0, 01000) = s_3 $$

11. A finite-state automaton $A$, given by the transition diagram on the next
    page, has next-state function $N$ and eventual-state function $N^*$.

(See Page 880 for finite-state automaton diagram.)

a. Find $N(s_3, 0)$ and $N(s_2, 1)$.

$$ N(s_3, 0) = s_4 $$

$$ N(s_2, 1) = s_4 $$

b. Find $N(s_0, 0)$ and $N(s_4, 1)$.

$$ N(s_0, 0) = s_1 $$

$$ N(s_4, 1) = s_3 $$

c. Find $N^*(s_0, 010011)$ and $N^*(s_3, 01101)$.

$$ N^*(s_0, 010011) = s_3 $$

$$ N^*(s_3, 01101) = s_4 $$

d. Find $N^*(s_0, 1111)$ and $N^*(s_2, 00111)$.

$$ N^*(s_0, 1111) = s_3 $$

$$ N^*(s_2, 00111) = s_2 $$

12. Consider again the finite-state automaton of exercise 2.

a. To what state does the automaton go when the symbols of the following strings
are input to it in sequence, starting from the initial state?

(i) 1110001

$$ N^*(s_0, 1110001) = s_2 $$

(ii) 0001000

$$ N^*(s_0, 0001000) = s_2 $$

(iii) 11110000

$$ N^*(s_0, 11110000) = s_1 $$

b. Which of the strings in part (a) send the automaton to an accepting state?

$$ 1110001, 0001000 $$

c. What is the language accepted by the automaton?

The language accepted by this automaton is the set of all strings of $0$'s and
$1$'s that containa t least one $0$ followed (not necessarily immediately) by at
least one $1$.

d. Find a regular expression that defines the language.

$$ 1^*00^*1(0 | 1)^* $$

13. Consider again the finite-state automaton of exercise 3.

a. To what state does the automaton go when the symbols of the following strings
are input to it in sequence, starting from the initial state?

(i) bb

$$ N^*(U_0, bb) = U_3 $$

(ii) aabbbaba

$$ N^*(U_0, aabbbaba) = U_2 $$

(iii) babbbbbabaa

$$ N^*(U_0, babbbbbabaa) = U_2 $$

(iv) bbaaaabaa

$$ N^*(U_0, bbaaaabaa) =  U_3 $$

b. What of the strings in part (a) send the automaton to an accepting state?

$$ bb, bbaaabaa $$

(or parts (i) and (iv))

c. What is the language accepted by the automaton?

Any language where the first two characters are $bb$ followed by any number of
$a$'s and/or $b$'s.

d. Find a regular expression that defines the language.

$$ bb(a | b)^* $$

In each of 14-19, (a) find the language accepted by the automaton in the
referenced exercise, and (b) find a regular expression that defines the same
language.

14. Exercise 4

a.

The language accepted by this finite-state automaton is the set of all strings
of $0$ and $1$'s that ends in $00$.

b.

$$ (0 | 1)^*00 $$

15. Exercise 5

a.

The language accepted by this finite-state automaton is the set of all strings
of $x$'s and $y$'s that either begin with $yy$ and end in any amount of $y$'s,
or start with $xx$ and end in any amount of $x$'s.

b.

$$ yyy^* | xxx^* $$

16. Exercise 6

a.

The language accepted by this finite-state automaton is the set of all strings
of $0$'s and $1$'s that have any amount of $0$'s or have any amount of $0$'s but
have $1$'s that are a multiple of 4.

b.

$$ 0^*|(0^*10^*10^*10^*1)^* $$

17. Exercise 7

a.

The language accepted by this finite-state automaton is the set of all strings
of $0$'s and $1$'s that have any amount of $0$'s or have any amount of $0$'s but
have $1$'s that are a multiple of 2.

b.

$$ 0^*|(0^*10^*1)^* $$

18. Exercise 8

a.

The language accepted by this finite-state automaton is the set of all strings
of $0$'s and $1$'s that start with any amount of $0$'s or $1$'s followed by any
amount of $1$'s.

b.

$$ (0 | 1)1^* $$

19. Exercise 9

a.

The language accepted by this automaton is the set of all strings of $0$'s and
$1$'s, with the property that if $n$ is the number of $1$'s in the string, then
$n \mod 4 = 1$.

b.

$$ (0^*10^*10^*10^*1)^*1(0^*10^*10^*10^*1)^* $$

In each of 20-28, (a) design an automaton with the given input alphabet that
accepts the given set of strings, and (b) find a regular expression that defines
the language accepted by the automaton.

20. Input alphabet $= \{0, 1\}$; Accepts the set of all strings for which the
    final three input symbols are $1$.

a. (Done by hand.)

b.

$$ (0 | 1)^*111 $$

21. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that start with
    $01$.

a. (Done by hand.)

b.

$$ 01(0 | 1)^* $$

22. Input alphabet $= \{a, b\}$; Accepts the set of all strings of length at
    least $2$ for which the final two input symbols are the same.

a. (Done by hand.)

b.

$$ (a|b)^*(aa|bb) $$

23. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that start with
    $01$ or $10$.

a. (Done by hand.)

b.

$$ (01|10)(0 | 1)^* $$

24. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that start with
    $101$.

a. (Done by hand.)

b.

$$ 101(0|1)^* $$

25. Input alphabet $= \{0, 1\}$; Accepts the set of all strings that end in
    $10$.

a. (Done by hand.)

b.

$$ (0|1)^*10 $$

26. $Input alphabet $= \{a, b\}$$; Accepts the set of all strings that contain
    exactly two $b$'s.

a. (Done by hand.)

b.

$$ a^*ba^*ba^* $$

27. Input alphabet $$i= \{0, 1\}; Accepts the set of all strings that start with
    $0$ and contain exactly one $1$.

a. (Done by hand.)

b.

$$ 0^+10^* $$

28. Input alphabet. $= \{0, 1\}$; Accepts the set of all strings that contain
    the pattern $010$.

a. (Done by hand.)

b.

$$ (0 | 1)^*010(0 | 1)^* $$

In 29-47, design a finite-state automaton to accept the language defined by the
regular expression in the referenced exercise from Section 12.1.

29. Exercise 16

Regex:

$$ 0^*1(0^*1^*)^* $$

(Done by hand.)

30. Exercise 17

Regex:

$$ b^* | b^*ab^* $$

(Done by hand.)

31. Exercise 18

Regex:

$$ x^*(yxxy | x)^* $$

(Done by hand.)

32. Exercise 19

Regex:

$$ b^*ab^*ab^*a $$

(Done by hand.)

33. Exercise 20

Regex:

$$ 1(0 | 1)^*00 $$

(Done by hand.)

34. Exercise 21

Regex:

$$ (x | y)y(x | y)^* $$

(Done by hand.)

35. Exercise 24

Regex:

$$ (01^*2)^* $$

(Done by hand.)

36. Exercise 25

Regex:

$$ 0^*10^*(0^*10^*1)^* $$

(Done by hand.)

37. Exercise 26

Regex:

$$ (a | b)^*b(a | b)(a | b) $$

(Done by hand.)

38. Exercise 27

Regex:

$$ y^*(xy^+)^*xy^* | y^* $$

Omitted.

39. Exercise 31

Regex:

$$ pre[a - z]^+ $$

(Done by hand.)

40. Exercise 32

Regex:

$$ [A - Z]^*(BIO | INFO)[A - Z]^* $$

(Done by hand.)

41. Exercise 33

Regex:

$$ [a - z]^3[a - z]^*ly $$

(Done by hand.)

42. Exercise 34

Regex:

$$ [a - z]^*(a | e | i | o | u)[a - z]^* $$

(Done by hand.)

43. Exercise 35

Regex:

$$ [b-d f-h j-n p-t v-z]^*(a | e | i | o | u)[b-d f-h j-n p-t v-z]^* $$

(Done by hand.)

44. Exercise 36

Regex:

$$ [B-D F-H J-N P-T V-Z]^+(A | E | I | O | U)(A | E | I | O | U)[B-D F-H J-N P-T V-Z]^* $$

(Done by hand.)

45. Exercise 37

Regex:

$$ [0-9]^3-[0-9]^2-3[0-9]^26 $$

(Done by hand.)

46. Exercise 38

Regex:

$$ (800 | 888)-[0-9]^3-2[0-9]^22 $$

(Done by hand.)

47. Exercise 39

Regex:

$$ (+ | -)?[0-9]^+(\.[0-9]^+)? $$

(Done by hand.)

48. A simplified telephone switching system allows the following strings as
    legal telephone numbers:

a. A string of seven digits in which neither of the first two digits is a $0$ or
$1$ (_a local call string_).

b. A $1$ is followed by a three-digit _area code string_ (any digit except $0$
or $1$ followed by a $0$ or $1$ followed by any digit) followed by a seven-digit
local call string.

c. A $0$ alone or followed by a three-digit area code string plus a seven-digit
local call string.

Design a finite-state automaton to recognize all the legal telephone numbers in
(a), (b), and \(c\). Include an "error state" for invalid telephone numbers.

Regex is:

$$ 0([2-9](0 | 1)[0-9][2-9]^2[0-9]^5)? | (1[2-9](0 | 1)[0-9])?[2-9]^2[0-9]^5  $$

(Graph omitted, this is a bit much.)

49. Write a computer algorithm that simulates the action of the finite-state
    automaton of exercise 2 by mimicking the action of the transition diagram.

Omitted.

50. Write a computer algorithm that simulates the action of the finite-state
    automaton of exercise 8 by repeated application of the next-state function.

Omitted.

51. Let $L$ be the language consisting of all strings of the form $a^mb^n$,
    where $m$ and $n$ are positive integers and $m \geq n$. Show that there is
    no finite-state automaton that accepts $L$.

Omitted.

52. Let $L$ be the language consisting of all strings of the form $a^mb^n$,
    where $m$ and $n$ are positive integers and $m \leq n$. Show that there is
    no finite-state automaton that accepts $L$.

Omitted.

53. Let $L$ be the language consisting of all strings of the form $a^n$, where
    $n = m^2$, for some positive integer $m$. Show that there is no finite-state
    automaton that accepts $L$.

Omitted.

54.

a. Let $A$ be a finite-state automaton with input alphabet $\Sigma$, and suppose
$L(A)$ is the language accepted by $A$. The complement of $L(A)$ is the set of
all strings over $\Sigma$ that are not in $L(A)$. Show that the complement of a
regular language is regular by proving the following: If $L(A)$ is the language
accepted by a finite-state automaton $A$, then there is a finite-state automaton
$A'$ that accepts the complement of $L(A)$.

Omitted.

b. Show that the intersection of any two regular languages is regular as
follows: First prove that if $L(A_1)$ and $L(A_2)$ are languages accepted by
automata $A_1$ and $A_2$, respectively, then there is an automaton $A$ that
accepts $(L(A_1))^c \cup (L(A_2))^c$. Then use one of De Morgan's laws for sets,
the double complement law for sets, and the result of part (a) to prove that
there is an automaton that accepts $L(A_2) \cap L(A_2)$.

Omitted.

---

Page 891

**Exercise Set 12.3**

1. Consider the finite-state automaton $A$ given by the following transition
   diagram:

(see Page 891 for diagram.)

a. Find the $0$-, $1$-, and $2$-equivalence classes of states of $A$.

b. Draw the transition diagram for $\bar{A}$, the quotient automaton of $A$.

2. Consider the finite-state automaton $A$ given by the following transition
   diagram:

(see Page 891 for diagram.)

a. Find the $0$-, $1$-, and $2$-equivalence classes of states of $A$.

b. Draw the transition diagram for $\bar{A}$, the quotient automaton of $A$.

3. Consider the finite-state automaton $A$ discussed in Example 12.3.1:

(see Page 891 for diagram.)

a. Find the $0$-, and $1$-equivalence classes of states of $A$.

b. Draw the transition diagram of $\bar{A}$, the quotient automaton of $A$.

4. Consider the finite-state automaton $A$ given by the following transition
   diagram:

(see Page 892 for diagram.)

a. Find the $0$-, $1$-, $2$-, and $3$-equivalence classes of states of $A$.

b. Draw the transition diagram for $\bar{A}$, the quotient automaton of $A$.

5. Consider the finite-state automaton $A$ given by the following transition
   diagram:

(see Page 892 for diagram.)

a. Find the $0$-, $1$-, $2$-, and $3$-equivalence classes of states of $A$.

b. Draw the transition diagram for $\bar{A}$, the quotient automaton of $A$.

6. Consider the finite-state automaton $A$ given by the following transition
   diagram:

(see Page 892 for diagram.)

a. Find the $0$-, $1$-, $2$-, and $3$-equivalence classes of states of $A$.

b. Draw the transition diagram for $\bar{A}$, the quotient automaton of $A$.

7. Are the automata $A$ and $A'$ shown below equivalent?

(see Page 892 for diagram.)

8. Are the automata $A$ and $A'$ shown below equivalent?

(see Page 893 for diagram.)

9. Are the automata $A$ and $A'$ shown below equivalent?

(see Page 893 for diagram.)

10. Are the automata $A$ and $A'$ shown below equivalent?

(see Page 893 for diagram.)

11. Prove property (12.3.1).

12. How should the proof of property (12.3.1) be modified to prove property
    (12.3.2)?

13. Prove property (12.3.3).

14. Prove property (12.3.4).

15. Prove property (12.3.5).

16. Prove property (12.3.6).

17. Prove that if two states of a finite-state automaton are $k$-equivalent for
    some integer $k$, then those states are $m$-equivalent for every nonnegative
    integer $m < k$.

18. Write a complete proof of property (12.3.7).

19. Write a complete proof of property (12.3.8).
