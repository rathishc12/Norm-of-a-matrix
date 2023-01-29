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
# Register No: 22009283
# Developed By: Rathish kumar C
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
![norm1](https://user-images.githubusercontent.com/120539398/214777358-e8df9cf6-90a8-4c27-bbd5-f09789ece111.png)
<br>
<br>
<br>

### 2-Norm of a Matrix
![norm2](https://user-images.githubusercontent.com/120539398/215312470-f4356aa3-950c-4a8d-b286-c8f88580bd12.png)
<br>
<br>
<br>

### Infinity Norm of a Matrix
![norm3](https://user-images.githubusercontent.com/120539398/215312481-7fd0d07f-9fb3-48a6-8ce2-72cdc8126f8b.png)
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
