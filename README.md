# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Create a text1.txt with some content in it
## Step 2:

Open the text1.txt file in read mode
## Step 3:

Create a copy.txt file using write mode
## Step 4:

Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Programmed By: K.R.Hashish Visya Sagar
RegisterNumber: 212222230047
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/hashish9275/copy-file/assets/118707521/e0c6061e-d4d4-403e-9edf-443aa3e0a229)

![image](https://github.com/hashish9275/copy-file/assets/118707521/e2a41eb7-3674-45a4-b7cc-45e95bed99b8)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
