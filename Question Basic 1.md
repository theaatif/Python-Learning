## Q1. Sum of Numbers from 1 to N

🎯 Concept: Loops + range()

📝 Problem:  
Ask the user for a number N. Then calculate and print the sum of all numbers from 1 to N.

🧠 For example:  
If N = 5 → 1 + 2 + 3 + 4 + 5 = 15

```python
num = int(input(""))

sum = 0
for i in range(1,num+1):
	sum = sum + i
print(sum)

```

