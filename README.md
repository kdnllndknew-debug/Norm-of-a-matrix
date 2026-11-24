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
Python
```
# Register No:
# Developed By:
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by:Hayas T I
RegisterNumber:26018713
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix

```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```


## Output:
### 1-Norm of a Matrix
<br><img width="1222" height="767" alt="Screenshot 2026-11-24 112456" src="https://github.com/user-attachments/assets/40eab09b-3282-4bc9-abcf-098bc8cbe9f1" />


<br>
<br>

### 2-Norm of a Matrix
<br><img width="1197" height="820" alt="image" src="https://github.com/user-attachments/assets/2725493d-b1e7-4132-98cd-21a0e7a0c250" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1181" height="717" alt="image" src="https://github.com/user-attachments/assets/031f5c9d-b4d3-4c28-8797-8aa669102551" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
