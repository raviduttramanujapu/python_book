#  Excercises

## List

### Create bar chart

Given a list of values, create a horizontal bar chart using `=` symbol.

```
data = [10, 20, 30, 40, 50]
max_bar_width = 50

for i in data:
    scaled_num = int(i/max(data)  * max_bar_width) + 1
    print ('=' * scaled_num)
===========
=====================
===============================
=========================================
===================================================
```

## Functions
### Compare two list
Write a function which takes two list as inputs and compares the elements in the lists. Return `True` if the list elements are identical, else return `False`
```
def compare_lists(a, b):
    '''
    Compares two list
    '''
    for (x,y) in zip(a,b):
        if x == y:
            pass
        else:
            return False
    return True

a = [1, 2, 5]
b = [1, 4, 5]
print (compare_lists(a, b))
>> False
```

## Dictionary
### Reverse a dictionary
Write a code to reverse a dictionary. Keys should become the values and values should turn in to keys.
```
data = {'a': 1, 'b': 2, 'c': 3}
result = {}

for key, value in data.items():
    result[value] = key
print ('Input:', data)
print ('Output:', result)
>> Input: {'a': 1, 'b': 2, 'c': 3}
>> Output: {1: 'a', 2: 'b', 3: 'c'}
```