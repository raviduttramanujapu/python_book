#  Excercises

## List

### Exercise 1

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
