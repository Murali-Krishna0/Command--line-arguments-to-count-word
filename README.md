# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
```
Step 1:
Import numpy as np

Step 2:
Enter the input values

Step 3:
Write python program for getting the word count from the contents of a file using command line arguments

Step 4:
Run the program

Step 5:
Input the values

Step 6:
End the program
```

## PROGRAM:
```
#program to find the number of words in a text file
#Developed by : MURALI KRISHNA S #Register number :212223230129

import sys
count=0
with open(sys.argv[1],'r') as f1:
     for i in fp:
        words=i.split()
        count+=len(words)
print("word count  in file is",count)
```


### OUTPUT:
![image](https://github.com/Murali-Krishna0/Command--line-arguments-to-count-word/assets/149054535/3333d81b-ae2f-4587-bd4e-03db85163747)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
