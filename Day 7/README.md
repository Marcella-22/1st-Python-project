# Simple calculator
Description : A simple python programme that performs basic arithmetic operations.

Language : Python

How to run: Open

Code:
 ```python
def add (a, b) :
    return a+b
def subtract(a, b) :
    return a-b
def multiply (a, b) :
    return a*b
def divide (a, b) :
    if b == 0 :
        return "Error: Divison by zero"
    return a/b

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
operation = input("Enter operation (+, -, *, /): ")
if operation == "+" :
    print(f"{num1} + {num2} = {add(num1, num2)}")
elif operation == "-" :
    print(f"{num1} - {num2} = {subtract(num1, num2)}")
elif operation == "*" :
    print(f"{num1} * {num2} = {multiply(num1, num2)}")
elif operation == "/" :
    print(f"{num1} / {num2} = {divide(num1, num2)}")
```
Output :
<img width="1366" height="768" alt="Screenshot 2026-01-17 11 24 11" src="https://github.com/user-attachments/assets/d0416107-6a1c-41b8-b601-dc7d1c0883fe" />
