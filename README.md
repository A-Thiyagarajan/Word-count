# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0

### Step 2:
open it with txt file

### Step 3:
Give range for i

### Step 4:
Then nxt split the words

### Step 5:
count the number of words

### Step 6:
Giving print statement for getting output.

## PROGRAM:
```
# Program to count the no. of words in a file.
# Developed by THIYAGARAJAN A
# Reg.no: 212222240110
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
```



### OUTPUT:
![NoOfWords](https://github.com/A-Thiyagarajan/Word-count/assets/118707693/7e0e2bd6-186c-47d3-bdf9-aa529f3b737e)



## RESULT:
Thus the program is written to find the word count from a text.
