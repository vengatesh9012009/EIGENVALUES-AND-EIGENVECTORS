# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Read the input values
### Step 2: Import the required packages
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the output

## Program:
### #Program to find the eigen values and eigen vectors.
### #Developed by: VENGATESH S
### #RegisterNumber:26018307
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
### values,Vectors=np.linalg.eig(A)
### print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:
 <img width="400" height="400" alt="{AB12F9F5-5DE6-43C5-B97F-EB6E950BC70F}" src="https://github.com/user-attachments/assets/ee198897-b6f6-4f98-93f7-6744d06744ae" />
 <img width="400" height="400" alt="Screenshot 2026-10-13 182036" src="https://github.com/user-attachments/assets/92c0a59c-32c3-4b17-9c16-2d30ed050122" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
