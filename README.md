# Python cheat sheet
## Basics
### Print
Prints a string into the console.
````python
print("Hello world")
````
### Input
Prints a string into the console, and ask the user for a string input.
````python
input("What's your name?")
````
### Comments
Adding a # symbol in font of text lets you make comments on a line of code.
The computer will ignore your comments.
````python
# This is a comment print("This is code")
````
### Variables
A variable give a name to a piece of data. Like a box with a label, it tells you what's inside the box.
````python
my_name = "Luis"
my age = 23
````
### The += Operator
This is a convient way of saying. "take the previous value and add to it".
````python
my_age = 12
my_age += 4
# my_age is now 16
````
## Data types
### Integers
Integers are whole numbers.
````python
my_number = 354
````
### Floating Point Numbers
Floats are numbers with decimal places. When you do a calculation that results in a fraction e.g 4/3 the result will always be a floating point number.
````python
my_float = 3.14159
````
### Strings
A string is just a string of characters.
It should be surrounded by double quotes.
````python
my_string = "Hello"
````
### String Concatenation
You can add strings to string to create a new string. This is called concatenation.
It results in a new string.
````python
"Hello" + "Luis"
# becomes "HelloLuis"
````
### Escaping a String
Because the double quote is special it denotes a string, if you want to use it in a string, you need to escape it with a "\"
````python
speech = "She said: \"Hi\""
print(speech)
# prints : She said : "Hi"
````
### F-Strings
You can insert a variable into a string using f-strings.
The syntax is simple, just insert the variable in-between a set of curly braces {}.
````python
days = 365
print(f"There are {days} in a year")
````
### Converting Data Types
You can convert a variable from 1 data type to another.
Converting to float:
float()
Converting to int:
int()
Converting to string:
str()
````python
n = 354
new_n = float(n)
print(new_n) # result 354.0
````
### Checking Data Types
You can use the type() function to check what is the data type of a particular variable.
````python
n = 3.14159
type(n) # result float
````

## Maths
### Arithmetic Operators
You can do mathematical calculations with Python as long as you know the right operators.
````python
3 + 2 # Add
4 - 1 # Subtract
2 * 3 # Multiply
5 / 2 # Divide
5 ** 2 # Exponent
````
### The += Operator
This is a convenient way to modify a variable.
It takes the existing value in a variable and adds to it.
<br>
You can also use any of the other mathematical operators e.g. -= or *=.
````python
my_number = 4
my_number += 2
# result is 6
````
### The module Operator
Often you'll want to know what is the remainder after a division.
<br>
e.g. 4 / 2 = 2 with no remainder
<br>
but 5 / 2 = 2 with 1 remainder
<br>
The modulo does not give you the result of the division, just the remainder.
of the division, just the remainder.
<br>
It can be really helpful in certain situations, e.g. figuring out if a number is odd or even.
````python
5 % 2
# result is 1
````
