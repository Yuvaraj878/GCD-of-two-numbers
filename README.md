# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Yuvaraj.S
RegisterNumber:  22008589
*/
def gcd():
    a=int(input())
    b=int(input())
    if a>b:
        small = b
    else:
        small=a
    for c in range (1,small+1):
        if (a%c==0 and b%c==0):
            hcf=c
    print("GCD of two numbers is:",hcf)
```          



## Output:
![gcd of two number](gcd.png)
file:///home/sec/GCD-of-two-numbers/GCD.png![image](https://user-images.githubusercontent.com/118622554/210133813-68d3e5d0-5111-4246-a621-f2ea1db15a20.png)




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
