# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function.
### Step 2: 
Get the variables from user to enter inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
After rotating the variables, store the rotated variables in a seperate list
### Step 6: 
At last, print the list of rotated variables
## Program:
```
#Program to circulate N values.
#Developed by: 
#RegisterNumber:
def circulate():
    l = eval(input())
    n = int(input())
    l = l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![image](https://github.com/Darkwebnew/Circulate-the-values-of-N-variables/assets/143114486/d4959aa9-5b04-4cd4-ad01-1df1d91c520a)
## Result:
Thus the python program to circulate the n variable using function concept is successfully executed.
