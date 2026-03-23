# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import Numpy module and lu library from scilig modules
2.Declare the array
3.Using lu library calculate the Lower triangle matrix and upper triangle matrix
4.End the program

## Program:
(i) To find the L and U matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Athul Krishna A V
RegisterNumber: 25013602
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
Developed by: Mithun Kumar V
RegisterNumber: 212225040236
*/
```
<img width="1536" height="1024" alt="Edit LU decompositio" src="https://github.com/user-attachments/assets/54ce6c9c-7def-40c6-89ca-df010b61511d" />

```
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
<img width="1211" height="508" alt="519057864-a3121832-1f01-4f64-91c0-8536b8d7e759" src="https://github.com/user-attachments/assets/c420beac-631a-42a0-9873-c434f552d154" />
![Uploading 519058114-05c7859e-f837-43e6-9dd6-7cf8c7a60930.png…]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

