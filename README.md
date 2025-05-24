# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM:
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## PROGRAM:
```
#Program to find the square root for the given number(newton's method) using function.
#Developed by :Daksha Subbaian
#Register Number:212223230036
n=int(input())
app=0.5*n
for i in range(1,10):
    b=0.5*(app+(n/app))
    app=b
print("Square root of the number:",app)
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/12cbec57-a779-4d69-85c9-2feb2a2163c7)




## RESULT:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
