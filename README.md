# Find the GCD of two numbers

## AIM:

To write a program to find the GCD of two numbers using function.

## Equipments Required:

1. Hardware – PCs

2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

1. Define a function.

2. Get the two numbers from the user.

3. Compare the two values, to find the smaller number.

4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
Program to find the gcd of two number using function.
Developed by: Amruthavarshini Gopal
RegisterNumber: 23000851 

def gcd():
    a=int(input())
    b=int(input())
    if(a>b):
        gcd=b
    else:
        gcd=a
    for c in range(1,gcd+1):
        if(a%c==0 and b%c==0):
            hcf=c
    print("GCD of two numbers is:",hcf)
```

## Output:

![gcd of two number](gcd.png)

![Alt text](gcd1.png)

## Result:

Thus the program to find the GCD of two numbers is written and verified using python programming.
