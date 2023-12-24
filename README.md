# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys module

### Step 2: 
using sys module,open a file with read mode
 
### Step 3: 
read the file and spilt the file and store in the variable

### Step 4:  
print the length of the variable

### Step 5: 
End the program
 

## PROGRAM:
```
To write a python program for getting the word count from the contents of a file using command line arguments.
Developed by: SANTHOSH KUMAR R
Reference no: 23013562

import sys
f=open(sys.argv[1],"r")
a=f.read().split()
print(len(a))
```

### OUTPUT:
![Screenshot 2023-12-24 185926](https://github.com/Santhosh-0031/command-line-arguments-to-count-word/assets/145551108/c3daa597-814f-4bd5-928d-5a4fd24d49dc)

i) TEXT FILE
![Screenshot 2023-12-24 190046](https://github.com/Santhosh-0031/command-line-arguments-to-count-word/assets/145551108/7ecf7b76-67a9-46fa-a669-6dea041095f9)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
