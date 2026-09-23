# Atomation_python_practice
# Name : KESAVAN S
# Reg No : 212223060125


# 1. Binary numbers divisible by 5

```python
x = input().split(",")

for i in x:
    decimal = 0

    for j in i:
        decimal = decimal * 2 + int(j)

    if decimal % 5 == 0:
        print(i, end=" ")
```

# 2. Count letters and digits

```python
x = input()

alpCount = 0
digCount = 0

for i in x:
    if i.isalpha():
        alpCount += 1
    elif i.isdigit():
        digCount += 1

print("LETTERS :", alpCount)
print("DIGITS :", digCount)
```

# 3. Factorial of a number

```python
n = int(input())

fact = 1

for i in range(1, n + 1):
    fact = fact * i

print(fact)
```
