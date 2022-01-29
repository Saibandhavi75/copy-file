# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Start

### Step 2:Open the first file in read mode by an appropriate method 
 
### Step 3: Open the Second file in write mode by an appropriate method.

### Step 4: Loop until a variable 'i' in the first file.so Variable i propagates all over the content

### Step 5: Loop until a variable 'i' in the first file.so Variable i propagates all over the content

### Step 6: stop

## PROGRAM:
```python
#Develpoed By:A.Sai bandhavi
#Reference No:21005573
with open('first.txt','r') as firstfile, open('second.txt','a') as secondfile:
    # read content from first file
    for line in firstfile:
        # append content to second file
        secondfile.write(line)
```
### OUTPUT:
![output](https://github.com/Saibandhavi75/copy-file/blob/main/exp%2010(1).PNG?raw=true)

![output](https://github.com/Saibandhavi75/copy-file/blob/main/exp%2010-2.PNG?raw=true)

![output](https://github.com/Saibandhavi75/copy-file/blob/main/exp%2010-3.PNG?raw=true)


## RESULT:
Thus the program is written to copy the contents from one file to another file.