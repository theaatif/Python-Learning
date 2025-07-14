

## 💡 What is a String?

A string is just text inside quotes.

```python
name = "Aatif"
greeting = 'Hello'
```

✅ You can use either single (' ') or double (" ") quotes.

## 🔹 1. Basic String Operations

```python
name = "Aatif"

print(len(name))         # 5 → length
print(name[0])           # 'A' → first character
print(name[-1])          # 'f' → last character
print(name.upper())      # 'AATIF'
print(name.lower())      # 'aatif'
```

## 🔹 2. String Slicing

Like lists, you can slice strings too:

```python
word = "Python"

print(word[0:2])   # 'Py' → from index 0 up to (not including) 2
print(word[:3])    # 'Pyt' → from start to index 3
print(word[3:])    # 'hon' → from index 3 to end
```

## 🔹 3. String Methods

|Method|Example|Result|
|---|---|---|
|upper()|"hi".upper()|"HI"|
|lower()|"HELLO".lower()|"hello"|
|strip()|" hello ".strip()|"hello" (removes spaces)|
|replace()|"a b c".replace(" ", "-")|"a-b-c"|
|split()|"a,b,c".split(",")|['a', 'b', 'c'] (list)|
|join()|"-".join(["a", "b", "c"])|"a-b-c"|
|find()|"hello".find("e")|1 (index)|
|in|"a" in "banana"|True|
## 🔹 4. String Formatting (f-strings)

```python
name = "Aatif"
age = 21

print(f"My name is {name} and I am {age} years old.")
```

🧠 f-strings = Easy way to combine variables into strings!

## 🔹 5. Looping Through a String

```python
for char in "Aatif":
    print(char)
```

