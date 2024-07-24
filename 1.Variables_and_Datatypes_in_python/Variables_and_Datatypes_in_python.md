## 1 Integer Operations: <br>

### Write a Python program that takes two integers as input from the user and performs the following operations:

- #### Addition.
- #### Subtraction.
- #### Multiplication.
- #### Division.
- #### Modulous.
- #### Exponentiation. 

<br>

### Solution:

```python
num=int(input("Enter a number: "))
num2=int(input("Enter a second number: "))
#Addition:
print("Addition: ",num+num2)

#subtraction:
print("Subtraction: ",num-num2)

#multiplication:
print("Multiplication: ",num*num2)

#Division:
print("Division: ",num/num2)

#Modulous:
print("Modulous: ",num%num2)

#Exponentiation:
print("Exponentiation: 6",num**num2)
``` 
<br>

## 2 String Manipulation:<br>

### Write a Python program that takes a string input from the user and performs the following operations:

- #### Count the number of characters in the string.
- #### Convert the string to uppercase.
- #### Convert the string to lowercase.
- #### Reverse the string.
- #### Check if the string is a palindrome.

<br>

### Solution:

```python
rosh=str(input("Enter a string: "))
#Number of characters in the string:
print("The number of characters in the string is : ",len(rosh))

#converting the string to uppercase
print(rosh.upper())

#converting the first character to uppercase
print(rosh.capitalize())

#converting the string to lowercase
print(rosh.lower())

#Reverse the string
print(rosh[::-1])

#Checking for palindrome
if rosh==rosh[::-1]:
    print("Palindrome")

else:
    (print("Not Palindrome"))
```
<br>

## 3 List Operations:<br>

### Write a Python program that performs the following operations on a list:  

- #### Create a list of integers.
- #### Append an element to the list.
- #### Remove an element from the list.
- #### Sort the list in ascending order.
- #### Find the maximum and minimum elements in the list.
- #### Calculate the sum of all elements in the list.

<br>

### Solution:

```python
rosh=[4,6,2,7,9,3]
print(rosh)

#Appending element to the list
rosh.append(1)
print(rosh)

#Removing element from the list
rosh.remove(9)
print(rosh)

#Accending order
rosh.sort()
print(rosh)
#OR
print(sorted(rosh))

#Decending order
rosh.sort(reverse=True)
print(rosh)
#OR
print(sorted(rosh,reverse=True))

#Maximum of list
print(max(rosh))

#Minimum of list
print(min(rosh))

#Sum of all elements in the list
print(sum(rosh))
```

<br>

## 4 Dictionary Operations:

### Write a Python program that performs the following operations on a dictionary:

- #### Create a dictionary of student names and their corresponding ages.
- #### Add a new student to the dictionary.
- #### Remove a student from the dictionary.
- #### Update the age of a student.
- #### Print all the keys and values in the dictionary.

<br>

### Solution:

```python 
#rosh ={ "Roshan" : 17, "Darshan" : 23, "Melbin" : 16}
rosh=dict(Roshan = 17,Darshan= 23,Melbin=16)
print(rosh)

#Adding student to the dictionary
rosh["Akash"]=18
print(rosh)

#Removing student from the dictionary
del rosh["Akash"]
print(rosh)

#Updating the age of a student
rosh["Roshan"]=20
print(rosh)

#Print all the keys and values in the dictionary.
print(rosh.keys())
print(rosh.values())
```

<br>

## 5 Set Operations:

### Write a Python program that performs the following operations on sets:

- #### Create two sets of integers.
- #### Find the union of the two sets.
- #### Find the intersection of the two sets.
- #### Find the difference between the two sets.
- #### Check if one set is a subset of the other.

<br>

### Solution:

```python
A = {4,7,3,6,9}
B = {3,9,6,0,1}

#Find the union of the two sets.
print(A|B)
print(A.union(B))

#Find the intersection of the two sets
print(A&B)
print(A.intersection(B))

#Find the difference between the two sets.
print(A-B)
print(A.difference(B))

#Find the symetric difference between the two sets
print(A^B)
print(A.symmetric_difference(B))

#Check if one set is a subset of the other.
print(A.issubset(B))
print(B.issubset(A))
```

<br>

## 6 Data Type Conversion:

### Write a Python program that takes user input as a string representing a number and converts it to:

- #### Integer
- #### Float
  
<br>

### Solution:

```python
rosh=input("Enter a string: ")

#converting to integer
darshan = int(rosh)
print(type(darshan))

# converting to float
roshan = float(rosh)
print(type(roshan))
```

<br>

## 7 Temperature Conversion:

### Write a Python program that converts temperature from Celsius to Fahrenheit and vice versa. Allow the user to choose the conversion type and input the temperature value.

<br>

### Solution:

```python
import math
rosh = float(input("Enter the temperature: "))
temp = input("Enter 'F' for fahrenheit or 'C' for celsius: ")
temp1 = temp.upper()
if temp1 == "F":
    print((rosh*1.8)+32)
else:
    print((rosh-32)*5/9)
```
<br>

## 8 BMI Calculator:

### Write a Python program that calculates the Body Mass Index (BMI) using the formula: BMI = weight(kg) / (height(m) * height(m)). Prompt the user to enter their weight in kilograms and height in meters, then calculate and display their BMI.

<br>

### Solution:
```python
rosh = int(input("Enter your weight in KG: "))
darsh = float(input("Enter your height in meters(m): "))
print(rosh/(darsh*darsh))
```