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
