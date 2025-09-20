# SarthakFraction

A human-friendly Python package to handle fractions in a natural and simple way.  
Supports creating fractions from strings (like `"4/5"` or `"8"`) and performing arithmetic operations.

---

## ✨ Features

- Create fractions easily from strings: `"4/5"`, `"8"`, `"15/3"`.
- Perform arithmetic with intuitive operators:
  - `+` addition
  - `-` subtraction
  - `*` multiplication
  - `/` division
- Results are always simplified (e.g., `"10/20"` → `"1/2"`).
- Human-friendly string output.

---

## 📦 Installation

Install directly from PyPI:

```bash
pip install SarthakFraction
Usage
# Import the Fraction class
from SarthakFraction.Fraction import Fraction

# Create fractions from strings
f1 = Fraction("4/5")
f2 = Fraction("3/5")
f3 = Fraction("8")   # whole numbers are also supported

# Arithmetic
print(f1 + f2)   # 7/5
print(f1 - f2)   # 1/5
print(f1 * f2)   # 12/25
print(f1 / f2)   # 4/3

# Whole numbers are displayed with denominator = 1
print(f3)        # 8/1


⚠️ Important: All inputs must be provided as strings, like "4/5" or "8".

📖 Future Plans

Add a built-in help() function for the module that prints a detailed user manual
(covering usage examples, supported operations, and limitations).

📜 License

This project is licensed under the MIT License — see the LICENSE
 file for details.



