# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen Vectors.
### Step 3: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors,then end the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rahul.V
#RegisterNumber: 23006860
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
b,vectors=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",vectors)
```

## Output:
![Screenshot 2023-12-27 092718](https://github.com/23006860/EIGENVALUES-AND-EIGENVECTORS/assets/139841752/2c4a1c3b-3b06-4590-9034-2159f95d0548)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
