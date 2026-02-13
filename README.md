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
# Register No:212224240085
# Developed By:Mageshkumar U
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
<img width="585" height="213" alt="image" src="https://github.com/user-attachments/assets/96b9d61d-f381-455e-9648-f74892d88e9a" />

### 2-Norm of a Matrix
<img width="531" height="255" alt="image" src="https://github.com/user-attachments/assets/d73a8f4c-ed44-4619-b9d7-722e7b308f14" />

### Infinity Norm of a Matrix
<img width="599" height="211" alt="image" src="https://github.com/user-attachments/assets/08c13427-f27a-425c-a2b7-f352d9d07e50" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified
