Question no. 4 >> Discuss the diffrent type of opretor in python and provide example how they are used

Answer >>
## >> Operators in Python
Python has several types of operators that are used to perform various operations on variables and values. Here are the different types of operators in Python:

## 1. Arithmetic Operators
Used for basic mathematical operations.

Operator	Description	Example
+	Addition	a = 5; b = 3; print(a + b) # 8
-	Subtraction	a = 5; b = 3; print(a - b) # 2
*	Multiplication	a = 5; b = 3; print(a * b) # 15
/	Division	a = 10; b = 2; print(a / b) # 5.0
%	Modulus (remainder)	a = 10; b = 3; print(a % b) # 1
**	Exponentiation	a = 2; b = 3; print(a ** b) # 8
## 2. Comparison Operators
Used to compare values.

Operator	Description	Example
==	Equal to	a = 5; b = 5; print(a == b) # True
!=	Not equal to	a = 5; b = 3; print(a != b) # True
>	Greater than	a = 5; b = 3; print(a > b) # True
<	Less than	a = 5; b = 3; print(a < b) # False
>=	Greater than or equal to	a = 5; b = 5; print(a >= b) # True
<=	Less than or equal to	a = 5; b = 3; print(a <= b) # False

## 3. Logical Operators
Used to combine conditional statements.

Operator	Description	Example
and	Logical AND	a = 5; b = 3; print(a > 2 and b > 2) # False
or	Logical OR	a = 5; b = 3; print(a > 2 or b > 2) # True
not	Logical NOT	a = 5; print(not a > 2) # False

## 4. Assignment Operators
Used to assign values to variables.

Operator	Description	Example
=	Assignment	a = 5; print(a) # 5
+=	Addition assignment	a = 5; a += 3; print(a) # 8
-=	Subtraction assignment	a = 5; a -= 3; print(a) # 2
*=	Multiplication assignment	a = 5; a *= 3; print(a) # 15
/=	Division assignment	a = 10; a /= 2; print(a) # 5.0

## 5. Membership Operators
Used to test membership in sequences.

Operator	Description	Example
in	Membership test	my_list = [1, 2, 3]; print(2 in my_list) # True
not in	Non-membership test	my_list = [1, 2, 3]; print(4 not in my_list) # True

## 6. Identity Operators
Used to test object identity.

Operator	Description	Example
is	Identity test	a = 5; b = 5; print(a is b) # True
is not	Non-identity test	a = 5; b = 3; print(a is not b) # True
These are the different types of operators in Python, along with examples of how they are used.