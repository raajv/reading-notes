Operators
JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

Assignment operators
Comparison operators
Arithmetic operators
Bitwise operators
Logical operators
String operators
Conditional (ternary) operator
Comma operator
Unary operators
Relational operators
JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

operand1 operator operand2
Copy to Clipboard
For example, 3+4 or x*y.

A unary operator requires a single operand, either before or after the operator:

operator operand
Copy to Clipboard
or

operand operator
Copy to Clipboard
For example, x++ or ++x.

Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.
Arithmetic operators
Operator	Description	Example
Remainder (%)	Binary operator. Returns the integer remainder of dividing the two operands.	12 % 5 returns 2.
Increment (++)	Unary operator. Adds one to its operand. If used as a prefix operator (++x), returns the value of its operand after adding one; if used as a postfix operator (x++), returns the value of its operand before adding one.	If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4.
Decrement (--)	Unary operator. Subtracts one from its operand. The return value is analogous to that for the increment operator.	If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2.
Unary negation (-)	Unary operator. Returns the negation of its operand.	If x is 3, then -x returns -3.
Unary plus (+)	Unary operator. Attempts to convert the operand to a number, if it is not already.	
+"3" returns 3.

+true returns 1.

Exponentiation operator (**)	Calculates the base to the exponent power, that is, base^exponent	2 ** 3 returns 8.
10 ** -1 returns 0.1.
