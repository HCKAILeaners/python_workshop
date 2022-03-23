# Day 1 of Python Workshop

## Goals:

Get to know about:

- [x] Programming Languages
  
  - What makes a programming language low level and high level?
  - Compiled and Interpreted?

- [x] Python
  
  - Introduction
    - Why it's so popular?
    - Code execution pattern

- [x] Print Statement
  
  - printing hello world
  - formated printing

- [x] Variables

- [x] Arithmetic operations

- [x] Help method in python

- [ ] Taking Input

- [ ] Data Types in detail

## Programming Language

In layman's term, its the language to interact with computer and tell it what to do.

### What makes programming language high level and low level?

- High Level Programming Language
  It is more user oriented i.e., closely resembles English and made to make developer more productive.

- Low Level Programming Language
  It is more machine oriented i.e., close to computer's hardware and doesn't resemble English that much.
  
  ### Compiled and Interpreted

- Compiled
  The source code is scanned and complied at once into executable code which is machine dependent.

- Interpreted
  The source code is usually converted to intermediate language i.e., byte_code and each instruction is executed using virtual machine.

# Python

Python is a high level general purpose programming language. It is dynamically typed and has automatic garbage collection.
High Level since it closely resembles English, General purpose as it is widely used in:

- Web Development

- Software Development

- Scripting

- Networking

- IOT and lot more
  It is dynamically typed, we do not need to specify types in source code, the type is automatically decided by python interpreter during run time.
  With these advantages, it's simplicity and beginner friendly syntax, it is popular these days.
  
  ## Code execution
  
  ### What we see?
  
  Source code -> interpreter -> execution
  
  ### What actually happens?
  
  ![python code execution](https://procodeguide.b-cdn.net/wp-content/uploads/2021/07/Python-Execution-Model-1024x576.png)
  Source: [procodeguide](https://procodeguide.com/python-tutorials/python-programming/)

## Print Statement

- Prints the provided string in terminal

```python
print("Hello World")
```

See variable declaration first

### Formated Printing

```python
username = "Nishant"
print(f"My name is: {username}")

# Output: My name is: Nishant
```

### Escape Characters

Escape characters are those characters which alters the character sequence, for example: when you add `\` (backslash) in string followed by some characters like `n``t`, etc. It behaves different than usual. This is because `\` denotes start of escape sequence. For example: adding `\n` will add a new line and prints anything after it in that new line.

```python
"""
\n is a escape sequence which adds new line
"""

print("Hello everyone,\ngoing good?")


"""Output:
Hello everyone,
going good?
"""
```

### Escaping escape characters

We can insert and use backslash by adding double backslash like

```python
print("Hello everyone,\\ngoing good?")

#Output: Hello everyone,\ngoing good?
```

We can print string, ignoring escape sequence (raw) by adding r before string like:

```python
print(r"Hello everyone,\n going good?")

# Output: Hello everyone,\n going good?
```

## Variable declaration

`variable_name = value`

```python
username = "Nishant"
```

`Note: We do not need to add type, it is automatically added by interpreter during run time.`e

## Arithmetic Operations

The arithmetic operations should be done in between same types ( will learn about types later ), however multipying string and number repeats the string.

- Addition

```python
x = 2
y = 3
z = x + y
print(z)
# Output: 5
```

- floor division

```python
x = 5
y = 2
z = x // y
print(z)
# Output: 2
```

`There are other operations too: Subtraction (-), multiplication (*), division (/), exponentiation (**), modular division (%).`

## Help Method

In python terminal, we can get help of different methods by typing `help(method_name)`

```bash
import math
help(math.pow)
```
