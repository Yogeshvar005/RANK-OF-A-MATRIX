# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import numpy as np.
### Step 2: 
Assign in np.array() in rank of matrix
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Print the value and end the program
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: Yogeshvar.M
#RegisterNumber: 222003358
import numpy as np
A = np.array([[1,2,3],[3,6,9]])
values = np.linalg.matrix_rank(A)
print(values)
```
## Output:
![output](rank.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

