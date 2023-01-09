# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
creating a function
### Step 2:
Get the list which need to be circulated.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Printing the circulated value
## Program:y
~~~py
def circulate():
    a=eval(input())
    n=int(input())
    c=a[n:]+a[:n]
    print("After circulating the values are:",c)
~~~

## Output:
![circulating n variable](/c1.png)
![circulating got](/circulaing.png)

## Result:
Thus using python program the circulation of the value of N variable has been executed successfully.