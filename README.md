# copy-file
### Name : Divya R V
### Register No : 23014030
### Department : CSE(CS)
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file with some content in it.
### Step 2: 
Open the created text file. 
### Step 3: 
Create another empty text file.
### Step 4:  
Copy the content of text file to empty file using write function. 

## PROGRAM:
## #Program for copying the contents from one file to another file
### Developed by: Divya R V
### Register Number: 23014030
```
with open("shyam.txt",'r') as file1:
    msg=file1.read()
with open("shyamnew.txt",'w') as file2:
    file2.write(msg)
```
### OUTPUT:
![Screenshot 2024-01-02 202132](https://github.com/rdivyav/copy-file/assets/148604723/63ea897a-1281-410d-9aea-b55e40139b93)

![Screenshot 2024-01-02 202220](https://github.com/rdivyav/copy-file/assets/148604723/e948ecea-1550-4e9c-90cf-f451039b6ed2)

![Screenshot 2024-01-02 202249](https://github.com/rdivyav/copy-file/assets/148604723/0f14a16d-f618-4032-b5e2-305cc917cd78)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
