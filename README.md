# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm : LU Decomposition
###
5.a
###
Step 1. Start the program and import the required python libraries
###
Step 2. Read the input matrix and initialize L and U
###
Step 3. Calculate the L and U matrices using the decomposition method
###
Step 4. Display the L and U matrices and stop the program
###
5.b
###
Step 1. Start the program and import the required python libraries
###
Step 2. Read the input matrix and initialize L and U
###
Step 3. Calculate the L and U matrices using the decomposition method
###
Step 4. Display the L and U matrices and stop the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Mariya Asna
RegisterNumber: 26018761
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
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
Developed by: Mariya Asna
RegisterNumber: 26018761
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:
![lu decomposition]()
5.a
<img width="1097" height="792" alt="Screenshot 2026-10-14 095049" src="https://github.com/user-attachments/assets/03d7a964-990a-4761-a5b1-7c0b7f201ef1" />
5.b
<img width="1027" height="661" alt="Screenshot 2026-10-14 095121" src="https://github.com/user-attachments/assets/b2b37bf3-423d-4877-a808-75780d3ce54b" />







## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

