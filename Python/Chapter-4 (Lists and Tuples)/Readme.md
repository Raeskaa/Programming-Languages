# Chapter 4 – Lists and Tuples

Python Lists are containers to store a set of values of any data type.

```
friends = [‘Apple’, ‘Akash’, ‘Rohan’, 7, False]
```

The list can contain different types of elements such as int, float, string, Boolean, etc. Above list is a collection of different types of elements.

### List Indexing

A list can be index just like a string.

```
L1 = [7, 9, ‘harry’]

L1[0] – 7

L1[1] – 9

L1[70] – Error

L1[0:2] – [7,9] (This is known as List Slicing)
```

### List Methods

Consider the following list:

```
L1 = [1, 8, 7, 2, 21, 15]
```

- sort() – updates the list to [1,2,7,8,15,21]
- reverse() – updates the list to [15,21,2,7,8,1]
- append(8) – adds 8 at the end of the list
- insert(3,8) – This will add 8 at 3 index
- pop(2) – It will delete the element at index 2 and return its value
- remove(21) – It will remove 21 from the last

### Tuples in Python:

A tuple is an immutable (can’t change or modified) data type in Python.

```
a = () #It is an example of empty tuple

a = (1,) #Tuple with only one element needs a comma

a = (1, 7, 2) #Tuple with more than one element
```

Once defined, tuple elements can’t be manipulated or altered.

#### Tuple methods:

Consider the following tuple,

```
a = (1, 7, 2)
```

- count(1) – It will return the number of times 1 occurs in a.
- index(1) – It will return the index of the first occurrence of 1 in a.
