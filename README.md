# Planet Logic Validator
A Python class implementation that practices Object-Oriented Programming (OOP) and data validation.

## Features
- Custom error handling using `TypeError` and `ValueError`.
- String formatting with f-strings.
- Method implementation for object behavior (`orbit`).

## How to use
```python
from planet import Planet
earth = Planet("Earth", "terrestrial", "Sun")
print(earth.orbit())
