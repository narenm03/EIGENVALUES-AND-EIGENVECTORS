# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy as np
### Step 2: 
arrange the given matrix in np.array command
### Step 3:  Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
run the program and get the output

## Program:
```
import numpy as np
a= np.array([[2,2,],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```


## Output:
![image](https://github.com/user-attachments/assets/cdb30cac-42d6-4ff4-932d-ea1c160a54cf)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
