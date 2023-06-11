# Word-count

## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
Open file in read mode.

### Step 2: 
Read the text using read funcion.

### Step 3: 
Using split() function to split the words in the txt file and count it.

### Step 4:  
The length of the split list should be equal to the number of words in the text file.

### Step 5: 
Now give print().

### Step 6: 
Number of words in the txt file is displayed as the output.

## PROGRAM:
```
Developed By: Sivaramakrishnan B
Register No: 212222110044

num_words =0
with open('python.py','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={0}".format(num_words))

```

### OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/Word-count/assets/119476322/ae6370fc-fcf5-4a4d-8389-2364186e90c4)

## RESULT:
Thus the program is written to find the word count from a text.
