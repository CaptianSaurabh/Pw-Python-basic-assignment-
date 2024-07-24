Question no. 6 >> How do conditional statements work in python ? lustrate with example.

Answer
Conditional Statements in Python
Conditional statements in Python are used to execute different blocks of code based on certain conditions or decisions. They are used to control the flow of a program's execution.

Types of Conditional Statements:
## 1 >>
if Statement:
if condition:
    # code to execute if condition is True
## 2 >>
if-else Statement:
if condition:
    # code to execute if condition is True
else:
    # code to execute if condition is False
## 3 >>
if-elif-else Statement:
if condition1:
    # code to execute if condition1 is True
elif condition2:
    # code to execute if condition1 is False and condition2 is True
else:
    # code to execute if both conditions are False
Examples:

if Statement:
x = 5
if x > 10:
    print("x is greater than 10")
Output: No output, because the condition x > 10 is False.
## 4 >>
if-else Statement:
x = 5
if x > 10:
    print("x is greater than 10")
else:
    print("x is less than or equal to 10")
Output: x is less than or equal to 10
## 5 >>
if-elif-else Statement:
x = 5
if x > 10:
    print("x is greater than 10")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")
Output: x is equal to 5


## >> Key Takeaways:

Conditional statements are used to control the flow of a program's execution.
if statements are used to execute code if a condition is True.
if-else statements are used to execute different code blocks based on a condition.
if-elif-else statements are used to execute different code blocks based on multiple conditions.
Conditional statements are essential in Python programming.