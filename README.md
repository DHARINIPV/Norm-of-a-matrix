# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:
```Python
# Register No: 212222240024
# Developed By: Dharini PV

# 1-Norm of a Matrix

import numpy as np

a=np.array(eval(input()))

soln=np.linalg.norm(a,1)

norm="{:.2f}".format(soln)

print(norm)

# 2-Norm of a Matrix

import numpy as np

a=np.array(eval(input()))

soln=np.linalg.norm(a,2)

norm="{:.2f}".format(soln)

print(norm)

# Infinity Norm of a Matrix

import numpy as np

a=np.array(eval(input()))

soln=np.linalg.norm(a,np.inf)

norm="{:.2f}".format(soln)

print(norm)
```

## Output:
### 1-Norm of a Matrix

![image](https://github.com/DHARINIPV/Norm-of-a-matrix/assets/119400845/07b194fa-e55b-4200-9456-84dfee542f90)

### 2-Norm of a Matrix

![image](https://github.com/DHARINIPV/Norm-of-a-matrix/assets/119400845/ed467892-1a24-40dd-b80f-4b7b455c4e23)

### Infinity Norm of a Matrix

![image](https://github.com/DHARINIPV/Norm-of-a-matrix/assets/119400845/27c3c25a-93f4-4407-b970-f925539d1fbf)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
