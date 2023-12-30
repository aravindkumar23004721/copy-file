![Screenshot 2023-12-30 224511](https://github.com/aravindkumar23004721/copy-file/assets/148962674/914b1c69-ca6f-4750-8398-4d36df3d40d1)# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the source file in read mode.

### Step 2:
Read the contents of the source file and store it in a variable

### Step 3:
Close the source file.

### Step 4:
Open the destination file in write mode. If the file doesn't exist, it will be created.

### Step 5:
Write the contents from the variable to the destination file.

### Step 6:
Read the contents of the destination file and print it to verify the copy operation.

### Step 7:
End the program
## PROGRAM:
```python
#Program to copy the text from one file to another
#Developed by :Aravindkumar ss
#Register umber :23004721
f=open(r"/content/mano1.txt","r")
a=f.read()
print(a)
b=open(r"/content/mano.txt","w+")
b.write(a)
b.seek(0)
print(b.read())
```
### OUTPUT:
![Screenshot 2023-12-30 224511](https://github.com/aravindkumar23004721/copy-file/assets/148962674/32513f72-f3d1-4800-9bcf-24fc66d91181)
![Screenshot 2023-12-30 225343](https://github.com/aravindkumar23004721/copy-file/assets/148962674/f45faf58-2251-4778-b23a-fedfe45dacf6)
![Screenshot 2023-12-30 225124](https://github.com/aravindkumar23004721/copy-file/assets/148962674/a9bfecf7-50c5-4628-bda5-c61f79c2ef9e)
### RESULT:
Thus the program is written to copy the contents from one file to another file.
