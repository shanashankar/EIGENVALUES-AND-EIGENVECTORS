# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to  use the built in functions for calculations
### Step 2: prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:sahana shankar
#RegisterNumber:26002875

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,Vectors=np.linalg.eig(A)

print(f"Eigen values are {values} and Eigen Vectors are {Vectors}")

## Output:

<img width="1920" height="1080" alt="ex 04 output" src="https://github.com/user-attachments/assets/f799a9ea-8297-4cf4-8eaf-238a66db2a00" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
