# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation.
2.Prepare the lists from each linear equations and assign in np.array().   
3.Using the lu() function in scipy.linalg module, we can find the solutions.   
4.End the program.
## Program:
(i) To find the L and U matrix
```pythono
'''
Program to find L and U matrix using LU decomposition.
Developed by : DARSHAN S  
RegisterNumber: 212222100010
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: DARSHAN S 
RegisterNumber: 212222100010
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
(i) To find the L and U matrix

![LU matrix](https://github.com/Darshans05/LU-Decomposition/assets/115534676/1add59a4-26fe-44cb-8f67-76fadcee57ca)

(ii) To find the LU Decomposition of a matrix

![solve a matrix](https://github.com/Darshans05/LU-Decomposition/assets/115534676/879fc7d3-eb69-4265-8b12-a3b0dc689237)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

