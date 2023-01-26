# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Creating a function
### Step 2: 
Get the list which need to be circulated
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Printing the circulated value 
## Program:
```py
/*
Program to circulate the values of n variables in a list
Developed by: Sanjay Ragavendar
RegisterNumber:  22009286
*/
def circulate():
    a=eval(input())
    n=int(input())
    c=a[n:]+a[:n]
    print('After circulating the values are:',c)
```

## Output:
![image](https://user-images.githubusercontent.com/91368803/214847252-bca16975-86e9-4d9a-a272-e975f2438cae.png)

## Result:
Thus using python program the circulation of the value of N variable has been executed successfully.
