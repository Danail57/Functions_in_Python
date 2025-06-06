# Functions_in_Python

# Python Functions Guide

This README provides an introduction to **functions in Python** — how to define, call, and use them effectively.

---

## What is a Function?

A **function** is a reusable block of code that performs a specific task.

### Syntax:
```python
def function_name(parameters):
    # code block
    return result

**Example**

def rectangle_area(width, height):
    return area

width = int(input())
height = int(input())

area = width * height
rectangle_area(width, height)

print(area)
