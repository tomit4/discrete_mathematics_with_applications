**Test Yourself**

Page 73

1. An _and_ statement is true when, and only when, both components are _______.

**Solution**

True.

2. An _or_ statement is false when, and only when, both components are _______.

**Solution**

False.

3. Two statement forms are logically equivalent when, and only when, they always
   have _______.

**Solution**

The same truth values.

4. De Morgan's laws says (1) that the negation of an _and_ statement is
   logically equivalent to the _______ statement in which each component is
   _______, and (2) that the negation of an _or_ statement is logically
   equivalent to the _______ statement in which each component is _______.

**Solution**

or; negated; and; negated.

5. A tautology is a statement that is always _______.

**Solution**

true

6. A contradiction is a statement that is always _______.

**Solution**

false

---

**Test Yourself**

Page 86

1. An _if-then_ statement is false if, and only if, the hypothesis is _______
   and the conclusion is _______.

**Solution**

true; false

2. The negation of "if $p$ then $q$" is _______.

**Solution**

$p$ and not $q$.

$$ p \wedge \neg q $$

3. The converse of "if $p$ then $q$" is _______.

**Solution**

if $q$ then $p$

$$ q \to p $$

4. The contrapositive of "if $p$ then $q$" is _______.

**Solution**

if not $q$ then not $p$.

$$ \neg q \to \neg p $$

5. The inverse of "if $p$ then $q$" is _______.

**Solution**

if not $p$ then not $q$.

$$ \neg p \to \neg q $$

6. A conditional statement and its contrapositive are _______.

**Solution**

logically equivalent.

7. A conditional statement and its converse are not _______.

**Solution**

logically equivalent.

8. "$R$ is a sufficient condition for $S$" means "if _______ then _______."

**Solution**

$R$; $S$.

9. "$R$ is a necessary condition for $S$" means "if _______ then _______."

**Solution**

$S$; $R$

10. "$R$ only if $S$" means "if _______ then _______."

**Solution**

$R$; $S$

---

**Test Yourself**

Page 99

1. For an argument to be valid means that every argument of the same form whose
   premises _______ has a _______ conclusion.

are all true; true

2. For an argument to be invalid means that there is an argument of the same
   form whose premises _______ and whose conclusion _______.

are all true; is false

3. For an argument to be sound means that it is _______ and its premises
   _______. In this case we can be sure that its conclusion _______.

valid; are all true; is true

---

**Test Yourself**

Page 113

1. The input/output table for a digital logic circuit is a table that shows
   _______.

The output signal(s) that correspond to all possible combinations of input
signals to the circuit.

2. The Boolean expression that corresponds to a digital logic circuit is
   _______.

a Boolean expression that represents the input signals as variables and
indicates the successive actions of the logic gates on the input signals.

3. A recognizer is a digital logic circuit that _______.

outputs a 1 for exactly one particular combination of input signals and outputs
0s for all other combinations.

4. Two digital logic circuits are equivalent if, and only if, _______.

they have the same input/output table

5. A NAND-gate is constructed by placing a _______ gate immediately following an
   _______ gate.

NOT; AND

6. A NOR-gate is constructed by placing a _______ gate immediately following an
   _______ gate.

NOT; OR

---

**Test Yourself**

Page 129

1. To represent a nonnegative integer in binary notation means to write it as a
   sum of products of the form _______, where _______.

$d \cdot 2^n$ $d = 1$, and $n$ is a nonnegative integer.

2. To add integers in binary notation, you use the facts that $1_2 + 1_2 = $
   _______ and $1_2 + 1_2 + 1_2 = $ _______.

$10_2$; $11_2$

3. To subtract integers in binary notation, you use the facts that $10_2 - 1_2 =
   $ _______ and $11_2 - 1_2 = $ _______.

$1_2$; $10_2$

4. A half-adder is a digital logic circuit that _______, and a full-adder is a
   digital logic circuit that _______.

outputs the sum of any two binary digits; outputs the sum of any three binary
digits

5. If $a$ is an integer with $-128 \leq a \leq 127$, the 8-bit two's complement
   of $a$ is _______ if $a \geq 0$ and is _______ if $a < 0$.

The 8-bit representation of $a$; The 8-bit representation of $2^8 - |a|$

6. To find the 8-bit two's complement of a negative integer $a$ that is at least
   -128, you _______, _______, and _______.

- Write the 8-bit binary representation for $|a|$.

- Switch all the 1's to 0's and all the 0's to 1's. (This is called flipping, or
  complementing, the bits.)

- Add 1 in binary notation.

7. To add two integers in the range -128 through 127 whose sum is also in the
   range -128 through 127, you _______, ______, _______, and _______.

- Convert both integers to their 8-bit two's complement representations.

- Add the resulting integers using ordinary binary addition,

- Discarding any carry bit of 1 that may occur in the 2<sup>8</sup>th position.

- Convert the result back to decimal form.

8. To represent a nonnegative integer in hexadecimal notation means to write it
   as a sum of products of the form _______, where _______.

$d \cdot 16^n$; $d = 0, 1, 2, \dots 9, A, B, C, D, E, F$ and $n$ is a
nonnegative integer.

9. To convert a nonnegative integer from hexadecimal to binary notation, you
   _______ and _______.

- Write each hexadecimal digit of the integer in 4-bit binary notation.

- Juxtapose the results.
