# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : imprt numpy moduile as np.
### Step 2: store yhe matrices in an array A using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: now print calculated eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Joshua Daniel A 
#RegisterNumber: 212225040161 (25017654)

import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
<img width="1658" height="216" alt="Screenshot 2026-02-05 091210" src="https://github.com/user-attachments/assets/3ff5b83e-6799-4145-afa4-6dfe7410c445" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
