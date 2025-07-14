In JavaScript, you used arrays like:

```javascript
let arr = [1, 2, 3];
```

In Python, it's:

```python
my_list = [1, 2, 3]
```
##  1. Creating a List

```python
fruits = ["apple", "banana", "cherry"]
numbers = [1, 2, 3, 4, 5]
mixed = [1, "hello", True, 3.14]
```

> Python lists can hold any type, even mixed types!

##  2. Accessing Elements

Lists use index numbers starting from 0:

```python
print(fruits[0])   # apple
print(fruits[1])   # banana
```

> Negative indexing also works:

```python
print(fruits[-1])  # cherry (last item)
```

##  3. Modifying Lists

Change values:

```python
fruits[1] = "mango"
print(fruits)  # ['apple', 'mango', 'cherry']
```

##  4. List Functions & Methods

|Task|Code Example|
|---|---|
|Add to end|fruits.append("orange")|
|Insert at position|fruits.insert(1, "grapes")|
|Remove by value|fruits.remove("apple")|
|Remove last item|fruits.pop()|
|Check existence|"banana" in fruits|
|Length|len(fruits)|
|Sort|fruits.sort()|
|Reverse|fruits.reverse()|

##  5. Looping Through a List

```python
for fruit in fruits:
    print(fruit)
```

You can also use index-based loop:

```python
for i in range(len(fruits)):
    print(fruits[i])
```

##  6. Slicing Lists

```python
nums = [10, 20, 30, 40, 50]
print(nums[1:4])   # [20, 30, 40]
print(nums[:3])    # [10, 20, 30]
print(nums[-2:])   # [40, 50]
```

##### Example 
```python
nums = [10, 20, 30, 40, 50]

print(nums[2:]) #Starts from index 2 (which is 30) Goes till the end -> #[30, 40, 50] 


print(nums[:2]) #Starts from beginning (index 0) Stops just before index 2 -> #[10, 20] 
```

## 7.  List Comprehension (bonus – advanced)

Fast way to build a list:

```python
squares = [x**2 for x in range(5)]
print(squares)  # [0, 1, 4, 9, 16]
```

---

```python
list2 = list("Aatif")
print(list2) #['A', 'a', 't', 'i', 'f']

```
