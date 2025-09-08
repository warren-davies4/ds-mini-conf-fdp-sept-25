# Getting Started with Python

Welcome to the Python Getting Started guide! This document is designed to help you set up Python on your machine and get you started with the basics of programming in Python.

## Installation

### Windows

1. Download the Python installer from the [official Python website](https://www.python.org/downloads/).
2. Run the installer and ensure you check the box that says "Add Python to PATH".
3. Follow the installation instructions.

### macOS

1. You can install Python using Homebrew. Open your terminal and run:
   ```
   brew install python
   ```
2. Alternatively, download the installer from the [official Python website](https://www.python.org/downloads/) and follow the instructions.

### Linux

1. Most Linux distributions come with Python pre-installed. You can check if Python is installed by running:
   ```
   python3 --version
   ```
2. If it's not installed, you can install it using:
   ```
   sudo apt update
   sudo apt install python3
   ```

## Basic Syntax

### Hello, World!

The first program you should write in any programming language is a simple "Hello, World!" program. In Python, you can do this with the following code:

```python
print("Hello, World!")
```

### Variables and Data Types

In Python, you can create variables to store data. Here are some examples:

```python
# Integer
age = 30

# Float
height = 5.9

# String
name = "Alice"

# Boolean
is_student = True
```

### Control Structures

Python uses indentation to define blocks of code. Here’s an example of a simple `if` statement:

```python
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

## Simple Examples

### A Simple Calculator

Here’s a basic example of a calculator that adds two numbers:

```python
def add(x, y):
    return x + y

num1 = 5
num2 = 10
result = add(num1, num2)
print("The sum is:", result)
```

### Looping Through a List

You can use loops to iterate through lists. Here’s an example:

```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

## Conclusion

Congratulations! You have now set up Python and learned some basic syntax. You can explore more about Python programming by checking out the other sections of this documentation. Happy coding!