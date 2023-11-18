# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get n variables from the user
### Step 2: 
Get input
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Print the value it would be interchanged
### Step 6: 
End the program
## Program:
#Program to circulate N values.
#Developed by:Dhivya dharshini.B 
#RegisterNumber:23008727
def circulate():
   list1=eval(input())
   n=int(input())
   result=list1[n:]+list1[:n]
   print("After circulating the values are:",result)
## Output:
![OUTPUT](/Screenshot%202023-11-18%20113910.png)

## Result:
Thus the circulation of n variables sucessfully executed
