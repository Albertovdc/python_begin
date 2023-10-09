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
## Functions
### Creating functions
This is the basics syntax for a function in Python.It allows you to give a set of instructions a name, so you can trigger it multiple times without having to re-write or copy-paste it. The contents of the function must be indented to signal that it's inside.
````python
def my_function():
    print("Hello")
    name = input("Your name:")
    print(f"Hello {name}")
````
### Calling Functions
You activate the function by calling it.
<br>
This is simply done by a set of round brackets.This allows you to determine when to trigger the function and how many times.
````python
my_function()
my_function()
# The function my_function
# will run twice.
````
### Functions with Inputs
In addition to simple functions, you can give the function an input, this way, each time the function can do something different depending on the input. It makes your function more useful and re-usable.
````python
def add(n1, n2):
    print(n1 + n2)
add(2, 3)
````
### Functions with Outputs
In addition to inputs, a function can also have an output. The output value is proceeded bye the keyword "return".
<br>
This allows you to store the result from a function.
````python
def add(n1, n2):
    return n1 + n2
result = add(2, 3)
````
### Variable Scope
````python
n = 2
def my_function():
    n = 3
    print(n)
print(n) # Prints 2
my_function() #Prints 3
````
