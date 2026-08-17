# exp 2 RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### step 1:
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4:
End the program
## Program:
```py
#Program to find the rank of a matrix.
#Developed by: m.sanjay babu
#RegisterNumber:21225040369
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[1,2,3],[3,6,9]])
result = np.linalg.matrix_rank(matrixA)
print(result)
```
## Output:
<img width="346" height="157" alt="image" src="https://github.com/user-attachments/assets/32f4f9b1-e0be-44a0-9d7f-c5956c611496" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

