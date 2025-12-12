# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Form the characteristic equation
### Step 2: Solve the characteristic polynomial
### Step 3: For each eigenvalue, find its eigenvector
### Step 4: Normalize (optional)

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Navaneeth S
#RegisterNumber:25009883
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:

<img width="882" height="172" alt="image" src="https://github.com/user-attachments/assets/e54c0da1-f6c4-44e6-bc87-d482a5fbe087" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
