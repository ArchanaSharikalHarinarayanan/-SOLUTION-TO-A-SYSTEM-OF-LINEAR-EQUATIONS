# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
### Question:
Write a program to find the eigenvalues and associated eigenvectors for the matrix [2,2],[1,3]

## Program:
```
Developed by:sowmiya g
RegisterNumber:2305002023
```
```
import numpy as np
A=np.array([[2,2],[1,-3]])
values,vector=np.linalg.eig(A)
print("Eigenvalues are {} and Eigenvectors are {}".format(values,vector))
```
## Output:
![Screenshot 2024-04-12 145002](https://github.com/ArchanaSharikalHarinarayanan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/146059163/2ff5a2d0-9528-4f8b-b3dc-3203acb4e31f)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

