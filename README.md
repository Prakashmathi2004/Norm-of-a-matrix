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

# Register No:212222100035
# Developed By:M.PRAKASH


# 1-Norm of a Matrix
~~~
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~
# 2-Norm of a Matrix
~~~
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~

# Infinity Norm of a Matrix
~~~
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~

## Output:
### 1-Norm of a Matrix
<img width="542" alt="image" src="https://user-images.githubusercontent.com/118350045/235361413-965b3353-9012-4377-a840-d0f63253a249.png">

### 2-Norm of a Matrix
<img width="542" alt="image" src="https://user-images.githubusercontent.com/118350045/235361392-2de1c2c4-5e8e-4c8e-a248-452257664e8b.png">


### Infinity Norm of a Matrix
<img width="544" alt="image" src="https://user-images.githubusercontent.com/118350045/235361481-796f079d-93f3-4f08-9ec6-84529d67d092.png">


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
