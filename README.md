# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Get the input matrix from the user

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program
```

## Program:


DEVELOPED BY : JERUSHLIN JOSE J B 
REG :212222240039

```
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```


## Output:



![image](https://github.com/Jerushli/EIGENVALUES-AND-EIGENVECTORS/assets/120041243/69dcd5e0-1182-42b3-b790-d964b647453d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
