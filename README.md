# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy library.
### Step 2: 
Create a matrix using np.array().
### Step 3: 
Find the inverse of the matrix using np.linalg.inv().
### Step 4:
Display the inverse matrix using the print() statement.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: NEHA S
#RegisterNumber: 212225100030

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="932" height="212" alt="image" src="https://github.com/user-attachments/assets/a7b13dab-1c89-4d02-80f7-2c17b13f9829" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

