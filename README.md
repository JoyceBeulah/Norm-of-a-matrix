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
# Register No:22009334
# Developed By:R. Joyce Beulah
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![ot](https://user-images.githubusercontent.com/118343698/215129877-b838b73d-3335-4872-9c5b-f4d046c8e2e5.png)

### 2-Norm of a Matrix
![0](https://user-images.githubusercontent.com/118343698/215130147-b9a33d6a-95fe-42c9-ba2c-2109155de852.png)


### Infinity Norm of a Matrix
![00](https://user-images.githubusercontent.com/118343698/215130357-7098c09c-c55a-4c98-9f50-b3c9dad95ceb.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
