Page 61

**Definition**

A **statement** (or **proposition**) is a sentence that is true or false but not
both.

---

Page 63

**Definition**

If $p$ is a statement variable, the **negation** of $p$ is "not $p$" or "It is
not the case that $p$" and is denoted $\neg p$. It has opposite truth value from
$p$: if $p$ is true, $\neg p$ is false; if $p$ is false, $\neg p$ is true.

---

Page 64

**Definition**

If $p$ and $q$ are statement variables, the **conjunction** of $p$ and $q$ is
"$p$ and $q$", denoted $p \wedge q$. It is true when, and only when, both $p$
and $q$ are true. If either $p$ or $q$ is false, or if both are false,
$p \wedge q$ is false.

---

Page 64

**Definition**

If $p$ and $q$ are statement variables, the **disjunction** of $p$ and $q$ is
"$p$ or $q$", denoted $p \vee q$. It is true when either $p$ is true, or $q$ is
true, or both $p$ and $q$ are true; it is false only when both $p$ and $q$ are
false.

---

Page 65

**Definition**

A **statement form** (or **propositional form**) is an expression made up of
statement variables (such as $p$, $q$, and $r$) and logical connectives (such as
$\neg$, $\wedge$, and $\vee$) that becomes a statement when actual statements
are substituted for the component statement variables. The **truth table** for a
given statement form displays the truth values that correspond to all possible
combinations of truth values for its component statement variables.

---

Page 67

**Definition**

Two _statement forms_ are called **logically equivalent** if, and only if, they
have identical truth values for each possible substitution of statements for
their statement variables. The logical equivalence of statements forms $P$ and
$Q$ is denoted by writing $P \equiv Q$.

Two _statements_ are called **logically equivalent** if, and only if, they have
logically equivalent forms when identical component statement variables are used
to replace identical component statements.

---

Page 69

**De Morgan's Laws**

The negation of an _and_ statement is logically equivalent to the _or_ statement
in which each component is negated.

The negation of an _or_ statement is logically equivalent to the _and_ statement
in which each component is negated.

---

Page 71

**Definition**

A **tautology** is a statement form that is always true regardless of the truth
values of the individual statements substituted for its statement variables. A
statement whose form is a tautology is a **tautological statement**.

A **contradiction** is a statement form that is always false regardless of the
truth values of the individual statements substituted for its statement
variables. A statement whose form is a contradiction is a **contradictory
statement**.

---

Page 72

**Theorem 2.1.1 Logical Equivalences**

Given any statement variables $p$, $q$, and $r$, a tautology $\mathbf{t}$ and a
contradiction $\mathbf{c}$, the following logical equivalences hold.

1. _Communitative laws:_

$$ p \wedge q \equiv q \wedge p $$

$$ p \vee q \equiv q \vee p $$

2. _Associative laws:_

$$ (p \wedge q) \wedge r \equiv p \wedge (q \wedge r) $$

$$ (p \vee q) \vee r \equiv p \vee (q \vee r) $$

3. _Distributive laws:_

$$ p \wedge (q \vee r) \equiv (p \wedge q) \vee (p \wedge r) $$

$$ p \vee (q \wedge r) \equiv (p \vee q) \wedge (p \vee r) $$

4. _Identity laws:_

$$ p \wedge \mathbf{t} \equiv p $$

$$ p \vee \mathbf{c} \equiv p $$

5. _Negation laws:_

$$ p \vee \neg p \equiv \mathbf{t} $$

$$ p \wedge \neg p \equiv \mathbf{c} $$

6. _Double negative law:_

$$ \neg(\neg p) \equiv p $$

6. _Idempotent laws:_

$$ p \wedge p \equiv p $$

$$ p \vee p \equiv p $$

8. _Universal bound laws:_Double

$$ p \vee \mathbf{t} \equiv \mathbf{t} $$

$$ p \wedge \mathbf{c} \equiv \mathbf{c} $$

9. _De Morgan's laws:_

$$ \neg (p \wedge q) \equiv \neg p \vee \neg q $$

$$ \neg (p \vee q) \equiv \neg p \wedge \neg q $$

10 _Absorption laws:_

$$ p \vee (p \wedge q) \equiv p $$

$$ p \wedge (p \vee q) \equiv p $$

11. _Negations of $\mathbf{t}$ and $\mathbf{c}$:_

$$ \neg \mathbf{t} \equiv \mathbf{c} $$

$$ \neg \mathbf{c} \equiv \mathbf{t} $$

---

Page 77

**Definition**

If $p$ and $q$ are statement variables, the **conditional** of $q$ by $p$ is "If
$p$ then $q$" or "$p$ implies $q$" and is denoted $p \to q$. It is false when
$p$ is true and $q$ is false; otherwise it is true. We call $p$ the
**hypothesis** (or **antecedent**) if the conditional and $q$ the **conclusion**
(or **consequent**).

---

Page 80

**Definition**

The **contrapositive** of a conditional statement of the form "If $p$ then $q"
is

$$ \text{If } \neg q \text{ then } \neg p $$

Symbolically,

The contrapositive of $p \to q$ is $\neg q \to \neg p$.

---

Page 81

**Definition**

Suppose a conditional statement of the form "If $p$ then $q$" is given.

1. The **converse** is "If $q$ then $p$."

2. The **inverse** is "If $\neg p$ then $\neg q$."

Symbolically,

The converse of $p \to q$ is $q \to p$,

and

The inverse of $p \to q$ is $\neg p \to \neg q$.

---

Page 82

**Definition**

If $p$ and $q$ are statements,

$p$ **only if** $q$ means "if not $q$, then not $p$,"

or, equivalently,

"if $p$ then $q$."

---

Page 83

**Definition**

Given statement variables $p$ and $q$, the **biconditional of $p$ and $q$** is
"$p$ if, and only if, $q$", and is denoted $p \leftrightarrow q$. It is true if
both $p$ and $q$ have the same truth values and is false if $p$ and $q$ have
opposite truth values. The words _if and only if_ are sometimes abbreviated
**iff**.

---

Page 84

**Definition**

If $r$ and $s$ are statements:

$r$ is a **sufficient condition** for $s$ means "if $r$ then $s$."

$r$ is a **necessarily condition** for $s$ means "if not $r$, then not $s$."

---

Page 89

**Definition**

An **argument is a sequence of statements, and an **argument form** is a
sequence of statement forms. All statements in an argument and all statement
forms in an argument form, except for the final one, are called **premises** (or
**assumptions** or **hypotheses**). The final statement or statement form is
called the **conclusion**. The symbol $\therefore$, which is read "therefore,"
is normally placed just before the conclusion.

To say that an _argument form_ is **valid** means that no matter what particular
statements are substituted for the statement variables in its premises, if the
resulting premises are all true, then the conclusion is also true. To say that
an _argument_ is **valid** means that its form is valid.

---

Page 90

**testing an Argument for Validity**

1. Identify the premises and conclusion of the argument form.

2. Construct a truth table showing the truth values of all the premises and the
   conclusion.

3. A row of the truth table in which all the premises are true is called a
   **critical row**. If there is a critical row in which the conclusion is
   false, then it is possible for an argument of the given form to have true
   premises and a false conclusion, and so the argument form is invalid. If the
   conclusion in _every_ critical row is true, then the argument form is valid.

---

Page 97

**Definition**

An argument is called **sound** if, and only if, it is valid _and_ all its
premises are true. An argument that is not sound is called **unsound**.

---

Page 97

**Contradiction Rule**

If you can show that the supposition that statement $p$ is false leads logically
to a contradiction, then you can conclude that $pr is true.
