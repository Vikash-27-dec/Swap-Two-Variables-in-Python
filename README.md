# Swap-Two-Variables-in-Python
# Swap Two Variables in Python 🌀

This repository contains a simple Python program to swap the values of two variables. This is a fundamental concept in Python programming, useful for beginners to understand variable manipulation.

## 🔧 What’s Inside?

The script demonstrates:

- Swapping variables using a temporary third variable
- Swapping variables without using a third variable (using Python’s tuple unpacking)

## 📌 Code Example

```python
# Using a temporary variable
a = 5
b = 10
temp = a
a = b
b = temp
print("After swapping: a =", a, "b =", b)

# Without using a temporary variable
x = 20
y = 30
x, y = y, x
print("After swapping: x =", x, "y =", y)

