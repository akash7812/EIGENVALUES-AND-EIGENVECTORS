# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy library from the python. 
### Step 2: 
Insert the coordinates into array field.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: AKASH KUMAR M.
#RegisterNumber:23011321
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![output](https://github.com/akash7812/EIGENVALUES-AND-EIGENVECTORS/assets/146819826/929a7b6e-277a-4ca2-84fb-6c01ec850c1c)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
