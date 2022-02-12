# Chapter 7 – Loops in Python

Sometimes we want to repeat a set of statements in our program. For instance: Print 1 to 1000

Loops make it easy for a programmer to tell the computer, which set of instructions to repeat, and how!

## Types of loops in Python

Primarily there are two types of loops in Python

- While loop

- For loop
  We will look into this one by one!

### While loop

The syntax of a while loop looks like this:

```
''' while condition:
#Body of the loop '''
```

- The block keeps executing until the condition is true/false
  In while loops, the condition is checked first. If it evaluates to true, the body of the loop is executed, otherwise not!

If the loop is entered, the process of condition check and execution is continued until the condition becomes false.

#### Quick Quiz:

Write a program to print 1 to 50 using a while loop.

An Example:

```
i = 0
while i<5:
print(“Harry”)
i = i+1
```

(Above program will print Harry 5 times)

Note: if the condition never becomes false, the loop keeps getting executed.

#### Quick Quiz:

Write a program to print the content of a list using while loops.

For loop
A for loop is used to iterate through a sequence like a list, tuple, or string (iterables)

The syntax of a for loop looks like this:

```
l = [1, 7, 8]
for item in l:
print(item)
```

(Above program will print 1, 7, and 8)

### Range function in Python

The range function in python is used to generate a sequence of numbers.

We can also specify the start, stop, and step-size as follows:

            range(start, stop, step_size)

- step size is usually not used with range()

#### An example demonstrating range() function

```
for i in range(0, 7): #range(7) can also be used
print(i) #prints 0 to 6
```

For loop with else
An optional else can be used with a for loop if the code is to be executed when the loop exhausts.

Example:

```
l = [1, 7, 8]
for item in l:
print(item)
else:
print(“Done”) #This is printed when the loop exhausts!
```

Output:

```
1

7

8

Done
```

#### The break statement

‘break’ is used to come out of the loop when encountered. It instructs the program to – Exit the loop now.

Example:

```
for i in range(0, 80):
print(i) #This will print 0, 1, 2 and 3
if i == 3:
break
```

#### The continue statement

‘continue’ is used to stop the current iteration of the loop and continue with the next one. It instructs the program to “skip this iteration.”

Example:

```
for i in range(4):
print(“printing”)
if i == 2: #if i is 2, the iteration is skipped
continue
print(i)
```

pass statement
pass is a null statement in python. It instructs to “Do nothing.”

Example:

```
l = [1, 7, 8]
for item in l:
pass #without pass, the program will throw an error
```

# Chapter 7 – Practice Set

- Write a program to print the multiplication table of a given number using for loop.
- Write a program to greet all the person names stored in a list l1 and which starts with S.

```
  l1 = [“Harry”, “Sohan”, “Sachin”, “Rahul”]
```

- Attempt problem 1 using a while loop.
- Write a program to find whether a given number is prime or not.
- Write a program to find the sum of first n natural numbers using a while loop.
- Write a program to calculate the factorial of a given number using for loop.
- Write a program to print the following star pattern.

```
\*

---

**\*** for n=3
```

Write a program to print the following star pattern:

```

- \*\*

  \*\*\* for n = 3

```

Write a program to print the following star pattern:

```
- -             #For n=3

```

- Write a program to print the multiplication table of n using for loop in reversed order.
