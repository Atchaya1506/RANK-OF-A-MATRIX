# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the numpy module to use the built-in functions for calculation
### Step 2:  Prepare the lists from each equation and assign in np.array
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program
## Program:
```
import numpy as np

A = np.array([[1, 3],
              [2, 5]])

B = np.array([5, -3])

solution = np.linalg.solve(A, B)

print(solution)

```
## Output:

<img width="790" height="817" alt="image" src="https://github.com/user-attachments/assets/8671024e-a56b-4683-8a6c-dad6d8733bfe" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

