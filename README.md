# MAI---EX-4
## EIGENVALUES-AND-EIGENVECTORS
Name: NISHMA SHERIN . K 

Register number: 212224240104
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Read the given square matrix.

Step 2:
Import the NumPy library and store the matrix in array form.

Step 3:
Using np.linalg.eig(), obtain the eigenvalues and eigenvectors of the given matrix.

Step 4:
Display the eigenvalues and the corresponding eigenvectors.

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[4,2],
              [2,4]])
              
values, vectors = np.linalg.eig(A)

print("Eigen values are", values, "and Eigen Vectors are", vectors)

```
## Output:
<img width="1303" height="299" alt="image" src="https://github.com/user-attachments/assets/f2c31bf4-9450-4d74-8dfc-34d01e146870" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
