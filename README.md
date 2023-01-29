# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
Anaconda - Python 3.7
ALGORITHM:
#Step 1: Import the sys module.

Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

Step 3:
Read the file using read() method

Step 4:
Use split() method to split the file content into words.

Step 5:
Use len() to find the total words.

Step 6:
Run the program to determine the number of words in the file created.
## PROGRAM:
~~~
'''
#Developed by: Lakshman reddy
#RegisterNumber: 22004423
'''
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)

~~~
### OUTPUT:
TextFile:
![image](https://user-images.githubusercontent.com/118707265/215315208-2fbb8fec-eacc-43fa-8185-41c50ac23324.png)

Pythonflie:
![image](https://user-images.githubusercontent.com/118707265/215315231-514ac3ac-7792-4f39-8141-f1f4d5b626d9.png)
![image](https://user-images.githubusercontent.com/118707265/215315239-57a6e7a0-53be-4130-980a-22829e00c4b9.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
