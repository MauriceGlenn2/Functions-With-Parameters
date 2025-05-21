# Functions-With-Parameters

## Overview

In this exercise, I learned how to use **functions with inputs** in Python. This included defining functions that accept **parameters**, and then calling those functions with **arguments**. Understanding how to pass data into functions is essential for creating reusable and modular code.

---

## What I Learned

### ✅ Functions with One Parameter

I started with a simple function that takes a single parameter (like a name or age). This helped me understand how to pass one piece of information into a function and use it inside the function body.

#### Example:
```python
def greet_with_name(name):
    print(f"Hello {name}")
    print(f"What's up {name}")

greet_with_name("Moe")
```


### ✅ Defining a Function with Two Parameters

I created a function called `greet_with()` that accepts two parameters: `name` and `location`. These are used to print a personalized greeting based on the inputs provided.

#### Example:
```python
def greet_with(name, location):
    print(f"Hello {name}")
    print(f"What's it like in {location}")
# greet_with("Amanda", "Mars")
greet_with(location="mars", name="Amanda")
