# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3:  Using the np.linalg.inv, we can find the solutions.
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Ajay Karthick R
#RegisterNumber:212225230007
import numpy as np

# Define the matrix (based on the provided result, this matches A)
A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])

# Calculate the inverse
try:
    inverse_matrix = np.linalg.inv(A)
    print(inverse_matrix)
except np.linalg.LinAlgError:
    print("Matrix is singular and cannot be inverted.")

```
## Output:
![alt text](image.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

