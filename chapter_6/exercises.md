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
