 What is a Set in Python?

A set is:

- An unordered collection of unique elements.
    
- No duplicates allowed.
    
- Like a “bag” where the order doesn't matter.
    

> In JavaScript, it's kind of like new Set([1,2,3]).


##  How to Create a Set

```python
# Create a set
my_set = {1, 2, 3, 4}
print(my_set)  # Output: {1, 2, 3, 4}
```

 Notice:

> No duplicates allowed → `{1, 2, 2, 3}` becomes `{1, 2, 3}`
    

```python
nums = {1, 2, 2, 3, 3, 4}
print(nums)  # Output: {1, 2, 3, 4}
```


##  Adding and Removing Elements

```python
my_set = {1, 2}
my_set.add(3)
print(my_set)  # {1, 2, 3}

my_set.remove(2)
print(my_set)  # {1, 3}
```

>remove() will give an error if item not found  
✅ safer: use discard()

```python
my_set.discard(10)  # no error even if 10 is not in the set
```

##  Set Operations (like Venn Diagram!)

|Operation|Python Code|Example|
|---|---|---|
|Union|set1.union(set2)|All unique from both|
|Intersection|set1.intersection(set2)|Common items|
|Difference|set1.difference(set2)|Items only in set1|

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))        # {1, 2, 3, 4, 5}
print(a.intersection(b)) # {3}
print(a.difference(b))   # {1, 2}
```
##  Useful Set Methods

| Method     | Description                          |     |
| ---------- | ------------------------------------ | --- |
| add(x)     | Adds x to the set                    |     |
| remove(x)  | Removes x (error if not present)     |     |
| discard(x) | Removes x (no error if missing)      |     |
| clear()    | Empties the set                      |     |
| copy()     | Returns a shallow copy               |     |
| pop()      | Removes and returns a random element |     |

##  Why Use Sets?

✅ Fast lookups (like checking if a value exists)  
✅ Removes duplicates automatically  
✅ Great for comparisons (is A in B?)

---

##  Tiny Practice

Try this:

```python
# 1. Remove duplicates from this list using set
nums = [1, 2, 2, 3, 4, 4, 5]
unique_nums = set(nums)
print(unique_nums)

# 2. Find common elements in two lists
a = set([1, 2, 3, 4])
b = set([3, 4, 5, 6])
print(a.intersection(b))
```

---

Want a short quiz + real-world example using sets (like detecting duplicates or email overlaps)? Just say “Give me quiz & project example”.