# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 1-norm,2-norm and infinity norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
'''
Program to find 1-norm of a matrix.
Developed by: KESAV DEEPAK SRIDHARAN
RegisterNumber: 23002011
'''
import numpy as np
a = np.array(eval(input()))
ans = np.linalg.norm(a,1)
norm = '{:.2f}'.format(ans)
print(norm)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: KESAV DEEPAK SRIDHARAN
RegisterNumber: 23002011
'''
import numpy as np
a = np.array(eval(input()))
ans = np.linalg.norm(a,2)
norm = '{:.2f}'.format(ans)
print(norm)

# Infinity Norm of a Matrix
'''
Program to find infinity-norm of a matrix.
Developed by: KESAV DEEPAK SRIDHARAN
RegisterNumber: 23002011
'''
import numpy as np
a = np.array(eval(input()))
ans = np.linalg.norm(a,np.inf)
norm = '{:.2f}'.format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![output1](out1.png)

### 2-Norm of a Matrix
![output2](out2.png)

### Infinity Norm of a Matrix
![output3](out3.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
