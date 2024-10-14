# Python

### Data Types
```python
# Numeric Types
x = 5                  # Integer
y = -3                 # Negative Integer
pi = 3.14              # Float
z = 3 + 4j             # Complex number

# Sequence Types
name = "Alice"         # String
fruits = ['apple', 'banana', 'cherry']  # List
coordinates = (10.0, 20.0)  # Tuple

# Mapping Type
student = {
    'name': 'John',
    'age': 25,
    'grade': 'A'
}

# Set Types
unique_numbers = {1, 2, 3, 4, 4}  # Set
frozen_set = frozenset([1, 2, 3, 4])  # Frozenset

# Boolean Type
is_valid = True          # Boolean
is_empty = False         # Another Boolean

# Binary Types
b = bytes([50, 100, 76])  # Bytes
ba = bytearray([50, 100, 76])  # Bytearray
mv = memoryview(b'Hello')  # Memory view

# None Type
a = None                  # None
```


### Conditional
```python
x = 10
y = 15

if x > y:
    print("x is greater than y")
elif x < y:
    print("x is less than y")
else:
    print("x is equal to y")

# Combining conditions
if x > 5 and y > 10:
    print("Both x and y are greater than their respective values")

# Ternary operator
status = "x is larger" if x > y else "y is larger"
print(status)
```

### Loops
```python
# For Loop Example
print("For Loop:")
for i in range(5):  # Loop through numbers 0 to 4
    print(i)

# While Loop Example
print("\nWhile Loop:")
count = 0
while count < 5:  # Continue while count is less than 5
    print(count)
    count += 1  # Increment count

```

#### control statements (break, continue, pass)
```python
# For Loop with Control Statements
print("For Loop:")
for i in range(5):
    if i == 2:
        continue  # Skip the iteration when i is 2
    if i == 4:
        break  # Exit the loop when i is 4
    print(i)  # Print i

# While Loop with Control Statements
print("\nWhile Loop:")
count = 0
while count < 5:
    if count == 3:
        pass  # Do nothing when count is 3
    print(count)  # Print count
    count += 1  # Increment count
```


### Input

#### Input Using Map
```python
# Input: 1,2,3
arr = list(map(int, input().split(",")))  # Split by comma and convert to list of integers
print(arr)  # Output: [1, 2, 3]
```

#### Input using List comprehension
```python
# Input: 1,2,3
arr = [int(i) for i in input().split(',')]
print(arr)  # Output: [1, 2, 3]
```

### Iterating Over list

#### Using for loop
```python
arr = [1, 2, 3, 4, 5]

for i in arr:
    print(i)
```

#### Using enumerate()
```python
arr = ['a', 'b', 'c', 'd']

for index, value in enumerate(arr):
    print(f'Index: {index}, Value: {value}')
```


### List methods
```python
arr.append(4)        # Add an element
arr.insert(1, 10)    # Add at a particular index
arr[0]               # Access an element
arr[0] = 5           # Change an item
arr.remove(2)        # Remove an item by value
arr.pop(0)           # Remove an item by index
arr.clear()          # Remove all items
len(arr)             # Length of the list
arr.count(4)         # Count occurrences of an element
4 in arr             # Check if exists

print(arr)           # Print the list
arr.sort()           # Sort the list
arr.reverse()        # Reverse the list
```


### Dictionary methods
```python
d['a'] = 1                # Add an item
d.get('a')                # Access a value
d['a'] = 2                # Change an item
d.pop('a')                # Remove an item by key
d.clear()                 # Remove all items
len(d)                    # Length of the dictionary
'a' in d                  # Check if key exists

print(d)                  # Print the dictionary
d.update({'b': 2})        # Add multiple items
d.keys()                  # Get all keys
d.values()                # Get all values
d.items()                 # Get all key-value pairs
```


### String methods
```python
s = "  Hello World  "

s.lower()                # Convert to lowercase: "  hello world  "
s.upper()                # Convert to uppercase: "  HELLO WORLD  "
s.strip()                # Remove leading and trailing whitespace: "Hello World"
s.split()                # Split into a list: ["Hello", "World"]
s.join(["Hello", "World"])  # Join list with space: "Hello World"
s.replace("World", "Python")  # Replace substring: "  Hello Python  "
s.find("e")              # Find index of substring: 1
s.rfind("o")             # Find last index of substring: 7
s.index("o")             # Find index of substring: 4
s.count("l")             # Count occurrences of substring: 3
s.startswith("  He")     # Check if starts with substring: True
s.endswith("ld  ")        # Check if ends with substring: True
s.isdigit()              # Check if all characters are digits: False
s.isalpha()              # Check if all characters are alphabetic: False
s.isalnum()              # Check if all characters are alphanumeric: False
s.islower()              # Check if all characters are lowercase: False
s.isupper()              # Check if all characters are uppercase: False
s.swapcase()             # Swap case of characters: "  hELLO wORLD  "
s.capitalize()           # Capitalize first character: "  hello world  "
s.title()                # Title case: "  Hello World  "
```





