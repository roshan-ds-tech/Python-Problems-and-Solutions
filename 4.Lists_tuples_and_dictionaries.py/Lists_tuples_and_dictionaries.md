## 1 List Operations-1:

### Write a Python function to remove duplicates from a list.

<br>

## Solution:
```python
def remove_duplicates(x):
    melb = set(x)
    print(melb)

rosh = [1,"rosh",3,"darsh",6,3,6,"darsh"]
remove_duplicates(rosh)
```

<br>

## List Operations-2:

### Write a Python function to reverse a list in-place (without using built-in reverse() method).

<br>

## Solution:

```python
def reverse_list(x):
    print(x[::-1])

rosh = ["rosh","darsh",3,5,7,"melb"]
reverse_list(rosh)
```

<br>

## List Operations-3:

### Write a Python function to find the second largest element in a list.

<br>

## Solution:
```python
def second_largest_element(x,y):
    print(x[1])
    print(y[1])

rosh = [1,4,6]
darsh = ["melb","darsh","rosh"]

rosh.sort(reverse=True)
darsh.sort(reverse=True)

print(rosh,darsh)

second_largest_element(rosh,darsh)
```
<br>

## 2 Tuple Operations-1:

### Write a Python program to concatenate two tuples.

<br>

## Solution:
```python
def concatenate_tuple(x,y):
    print(x+y)

rosh = ("rosh","darsh",3)
darsh = ("melb",6,8)

concatenate_tuple(rosh,darsh)
```

<br>

## Tuple Operation-2:

### Write a Python function to find the maximum and minimum elements in a tuple.

<br>

## Solution:
```python
def max_min(x,y):
    print(max(x))
    print(min(y))

rosh = ("darsh","rosh","melb")
darsh = (2,5,8)

melb = list(rosh)
melb.sort(reverse=True)
print(melb)

nib = list(darsh)
nib.sort(reverse=True)
print(nib)

max_min(rosh,darsh)
```
<br>

## Tuple Operation-3:

### Write a Python program to convert a tuple of strings into a single string.

<br>

## Solution:
```python
def tuple_string(x):
    melb = " ".join(x)
    print(melb)
    

rosh = ("Hello","welcome","to","Python!")
tuple_string(rosh)
```
<br>

## 3 Dictionary Operations-1:

### Write a Python function to merge two dictionaries.
<br>

## Solution:
```python
def merge_dictionary(x,y):
    rosh = x
    darsh = y
    rosh.update(darsh)
    print(rosh)

melb = {"one": 1, "two": 2, "three": 3}
nib = {"two": 3,"four": 4,"one": 2}

merge_dictionary(melb,nib)
```
<br>

## Dictionary Operations-2:

### Write a Python function to sort a dictionary by its values.

<br>

## Solution:
```python
def sort_dictionary():
    rosh = { "c": 3,"b": 2, "a": 1, "d": 4}
    darsh = sorted(rosh.items())
    print(darsh)

sort_dictionary()
```

<br>

## Dictionary Operations-3:

### Write a Python program to check if a given key exists in a dictionary.

<br>

## Solution:
```python
rosh = input("Enter the key: ")
dictionary = {"one": 1,"two": 2, "name": "roshan", "age": 18}

if rosh in dictionary:
    print(True) 
else:
    print(False) 
```

<br>

## 4 Combining Data Structures-1:

### Write a Python program to count the frequency of elements in a list and store the result in a dictionary.

<br>

## Solution:
```python
from collections import Counter
rosh = [1,2,3,2,3,1,5,1,6]
nib = ["roshan","darshan","melbin","supiesh","darshan","roshan","roshan","supiesh","roshan"]

melb = Counter(rosh)
supi = Counter(nib)

darsh = dict(melb)
kart = dict(supi)

print(kart)
print(darsh)
```
<br>

## Combinig Data Structures-2:

### Write a Python function to find common elements between two lists and store them in a tuple.

<br>

## Solution:
```python
def python_tuple(x,y):
    melb = set(x)
    nib = set(y)
    print(melb&nib)

rosh = [4,7,3,5,6,3,4,7,5,1]
darsh = [1,2,3,9,6,4,7,9,3]

python_tuple(rosh,darsh)
```

<br>

## Combining Data Structures-3:

### Write a Python program to create a dictionary where keys are integers from 1 to n and values are squares of the keys.

<br>

## Solution:
```python
n = 10

rosh = {i: i*i for i in range(1,n+1)}
print(rosh)
```

<br>

## 5 Advanced Problems-1:

### Write a Python program to implement a stack using a list.

<br>

## Solution:
```python
stack = []
rosh = input("Enter the first element of the stack: ")
darsh = input("Enter the second element of the stack:  ")
melb = input("Enter the third element of the stack: ")

stack.append(rosh)
stack.append(darsh)
stack.append(melb)

print(stack)
print("elements poping from the stack: ")
print(stack.pop())
print(stack.pop())
print(stack.pop())

print("final stack: ", stack)
```

<br>

## Advanced Problems-2:

### Write a Python program to implement a queue using a list.

<br>

## Solution:
```python
from collections import deque
que = deque()

rosh = input("Enter the first element of the queue: ")
darsh = input("Enter the second element of the queue:  ")
melb = input("Enter the third element of the queue: ")

que.append(rosh)
que.append(darsh)
que.append(melb)

print("Initial queue: ", que)

print("Enque: ")
que.append("supiesh")
print(que)

print("Deque: ")
print(que.popleft())
print(que.popleft())
print(que.popleft())
print(que.popleft())

print("Final queue: ",que)
```

