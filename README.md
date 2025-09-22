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
# Register No:212224100038
# Developed By:Mukesh Raj D
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
<br><img width="1387" height="644" alt="Screenshot 2025-09-22 144034" src="https://github.com/user-attachments/assets/95b16a9d-978e-4589-b58e-2e588ccb06ed" />

<br>

### 2-Norm of a Matrix
<br>
<br><img width="1574" height="617" alt="Screenshot 2025-09-22 144053" src="https://github.com/user-attachments/assets/c04210a5-5427-428f-971d-d2f81c899430" />

<br>

### Infinity Norm of a Matrix
<br><img width="1680" height="625" alt="Screenshot 2025-09-22 144106" src="https://github.com/user-attachments/assets/47f97e23-9054-4c39-b106-5b7058d7e648" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
