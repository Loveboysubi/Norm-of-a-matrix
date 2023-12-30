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
# Register No: 23003621
# Developed By: Subishesh. P
# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Loveboysubi/Norm-of-a-matrix/assets/138970879/a89750f9-a603-42e5-b4ad-1a689383b0bc)


### 2-Norm of a Matrix
![image](https://github.com/Loveboysubi/Norm-of-a-matrix/assets/138970879/d6aa6698-c0c3-4c1e-8c1b-ddec953e9598)


### Infinity Norm of a Matrix
![image](https://github.com/Loveboysubi/Norm-of-a-matrix/assets/138970879/fbec3db7-6cfc-4eb0-be94-84a297234960)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
