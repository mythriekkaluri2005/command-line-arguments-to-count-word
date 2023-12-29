# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
 Open the file with sys.argv[1]
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words
## PROGRAM:
```
'''
Program for getting the word count from the contents of a file using command line arguments
Developed by: Ekkaluri Mythri
RegisterNumber: 23003922
'''
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![Screenshot 2023-12-29 103903](https://github.com/mythriekkaluri2005/command-line-arguments-to-count-word/assets/150231422/b4974d27-2349-4d5b-91fa-961d215b2f1a)
![Screenshot 2023-12-29 103920](https://github.com/mythriekkaluri2005/command-line-arguments-to-count-word/assets/150231422/dd99c457-a1b3-4102-a96b-81101e7e16dc)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
