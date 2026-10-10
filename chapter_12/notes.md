Page 853

**Alphabet $\Sigma$:** a finite set of characters

**String over $\Sigma$:** (1) a finite juxtaposition of elements (called
**characters**) of $\Sigma$ or (2) a null string $\lambda$

**Length of a string over $\Sigma$:** the number of characters that made up the
string, with the null string having length $0$.

**Formal language over $\Sigma$:** a set of strings over the alphabet

---

Page 853

**Notation**

Let $\Sigma$ be an alphabet. For each nonnegative integer $n$, let

$$ \Sigma^n = \text{ the set of all strings over } \Sigma \text{ that have length } n $$

$$ \Sigma^+ = \text{ the set of all strings over } \Sigma \text{ that have length at least } 1 $$

and

$$ \Sigma^* = \text{ the set of all strings over } \Sigma $$

---

Page 855

**Definition**

Let $\Sigma$ be an alphabet. Given any strings $x$ and $y$ over $\Sigma$, the
**concatenation of $x$ and $y$** is the string obtained by writing all the
characters of $x$ followed by all the characters of $y$. For any languages $L$
and $L'$ over $\Sigma$, three new languages can be defined as follows:

The **concatenation of $L$ and $L'$**, denoted $LL'$, is

$$ LL' = \{xy | x \in L \text{ and } y \in L'\} $$

The **union of $L$ and $L'$**, denoted $L \cup L'$, is

$$ L \cup L' = \{x | x \in L \text{ or } x \in L'\} $$

The **Kleene closure of $L$**, denoted $L^*$, is

$$ L^*  = \{x | x \text{ is the concatenation of any finite number of strings in } L\} $$

Note that $\lambda$ is in $L^*$ because it is regarded as a concatenation of
zero strings in $L$.

---

Page 855

**Definition**

Given an alphabet $\Sigma$, the following are **regular expressions over
$\Sigma$**:

I. Base: $\emptyset, \lambda$, and each individual symbol in $\Sigma$ are
regular expressions over $\Sigma$.

II. Recursion: If $r$ and $s$ are regular expressions over $\Sigma$, then the
following are also regular expressions over $\Sigma$:

(i) $(rs)$

(ii) $(r | s)$

(iii) $(r^*)$

where $rs$ denotes the concatenation of $r$ and $s$, $r^*$ denotes the
concatenation of $r$ with itself any finite number (including zero) of times,
and $r | s$ denotes either one of the strings $r$ or $s$. The regular expression
$r^*$ is called the **Kleene closure** of $r$.

III. Restriction: Nothing is a regular expression over $\Sigma$ except for
objects defined in (I) and (II) above.

---

Page 856

**Definition**

For any finite alphabet $\Sigma$, the function $L$ that associates a language to
each regular expression over $\Sigma$ is defined by (I)-(III) below. For each
such regular expression $r$, $L(r)$ is called the **language defined by $r$**.

I. Base: $L(\emptyset) = \emptyset, L(\lambda) = \{\lambda\}, L(a) = \{a\}$ for
every $a$ in $\Sigma$.

II. Recursion: If $L(r)$ and $L(r')$ are the languages defined by the regular
expressions $r$ and $r'$ over $\Sigma$, then

(i) $L(rr') = L(r)L(r')$

(ii) $L(r | r') = L(r) \cup L(r')$

(iii) $L(r^*) = (L(r))^*$

III. Restriction: The function $L$ is completely determined by I and II above.

---

Page 866

**Definition**

A **finite-state automaton $A$** consists of five objects:

1. A finite set $I$, called the **input alphabet**, of input symbols.

2. A finite set $S$ of **states** the automaton can assume.

3. A designated state $s_0$ called the **initial state**.

4. A designated set of states called the set of **accepting states**.

5. A **next-state function $N: S \times I \to S$** that associates a
   "next-state" to each ordered pair consisting of a "current state" and a
   "current input." For each state $s$ and $S$ and input symbol $m$ in $I$,
   $N(s, m)$ is the state to which $A$ goes if $m$ is input to $A$ when $A$ is
   in state $s$.

---

Page 868

**Definition**

Let $A$ be a finite-state automaton with set of input symbols $I$. Let $I^*$ be
the set of all strings over $I$, and let $w$ be a string in $I^*$. Then **$w$ is
accepted by $A$** if, and only if, $A$ goes to an accepting state when the
symbols of $w$ are input to $A$ in sequence from left to right, starting when
$A$ is in its initial state. The **language accepted by $A$**, denoted $L(A)$,
is the set of all strings that are accepted by $A$.

---

Page 869

**Definition**

Let $A$ be a finite-state automaton with set of input symbols $I$, the set of
states $S$, and next-state function $N: S \times I \to S$. Let $I^*$ be the set
of all strings over $I$, and define the **eventual-state function
$N^*: S \times I^* \to S$** as follows:

For any state $s$ and for any input string $w$,

$$ N^*(s, w) = \left[\text{the state to which } A \text{ goes if the symbols of } w \text{ are input to } A \text{ in sequence, starting when } A \text{ is in state } s\right] $$

---

Page 873

**Algorithm 12.2.1 A Finite-State Automaton**

_[This algorithm simulates the action of the finite-state automaton of Figure
12.2.5 by mimicking the functioning of the transition diagram. The states are
denoted $0, 1, 2$ and $3$.]_

**Input:** string _[a string of $0$'s and $1$'s plus an end marker $e$]_

**Algorithm Body:**

$\textit{state } := 0\\ \textit{symbol: } = \text{ first symbol in the input string}\\ \textbf{while } (\textit{symbol } \neq \textit{e})\\ \ \ \textbf{if } \textit{state} = 0 \textbf{ then if } \textit{symbol} = 0\\ \ \ \ \ \textbf{then } \textit{state} := 1\\ \ \ \ \ \textbf{else } \textit{state} = 0\\ \ \ \textbf{else if } \textit{state} = 1 \textbf{ then if } \textit{symbol} = 0\\ \ \ \ \ \textbf{then } \textit{state} := 1 \\ \ \ \ \ \textbf{else } \textit{state} := 2\\ \ \ \textbf{else if } \textit{state} = 2 \textbf{ then if } \textit{symbol} = 0\\ \ \ \ \ \textbf{then } \textit{state} := 1\\ \ \ \ \ \textbf{else } \textit{state} := 3\\ \ \ \textbf{else if } \textit{state} = 3 \textbf{ then if } \textit{symbol} = 0\\ \ \ \ \ \textbf{then } \textit{state} := 1\\ \ \ \ \ \textbf{else } \textit{state} := 0\\ \ \ \textit{symbol} := \text{next symbol in the input string}\\ \textbf{end while}$

_[After execution of the $\textbf{while}$ loop, the value of state is $3$ if,
and only if, the input string ends iin $011e$.]_

**Output:** $\textit{state}$

---

Page 873

**Algorithm 12.2.2 A Finite-State Automaton**

_[This algorithm simulates the action of the finite-state automaton of Figure
12.2.5 by repeated application of the next-state function. The states are
denoted $0, 1, 2$, and $3$._

**Input:** $\textit{string}$ _[a string of $0$'s and $1$'s plus an end marker
$e$]_

**Algorithm Body:**

$N(0, 0) := 1, N(0, 1) := 0, N(1, 0) := 1, N(1, 1) := 2,\\ N(2, 0) := 1, N(2, 1) := 3, N(3, 0) := 1, N(3, 1) := 0\\ \textit{state} := 0\\ \textit{symbol} := \text{first symbol in the input string}\\ \textbf{while } (\textit{symbol} \neq e)\\ \ \ \textit{state} := N(\textit{state}, \textit{symbol})\\ \ \ \textit{symbol} := \text{next symbol in the input string}\\ \textbf{end while}$

_[After execution of the $\textbf{while}$ loop, the value of state is $3$ if,
and only if, the input string ends in $011e$.]_

**Output:** $\textit{state}$

---

Page 874

**Kleene's Theorem, Part 1**

Given any language that is accepted by a finite-state automaton, there is a
regular expression that defines the same language.

**Proof:**

Suppose $A$ is a finite-state automaton with a set $I$ of input symbols, a set
$S$ of $n$ states, and a next-state function $N: S \times I \to S$. Let $I^*$
denote the set of all strings over $I$. Number the states
$s_1, s_2, s_3, \dots, s_n$, using $s_1$ to denote the initial state, and for
each integer $k = 1, 2, 3, \dots, n$, let

$$ L_{i, j}^k = \left\{ x \in I^* \mid \text{when the symbols of } x \text{ are input to } A \text{in sequence, } A \text{ goes from state } s_i \text{ to state } s_j \text{ without traveling through an intermediate state } s_h \text{ for which } h > k\right\} $$

Note that either index $i$ or index $j$ in $L_{i, j}^k$ could be greater than
$k$; the only restriction is that the symbols of a string in $L_{i, j}^k$ cannot
make $A$ both enter and exit an intermediate state with index greater than $k$.

If $s_j$ is an accepting state and if $k = n$ and $i = 1$, then $L_{i, j}^n$ is
the set of all strings that send $A$ to $s_j$ when the symbols of the string are
input to $A$ in sequence starting from $s_1$. Thus

$$ L_{1, j}^n \subseteq L(A) $$

Moreover, because the sequence of symbols in every string in $L(A)$ sends $A$ to
_some_ accepting state $s_j$,

$$ L(A) \text{ is the union of all the sets } L_{1, j}^n \text{, where } s_j \text{ is an accepting state} $$

We use a version of mathematical induction to build up a set of regular
expressions over $I$. Let the property $P(m)$ be the sentence

For any pair of integers $i$ and $j$ with $1 \leq i$, $j \leq n$, there is a
regular expression $r_{i, j}^m$ that defines $L_{i, j}^m$.

_Show that $P(0)$ is true:_

For each pair of integers $i$ and $j$ with $1 \leq i$, $j \leq n$, $L_{i, j}^0$
is the set of all strings that send $A$ from $s_i$ to $s_j$ without sending it
through any intermediate state $s_h$ for which $h > 0$. Because the subscript of
every state in $A$ is greater than zero, the strings in $L_{i, j}^0$ do not send
$A$ through any intermediate states at all, and so each is a single input symbol
from $I$. In other words, for all integers $i$ and $j$ with $1 \leq i$,
$j \leq n$,

$$ L_{i, j}^0 = \{a \in I | N(s_i, a) = s_j\} $$

Hence $L_{i, j}^0$ is a subset of $I$, and so (because $I$ is finite), there is
an integer $M$ so that we may denote the elements of $L_{i, j}^0$ as follows:

$$ L_{i, j}^0 = \{a_1, a_2, a_3, \dots, a_M\} \subseteq I $$

Now, by definition of regular expression, each single input symbol of $I$ is a
regular expression over $I$; thus every element of $L_{i, j}^0$ is a regular
expression over $I$. The result is that for all integers $i$ and $j$ with
$1 \leq i$, $j \leq n$, the following regular expression defines $L_{i, j}^0$:

$$ a_1 | a_2 | a_3 | \cdots | a_M $$

_Show that for every integer $k$ with $0 \leq k \leq n$, if $P(k)$ is true then
$P(k + 1)$ is true:_

Let $k$ be any integer with $1 \leq k \leq n$, and suppose that

For each pair of integers $p$ and $q$ with $1 \leq p$, $q \leq n$, there is a
regular expression $r_{p, q}^k$ that defines $L_{p, q}^k$.

This is the inductive hypothesis.

We will show that

For each pair of integers $i$ and $j$ with $1 \leq i$, $j \leq n$, there is a
regular expression $r_{i, j}^{k + 1}$ that defines $L_{i, j}^{k + 1}$.

So suppose that $i$ and $j$ are any pair of integers with $1 \leq i$,
$j \leq n$, and observer that any string in $L_{i, j}^{k + 1}$ sends $A$ from
$s_i$ to $s_j$, either by a route that makes $A$ pass through $s_{k + 1}$ or by
a route that does not make $A$ pass through $s_{k + 1}$. Now each string that
sends $A$ from $s_i$ to $s_j$ and makes $A$ pass through $s_{k + 1}$ one or more
times can be broken into segments. The symbols in the first segment send $A$
from $s_i$ to $s_{k + 1}$ without making $A$ pass through $s_{k + 1}$ to $s_j$
without making $A$ pass through $s_{k + 1}$. (The intermediate segment could be
the null string.) A typical path showing two intermediate segments is
illustrated on the next page.

(See Page 876 for illustration.)

Note that each intermediate segment of the string is in $L_{k + 1, k + 1}^k$,
and by assumption the regular expression $r_{k + 1, k + 1}^k$ defines this set.
By the same reasoning, $r_{i, k + 1}^k$ defines the set of all possible first
segments of the string, and $r_{k + 1, j}^k$ defines the set of all strings that
send $A$ from $s_i$ to $s_j$ without making it pass through a state $s_m$ with
$m > k$. Thus we may define the regular expression $r_{i, j}^{k + 1}$ as
follows:

$$ r_{i, j}^{k + 1} = r_{i, j}^k | r_{i, k + 1}^k(r_{k + 1, k + 1}^k)^*r_{k + 1, j}^k $$

Then $r_{i, j}^{k + 1}$ defines the set of all strings that send $A$ from $s_i$
to $s_j$ without making it pass through any states $s_m$ with $m > k + 1$, and
so $r_{1, j}^{k + 1}$ defines $L_{1, j}^{k + 1}$ _[as was to be shown.]_

To complete the proof, let $s_{j_1}, s_{j_2}, \dots, s_{j_k}$ be the accepting
state of $A$. Because $L(A)$ is the union of all the $L_{1, j}^n$ where $s_j$ is
an accepting state, we have

$$ L(A) = L\left(r_{1, j_1}^n \cup L\left(r_{1, j_2}^n\right) \cup \cdots \cup L\left(r_{1, j_n}^n\right)\right) $$

$$ = L\left(r_{1, j_1}^n | r_{1, j_2}^n | \cdots | r_{1, j_n}^n\right) $$

by the recursive definition for the language defined by a regular expression

Thus if we let $r = r_{1, j_1}^n | r_{1, j_2}^n | \cdots | r_{1, j_n}^n$, we
have that $L(A) = L(r)$. In other words, we have constructed a regular
expression $r$ that defines the language accepted by $A$.

---

Page 876

**Kleene's Theorem, Part 2**

Given any language defined by a regular expression, there is a finite-state
automaton that accepts the same language.
