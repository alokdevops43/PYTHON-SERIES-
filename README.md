# Python Learning Journey - Day 1

## Overview

This repository contains my Day 1 Python practice programs.

Today I learned the fundamentals of Python and created some small programs to understand how Python works.

## Topics Learned

* Printing output using `print()`
* Python comments
* Python modules
* Installing and using packages with `pip`
* Using external libraries
* Working with the `os` module
* Reading directory contents

---

## Files

### 1. `first.py`

A simple Python program that prints:

```python
print("Hello, World!")
```

Concept learned:

* Basic Python syntax
* Using the `print()` function

---

### 2. `module.py`

A program that uses the `pyjokes` package to print a random joke.

```python
import pyjokes

joke = pyjokes.get_joke()
print(joke)
```

Concepts learned:

* Importing modules
* Installing packages with `pip`
* Using external libraries
* Writing comments

Package used:

```bash
pip install pyjokes
```

---

### 3. `problem1.py`

Practice file containing multiple beginner exercises.

Exercises:

#### Twinkle Twinkle Little Star

Learned how to print multi-line text.

#### Text To Speech (Practice)

Used `pyttsx3`.

```python
import pyttsx3
```

Package:

```bash
pip install pyttsx3
```

#### Directory Content Viewer

Used Python's built-in `os` module.

```python
import os

path = input('/')

contents = os.listdir(path)

for item in contents:
    print(item)
```

Concepts learned:

* Taking user input
* Using built-in modules
* Accessing folders and files

---

## Day 1 Summary

Today I started my Python journey and learned the basics of:

* Print statements
* Comments
* Modules
* pip
* External libraries
* User input
* File system access

## Goal

Build a strong Python foundation before moving to:

* Variables
* Data Types
* Operators
* Conditional Statements
* Loops
* Functions
* Object-Oriented Programming

---

Author: ALOK Choudhary

Day: 1
