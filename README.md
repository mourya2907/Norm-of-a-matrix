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
# Register No: 24006288
# Developed By: MOURYA G
# 1-Norm of a Matrix

#Developed By: MOURYA G
#Register Number: 24006288
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)


# 2-Norm of a Matrix

Program to find 2-norm of a matrix.
#Developed By: MOURYA G
#Register Number: 24006288
'''
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_mat="{:.2f}".format(ans)
print(norm_mat)


# Infinity Norm of a Matrix
'''
Program to find the Infinity of a matrix 
#Developed By: MOURYA G
#Register Number: 24006288
'''
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)




```
## Output:
### 1-Norm of a Matrix
<br>![alt text](image.png)
<br>
<br>

### 2-Norm of a Matrix
<br>![alt text](image-1.png)
<br>
<br>

### Infinity Norm of a Matrix
<br>![alt text](image-2.png)
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
