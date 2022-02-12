# Chapter 8 – Functions and Recursions

A function is a group of statements performing a specific task.

When a program gets bigger in size and its complexity grows, it gets difficult for a programmer to keep track of which piece of code is doing what!

A function can be reused by the programmer in a given program any number of times.

### Example and Syntax of a function

The syntax of a function looks as follows:

```
def func1():
print(“Hello”)
```

This function can be called any number of times, anywhere in the program.

### Function call

Whenever we want to call a function, we put the name of the function followed by parenthesis as follows:

```
func1() #This is called function call
```

### Function definition

The part containing the exact set of instructions that are executed during the function call.

#### Quick Quiz:

Write a program to greet a user with “Good day” using functions.

Types of functions in Python
There are two types of functions in Python:

1. Built-in functions #Already present in Python
2. User-defined functions #Defined by the user
   Examples of built-in function includes len(), print(), range(), etc.

The func1() function we defined is an example of a user-defined function.

### Functions with arguments

A function can accept some values it can work with. We can put these values in the parenthesis. A function can also return values as shown below:

```
def greet(name):
gr = “Hello” + name
return gr
```

```
a = greet(“Harry”) #“Harry” is passed to greet in name

# a will now contain “Hello Harry”
```

### Default Parameter Value

We can have a value as the default argument in a function.

If we specify name = “stranger” in the line containing def, this value is used when no argument is passed.

For Example:

```
def greet(name=’stranger’):
#function body
```

```
greet() #Name will be ‘stranger’ in function body(default)

greet(“Harry”) #Name will be “Harry” in function body(passed)
```

## Recursion

Recursion is a function which calls itself.

It is used to directly use a mathematical formula as a function. For example:

```
factorial(n) = n \* factorial(n-1)
```

This function can be defined as follows:

```
def factorial(n):
if i == 0 or i == 1 : #Base condition which doesn’t call the function any further
return i
else:
return n\*factorial(n-1) #Function calling itself
```

This works as follows:

The programmer needs to be extremely careful while working with recursion to ensure that the function doesn’t infinitely keep calling itself.

Recursion is sometimes the most direct way to code an algorithm.

# Chapter 8 – Practice Set

- Write a program using the function to find the greatest of three numbers.
- Write a python program using the function to convert Celsius to Fahrenheit.
- How do you prevent a python print() function to print a new line at the end?
- Write a recursive function to calculate the sum of first n natural numbers.
- Write a python function to print the first n lines of the following pattern.

```
---

\*\* #For n = 3
```

- Write a python function that converts inches to cms.
- Write a python function to remove a given word from a list and strip it at the same time.
- Write a python function to print the multiplication table of a given number.
  ### Project 1: Snake, Water, Gun Game
  We all have played snake, water gun game in our childhood. If you haven’t, google the rules of this game and write a Python program capable of playing this game with the user.
