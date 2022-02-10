# Chapter 5 – Dictionary and Sets

Dictionary is a collection of key-value pairs.

Syntax:

```
''' a = {“key”: “value”,
“harry”: “code”,
“marks” : “100”,
“list”: [1,2,9]}
a[“key”] # Prints value
a[“list”] # Prints [1,2,9] '''
```

### Properties of Python Dictionaries

- It is unordered
- It is mutable
- It is indexed
- It cannot contain duplicate keys

### Dictionary Methods

Consider the following dictionary,

```
a = {“name”: “Harry”,
“from”: “India”,
“marks”: [92,98,96]}
```

- items() : returns a list of (key,value) tuple.
- keys() : returns a list containing dictionary’s keys.
- update({“friend”: “Sam”}) : updates the dictionary with supplied key-value pairs.
- get(“name”) : returns the value of the specified keys (and value is returned e.g., “Harry” is returned here)
  More methods are available on docs.python.org

### Sets in Python

Set is a collection of non-repetitive elements.

```
S= Set() # No repetition allowed!

S.add(1)

S.add(2)
```

# or Set = {1,2}

If you are a programming beginner without much knowledge of mathematical operations on sets, you can simply look at sets in python as data types containing unique values.

#### Properties of Sets

- Sets are unordered # Elements order doesn’t matter
- Sets are un-indexed # Cannot access elements by index
- There is no way to change items in sets
- Sets cannot contain duplicate values
  Operations on Sets
  Consider the following set:

```
S = {1,8,2,3}
```

- Len(s) : Returns 4, the length of the set
- remove(8) : Updates the set S and removes 8 from S
- pop() : Removes an arbitrary element from the set and returns the element removed.
- clear() : Empties the set S
- union({8, 11}) : Returns a new set with all items from both sets. #{1,8,2,3,11}
- intersection({8, 11}) : Returns a set which contains only items in both sets. #{8}

## Chapter 5 – Practice Set

- Write a program to create a dictionary of Hindi words with values as their English translation. Provide the user with an option to look it up!
- Write a program to input eight numbers from the user and display all the unique numbers (once).
- Can we have a set with 18(int) and “18”(str) as a value in it?
- What will be the length of the following set S:

```
S = Set()

S.add(20)

S.add(20.0)

S.add(“20”)
```

What will be the length of S after the above operations?

- S = {}, what is the type of S?
- Create an empty dictionary. Allow 4 friends to enter their favorite language as values and use keys as their names. Assume that the names are unique.
- If the names of 2 friends are the same; what will happen to the program in Program 6?
- If the languages of two friends are the same; what will happen to the program in Program 6?
- Can you change the values inside a list which is contained in set S

```
S = {8, 7, 12, “Harry”, [1, 2]}
```
