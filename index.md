# PYTHON!

[Install Python Here](https://www.python.org/downloads/)

## Table of Contents
1. [Your First Python Program](https://ssloke420.github.io/py/#your-first-python-program)
2. [Python Variables](https://ssloke420.github.io/py/#python-variables)
3. [Python Comments](https://ssloke420.github.io/py/#python-comments)
4. [Python Data Types](https://ssloke420.github.io/py/#python-data-types)
5. [Python Operators](https://ssloke420.github.io/py/#python-operators)
6. [Python Arrays](https://ssloke420.github.io/py/#python-arrays)
## Your First Python Program
For your first Python program, we will be creating a hello world program, which is a popular first step in learning a new language.
Enter this code into your python file:
```python
print("Hello World!")
```
This code outputs:
```
Hello World
```
The print statement is how we output text in Python. You must surround the text in quotes, if you are not using a variable. Numbers do not need quotes.

```python
print("I am 12 years old")
print(12)
```
------------------------------------------------------------------------------------------------------

## Python Variables
Variables are storage containers for information. You use the '=' operator to assign a value to one. You can store numbers, strings, and other datatypes in them.

```python
name = "Billy"
age = 15
print(name)
print(age)
```
This outputs the following:
```
Billy
15
```
Notice that we do not use quotes when using a variable name.

-------------------------------------------------------------------------------------------------------------

## Python Comments
Comments are text in Python that the computer ignores. Comments are defined by a #.
```python
# The computer ignores me.
print("This text is not ignored") #This is also ignored
```

--------------------------------------------------------------------------------------------------------------

## Python Data Types

There are many data types in Python. The most common ones are floating point values, integers, booleans, and strings.
```python
myFloat = 3.14 #Decimal Values
myInt = 1207 #Integer Values
myBool = True #True or False
myStr = "Bob" #Text
```
### Data Type Conversion

You can convert types where applicable.

```python
pi = float("3.14") #This works.
pi = float("Three point one four.") #This does not work.
truth = bool("True")
age = int("10")
```
Remember, if you try to convert invalidly, you will get an error.

------------------------------------------------------------------------------------------------------------------------------
## Python Operators

### Python Math Operators

| Operator | What it does | Example |
| -------- | ------------| -------- |
|    +     | Addition | add = 1 + 1 |
|    -     | Subtraction | sub = 10 - 8 |
|    *     | Multiplication | mult = 6 * 9 |
|    /     | Division | div = 80 / 10 |
|    **    |  Exponents | exp = 2 ** 5 |
|    %     |  Modulus  | mod = 10 % 2  |
|   //      | Floor Division | fld = 100 // 9 |

To assign a value after performing a operation, you can use any of the above opertaors with an equals sign after it.

```python
n = 1
n += 1
print(n) #Outputs 2
```
### Python Boolean Operators
```python
print(1 > 5) # Outputs False
print(1 == 1) # Outputs True
print("Monkey" == "Monkey") # Outputs True
print(5 >= 5) #Outputs True
print(1 > 2 and 2 == 2) # Outputs False, because only one condition is met.
print(1 > 2 or 2  == 2) # Outputs True, because at least one condition is met
print(not 1 == 1) # Reverts the result to False
```
There are many other operators, but these are some of the most basic ones.

-------------------------------------------------------------------------------------------------------------
## Python Arrays
There are 3 different types of "arrays" (they are not really arrays) in Python. There are lists, sets and tuples.
Lists are normal ordered values. Tuples are not changeable. Sets can only have one of each value, and are not ordered.
You can index lists by putting the index you want to access in square brackets after the name of the array variable.
Remember, the index starts at 0 for the first variable.
```python
myList = [1, 2, 3, 4, 720]
myTuple = (1, 2)
mySet = {5, 8 , 9 , 7}
print(myList[2]) #Outputs 3
print(myTuple[0]) #Outputs 1
print(mySet[2]) #Outputs a different number everytime
print(myTuple[2]) #Outputs an error
```
-------------------------------------------------------------------------------------------------------------------------------
## Python User Input
You can get user input by using the `input()` function stored in a variable.
```python
myName = input("Enter your name: ")
print(myName) #Outputs whatever the user typed in.
```

-----------------------------------------------------------------------------------------------------------------------------------
## Python Conditionals
The most basic Python conditional is an if statement. The code inside the statement is executed if the condition returns true.
```python
myAge = 19
if age > 18:
  print("You can vote!")
```

----------------------------------------------------------------------------------------------------------------------


