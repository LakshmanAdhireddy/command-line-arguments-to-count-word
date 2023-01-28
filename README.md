# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import the sys module

Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

Step 3:
Read the file using read() method.

Step 4:
Use split() method to split the file content into words.

Step 5:
Use len() to find the total words.

Step 6:
Run the program to determine the number of words in the file created.
## PROGRAM:
~~~
#Python program for getting the word count from the contents of a file using command line arguments.
#Developed by:Lakshman reddy
#RegisterNumber: 22004423
import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)

~~~
### OUTPUT:
![215007347-aca69f43-cfff-4ea8-83d6-e51538cf06cc](https://user-images.githubusercontent.com/118707265/215252523-247017b0-dfb8-47e9-8237-d06f9e676b1d.png)
![214853117-e07ba12c-ccbd-4383-822b-7f309869b434](https://user-images.githubusercontent.com/118707265/215252534-c4f188a3-1c1e-4afd-9d3f-cab3894d2062.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
