# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.

### Step 2: 
prepare the lists from the each inverseof a matrix and design in ip.array().

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:DHARANYA.N
#RegisterNumber:23006980
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/Rithikachezhian/EIGENVALUES-AND-EIGENVECTORS/assets/145742406/6a0babec-bf11-4220-b265-ccfc9003a316)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
