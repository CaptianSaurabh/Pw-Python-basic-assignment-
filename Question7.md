Question no. 7 >> Describe the diffrent types of loops in python and their use cases with example.

Types of Loops in Python
Python has two main types of loops: For Loops and While Loops. Each type of loop has its own use cases and is used to iterate over a sequence of values or to repeat a block of code.

1. For Loops
For loops are used to iterate over a sequence of values, such as a list, tuple, or string.

Syntax:
for variable in iterable:
    # code to execute
Use Cases:

Iterating over a list of items
Iterating over a string of characters
Iterating over a dictionary's keys or values
Example:
fruits = ['apple', 'banana', 'cherry']
for fruit in fruits:
    print(fruit)

Output:
apple
banana
cherry


2. While Loops
While loops are used to repeat a block of code as long as a certain condition is true.

Syntax:

while condition:
    # code to execute
Use Cases:

Repeating a task until a certain condition is met
Reading input from a user until a certain condition is met
Simulating a game loop
Example:
i = 0
while i < 5:
    print(i)
    i += 1

Output:
0
1
2
3
4


3. Nested Loops
Nested loops are used to iterate over multiple sequences of values.

Example:

for i in range(3):
    for j in range(3):
        print(i, j)

Output:
0 0
0 1
0 2
1 0
1 1
1 2
2 0
2 1
2 2

## >> Key Takeaways:

For loops are used to iterate over a sequence of values.
While loops are used to repeat a block of code until a condition is met.
Nested loops are used to iterate over multiple sequences of values.
Loops are essential in Python programming and are used to perform repetitive tasks.