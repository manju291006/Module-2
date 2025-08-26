# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING N NATURAL NUMBERS

###  Aim
To write a Python program to print the first N natural numbers.


###  Algorithm

1. Begin the program.
2. Use input() to read the value of n (the upper limit) from the user.
3. Convert the input to an integer.
4. Display the message *"Natural Numbers are :"*.
5. Use a for loop to iterate from 1 to n (inclusive).
6. In each iteration, print the current value of i.
7. Terminate the program.


### 🧾 Program
```
n=int(input())
for i in range(1,n+1):
    if(i%2==0):
        print(i)


```

### OUTPUT
<img width="362" height="509" alt="image" src="https://github.com/user-attachments/assets/e2776371-8461-4395-b025-83cd3ac976a4" />

### RESULT
thus the program was executed successfully 








# Exp. No: 2b  
## Functions – define a function named "result" that accepts 3  values and return its  multiplication.

###  Aim
To write a Python program to define a function named result that accepts three values and returns their multiplication.

---

###  Algorithm
Start the program.

Define a function named result that accepts three parameters.

Inside the function, calculate the multiplication of the three numbers.

Return the result to the main program and display it.

Stop the program.


### 🧾 Program
```
def result(a,b,c):
    return a*b*c
a=int(input())
b=int(input())
c=int(input())
print("Multiply is",result(a,b,c))
```

### OUTPUT
<img width="663" height="267" alt="image" src="https://github.com/user-attachments/assets/fbad9c42-4ae2-475d-b2b3-cdb18739e907" />

### RESULT
Thus the program was executed successfully 







# Exp. No: 2c  
## Built-In Funtions & Lambda Function – Write a lambda function which takes z as a parameter and returns z*56 using python

###  Aim
To write a Python program to create a lambda function that takes a parameter z and returns z * 56.


###  Algorithm
Start the program.

Define a lambda function that takes one parameter z.

Use the lambda function to calculate z * 56.

Display the result.

Stop the program.

### 🧾 Program
```
z=int(input())
x=lambda z:z*56
print(x(z))

```

### OUTPUT
<img width="393" height="227" alt="image" src="https://github.com/user-attachments/assets/60fb79af-5660-4d62-957b-7c5c89fd6496" />

### RESULT
Thus the program was executed successfully 






# Exp. No: 2d  
## Looping (Patterns) – pyramid pattern of numbers

###  Aim
To read an integer n and print a centered palindromic number pyramid with n rows

###  Algorithm
Start the program.

Read the number of rows n from the user.

Use a loop to repeat steps for each row from 1 to n.

Inside the loop, first print spaces, then print numbers in increasing order, and finally print numbers in decreasing order.

Stop the program.

### 🧾 Program
```
num=int(input())
for i in range(1,num+1):
    for j in range(1,i+1):
        print(j,end=" ")
        
    print()

```


### OUTPUT

<img width="402" height="514" alt="image" src="https://github.com/user-attachments/assets/b3b75aca-3ad0-4723-ac68-d3c6749d4728" />

### RESULT
thus the program was executed successfully 






# Exp. No: 2e  
## SEB– Write a  python program to determine traffic based on the fraction of roadways covered

###  Aim
To Write a  python program to determine traffic based on the fraction of roadways covered

###  Algorithm

Start the program.

Read the number of rows n from the user.

Repeat the steps for each row i from n down to 1.

In each row, print numbers from i down to 1 separated by spaces.

Stop the program.


### 🧾 Program
```
traffic_fraction=eval(input())
if(traffic_fraction>0.5):
    print("High Traffic!")
elif(traffic_fraction>0.25 and traffic_fraction<=0.5):
    print("Medium Traffic")
elif(traffic_fraction<0.25):
    print("Low Traffic")

```


### OUTPUT

<img width="471" height="217" alt="image" src="https://github.com/user-attachments/assets/5f86800e-deec-4e2d-a367-56ad106e6687" />

### RESULT
Thus the program was executed successfully 
