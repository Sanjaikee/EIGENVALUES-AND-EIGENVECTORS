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
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
b,c=np.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")
```

## Output:
![Screenshot 2023-11-24 110448](https://github.com/2005Mukesh/EIGENVALUES-AND-EIGENVECTORS/assets/138849308/bd0fc307-2ca3-4a5f-9a65-bf90381a84ce)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
