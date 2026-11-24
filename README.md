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


## Output:
### 1-Norm of a Matrix
<img width="1237" height="780" alt="image" src="https://github.com/user-attachments/assets/f03dfb4b-e695-4e18-a100-fb879d50b42a" />


### 2-Norm of a Matrix
<img width="1182" height="701" alt="image" src="https://github.com/user-attachments/assets/3a6c4fa8-534e-456f-8705-cecc3de8f2ff" />


### Infinity Norm of a Matrix
<img width="1192" height="787" alt="image" src="https://github.com/user-attachments/assets/1acceb16-4731-4316-be6e-9e28aae1cf33" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
