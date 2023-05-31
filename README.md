# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### step 1:
	 Get the input matrix using np.array() 
### step 2:	 
         Find the 2-norm of the matrix using np.linalg.norm()
### step 3:	 
	 Print the norm of the matrix in two decimal places.
	 
## Program:
```Python
# Register No: 212222230041
# Developed By: Gowrisankar.p
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,1)
norm="{:.2f}".format(solu)
print(norm)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,2)
norm="{:.2f}".format(solu)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(solu)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/gowrisankarponnusamy/Norm-of-a-matrix/assets/119393123/8a232fb4-4ccc-4ae5-aeda-ec2602e31ae4)


### 2-Norm of a Matrix
![image](https://github.com/gowrisankarponnusamy/Norm-of-a-matrix/assets/119393123/9f6b4ce9-ff1f-4652-9b45-509c80002fa8)


### Infinity Norm of a Matrix
![image](https://github.com/gowrisankarponnusamy/Norm-of-a-matrix/assets/119393123/21392468-52b5-412e-8e93-ae4ef4611c45)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
