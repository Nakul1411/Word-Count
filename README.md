# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
step 1:
To write a python program for getting the word count from a text file

Step 2:
Open the required file by using the function "with".

Step 3:
Then use the laptop to assign the i value in the file.

Step 4:
Using split function to spilt the words

Step 5:
Finding the given length of the words by using len() fuction.

Step 6:
Calling the function and Printing the number of words.
## PROGRAM:
num=0
with open("nakul.txt","r")as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
### OUTPUT:
![Screenshot 2024-05-21 145128](https://github.com/Nakul1411/Word-Count/assets/138849780/ae4ffa4b-d897-4c44-b7f9-9f6633f1390e)

## RESULT:
Thus the program is written to find the word count from a text.
