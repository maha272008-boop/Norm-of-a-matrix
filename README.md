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
```
# Register No:25017517
# Developed By:MAHALAKSHMI P
```

## 1-Norm of a Matrix

```
import numpy as np
A = np.array(eval(input()))
norm1 = np.linalg.norm(A,1)
print(f"{norm1:.2f}")

```


## 2-Norm of a Matrix

```

import numpy as np
A = np.array(eval(input()))
norm2 = np.linalg.norm(A,2)
print(f"{norm2:.2f}")



```

## Infinity Norm of a Matrix

```
import numpy as np
A = np.array(eval(input()))
norm3 = np.linalg.norm(A,ord=np.inf)
print(f"{norm3:.2f}")

```


## Output:

### 1-Norm of a Matrix
<img width="1089" height="430" alt="Screenshot 2025-11-27 082957" src="https://github.com/user-attachments/assets/bb49304f-14c0-4afa-8368-bf11ba22b606" />
<img width="969" height="226" alt="Screenshot 2025-11-27 083010" src="https://github.com/user-attachments/assets/829b43a3-c6d4-4a11-8c34-9b1e830d8b3d" />



### 2-Norm of a Matrix
<img width="1093" height="584" alt="Screenshot 2025-11-27 083036" src="https://github.com/user-attachments/assets/2688cf42-8902-4960-8544-bc679dc1cd6a" />
<img width="887" height="280" alt="Screenshot 2025-11-27 083045" src="https://github.com/user-attachments/assets/6713e1a5-3b64-4b42-b953-27826778b52a" />


### Infinity Norm of a Matrix
<img width="1261" height="437" alt="Screenshot 2025-11-27 083055" src="https://github.com/user-attachments/assets/17dc9dcc-2dbf-4afe-9f49-48d6906ff35b" />
<img width="789" height="231" alt="Screenshot 2025-11-27 083106" src="https://github.com/user-attachments/assets/41d98f5f-4217-4930-8c6d-05c91a586cfe" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
