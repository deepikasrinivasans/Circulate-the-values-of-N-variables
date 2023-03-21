# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
define the function circulate
### Step 2:
To calculate, enter the formula.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4:
Using the slicing concept rotate the list
### Step 5:
print the values after circulating.
### Step 6: 
end the program.

## Program:
```
#Program to circulate N values.
#Developed by: Deepika.S
#RegisterNumber: 212222230028
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
```
## Output:
![ex2](https://user-images.githubusercontent.com/119393935/226612593-4a7c0116-8e1e-4806-801f-a3cf530bb800.png)

## Result:
Thus, a python program to circulate the n variables using function concept is
successfully executed and displayed.
