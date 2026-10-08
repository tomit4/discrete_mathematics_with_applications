Page 862

**Exercise Set 12.1**

In 1 and 2, let $\Sigma = \{x, y\}$ be an alphabet.

1.

a. Let $L_1$ be the language consisting of all strings over $\Sigma$ that are
palindromes and have length $\leq 4$. List the elements of $L_1$ between braces.

b. Let $L_2$ be the language consisting of all strings over $\Sigma$ that begin
with an $x$ and have length $\leq 3$. List the elements of $L_2$.

2.

a. Let $L_3$ be the language consisting of all strings over $\Sigma$ of length
$\leq 3$ in which all the $x$'s appear to the left of all the $y$'s. List the
elements of $L_3$ between braces.

b. List between braces the elements of $\Sigma^4$, the set of all strings of
length $4$ over $\Sigma$.

c. Let $A = \Sigma^1 \cup \Sigma^1$ and $B = \Sigma^3 \cup \Sigma^4$. Describe
$A$, $B$, and $A \cup B$ in words.

3.

a. If the expression $ab + cd + \cdot$ in postfix notation is converted to infix
notation, what is the result?

b. Let $\Sigma = \{1, 2, *, /\}$ and let $L$ be the set of all strings over
$\Sigma$ obtained by writing first a number ($1$ or $2$), then a second number
($1$ or $2$), which can be the same as the first one, and finally an operation
(denoted $*$ or $/$, where $*$ indicates multiplication and $/$ indicates
division). Then $L$ is a set of postfix, or reverse Polish, expressions. List
all the elements of $L$ between braces, and evaluate the resulting expressions.

In 4-6, describe $L_1L_2, L_1 \cup L_2$, and $(L_1 \cup L_2)^*$ for the given
languages $L_1$ and $L_2$.

4. $L_1$ is the set of all strings of $a$'s and $b$'s that start with an $a$ and
   contain only that one $a$; $L_2$ is the set of all strings of $a$'s and $b$'s
   that contain an even number of $a$'s.

5. $L_1$ is the set of all strings of $a$'s, $b$'s, and $c$'s that contain no
   $c$'s and have the same number of $a$'s as $b$'s; $L_2$ is the set of all
   strings of $a$'s, $b$'s, and $c$'s that contain no $a$'s or $b$'s.

6. $L_1$ is the set of all strings of $0$'s and $1$'s that start with a $0$;
   $L_2$ is the set of all strings of $0$'s and $1$'s that end with a $0$.

In 7-9, add parentheses to emphasize the order of precedence in the given
expressions.

7. $(a | b^*b)(a^*|ab)$

8. $0*1 | 0(0^*1)^*$

9. $(x | yz^*)^*(yx | (yz)^*z)$

In 10-12, use the rules about the order of precedence to eliminate the
parentheses in the given regular expression.

10. $((a(b^*)) | (c(b^*))) ((ac) | (bc))$

11. $(1(1^*)) | ((1(0^*)) | ((1^*)1))$

12. $(xy)(((x^*)y)^*) | (((yx) | y)(y^*))$

In 13-15, use set notation to derive the language defined by the given regular
expression. Assume $\Sigma = \{a, b, c\}$.

13. $\lambda | ab$

14. $\emptyset | \lambda$

15. $(a | b)c$

In 16-18, write five strings that belong to the language defined by the given
regular expression.

16. $0^*1(0^*1^*)^*$

17. $b^*|b^*ab^*$

18. $x^*(yxxy|x)^*$

In 19-21, use words to describe the language defined by the given regular
expression.

19. $b^*ab^*ab^*a$

20. $1(0|1)^*00$

21. $(x|y)y(x|y)^*$

In 22-24, indicate whether the given strings belong to the language defined by
the given regular expression. Briefly justify your answers.

22. Expression: $(b|\lambda)a(a|b)^*a(b|\lambda)$, strings: $aaaba$, $baabb$

23. Expression: $(x^*y|zy^*)^*$, strings: $zyyxz$, $zyyzy$

24. Expression: $(01^*2)^*$, strings: $120$, $01202$

In 25-27, find a regular expression that defines the given language.

25. The language consisting of all strings of $0$'s and $1$'s with an odd number
    of $1$'s. (Such a string is said to have _odd parity_.)

26. The language consisting of all strings of $a$'s and $b$'s in which the third
    character from the end is a $b$.

27. The language consisting of strings of $x$'s and $y$'s in which the elements
    in every pair of $x$'s are separated by at least one $y$.

Let $r$, $s$, and $t$ be regular expressions over $\Sigma = \{a, b\}$. In 28-30,
determine whether the two regular expressions define the same language. If they
do, describe the language. If they do not, give an example of a string that is
in one of the languages but not the other.

28. $(r | s)t$ and $rt | st$

29. $(rs)^*$ and $r^*s^*$

30. $(rs)^*$ and $((rs)^*)^*$

In 31-39, write a regular expression to define the given set of strings. Use the
shorthand notations given in the section whenever convenient. In most cases,
your expressions will describe other strings in addition to the given ones, but
try to make the answer fit the given strings as closely as possible within
reasonable space limitations.

31. All words that are written in lowercase letters start with the letters $pre$
    but do not consist of $pre$ all by itself.

32. All words that are written in uppercase letters, and contain the letters
    $BIO$ (as a unit) or $INFO$ (as a unit).

33. All words that are written in lowercase letters, end in $ly$, and contain at
    least five letters.

34. All words that are written in lowercase letters and contain at least one of
    the vowels a, e, i, o, or u.

35. All words that are written in lowercase letters and contain exactly one of
    the vowels a, e, i, o, or u.

36. All words that are written in uppercase letters and do not start with one of
    the vowels A, E, I, O, or U but contain exactly two of these vowels next to
    each other.

37. All United States social security numbers (which consist of three digits, a
    hyphen, two digits, another hyphen, and finally four more digits), where the
    final four digits start with a 3 and end with a 6.

38. All telephone numbers that have three digits, then a hyphen, then three more
    digits, then a hyphen, and then four digits, where the first three digits
    are either 800 or 888 and the last four digits start and end with a 2.

39. All signed or unsigned numbers with or without a decimal point. A signed
    number has one of the prefixes $+$ or $-$, and an unsigned number does not
    have a prefix. Represent the decimal point as \\. to distinguish it from the
    single dot symbol for an arbitrary character.

40. Write a regular expression to perform a complete check to determine whether
    a given string represents a valid date from 1980 to 2079 written in one of
    the formats of Example 12.1.11 (During this period, leap years occur every
    four years starting in 1980.)

41. Write a regular expression to define the set of strings of $0$'s and $1$'s
    with an even number of $0$'s and even number of $1$'s.
