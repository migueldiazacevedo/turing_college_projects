# Calculator Module

A simple Python class for performing basic arithmetic operations. This `Calculator` class allows you to perform addition, subtraction, multiplication, division, and nth root calculations.

see more details at https://github.com/migueldiazacevedo/turing_college_projects/tree/main/module1-sprint1
see package details at: https://test.pypi.org/project/calculator-pkg-MAD/

## Installation

You can use the `Calculator` class by importing it into your Python project. Here's how you can do it:

$ pip install -i https://test.pypi.org/simple/ calculator-pkg-MAD==0.1.0

```python
from calculator_pkg_MAD.calculator import Calculator

# Create an instance of the Calculator
calculator = Calculator()
```
## Usage 

### Initializing a calculator
You can create a Calculator instance and initialize it with an optional initial value.
```python
# Create a Calculator with an initial value of 10
calculator = Calculator(10)
```

### Performing Calculations
The `Calculator` class provides the following methods for performing calculations:

- `add(*args: float)`: Add numbers together.
- `subtract(*args: float)`: Subtract numbers from one another.
- `multiply(*args: float)`: Multiply numbers together.
- `divide(*args: float)`: Divide numbers.
- `n_root(nth_root: int)`: Take the nth root of a number.

Example Usage

```python
# Create a calculator instance
calculator = Calculator()

# Perform calculations
calculator.add(5, 3)  # Adds 5 and 3, result: 8.0
calculator.subtract(10, 2)  # Subtracts 2 from the current value, result: 6.0
calculator.multiply(4, 2)  # Multiplies by 2, result: 12.0
calculator.divide(6, 2)  # Divides by 2, result: 6.0
calculator.n_root(2)  # Takes the square root, result: 2.449489742783178
```
### Controlling Output
The `Calculator` class allows you to control whether the value is printed to the console or not using the `hide_print` attribute.
### Exception Handling 
The `Calculator` class raises a `ValueError` when attempting to divide by zero.

### License 
This code is released under the [MIT License](https://opensource.org/license/mit/) 

