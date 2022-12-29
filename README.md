# INVERSE-OF-A-MATRIX

## Aim:
To write a python program to find the inverse of a matrix

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : 
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_inv(), we can find the rank of the given matrix.

### Step 4: 
End the program

## Program:

```python
#Program to find the inverse of a matrix.
#Developed by: SATHISH R
#RegisterNumber:22009045
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(A)
print(inverse)
```

## Output:

![inverse](https://user-images.githubusercontent.com/120574768/209985228-2b242949-5f1b-43eb-8acd-bec453cf1eaf.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

