# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy modules as np
### Step 2: Define the matrix as numpy array.
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: Display the result using print() function

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Neeli Darshini
#RegisterNumber:212225230200
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[6, 2, 3],[3, 1, 1],[10, 3, 4]])
result=np.linalg.inv(matrix)
print(result)
```

## Output:
<img width="586" height="222" alt="image" src="https://github.com/user-attachments/assets/41674c2a-cd8d-45fd-bded-e1a43aff10cd" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

