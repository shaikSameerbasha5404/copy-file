# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.
### Step 2: 
 Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.
## PROGRAM:
```python
# Developed By: shaik sameer basha
# Reference number: 22004926
with open("copy.txt", "r") as firstfile:
    with open("text.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:
![5c 1](https://user-images.githubusercontent.com/118707756/214851843-041d52d3-72ba-44fe-ab84-5869723793bb.jpg)
![5c 2](https://user-images.githubusercontent.com/118707756/214851942-33049d7d-7def-4ed3-9a34-0056b1fb7142.jpg)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
