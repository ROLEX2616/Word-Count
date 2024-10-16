## DATE:
## Ex No 9 - Word-Count
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
# Developed by: HAREESH R
# Register number: 212223230068
num=0
with open ("sam.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words in the file is",num)








```
### OUTPUT:
![Screenshot 2024-10-16 113130](https://github.com/user-attachments/assets/4ea0f2e1-d7fe-4d48-85d4-b6bc92ba3fb9)


![Screenshot 2024-10-16 113052](https://github.com/user-attachments/assets/533cd3a5-7a20-4a33-b29a-6d48d968b104)

## RESULT:
Thus the program is written to find the word count from a text.
