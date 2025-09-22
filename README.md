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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix=print("{:.2f}".format(ans))



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2) 
Norm_of_matrix=print("{:.2f}".format(ans)) 



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<br>
<br><img width="1387" height="644" alt="Screenshot 2025-09-22 144034" src="https://github.com/user-attachments/assets/608c18d8-76e3-46c1-afb4-3f8290f639bb" />

<br>

### 2-Norm of a Matrix
<br>
<br><img width="1574" height="617" alt="Screenshot 2025-09-22 144053" src="https://github.com/user-attachments/assets/3b649454-30b2-4c88-a11c-e157e5ba48cd" />

<br>

### Infinity Norm of a Matrix
<br>
<br><img width="1680" height="625" alt="Screenshot 2025-09-22 144106" src="https://github.com/user-attachments/assets/81cece10-7a80-4679-ae39-95a9df9fa2f2" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
