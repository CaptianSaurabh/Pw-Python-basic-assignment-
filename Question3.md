Question no. 3 >> compare the contrast mutable and imutable object in python with example

Answer >> 

## Mutable vs Immutable Objects in Python ##

In Python, objects can be either mutable or immutable. The main difference between the two is that mutable objects can be modified after creation, while immutable objects cannot.

## 1  Mutable Objects >>

Mutable objects can be changed after they are created. Examples of mutable objects include:
>> Lists, Dictionaries, Sets, User-defined classes

# Create a mutable list
my_list = [1, 2, 3]

# Modify the list
my_list.append(4)
print(my_list)  # [1, 2, 3, 4]

## 2 Immutable Objects

Immutable objects cannot be changed after they are created. Examples of immutable objects include:
>> Integers, Floats, Strings, Tuples

# Create an immutable string
my_string = "hello"

# Try to modify the string
try:
    my_string[0] = "H"
except TypeError:
    print("Cannot modify an immutable object!")


## >> Key Takeaways:

Mutable objects can be modified after creation.
Immutable objects cannot be modified after creation.
Use mutable objects when you need to modify data, and immutable objects when you need to ensure data integrity.