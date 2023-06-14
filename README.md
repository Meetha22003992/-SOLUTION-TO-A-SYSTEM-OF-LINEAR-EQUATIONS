# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.Import the numpy module to use the built-in functions for calculation

2.Prepare the lists from each linear equations and assign in np.array()

3.Using the np.linalg.solve(), we can find the solutions.

4. End the program
## Program:
```
#Program to find the solution for the given linear equations. 
#Developed by: Meetha Prabhu
#RegisterNumber: 212222240065

import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
soln=np.linalg.solve(A,B)
print(soln)
```
## Output:
![System ss](https://user-images.githubusercontent.com/119401038/225926326-75564b5c-0ec6-4486-a430-4a03f30fb953.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

