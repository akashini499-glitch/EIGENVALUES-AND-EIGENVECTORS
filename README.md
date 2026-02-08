# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
import numpy as np

matrix = np.array([[-2,  2, -3],
                   [2, 1, - 6],
                   [-1, -2,  0]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
## Output:
<img width="1289" height="367" alt="Screenshot 2026-02-08 160241" src="https://github.com/user-attachments/assets/d002fd7d-fb5a-4830-a2dd-a37fd6a09d0c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
