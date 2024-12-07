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
```python
# 1-Norm of a Matrix
'''
Developed by:AYSHWARIYA.J
RegisteredNumber:24901138
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm'''
Program to find 2-norm of a matrix.
Developed by:AYSHWARIYA.J
RegisterNumber:24901138 
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
# Type your code here
 of a Matrix




# Infinity Norm of a Matrix
'''
Developed by:AYSHWARIYA.J
RegisterNumber:24901138
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![EXP07 (i)](https://github.com/user-attachments/assets/0caaa55d-e318-46c1-8c42-3392e79e1e60)


### 2-Norm of a Matrix
![EXP07 (ii)](https://github.com/user-attachments/assets/dc7cb7df-bdce-4fcb-b406-578128c7f002)


### Infinity Norm of a Matrix
![EXP07 (iii)](https://github.com/user-attachments/assets/b924472b-abf3-45bd-8f5d-d4b229e51ca2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
