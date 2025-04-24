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
# Register No: 212224230039
# Developed By: Blessing S
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-24 201712](https://github.com/user-attachments/assets/d02b2262-1019-4fad-ab03-5a504a7edfe5)


### 2-Norm of a Matrix
![Screenshot 2025-04-24 201802](https://github.com/user-attachments/assets/bf8dcfce-b005-444f-a811-924faa4cdbe5)


### Infinity Norm of a Matrix
![Screenshot 2025-04-24 201835](https://github.com/user-attachments/assets/49f88657-c155-41f7-ab47-bd56daf9eb4d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
