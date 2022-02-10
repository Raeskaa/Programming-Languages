# Chapter 2 – Variables and Data Types

A variable is a name given to a memory location in a program. For example

```
a=30

b=”Harry”

c=71.22
```

### Variable – Container to store a value

### Keywords – Reserved words in Python

### Identifiers – class/function/variable name

### Data Types:

Primarily there are the following data types in Python:

- Integers
- Floating point numbers
- Strings
- Booleans
- None
  Python is a fantastic language that automatically identifies the type of data for us.

```
a = 71 #Identifies a as class<int>

b = 88.44 #Identifies b as class<float>

name = “Harry” #Identifies name as class<Str>
```

Rules for defining a variable name: (Also applicable to other identifiers)

A variable name can contain alphabets, digits, and underscore.
A variable name can only start with an alphabet and underscore.
A variable can’t start with a digit.
No white space is allowed to be used inside a variable name.
Examples of few valid variable names,

Harry, harry, one8, \_akki, aakash, harry_bro, etc.

### Operators in Python

The following are some common operators in Python:

- Arithmetic Operators (+, -, \*, /, etc.)
- Assignment Operators (=, +=, -=, etc.)
- Comparison Operators (==, >=, <=, >, <, !=, etc.)
- Logical Operators (and, or, not)
  type() function and Typecasting

#### Type function is used to find the data type of a given variable in Python.

```
a = 31

type(a) #class<int>

b = “31”

type(b) #class<str>

```

A number can be converted into a string and vice versa (if possible)

There are many functions to convert one data type into another.

```
Str(31) # ”31” Integer to string conversion

int(“32”) # 32 String to int conversion

float(32) #32.0 Integer to float conversion
```

… and so on

Here “31” is a string literal, and 31 is a numeric literal.

### input() function

This function allows the user to take input from the keyboard as a string.

```
a = input(“Enter name”) #if a is “harry”, the user entered harry
```

#### Note: The output of the input function is always a string even if the number is entered by the user.

Suppose if a user enters 34, then this 34 will automatically convert to “34” string literal.
