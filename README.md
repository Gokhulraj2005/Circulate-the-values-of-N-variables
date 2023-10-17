# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user 
using the eval(input()) 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using concatenation operation display the entire rotated list 
### Step 6: 
stop the program
## Program:
```
#Program to circulate N values.
#Developed by: GOKHULRAJ V
#RegisterNumber:23004889
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![output](https://github.com/Gokhulraj2005/Circulate-the-values-of-N-variables/assets/138849253/7e7dc140-5b13-460a-aa99-2af0c7b52c26)

## Result:
The above porogram is executed successfully.
