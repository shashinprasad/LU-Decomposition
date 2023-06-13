# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Read the elements of augmented matrix into arrays a and b.
2. Calculate elements of L and U.
3. Print elements of L and U.
4. Find V by solving LV = B by forward substitution.
5. Find X by solving UX = V by backward substitution.
6. Print Array X as the solution.

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Sashin Prasad S
RegisterNumber: 212222230144

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Sashin Prasad S
RegisterNumber: 212222230144
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
(i)

![Screenshot 2023-06-13 184528](https://github.com/shashinprasad/LU-Decomposition/assets/129143499/6feabc58-c8c9-4066-a7c3-9a4ff482e959)


(ii)

![Screenshot 2023-06-13 184537](https://github.com/shashinprasad/LU-Decomposition/assets/129143499/f4381173-5e38-4baa-9c44-1c63e5184f85)



## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

