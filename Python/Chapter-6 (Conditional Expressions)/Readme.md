# Chapter 6 – Conditional Expressions

Sometimes we want to play pubg on our phone if the day is Sunday.

Sometimes we order Ice-cream online if the day is sunny.

Sometimes we go hiking if our parents allow.

All these are decisions that depend on the condition being met.

In python programming too, we must be able to execute instructions on a condition(s) being met. This is what conditions are for!

## If else and elif in Python

If else and elif statements are a multiway decision taken by our program due to certain conditions in our code.

### Syntax:

```
if (condition1): // if condition 1 is true
print(“yes”)
elif (condition2): // if condition 2 is true
print(“No”)
else: // otherwise
print(“May be”)
```

### Code example:

```
a = 22
if (a>9):
print(“Greater”)
else:
print(“lesser”)
```

#### Quick Quiz:

Write a program to print yes when the age entered by the user is greater than or equal to 18.

#### Relational Operators

Relational operators are used to evaluate conditions inside if statements. Some examples of relational operators are:

```
= = -> equals

> = -> greater than/equal to

<=, etc.
```

#### Logical Operators

In python, logical operators operate on conditional statements. Example:

```
and -> true if both operands are true else false

or -> true if at least one operand is true else false

not -> inverts true to false and false to true
```

#### elif clause

elif in python means [else if]. If statement can be chained together with a lot of these elif statements followed by an else statement.

```
if (condition1):
#code
elif (condition 2):
#code
elif (condition 2):
#code
….
else:
#code
```

- The above ladder will stop once a condition in an if or elif is met.

### Important Notes:

- There can be any number of elif statements.
- Last else is executed only if all the conditions inside elifs fail.

# Chapter 6 – Practice Set

- Write a program to find the greatest of four numbers entered by the user.
- Write a program to find out whether a student is pass or fail if it requires a total of 40% and at least 33% in each subject to pass. Assume 3 subjects and take marks as an input from the user.
- A spam comment is defined as a text containing the following keywords:
  “make a lot of money”, “buy now”, “subscribe this”, “click this”. Write a program to detect these spams.

- Write a program to find whether a given username contains less than 10 characters or not.
- Write a program that finds out whether a given name is present in a list or not.
- Write a program to calculate the grade of a student from his marks from the following scheme:
  90-100 Ex
  80-90 A
  70-80 B
  60-70 C
  50-60 D
  <50 F
- Write a program to find out whether a given post is talking about “Harry” or not.
