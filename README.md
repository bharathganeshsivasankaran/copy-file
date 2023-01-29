# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read
mode
### Step 2:
Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using writing access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.

## PROGRAM:
```
with open("sample1.txt", "r") as firstfile:
      with open("sample2.txt", "a") as secondfile:
           for line in firstfile:
                secondfile.write(line)
````

### OUTPUT:
![output1 1](https://user-images.githubusercontent.com/119478098/215330155-c45c01a3-33aa-44a8-afae-ecd59da37af0.jpg)
![output1 2](https://user-images.githubusercontent.com/119478098/215330162-69940080-0d97-430c-9cc8-dba548a56897.jpg)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
