
##  What is a Tuple?

A tuple is just like a list, but:

- ✅ Ordered
    
- ✅ Allows duplicates
    
- ❌ Cannot be changed (immutable)
    

Think of it like a box of items you can't change once packed.

##  1. Creating a Tuple

```python
my_tuple = (10, 20, 30)
```

> Notice the parentheses () instead of square brackets []


##  2. Accessing Items (Same as List)

```python
print(my_tuple[0])  # 10
print(my_tuple[-1]) # 30
```

>You can use positive and negative indexing.

##  3. Why Use Tuples?

- You want to protect data from being changed.
    
- Tuples use less memory than lists → slightly faster.
    
- Good for fixed data like (latitude, longitude) or (name, age)
    

##  4. Tuple with One Item?

To create a single-item tuple, use a comma:

```python
x = (5)      # ❌ This is just a number!
y = (5,)     # ✅ This is a tuple with one item
```

##  5. Tuple Methods

Tuples are limited — only a few things you can do:

|Method|Example|Result|
|---|---|---|
|count()|my_tuple.count(10)|Count how many times 10 appears|
|index()|my_tuple.index(20)|Gives index of value 20|

##  6. Looping Through a Tuple

```python
for item in my_tuple:
    print(item)
```

