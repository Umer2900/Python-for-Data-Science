# Python for Data Science - Day 1 Tutorial

## Overview
This repository contains a tutorial document titled **"Day 1 - Python for Data Science"**, prepared by Mohammad Umer. The tutorial introduces fundamental Python concepts essential for data science, including basic syntax, data types, variables, type conversion, and keywords. The content is structured as a series of notes and Python code examples, extracted from a provided PDF document.

## Contents
The tutorial is organized into the following sections, each covering a key aspect of Python programming:

1. **Print Function**  
   - Demonstrates how to use the `print()` function to display text, including handling multi-line strings (e.g., printing a poem).
   - Highlights common errors, such as `SyntaxError` due to unterminated string literals, and provides correct syntax examples.

2. **Data Types**  
   - Explains the concept of data types in Python and how to check them using the `type()` function.
   - Covers basic (primitive) data types:  
     - `int`: Integer numbers (e.g., 29, -23)
     - `float`: Floating-point numbers (e.g., 2.5, -0.001)
     - `str`: Strings (e.g., "hello", "Python")
     - `bool`: Boolean values (`True`, `False`)
   - Includes examples to verify data types and check if an object is an instance of a specific type using `isinstance()`.

3. **Type Conversion**  
   - Introduces type conversion (e.g., converting a `float` to an `int`).
   - Provides examples to illustrate the process and verify the resulting data type.

4. **Variables**  
   - Explains variables as reserved memory locations for storing data.
   - Covers variable naming conventions and rules:  
     - Names cannot be Python keywords.
     - Names must be descriptive and start with a letter or underscore (`_`).
     - Names can include letters, numbers, and underscores but are case-sensitive.
     - Invalid examples (e.g., `2age`, `@name`) are shown to clarify common mistakes.

5. **Random Values and Case Sensitivity**  
   - Demonstrates generating random numbers using the `random.randint()` function.
   - Highlights Python’s case sensitivity with examples showing how `name` and `Name` are treated as distinct variables.

6. **Keywords**  
   - Lists Python’s reserved keywords using the `keyword.kwlist` module.
   - Explains that keywords cannot be used as variable names (identifiers).
   - Includes examples of errors caused by attempting to use keywords as identifiers (e.g., `try = 29`).

## Prerequisites
- Basic understanding of programming concepts.
- Python 3.x installed on your system.
- Familiarity with running Python code in an interactive environment (e.g., Jupyter Notebook, Python IDLE).
