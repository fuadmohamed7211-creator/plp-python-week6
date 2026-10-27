# PLP Python Week 6 Assignment

## Files Included
* **safe_tools.py**: Contains robust functions utilizing try/except error handling to manage exceptions smoothly without crashing.

## Reflection Question
* **Why can the if check not catch "abc" on its own?** 
An `if` check evaluates a condition on data that is already running inside the program. When Python attempts to parse or evaluate incompatible data types (like passing a string like `"abc"` into an integer conversion function or looking up a non-existent dictionary key), the program crashes with an unhandled exception before an `if` statement can even evaluate it. Try/except blocks are required to safely intercept these runtime exceptions.