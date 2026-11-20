# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212224230098
# Developed By: JAGADEESH.A
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: JAGADEESH.A
RegisterNumber: 212224230098
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1296" height="275" alt="Screenshot 2026-11-04 124645" src="https://github.com/user-attachments/assets/48a9d3fb-c02d-4f15-a2bf-0615e4845ee2" />


### 2-Norm of a Matrix
<img width="1290" height="308" alt="Screenshot 2026-11-04 124658" src="https://github.com/user-attachments/assets/12b1bd32-131d-4791-aa87-7f5bd203c74f" />


### Infinity Norm of a Matrix
<img width="1290" height="270" alt="Screenshot 2026-11-04 124710" src="https://github.com/user-attachments/assets/ca42fca9-7701-422f-b40c-efafea531ac3" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
