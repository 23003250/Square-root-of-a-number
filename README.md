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
Developed by: MIDHUN S
RegisterNumber: 23003250 
*/
def square():
    num1=int(input())
    num2=0.5*num1
    for i in range(0,num1):
        num2=0.5*(num2+(num1/num2))
    print("Square root of the number:",num2)
square()
```

## Output:
![output](/Screenshot%202023-07-26%20201724.jpg)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
