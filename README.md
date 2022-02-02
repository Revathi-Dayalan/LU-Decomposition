# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. calculate the elements of L and U
2. print elements of L and U
3. find v by solving LU=b by forward substittion
4. find x by solving ux= v by backward substitution
5. print arrary as the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:REATHI DAYALAN 
RegisterNumber: 
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```
import numpy as np
import scipy
from scipy.linalg import lu_factor,lu_solve
A=np.array (eval(input()))
B=np.array (eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

## Output:
![output](.//pic.png)
![output](.//pic1.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

