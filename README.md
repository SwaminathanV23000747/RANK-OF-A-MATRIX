# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in function for calculation.

### Step 2: 
Prepare the lists from each linear equation and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program.
## Program:
```python
#Developed by: Swaminathan V 
#RegisterNumber: 23000747

import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
## Output:
![2-Rank of a matrix](https://github.com/SwaminathanV23000747/RANK-OF-A-MATRIX/assets/148931113/b9eba9fb-1d33-4684-a125-10d3460346ca)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

