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
#write a python ptogram to find the square root for the given number(newton's method)using function.
#Developedn by: Santhosh L
#reg no: 212222100046
def sq(number,number_item=100):
    a=float(number)
    for i in range(number_item):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",sq(a))
```

## Output:
![Screenshot (4)](https://github.com/sandy29l/Square-root-of-a-number/assets/123359969/b600e66b-d6fd-4711-9ea6-1f3c256e4a40)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
