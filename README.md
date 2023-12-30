# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with .txt file extension
### Step 2:
Add some text in that file
### Step 3:
Create a python file
### Step 4:
Write the code to count the number of words in that file
### Step 5:
Run the program
### Step 6:
Display the output

## PROGRAM:
```python
'''#program to find the number of words in text file
#Devloped by: Vinnush Kumar L S
#RegisterNumber:23012349
'''
num=0
sample=input()
with open(sample,"r") as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
        print("The number of words are in the files is",num)
```
### OUTPUT:
![image](https://github.com/vinnush147/Word-count/assets/147139234/e4db3e07-fbf6-4011-b568-d95ca963c0a7)
![image](https://github.com/vinnush147/Word-count/assets/147139234/8ccd1a13-7737-406a-99c3-95f9ebe086a1)



## RESULT:
Thus the program is written to find the word count from a text.
