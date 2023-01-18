# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
get the input from the user
### Step 2:
name the inputs as variables
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
end with print statment to get the output

## Program:
``` python
import numpy as np
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![m4](https://user-images.githubusercontent.com/121608770/213080645-49e8d1db-01b2-437b-b9ea-2be56c9d6603.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
