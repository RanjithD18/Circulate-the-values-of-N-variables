# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Define the function
### Step 2: 
Get the value from the user for the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the circulated list
### Step 6: 
End the program

## Program:
#Program to circulate N values.

#Developed by: Ranjith D

#RegisterNumber: 21500662

def circulate():
    
    num=[10,20,30,40,50,60]
    
    n=int(input())
    
    cir=num[n:]+num[:n]
    
    print("After circulating the values are:",cir)

## Output:
![output](https://github.com/RanjithD18/Circulate-the-values-of-N-variables/blob/main/Screenshot%20(9).png?raw=true)
## Result:
Circulating the n variables using function concept are successfully executed
