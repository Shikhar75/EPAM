# Python Data Structures and Functions

## Introduction

Python provides built-in ways to organise information and reuse instructions. Lists, tuples, dictionaries, and functions are useful building blocks for writing clear programs.

## Important Concepts

### 1. Lists

A list stores multiple items in an ordered collection. Lists can be changed after creation.

```python
topics = ["Python", "AI", "Git"]
topics.append("Agents")
```

### 2. Tuples

A tuple also stores an ordered collection, but its items cannot be changed after it is created.

```python
coordinates = (10, 20)
```

### 3. Dictionaries

A dictionary stores information as key-value pairs.

```python
student = {
    "name": "Alex",
    "year": 2
}

print(student["name"])
```

### 4. Functions

A function is a reusable block of code that performs a task. It can accept inputs called parameters and can return a result.

```python
def greet(name):
    return "Hello, " + name

print(greet("Alex"))
```

### 5. Modules

A module is a Python file or library containing code that can be reused in another program.

```python
import math

print(math.sqrt(25))
```

## Practical Applications

- Lists can store a collection of learning topics.
- Dictionaries can represent a student's details.
- Functions can prevent the same instructions from being written repeatedly.
- Modules provide ready-made features for common tasks.

## My Understanding

Data structures help me organise information in different ways. Lists are flexible collections, tuples are fixed collections, and dictionaries connect keys to values. Functions and modules help me reuse code and keep programs organised.

## Self-Assessment

1. How is a list different from a tuple?
2. What is a key-value pair?
3. Why are functions useful?
4. What does the `return` statement do?
5. Why might I import a module?
