# Week 6 Assignment - Safe Functions

## Files

* `safe_tools.py` - Contains three safe functions that use try/except to handle errors without crashing the program.
* `README.md` - Describes the assignment and explains why an if statement cannot catch invalid number conversion by itself.

## Why can't an if check catch "abc" on its own?

An `if` statement can check a condition, but converting `"abc"` to an integer with `int()` causes a `ValueError`. The conversion must be attempted first, and `try/except` catches the error when the conversion fails.

## Concepts Practiced

This assignment demonstrates:

* `try` and `except`
* `ZeroDivisionError`
* `ValueError`
* `KeyError`
* Returning values from functions
* Handling errors without crashing the program
