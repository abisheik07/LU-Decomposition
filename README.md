# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Program 1:

1. Step1: Import numpy and scipy.linalg,in linalg you can input lu. and in second program can import lu_factor and lu_solve from python library as same as in second program.

2. Step2:Get the input from user as the form of nested list to compute numpy array format

3. Step3: Use inputted array (matrix) to compute in corresponding builtin modules function such as lu and create new variables such as piv,i matrix u matrix to store

4. Step4: Print the corresponding bvariable to get output (I_matrix)

5. Step5: Print the corresponding bvariable to get output (u_matrix) 
 
program 2:
1. Step1: In second program can import lu factor and lu solve from python library as same as in second program.

2. Step2: Get the input from user in the form of nested list to compute numpy array format and declare it for both the variables.

3. Step3: Create the variable to Use inputted array to compute of lu factor of matrix varaible.

4. Step4: Create the new variable for lu solve to compute of 'x' variable and 'b' variable.

5. Step5: Print the corresponding variable (solution) to get the output.
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: abisheik raj
RegisterNumber: 24900664
*/
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: abisheik raj 
RegisterNumber: 24900664
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```
## Output:
![lu decomposition]()
![](<Screenshot 2024-12-26 132755.png>)
![](<Screenshot 2024-12-26 132809.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

