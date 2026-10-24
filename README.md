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
# Register No:26019370
# Developed By:SURYA S
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
norm="{:.2f}".format(norm1)
print(norm)




# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
norm2=np.linalg.norm(a,2)
norm="{:.2f}".format(norm2)
print(norm)




# Infinity Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
noem3=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(noem3)
print(norm)





```
## Output:
### 1-Norm of a Matrix
<br><img width="1192" height="377" alt="image" src="https://github.com/user-attachments/assets/09851d95-71bc-463e-91c6-dd9cc909ed13" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1137" height="432" alt="image" src="https://github.com/user-attachments/assets/e59e6e0a-fc08-4f01-9cb9-635eca470e09" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1087" height="376" alt="image" src="https://github.com/user-attachments/assets/bb9ffdb5-14ce-4e0d-881c-cda5edfcf730" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
