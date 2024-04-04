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
#Program to find the solution for the given linear equations. 
#Developed by: Shaik Eesub 
#RegisterNumber:2305002021 
import numpy as np 
a=[[1,3],[2,5]] b=[5,-3] 
c=np.linalg.solve(a,b) 
print(c)

## Output:![286957098-58b99f2a-8c6c-4c51-9ee3-61b1677b7f3f_page-0001](https://github.com/eesub799/Linear-Algebra/assets/155223154/4ef607af-04d6-4e6a-b85c-e47c7616e0f5)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

