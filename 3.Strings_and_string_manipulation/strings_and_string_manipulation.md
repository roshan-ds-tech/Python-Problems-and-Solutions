## 1 Palindrome Checker:

### Write a Python program that checks if a given string is a palindrome. A palindrome is a word, phrase, number, or other sequence of characters that reads the same forward and backward.

### Example: "radar", "level", "madam".

<br>

## Solution:

```python
rosh = input("Eter the string: ")
darsh = rosh[::-1]
if rosh==darsh:
    print("Palindrome")
else:
    print("Not Palindrome")
```

<br>

## 2 String Reversal:

### Write a Python program that takes a string input from the user and prints its reverse.

### Example: Input: "hello", Output: "olleh".

<br>

## Solution:

```python
rosh = input("Eter the string: ")
darsh = rosh[::-1]
print(darsh)
```

<br>

## 3 String Concatenation:

### Write a Python program that takes two strings as input from the user and concatenates them.

### Example: Input: "Hello", "World", Output: "HelloWorld".

<br>

## Solution:

```python
rosh = input("Enter the first string: ")
darsh = input("Enter the second string: ")
print(rosh+darsh)
```

<br>

## 4 String Length:

### Write a Python program that takes a string input from the user and prints its length.

### Example: Input: "Python", Output: Length: 6.

<br>

## Solution:

```python
rosh = input("Enter the string: ")
print(len(rosh))
```

<br>

## 5 Character Frequency Counter:

### Write a Python program that takes a string input from the user and counts the frequency of each character in the string.

### Example: Input: "hello", Output: {'h': 1, 'e': 1, 'l': 2, 'o': 1}.

<br>

## Solution:
```python
from collections import Counter
rosh = input("Enter the string: ")
print(Counter(rosh))
```

<br>

## 6 String Case Conversion:

### Write a Python program that takes a string input from the user and converts it to uppercase or lowercase.

### Example: Input: "Hello", Output: "hello".

<br>

## Solution:
```python
rosh = input("Enter a string: ")
darsh = rosh.capitalize()
melb = rosh.lower()
if rosh == darsh:
    print(melb)
else: 
    print(darsh)
```

<br>

## 7 String Rotation:

### Write a Python program that checks if one string is a rotation of another string.

### Example: Input: "abcd", "cdab", Output: True (because "cdab" is a rotation of "abcd").

<br>

## Solution:
```python
rosh = list(input("Enter a string: "))
darsh = list(input("Enter a string: "))
rosh.sort()
darsh.sort()
if rosh==darsh:
    print(True)
else:
    print(False)
```

## 8 Substring Search:

### Write a Python program that takes two strings as input from the user and checks if the second string is a substring of the first string.

### Example: Input: "hello world", "world", Output: True.

<br>

## Solution:
```python
def substring_search(x,y):
    return y in  x


rosh = input("Enter the first string: ")
darsh = input("ENter the second string: ")
print(substring_search(rosh,darsh))
```

<br>

## 9 Anagram Checker:

### Write a Python program that checks if two strings are anagrams of each other. An anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.

### Example: Input: "listen", "silent", Output: True.

<br>

## Solution:
```python
def anagram_checker(s1,s2):
    return sorted(s1)==sorted(s2)

rosh = input("Enter the first string: ")
darsh = input("Enter the second string: ")
print(anagram_checker(rosh,darsh))
```