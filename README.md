# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Define the function tp circulate variables.
### Step 2: 
Assign the given values in a list.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Assign a variable for the new list after slicing and print the variable.
### Step 6:
End of the program.
## Program:
```python
#Program to circulate N values.
#Developed by:M.D.Harini
#RegisterNumber:22001980
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are: {}".format(a, n))
```
## Output:
![n variables1](https://user-images.githubusercontent.com/113497680/190848352-64012351-86fc-4179-9d65-925a62486464.png)





## Result:
Thus the circulate n variables are successfully executed



