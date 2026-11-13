# Week 6 Assignment - Safe Tools

## Files Included
- **safe_tools.py**: Contains three error-handled functions (`safe_divide`, `safe_number`, and `get_field`) designed to prevent program crashes using `try`/`except` blocks.

## Assignment Question
*Why can an `if` check not catch `"abc"` on its own?*

An `if` check cannot easily anticipate every potential runtime formatting failure or type conversion error without duplicating complex parsing logic. When you attempt to convert an incompatible string like `"abc"` into an integer using `int()`, Python raises a `ValueError` at runtime rather than returning a boolean value, making `try/except` the proper mechanism for catching and managing conversion exceptions safely.# plp-python-week6
