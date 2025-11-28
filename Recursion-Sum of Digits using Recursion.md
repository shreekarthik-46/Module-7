# 7)c) Recursion:Sum of Digits using Recursion in Python

##  AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

##  ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

##  PROGRAM:
```
ef sum_digits(n):
   
    if n == 0:
        return 0
    return (n % 10) + sum_digits(n // 10)

num = int(input())

print(sum_digits(num))
```

## OUTPUT

![sum recur](https://github.com/user-attachments/assets/6db239ae-40fc-4d87-8406-dd724aa75f8d)

## RESULT
Thus a Python program to calculate the **sum of all digits** in a number using **recursion** is created.
