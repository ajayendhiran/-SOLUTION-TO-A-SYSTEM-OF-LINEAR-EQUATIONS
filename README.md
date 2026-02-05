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
#Developed by:A.jayendhiran 
#RegisterNumber:25017257
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array ([-9,4,-1])
X=np.linalg.solve(A,B)
print(X)
```
## Output:
<img width="1304" height="819" alt="Screenshot 2026-02-05 083142" src="https://github.com/user-attachments/assets/034e9b44-5635-418b-afff-a07f2358d972" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

