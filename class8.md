# Class 8 Notes

## Operators

**JavaScript** has both binary and unary operators, and one special ternary operator, which is the conditional operator. Binary operators require two operands, one before the operator and one after the operator. Here are two of the types of operators:

- **Assignment operators** assign a value to its left operand based on the value of its right operand. The assignment operator is (=),which assigns the value of its right operand to its left. There is also compound assignment operatores, here some examples(on the examples below names are on the left, operator in the middle and meaning of what the operator is doing is on the on the right):
- Assignment, x = f(), x = f()

- Addition assignment, x += f(), x = x + f()

- Subtraction assignment, x -= f(), x = x - f()

- Multiplication assignment, x *= f(), x = x * f()

- Division assignment, x /= f(),x = x / f()

- Remainder assignment, x %= f(), x = x % f()

- Exponentiation assignment, x **= f(), x = x ** f()

- Left shift assignment, x <<= f(), x = x << f()

- Right shift assignment, x >>= f(), x = x >> f()

- Unsigned right shift assignment, x >>>= f(), x = x >>> f()

- Bitwise AND assignment, x &= f(), x = x & f()

- Bitwise XOR assignment, x ^= f(), x = x ^ f()

- Bitwise OR assignment, x |= f(), x = x | f()

- **Comparison operators** compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. In most cases, if the two operands are not of the same type, JavaScript will attempt to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. Here are some examples of comparison operators:

- Equal (==)- Returns true if the operands are equal

- Not equal (!=)- Returns true if the operands are not equal

- Strict equal (===)- Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS.

- Strict not equal (!==)- Returns true if the operands are of the same type but not equal, or are of different type.

- Greater than (>)- Returns true if the left operand is greater than the right operand.

- Greater than or equal (>=)- Returns true if the left operand is greater than or equal to the right operand.

- Less than (<)- Returns true if the left operand is less than the right operand

- Less than or equal (<=)- Returns true if the left operand is less than or equal to the right operand

## Expressions

An **expression** is any valid unit of code that resolves to a value. There are two types of expressions, those with side effects and those that in some sense evaluate and therefore resolve to a value. Here the following expressions in JavaScript:

- Arithmetic: evaluates to a number

- String: evaluates to a character string

- Logical: evaluates to true or false

- Primary expressions: Basic keywords and general expressions in JavaScript

- Left-hand-side expressions: Left values are the destination of an assignment

## Loops

**Loops** offer a quick and easy way to do something over and over again. There are many different kinds of loops, but they all basically do the same thing(repeat an action). Here are the statements for loops:

- for statement

- do...while statement

- while statement

- labeled statement

- break statement

- continue statement

- for...in statement

- for...of statement