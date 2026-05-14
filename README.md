# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix 
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Start and input the order and elements of the matrix.
### Step 2: Perform row operations to convert the matrix into row echelon form.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix and stop.
## Program:
#Program to find the rank of a matrix.
#Developed by: Bristo AK
#RegisterNumber:212225230037
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixa=( [[1,2,3],[3,6,9]])
result=np.linalg.matrix_rank(matrixa)
print(result)
```
## Output:
<img width="1247" height="173" alt="Screenshot 2026-05-14 104357" src="https://github.com/user-attachments/assets/8919eceb-2995-4ac2-888a-143493a31a93" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

