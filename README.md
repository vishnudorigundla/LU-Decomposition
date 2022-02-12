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

## Program:-
program1 :-
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
program 2 :-
~~~
'''Program to solve a matrix using LU decomposition.
Developed by: D.vishnuvardhan reddy
RegisterNumber: 21005311
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = eval(input())
b = eval(input())
lu,piv = lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)

~~~

## Output:
![OUTPUT](/IMAGES/lu.png)
![OUTPUT](/IMAGES/lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

