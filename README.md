# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Import numpy
### Step 2: 
Create function 
### Step 3: 
Define the input type

### Step 4: 
Get the value from the user for the number of rotation


### Step 5: 
Using the slicing concept rotate the list
### Step 6: 
Print the output
## Program:
~~~
import numpy as np
def circulate():
    num1=[10,20,30,40,50,60]
    n=int(input())
    num1=num1[n:]+num1[:n]
    print("After circulating the values are:",num1)
~~~    
## Output:
![Github logo](circulate.png)

## Result:
Thus the values are circulated.
