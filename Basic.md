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
