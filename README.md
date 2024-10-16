## DATE:
# EX.NO.9 Word Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0.
### Step 2: 
Open it with txt file.
### Step 3: 
Give range for i.
### Step 4:  
Then next split the words.
### Step 5: 
Count the number of words.
### Step 6: 
Giving print statement for getting output.
## PROGRAM:
```
# Word count in a Text file
# Developed by: POZHILAN V D 
# Register number: 212223240118
num=0
with open ("file.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words in the file is",num)

```
### OUTPUT:

![image](https://github.com/user-attachments/assets/3916aa35-93cb-494f-8852-600e7a02624d)

![image](https://github.com/user-attachments/assets/d90cb77c-994e-40f5-ade3-2de393dda92d)

![image](https://github.com/user-attachments/assets/abd11a9c-e31a-4e93-8057-1e6e26024f1b)

## RESULT:
Thus the program is written to find the word count from a text.
