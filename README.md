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
```
# Register No: 212225230134
# Developed By: Kavinithan C
# 1-Norm of a Matrix
```
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```




# 2-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```




# 3-Infinity Norm of a Matrix
```import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
x="{:.2f}".format(ans)
print(x)
```






## Output:
### 1-Norm of a Matrix
<img width="1331" height="714" alt="image" src="https://github.com/user-attachments/assets/29f92bdd-765c-4006-ab66-a0e3f9f38934" />


### 2-Norm of a Matrix
<img width="1346" height="784" alt="image" src="https://github.com/user-attachments/assets/beb21e75-babf-44d5-9698-f70ab0d9ddf6" />


### Infinity Norm of a Matrix
<img width="1342" height="699" alt="image" src="https://github.com/user-attachments/assets/c72df563-e8a7-486a-b59b-30b10323673e" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
