# 7)b)  Recursion: Python program for differnece of two factorial using recursion in Python

##  AIM:
To write a Python program to find the result of a! - b! using recursion

---

##  ALGORITHM:

1. **Start**
2. Define a recursive function `factorial(n)
   - **Base Case:** If the the given number is 0 returns `1`
   - **Recursive Case:** If the given number is other than zero find the factorial of it and  return `n*factorial(n-1)`
3. Get  two input from the user
4. Call the recursive function for the two inputs and find the differnece
5. Store it in a varaible and print the output
6. **Stop**

---

##  PROGRAM:
```
def factorial(n):
    if(n==0):
        return 1
    return(n*factorial(n-1))
    
a=int(input())
b=int(input())
sum=factorial(a)-factorial(b)
print(sum)
```

## OUTPUT
![fact of 2](https://github.com/user-attachments/assets/595fef5d-5ec3-4dfa-8209-8b4582b8cd30)


## RESULT
Thus a Python program to find the result of a! - b! using recursion is cretaed.


