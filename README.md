# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation 

Step 2:
Prepare the lists from the matrix and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix. 

Step 4:
End the program

## Program:import numpy as np


A = np.array([[4, 2],
              [2, 4]])

eigenvalues, eigenvectors = np.linalg.eig(A)


print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)

## Output:<img width="1291" height="608" alt="Screenshot 2025-10-07 143530" src="https://github.com/user-attachments/assets/0242d4a1-57f4-4fb1-ae36-4624014b7c15" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
