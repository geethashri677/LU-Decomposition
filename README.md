<img width="1255" height="326" alt="Screenshot 2026-02-05 143521" src="https://github.com/user-attachments/assets/959010ef-fcf2-42d1-a95d-c98e29148323" /># LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:GEETHA SHRI.G 
RegisterNumber:212225220032 
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:GEETHA SHRI.G 
RegisterNumber:212225220032 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

```

## Output:
<img width="1258" height="567" alt="Screenshot 2026-02-05 143511" src="https://github.com/user-attachments/assets/d694d8d7-0727-415c-86dd-4c12c7a718e1" />

<img width="1255" height="326" alt="Screenshot 2026-02-05 143521" src="https://github.com/user-attachments/assets/79d844bb-b807-40e0-8824-8215b2635d6e" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

