# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2: 
Using keyword "with" to open the requied file.
 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4: 
The empty file is open by using 'W' which is used to write only.

### Step 5: 
The four function is used to take each line from the main file.

### Step 6:
The four function is used to take each line from the main file.

## PROGRAM:
```
#Developed by: JAYAMANI R
#Reference no: 22008124
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```

### OUTPUT:
![Screenshot from 2023-01-26 15-45-24](https://user-images.githubusercontent.com/85949888/214811199-4841f101-4b66-4605-807d-e359d3eb8fc7.png)

![Screenshot from 2023-01-26 15-45-34](https://user-images.githubusercontent.com/85949888/214811276-95e929a8-64c9-42da-b46f-1a85bd400e48.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
