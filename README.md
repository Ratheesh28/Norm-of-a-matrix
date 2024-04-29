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
# Register No: 212223110040
# Developed By: Ratheesh Kumar B R
# 1-Norm of a Matrix
'''
program to find 1-norm of a matrix.
Developed by: Ratheesh Kumar B R
RegisterNumber: 212223110040
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
program to find 2-norm of a matrix.
Developed by: Ratheesh Kumar B R
RegisterNumber: 212223110040
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
'''
program to find the Infinity of a matrix.
Developed by: Ratheesh Kumar B R
RegisterNumber: 212223110040
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
![Screenshot 2024-04-29 134234](https://github.com/Ratheesh28/Norm-of-a-matrix/assets/138849186/01ce26df-c4a9-42f5-b78e-8734e66a7f14)
![Screenshot 2024-04-29 134253](https://github.com/Ratheesh28/Norm-of-a-matrix/assets/138849186/8398b2bd-1fd2-48aa-9153-7dd201dacae0)
![Screenshot 2024-04-29 134314](https://github.com/Ratheesh28/Norm-of-a-matrix/assets/138849186/e9e115c6-376a-4861-8170-4379706e412f)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
