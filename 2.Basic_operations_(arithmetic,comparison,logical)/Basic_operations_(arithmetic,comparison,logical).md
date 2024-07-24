## 1 Arithmetic Operations:

### Write a Python program that takes two numbers as input from the user and performs arithmetic operations:

- #### Addition
- #### Subtraction
- #### Multiplication
- #### Division (handle division by zero)
- #### Modulus (remainder of division)
- #### Exponentiation

<br>

### Solution: 

```python
rosh = int(input("Enter the first number: "))
darsh = int(input("Enter the second number: "))

#Addition
print(rosh+darsh)

#Subtraction
print(rosh-darsh)

#Multiplication
print(rosh*darsh)

#Division
print(rosh/darsh)

#Modulous
print(rosh%darsh)

#exponential
print(rosh**darsh)
```

<br>

## 2 Area and Perimeter Calculator:

### Write a Python program that calculates the area and perimeter of a rectangle. Prompt the user to enter the length and width of the rectangle as input.

<br>

### Solution:

```python
rosh = int(input("Enter the length of the rectangle: "))
darsh = int(input("Enter the width of the rectangle: "))

#Area of the rectangle: A=l×w
print("Area of the rectangle is: ",rosh*darsh)

#perimeter of the rectangle: P=2(l+w)
print("Perimeter of the rectangle is: ",2*(rosh+darsh))
```

<br>

## 3 Quadratic Equation Solver:

### Write a Python program that solves a quadratic equation of the form ax^2 + bx + c = 0. Prompt the user to enter the values of coefficients a, b, and c, and calculate the roots of the equation using the quadratic formula.

<br>

### Solution:

```python
import cmath
darsh = input("Enter the valye of a,b,c for quadratic equation: ")
a,b,c= darsh.split()
a = int(a)
b = int(b)
c = int(c)

rosh = cmath.sqrt(b**2 - 4*a*c)
melb = -b + rosh
abl = -b - rosh

print(melb/(2*a))
print(abl/(2*a))
```

<br>

## 4 Simple Interest Calculator:

### Write a Python program that calculates the simple interest based on the principal amount, rate of interest, and time period. Prompt the user to enter these values and compute the simple interest.

<br>

### Solution:

```python
rosh = int(input("Enter the principal amount: "))
darsh = int(input("Enter the rate of interest: "))
melb = int(input("Enter the time period: "))
print("The simple interest is (SI): ",(rosh*darsh*melb)/100)
```

<br>

## 5 Distance Calculator:

### Write a Python program that calculates the distance between two points on the coordinate plane using the distance formula. Prompt the user to enter the coordinates of two points (x1, y1) and (x2, y2), then compute and display the distance between them.

<br>

### Solution:

```python
import math
rosh = input("Enter the values of first point (x1,y1): ")
darsh = input("Enter the values of second point (x2,y2): ")

#splitting first input
a,b = rosh.split()
a = int(a)
b = int(b)

#splitting second input
c,d = darsh.split()
c = int(c)
d = int(d)

#First point
fpoint = (c-a)**2

#second point
spoint = (d-b)**2

add = fpoint+spoint
square = math.sqrt(add)
print(square)
```

<br>

## 6 Factorial Calculator:

### Write a Python program that calculates the factorial of a given number. Prompt the user to enter a positive integer n, then calculate and display the factorial of n.

<br>

### Solution:

```python
import math
rosh  = int(input("Enter the number to find the factorial: "))
darsh = math.factorial(rosh)
print(darsh)
```

<br>

## 7 Palindrome Checker:

### Write a Python program that checks if a given string is a palindrome. Prompt the user to enter a string, then determine if it is a palindrome (reads the same forwards and backwards).

<br>

### Solution:

```python
rosh  = input("Enter the string: ")
att = rosh.lower()
darsh = list(att)
melb = darsh[::-1]
 

#checking for palindrome
if darsh==melb:
    print("Palindrome")
else:
    print("Not Plaindrome")
```

<br>

## 8 Simple Calculator:

### Write a Python program that simulates a simple calculator. Prompt the user to enter two numbers and choose an operation (addition, subtraction, multiplication, division). Perform the selected operation on the two numbers and display the result.


<br>

### Solution:

```python
rosh = int(input("Enter the first number: "))
att = int(input("Enter the second the number: "))
darsh = input("Enter the operation in symbols: ")

if darsh=="+":
    print(rosh+att)
elif darsh=="-":
    print(rosh-att)
elif darsh=="*":
    print(rosh*att)
else:
    print(rosh//att)
```