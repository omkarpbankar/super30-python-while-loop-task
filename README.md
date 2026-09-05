# Super30 Python While Loop Task

## Overview

This repository demonstrates condition-controlled iteration with Python `while` loops. The notebook is designed for the Super30 assignment and focuses on situations where the number of repetitions is not known in advance.

## Topics Covered

- Print numbers from 1 to 100.
- Print numbers from 100 to 1.
- Print even numbers from 1 to 100.
- Sum the digits of an integer, including the example `5832 -> 18`.
- Reverse an integer, including the example `12345 -> 54321`.
- Count the digits in an integer.
- Calculate factorial with `while`.
- Sum user-entered numbers until the sentinel value `0`.
- Repeatedly check a password until it is correct.
- Run a guessing game until the secret number is guessed.
- Use a menu-driven calculator with Add, Subtract, Multiply, Divide, and Exit.
- Use an ATM menu with balance, deposit, withdrawal, and Exit options.

## Files

- `while_loop_task.ipynb`: Runnable explanations and Python solutions.
- `README.md`: Assignment overview and topic summary.

## Running the Notebook

1. Open `while_loop_task.ipynb` in VS Code or Jupyter.
2. Select a Python 3 kernel.
3. Run the non-interactive cells to see the examples.
4. Uncomment one interactive function call at a time when you want to enter values manually.

The calculator demo runs automatically with scripted choices so the notebook does not block waiting for input. The complete interactive calculator and ATM programs are included directly above their commented function calls.

## Why `while`?

A `for` loop is best when iterating over a known sequence or fixed range. A `while` loop is preferable for the sentinel, password, guessing-game, calculator, and ATM programs because each loop continues until a condition changes: the user enters `0`, enters the correct password, guesses correctly, or selects Exit. The number of iterations is therefore unknown ahead of time.

## Loop Safety

Every major loop identifies its initialization, condition, and update or termination path. Input-driven loops have explicit sentinel values or Exit choices, which prevents accidental infinite loops.

## Submission Checklist

- [x] GitHub repository named `super30-python-while-loop-task`
- [x] Jupyter notebook included
- [x] README overview and topic coverage included
- [x] Major `while` loops document initialization, condition, and update/termination
- [x] Calculator and ATM implementations included
- [x] Explanation of why `while` is preferable to `for` included
