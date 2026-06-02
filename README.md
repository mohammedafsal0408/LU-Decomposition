# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the required libraries such as NumPy and SciPy.
2. Define the matrix using np.array() and store it in a variable.
3. Use the scipy.linalg.lu() function to perform LU Decomposition and obtain the lower triangular matrix (L), upper triangular matrix (U), and permutation matrix (P).
4. Display the matrices P, L, and U using the print() function.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MOHAMMED AFSAL S
RegisterNumber: 212225040247
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MOHAMMED AFSAL S
RegisterNumber: 212225040247
*/

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
B=np.array(eval(input()))
x=np.linalg.solve(A,B)
print(x)
```

## Output:
<img width="1165" height="440" alt="image" src="https://github.com/user-attachments/assets/b70b0ec8-fe14-4e4f-88a8-96e795f4d7aa" />

<img width="940" height="178" alt="image" src="https://github.com/user-attachments/assets/32217629-2876-4f79-9acb-62c84bb3b16a" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

