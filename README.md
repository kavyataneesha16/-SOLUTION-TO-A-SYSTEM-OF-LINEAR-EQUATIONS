<img width="373" height="168" alt="image" src="https://github.com/user-attachments/assets/19e72650-cf28-4611-b962-3e6a0f72ed9d" /># -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: G.Kavya
#RegisterNumber:212225220050
import numpy as np
A=[[1,3],[2,5]]
B=np.array([5,-3])
C=np.linalg.solve(A,B)
print(C)

## Output:
<img width="373" height="168" alt="image" src="https://github.com/user-attachments/assets/5aa39ea6-97ef-4318-9770-85d4139b3d39" />
<img width="373" height="168" alt="Screenshot 2026-03-26 204725" src="https://github.com/user-attachments/assets/01bf5bd1-7811-43f4-b284-b34416875807" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

