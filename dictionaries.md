# Dictionary

Here `a` is one key, `1` is value for the key `a`

```
x = {'a':1, 'b':2, 'c': 3}
```

## Iterating the dictionary
### First method 

```
for item in x:
    print (item) # here item will be having key
    print (x[item]) # This will give you the value for a key

```
Output:
```
a
1
c
3
b
2
```

### Second method
```
for item in x.items():
    print (item) #items wilbe a tuple
    print (item[0]) # Will give you the key
    print (item[1]) # will give you the value
```
Output
```
('a', 1)
a
1
('c', 3)
c
3
('b', 2)
b
2
```

### Third method
```
for key, value in x.items():
    print (key) # To get the key
    print (value) # To get the value
```
Output
```
a
1
c
3
b
2
```

### Exercise

To reverse a dictionary. Convert keys in to values & values in to keys

```
data = {'a': 1, 'b': 2, 'c': 3}
```
#### Expected output
```
result = {1: 'a', 2: 'b', 3:'c'}
```

#### Solution
Based on first method
```
result = {}
for i in data:
    key = i
    value = data[i]
    result[value] = key
print (result)
>> {1: 'a', 2: 'b', 3: 'c'}
```

Based on second method
```
result = {}
for item in data.items():
    key = item[0]
    value = item[1]
    result[value] = key
print (result)
>> {1: 'a', 2: 'b', 3: 'c'}
```
Based on the third method
```
result = {}
for key, value in data.items():
    result[value] = key
print (result)
>> {1: 'a', 2: 'b', 3: 'c'}
```
