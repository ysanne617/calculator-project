# Calculator Project
A simple calculator project implemented in Python.

## Installation
```bash
git clone https://github.com/ysanne617/calculator-project.git
cd calculator-project
uv sync
```
## Usage
```python
from calculator import Calculator 
calc = Calculator()
print(calc.add(2, 3))  # Output: 5
print(calc.subtract(5, 2))  # Output: 3
```
## Tests
To run the tests, use the following command:
```bash
pytest tests
```