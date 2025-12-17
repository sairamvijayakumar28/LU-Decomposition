# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input())) 
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
![lu decomposition]()
<img width="1842" height="751" alt="Screenshot 2025-12-17 152435" src="https://github.com/user-attachments/assets/02c08283-8f1b-4574-b403-75122502a7ec" />
<img width="1858" height="851" alt="Screenshot 2025-12-17 152451" src="https://github.com/user-attachments/assets/bdaf1ee5-c947-4472-a63c-f061b9b5c672" />
<img width="1866" height="788" alt="Screenshot 2025-12-17 152502" src="https://github.com/user-attachments/assets/b63cc052-d381-4384-a0ca-7f42418512b2" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

