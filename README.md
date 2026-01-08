# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
step1. Get the input matrix using np.array()   
step2. Find the 2-norm of the matrix using np.linalg.norm()
step3. Print the norm of the matrix in two decimal places.
## Program:
```Python
import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,np.inf):.2f}")

import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,2):.2f}")

import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,np.inf):.2f}")

```
## Output:
### 1-Norm of a Matrix
<img width="1899" height="848" alt="Screenshot 2025-12-26 154710" src="https://github.com/user-attachments/assets/fef7c3ec-1404-4230-9efc-cb771ed9d50d" />


### 2-Norm of a Matrix
<img width="1899" height="837" alt="Screenshot 2025-12-26 154729" src="https://github.com/user-attachments/assets/6c4fc023-b3a4-4603-b32a-f7daf78c5068" />

### Infinity Norm of a Matrix
<img width="1906" height="842" alt="Screenshot 2025-12-26 154745" src="https://github.com/user-attachments/assets/ac2a0003-2e24-40d8-81c1-f9aaf05dde4c" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
