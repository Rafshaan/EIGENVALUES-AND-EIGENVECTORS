# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import NumPy as np to use its mathematical and linear algebra functions
### Step 2:
Create a square matrix A by placing the given values inside a nested list.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the eigenvalues and eigenvectors as the output and end the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: A.RAFSHAAN AHMED
#RegisterNumber: 212224230214
import numpy as np
A=[4,2],[2,4]
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
![alt text](image.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
