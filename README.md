# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file

### Step 2: 
Open the required file by using the function "with".
 
### Step 3: 
Then use the laptop to assign the i value in the file.

### Step 4:
  Using split function to spilt the words

### Step 5: 
Finding the given length of the words by using len() fuction.

### Step 6:
 Calling the function and Printing the number of words.

## PROGRAM:
```
#Program to find the word count.
#Developed by: ALDRIN LIJO J E
#RegisterNumber: 22009215
```
```PY
num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)

```
### OUTPUT:
![1](https://user-images.githubusercontent.com/118544279/215255519-d3e9a753-f3ce-4f25-a067-0b820311be11.png)
![2](https://user-images.githubusercontent.com/118544279/215255548-de08121d-5784-4464-9f02-2ae3f421ffa4.png)

## RESULT:
Thus the program is written to find the word count from a text.
