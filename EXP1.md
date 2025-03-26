# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
```
i.)do…while: 
def display(): 
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric(): 
while True: 
start=int(start) 
end=int(end) 
print(start,end=‘ ‘) 
if start<end: 
start+=1 
else: 
break 
else: 
print("Enter a valid positive number.") display()

ii.) while…do 
start=input("Enter a positive value for START: ") end=input("Enter 
a positive value for END: ") 
if 
start.isnumeric() 
start=int(start) 
end=int(end) 
while start<end: 
print(start) 
start+=1 
else: 
and end.isnumeric(): 
print("Enter a valid positive number.")

iii.) switch 
def switch(): 
switcher={ 
0:"even", 
1:"odd" 
} 
n=input('Enter a value for N: ') try: 
n=int(n) 
print(switcher[n%2]) 
except ValueError: 
print("Enter a valid number.") 
switch()

iv.) if else 
def compare(): 
a=input("Enter a value for A: ") 
b=input("Enter a value for B: ") 
try: 
a=int(a) 
b=int(b) 
if a>b: 
print("A is greater than") 
elif a<b: 
print("B is greater than") 
else: 
print("A is equal to B") 
except ValueError: 
print(“Enter a valid number.”)

v.) for 
def iterate(): 
string=input("Enter a string: ") for 
i in string: 
print(ord(i),end=" ") 
iterate()
```













### Output:


![Screenshot 2025-03-26 092943](https://github.com/user-attachments/assets/75eb19fe-ced9-4657-94af-fadd468d17cc)

![Screenshot 2025-03-26 093017](https://github.com/user-attachments/assets/fefa58fa-7e70-44ed-b06d-8890200b90e3)

![Screenshot 2025-03-26 093043](https://github.com/user-attachments/assets/1a5533bf-4f37-414d-a2c3-2b6bcdb3e51b)

![Screenshot 2025-03-26 093105](https://github.com/user-attachments/assets/553c593f-eec6-4ad0-aeb0-ee938589815e)

![Screenshot 2025-03-26 093131](https://github.com/user-attachments/assets/d7a0e56c-8061-4092-a840-1da7c5c83dfb)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


