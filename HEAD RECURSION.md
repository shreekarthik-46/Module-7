# 7)a) Types of Recursion: Head Recursion in Python

##  AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

##  ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

##  PROGRAM:
```
def result(n,i):
    if (i>n):
        return
    print(i,end=" ")
    result(n,i+1)
 

n = int(input())
i=1
result(n,i)
```



## OUTPUT

![head ](https://github.com/user-attachments/assets/ef8e7256-b2db-4b33-b489-9182c9c0d955)


## RESULT
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

