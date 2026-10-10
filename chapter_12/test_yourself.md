Page 861

**Test Yourself**

1. If $x$ and $y$ are strings, the concatenation of $x$ and $y$ is ____.

the string obtained by writing all the characters of $x$ followed by all the
characters of $y$.

2. If $L$ and $L'$ are languages, the concatenation of $L$ and $L'$ is ____.

$$ \{xy | x \in L \wedge y \in L' \} $$

3. If $L$ and $L'$ are languages, the union of $L$ and $L'$ is ____.

$$ \{x | x \in L \cup L' \} $$

4. If $L$ is a language, the Kleene closure of $L$ is ____.

$$ \{x | x \text{ is a concatenation of any finite number of strings of } L\} $$

5. The set of regular expressions over an alphabet $\Sigma$ is defined
   recursively. The base for the definition is the statement that ____. The
   recursion for the definition specifies that if $r$ and $s$ are any regular
   expressions over $\Sigma$, then the following are also regular expressions in
   the set: ____, ____, and ____.

$\emptyset, \lambda$, and each individual symbol in $\Sigma$ are regular
expressions over $\Sigma$; $(rs)$; $(r | s)$; $(r^*)$

6. The function that associates a language to each regular expression over an
   alphabet $\Sigma$ is defined recursively. The base for the definition is the
   statement that $L(\emptyset) =$ ____, $L(\lambda) =$ ____, and $L(a) =$ ____
   for every $a$ in $\Sigma$. The recursion for the definition specifies that if
   $L(r)$ and $L(r')$ are the languages defined by the regular expressions $r$
   and $r'$ over $\Sigma$, then $L(rr') =$ ____, $L(r | r') =$ ____, and
   $L(r^*) =$ ____.

$\emptyset$; $\{\lambda\}$; $\{a\}$; $L(r)L(r')$; $L(r) \cup L(r')$ $(L(r))y*$

7. The notation $[A - C]$ is an example of a ____ and denotes the regular
   expression ____.

character class; $(A | B | C)$

8. Use of a single dot in a regular expression stands for ____.

an arbitrary character

9. The symbol ^, placed at the beginning of a character class, indicates ____.

a character of the same type as those in the range of the class is to occur at
that point in the string except for one of the specific characters indicated
after the ^ sign

10. If $r$ is a regular expression, the notation $r +$ denotes ____.

the concatenation of $r$ with itself any positive finite number of times

11. If $r$ is a regular expression, the notation $r\text{?}$ denotes ____.

$(\lambda | r)$

12. If $r$ is a regular expression, the notation $r\{n\}$ denotes ____ and the
    notation $r\{m, n\}$ denotes ____.

the concatenation of $r$ with itself exactly $n$ times; the concatenation of $r$
with itself anywhere from $m$ through $n$ times
