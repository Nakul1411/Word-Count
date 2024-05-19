# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Prompt the user to enter the filename and store it in the variable filename
### Step 2: 
 Initialize a variable num to 0.
### Step 3: 
Open the file using with open(filename, "r") as file: for proper file handling.
### Step 4:  
Iterate through each line in the file using for word in file:. Split each line into words: Word = word.split().
### Step 5: 
Update the word count: num = num + len(Word).
### Step 6: 
Print the total number of words in the file: print("Number of words in file:", num).
## PROGRAM:
filename=input("Enter filename:")
num=0
with open(filename,"r") as file:
    for word in file:
        Word=word.split()
        num=num+len(Word)
print("Number of words in file:",num)
### OUTPUT:
![Screenshot 2024-05-19 130813](https://github.com/Nakul1411/Word-Count/assets/138849780/14685c7e-5c63-4c94-9a81-91a38eb9ca20)



## RESULT:
Thus the program is written to find the word count from a text.
