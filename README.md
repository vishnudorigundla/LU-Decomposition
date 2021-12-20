# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy and scipy.linalg
2. Take the input of the given matrix using eval
3. Calculate the values using the functions improved
4. print the required values.

## Program:
~~~
Program to find the LU Decomposition of a matrix.
Developed by:D.vishnu vardhan reddy 
RegisterNumber: 21005311.
<br/>
import numpy as np
from scipy.linalg import lu
A =eval (input())
P,L,U=lu(A)
print(L)
print(U)
~~~

## Output:
![OUTPUT](/IMAGES/lu.png)
![OUTPUT](/IMAGES/lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

