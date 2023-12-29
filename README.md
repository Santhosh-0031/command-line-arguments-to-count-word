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
![Screenshot 2023-12-29 190223](https://github.com/Santhosh-0031/command-line-arguments-to-count-word/assets/145551108/d334c338-02bb-4848-bbe8-00c60c045e32)

i) TEXT FILE
![Screenshot 2023-12-29 190223](https://github.com/Santhosh-0031/command-line-arguments-to-count-word/assets/145551108/69aaceb5-0a91-49ba-a32f-54f0e3e6b6ec)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
