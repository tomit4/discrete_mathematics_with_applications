Page 411

**Exercise Set 6.1**

1. In each of (a) -(f), answer the following questions: Is $A \subseteq B$? Is
   $B \subseteq A$? Is either $A$ or $B$ a proper subset of the other?

a. $A = \{2, \{2\}, (\sqrt{2})^2\}$, $B = \{2, \{2\}, \{\{2\}\}\}$

$A \subseteq B$ ?:

$$ A = \{2, \{2\}, (\sqrt{2})^2\} = \{2, \{2\}, 2\} = \{2, \{2\}\} $$

Yes, every element in $A$ is in $B$.

$B \subseteq A$ ?:

No, because $\{\{2\}\}$ is an element of $B$, but is not an element of $A$, so
$\B \nsubseteq A$.

Is either $A$ or $B$ a proper subset of the other?

Yes, $A$ is a proper subset of $B$, because every element in $A$ is in $B$, but
not every element in $B$ is in $A$.

b. $A = \{3, \sqrt{5^2 - 4^2}, 24 \mod 7\}$, $B = \{8 \mod 5\}$

$A \subseteq B$ ?:

$$ A = \{3, \sqrt{5^2 - 4^2}, 24 \mod 7\} = \{3, 3, 3\} = \{3\} $$

$$ B = \{8 \mod 5\} = \{3\} $$

Yes, $A$ is a subset of $B$ since every element of $A$ is in $B$.

$B \subseteq A$ ?:

Yes, $B$ is a subset of $A$ since every element of $B$ is in $A$.

Is either $A$ or $B$ a proper subset of the other?

Yes, both $A$ and $B$ are proper subsets of the other since $A = B$.

c. $A = \{\{1, 2\}, \{2, 3\}\}$, $B = \{1, 2, 3\}$

$A \subseteq B$ ?:

No, because there are no elements in $A$ that are in $B$, $A \nsubseteq B$

$B \subseteq A$ ?:

No, because there are no elements in $B$ that are in $A$, $B \nsubseteq A$

Is either $A$ or $B$ a proper subset of the other?

No, since neither set share any elements, neither is a proper subset of the
other.

d. $A = \{a, b, c\}$, $B = \{\{a\}, \{b\}, \{c\}\}$

$A \subseteq B$ ?:

No, because there are no elements in $A$ that are in $B$, $A \nsubseteq B$

$B \subseteq A$ ?:

No, because there are no elements in $B$ that are in $A$, $B \nsubseteq A$

Is either $A$ or $B$ a proper subset of the other?

No, since neither set share any elements, neither is a proper subset of the
other.

e. $A = \{\sqrt{16}, \{4\}\}$, $B = \{4\}$

$A \subseteq B$ ?:

$$ A = \{\sqrt{16}, \{4\}\} = \{4, \{4\}\} $$

No, because every element of $A$ is not an element in $B$ ($4$ is not in $B$),
$A \nsubseteq B$.

$B \subseteq A$ ?:

Yes, because every element in $B$ is an element in $A$, $B \subseteq A$.

Is either $A$ or $B$ a proper subset of the other?

Yes, $B$ is a proper subset of $A$ since $B \subseteq A$ and $A \nsubseteq B$.

f. $A = \{x \in \mathbb{R} | \cos x \in \mathbb{Z}\}$,
$B = \{x \in \mathbb{R} | \sin x \in \mathbb{Z}\}$

From trigonometry, we know that $\cos x = -1 \text{ or } 0 \text{ or } 1$ and
$\sin x = -1 \text{ or } 0 \text{ or } 1 $. When we evaluate for $x$ in these
cases we find:

$$ A = \{\dots, -\frac{5\pi}{2}, -\frac{3\pi}{2}, \pi, -\frac{\pi}{2}, 0, \frac{\pi}{2}, \frac{3\pi}{2}, \frac{5\pi}{2}, \dots\} $$

$$ B = \{\dots, -\frac{5\pi}{2}, -\frac{3\pi}{2}, \pi, -\frac{\pi}{2}, 0, \frac{\pi}{2}, \frac{3\pi}{2}, \frac{5\pi}{2}, \dots\} $$

$A \subseteq B$ ?: Yes.

$B \subseteq A$ ?: Yes.

Yes, $B$ is a proper subset of $A$ since $B \subseteq A$ and $A \nsubseteq B$.

Yes, since $A = B$.

2. Complete the proof from Example 6.1.3: Prove that $B \subseteq A$ where

$$ A = \{m \in \mathbb{Z} | m, = 2a \text{ for some integer } a\} $$

and

$$ B = \{n \in \mathbb{Z} | n = 2b - 2 \text{ for some integer } b\} $$

_Part 2, Proof that $B \subseteq A$:_

Suppose $x$ is a particular but arbitrarily chosen element of $B$.

By definition of $B$, there is an integer, say $b$, such that $x = 2b - 2$.

To prove that $B \subseteq A$, we must show that there is some $x$ that can
equal both $2a$, for some integer $a$, and that same $x$ can also equal
$2b - 2$.

$$ 2b - 2 = 2a $$

$$ a = b - 1 $$

By the difference integers, $a$ is an integer. Then, by substitution:

$$ 2a = 2(b - 1) $$

$$ = 2b - 2 $$

$$ = x $$

Thus, by definition of $A$, $x$ is an element of $A$.

Q.E.D.

3. Let sets $R$, $S$, and $T$ be defined as follows:

$$ R = \{x \in \mathbb{Z} | x \text{ is divisible by } 2\}  $$

$$ S = \{y \in \mathbb{Z} | y \text{ is divisible by } 3\}  $$

$$ T = \{z \in \mathbb{Z} | z \text{ is divisible by } 6\}  $$

Prove or disprove each of the following statements.

a. $R \subseteq T$

$R \nsubseteq T$ since $2 \in R$ since $2 \mid 2$, but $2 \notin T$ since
$6 \cancel{\mid} 2$.

b. $T \subseteq R$

**Proof:**

Suppose $n$ is any integer such that $6 \mid n$, therefore $n \in T$.

By the definition of divisibility:

$$ n = 6m $$

for some integer $m$.

$$ n = 2(3m) $$

By the product of integers, $3m$ is an integer. It follows that
$n = 2 \cdot (\text{some integer})$. Thus $2 \mid n$, so $n \in R$. This is what
was to be shown.

Q.E.D.

c. $T \subseteq S$

**Proof:**

Suppose $n$ is any integer such that $6 \mid n$, therefore $n \in T$.

By the definition of divisibility:

$$ n = 6m $$

for some integer $m$.

$$ n = 3(2m) $$

By the product of integers, $2m$ is an integer. It follows that
$n = 3 \cdot (\text{some integer})$. Thus $3 \mid n$, so $n \in S$. This is what
was to be shown.

Q.E.D.

4. Let $A = \{n \in \mathbb{Z} | n = 5r \text{ for some integer } r\}$ and
   $B = \{m \in \mathbb{Z} | m = 20s \text{ for some integer } s\}$. Prove or
   disprove each of the following statements.

a. $A \subseteq B$

$A \nsubseteq B$ since $5 \in A$ since $5 \mid 5$, but $5 \notin B$ since
$5 \cancel{\mid} 20$.

b. $B \subseteq A$

**Proof:**

Suppose $n$ is any integer such that $20 \mid n$, therefore $n \in B$.

By the definition of divisibility:

$$ n = 20m $$

for some integer $m$.

$$ n = 5(4m) $$

By the product of integers, $4m$ is an integer. It follows that
$n = 5 \cdot (\text{some integer})$. Thus $5 \mid n$, so $n \in A$. This is what
was to be shown.

Q.E.D.

5. Let $C = \{n \in \mathbb{Z} | n = 6r - 5 \text{ for some integer } r\}$ and
   $D = \{m \in \mathbb{Z} | m = 3s + 1 \text{ for some integer } s\}$. Prove or
   disprove each of the following statements.

a. $C \subseteq D$

**Proof:**

Suppose $n$ is any integer such that $n = 6r - 5$ for some integer $r$, which
means that $n \in C$.

Also suppose that $m$ is any integer such that $m = 3s + 1$ for some integer
$s$, which means that $m \in S$.

We must show that there exists some $r$ that when substituted for $s$ will
satisfy the definition of $n$.

Let $s = 2r - 2$. Then, by substitution:

$$ m = 3(2r - 2) + 1 $$

$$ = 6r - 6 + 1 $$

$$ = 6r - 5 $$

$$ = n $$

By the product and difference of integers, $6r - 5$ is an integer, therefore
$n \in D$. This is what was to be shown.

Q.E.D.

b. $D \subseteq C$

**Disproof:**

$D \nsubseteq C$ because there are elements in $D$ that are not in $C$. For
example $4$ is in $D$ because $4 = 3(1) + 1$, but $4$ is not in $C$. If $4$ were
in $C$, this would mean:

$$ 4 = 6r - 5 $$

for some integer $r$.

$$ 4 + 5 = 6r $$

$$ 9 = 6r $$

$$ \frac{9}{6} = r $$

$$ \frac{3}{2} = r $$

But $\dfrac{3}{2}$ is not an integer. This is a contradiction, therefore
$D \nsubseteq C$.

Q.E.D.

6. Let $A = \{x \in \mathbb{Z} | x = 5a + 2 \text{ for some integer } a\}$,
   $B = \{y \in \mathbb{Z} | y = 10b - 3 \text{ for some integer } b\}$, and
   $C = \{z \in \mathbb{Z} | z = 10c + 7 \text{ for some integer } c\}$.

Prove or disprove each of the following statements.

a. $A \subseteq B$

**Disproof (by counterexample):**

Suppose $n$ is any integer such that $n = 5a + 2$ for some integer $a$. This
means that $n \in A$.

Suppose also that there is some integer $m$ such that $m = 10b - 3$ for some
integer $b$. This means that $m \in B$.

To show that there is some integer $b$ that will satisfy $n$, we must relate it
to $a$:

$$ 5a + 2 = 10b - 3 $$

$$ 5a + 5 = 10b $$

$$ 5a + 5 = 10b $$

$$ \frac{1}{2}a + \frac{1}{2} = b $$

$$ \frac{a + 1}{2} = b $$

In order for $A \subseteq B$, every element of $A$ must be in $B$. If $a = 0$,
then $n = 2$, so $n \in A$. If $a = 0$, then $b = \dfrac{1}{2}$, which is not an
integer, thus $2 \notin B$. Therefore $A \nsubseteq B$.

Q.E.D.

b. $B \subseteq A$

**Proof:**

Suppose $y$ is any integer such that $y = 10b - 3$ for some integer $b$. This
means that $y \in B$.

Let's first find $a$ as it relates to $y$.

$$ y = 5a + 2 $$

$$ 10b - 3 = 5a + 2 $$

$$ 10b - 5 = 5a $$

$$ 2b - 1 = a $$

So let $a = 2b - 1$.

Then substitute in for the condition for $A$:

$$ x = 5a + 2 $$

$$ = 5(2b - 1) + 2 $$

$$ = 10b - 5 + 2 $$

$$ = 10b - 3 $$

$$ = y $$

Therefore $y \in A$.

Q.E.D.

c. $B = C$

To prove $B = C$, we must prove both that $B \subseteq C$ and $C \subseteq B$.

_Prove $B \subseteq C$:

Suppose $y$ is any integer such that $y = 10b - 3$ for some integer $b$. This
means that $y \in B$.

Let's first find some integer $c$ as it relates to $y$:

$$ y = 10c + 7 $$

$$ 10b - 3 = 10c + 7 $$

$$ 10b - 10 = 10c $$

$$ b - 1 = c $$

So, let $c = b - 1$.

Then substitute in for the condition for $C$:

$$ z = 10c + 7 $$

$$ = 10(b - 1) + 7 $$

$$ = 10b - 10 + 7 $$

$$ = 10b - 3 $$

$$ = y $$

Thus $y \in C$, and therefore $B \subseteq C$.

_Prove $C \subseteq B$:

Suppose $z$ is any integer such that $z = 10c + 7$ for some integer $c$. This
means that $z \in C$.

Let's first find some integer $b$ as it relates to $z$:

$$ z = 10b - 3 $$

$$ 10c + 7 = 10b - 3 $$

$$ 10c + 10 = 10b $$

$$ c + 1 = b $$

So, let $b = c + 1$.

Then substitute in for the condition for $B$:

$$ y = 10b - 3 $$

$$ = 10(c + 1) - 3 $$

$$ = 10c + 10 - 3 $$

$$ = 10c + 7 $$

$$ = z $$

Therefore $z \in B$.

Thus $z \in B$, and therefore $C \subseteq B$.

Since $B \subseteq C$ and $C \subseteq B$, it follows that $B = C$. This is what
was to be shown.

Q.E.D.

7. Let $A = \{x \in \mathbb{Z} | x = 6a + 4 \text{ for some integer } a\}$,
   $B = \{y \in \mathbb{Z} | y = 18b - 2 \text{ for some integer } b\}$, and
   $C = \{z \in \mathbb{Z} | z = 18c + 16 \text{ for some integer } c\}$.

Prove or disprove each of the following statements.

a. $A \subseteq B$

**Disproof (by counterexample):**

Suppose $x$ is any integer such that $x = 6a + 4$ for some integer $a$. This
means that $x \in A$.

Let's first find some integer $b$ as it relates to $a$.

$$ x = 18b - 2 $$

$$ 6a + 4 = 18b - 2 $$

$$ 6a + 6 = 18b $$

$$ \frac{6}{18}a + \frac{6}{18} = b $$

$$ \frac{1}{3}a + \frac{1}{3} = b $$

$$ \frac{a + 1}{3} = b $$

By definition of $b$, $b$ must always be an integer for all $a$.

Suppose $a = 0$, then:

$$ x = 6(0) + 4 = 4 $$

so $4 \in A$, but:

$$ b = \frac{0 + 1}{3} = \frac{1}{3} $$

so $4 \notin B$. We can see this as $4 = 18b - 2$ results in $b = \dfrac{1}{3}$,
but $b$ must be an integer.

b. $B \subseteq A$

**Proof:**

Suppose $y$ is any integer such that $y = 18b - 2$ for some integer $b$. This
means that $y \in B$.

Let's first find some integer $a$ as it relates to $b$.

$$ y = 6a + 4 $$

$$ 18b - 2 = 6a + 4 $$

$$ 18b - 6 = 6a $$

$$ 3b - 1 = a $$

Now, substitute $a$ in for the condition for $A$:

$$ x = 6a + 4 $$

$$ = 6(3b - 1) + 4 $$

$$ = 18b - 2 $$

$$ = y $$

Therefore $B \subseteq A$.

c. $B = C$

To prove $B = C$, we must prove both that $B \subseteq C$ and $C \subseteq B$.

_Prove $B \subseteq C$:

Suppose $y$ is any integer such that $y = 18b - 2$ for some integer $b$. This
means that $y \in B$.

Let's first find some integer $c$ as it relates to $b$.

$$ y = 18c + 16 $$

$$ 18b - 2 = 18c + 16 $$

$$ 18b - 18 = 18c $$

$$ b - 1 = c $$

So, let $c = b - 1$. Now substitute $c$ in for the condition of $C$:

$$ z = 18c + 16 $$

$$ = 18(b - 1) + 16 $$

$$ = 18b - 18 + 16 $$

$$ = 18b - 2 $$

$$ = y $$

Therefore $B \subseteq C$.

_Prove $C \subseteq B$:

Suppose $z$ is any integer such that $z = 18c + 16$ for some integer $c$.

Let's first find some $b$ as it relates to $c$.

$$ z = 18b - 2 $$

$$ 18c + 16 = 18b - 2 $$

$$ 18c + 18 = 18b $$

$$ c + 1 = b $$

So, let $b = c + 1$. Now, let's substitute $b$ in for the condition for $B$.

$$ y = 18b - 2 $$

$$ = 18(c + 1) - 2 $$

$$ = 18c + 18 - 2 $$

$$ = 18c + 16 $$

$$ = z $$

Therefore $C \subseteq B$.

Since $B \subseteq C$ and $C \subseteq B$, we conclude that $B = C$. This is
what was to be shown.

Q.E.D.

8. Write in words to read each of the following out loud. Then write each set
   using the symbols for union, intersection, set difference, or set complement.

a. $\{x \in U | x \in A \text{ and } x \in B\}$

_In words:_

The set of all $x$ in $U$ such that $x$ is in $A$ and $x$ is in $B$.

_In symbolic notation:_

$$ A \cap B $$

b. $\{x \in U | x \in A \text{ or } x \in B\}$

_In words:_

The set of all $x$ in $U$ such that $x$ is in $A$ or $x$ is in $B$.

_In symbolic notation:_

$$ A \cup B $$

c. $\{x \in U | x \in A \text{ and } x \notin B\}$

_In words:_

The set of all $x$ in $U$ such that $x$ is in $A$ and $x$ is not in $B$.

_In symbolic notation:_

$$ A - B $$

d. $\{x \in U | x \notin A\}$

_In words:_

The set of all $x$ in $U$ such that $x$ is not in $A$.

_In symbolic notation:_

$$ A^c $$

9. Complete the following sentences without using the symbols $\cup$, $\cap$, or
   $-$.

a. $x \notin A \cup B$ if, and only if, _____.

$x$ is not in $A$ and $x$ is not in $B$.

b. $x \notin A \cap B$ if, and only if, _____.

$x$ is not in $A$ or $x$ is not in $B$.

c. $x \notin A - B$ if, and only if, _____.

$x$ is not in $A$, or $x$ is in $B$, or both.

Note: recall that the negation of an "and", which is $A - B$, is an "or", thus:

$$ x \in (A - B) \to x \in A \wedge x \notin B $$

so:

$$ \neg(x \in (A - B)) \to \neg(x \in A \wedge x \notin B) \to x \notin A \vee x \in B $$

10. Let $A = \{1, 3, 5, 7, 9\}$, $b = \{3, 6, 9\}$, and $C = \{2, 4, 6, 8\}$.
    Find each of the following:

a. $A \cup B$

$$ A \cup B = \{1, 3, 5, 6, 7, 9\} $$

b. $A \cap B$

$$ A \cap B = \{3, 9\} $$

c. $A \cup C$

$$ A \cup C = \{1, 2, 3, 4, 5, 6, 7, 8, 9\} $$

d. $A \cap C$

$$ A \cap C = \emptyset $$

e. $A - B$

$$ A - B = \{1, 5, 7\} $$

f. $B - A$

$$ B - A = \{6\} $$

g. $B \cup C$

$$ B \cup C = \{2, 3, 4, 6, 8, 9\} $$

h. $B \cap C$

$$ B \cap C = \{6\} $$

11. Let the universal set $\mathbb{R}$, the set of all real numbers, and let
    $A = \{x \in \mathbb{R} | 0 < x \leq 2\}$,
    $B = \{x \in \mathbb{R} | 1 \leq x < 4\}$, and
    $C = \{x \in \mathbb{R} | 3 \leq x < 9\}$. Find each of the following:

a. $A \cup B$

$$ A \cup B = \{x \in \mathbb{R} | 0 < x < 4\} $$

b. $A \cap B$

$$ A \cap B = \{x \in \mathbb{R} | 1 \leq x \leq 2\} $$

c. $A^c$

$$ A^c = \{x \in \mathbb{R} | x \leq 0 \text{ or } x > 2\} $$

d. $A \cup C$

$$ A \cup C = \{x \in \mathbb{R} | 0 < x \leq 2 \text{ or } 3 \leq x < 9 \} $$

e. $A \cap C$

$$ A \cap C = \emptyset $$

f. $B^c$

$$ B^c = \{x \in \mathbb{R} | x < 1 \text{ or } x \geq 4\} $$

g. $A^c \cap B^c$

$$ A^c = \{x \in \mathbb{R} | x \leq 0 \text{ or } x > 2\} $$

$$ B^c = \{x \in \mathbb{R} | x < 1 \text{ or } x \geq 4\} $$

$$ A^c \cap B^c = \{x \in \mathbb{R} | x \leq 0 \text{ or } x \geq 4\}  $$

h. $A^c \cup B^c$

$$ A^c = \{x \in \mathbb{R} | x \leq 0 \text{ or } x > 2\} $$

$$ B^c = \{x \in \mathbb{R} | x < 1 \text{ or } x \geq 4\} $$

$$ A^c \cup B^c = \{x \in \mathbb{R} | x < 1 \text{ or } x > 2\} $$

i. $(A \cap B)^c$

$$ A \cap B = \{x \in \mathbb{R} | 1 \leq x \leq 2\} $$

$$ (A \cap B)^c = \{x \in \mathbb{R} | x < 1 \text{ or } x > 2 \} $$

j. $(A \cup B)^c$

$$ A \cup B = \{x \in \mathbb{R} | 0 < x < 4\} $$

$$ (A \cup B)^c = \{x \in \mathbb{R} | x \leq 0 \text{ or } x \geq 4\} $$

12. Let the universal set be $\mathbb{R}$, the set of all real numbers, and let
    $A = \{x \in \mathbb{R} | -3 \leq x \leq 0\}$,
    $B = \{x \in \mathbb{R} | -1 < x < 2\}$, and
    $C = \{x \in \mathbb{R} | 6 < x \leq 8\}$. Find each of the following:

a. $A \cup B$

$$ A \cup B = \{x \in \mathbb{R} | -3 \leq x < 2\} $$

b. $A \cap B$

$$ A \cap B = \{x \in \mathbb{R} | -1 < x \leq 0\} $$

c. $A^c$

$$ A^c = \{x \in \mathbb{R} | x < -3 \text{ or } x > 0 \} $$

d. $A \cup C$

$$ A \cup C = \{x \in \mathbb{R} | -3 \leq x \leq 0 \text{ or } 6 < x \leq 8\} $$

e. $A \cap C$

$$ A \cap C = \emptyset $$

f. $B^c$

$$ B^c = \{x \in \mathbb{R} | x \leq -1 \text{ or } x \geq 2 \} $$

g. $A^c \cap B^c$

$$ A^c = \{x \in \mathbb{R} | x < -3 \text{ or } x > 0 \} $$

$$ B^c = \{x \in \mathbb{R} | x \leq -1 \text{ or } x \geq 2 \} $$

$$ A^c \cap B^c = \{x \in \mathbb{R} | x < -3 \text{ or } x \geq 2 \} $$

h. $A^c \cup B^c$

$$ A^c = \{x \in \mathbb{R} | x < -3 \text{ or } x > 0 \} $$

$$ B^c = \{x \in \mathbb{R} | x \leq -1 \text{ or } x \geq 2 \} $$

$$ A^c \cup B^c = \{x \in \mathbb{R} | x \leq -1 \text{ or } x > 0 \} $$

i. $(A \cap B)^c$

$$ A \cap B = \{x \in \mathbb{R} | -1 < x \leq 0\} $$

$$ (A \cap B)^c = \{x \in \mathbb{R} | x \leq -1 \text{ or } x > 0\} $$

j. $(A \cup B)^c$

$$ A \cup B = \{x \in \mathbb{R} | -3 \leq x < 2\} $$

$$ (A \cup B)^c = \{x \in \mathbb{R} | x < -3 \text{ or } x \geq 2 \}$$

13. Let $S$ be the set of all strings of $0$'s and $1$'s of length $4$, and let
    $A$ and $B$ be the following subsets of $S$:
    $A = \{1110, 1111, 1000, 1001\}$ and $B = \{1100, 0100, 1111, 0111\}$. Find
    each of the following:

a. $A \cap B$

$$ A \cap B = \{1111\} $$

b. $A \cup B$

$$ A \cup B = \{1100, 0100, 1110, 1111, 0111, 1000, 1001\} $$

c. $A - B$

$$ A - B = \{1110, 1000, 1001\} $$

d. $B - A$

$$ B - A = \{1100, 0100, 0111\} $$

14. In each of the following, draw a Venn diagram for sets $A$, $B$, and $C$
    that satisfy the given conditions.

a. $A \subseteq B$, $C \subseteq B$, $A \cap C = \emptyset$

Done physically.

b. $C \subseteq A$, $B \cap C = \emptyset$

Done physically.

15. In each of the following, draw a Venn diagram for sets $A$, $B$, and $C$
    that satisfy the given conditions.

a. $A \cap B = \emptyset$, $A \subseteq C$, $C \cap B \neq \emptyset$

Done physically.

b. $A \subseteq B$, $C \subseteq B$, $A \cap C \neq \emptyset$

Done physically.

c. $A \cap B \neq \emptyset$, $B \cap C \neq \emptyset$, $A \cap C = \emptyset$,
$A \nsubseteq B$, $C \nsubseteq B$

Done physically.

16. Let $A = \{a, b, c\}$, $B = \{b, c, d\}$, and $C = \{b, c, e\}$.

a. Find $A \cup (B \cap C)$, $(A \cup B) \cap C$, and
$(A \cup B) \cap (A \cup C)$. Which of these sets are equal?

$$ B \cap C = \{b, c\} $$

$$ A \cup (B \cap C) = \{a, b, c\} $$

$$ A \cup B = \{a, b, c, d\} $$

$$ (A \cup B) \cap C = \{b, c\} $$

$$ A \cup C = \{a, b, c, e\} $$

$$ (A \cup B) \cap (A \cup C) = \{a, b, c\} $$

$$ A \cup (B \cap C) = (A \cup B) \cap (A \cup C) $$

b. Find $A \cap (B \cup C)$, $(A \cap B) \cup C$, and
$(A \cap B) \cup (A \cap C)$. Which of these sets are equal?

$$ B \cup C = \{b, c, d, e\} $$

$$ A \cap (B \cup C) = \{b, c\} $$

$$ A \cap B = \{b, c\} $$

$$ (A \cap B) \cup C = \{b, c, e\} $$

$$ A \cap C = \{b, c\} $$

$$ (A \cap B) \cup (A \cap C) = \{b, c\} $$

$$ A \cap (B \cup C) = A \cap C = (A \cap B) \cup (A \cap C) $$

c. Find $(A - B) - C$ and $A - (B - C)$. Are these sets equal?

$$ A - B = \{a\} $$

$$ (A - B) - C = \{a\} $$

$$ B - C = \{d\} $$

$$ A - (B - C) = \{a, b, c\} $$

$$ (A - B) - C \neq A - (B - C) $$

17. Consider the following Venn diagram. For each of (a)-(f), copy the diagram
    and shade the region corresponding to the indicated set.

a. $A \cap B$

Omitted.

b. $B \cup C$

Omitted.

c. $A^c$

Omitted.

d. $A - (B \cup C)$

Omitted.

e. $(A \cup B)^c$

Omitted.

f. $A^c \cap B^c$

Omitted.

(See page 412 for image)

18.

a. Is the number $0$ in $\emptyset$? Why?

No, by the definition of $\emptyset$, there are no elements in $\emptyset$. In
other words $\emptyset \neq \{0\}$.

b. Is $\emptyset = \{\emptyset\}$? Why?

No, by the definition of $\emptyset$, there are no elements in $\emptyset$. In
other words $\emptyset \neq \{\emptyset\}$.

c. Is $\emptyset \in \{\emptyset\}$ Why?

Yes, because $\emptyset$ itself can be an element in a set, it is true that
$\emptyset \in \{\emptyset\}$.

d. Is $\emptyset \in \emptyset$? Why?

No, by the definition of $\emptyset$, it is empty, it has no elements, therefore
$\emptyset$ cannot contain itself. $\emptyset \notin \emptyset$.

19. Let $A_i = \{i, i^2\}$ for each integer $i = 1, 2, 3, 4$.

a. $A_1 \cup A_2 \cup A_3 \cup A_4 = \text{ ?}$

$$
A_1 = \{1, 1^2\} = \{1, 1\} = \{1\} \\
A_2 = \{2, 2^2\} = \{2, 4\} \\
A_3 = \{3, 3^2\} = \{3, 9\} \\
A_4 = \{4, 4^2\} = \{4, 16\} \\
$$

$$ A_1 \cup A_2 \cup A_3 \cup A_4 = \{1, 2, 3, 4, 9, 16\} $$

b. $A_1 \cap A_2 \cap A_3 \cap A_4 = \text{ ?}$

$$ A_1 \cap A_2 \cap A_3 \cap A_4 = \emptyset $$

c. Are $A_1, A_2, A_3$, and $A_4$ mutually disjoint? Explain.

No, since $A_2$ and $A_4$ both contain the element $4$, they are not mutually
disjoint.

20. Let $B_i = \{x \in \mathbb{R} | 0 \leq x\leq i\}$ for each integer
    $i = 1, 2, 3, 4$.

a. $B_1 \cup B_2 \cup B_3 \cup B_4 = \text{ ?}$

$$ B_1 \cup B_2 \cup B_3 \cup B_4 = \{x \in \mathbb{R} | 0 \leq x \leq 4\} $$

b. $B_1 \cap B_2 \cap B_3 \cap B_4 = \text{ ?}$

$$ B_1 \cap B_2 \cap B_3 \cap B_4 = \{x \in \mathbb{R} | 0 \leq x \leq 1\} $$

c. Are $B_1, B_2, B_3$, and $B_4$ mutually disjoint? Explain.

No, since all sets include all real numbers within the range $0 \leq x \leq 1$,
they are not mutually disjoint.

21. Let $C_i = \{i, -i\}$ for each nonnegative integer $i$.

$$
C_0 = \{0, -0\} = \{0\} \\
C_1 = \{1, -1\} \\
C_2 = \{2, -2\} \\
C_3 = \{3, -3\} \\
C_4 = \{4, -4\} \\
$$

a. $\bigcup_{i = 0}^{4}C_i = \text{ ?}$

$$ \bigcup_{i = 0}^{4}C_i = C_0 \cup C_1 \cup C_2 \cup C_3 \cup C_4 $$

$$ \bigcup_{i = 0}^{4}C_i = \{-4, -3, -2, -1, 0, 1, 2, 3, 4\} $$

b. $\bigcap_{i = 0}^{4}C_i = \text{ ?}$

$$ \bigcap_{i = 0}^{4}C_i = \emptyset $$

c. Are $C_0, C_1, C_2, \dots$ mutually disjoint? Explain.

Yes, since none of the sets have any elements in common, they are mutually
disjoint.

d. $\bigcup_{i = 0}^{n}C_i = \text{ ?}$

$$ \bigcup_{i = 0}^{n}C_i = \{-n, -(n - 1), \dots -2, -1, 0, 1, 2, \dots (n - 1), n\} $$

e. $\bigcap_{i = 0}^{n}C_i = \text{ ?}$

$$ \bigcap_{i = 0}^{n}C_i = \emptyset $$

f. $\bigcup_{i = 0}^{\infty}C_i = \text{ ?}$

$$ \bigcup_{i = 0}^{\infty}C_i = \{-\infty, \dots, -2, -1, 0, 1, 2, \dots, \infty\} = \mathbb{Z} $$

g. $\bigcap_{i = 0}^{\infty}C_i = \text{ ?}$

$$ \bigcap_{i = 0}^{\infty}C_i = \emptyset $$

22. Let $D_i = \{x \in \mathbb{R} | -i \leq x \leq i\} = [-i, i]$ for each
    nonnegative integer $i$.

$$
D_0 = [-0, 0] = \{0\} \\
D_1 = [-1, 1] \\
D_2 = [-2, 2] \\
D_3 = [-3, 3] \\
D_4 = [-4, 4] \\
$$

a. $\bigcup_{i = 0}^{4}D_i = \text{ ?}$

$$ \bigcup_{i = 0}^{4}D_i = \{x \in \mathbb{R} | -4 \leq x \leq 4\} = [-4, 4] $$

b. $\bigcap_{i = 0}^{4}D_i = \text{ ?}$

$$ \bigcap_{i = 0}^{4}D_i = \{0\} $$

c. Are $D_0, D_1, D_2, \dots$ mutually disjoint? Explain.

No, in fact all sets have at least $\{0}$ in common , as $i$ increases, so does
the amount of elements all sets have in common, or $D_k \subseteq D_{k + 1}$.

d. $\bigcup_{i = 0}^{n}D_i = \text{ ?}$

$$ \bigcup_{i = 0}^{n}D_i = \{x \in \mathbb{R} | -n \leq x \leq n\} = [-n, n] $$

e. $\bigcap_{i = 0}^{n}D_i = \text{ ?}$

$$ \bigcap_{i = 0}^{n}D_i = \{0\} $$

f. $\bigcup_{i = 0}^{\infty}D_i = \text{ ?}$

$$ \bigcup_{i = 0}^{\infty}D_i = (-\infty, \infty) = \mathbb{R} $$

g. $\bigcap_{i = 0}^{\infty}D_i = \text{ ?}$

$$ \bigcap_{i = 0}^{\infty}D_i = \{0\} $$

23. Let
    $V_i = \{x \in \mathbb{R} | -\dfrac{1}{i} \leq x \leq \dfrac{1}{i}\} = \left[-\dfrac{1}{i}, \dfrac{1}{i}\right]$
    for each positive integer $i$.

$$
V_1 = \left[-\frac{1}{1}, \frac{1}{1}\right] = [-1, 1] \\
V_2 = \left[-\frac{1}{2}, \frac{1}{2}\right] \\
V_3 = \left[-\frac{1}{3}, \frac{1}{3}\right] \\
V_4 = \left[-\frac{1}{4}, \frac{1}{4}\right] \\
$$

a. $\bigcup_{i = 1}^{4}V_i = \text{ ?}$

$$ \bigcup_{i = 1}^{4}V_i = [-1, 1] $$

b. $\bigcap_{i = 1}^{4}V_i = \text{ ?}$

$$ \bigcap_{i = 1}^{4}V_i = \left[-\frac{1}{4}, \frac{1}{4}\right] $$

c. Are $V_1, V_2, V_3, \dots$ mutually disjoint? Explain.

No, every set includes $0$.

d. $\bigcup_{i = 1}^{n}V_i = \text{ ?}$

$$ \bigcup_{i = 1}^{n}V_i = [-1, 1] $$

e. $\bigcap_{i = 1}^{n}V_i = \text{ ?}$

$$ \bigcap_{i = 1}^{n}V_i = \left[-\frac{1}{n}, \frac{1}{n}\right] $$

f. $\bigcup_{i = 1}^{\infty} = \text{ ?}$

$$ \bigcup_{i = 1}^{\infty} = [-1, 1] $$

g. $\bigcap_{i = 1}^{\infty} = \text{ ?}$

$$ \bigcap_{i = 1}^{\infty} = \{0\} \text{ because as } i \to \infty \text{ then } \frac{1}{i} \to 0 $$

24. Let $W_i = \{x \in \mathbb{R} | x > i\} = (i, \infty)$ for each nonnegative
    integer $i$.

$$
W_0 = (0, \infty) \\
W_1 = (1, \infty) \\
W_2 = (2, \infty) \\
W_3 = (3, \infty) \\
W_4 = (4, \infty) \\
$$

a. $\bigcup_{i = 0}^{4}W_i = \text{ ?}$

$$ \bigcup_{i = 0}^{4}W_i = (0, \infty) $$

b. $\bigcap_{i = 0}^{4}W_i = \text{ ?}$

$$ \bigcap_{i = 0}^{4}W_i = (4, \infty) $$

c. Are $W_0, W_1, W_2, \dots$ mutually disjoint? Explain.

No, because they all have $(i, \infty)$ in common, or $W_{i + 1} \subseteq W_i$.

d. $\bigcup_{i = 0}^{n}W_i = \text{ ?}$

$$ \bigcup_{i = 0}^{n}W_i = (0, \infty) $$

e. $\bigcap_{i = 0}^{n}W_i = \text{ ?}$

$$ \bigcap_{i = 0}^{n}W_i = (n, \infty) $$

f. $\bigcup_{i = 0}^{\infty}W_i = \text{ ?}$

$$ \bigcup_{i = 0}^{\infty}W_i = (0, \infty) $$

g. $\bigcap_{i = 0}^{\infty}W_i = \text{ ?}$

$$ \bigcap_{i = 0}^{\infty}W_i = \emptyset $$

There is no real number greater than every positive integer, so no element
belongs to all $W_i$.

25. Let
    $R_i = \{x \in \mathbb{R} | 1 \leq x \leq 1 + \dfrac{1}{i}\} = \left[1, 1 + \dfrac{1}{i}\right]$
    for each positive integer $i$.

$$
R_1 = \left[1, 1 + \frac{1}{1}\right] = [1, 2] \\
R_2 = \left[1, 1 + \frac{1}{2}\right] = \left[1, \frac{3}{2}\right] \\
R_3 = \left[1, 1 + \frac{1}{3}\right] = \left[1, \frac{4}{3}\right] \\
R_4 = \left[1, 1 + \frac{1}{4}\right] = \left[1, \frac{5}{4}\right] \\
$$

a. $\bigcup_{i = 1}^{4}R_i = \text{ ?}$

$$ \bigcup_{i = 1}^{4}R_i = [1, 2] $$

b. $\bigcap_{i = 1}^{4}R_i = \text{ ?}$

$$ \bigcap_{i = 1}^{4}R_i = \left[1, \frac{5}{4}\right] $$

c. Are $R_1, R_2, R_3, \dots$ mutually disjoint? Explain.

No, they all include the element $1$.

d. $\bigcup_{i = 1}^{n}R_i = \text{ ?}$

$$ \bigcup_{i = 1}^{n}R_i = [1, 2] $$

e. $\bigcap_{i = 1}^{n}R_i = \text{ ?}$

$$ \bigcap_{i = 1}^{n}R_i = \left[1, 1 + \frac{1}{n}\right]$$

f. $\bigcup_{i = 1}^{\infty}R_i = \text{ ?}$

$$ \bigcup_{i = 1}^{\infty}R_i = [1, 2] $$

g. $\bigcap_{i = 1}^{\infty}R_i = \text{ ?}$

$$ \bigcap_{i = 1}^{\infty}R_i = \{1\} $$

Because $\dfrac{1}{\infty} \to 0$ and
$\left(1 + \dfrac{1}{\infty}\right) \to 1$.

26. Let
    $S_i = \{x \in \mathbb{R} | 1 < x < 1 + \dfrac{1}{i}\} = \left(1, 1 + \dfrac{1}{i}\right)$
    for each positive integer $i$.

$$
S_1 = \left(1, 1 + \frac{1}{1}\right) = (1, 2) \\
S_2 = \left(1, 1 + \frac{1}{2}\right) = \left(1, \frac{3}{2}\right) \\
S_3 = \left(1, 1 + \frac{1}{3}\right) = \left(1, \frac{4}{3}\right) \\
S_4 = \left(1, 1 + \frac{1}{4}\right) = \left(1, \frac{5}{4}\right) \\
$$

a. $\bigcup_{i = 1}^{4}S_i = \text{ ?}$

$$ \bigcup_{i = 1}^{4}S_i = (1, 2) $$

b. $\bigcap_{i = 1}^{4}S_i = \text{ ?}$

$$ \bigcap_{i = 1}^{4}S_i = \left(1, \frac{5}{4}\right) $$

c. Are $S_1, S_2, S_3, \dots$ mutually disjoint? Explain.

No, any element sufficiently close to $1$ are in all the sets.

d. $\bigcup_{i = 1}^{n}S_i = \text{ ?}$

$$ \bigcup_{i = 1}^{n}S_i = (1, 2) $$

e. $\bigcap_{i = 1}^{n}S_i = \text{ ?}$

$$ \bigcap_{i = 1}^{n}S_i = \left(1, 1 + \frac{1}{n}\right) $$

f. $\bigcup_{i = 1}^{\infty}S_i = \text{ ?}$

$$ \bigcup_{i = 1}^{\infty}S_i = (1, 2) $$

g. $\bigcap_{i = 1}^{\infty}S_i = \text{ ?}$

$$ \bigcap_{i = 1}^{\infty}S_i = \emptyset $$

Because the range converges on $1$, but cannot include $1$, the set is empty.

27.

a. Is $\{\{a, d, e\}, \{b, c\}, \{d, f\}\}$ a partition of
$\{a, b, c, d, e, f\}$?

No, since $d$ is an element in two sets, the sets are not mutually disjoint, and
so therefore is not a partition.

b. Is $\{\{w, x, v\}, \{u, y, q\}, \{p, z\}\}$ a partition of
$\{p, q, u, v, w, x, y, z\}$?

$$ \{w, x, v\} \cup \{u, y, q\} \cup \{p, z\} = \{p, q, u, v, w, x, y, z\} $$

and:

$$ \{w, x, v\} \cap \{u, y, q\} \cap \{p, z\} = \emptyset $$

So yes, the given sets are a partition of the overall set.

c. Is $\{\{5, 4\}, \{7, 2\}, \{1, 3, 4\}, \{6, 8\}\}$ a partition of
$\{1, 2, 3, 4, 5, 6, 7, 8\}$?

No, as $4$ is an element in two of the given sets, and so the given sets are not
a partition of the overall set.

d. Is $\{\{3, 7, 8\}, \{2, 9\}, \{1, 4, 5\}\}$ a partition of
$\{1, 2, 3, 4, 5, 6, 7, 8, 9\}$?

No, since none of the sets contain $6$.

e. Is $\{\{1, 5\}, \{4, 7\}, \{2, 8, 6, 3\}\}$ a partition of
$\{1, 2, 3, 4, 5, 6, 7, 8\}$?

Yes, since none of the elements in each of the given sets are in any other of
the given sets and all of the elements make up the overall set.

28. Let $E$ be the set of all even integers and $O$ the set of all odd integers.
    Is $\{E, O\}$ a partition of $\mathbb{Z}$, the set of all integers? Explain
    your answer.

Yes, since no integer is both even and odd, and all integers are either even or
odd, $\{E, O\}$ is a partition of $\mathbb{Z}$.

29. Let $\mathbb{R}$ be the set of all real numbers. Is
    $\{\mathbb{R}^+, \mathbb{R}^-, \{0\}\}$ a partition of $\mathbb{R}$? Explain
    your answer.

Yes, since all real numbers are either positive, negative, or $0$, and
$\mathbb{R}^+$, $\mathbb{R}^-$ and $\{0\}$ do not have any elements in common,
these subsets all form a partition of $\mathbb{R}$.

30. Let $\mathbb{Z}$ be the set of all integers and let

$$ A_0 = \{n \in \mathbb{Z} | n = 4k, \text{ for some integer } k\} $$

$$ A_1 = \{n \in \mathbb{Z} | n = 4k + 1, \text{ for some integer } k\} $$

$$ A_2 = \{n \in \mathbb{Z} | n = 4k + 2, \text{ for some integer } k\} $$

and

$$ A_3 = \{n \in \mathbb{Z} | n = 4k + 3, \text{ for some integer } k\} $$

Is $\{A_0, A_1, A_2, A_3\}$ a partition of $\mathbb{Z}$? Explain your answer.

Yes. These sets are mutually disjoint, and by the quotient-remainder theorem,
every integer has exactly one of the forms $n = 4k$, $n = 4k + 1$, $n = 4k + 2$,
$n = 4k + 3$.

31. Suppose $A = \{1, 2\}$ and $B = \{2, 3\}$. Find each of the following:

a. $\mathscr{P}(A \cap B)$

$$ A \cap B = \{2\} $$

$$ \mathscr{P}(A \cap B) = \{\emptyset, \{2\}\} $$

b. $\mathscr{P}(A)$

$$ \mathscr{P}(A) = \{\emptyset, \{1\}, \{2\}, \{1, 2\}} $$

c. $\mathscr{P}(A \cup B)$

$$ A \cup B = \{1, 2, 3\} $$

$$ \mathscr{P}(A \cup B) = \{\emptyset, \{1\}, \{2\}, \{3\}, \{1, 2\}, \{1, 3\}, \{2, 3\}, \{1, 2, 3\}\} $$

d. $\mathscr{P}(A \times B)$

$$ A \times B = \{(1, 2), (1, 3), (2, 2), (2, 3)\} $$

$$ \mathscr{P}(A \times B) = \{\emptyset, \{(1, 2)\}, \{(1, 3)\}, \{(2, 2)\}, \{(2, 3)\}, \{(1, 2), (1, 3)\}, \{(1, 2), (2, 2)\}, \{(1, 2,), (2, 3)\}, \{(1, 3), (2, 2)\}, \{(1, 3), (2, 3)\}, \{(2, 2), (2, 3)\}, \{(1, 2), (1, 3), (2, 2)\}, \{(1, 2), (1, 3), (2, 3)\}, \{(1, 2), (2, 2), (2, 3)\}, \{(1, 3), (2, 2), (2, 3)\}, \{(1, 2), (1, 3), (2, 2), (2, 3)\}\} $$

32.

a. Suppose $A = \{1\}$ and $B = \{u, v\}$. Find $\mathscr{P}(A \times B)$.

$$ A \times B = \{(1, u), (1, v)\} $$

$$ \mathscr{P}(A \times B) = \{\emptyset, \{(1, u)\}, \{(1, v)\}, \{(1, u), (1, v)\}\} $$

b. Suppose $X = \{a, b\}$ and $Y = \{x, y\}$. Find $\mathscr{P}(X \times Y)$.

$$ X \times Y = \{(a, x), (a, y), (b, x), (b, y)\} $$

$$ \mathscr{P}(X \times Y) = \{\emptyset, \{(a, x)\}, \{(a, y)\}, \{(b, x)\}, \{(b, y)\}, \{(a, x), (a, y)\}, \{(a, x), (b, x)\}, \{(a, x), (b, y)\}, \{(a, y), (b, x)\}, \{(a, y), (b, y)\}, \{(b, x), (b, y)\}, \{(a, x), (a, y), (b, x)\}, \{(a, x), (a, y), (b, y)\}, \{(a, x), (b, x), (b, y)\}, \{(a, y), (b, x), (b, y)\} \{(a, x), (a, y), (b, x), (b, y)\}\} $$

33.

a. Find $\mathscr{P}(\emptyset)$.

$$ \mathscr{P}(\emptyset) = \{\emptyset\} $$

b. Find $\mathscr{P}(\mathscr{P}(\emptyset))$.

$$ \mathscr{P}(\mathscr{P}(\emptyset)) = \{\emptyset, \{\emptyset\}\} $$

b. Find $\mathscr{P}(\mathscr{P}(\mathscr{P}(\emptyset)))$.

$$ \mathscr{P}(\mathscr{P}(\mathscr{P}(\emptyset))) = \{\emptyset, \{\emptyset\}, \{\emptyset, \{\emptyset\}\}, \{\{\emptyset\}\}\} $$

34. let $A_1 = \{1\}$, $A_2 = \{u, v\}$, and $A_3 = \{m, n\}$. Find each of the
    following sets:

a. $A_1 \cup (A_2 \times A_3)$

$$ A_2 \times A_3 = \{(u, m), (u, n), (v, m), (v, n)\} $$

$$ A_1 \cup (A_2 \times A_3) = \{1, (u, m), (u, n), (v, m), (v, n)\} $$

b. $(A_1 \cup A_2) \times A_3$

$$ A_1 \cup A_2 = \{1, u, v\} $$

$$ (A_1 \cup A_2) \times A_3 = \{(1, m), (1, n), (u, m), (u, n), (v, m), (v, n)\} $$

35. let $A = \{a, b\}$, $B = \{1, 2\}$, and $C = \{2, 3\}$. Find each of the
    following sets:

a. $A \times (B \cup C)$

$$ B \cup C = \{1, 2, 3\} $$

$$ A \times (B \cup C) = \{(a, 1), (a, 2), (a, 3), (b, 1), (b, 2), (b, 3)\} $$

b. $(A \times B) \cup (A \times C)$

$$ A \times B = \{(a, 1), (a, 2), (b, 1), (b, 2)\} $$

$$ A \times C = \{(a, 2), (a, 3), (b, 2), (b, 3)\} $$

$$ (A \times B) \cup (A \times C) = \{(a, 1), (a, 2), (a, 3), (b, 1), (b, 2), (b, 3)\} $$

c. $A \times (B \cap C)$

$$ B \cap C = \{2\} $$

$$ A \times (B \cap C) = \{(a, 2), (b, 2)\} $$

d. $(A \times B) \cap (A \times C)$

$$ A \times B = \{(a, 1), (a, 2), (b, 1), (b, 2)\} $$

$$ A \times C = \{(a, 2), (a, 3), (b, 2), (b, 3)\} $$

$$ (A \times B) \cap (A \times C) = \{(a, 2), (b, 2)\} $$

36. Trace the action of Algorithm 6.1.1 on the variables $i$, $j$,
    $\text{found}$, and $\text{answer}$ for $m = 3$, $n = 3$, and sets $A$ and
    $B$ represented as the arrays
    $a[1] = u, a[2] = v, a[3] = w, b[1] = w, b[2] = u,$ and $b[3] = v$.

Omitted.

37. Trace the action of Algorithm 6.1.1 on the variables $i$, $j$,
    $\text{found}$, and $\text{answer}$ for $m = 4$, $n = 4$ and sets $A$ and
    $B$ represented as the arrays
    $a[1] = u, a[2] = v, a[3] = w, a[4] = x, b[1] = r, b[2] = u, b[3] = y, b[4] = z$.

Omitted.

38. Write an algorithm to determine whether a given element $x$ belongs to a
    given set that is represented as the array $a[1], a[2], \dots, a[n]$.

Omitted.

---

Page 427

**Exercise Set 6.2**

1.

a. To say that an element is in $A \cap (B \cup C)$ means that it is in __ (1)
__ and in __ (2) __.

(1) $A$

(2) $B \cup C$

b. To say that an element is in $(A \cap B) \cup C$ means that it is in __ (1)
__ or in __ (2) __.

(1) $A \cap B$

(2) $C$

c. To say that an element is in $A - (B \cap C)$ means that it is in __ (1) __
and not in __ (2)__.

(1) $A$

(2) $B \cap C$

d. To prove that $(A \cup B) \cap C \subseteq A \cup (B \cap C)$, we suppose
that $x$ is any element in __ (1) __. Then we must show that __ (2) __.

(1) $(A \cup B) \cap C$

(2) $x \in A \cup (B \cap C)$

e. If $A$, $B$, and $C$ are any sets such that $B \subseteq C$, to prove that
$A \cap B \subseteq A \cap C$, we suppose that $x$ is any element in __ (1) __.
Then we must show that __ (2) __.

(1) $A \cap B$

(2) $A \cap C$

2. The following are two proofs that for all sets $A$ and $B$,
   $A - B \subseteq A$. The first is less formal, and the second is more formal.
   Fill in the blanks.

a. **Proof:** Suppose $A$ and $B$ are any sets. To show that
$A - B \subseteq A$, we must show that every element in __ (1) __ is in __ (2)
__. But any element in $A - B$ is in __ (3) __ and not in __ (4) __ (by
definition of $A - B$). In particular, such an element is in $A$.

(1) $A - B$

(2) $A$

(3) $A$

(4) $B$

b. **Proof:** Suppose $A$ and $B$ are any sets and $x \in A - B$. _[We must show
that __ (1) __.]_ By definition of set difference, $x \in$ __ ( 2 ) __ and
$x \notin$ __ (3) __. In particular, $x \in$ __ (4) __ _[which is what was to be
shown]._

(1) $x \in A$

(2) $A$

(3) $B$

(4) $A$

In 3 and 4, supply explanations of the steps in the given proofs.

3. **Theorem:** For all sets $A$, $B$, and $C$, if $A \subseteq C$,
   $B \subseteq C$, then $A \subseteq C$.

**Proof:**

| Statement                                                                            | Explanation                           |
| ------------------------------------------------------------------------------------ | ------------------------------------- |
| Suppose $A$, $B$, and $C$ are any sets such that $A \subseteq B$ and $B \subseteq C$ | starting point                        |
| We must show that $A \subseteq C$.                                                   | conclusion to be shown                |
| Let $x$ be any element in $A$.                                                       | start of an element proof             |
| Then $x$ is in $B$.                                                                  | __ (a) __                             |
| It follows that $x$ is in $C$.                                                       | __ (b) __                             |
| Thus every element in $A$ is in $C$                                                  | since $x$ could be any element of $A$ |
| Therefore, $A \subseteq C$ _[as was to be shown]._                                   | __ \(c\) __                           |

a. by definition of a subset (because $A$ is a subset of $B$)

b. by definition of a subset (because $B$ is a subset of $C$)

c. by definition of a subset

4. **Theorem:** For all sets $A$ and $B$, if $A \subseteq B$, then
   $A \cup B \subseteq B$.

**Proof:**

| Statement                                                         | Explanation                                  |
| ----------------------------------------------------------------- | -------------------------------------------- |
| Suppose $A$, $B$, and $C$ are any sets such that $A \subseteq B$. | starting point                               |
| We must show that $A \cup B \subseteq B$                          | conclusion to be shown                       |
| Let $x$ be any element in $A \cup B$.                             | start of an element proof                    |
| Then $x$ is in $A$ or $x$ is in $B$.                              | __ (a) __                                    |
| In case $x$ is in $A$, then $x$ is in $B$                         | __ (b) __                                    |
| In case $x$ is in $B$, then $x$ is in $B$.                        | tautology ($p \to p$)                        |
| So in either case $x$ is in $B$.                                  | proof by division into cases                 |
| Thus every element in $A \cup B$ is in $B$                        | since $x$ could be any element of $A \cup B$ |
| Therefore, $A \cup B \subseteq B$ _[as was to be shown]._         | __ \(c\) __                                  |

a. by the definition of a union (because $A \cup B$)

b. by definition of a subset (because $A \subseteq B$)

c. by definition of a subset

5. Prove that for all sets $A$ and $B$, $(B - A) = B \cap A^c$.

**Proof:**

Let $A$ and $B$ be any sets.

To prove that $(B - A) = B \cap A^c$, we must first prove
$(B - A) \subseteq B \cap A^c$ and then prove $B \cap A^c \subseteq (B - A)$.

_Proof ($(B - A) \subseteq B \cap A^c$):_

Suppose $x$ is some element such that $x \in (B - A)$.

By the definition of the difference of sets, this means that $x \in B$ and
$x \notin A$. It then follows by the definition of the complement of sets that
$x \in B$ and $x \in A^c$.

By definition of an intersection, it then follows further that
$x \in B \cap A^c$.

Therefore every element that is in $(B - A)$ is also in $B \cap A^c$. This is
what was to be shown.

_Proof ($B \cap A^c \subseteq (B - A)$):_

Suppose $x$ is some element such that $x \in B \cap A^c$.

By definition of the intersection of sets, this means that $x \in B$ and
$x \in A^c$. By definition of the complement of sets, this means that $x \in B$
and $x \notin A$.

It follows that if $x \in B$ and $x \notin A$, then by the definition of the
difference of sets $x \in (B - A)$.

Therefore every element that is in $B \cap A^c$ is in $(B - A)$. This is what
was to be shown.

Since both relations have been proved, it is concluded that
$(B - A) = B \cap A^c$, by definition of set equality.

Q.E.D.

6. Let $\cap$ and $\cup$ stand for the words "intersection" and "union",
   respectively. Fill in the blanks in the following proof that for all sets
   $A$, $B$, and $C$, $A \cap (B \cup C) = (A \cap C) \cup (A \cap C)$.

**Proof:** Suppose $A$, $B$, and $C$ are any sets.

(1) Proof that $A \cap (B \cup C) \subseteq (A \cap B) \cup (A \cap C)$:

Let $x \in A \cap (B \cup C)$. _[We must show that $x \in$ __ (a) __ ]._

By definition of $\cap$, $x \in$ __ (b) __ and $x \in B \cup C$.

Thus $x \in A$ and, by definition of $\cup$, $x \in B$ or __ \(c\) __.

_Case 1 $(x \in A \text{ and } x \in B)$:_ In this case, $x \in A \cap B$ by
definition of $\cap$.

_Case 2 $(x \in A \text{ and } x \in C)$:_ IN this case, $x \in A \cap C$ by
definition of $\cap$.

By cases 1 and 2, $x \in A \cap B$ or $x \in A \cap C$, and so, by definition of
$\cup$, __ (d) __.

_[So $A \cap (B \cup C) \subseteq (A \cap B) \cup (A \cap C)$ by definition of
subset.]_

(2) Proof that $(A \cap B) \cup (A \cap C) \subseteq A \cap (B \cup C)$:

Let $x \in (A \cap B) \cup (A \cap C)$. _[We must show that
$x \in A \cap (B \cup C)$.]_

By definition of $\cup$, $x \in A \cap B$ __ (a) __ $x \in A \cap C$.

_Case 1 $(x \in A \cap B)$:_ In this case, by definition of $\cap$, $x \in A$
and $x \in B$$.

Since $x \in B$, then $x \in B \cup C$ by definition of $\cup$.

_Case 2 $(x \in A \cap C)$:_ In this case, by definition of $\cap$, $x \in A$ __
(b) __ $x \in C$.

Since $x \in C$, then $x \in B \cup C$ by definition of $\cup$.

In both cases $x \in A$ and $$ix \in B \cup C, and so, by definition of $\cap$,
__ \(c\) __.

_[So $(A \cap B) \cup (A \cap C) \subseteq A \cap (B \cup C)$ by definition of
__ (d) __ .]_

(3) Conclusion: _[Since both subset relations have been proved, it follows, by
definition of set equality, that __ (a) __.]_

Use an element argument to prove each statement in 7-22. Assume that all sets
are subsets of a universal set $U$.

(1a) $x \in (A \cap B) \cup (A \cap C)$

(1b) $A$

(1c) $x \in C$

(1d) $x \in (A \cap B) \cup (A \cap C)$

(2a) or

(2b) and

(2c) $x \in A \cap (B \cup C)$

(2d) subset

(3a) for all sets $A$, $B$, and $C$,
$A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$

7. For all sets $A$ and $B$, $(A \cap B)^c = A^c \cup B^c$.

**Proof:**

Let $A$ and $B$ be any sets.

To prove that $(A \cap B)^c = A^c \cup B^c$, we must show that
$(A \cap B)^c \subseteq A^c \cup B^c$ and also show that
$A^c \cup B^c \subseteq (A \cap B)^c$.

_Proof ($(A \cap B)^c \subseteq A^c \cup B^c$):_

Suppose $x$ is some element such that $x \in (A \cap B)^c$.

By the definition of complement, this means that $x \notin (A \cap B)$.

By the definition of intersection of sets (and by De Morgan's Laws of negation
of sets), this means that $x \notin A$ or $x \notin B$. It follows by the
definition of complement of sets that $x \in A^c$ or $x \in B^c$.

Thus, by definition of the union of sets, $x \in A^c \cup B^c$.

Therefore all elements in $(A \cap B)^c$ are in $A^c \cup B^c$. Specifically,
$(A \cap B)^c \subseteq A^c \cup B^c$.

This is what was to be shown.

_Proof ($A^c \cup B^c \subseteq (A \cap B)^c$):_

Suppose $x$ is some element such that $x \in A^c \cup B^c$. By the definition of
the union of sets, $x \in A^c$ or $x \in B^c$. By the definition of complement
of sets, this means that $x \notin A$ or $x \notin B$.

By definition of the union of sets, it follows that $x \in A^c \cup B^c$. Then
by De Morgan's Laws of Sets, $x \in (A \cap B)^c$.

Therefore all elements in $A^c \cup B^c$ are in $(A \cap B)^c$. Specifically,
$A^c \cup B^c \subseteq (A \cap B)^c$.

This is what was to be shown.

_Conclusion:_

Since both sets have been shown to be subsets of the other, it is concluded that
$A^c \cup B^c = (A \cap B)^c$, by definition of set equality.

Q.E.D.

8. For all sets $A$ and $B$, $(A \cap B) \cup (A \cap B^c) = A$.

(This property is used in Section 9.9.)

**Proof:**

Let $A$ and $B$ be any sets.

To prove that $(A \cap B) \cup (A \cap B^c) = A$, it must be shown that
$(A \cap B) \cup (A \cap B^c) \subseteq A$ and also that
$A \subseteq (A \cap B) \cup (A \cap B^c)$.

_Proof ($(A \cap B) \cup (A \cap B^c) \subseteq A$):_

Suppose $x$ is any element such that $x \in (A \cap B) \cup (A \cap B^c)$.

By definition of $\cup$, this means that $x \in A \cap B$ or $x \in A \cap B^c$

_Case $x \in A \cap B$:_

By definition of $\cap$, this means that $x \in A$ and $x \in B$. By definition
of $\subseteq$, if $x \in A$ and $x \in B$, then $A \cap B \subseteq A$.

_Case $x \in A \cap B^c$:_

By definition of $\cap$, this means that $x \in A$ and $x \in B^c$. By
definition of complement, this means that $x \in A$ and $x \notin B$. By
tautology and by definition of $\subseteq$, if $x \in A$ and $x \notin B$, then
$x \in A \cap B^c \subseteq A$.

Thus in both cases, it has been shown that any element in $A \cap B$ or
$A \cap B^c$ is in $A$. Specifically $(A \cap B) \cup (A \cap B^c) \subseteq A$.

This is what was to be shown.

_Proof ($A \subseteq (A \cap B) \cup (A \cap B^c)$):_

Suppose $x$ is any element such that $x \in A$.

To prove $x \in A \subseteq (A \cap B) \cup (A \cap B^c)$, we must prove that
either $x \in B$ or $x \in B^c$ (by definition of $\cup$ and the complement of
sets.)

_Case $x \in B$:_

By the supposition, it is known that $x \in A$ and $x \in B$. By the definition
of $\cap$, this means that $x \in A \cap B$.

_Case $x \notin B$:_

By the supposition, it is known that $x \in A$ and $x \notin B$. By the
definition of $\cap$ and the complement of sets, this means that
$x \in A \cap B^c$.

In the case that $x \in B$, it has been shown that then $x \in A \cap B$. In the
case that $x \notin B$, it has been shown that $x \in A \cap B^c$. Thus it can
be stated that $x \in A \cap B$ or $x \in A \cap B^c$. By the definition of
$\cup$, it follows that $x \in (A \cap B) \cup (A \cap B^c)$.

Therefore it can be said that every element in $A$ is in
$(A \cap B) \cup (A \cap B^c)$. Specifically,
$A \subseteq (A \cap B) \cup (A \cap B^c)$.

This is what was to be shown.

_Conclusion:_

It has been shown that $(A \cap B) \cup (A \cap B^c) \subseteq A$ and
$A \subseteq (A \cap B) \cup (A \cap B^c)$. By the definition of the equality of
sets, this means that $(A \cap B) \cup (A \cap B^c) = A$.

Q.E.D.

9. For all sets $A$, $B$, and $C$,

$$ (A - B) \cup (C - B) = (A \cup C) - B $$

**Proof:**

Let $A$, $B$, and $C$ be any sets.

To prove $(A - B) \cup (C - B) = (A \cup C) - B$, it must be shown that
$(A - B) \cup (C - B) \subseteq (A \cup C) - B$ and that
$(A \cup C) - B \subseteq (A - B) \cup (C - B)$.

_Proof ($(A - B) \cup (C - B) \subseteq (A \cup C) - B$):_

Suppose $x$ is some element such that $x \in (A - B) \cup (C - B)$.

By the definition of $\cup$, this means that $x \in (A - B)$ or $x \in (C - B)$.

In the case that $x \in (A - B)$, $x \in A$ and $x \notin B$. In the case that
$x \in (C - B)$, $x \in C$ and $x \notin B$. In both cases $x \notin B$.

It follows that $x \in A$ or $x \in C$. Specifically $x \in (A \cup C)$. In
either case, $x \notin B$. Hence, by the definition of difference of sets,
$x \in (A \cup C) - B$.

Therefore every element in $(A - B) \cup (C - B)$ is in $(A \cup C) - B$.
Specifically, $(A - B) \cup (C - B) \subseteq (A \cup C) - B$.

This is what was to be shown.

_Proof ($(A \cup C) - B \subseteq (A - B) \cup (C - B)$):_

Suppose $x$ is some element such that $x \in (A \cup C) - B$.

By the definition of difference of sets, this means that $x \in (A \cup C)$ and
$x \notin B$. By the definition of $\cup$, this means that $x \in A$ or
$x \in C$.

In the case that $x \in A$, then $x \in A$ and $x \notin B$. By the definition
of complements, this means that $x \in A \cap B^c$. It follows by the set
difference law, that $x \in A - B$.

In the case that $x \in C$, then $x \in A$ and $x \notin B$. By the definition
of complements, this means that $x \in C \cap B^c$. It follows by the set
difference law, that $x \in C - B$.

Thus it can be said that $x \in A - B$ or $x \in C - B$. By the definition of
$\cup$, it follows that $x \in (A - B) \cup (C - B)$.

Therefore every element in $(A \cup C) - B$ is in $(A - B) \cup (C - B)$.
Specifically, $A \cup C - B \subseteq (A - B) \cup (C - B)$.

This is what was to be shown.

_Conclusion:_

Since both subset relations have been proved, it is concluded that
$(A - B) \cup (C - B) = (A \cup C) - B$ by definition of set equality.

Q.E.D.

10. For all sets $A$, $B$, and $C$,

$$ (A \cup B) \cap C \subseteq A \cup (B \cap C) $$

**Proof:**

Let $A$, $B$, and $C$ be any sets.

Suppose $x$ is some element such that $x \in (A \cup B) \cap C$.

By the definition of $\cap$, this means that $x \in (A \cup B)$ and $x \in C$.
By the definition of $\cup$, this means that $x \in A$ or $x \in B$.

_Case $x \in A$:_

Since $x \in A$ and $x \in C$, it follows that $x \in A \cup (B \cap C)$, since
$x \in A$.

_Case $x \in B$:_

Since $x \in A$ and $x \in C$, this means that $x \in B \cap C$. It follows that
$x \in A \cup (B \cap C)$, since $x \in B \cap C$.

Thus in both cases $x \in A \cup (B \cap C)$.

Therefore every element in $(A \cup B) \cap C$ is in $A \cup (B \cap C)$. By the
definition of a subset, this means that
$(A \cup B) \cap C \subseteq A \cup (B \cap C)$.

This is what was to be shown.

Q.E.D.

11. For all sets $A$, $B$, and $C$,

$$ A \cap (B - C) \subseteq (A \cap B) - (A \cap C) $$

**Proof:**

Let $A$, $B$, and $C$ be any sets.

Suppose $x$ is some element such that $x \in A \cap (B - C)$.

By definition of $\cap$, this means that $x \in A$ and $x \in (B - C)$. By the
definition of difference of sets, this means that $x \in A$ and $x \in B$ and
$x \notin C$.

Since $x \in A$ and $x \in B$, it follows that $x \in A \cap B$.

Since $x \in A$ and $x \notin C$, by the definition of complement, it can be
said that $x \in A \cap C^c$, or $x \notin A \cap C$.

Thus $x \in A \cap B$ and $x \notin A \cap C$. Hence, by the difference of sets,
$x \in (A \cap B) - (A \cap C)$.

Therefore it can be said that every element in $A \cap (B - C)$ is in
$(A \cap B) - (A \cap C)$. Specifically
$A \cap (B - C) \subseteq (A \cap B) - (A \cap C)$.

This is what was to be shown.

Q.E.D.

12. For all sets $A$, $B$, and $C$,

$$ (A \cup B) - C \subseteq (A - C) \cup (B - C) $$

**Proof:**

Let $A$, $B$, and $C$ be any sets.

Suppose $x$ is some element such that $x \in (A \cup B) - C$.

By the definition of difference, this means that $x \in A \cup B$ and
$x \notin C$.

By the definition of $\cup$, it follows that $x \in A$ or $x \in B$.

_Case $x \in A$:_

Since $x \in A$ and $x \notin C$, by the definition of difference, it can be
said that $x \in A - C$.

_Case $x \in B$:_

Since $x \in B$ and $x \notin C$, by the definition of difference, it can be
said that $x \in B - C$.

Hence it can be said that $x \in A - C$ or $x \in B - C$. By the definition of
$\cup$, it follows that $x \in (A - C) \cup (B - C)$.

Therefore it can said that any element in $(A \cup B) - C$ is also in
$(A - C) \cup (B - C)$. Specifically, by definition of a subset,
$(A \cup B) - C \subseteq (A - C) \cup (B - C)$.

This is what was to be shown.

Q.E.D.

13. For all sets $A$, $B$, and $C$,

$$ (A - B) \cap (C - B) = (A \cap C) - B $$

Let $A$, $B$, and $C$ be any sets.

To prove $(A - B) \cap (C - B) = (A \cap C) - B$, it must be shown that
$(A - B) \cap (C - B) \subseteq (A \cap C) - B$ and that
$(A \cap C) - B \subseteq (A - B) \cap (C - B)$.

_Proof ($(A - B) \cap (C - B) \subseteq (A \cap C) - B$):_

Suppose $x$ is some element such that $x \in (A - B) \cap (C - B)$.

By the definition of $\cap$, this means that $x \in A - B$ and $x \in C - B$.

By the definition of difference, this means that $x \in A$ and $x \notin B$ and
$x \in C$ and $x \notin B$.

Thus $x$ is in $A$ and $C$, or (by definition of $\cap$), $x \in A \cap C$.
Since $x \notin B$, it follows then that $x \in (A \cap C) \cap B^c$, by the
definition of complement.

By the set difference law, it follows that $x \in (A \cap C) - B$.

Thus every element in $(A - B) \cap (C - B)$ is in $(A \cap C) - B$. By the
definition of subset, it follows that
$(A - B) \cap (C - B) \subseteq (A \cap C) - B$.

This is what was to be shown.

_Proof ($(A \cap C) - B \subseteq (A - B) \cap (C - B)$):_

Suppose $x$ is some element such that $x \in (A \cap C) - B$.

By the definition of difference this means that $x \in A \cap C$ and
$x \notin B$. By the definition of $\cap$, this means that $x \in A$ or
$x \in C$ and $x \notin B$.

_Case $x \in A$:_

Since $x \in A$ and $x \notin B$, this means that $x \in A \cap B^c$. By the set
difference law, this means that $x \in A - B$.

_Case $x \in C$:_

Since $x \in C$ and $x \notin B$, this means that $x \in C \cap B^c$. By the set
difference law, this means that $x \in C - B$.

It follows that $x \in A - B$ or $x \in C - B$. By the definition of $\cap$,
this means that $x \in (A - B) \cap (C - B)$.

Thus every element in $(A \cap C) - B$ is in $(A - B) \cap (C - B)$. By the
definition of subset, this means that
$(A \cap C) - B \subseteq (A - B) \cap (C - B)$.

This is what was to be shown.

Q.E.D.

14. For all sets $A$ and $B$, $A \cup (A \cap B) = A$.

**Proof:**

Let $A$ and $B$ be any sets.

To prove $A \cup (A \cap B) = A$, it must be shown that
$A \cup (A \cap B) \subseteq A$ and $A \subseteq A \cup (A \cap B)$.

_Proof ($A \cup (A \cap B) \subseteq A$):_

Suppose $x$ is some element such that $x \in A \cup (A \cap B)$.

By the definition of $\cup$, this means that $x \in A$ or $x \in A \cap B$.

_Case $x \in A$:_

Since $x \in A$, by tautology, $x \in A$.

_Case $x \in A \cap B$:_

By the definition of $\cap$, $x \in A$ and $x \in B$.

In either case $x \in A$. By the definition of subset, this means that
$x \subseteq A$.

Thus every element in $A \cup (A \cap B)$ is in $A$. By the definition of
subset, this means that $A \cup (A \cap B) \subseteq A$.

This is what was to be shown.

_Proof ($A \subseteq A \cup (A \cap B)$):_

Suppose $x$ is some element such that $x \in A$.

By tautology, $x \in A \to x \in A$.

Since $x \in A$, $x \in A \cap B$, by virtue of $x \in A$.

It follows that $x \in A$ or $x \in A \cap B$.

Thus it can be said that every element in $A$ is in $A \cup (A \cap B)$. By
definition of subset, this means that $A \subseteq A \cup (A \cap B)$.

This is what was to be shown.

_Conclusion:_

Since both subset relations have been proved, it has been shown that
$A \cup (A \cap B) = A$.

Q.E.D.

15. For every set $A$, $A \cup \emptyset = A$.

**Proof:**

Let $A$ be any set.

To prove that $A \cup \emptyset = A$, it must be shown that
$A \cup \emptyset \subseteq A$, and that $A \subseteq A \cup \emptyset$.

_Proof ($A \cup \emptyset \subseteq A$):_

Suppose $x$ is some element such that $x \in A \cup \emptyset$.

By the definition of $\cup$, this means that $x \in A$ or $x \in emptyset$. But
$x \notin \emptyset$, as $\emptyset$ can have no elements.

Hence $x \in A$, and therefore $A \cup \emptyset \subseteq A$.

_Proof ($A \subseteq A \cup \emptyset$):_

Suppose $x$ is some element such that $x \in A$. It follows that $x \in A$ or
$x \in \emptyset$. By definition of $\cup$, this means that
$x \in A \cup \emptyset$.

Therefore $A \subseteq A \cup \emptyset$.

Since both subset relations have been proved, it can be said that
$A \cup \emptyset = A$ by the definition of set equality.

This is what was to be proved.

Q.E.D.

16. For all sets $A$, $B$, and $C$, if $A \subseteq B$ then
    $A \cap C \subseteq B \cap C$.

**Proof:**

Let $A$, $B$, and $C$ be any sets such that $A \subseteq B$.

Suppose $x$ is some element such that $x \in A \cap C$.

By the definition of $\cap$, this means that $x \in A$ and $x \in C$.

Since $x \in A$ and $A \subseteq B$, then $x \in B$ by definition of subset.

Since $x \in B$ and $x \in C$, by the definition of $\cap$, it can be said that
$x \in B \cap C$.

Thus it has been shown that any element in $A \cap C$ is in $B \cap C$.
Specifically $A \cap C \subseteq B \cap C$ by the definition of subset.

This is what was to be shown.

Q.E.D.

17. For all sets $A$, $B$, and $C$, if $A \subseteq B$ then
    $A \cup C \subseteq B \cup C$.

**Proof:**

Let $A$, $B$, and $C$ be any sets such that $A \subseteq B$.

Suppose $x$ is some element such that $x \in A \cup C$.

By definition of $\cup$, this means that $x \in A$ or $x \in C$.

_Case $x \in A$:_

Since $x \in A$ and since $A \subseteq B$, this means that $x \in B$.

_Case $x \in C$:_

By tautology, $x \in C$.

It follows that $x \in B$ or $x \in C$. By the definition of $\cup$, this is
$x \in B \cup C$.

Thus it can be said that any element in $A \cup C$ is in $B \cup C$, or
$A \cup C \subseteq B \cup C$ by the definition of subset.

This is what was to be shown.

Q.E.D.

18. For all sets $A$ and $B$, if $A \subseteq B$ then $B^c \subseteq A^c$.

**Proof:**

Let $A$ and $B$ be any sets such that $A \subseteq B$.

Suppose $x$ is some element such that $x \in B^c$.

By the definition of complement, this means that $x \notin B$.

Since $A \subseteq B$, it follows that any element not in $B$ is not in $A$,
thus $x \notin A$. By the definition of complement, this means that $x \in A^c$

Hence it can said that any element in $B^c$ is in $A^c$, or $B^c \subseteq A^c$
by the definition of subset.

This is what was to be shown.

Q.E.D.

19. For all sets $A$, $B$, and $C$, if $A \subseteq B$ and $A \subseteq C$ then
    $A \subseteq B \cap C$.

**Proof:**

Let $A$, $B$, and $C$ be any sets such that $A \subseteq B$ and $A \subseteq C$.

Suppose $x$ is some element such that $x \in A$.

Since $x \in A$ and $A \subseteq B$, it follows by the definition of subset that
$x \in B$.

Since $x \in A$ and $A \subseteq C$, it follows by the definition of subset that
$x \in C$.

Thus it can be said that $x \in B$ and $x \in C. By the definition of $\cap$,
this is $x \in B \cap C$.

Therefore it has been shown that any element in $A$ is in $B \cap C$, or
$A \subseteq B \cap C$, by the definition of subset.

This is what was to be shown.

Q.E.D.

20. For all sets $A$, $B$, and $C$, if $A \subseteq C$ and $B \subseteq C$ then
    $A \cup B \subseteq C$.

**Proof:**

Let $A$, $B$, and $C$ be any sets such that $A \subseteq C$ and $B \subseteq C$.

Suppose $x$ is some element such that $x \in A \cup B$.

By the definition of $\cup$, this means that $x \in A$ or $x \in B$.

_Case $x \in A$:_

Since $x \in A$ and $A \subseteq C$, this means, by definition of subset, that
$x \in C$.

_Case $x \in B$:_

Since $x \in B$ and $B \subseteq C$, this means, by definition of subset, that
$x \in C$.

In either case, $x \in C$.

Therefore it can be said that any element in $A \cup B$ is in $C$, or
$A \cup B \subseteq C$, by definition of subset.

This is what was to be shown.

Q.E.D.

21. For all sets $A$, $B$, and $C$,

$$ A \times (B \cup C) = (A \times B) \cup (A \times C) $$

**Proof:**

Let $A$, $B$, and $C$ be any set.

To prove $A \times (B \cup C) = (A \times B) \cup (A \times C)$, it must be
shown that $A \times (B \cup C) \subseteq (A \times B) \cup (A \times C)$ and
$(A \times B) \cup (A \times C) \subseteq A \times (B \cup C)$.

_Proof ($A \times (B \cup C) \subseteq (A \times B) \cup (A \times C)$):_

Suppose $(x, y)$ are any Cartesian pair such that
$(x, y) \in A \times (B \cup C)$.

By the definition of a Cartesian pair, this means that $x \in A$ and
$y \in B \cup C$.

By definition of $\cup$, this means that $y \in B$ or $y \in C$.

_Case $y \in B$:_

Since $x \in A$ and $y \in B$, by definition of Cartesian product,
$(x, y) \in A \times B$.

_Case $y \in C$:_

Since $x \in A$ and $y \in C$, by definition of Cartesian product,
$(x, y) \in A \times C$.

Thus it can be said that $(x, y) \in A \times B$ or $(x, y) \in A \times C$. By
definition of $\cup$, this is $(x, y) \in (A \times B) \cup (A \times C)$.

Thus it can be said that any Cartesian pair of elements in $A \times (B \cup C)$
are in $(A \times B) \cup (A \times C)$, or
$A \times (B \cup C) \subseteq (A \times B) \cup (A \times C)$.

This is what was to be shown.

_Proof ($(A \times B) \cup (A \times C) \subseteq A \times (B \cup C)$):_

Suppose $(x, y)$ are some Cartesian pair such that
$(x, y) \in (A \times B) \cup (A \times C)$.

By the definition of $\cup$, this means that $(x, y) \in (A \times B)$ or
$(x, y) \in (A \times C)$.

_Case $(x, y) \in (A \times B)$:_

This means that $x \in A$ and $y \in B$. Since $y \in B$, it follows that
$y \in B \cup C$, by virtue of $y \in B$.

Thus it can be said, by the definition of Cartesian product, that
$(x, y) \in A \times (B \cup C)$.

_Case $(x, y) \in (A \times C)$:_

This means that $x \in A$ and $y \in C$. Since $y \in C$, it follows that
$y \in B \cup C$, by virtue of $y \in C$.

Thus it can be said, by the definition of Cartesian product, that
$(x, y) \in A \times (B \cup C)$.

Hence in both cases $(x, y) \in A \times (B \cup C)$.

Thus it has been shown that every Cartesian pair in
$(A \times B) \cup (A \times C)$ is in $A \times (B \cup C)$, or
$(A \times B) \cup (A \times C) \subseteq A \times (B \cup C)$.

This is what was to be shown.

_Conclusion:_

Since both subset relations have been proven, it can be concluded that
$A \times (B \cup C) = (A \times B) \cup (A \times C)$ by the definition of set
equality.

This is what was to be shown.

Q.E.D.

22. For all sets $A$, $B$, and $C$,

$$ A \times (B \cap C) = (A \times B) \cap (A \times C) $$

**Proof:**

Let $A$, $B$, and $C$ be any sets.

To prove $A \times (B \cap C) = (A \times B) \cap (A \times C)$, it must be
shown that $A \times (B \cap C) \subseteq (A \times B) \cap (A \times C)$ and
that $(A \times B) \cap (A \times C) \subseteq A \times (B \cap C)$.

_Proof ($A \times (B \cap C) \subseteq (A \times B) \cap (A \times C)$):_

Suppose $(x, y)$ be some elements such that $(x, y) \in A \times (B \cap C)$.

This means that $x \in A$ and $y \in B \cap C$.

By the definition of $\cap$, this means that $y \in B$ and $y \in C$.

Since $x \in A$ and $y \in B$, this means that $(x, y) \in A \times B$ (by the
definition of Cartesian product).

Furthermore, since $x \in A$ and $y \in C$, this means that
$(x, y) \in A \times C$ (by the definition of Cartesian product).

Thus $(x, y) \in A \times B$ and $(x, y) \in A \times C$ or
$(x, y) \in (A \times B) \cap (A \times C)$ (by the definition of $\cap$).

Hence it has been shown that
$A \times (B \cap C) \subseteq (A \times B) \cap (A \times C)$.

_Proof ($(A \times B) \cap (A \times C) \subseteq A \times (B \cap C)$):_

Suppose $(x, y)$ be some elements such that
$(x, y) \in (A \times B) \cap (A \times C)$.

By the definition of $\cap$, this means that $(x, y) \in A \times B$ and
$(x, y) \in A \times C$.

Since $(x, y) \in A \times B$, $x \in A$ and $y \in B$.

Since $(x, y) \in A \times C$, this means that $x \in A$ and $y \in C$.

Since $y \in B$ and $y \in C$, $y \in B \cap C$ (by the definition of $\cap$).

Since $x \in A$ and $y \in B \cap C$, by the definition of Cartesian product,
$(x, y) \in A \times (B \cap C)$.

Hence it has been shown that
$(A \times B) \cap (A \times C) \subseteq A \times (B \cap C)$.

_Conclusion:_

Since both subset relations have been proven, it is concluded that
$A \times (B \cap C) = (A \times B) \cap (A \times C)$ by the definition of set
equality.

This is what was to be shown.

Q.E.D.

23. Find the mistake in the following "proof" that for all sets $A$, $B$, and
    $C$, if $A \subseteq B$ and $B \subseteq C$ then $A \subseteq C$.

**Proof:** Suppose $A$, $B$, and $C$ are any sets such that $A \subseteq B$ and
$B \subseteq C$. Since $A \subseteq B$, there is an element $x$ such that
$x \in A$ and $x \in B$, and since $B \subseteq C$, there is an element $x$ such
that $x \in B$ and $x \in C$. Hence there is an element $x$ such that $x \in A$
and $x \in C$ and so $A \subseteq C$.

There is more than one error in this "proof." The most serious is the misuse of
the definition of subset. To say that $A$ is a subset of $B$ means that for
every $x$, **if** $x \in A$ **then** $x \in B$. It does not mean that there
exists an element of $A$ that is also an element of $B$. The second error in the
proof occurs in the last sentence. Even if there is an element in $A$ that is in
$B$ and an element in $B$ that is in $C$, it does not follow that there is an
element in $A$ that is in $C$.

For instance, suppose $A = \{1, 2\}$, $B = \{2, 3\}$, and $C = \{3, 4\}$. Then
there is an element in $A$ that is in $B$ (namely $2$) and there is an element
in $B$ that is in $C$ (namely, $3$), but there is no element in $A$ that is in
$C$.

24. Find the mistake in the following "proof."

**Theorem:** For all sets $A$ and $B$, $A^c \cup B^c \subseteq (A \cup B)^c^c$

**Proof:** Suppose $A$ and $B$ are any sets, and $x \in A^c \cup B^c$. Then
$x \in A^c$ or $x \in B^c$ by definition of union. It follows that $x \notin A$
or $x \notin B$ by definition of complement, and so $x \notin A \cup B$ by
definition of union. Thus $x \in (A \cup B)^c$ by definition of complement, and
hence $A^c \cup B^c \subseteq (A \cup B)^c$.

The mistake in this "proof" occurs when the author misuses the definition of
union in the sentence "and so $x \notin A \cup B$ by definition of union."

For example, take $x = 1$, $A = \{1\}$ and $B = \{2\}$, then $A^c \cup B^c$ is
true since $B^c$ is true, but $x \notin A \cup B$ ($x \in (A \cup B)^c$) is
false since $1 \in \{1, 2\}$.

25. Find the mistake in the following "proof" that for all sets $A$ and $B$,
    $(A - B) \cup (A \cap B) \subseteq A$.

**Proof:** Suppose $A$ and $B$ are any sets, and suppose
$x \in (A - B) \cup (A \cap B)$. If $x \in A$ then $x \in A - B$, and so, by
definition of difference, $x \in A$ and $x \notin B$. In particular, $x \in A$,
and, therefore, $(A - B) \cup (A \cap B) \subseteq A$ by definition of subset.

The author of this "proof" makes a mistake when they assume the conclusion, "If
$x \in A$." The supposition should be "Suppose $x$ is some element such that
$x \in (A - B) \cup (A \cap B)$" and follow from there.

Furthermore it does not follow that if $x \in A$, then $x \in A - B$. Suppose
$A = B = \{x\}$, then $x \in A$, but $A - B = \emptyset$, and by definition of
$\emptyset$, $x \notin \emptyset$, so $x \notin A - B$.

26. Consider the Venn diagram below.

(See page 429 for image.)

a. Illustrate one of the distributive laws by shading in the region
corresponding to $A \cup (B \cap C)$ on one copy of the diagram and
$(A \cup B) \cap (A \cup C)$ on another.

Omitted.

b. Illustrate the other distributive law by shading in the region corresponding
to $A \cap (B \cup C)$ on one copy of the diagram and
$(A \cap B) \cup (A \cap C)$ on another.

Omitted.

c. Illustrate one of De Morgan's laws by shading in the region corresponding to
$(A \cup B)^c$ on one copy of the diagram and $A^c \cap B^c$ on the other.
(Leave the set $C$ out of your diagrams.)

Omitted.

d. Illustrate the other De Morgan's law by shading in the region corresponding
to $(A \cap B)^c$ on one copy of the diagram and $A^c \cup B^c$ on the other.
(Leave the set $C$ out of your diagrams.)

Omitted.

27. Fill in the blanks in the following proof that for all sets $A$ and $B$,
    $(A - B) \cap (B - A) = \emptyset$.

**Proof:**

Let $A$ and $B$ be any sets and suppose $(A - B) \cap (B - A) \neq \emptyset$.
That is, suppose there is an element $x$ in __ (a) __. BY definition of __ (b)
__, $x \in A - B$ and $x \in$ __ \(c\) __. Then by definition of set difference,
$x \in A$ and $x \notin B$ and $x \in$ __ (d) __ and $x \notin$ __ (e) __. IN
particular $x \in A$ and $x \notin$ __ (f) __, which is a contradiction. Hence
_[the supposition that $(A - B) \cap (B - A) \neq \emptyset$ is false, and so]_
__ (g) __.

a. $(A - B) \cap (B - A)$

b. intersection

c. $B - A$

d. $B$

e. $A$

f. $A$

g. $(A - B) \cap (B - A) = \emptyset$

Use the element method for proving a set equals the empty set to prove each
statement in 28-38. Assume that all sets are subsets of a universal set $U$.

28. For all sets $A$ and $B$, $(A \cap B) \cap (A \cap B^c) = \emptyset$. (This
    property is used in Section 9.9.)

**Proof (by contradiction):**

Let $A$ and $B$ be any sets and suppose
$(A \cap B) \cap (A \cap B^c) \neq \emptyset$.

Suppose $x$ is some element such that $x \in (A \cap B) \cap (A \cap B^c)$.

By the definition of $\cap$, this means that $x \in (A \cap B)$ and
$x \in (A \cap B^c)$.

Since $x \in (A \cap B)$, this means that $x \in A$ and $x \in B$.

Since $x \in (A \cap B^c)$, this means that $x \in A$ and $x \notin B$.

So $x \in B$ and $x \notin B$, which is a contradiction.

Hence the supposition is false, and therefore
$(A \cap B) \cap (A \cap B^c) = \emptyset$.

Q.E.D.

29. For all sets $A$, $B$, and $C$,

$$ (A - C) \cap (B - C) \cap (A - B) = \emptyset $$

**Proof (by contradiction):**

Let $A$, $B$, and $C$ be any sets, and suppose
$(A - C) \cap (B - C) \cap (A - B) \neq \emptyset$.

Suppose $x$ is some element such that $x \in (A - C) \cap (B - C) \cap (A - B)$.

By the definition of $\cap$, this means that $x \in (A - C)$ and $x \in (B - C)$
and $x \in (A - B)$.

By the definition of difference, this means that $x \in A$ and $x \notin C$ and
$x \in B$ and $x \notin C$ and $x \in A$ and $x \notin B$.

So $x \in B$ and $x \notin B$, which is a contradiction.

Hence the supposition is false, and therefore
$(A - C) \cap (B - C) \cap (A - B) = \emptyset$.

Q.E.D.

30. For every subset $A$ of a universal set $U$, $A \cap A^c = \emptyset$.

**Proof (by contradiction):**

Let $A$ be any set and suppose $A \cap A^c \neq \emptyset$.

Suppose $x$ is some element such that $x \in A \cap A^c$.

By the definition of $\cap$, this means that $x \in A$ and $x \in A^c$.

By the definition of complement, this means that $x \in A$ and $x \notin A$,
which is a contradiction.

Hence the supposition is false, and therefore $A \cap A^c = \emptyset$.

Q.E.D.

31. If $U$ denotes a universal set, then $U^c = \emptyset$.

**Proof (by contradiction):**

Let $U$ be the universal set of all elements, and suppose $U^c \neq \emptyset$.

Suppose $x$ is some element such that $x \in U^c$.

By definition of complement, this means that $x \notin U$.

Since $U$ is the universal set of all elements, it follows that $x \in U$.

So $x \notin U$ and $x \in U$, which is a contradiction.

Hence the supposition is false, and therefore $U^c = \emptyset$.

Q.E.D.

32. For every set $A$, $A \times \emptyset = \emptyset$.

**Proof (by contradiction):**

Let $A$ be any set and suppose $A \times \emptyset \neq \emptyset$.

Suppose $(x, y)$ are any element pair such that $(x, y) \in A \times \emptyset$.

By the definition of Cartesian product, this means that $x \in A$ and
$y \in emptyset$. By the definition of $\emptyset$, $y \notin \emptyset$.

So $y \in \emptyset$ and $y \notin \emptyset$, which is a contradiction.

Hence the supposition is false, and therefore $A \times \emptyset = \emptyset$.

Q.E.D.

33. For all sets $A$ and $B$, if $A \subseteq B$ then $A \cap B^c = \emptyset$.

**Proof (by contradiction):**

Let $A$ and $B$ be any sets such that $A \subseteq B$.

Suppose $A \cap B^c \neq \emptyset$. Then let $x$ be some element such that
$x \in A \cap B^c$.

By the definition of $\cap$, this means that $x \in A$ and $x \in B^c$. By the
definition of complement, this means that $x \in A$ and $x \notin B$.

Since $x \in A$ and $A \subseteq B$, it follows that $x \in B$ by definition of
subset.

So $x \notin B$ and $x \in B$, which is a contradiction.

Hence the supposition is false, therefore $A \cap B^c = \emptyset$.

Q.E.D.

34. For all sets $A$ and $B$, if $B \subseteq A^c$ then $A \cap B = \emptyset$.

**Proof (by contradiction):**

Let $A$ and $B$ be any sets such that $B \subseteq A^c$.

Suppose $A \cap B \neq \emptyset$. Then let $x$ be some element such that
$x \in A \cap B$.

By the definition of $\cap$, this means that $x \in A$ and $x \in B$.

Since $x \in B$ and $B \subseteq A^c$, it follows that $x \notin A$.

So $x \in A$ and $x \notin A$, which is a contradiction.

Hence the supposition is false, and therefore $A \cap B = \emptyset$.

Q.E.D.

35. For all sets $A$, $B$, and $C$, if $A \subseteq B$ and
    $B \cap C = \emptyset$ then $A \cap C = \emptyset$.

**Proof (by contradiction):**

Let $A$, $B$, and $C$ be any sets such that $A \subseteq B$ and
$B \cap C = \emptyset$.

Suppose $A \cap C \neq \emptyset$, then let $x$ be some element such that
$x \in A \cap C$.

By the definition of $\cap$, this means that $x \in A$ and $x \in C$.

Since $x \in A$ and $A \subseteq B$, then $x \in B$ by definition of subset.

Thus $x \in B$ and $x \in C$, which is, by definition of $\cap$,
$x \in B \cap C$.

$B \cap C = \emptyset$, so $x \in emptyset$.

But by the definition of $\emptyset$, $x \notin \emptyset$.

So $x \in \emptyset$ and $x \notin \emptyset$, which is a contradiction.

Hence the supposition is false, and therefore $A \cap C = \emptyset$.

Q.E.D.

36. For all sets $A$, $B$, and $C$, if $C \subseteq B - A$, then
    $A \cap C = \emptyset$.

**Proof (by contradiction):**

Let $A$, $B$, and $C$ be any sets such that $C \subseteq B - A$.

Suppose $A \cap C \neq \emptyset$, then let $x$ be some element such that
$x \in A \cap C$.

By the definition of $\cap$, this means that $x \in A$ and $x \in C$.

Since $x \in C$, and $C \subseteq B - A$, this means that $x \in B - A$.
Furthermore, by the definition of difference, this means that $x \in B$ and
$x \notin A$.

So $x \in A$ and $x \notin A$, which is a contradiction.

Hence the supposition is false, and therefore $A \cap C = \emptyset$.

Q.E.D.

37. For all sets $A$, $B$, and $C$, if $B \cap C \subseteq A$, then
    $(C - A) \cap (B - A) = \emptyset$.

**Proof (by contradiction):**

Let $A$, $B$, and $C$ be any sets such that $B \cap C \subseteq A$.

Suppose $(C - A) \cap (B - A) \neq \emptyset$, then let $x$ be some element such
that $x \in (C - A) \cap (B - A)$.

By the definition of $\cap$, this means that $x \in (C - A)$ and
$x \in (B - A)$.

By the definition of difference, this means that $x \in C$ and $x \notin A$ and
$x \in B$ and $x \notin A$.

Since $x \in B$ and $x \in C$, this means that $x \in B \cap C$.

$B \cap C \subseteq A$, so $x \in A$, by definition of subset.

So $x \notin A$ and $x \in A$, which is a contradiction.

Hence the supposition is false, and therefore
$(C - A) \cap (B - A) = \emptyset$.

38. For all sets $A$, $B$, $C$, and $D$, if $A \cap C = \emptyset$ then
    $(A \times B) \cap (C \times D) = \emptyset$.

Omitted.

Prove each statement in 39-44.

39. For all sets $A$ and $B$,

a. $(A - B) \cup (B - A) \cup (A \cap B) = A \cup B$

Omitted.

b. The sets $(A - B)$, $(B - A)$, and $(A \cap B)$ are mutually disjoint.

Omitted.

40. For every positive integer $n$, if $A$ and $B_1, B_2, B_3, \dots$ are any
    sets, then

$$ A \cap \left(\bigcup_{i = 1}^{n}B_i\right) = \bigcup_{i = 1}^{n}(A \cap B_i) $$

Omitted.

41. For every positive integer $n$, if $A_1, A_2, A_3, \dots$ and $B$ are any
    sets, then

$$ \bigcap_{i = 1}^{n}(A_i - B) = \left(\bigcup_{i = 1}^{n}A_i\right) - B $$

Omitted.

42. For every positive integer $n$, if $A_1, A_2, A_3, \dots$ and $B$ are any
    sets, then

$$ \bigcap_{i = 1}^{n}(A_i - B) = \left(\bigcap_{i = 1}^{n}A_i\right) - B $$

Omitted.

43. For every positive integer $n$, if $A$ and $B_1, B_2, B_3, \dots$ are any
    sets, then

$$ \bigcup_{i = 1}^{n}(A \times B_i) = A \times \left(\bigcup_{i = 1}^{n}B_i\right) $$

Omitted.

44. For every positive integer $n$, if $A$ and $B_1, B_2, B_3, \dots$ are any
    sets, then

$$ \bigcap_{i = 1}^{n}(A \times B_i) = A \times \left(\bigcap_{i = 1}^{n}B_i\right) $$

Omitted.
