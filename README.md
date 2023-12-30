# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2:
Define a function get_word_count(file_path) to calculate the word count in the file.
### Step 3:
Check if the script is being run as the main program
### Step 4:
Check if the correct number of command-line arguments (i.e., 2) is provided.
### Step 5:
Get the file path from the command-line argument
### Step 6:
Print the word count if it is not None.
### Step 7:
End the program
## PROGRAM:
```python
Program for getting the word count using command line arguments.
Developed by:ARAVIND KUMAR SS 
Register number: 23004721
import sys
def get_word_count(file_path):
    try:
        with open(file_path, 'r') as file:
            content = file.read()
            word_count = len(content.split())
            return word_count
    except FileNotFoundError:
        print(f"Error: File '{file_path}' not found.")
        return None
if name == "main":
    if len(sys.argv) != 2:
        print("Usage: python word_count.py <file_path>")
        sys.exit(1)
    file_path = sys.argv[1]
    word_count = get_word_count(file_path)
    if word_count is not None:
        print(f"Word count in '{file_path}': {word_count}")
```
### OUTPUT:
![python](https://github.com/aravindkumar23004721/copy-file/assets/148962674/4824ec51-89c8-48c6-8b45-4b48e7653a7f)
![python 1](https://github.com/aravindkumar23004721/copy-file/assets/148962674/55f8cb0f-23e9-4912-9da2-db1e2ddfe9f3)
![python 2](https://github.com/aravindkumar23004721/copy-file/assets/148962674/3aa954be-1fca-49b1-aec9-60e4ce2e8e6e)
![python 3](https://github.com/aravindkumar23004721/copy-file/assets/148962674/7213ce37-0ca6-4449-a8d2-1ae8ad8caecd)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
