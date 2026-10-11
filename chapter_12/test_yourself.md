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

---

Page 878

**Test Yourself**

1. The five objects that make up a finite-state automaton are ____, ____, ____,
   ____, and ____.

a finite set of input symbols; a finite set of states; a designated initial
state; a designated set of accepting states; a next-state function that
associates a "next-state" with each state and input symbol of the automaton

2. The next-state table for an automaton shows the values of ____.

the next-state function for each state and input symbol of the automaton

3. In the annotated next-state table, the initial state is indicated with an
   ____ and the accepting states are marked by ____.

arrow; double circles

4. A string $w$ consisting of input symbols is accepted by a finite-state
   automaton $A$ if, and only if, ____.

when the symbols in the string are input to the automaton in sequence from left
to right, starting from the initial state, the automaton ends up in an accepting
state

5. The language accepted by a finite-state automaton $A$ is ____.

the set of strings that are accepted by $A$

6. If $N$ is the next-state function for a finite-state automaton $A$, the
   eventual-state function $N^*$ is defined as follows: For each state $s$ of
   $A$ and for each string $w$ that consists of input symbols of $A$,
   $N^*(s, w) =$ ____.

the state to which $A$ goes if it is in state $s$ and the characters of $w$ are
input to it in sequence

7. One part of Kleene's theorem says that given any language that is accepted by
   a finite-state automaton, there is ____.

a regular expression that defines the same language

8. The second part of Kleene's theorem says that given any language defined by a
   regular expression, there is ____.

a finite-state automaton that accepts the same language

9. A regular language is ____.

a language defined by a regular expression (_Or:_ a language accepted by a
finite-state automaton)

10. Given the language consisting of all strings of the form $a^kb^k$, where $k$
    is a positive integer, the pigeonhole principle can be used to show that the
    language is ____.

not regular
