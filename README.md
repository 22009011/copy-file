# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```

Program for copying the contents from one file to another file
Developed by: THANJIYAPPAN.K
RegisterNumber: 212222240108

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/22009011/copy-file/assets/118343461/e182ca7e-1adc-41a4-bb3e-39a7cbf6d969)
![image](https://github.com/22009011/copy-file/assets/118343461/5869a8ba-2def-44d1-875e-0b54eb15a264)
![image](https://github.com/22009011/copy-file/assets/118343461/1dda4bc0-e3a7-4084-8793-bf269e1a9251)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
