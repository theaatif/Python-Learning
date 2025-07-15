Sure. Here's a clean and focused explanation of Python functions using only Markdown format, no emojis or fluff.


# Python Functions — Complete Beginner Guide

## What is a Function?

A function is a block of reusable code that performs a specific task. It helps organize code, reduce repetition, and make programs easier to read and maintain.


## Defining a Function

Use the def keyword:

```python
def function_name():
    # block of code
    pass
```

Example:

```python
def greet():
    print("Hello from function")
```

---

## Calling a Function

Once defined, call it using its name followed by parentheses:

```python
greet()
```

---

## Function with Parameters

You can pass data to functions using parameters:

```python
def greet(name):
    print("Hello", name)

greet("Aatif")
```

---

## Function with Multiple Parameters

```python
def add(a, b):
    print("Sum is:", a + b)

add(5, 3)
```

---

## Return Statement

To return a result from a function:

```python
def square(n):
    return n * n

result = square(4)
print(result)  # Output: 16
```

---

## Default Parameters

You can assign default values to parameters:

```python
def greet(name="Guest"):
    print("Hello", name)

greet("Aatif")   # Hello Aatif
greet()          # Hello Guest
```

---

## Keyword Arguments

You can pass arguments using parameter names:

```python
def introduce(name, age):
    print(name, "is", age, "years old")

introduce(age=25, name="Aatif")
```

---

## Return vs Print

- print() shows output on screen.
    
- return sends value back to caller.
    

Example:

```python
def double(x):
    return x * 2

print(double(4))  # prints 8
```

---

## Variable Scope

Variables inside a function are local:

```python
x = 10

def show():
    x = 5
    print("Inside:", x)

show()
print("Outside:", x)
```

To change a global variable:

```python
x = 10

def change():
    global x
    x = 20

change()
print(x)  # 20
```

---

## Mini Practice Tasks

1. Define a function that adds two numbers and returns the result.
    
2. Define a function that checks if a number is even or odd.
    
3. Write a function that returns the factorial of a number.
    
4. Write a function that reverses a string.
    
	1. Write a function that counts vowels in a given string.
    

Let me know if you want step-by-step help on any of these.