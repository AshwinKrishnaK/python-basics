# Python Basics

## Introduction
This repository contains the fundamental concepts of Python programming, covering a wide range of topics including variables, loops, data structures, functions, modules, file handling, exception handling, and object-oriented programming. It is designed to help beginners understand and practice Python basics.

## Table of Contents
1. [Variables](#variables)
2. [Loops](#loops)
3. [Data Structures](#data-structures)
    - [List](#list)
    - [Tuple](#tuple)
    - [Set](#set)
    - [Dictionary](#dictionary)
4. [Functions](#functions)
5. [Modules and Packages](#modules-and-packages)
6. [File Handling](#file-handling)
7. [Exception Handling](#exception-handling)
8. [Object-Oriented Programming (OOP)](#object-oriented-programming)
9. [Common Python Errors](#common-python-errors)

## Variables
Variables are used to store data in Python. You can assign different types of data to variables:

```python
x = 5  # integer
name = "Alice"  # string
price = 19.99  # float
is_available = True  # boolean
```

## Loops
Loops are used to iterate over sequences or execute a block of code multiple times:

### For Loop
```python
for i in range(5):  # Will loop from 0 to 4
    print(i)
```

### While Loop
```python
count = 0
while count < 3:
    print(count)
    count += 1
```

## Data Structures
### List
A list is used to store multiple items in a single variable. Lists are ordered, changeable, and allow duplicate values.

```python
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")  # Add an element to the end
```

### Tuple
A tuple is similar to a list, but it is immutable (cannot be changed).

```python
coordinates = (4, 5)
```

### Set
A set is an unordered collection that does not allow duplicate items.

```python
unique_numbers = {1, 2, 3, 4}
```

### Dictionary
A dictionary is used to store data in key-value pairs.

```python
person = {"name": "Alice", "age": 25}
print(person["name"])
```

## Functions
Functions are used to group reusable pieces of code.

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))
```

## Modules and Packages
Modules are Python files that contain functions or classes. You can import them into your code to reuse the functions:

```python
import math
print(math.sqrt(16))
```

Packages are collections of modules that are organized in directories.

## File Handling
You can use Python to read from or write to files:

```python
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```

## Exception Handling
Exceptions are errors that occur during execution. You can use `try` and `except` blocks to handle them gracefully:

```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("You cannot divide by zero!")
```

## Object-Oriented Programming
OOP is a paradigm that allows you to create classes and objects:

```python
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def start(self):
        print(f"{self.brand} {self.model} is starting.")

my_car = Car("Toyota", "Corolla")
my_car.start()
```

## Common Python Errors
1. **SyntaxError**: Happens when Python cannot understand the code due to incorrect syntax.
2. **IndentationError**: Occurs when there is incorrect indentation in the code.
3. **TypeError**: Occurs when an operation is applied to an object of inappropriate type.

## Conclusion
This repository serves as a starting point for anyone looking to learn Python. Each section contains examples to practice, making it easy to follow along and understand the concepts.

