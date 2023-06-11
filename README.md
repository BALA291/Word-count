# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.
### Step 2:
Open the required file by using the function "with"

### Step 3:
Then use the laptop to assign the i value in the file

### Step 4:
Using split function to spilt the words

### Step 5:
Finding the given length of the words by using len() fuction.

### Step 6:
Calling the function and Printing the number of words.

## PROGRAM:
```
#Developed By: BALAMURUGAN B
#Register No: 212222230016
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of wordds:",wordslen)
```
### OUTPUT:
![5AOUTII](https://github.com/BALA291/Word-count/assets/120717501/38e14215-e479-42c9-8dd8-9567c6aab340)
![5AOUT](https://github.com/BALA291/Word-count/assets/120717501/9d20e863-bc0b-493b-bd90-240b92c47647)

## RESULT:
Thus the program is written to find the word count from a text.
