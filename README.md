# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Get the input from the user.
### Step 2: 
Use the function import numpy.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and eigen vectors and end the program.
## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: Samyuktha.S

#RegisterNumber:22005276

import numpy as np

a=np.array([[2,2],[1,3]])

values,vectors=np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
![output](/ads.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
