# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Use open function to open the file in which we want to copy from and access it in read mode.

### Step2:

Read the file and store in a variable.
### Step3:

Now create a new file in which we want to paste the content using write access mode.
### Step 4:

Use write function to copy the read file that has been stored in the variable.
### Step 5:

The content in the original file will be copied in the new file.
### Step 6:

End the program.



## PROGRAM:
```python
To write a program for copying the contents from one file to another file.
Developed by: Dinesh Karthick.K.J
RegisterNumber: 22005847

with open("myfile.txt","r") as fp:
    x = fp.read()
with open("data3.txt","w") as fp1:
    fp1.write(x)
```
### OUTPUT:
![2](https://user-images.githubusercontent.com/120552008/214821744-684c7852-7eef-4937-a285-b6b1622aca9a.png)
![3](https://user-images.githubusercontent.com/120552008/214821760-9b48a45c-b6df-47d1-a5b2-f85b859ed56d.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
