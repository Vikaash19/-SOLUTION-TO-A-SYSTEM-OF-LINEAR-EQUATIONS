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
~~~
#Program to find the solution for the given linear equations.
#Developed by: Vikaash K S
#RegisterNumber: 23013426
import numpy as n
a=n.array([[1,3],[2,5]])
b=n.array([5,-3])
c=n.linalg.solve(a,b)
print(c)
~~~
## Output:
![equation of a matrix](https://github.com/Vikaash19/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/148514589/c2038d08-4c14-4794-97e7-75a14fda8526)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

