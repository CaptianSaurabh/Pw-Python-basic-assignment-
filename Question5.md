Question no. 5 Explain the concept of type casting in python wirh example


## >> Type Casting in Python
Type casting, also known as type conversion, is the process of converting a value of one data type to another data type. In Python, type casting is used to convert a value of one type to another type, such as converting a string to an integer or a float to a string.

Types of Type Casting:

## Implicit Type Casting: >> Python automatically performs implicit type casting in certain situations, such as when you assign a value of one type to a variable of another type.
## Explicit Type Casting: >> You can use built-in functions to explicitly cast a value from one type to another.
Examples:

## 1  >>Implicit Type Casting: 
# Assign a string to a variable
x = "10"
# Python implicitly converts the string to an integer
y = x + 5
print(y)  # 15


## 2 >>Explicit Type Casting:
int() function: Converts a value to an integer.
x = "10"
y = int(x)
print(y)  # 10

float() function: Converts a value to a float.
Copy code
x = "10.5"
y = float(x)
print(y)  # 10.5

str() function: Converts a value to a string.
x = 10
y = str(x)
print(y)  # "10"

list() function: Converts a value to a list.
x = "hello"
y = list(x)
print(y)  # ["h", "e", "l", "l", "o"]

tuple() function: Converts a value to a tuple.
x = "hello"
y = tuple(x)
print(y)  # ("h", "e", "l", "l", "o")

## >> Key Takeaways:

Type casting is used to convert a value of one data type to another data type.
Python performs implicit type casting in certain situations.
You can use built-in functions to explicitly cast a value from one type to another.
Type casting is useful when working with different data types in Python.