# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# Step 1:
Get the input matrix using np.array()   
# Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
# Step 3:
Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: LOGA MITHRA.R
# Developed By: 212223100027
# 1-Norm of a Matrix
```
#find the 1-Norm of a matrix and display the results in two decimal places.
#Developed by: LOGA MITHRA.R
#Register number: 212223100027
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
#Program to find 2-norm of a matrix.
#Developed by: LOGA MITHRA.R
#RegisterNumber: 212223100027
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix
```
#program to find infinity norm of a matrix
#Developed by: LOGA MITHRA.R
#Register number: 212223100027
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
## Output:
### 1-Norm of a Matrix
![output](/img%201.png)
### 2-Norm of a Matrix
![output](/img%202.png)
### Infinity Norm of a Matrix
![output](/img%203.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
