# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the Program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: KAMALESH R
#RegisterNumber: 212223230094
import numpy as np
A=np.array(([-2,2,-3],[2,1,-6],[-1,-2,0]))
values,Vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
```

## Output:
![Screenshot 2024-04-07 112755](https://github.com/KAMALESHNITHYA/EIGENVALUES-AND-EIGENVECTORS/assets/145743119/2a5a6d36-eda8-4f39-bc11-cfd6df0be894)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
