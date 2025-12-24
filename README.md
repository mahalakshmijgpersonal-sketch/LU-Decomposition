# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Use import numpy
2. Use lu decomposition
3. Find the L value
4. find the U value
 


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MAHALAKSHMI J
RegisterNumber: 25008001

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MAHALAKSHMI J
RegisterNumber: 25008001
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
 
*/
```

## Output:
<img width="998" height="796" alt="Screenshot 2025-12-24 082332" src="https://github.com/user-attachments/assets/d271886a-ad55-4d49-a3a6-3b083ea2aee5" />
<img width="732" height="552" alt="Screenshot 2025-12-24 082354" src="https://github.com/user-attachments/assets/27bb9616-d5a5-4542-8345-d77671b54959" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

