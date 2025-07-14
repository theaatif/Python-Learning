
- `if`, `elif`, `else` (JS: `if`, `else if`, `else`)
    
- Loops: `for`, `while`
    
- Practical logic: even/odd, grade checker, counter
    
#### 2.1 If-Else

```python
age = int(input("Enter your age: "))

if age >= 18:
    print("Adult")
elif age >= 13:
    print("Teenager")
else:
    print("Child")
```
#### 2.2 Loops

##### `for` loop (range-based)

```python
for i in range(5):
    print(i)
```

> Similar to `for(let i = 0; i < 5; i++)`

##### `while` loop

```python
count = 0
while count < 5:
    print(count)
    count += 1
```

#### 2.3 Break & Continue

```python
for i in range(5):
    if i == 3:
        break
    print(i)

for i in range(5):
    if i == 3:
        continue
    print(i)
```
