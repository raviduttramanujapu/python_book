## Excercises

### Example 1: Compare two list
Write a function which takes two list as inputs and compares the list. Return `True` if the list are identical, else return `False`
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