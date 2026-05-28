# LU Decomposition 

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
1) import numpy as np
from scipy.linalg import lu

A = np.array([
    [3, 2, 7],
    [2, 3, 1],
    [3, 4, 1]
])

P, L, U = lu(A)

print(L)
print(U)

2)import numpy as np
from scipy.linalg import lu_factor, lu_solve

A = np.array([
    [3, 2, 7],
    [2, 3, 1],
    [3, 4, 1]
])

B = np.array([4, 5, 7])

lu, piv = lu_factor(A)

X = lu_solve((lu, piv), B)

print(np.round(X, 3))

-
```

## Output:
<img width="1882" height="845" alt="Screenshot 2026-05-28 220209" src="https://github.com/user-attachments/assets/ad88c0c6-9c50-4f51-9749-ef9318d5bd57" />
<img width="1487" height="692" alt="Screenshot 2026-05-28 220224" src="https://github.com/user-attachments/assets/3449ecb5-6cd3-489a-8ad9-38b85d609d6d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

