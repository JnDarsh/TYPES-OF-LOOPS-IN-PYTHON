# Types of Loops in Python ⭐
# AIM

To understand and practice different types of loops in Python using numbers and symbols, and apply them to repetitive tasks.

# THEORY

Loops are used to repeat a block of code multiple times.
Python has mainly two types of loops:

1. For Loop 🔁

Iterates over a sequence like list, tuple, string, or range.

Syntax:

for variable in sequence:
    # code block


Example (Numbers 1–5):

for i in range(1, 6):
    print(i)


Output:

1
2
3
4
5


2. While Loop ⏳

Repeats a block while a condition is True.


3. Nested Loops 🔄

A loop inside another loop

Useful for pyramids, patterns, and grids

Example (Right-Angled Triangle):

for i in range(1, 6):
    for j in range(i):
        print("*", end=" ")
    print()


Output:

* 
* * 
* * * 
* * * * 
* * * * * 



# APPLICATIONS 💡

Repeating tasks automatically

Printing patterns with symbols or numbers

Iterating over lists, strings, or dictionaries

Building games, simulations, and tables

# CONCLUSION ✅

Loops are essential for repetitive tasks. Using for, while, or nested loops makes code efficient and readable.

# USAGE

For loop → when the number of iterations is known

While loop → when iterations depend on a condition

Nested loop → for patterns, tables, grids, or multi-level repetition

# WHAT WE LEARNT 🎓

Difference between for and while loops

How to use nested loops for complex patterns

Practical usage of loops with symbols and numbers

Loops make Python code short, neat, and efficient
