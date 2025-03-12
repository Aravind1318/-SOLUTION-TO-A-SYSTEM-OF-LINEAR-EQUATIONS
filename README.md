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
#Developed by: ARAVIND P
#RegisterNumber: 212224240015
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
sol=np.linalg.solve(A,B)
print(sol)
```
## Output: ![Screenshot 2025-03-12 100337](https://github.com/user-attachments/assets/aec14c1e-0374-49e4-b1cb-b1f71edc6a93)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

