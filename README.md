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
# Register No:23012987
# Developed By:Farhana H

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
<br>![image](https://github.com/syedfayaz3105/Norm-of-a-matrix/assets/147144126/770e974e-0958-4617-9b70-547840dd4436)
### 2-Norm of a Matrix
<br>![image](https://github.com/syedfayaz3105/Norm-of-a-matrix/assets/147144126/6b49c0c6-3f81-4ec0-bd21-3a903bf53600)

### Infinity Norm of a Matrix
<br>![image](https://github.com/syedfayaz3105/Norm-of-a-matrix/assets/147144126/b2f25901-501b-4e62-ad7f-4c4234dabe84)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
