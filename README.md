# Learn python with good examples

There are enough free and paid materials in online to learn python. But I see that there isn't enough real time or exciting examples with which the concepts taught. In this book I am trying to explain the concepts via real-time and interesting examples.


##Introduction to Python
* Installation
    * Anaconda Server
    * Download [Link](https://www.continuum.io/downloads). 
    * Python 3.5(64bit)
    * Test the installation
* Jupyter Notebook
    * Creating notebook
    * Executing commands
    * Markdown support
* Comments
    * Single line 
    * Multi-line comment
* Data types
    * Integer
    * Float
    * Boolean
    * String

## List and For loops
* Create a list
* `len(list)`
* Indexing (show image for example)
* Slicing
* Negative indexing & Slicing
* `range()`
* ** Exercise:** Summation of a list
    * for loop using `range()`
    * Display list elements using `range()`
    * Display list elements without using `range()`
* **Exercise**: Multiply element and index
    * `enumerate` for index and elements
* Append & Extend
* List comprehension

## Functions
* Introduction
* Passing arguments in order
* Passing arguments with name to avoid order
* return many outputs
* **Excercise** Create a bar chart
* Doc Strings
* Multiple return statements
    * Inside the functions have return statements inside if and else

## Dictionary
* Introduction
* Can handle any data type. List, Nested Dictionary
* How to access an element. Compare with list
* How to access all the elements using three methods
* How to reverse a dictionary using the above three methods
* `pop`, `len`,

## Exercises
* Reverse a list
* Find unique elements
* Compare two list

## Tuples
* Syntax and Usage(to group data)
* Just comma separated values
* Parenthesis are optional
* How to access the elements
* Indexing & Slicing same as list
* `tuple.count()` to get frequency of an element
* `tuple.index()` to get the position of an element
* Compare list & tuple
* But tuple is immuatable
* Tuple with single element - Comma is mandatory
* Functions can return tuples, lists
* Packing and unpacking
* Zip Function

## Modules
* Introduction
* Types of modules:
    * Inbuilt
    * User defined module
* Module import
    * simple `import numpy`
    * Alias: `import numpy as np`
    * Import everything: `from numpy import *`
    * specific imports `from numpy import nanmax, nanmin`
* Custom module
* Accessing variables

## OS module
* `os.getcwd()`
* `os.listdir()`
* `os.chdir()`
* `0s.mkdir()`
* `os.remove()`
* `os.path.isdir()`
* **Exercise**: Remove all csv files in a folder (including the subfolders)
* **[Reference](https://people.rit.edu/blbgse/pythonNotes/os.html)**

## File I/O
* Read a CSV file
* Read line by line
* `file.seek(0)`
* ** Exercise:** Get number of rows & columns in a file
* ** Exercise:** Calculate total runs, toal matches by player
* Write results to a file

## Regular expressions