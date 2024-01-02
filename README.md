# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
## Step 1:
Import sys module
## Step 2:
Using sys module,open a file with read mode
## Step 3:
Read the file and split the file and store it in the variable
## Step 4:
Print the length of the variable
## Step 5:
End the program
## PROGRAM:
```
# To write a program to count the contents of the file using command line arguments.
# Developed by: STANLEY S
# Reference number: 23014354
f = open('/content/drive/MyDrive/Colab Notebooks/Summa.txt','r')

import sys
n = open(sys.argv[0],'r')
a = f.read().split()
print(len(a))
```
### OUTPUT:
![image](https://github.com/STANLEY-13/command-line-arguments-to-count-word/assets/148198816/f4cbfc95-1e0d-437a-adbd-64b041c657c1)
![WhatsApp Image 2024-01-02 at 1 16 35 PM](https://github.com/STANLEY-13/command-line-arguments-to-count-word/assets/148198816/50e92e67-8d04-4f12-ad9b-430c46b203d3)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
