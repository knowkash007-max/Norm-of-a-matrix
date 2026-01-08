# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
step1: Get the input matrix using np.array()   
step2:Find the 2-norm of the matrix using np.linalg.norm()
step3:Print the norm of the matrix in two decimal places.
## Program:
```Python
import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,1):.2f}")

'''
Program to find 2-norm of a matrix.
Developed by:KNOWKASH G
RegisterNumber:25015209
'''
import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,2):.2f}")

import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,np.inf):.2f}")
```
## Output:
### 1-Norm of a Matrix
<img width="1899" height="848" alt="Screenshot 2025-12-26 154710" src="https://github.com/user-attachments/assets/3aad632f-a29f-4895-9823-a9b108ddc11e" />

### 2-Norm of a Matrix
<img width="1899" height="837" alt="Screenshot 2025-12-26 154729" src="https://github.com/user-attachments/assets/439c2d9b-d6f5-40c4-83a1-7e8ba0bcb539" />

### Infinity Norm of a Matrix
<img width="1906" height="842" alt="Screenshot 2025-12-26 154745" src="https://github.com/user-attachments/assets/d7272b6f-f5b8-4adb-aa64-39e71eafbeee" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
