## Operators in JavaScript

Operators in JavaScript are symbols that perform operations on operands. They can be classified into various categories based on their functionality.

### Arithmetic Operators

Arithmetic operators are used to perform mathematical calculations.

- **Addition (`+`):** Adds two operands.
- **Subtraction (`-`):** Subtracts the second operand from the first.
- **Multiplication (`*`):** Multiplies two operands.
- **Division (`/`):** Divides the first operand by the second.
- **Modulus (`%`):** Returns the remainder of the division of the first operand by the second.
- **Increment (`++`):** Increases the value of an operand by 1.
- **Decrement (`--`):** Decreases the value of an operand by 1.

### Assignment Operators

Assignment operators are used to assign values to variables.

- **Assignment (`=`):** Assigns the value of the right operand to the left operand.
- **Addition Assignment (`+=`):** Adds the value of the right operand to the variable and assigns the result to the variable.
- **Subtraction Assignment (`-=`):** Subtracts the value of the right operand from the variable and assigns the result to the variable.
- **Multiplication Assignment (`*=`):** Multiplies the variable by the value of the right operand and assigns the result to the variable.
- **Division Assignment (`/=`):** Divides the variable by the value of the right operand and assigns the result to the variable.
- **Modulus Assignment (`%=`):** Calculates the modulus of the variable and the right operand and assigns the result to the variable.

### Comparison Operators

Comparison operators are used to compare two values.

- **Equal to (`==`):** Returns true if the operands are equal.
- **Not equal to (`!=`):** Returns true if the operands are not equal.
- **Strict equal to (`===`):** Returns true if the operands are equal and of the same type.
- **Strict not equal to (`!==`):** Returns true if the operands are not equal and/or not of the same type.
- **Greater than (`>`):** Returns true if the left operand is greater than the right operand.
- **Less than (`<`):** Returns true if the left operand is less than the right operand.
- **Greater than or equal to (`>=`):** Returns true if the left operand is greater than or equal to the right operand.
- **Less than or equal to (`<=`):** Returns true if the left operand is less than or equal to the right operand.

### Logical Operators

Logical operators are used to combine or invert logical values.

- **Logical AND (`&&`):** Returns true if both operands are true.
- **Logical OR (`||`):** Returns true if either operand is true.
- **Logical NOT (`!`):** Returns true if the operand is false, and vice versa.

### Bitwise Operators

Bitwise operators perform bit-level manipulation of operands.

- **Bitwise AND (`&`):** Performs a bitwise AND operation.
- **Bitwise OR (`|`):** Performs a bitwise OR operation.
- **Bitwise XOR (`^`):** Performs a bitwise XOR (exclusive OR) operation.
- **Bitwise NOT (`~`):** Inverts the bits of its operand.
- **Left Shift (`<<`):** Shifts the bits of the left operand to the left by the number of positions specified by the right operand.
- **Right Shift (`>>`):** Shifts the bits of the left operand to the right by the number of positions specified by the right operand.
- **Zero-fill Right Shift (`>>>`):** Shifts the bits of the left operand to the right by the number of positions specified by the right operand, filling the leftmost bits with zeros.

### Conditional (Ternary) Operator

The conditional operator (`?:`) is a shorthand for an `if...else` statement.

```
let result = (condition) ? value1 : value2;
```
If `condition` is true, `value1` is returned; otherwise, `value2` is returned.