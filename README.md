# Norm of a matrix
## Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.


## Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:
```Python
# Register No:26009897
# Developed By: GOKUL N
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
norm3=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(norm3)
print(norm)





```
## Output:
### 1-Norm of a Matrix

<img width="1136" height="727" alt="image" src="https://github.com/user-attachments/assets/f13a7728-44a8-4674-a961-d570e8af1bbb" />

<img width="1272" height="278" alt="image" src="https://github.com/user-attachments/assets/f0ffb487-58bf-4189-ab2a-046bcb537956" />


### 2-Norm of a Matrix

<<img width="1266" height="772" alt="image" src="https://github.com/user-attachments/assets/af3ddd72-5200-4eff-a52c-9bdfb9d77354" />

<img width="1231" height="280" alt="image" src="https://github.com/user-attachments/assets/2b3677ce-01d4-46f1-94e8-b1a3d8a5ae4e" />


### Infinity Norm of a Matrix

<<img width="1451" height="577" alt="image" src="https://github.com/user-attachments/assets/d9e250fd-9538-4710-aa97-bc3316b4107a" />


<img width="1318" height="347" alt="image" src="https://github.com/user-attachments/assets/761802b5-69bd-4afc-a646-efc1d9530287" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
