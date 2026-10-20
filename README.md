# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
a = np.array([[2, 1, 1],
              [1, 1, 1],
              [1, -1, 2]])
b = np.linalg.inv(a)
print(b)
```
## Output:
<img width="917" height="198" alt="image" src="https://github.com/user-attachments/assets/8e39e2a2-fc69-476a-8462-a11dbc5a69b9" />
<img width="1111" height="732" alt="image" src="https://github.com/user-attachments/assets/afa9c33e-6cb7-4c1f-967b-2f1ee65570f5" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

