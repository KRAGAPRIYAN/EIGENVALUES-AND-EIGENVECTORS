# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Date: 06/05/2026
## Roll.No: 212225040323

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required libraries such as os and numpy.
### Step 2: Create a square matrix using the np.array() function and store it in a variable.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the Eigenvalues and Eigenvectors using the print() function.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: K RAGAPRIYAN
#RegisterNumber: 212225040323

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:

![alt text](<Screenshot 2026-05-19 225922.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
