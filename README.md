# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and import the required library (NumPy). Define the matrix
### Step 2: Find the determinant of matrix A to check whether it is invertible.
### Step 3: If the determinant is not zero, compute the inverse of the matrix using np.linalg.inv(A).
### Step 4: Display the inverse matrix. If the determinant is zero, print that the matrix is not invertible.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Sanjeev Kumar .K 
#RegisterNumber:212225230246
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[2,1,1],[1,1,1], [1,-1,2]])
inv=np.linalg.inv(matrixA)
print(inv)
```
## Output:

<img width="1453" height="809" alt="Screenshot 2026-05-02 084121" src="https://github.com/user-attachments/assets/c9a439d4-6746-4ce5-bdc3-4f5aae68271c" />

<img width="1493" height="388" alt="Screenshot 2026-05-02 084140" src="https://github.com/user-attachments/assets/f1a8a255-376c-48bf-afd5-b62731063619" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

