# DATE:
# EX.NO.10 Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.`
### Step 2: 
Create a file pointer and open the file which is passed in command line.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
## PROGRAM:
```python
# Program to find Command--line-arguments-to-count-word
# Developed by: MOHAN S
# Register no: 212223240094

import sys
fp=open(sys.argv[0])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()

```
### OUTPUT:
![Screenshot 2024-10-16 132557](https://github.com/user-attachments/assets/aa66c279-e89a-49cb-a33a-7c0c25e0fa6a)

![Screenshot 2024-10-16 132613](https://github.com/user-attachments/assets/2da95e60-c671-4473-a788-d225c219038f)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
