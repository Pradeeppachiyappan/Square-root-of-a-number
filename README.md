# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: pradeeep raj p
RegisterNumber: 212222240073 
*/
def square(n):
    x=n
    b=1
    for i in range(20):
        b=0.5*(b+x/b)
    return b
n=int(input())
sq=square(n)
print("Square root of the number:",sq)
```
## Output:
![Screenshot (61)](https://user-images.githubusercontent.com/118707347/235421022-8e759a68-6024-40bd-9b5e-3ba32102b29f.png)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
