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
# Register No:212225240117
# Developed By:Ramesh Jaisurya
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
n="{:.2f}".format(ans)
print(n)

# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
n="{:.2f}".format(ans)
print(n)

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
n="{:.2f}".format(ans)
print(n)

```
## Output:
### 1-Norm of a Matrix
<br><img width="1118" height="556" alt="image" src="https://github.com/user-attachments/assets/2cf2506e-8830-41a6-9df1-e7fbc7d326af" />

<br><img width="972" height="326" alt="image" src="https://github.com/user-attachments/assets/7b610ee5-35ff-4dc5-8d4a-9481b7ffa312" />

### 2-Norm of a Matrix
<br><img width="966" height="393" alt="image" src="https://github.com/user-attachments/assets/a313739e-4c50-4bc6-ae42-b731e5934092" />

<br><img width="959" height="344" alt="image" src="https://github.com/user-attachments/assets/10da6202-ae4a-4ea0-bc07-90e0e9baaef7" />

### Infinity Norm of a Matrix
<br><img width="968" height="329" alt="image" src="https://github.com/user-attachments/assets/da21eb5f-74ce-4f80-aa01-400684aa89d5" />

<br><img width="934" height="267" alt="image" src="https://github.com/user-attachments/assets/99f5e1fa-7fc7-4ae2-9d55-3c00d3a4ac3c" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
