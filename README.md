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
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: SIMSON ROY J
#RegisterNumber:212225040415
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=[[1,3],[2,5]]
B=np.array([5,-3])
C=np.linalg.solve(A,B)
print(C)
```
## Output:
<img width="429" height="165" alt="{EA746286-BC06-4048-82D5-A72C7C2D516A}" src="https://github.com/user-attachments/assets/d4b3c0d4-daf7-48e1-afc2-cb684ed0c46e" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

