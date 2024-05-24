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

# Developed By : MUKESH S
# Register No : 2305002016

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
![image](https://github.com/mukeshdj/Norm-of-a-matrix/assets/155506353/bdd24646-f1ba-4ac6-ba91-de83954fad6d)

### 2-Norm of a Matrix
![image](https://github.com/mukeshdj/Norm-of-a-matrix/assets/155506353/fffd1163-849d-418f-a2a6-e583d5b073f3)


### Infinity Norm of a Matrix
![image](https://github.com/mukeshdj/Norm-of-a-matrix/assets/155506353/21b3fa4e-0194-48d6-947c-2d58b543e237)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
