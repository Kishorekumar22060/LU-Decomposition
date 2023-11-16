## EX5- LU Decomposition 
## Date-13.09.2023
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np.
2. from scipy.linalg import lu, lu_factor, lu_solve.
3. solve using scipy.linalg.lu(variable)
4. print the output.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: KISHORE KUMAR U
RegisterNumber: 23000800
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: KISHORE KUMAR U
RegisterNumber: 23000800
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![image](https://github.com/Kishorekumar22060/LU-Decomposition/assets/141472136/f0093575-8ac3-4a9b-8616-d2ce9c2772a4)
![image](https://github.com/Kishorekumar22060/LU-Decomposition/assets/141472136/c2af687a-a1cf-445c-9923-6c10e1fc1650)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

