# Python Day 2

## Goals

- [ ] Taking input
- [ ] Data types in detail
- [ ] Conditional Statements
- [ ] Operators revision
- [ ] looping (for loop, while loop)
- [ ] iterables
- [ ] Some questions..

## Taking input

### Syntax

Uses python's builtin method `input([prompt_message: Optional])`

```python
x = input("Enter your name: ")
```

### Type casting input

```python
x = float(input("enter float: "))
y = int(input("Enter int:"))
z = input("Enter list of numbers").split(" ")
a = bool(input("You're happy: "))
print(type(x))
print(type(y))
print(type(z))
print(type(a))
```

### Data types

numbers, string, list, tuple, set, dictionary, complex, bytes

### Loops

must be iterables..

```python
for i in range(10):
    print(i)
```

```python
x = ["Rushal", "Dilip", "Swastika", "Shreeya", "Shashwot", "Riya"]
for i in x:
    print(i)
```
