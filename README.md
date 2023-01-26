# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open Jupyterlab and a plain text file and save the file with .txt extension

### Step 2: 
 Enter some words in file.txt file.
 
### Step 3: 
Create python notebook.


### Step 4:  
Enter the code with file name as excatly given in .txt extension.

### Step 5: 
Run the code ,it will copy from file to file2

### Step 6: 
Open the file2.txt it will copy the input and display.


## PROGRAM:
```
Developed by: Aakashraj M
Register number: 22008579

with open('a1.txt','r')as firstfile:
    with open('a2.txt','a')as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/121117266/214820826-b79f47ff-d89d-49c2-802a-88bed2ee5254.png)
![image](https://user-images.githubusercontent.com/121117266/214820905-76ca6065-f643-409b-b40f-12637881feff.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
