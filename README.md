# Word-count
AIM:
To write a python program for getting the word count from a text.

EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

ALGORITHM:
Step 1:
Open the file in read mode and handle it in text mode

Step 2:
Read the text using read() function.

Step 3:
Split the text using space separator .we assume that words in a sentence are separated by a space character.

Step 4:
The length of the split list should equal the numbe of words in the text file.

Step 5:
You can refine the count by clearing the string prior t splitting or validatting the words after splitting

Step 6:
End the program

PROGRAM:
##program to find the wword count.
##developed by:MOHAMED SULTHAN A
## register number:23004839

num_words =0
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
OUTPUT:
![image](https://github.com/Sulthan06042007/Word-count/assets/144980103/daf7d824-ae68-4b9c-a82a-b347f6d86055)

## RESULT:
Thus the program is written to find the word count from a text.
