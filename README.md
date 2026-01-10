# Python-Fundamentals

Beginner‑friendly Jupyter notebooks covering core Python concepts through short explanations and executable examples.

***

## Overview

This repository introduces fundamental Python syntax and features using simple, progressively more complex code snippets.

***

## Contents

- Print function and case sensitivity  
- Core data types and `type()`  
- Arithmetic, comparison, logical, and assignment operators  
- Typecasting between `int`, `float`, `bool`, and `str`  
- Conditional statements (`if`, `elif`, `else`)  
- `for` loops and `range()`  
- Small programming exercises (divisibility checks, tables, sums)  
- Probability examples with dice using nested loops  
- Data structures: lists, 2D lists (matrices), prime number generation  
- Diagonal traversal and sums in matrices  
- Dictionaries and nested dictionaries for student data  
- `input()`‑driven mini applications (building dictionaries from user input)

***

## Module Breakdown

### Basics and Data Types

- Demonstrates `print()` with integers, floats, and booleans and shows that Python is case sensitive (e.g., `True` vs `true`).
- Introduces four fundamental data types (**int**, float, bool, string) and the `type()` function to inspect them.

### Operators and Variables

- Shows arithmetic operators (`+`, `-`, `*`, `/`, `//`, `%`, `**`) including behavior with booleans and strings.
- Explains comparison operators (`==`, `!=`, `>`, `<`, `>=`, `<=`) and logical operators (`and`, `or`, `not`) with numeric and boolean operands.
- Uses simple variables (`a`, `b`) to show assignment, re‑assignment, augmented assignment (`+=`, etc.), and deletion via `del`.
- Covers explicit conversions among `int`, `float`, `bool`, and `str`, including examples that raise errors (e.g., `int('3.5')`).

### Conditionals and Small Problems

- Uses `if`/`elif`/`else` to build small programs: voting eligibility, divisibility by 5 and 7, and multi‑branch divisibility logic.
- Includes variants showing why conditions must accompany both `if` and `elif`, and the difference between chained `if`/`elif` and separate `if` blocks.

### For Loop

- Introduces `for` loops with `range()` for counting up, counting down, and generating multiplication tables (e.g., table of 13).
- Includes examples computing the sum of the first \(n\) numbers and iterating over nested ranges to explore dice outcomes.
- Uses nested `for` loops to enumerate outcomes when rolling two or three dice and to compute probabilities of specific sums.
- Generalizes to print the probability distribution of all possible sums for three dice from 3 to 18.

### Lists

- Introduces Python lists with mixed data types, list creation via `append`, and iterating using indices and `len()`.
- Builds lists based on conditions (e.g., numbers between 1–1000 divisible by 5 and 7 and even) and generates prime numbers up to 1000.
- Works with 2D lists as matrices: printing all elements, a specific row, and diagonal elements in both directions.
- Prints main and anti‑diagonal elements using index relations `i == j` and `i + j == n - 1`.
- Computes the sum of both diagonals and handles double‑counting of the center element in odd‑sized matrices.

### Dictionaries and Nested Data

- Introduces dictionaries with integer keys and string values, adding entries, and inspecting `len()`, `.keys()`, and `.values()`.
- Uses nested dictionaries to store student records (name, phone, address, subject marks) and computes total and average marks per student.
- Demonstrates `input()` for reading user data and building a roll‑number‑to‑name dictionary interactively.
- Extends student dictionaries to include computed averages, illustrating how to enrich nested structures programmatically.

***

## Usage

- Open the notebooks in Jupyter, VS Code, or Google Colab to execute the examples cell by cell.
- Use it as a **teaching** companion (projected during class) or as self‑study notes by editing and extending the given exercises.
