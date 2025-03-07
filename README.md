# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print'.

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X'
 

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Akash Prakash
RegisterNumber: 24008757

import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Akash Prakash
RegisterNumber: 24008757
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
b=np.array([4, 5, 7])
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)

*/
```

## Output:
![lu decomposition]()

![Screenshot 2024-12-26 232433](https://github.com/user-attachments/assets/b29943d7-1090-4926-ba4b-ded340f4a283)

![Screenshot 2024-12-26 232507](https://github.com/user-attachments/assets/3441b0bb-ef7a-4bd9-a81b-836c2e929089)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

