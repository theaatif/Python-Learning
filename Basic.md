 https://chatgpt.com/share/686a68ce-cf5c-800c-9bac-5e1b4e76004a
#### Hello Python! new vault Final
```python
print("Hello, Python!")  # like console.log in JS
```
> - **Key Point**: No semicolons, indentation is structure!

#### Variables & Data Types
```python
# JS: let x = 5;   --> Python:
x = 5          # int
pi = 3.14      # float
name = "Aatif" # str
is_happy = True  # bool
```
> Tip: No need to declare types (Python is dynamically typed)

#### User Input
```python
name = input("Enter your name: ")
print("Welcome,", name)

```
>`input()` always gives string → convert if needed:

```python
age = int(input("Enter your age: "))
```

####  Comments & Indentation

```python
# This is a comment
'''
 this is multiline comment
'''

if True:
    print("This is inside if")  # 4 space/tab indent

```


## Range in Python

###  Syntax:

```python
range(start, stop, step)
```

- `start`: (optional) number to start from (default is `0`)
    
- `stop`: (required) number to stop **before**
    
- `step`: (optional) difference between numbers (default is `1`)

 
 ### Common Examples:

#### 1. `range(stop)` – starts from 0

```python
for i in range(5):
    print(i)
```

🔸 Output: `0 1 2 3 4`

#### 2. `range(start, stop)`

```python
for i in range(1, 6):
    print(i)
```

🔸 Output: `1 2 3 4 5`

#### 3. `range(start, stop, step)`

```python
for i in range(2, 10, 2):
    print(i)
```

🔸 Output: `2 4 6 8`

#### 4. Reverse range

```python
for i in range(5, 0, -1):
    print(i)
```

🔸 Output: `5 4 3 2 1`

###  Convert range to list

```python
list(range(3, 8))
# Output: [3, 4, 5, 6, 7]
```

# Operators

### 1️⃣ Arithmetic Operators

Used for basic math (same as JavaScript):

|Operator|Meaning|Example|Output|
|---|---|---|---|
|+|Addition|2 + 3|5|
|-|Subtraction|5 - 2|3|
|*|Multiplication|4 * 3|12|
|/|Division|10 / 2|5.0|
|//|Floor Division|10 // 3|3|
|%|Modulus (remainder)|10 % 3|1|
|**|Exponentiation|2 ** 3|8|

> Tip:

>- `//` is like `Math.floor()` after division.
    
>- `/` always returns float (even if exact).
    

### 2️⃣ Comparison Operators

Used to compare values — returns True or False

|Operator|Meaning|Example|
|---|---|---|
|==|Equal to|5 == 5 → True|
|!=|Not equal to|5 != 3 → True|
|>|Greater than|7 > 5 → True|
|<|Less than|4 < 6 → True|
|>=|Greater or equal|5 >= 5 → True|
|<=|Less or equal|3 <= 4 → True|

### 3️⃣ Assignment Operators

Used to assign values to variables

|Operator|Meaning|Example|Same as|
|---|---|---|---|
|=|Assign value|x = 10|—|
|+=|Add and assign|x += 2 → x = x+2||
|-=|Subtract|x -= 3||
|*=|Multiply|x *= 4||
|/=|Divide|x /= 2||

### 4️⃣ Logical Operators

Used in conditions

|Operator|Meaning|Example|
|---|---|---|
|and|True if both are True|5 > 3 and 4 > 1 → True|
|or|True if any is True|5 < 3 or 4 > 1 → True|
|not|Reverses True/False|not True → False|

> JS equivalent: &&, ||, !


### 5️⃣ Membership Operators (🚀 Python Special)

|Operator|Meaning|Example|
|---|---|---|
|in|Exists in sequence|"a" in "apple" → True|
|not in|Doesn’t exist|3 not in [1,2,4] → True|

### 6️⃣ Identity Operators

|Operator|Meaning|Example|
|---|---|---|
|is|Same object in memory|a is b|
|is not|Not the same object|a is not b|



