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
# Register No: 212223230028
# Developed By: Baudhigan D
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Baudhigan D
RegisterNumber: 212223230028
'''
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
<br>![Screenshot 2024-05-14 201312](https://github.com/baudhigan/Norm-of-a-matrix/assets/151921158/8ff529fe-e54d-4882-abaa-a12a29836d1c)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2024-05-14 201409](https://github.com/baudhigan/Norm-of-a-matrix/assets/151921158/d40add76-bb6c-4eb0-ab64-d93ecaab2f43)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-05-14 201516](https://github.com/baudhigan/Norm-of-a-matrix/assets/151921158/56229780-5c08-45c3-9ce9-a7f74744b2c1)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
