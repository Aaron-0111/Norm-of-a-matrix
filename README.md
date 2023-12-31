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
# Register No: 23008897
# Developed By: AARON RAJESH R.
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)


# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom) 



```

## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-31 211257](https://github.com/Aaron-0111/Norm-of-a-matrix/assets/149347631/b52506d8-6afb-4a78-b405-d072b3d53286)

### 2-Norm of a Matrix
![Screenshot 2023-12-31 211321](https://github.com/Aaron-0111/Norm-of-a-matrix/assets/149347631/d864c7f0-70f3-4728-9866-acc4ba2eab5e)


### Infinity Norm of a Matrix
![Screenshot 2023-12-31 211338](https://github.com/Aaron-0111/Norm-of-a-matrix/assets/149347631/88b02a82-7d59-494c-aff5-e5098ebc5eaa)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
