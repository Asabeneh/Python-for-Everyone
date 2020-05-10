<div align="center">
  <h1> Python for Everyone</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

  <sub>Author:
  <a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
  <small> June 2019</small>
  </sub>
</div>

<h1 align="center" style="color:#306998;font-size:64px;">INTRODUCTION</h1>

Python for Everyon is a step by step guide to learn Python and programming in general. **_Python For Everyone_** is a guide for both beginners and advanced Python developers. Welcome to _Python For Everyone_.

**_Congratulations_** for deciding to learn Python. Python is eating the world. It has been the choice for developers to use python for different puprpose specifically to deal with data.

In this step by step guide, you will learn Pyton. Python is one of the most popular programming language.
You use Python **_to develop web applicaton_**, **_to develop mobile apps_**, **_desktop applications, games_** and mostly Python is use for **_data Sciecne_**, **_machine learning_** and **_AI_**.
**_Python_** has increased in popularity in recent years and has been the leading
programming language for data science and machine language.

<h1 align="center" style="color:#306998;font-size:64px;">SET UP</h1>

First install [Python](https://www.python.org/downloads/).
To write python code, we need to have a code editor. Lets install text or code editor. There are many open source code editors which can help you to write python code. These are the most commonly used ones:

- [Jupter Note book](https://www.anaconda.com/distribution/)
- [vscode](https://code.visualstudio.com/)
- [pycharm](https://www.jetbrains.com/pycharm/)
- [atom](https://atom.io/)
- [notepad++](https://notepad-plus-plus.org/) or others.

Jupter Notebook is highly recommended. You can use jupter note book by installing [anaconda](https://www.anaconda.com/distribution/). Anaconda is the most popular Python/R platform which allow you to use different development tools and making package installing so simple.

## Environment Setup

### Installing Python

To run a python script you need to install python. Let's [download](https://www.python.org/) python.
If your are a windows user. Click the button encircled in red.

[![installing on Windows](./images/installing_on_windows.png)](https://www.python.org/)

If you are a macOS user. Click the button encircled in red.

[![installing on Windows](./images/installing_on_macOS.png)](https://www.python.org/)

To check if python is installed write the following command on your device terminal.

```shell
python --version
```

![Python Version](./images/python_versio.png)

As you can see from the terminal, I am using _python 3.7.5_ version at the moment. If you mange to see the python version, well done. Python has been installed on your machine. Continue to the next section.

### Python Shell

Python is an interpreted scripting language, so it doesn't need to be compiled. It means it executes the code line by line. Python comes with a _Python Shell (Python Interactive Shell)_. It is used to execute a single python command and get the result.

Python Shell waits for the python code from the user. When you enter the code, it interprets the code and shows the result in the next line.
Open your terminal or command prompt(cmd) and write:

```shell
python
```

![Python Scripting Shell](./images/opening_python_shell.png)

The python interactive shell is opened and it is waiting for you to write python code. You will write your python script next to this symbol >>> and then click Enter.
Lets write our very first script on the python scripting shell.

![Python script on python shell](./images/adding_on_python_shell.png)

Well done, you wrote your first python script on python interactive shell. How do we close this shell ?
To close the shell, next to this symbol >> write **exit()** command and press Enter.

![Exit from python shell](./images/exit_from_shell.png)

Now, you know how to open the python interactive shell and how to exit from it.

Python will give you results if you write scripts that python understands, if not it returns errors. Let's make a deliberate mistake and see what python will return.

![Invalid Syntax Error](./images/invalid_syntax_error.png)

As you can see from the returned error, python is so clever that it knows the mistake we made and which was _Syntax Error: invalid syntax_. Using x as multiplication in python is a syntax error because (x) is not a valid syntax in python. Instead of (**x**) we use asterisk (*) for multiplication. The returned error clearly shows what to fix.
The process of identifying and removing errors from a program is called *debugging*. Let's debug it by putting * in place of **x**.

![Fixing Syntax Error](./images/fixing_syntax_error.png)

Our bug was fixed, the code ran and we got a result we were expecting. As a programmer you will see such kind of errors on daily basis. It is good to know how to debug. To be good at debugging you should understand what kind of errors you are facing:SyntaxError, IndexError, ModuleNotFoundError, KeyError, ImportError etc. We will see more about different python **_error types_** in later sections.

Let's practice more how to use python interactive shell. Go to your terminal or command prompt and write the word **python**.

![Python Scripting Shell](./images/opening_python_shell.png)

The python interactive shell is opened. Let's do some basic mathematic operations (addition, subtraction, multiplication, division, modulus, exponential).
Lets do some maths first before we write any python code:

- 2 + 3 = 5
- 3 - 2 = 1
- 3 \* 2 = 6
- 3 / 2 = 1.5
- 3 ^ 2 = 3 x 3 = 9

In python we have the following additional operations:

- 3 % 2 = 1 => which means finding the remainder
- 3 // 2 = 1 => which means removing the remainder

Lets change the above mathematical expressions to code. The python shell has been opened and lets write a comment at the very beginning of the shell.
A _comment_ is a part of the code which is not executed by python. So we can leave some text in our code to make our code more readable. Python does not run the comment part. A comment in python starts with hash(#) symbol.
This is how you write a comment in python

```shell
 # comment starts with hash
 # this is a python comment, because it starts with a (#) symbol
```

![Maths on python shell](./images/maths_on_python_shell.png)

Before we move on to the next section, lets practice more on the python interactive shell. Close the opened shell by writing _exit()_ on the shell and open it again and let's practice how to write text on the python shell.

![Writing String on python shell](./images/writing_string_on_shell.png)

### Installing Visual Studio Code

The python interactive shell is good to try and test small script codes but it won't be for a big project. In real work environment, developers use different code editors to write codes. In this 30 days of python programming challenge we will use visual studio code. Visual studio code is a very popular open source text editor. I am a fan of vscode and I would recommend to [download](https://code.visualstudio.com/) visual studio code, but if you are in favor of other editors, feel free to follow with what you have.

[![Visual Studio Code](./images/vscode.png)](https://code.visualstudio.com/)

If you installed visual studio code, let's see how to use it.

#### How to use visual studio code

Open the visual studio code by double clicking the visual studio icon. When you open it you will get this kind of interface. Try to interact with the labeled icons.

![Visual studio Code](./images/vscode_ui.png)

Create a folder named 30DaysOfPython on your desktop. Then open it using visual studio code.

![Opening Project on Visual studio](./images/how_to_open_project_on_vscode.png)

![Opening a project](./images/opening_project.png)

After opening it you will see shortcuts for creating files and folders inside of 30DaysOfPython project's directory. As you can see below, I have created the very first file, helloworld.py. You can do the same.

![Creating a python file](./images/helloworld.png)

After a long day of coding, you want to close your code editor, right? This is how you will close the opened project.

![Closing project](./images/closing_opened_project.png)

Congratulations, you have finished setting up the development environment. Let's start coding.

## Basic Python

### Python Syntax

A python script can be written in python interactive shell or in the code editor. A python file has an extension .py.

### Python Indentation

An indentation is a white space in a text. Indentation in many languages is used to increase code readability, however python uses indentation to create block of codes. In other programming languages curly brackets are used to create blocks of codes instead of indentation. One of the common bugs when writing python code is wrong indentation.

![Indentation Error](./images/indentation.png)

### Comments

Comments are very important to make the code more readable and to leave remarks in our code. Python doesn't run comment parts of our code.
Any text starting with hash(#) in python is a comment.

**Example: Single Line Comment**

```shell
    # This is the first comment
    # This is the second comment
    # Python is eating the world
```

**Example: Multiline Comment**

Triple quote can be used for multiline comment if it is not assigned to a variable

```shell
"""This is multiline comment
multiline comment takes multiple lines.
python is eating the world
"""
```

### Data types

In python there are several types of data types. Let's get started with the most common ones. Different data types will be covered in detail in other sections. For the time being let us just go through the different data types and get familiar with them. You do not have to have a clear understanding now.

#### Number

- Integer: Integer(negative, zero and positive) numbers
  Example:
  ... -3, -2, -1, 0, 1, 2, 3 ...
- Float: Decimal number
  Example
  ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex
  Example
  1 + j, 2 + 4j

#### String

A collection of one or more characters under a single or double quote. If a string is more than one sentence then we use a triple quote.

**Example:**

```py
'Asabeneh'
'Finland'
'Python'
'I love teaching'
'I hope you are enjoying Python for Everyone'
```

#### Booleans

A boolean data type is either a True or False value. T and F should be always uppercase.

**Example:**

```python
    True  #  Is the light on? If it is on, then the value is True
    False # Is the light on? If it is off, then the value is False
```

#### List

Python list is an ordered collection which allows to store different data type items. A list is similar to an array in JavaScript.

**Example:**

```py
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits!)
['Finland','Estonia', 'Sweden','Norway'] # all the same data types - a list of strings (countries!)
['Banana', 10, False, 9.81] # different data types in the list - string, integer, boolean and float
```

#### Dictionary

A python dictionary object is an unordered collection of data in a key:value pair format.

**Example:**

```py
{'name':'Asabeneh', 'country':'Finland', age:250, 'is_married':True}
```

#### Tuple

A tuple is an ordered collection of different data types like list but tuples can not be modified once they are created. They are immutable.

**Example:**

```py
('Asabeneh', 'Brook', 'Abraham', 'Lidiya')
```

#### Set

A set is a collection of data types similar to list and tuple. Unlike list and tuple, set is not an ordered collection of items. Like in mathematics, set in python stores only unique items.

In later sections, we will go in detail about each and every python data type.

**Example:**

```py
{3.14, 9.81, 2.7} # order is not important in set
```

### Checking Data types

To check the data type of certain data/variable we use the **type** function. In the following terminal you will see different python data types:

![Checking Data types](./images/checking_data_types.png)

### Python File

First open your project folder, 30DaysOfPython. If you don't have this folder, create a folder name called 30DaysOfPython. Inside this folder, create a file called helloworld.py. Now, let's do what we did on python interactive shell using visual studio code.
The python interactive shell was printing without using **print** but on visual studio code to see our result we should use a built in function **print(some data to print)**. See the examples below.

**Example:**

The file name is helloworld.py

```py
# Day 1 - 30DaysOfPython Challenge

print(2 + 3)             # addition(+)
print(3 - 1)             # subtraction(-)
print(2 * 3)             # multiplication(*)
print(3 / 2)             # division(/)
print(3 ** 2)            # exponential(**)
print(3 % 2)             # modulus(%)
print(3 // 2)            # Floor division operator(//)

# Checking data types
print(type(10))          # Int
print(type(3.14))        # Float
print(type(1 + 3j))      # Complex number
print(type('Asabeneh'))  # String
print(type([1, 2, 3]))   # List
print(type({'name':'Asabeneh'})) # Dictionary
print(type({9.8, 3.14, 2.7}))    # Set
print(type((9.8, 3.14, 2.7)))    # Tuple
```

To run the python file check the image below. You can run the python file either by running the green button or by typing _python helloworld.py_ in the terminal .

![Running python script](./images/running_python_script.png)



<h1 align="center" style="color:#306998;font-size:64px;">COMMENT</h1>

Comment is essential to make code readable to ourselves or for others. Commented part of our code is not interperated by Python interperator.

```python
# This is a single line comment
```

#### Exerciese:

- Write your first python comment
- Write an other more python comment
- Write you third pyhon comment
- Write a comment which says I am exited to learn Python Programming.
- Write a comment which says It is recommended to add a comment at the beginning of a code

<h1 align="center" style="color:#306998;font-size:64px;"> PRINTING USING PYTHON</h1>

```python
# Printing in Python
print('Hello, World!')
print('Hello,', "World", "!")
print("Welcome to Python!")
print('Learn python in', 2019)
print('Welcome to Python for Everyone')
print('Welcome','to', 'Python','for','Everyone')

```

    Hello, World!
    Hello, World !
    Welcome to Python!
    Learn python in 2019
    Welcome to Python for Everyone
    Welcome to Python for Everyone

#### Exerciese:

1. Writ a python comment saying 'How to print using print () at beginning of your code'
2. Print your first name using **_print()_**
3. Print your last name using **_print ()_**
4. Print your full name using **_print ()_**
5. Print your country using **_print()_**
6. Print your city using **_print()_**
7. Print your age using **_print ()_**
8. Print the year using **_print()_**
9. Print your qualification or your job using I**_print()_**
10. Are you single or married ? Answer should be True or False. Print the answer using **_print()_**

<h1 align="center" style="color:#306998;font-size:64px;">VARIABLES</h1>

Variables are containers or a means to store data in computer memory. pneumonic varialbes recommend to use in many programming langauges.

Valid variable names

```shell
    firstname
    lastname
    age
    country
    city
    first_name
    last_name
    capital_city
    _if # if we want to use reservered word as a variable
    first_name
    year_2019
    year2019
    current_year_2019
    num1
    num2
```

Invalid varaible names

- first-name
- num-1
- 1num

In Pyton For Everyone, we will use standard python varible naming which has been adopted by many python developers. The example below is an example of standard naming of variables, underscore when the variable name is long.

```python
# Variables in Python

first_name = "Asabeneh"
last_name = "Yetayeh"
country = "Helsinki"
age = 250
is_married = True
# Printing the values stored in the variables
print('First name:', first_name)
print('Last name: ', last_name)
print('Country: ', country)
print('Age: ', age)
print('Married: ', is_married)
```

    First name: Asabeneh
    Last name:  Yetayeh
    Country:  Helsinki
    Age:  250
    Married:  True

Variable can also be declared in one line:

```python
first_name, last_name, country, age, is_married = 'Asabeneh', 'Yetayeh', 'Helsink', 250, True
print(first_name, last_name, country, age, is_married)
print('First name:', first_name)
print('Last name: ', last_name)
print('Country: ', country)
print('Age: ', age)
print('Married: ', is_married)
```

    Asabeneh Yetayeh Helsink 250 True
    First name: Asabeneh
    Last name:  Yetayeh
    Country:  Helsink
    Age:  250
    Married:  True

#### Exerciese: Variables

1. Writ a python comment saying 'Variables in python'
2. Declare a first name variable and assign a value to it
3. Declare a last name variable and assign a value to it
4. Declare a full name variable and assign a value to it
5. Declare a country variable and assign a value to it
6. Declare a city variable and assign a value to it
7. Declare an age varialbel and assign a value to it
8. Declare a year varaible and assign a value to it
9. Declare a variable is_married and assign a value to it
10. Declare a variable is_true and assign a value to it
11. Declare a variable is_light_on and assign a value to it
12. Declare multiple variable on one line

## Getting User Input

```python
name = input('What is your name ?')
age = int(input('How old are you ?'))

if age < 18:
    print(name,' you are under age')
else:
    print(name, ', you are old enough')
```

    What is your name ?Asabeneh
    How old are you ?100
    Asabeneh , you are old enough

<h1 align="center" style="color:#306998;font-size:64px;">PYTHON DATA TYPES</h1>

Different data types in python. There are different data type in python programming. To identify the data tpe we use the type method.

```python
# Different python data types
# Let's declare different data tyeps

first_name = 'Asabeneh' # String
last_name = 'Yetayeh' # String
country = 'Finland' # String
city= 'Helsinki'
age = 250 # Number, it is not my real age, don't worry about it

print(type('Asabeneh'))
print(type(first_name))
print(type(10))
print(type(3.14))
print(type(1 + 1j))
print(type(True))
print(type([1, 2,3,4]))
print(type({"name":"Asabeneh","age":250, "is_married":250}))
print(type((1,2)))
print(type(zip([1,2],[3,4])))
```

    <class 'str'>
    <class 'str'>
    <class 'int'>
    <class 'float'>
    <class 'complex'>
    <class 'bool'>
    <class 'list'>
    <class 'dict'>
    <class 'tuple'>
    <class 'zip'>

#### Exerciese: Data Types

1. Writ a python comment saying 'Python Data types'
2. Declare a first name variable and assign a value to it
3. Declare a last name variable and assign a value to it
4. Declare an age varialbel and assign a value to it
5. Declare a full name variable and assign a value to it
6. Declare a country variable and assign a value to it
7. Declare a city variable and assign a value to it
8. Declare a variable is_married and assign a value to it
9. Declare a variable is_true and assign a value to it
10. Declare a variable is_light_on and assign a value to it
11. Check the data types of each variable using type()

## Numbers

1. Integers
2. Floating Numbers
3. Complex Numbers

Numbers are python data types.
Arthimetic Operators: +, -, \*, /

```python
# Arthimetic Operations in Python
# Integers

print('Additon: ', 1 + 2)
print('Substraction: ', 2 - 1)
print('Multiplication: ', 2 * 3)
print ('Division: ', 4 / 2) # Division in python gives floating number
print('Division: ', 6 / 2)
print('Division: ', 7 / 2)
print('Division without the remainder: ', 7 // 2) # gives without the floating number or without the remaining
print('Modulous: ', 3 % 2)
print ('Division without the remainder: ',7 // 3)
print('Exponentation: ', 3 ** 2)
# Floating numbers
print('Floating Number', 3.14)
# Complex numbers
print('Complex number: ', 1+1j)
print('Multiplying complext number: ',(1+1j) * (1-1j))


print('== Additon, Subtraction, Multipliation, Division, Modules ==')

num_one = 3
num_two = 4

total = num_one + num_two
diff = num_two - num_one
product = num_one * num_two
div = num_two / num_two
remainder = num_two % num_one


print('sum: ', total)
print('difference: ', diff)
print('product: ', product)
print('division: ', div)
print('remainder: ', remainder)

mass = 75
gravity = 9.81
# Calcualte the wieght of the object on planet earth
weight = mass * gravity

print(weight, 'N')
```

    Additon:  3
    Substraction:  1
    Multiplication:  6
    Division:  2.0
    Division:  3.0
    Division:  3.5
    Division without the remainder:  3
    Modulous:  1
    Division without the remainder:  2
    Exponentation:  9
    Floating Number 3.14
    Complex number:  (1+1j)
    Multiplying complext number:  (2+0j)
    == Additon, Subtraction, Multipliation, Division, Modules ==
    sum:  7
    difference:  1
    product:  12
    division:  1.0
    remainder:  1
    735.75 N

#### Exerciese: Numbers

1. Declare your age as integer variable
2. Declare your height as a float variable
3. Declare a complex number variable
4. Calcaulate an area of a triangle (area = 0.5 x b x h)
5. Calaculate the primeter of triangle (p = a + b + c)
6. Calaculate the of area rectangle (area = lenght x width)
7. Calaculate the primeter of rectangle (p = 2 x (length + width))
8. Calculate the area of a circle (area = 3.14 x r x r)
9. Calculate the circumference of a circle(c = 2 x pi x r)
10. Calculate the value of y (y = x2 + 6x + 9). Try to use different x value and figure out at what x value y is 0.

## Strings

String is data type. Any data under single or double quot are a string. There are diferent string methods to deal with string data types. To check the length of a string use the **_len()_** method.

```python
# Assigning variables to string value

first_name = "Asabeneh"
space = ' ' # an empty space string
last_name = "Yetayeh"
country = "Helsinki"
full_name = ' Asabeneh Yetayeh'

print(first_name)
print(len(first_name))
print(last_name)
print(len(last_name))
print(country)
print(space)  # You don't see the printed empty space
print(full_name) # there is indent because of the trailing space in the full name is string

```
    Asabeneh
    8
    Yetayeh
    7
    Helsinki

     Asabeneh Yetayeh

### String Concatination

Merging two or more strings together is called **_concatination_**

```python

# String concatination
first_name = "Asabeneh"
space = ' ' # an empty space string
last_name = "Yetayeh"
country = "Finland"
city = 'Helsinki'
full_name = first_name  + space + last_name
git_repo= 'Python ' + ' for ' + ' Everyone'
person_info = 'I am ' + full_name + '. I live in ' + country + ', '+ city + '.'
print('Full name: ', full_name)
print('Person Information:', person_info)
print('Git repository: ', git_repo)


```

    Full name:  Asabeneh Yetayeh
    Person Information: I am Asabeneh Yetayeh. I live in Finland, Helsinki.
    Git repository:  Python  for  Everyone

### String transformations

- **_s.lower()_**: Change all letters to lowercase
- **_s.upper()_**: Change all letters to uppercase
- **_s.capitalize()_**: Change all letters to capitalcase
- **_s.title()_**: Change to titlecase
- **_s.swapcase()_**: Change all uppercase letters to lowercase, and vice versa

```python
firstName = 'Asabeneh'
lastName = 'Yetayeh'
space = ' '
full_Name = first_name + space + last_name;

# Changing string to lower case
print('=== change to lower case ===')
print(first_name.lower())
print(last_name.lower())
print(full_Name.lower())

# Changing string to upper case
print('=== change to upper case ===')
print(first_name.upper())
print(lastName.upper())
print(full_Name.upper())


# Changing string to capitalize
print('=== change to capitalize ===')
print(first_name.capitalize())
print(lastName.capitalize())
print(full_Name.capitalize())

# Changing string to capitalize

print('=== change to title ===')
title = 'python for everyone'
sub_title = 'learning programming using python'
lang = 'python'
level = 'both begineer and advanced learners'
print(title.title())
print(sub_title.title())
print(lang.title())
print(level.title())

# Changing string to swapcase()
print('=== swapping cases ===')

first_name = 'ASABEEH'
last_name = 'yetayeh'
space = ' '
full_name = first_name + space + last_name;

print(first_name.swapcase())
print(last_name.swapcase())
print(full_name.swapcase())




```

    === change to lower case ===
    asabeneh
    yetayeh
    asabeneh yetayeh
    === change to upper case ===
    ASABENEH
    YETAYEH
    ASABENEH YETAYEH
    === change to capitalize ===
    Asabeneh
    Yetayeh
    Asabeneh yetayeh
    === change to title ===
    Python For Everyone
    Learning Programming Using Python
    Python
    Both Begineer And Advanced Learners
    === swapping cases ===
    asabeeh
    YETAYEH
    asabeeh YETAYEH

### Spliting string

Empty space is the default paramter.

- **_s.split()_**: Change the string to a list containing the string
- **_s.split(' ')_**:Change the string to a list containing the words of in the string
- **_s.split(',')_**: split the words at the comma

```python
# Spliting a stirng to list
first_name = 'Asabeneh'
last_name = 'Yetayeh'
full_name = 'Asabeneh Yetayeh'

programming_lang = 'python, R, matlab, and Java'


# Changing a string to list
print(first_name.split())
print(list(first_name))
print(full_name.split(' '))
print(programming_lang.split(','))


# To check the length of string
print(len(first_name))

# To check the data type of the string
print(type(first_name))
```

    ['Asabeneh']
    ['A', 's', 'a', 'b', 'e', 'n', 'e', 'h']
    ['Asabeneh', 'Yetayeh']
    ['python', ' R', ' matlab', ' and Java']
    8
    <class 'str'>

#### String Formatting

### Exercises- Strings

1. Concatinate the string 'Python', 'For','Everyone' to a single string, 'Python for Everyone'
1. Concatinate the string 'Coding', 'For' , 'All' to a single string, 'Coding For All'
1. Declare a variable name company and assign it to an initial value **"Coding For All"**.
1. Print company using **print()**
1. Print the **length** of the company string using **_len()_** method and _print()_
1. Change all the string to capital letters using **upper()** method
1. Change all the string to lowercase letters using **lower()** method
1. Use **_capitalize(),title(), swapcase()_** methods to format the value stored in the varaible name company
1. Cut(slice) out the first word of the company string
1. Check if the string contains a word **Coding** using the method index, find or other methods.
1. Replace the word coding in the string 'Coding For All' to Python using replace or other methods.
1. Change Python for Everyone to Python for All using the replace method or other methods
1. Split the string 'Coding For All' at the space using **split()** method
1. "Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon" **split** the string at the comma
1. What is character at index 10 in "Coding For All"
1. Create an acronym or an abbrivaton for the name 'Python For Everyone'
1. Create an acronym or an abbrivaton for the name 'Coding For All'
1. Use **index** to determine the position of the first occurrence of C in Coding For All
1. Use **index** to determine the position of the first occurrence of F in Coding For All
1. Use **rfind** to determine the position of the last occurrence of l in Coding For All People.
1. Use **index or find** to find the position of the first occurrence of the word **because** in the following sentence:**'You cannot end a sentence with because because because is a conjunction'**
1. Use **rindex** to find the position of the last occurrence of the word **because** in the following sentence:**'You cannot end a sentence with because because because is a conjunction'**
1. Slice out the phase **because because because** in the following sentence:**'You cannot end a sentence with because because because is a conjunction'**
1. Use **search** to find the position of the first occurrence of the word **because** in the following sentence:**'You cannot end a sentence with because because because is a conjunction'**
1. Slice out the phase **because because because** in the following sentence:**'You cannot end a sentence with because because because is a conjunction'**
1. Use **trim()** to remove if there is trailing whitespace at the beginning and the end of a string.E.g " Coding For All ".
1. Use **startswith()** method with the string Coding For All make the result true
1. Use **endswith()** method with the string Python for Everyone make the result true

## Booleans

A boolean value is either True or False.

- Comparison operatiors: >, >=, <, <=, ==, !=
- Logical Operators **_or_**, **_and_**, !

### Data Type Conversion

```python
num_str = '10'
print(num_str)
print(type(num_str))

num_int = int(num)
print(num_int)
print(type(num_int))

num_float = float(num_str)
print(num_float)

e = 2.71
```

    10
    <class 'str'>
    10
    <class 'int'>
    10.0

<h1 align="center" style="color:#306998;font-size:64px;">CONDITIONALS </h1>

```python
# Comparing something give either a True or False
print('True == True: ', True == True)
print('True == False: ', True == False)
print('False == False:', False == False)
print('True and True: ', True and True)
print('True or False:', True or False)
print('a in an:', 'a' in 'an')
print('4 is 2 ** 2:', 4 is 2 **2)

print(3 > 2)
print(3 >= 2)
print(3 != 2)
print(3 < 2)
print(3 <= 2)
print(3==2)
print(3!='3')
print(3==3)
```

    True == True:  True
    True == False:  False
    False == False: True
    True and True:  True
    True or False: True
    a in an: True
    4 is 2 ** 2: True
    True
    True
    True
    False
    False
    False
    True
    True

```python
num = 10
if num > 5:
    print('Number is greater than 5')
# The is conditon does't get exected so we need else
if num < 5:
    print('Number is less than 5')

if num < 5:
    print('Number is less than 5')
else:
    print('Number is greater than 5')

num = 5
if num < 5:
    print('Number is less than 5')
elif num == 5:
    print('Number is 5')
else:
    print('Number is greater than 5')



```

    Number is greater than 5
    Number is greater than 5
    Number is 5

### Exercises: Conditional

1. Get user input using input(“Enter your age:”). If user is 18 or older , give feedback:You are old enough to drive but if not 18 give feedback to wait for the years he supposed to wait for.
  
   ```sh
   Enter your age: 30
   You are old enough to drive.
   ```

   ```sh
   Enter your age:15
   You are left with 3 years to drive.
   ```

2. Compare the values of myAge and yourAge using if … else. Based on the comparison log to console who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

   ```sh
   Enter your age: 30
   You are 5 years older than me.
   ```

3. If a is greater than b return a is greater than b else a is less than b.
   Output:
   `sh let a = 4; let b = 3; 4 is greater than 3`
4. Write a code which give grade students according to theirs scores:
   - 80-100, A
   - 70-89, B
   - 60-69, C
   - 50-59, D
   - 0 -49, F
5. Check if the season is Autumn, Winter, Spring or Summer.
   If the user input is:
   - September, October or November, the season is Autumn.
   - December, January or February, the season is Winter.
   - March, April or May, the season is Spring
   - June, July or August, the season is Summer

<h1 align="center" style="color:#306998;font-size:64px;">LOOPS</h1>

### For loops:

```python
print('=== Whole Numbers===')
for x in range(11):
    print(x)

print('=== Even Numbers===')
# the range(initial, stop, step)
for n in range(0, 11, 2):
    print(n)

print('=== Odd Numbers===')
# the range(initial, stop, step)
for n in range(1, 11, 2):
    print(n)

```

    === Whole Numbers===
    0
    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    === Even Numbers===
    0
    2
    4
    6
    8
    10
    === Odd Numbers===
    1
    3
    5
    7
    9

### Continue and break in for loop

```python
for x in range(10):
    if (x is 1):
        continue
    if (x > 5):
        break
    print(x)
```

    0
    2
    3
    4
    5

### While Loop

```python
x = 0
while (x < 10):
    print(x)
    x += 1
```

    0
    1
    2
    3
    4
    5
    6
    7
    8
    9

### Exercises

1. Iterate 0 to 10 using for loop, do the same using while and do while loop.
1. Iterate 10 to 0 using for loop, do the same using while and do while loop.
1. Write a loop that makes seven calls to print() to output the following triangle:
   ```python
       #
       ##
       ###
       ####
       #####
       ######
       #######
   ```
1. Use nested loops to create the following:

```sh
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
```

1. Iterate the list, ['Python', 'Numpy','Pandas','Data Science', AI','ML'] using a for loop and print out the items.
1. Use for loop to iterate from 0 to 100 and print only even numbers
1. Use for loop to iterate from 0 to 100 and print only odd numbers
1. Use for loop to iterate from 0 to 100 and print and print the sum of all numbers.
   ```python
    # The sum of all numbers is 5050.
   ```
1. Use for loop to iterate from 0 to 100 and print the sum of all evens and the sum of all odds.
   ```python
   # The sum of all evens is 2550. And the sum of all odds is 2500.
   ```

# Lists

Lists are like arrays in JavaScript. They store different elements unlike other varialbles. List has different methods to modify and manipulate the list. Some of the methods which are used to modiyf lists **append**, **insert**, **extend**.

## Creating an empty list or list containing values

```python
# Creating lists
lst = [] # empty list
print(list)
lst = list() # empty list
print(lst)
numbers = [1, 2, 3, 4, 5, 6] # creating list 1 to 6
print(numbers)
one_to_hunderd = list(range(11)) # creating list 1 to 10
even_numbers = list(range(0,51, 2)) # Create even number lists 0 to 50
print(one_to_hunderd)
print(even_numbers)

names = ['Asabeneh','Brook','Sami','David']
print(names)
it_companies = ['Google','Facebook','Nokia','Apple','Oracle','Amazon','IBM']
print(it_companies)
constants = [3.14, 9.81, 98.6, 100]
print(constants)


```

    <class 'list'>
    []
    [1, 2, 3, 4, 5, 6]
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    [0, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50]
    ['Asabeneh', 'Brook', 'Sami', 'David']
    ['Google', 'Facebook', 'Nokia', 'Apple', 'Oracle', 'Amazon', 'IBM']
    [3.14, 9.81, 98.6, 100]

```python
for number in numbers:
    print(number)
    if (number % 2 == 0):
        print("is even")
    else:
        print("is odd")

print ("All done.")
```

    1
    is odd
    2
    is even
    3
    is odd
    4
    is even
    5
    is odd
    6
    is even
    All done.

## Appending value to lists

Using different methods to manipulate lists. Slicing using :, appending, extending and inserting:

```python
# First lets create a list
x = [1, 2, 3, 4, 5, 6]
print(len(x)) # to check the length of the list
```

    6

```python
x.append(8)
x.append(9)
x
```

    [1, 2, 3, 4, 5, 6, 8, 9]

## Inserting value among values in a list

Inserting a value at a certain index

```python
x.insert(6,7) # the missing value in the list which is 7 is inserted
x
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9]

## Use extend to two or more arrays together

```python
x.extend([9,10])
x
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 9, 10]

## Slicing

```python
x[:3]

```

    [1, 2, 3]

```python
x[3:]

```

    [4, 5, 6, 7, 8, 9, 9, 10]

```python
x[-2:]

```

    [9, 10]

## Concating lists (Merging)

```python
a = [1, 2,3]
b = [4, 5,6]
c = a + b
print(c)

```

    [1, 2, 3, 4, 5, 6]

List of lists

```python
x = [1, 2,3]
y = [4, 5,6];
z = [x, y]
print(z)

```

    [[1, 2, 3], [4, 5, 6]]

```python
print(x[0])
print(z[0])
print(z[0][0])
print(z[1])
print(z[1][0])

```

    1
    [1, 2, 3]
    1
    [4, 5, 6]
    4

```python
z = [3, 2, 1]
z.sort()
z
```

    [1, 2, 3]

```python
z.sort(reverse=True)
z
```

    [3, 2, 1]

## Sort vs Sorted in list

```python
nums_one = [3,1,4,2,5]
nums_sort =nums_one.sort() # mutate the original list and return None
print(nums_one)
print(nums_sort) # return None
nums_two = [3,1,4,2,5]
nums_sorted = sorted(nums_two) # Do not mutate the original list
print(nums_two)
print(nums_sorted)
```

    [1, 2, 3, 4, 5]
    None
    [3, 1, 4, 2, 5]
    [1, 2, 3, 4, 5]

## Getting index of a list using enumerate

```python
even_nums = [2,4,6,8,10]
for i, n in enumerate(even_nums):
    print('index:',i, n)
```

    index: 0 2
    index: 1 4
    index: 2 6
    index: 3 8
    index: 4 10

```python
for i, n in enumerate(range (10)):
    print('index:',i, n)
```

    index: 0 0
    index: 1 1
    index: 2 2
    index: 3 3
    index: 4 4
    index: 5 5
    index: 6 6
    index: 7 7
    index: 8 8
    index: 9 9

```python
(name, age) = ['Asabeneh', 250]
```

```python
print(name, age)
```

    Asabeneh 250

## List Comprehension

```python
[i  for i in range (11)] # list of whole numbers
```

    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

```python
[i * i for i in range (11)] # List of squares
```

    [0, 1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

```python
even_nums = [i for i in range(51) if i % 2 == 0] # List of even numbers
print(even_nums)
```

    [0, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50]

```python
odds = [i for i in range(51) if i % 2 != 0] # List of odd numbers
print(odds)
```

    [1, 3, 5, 7, 9, 11, 13, 15, 17, 19, 21, 23, 25, 27, 29, 31, 33, 35, 37, 39, 41, 43, 45, 47, 49]

```python
numbers = [1, 2, 3,4,5]
[n * n for n in numbers]  # maping using list comprehension

```

    [1, 4, 9, 16, 25]

```python

names = ['Asabeneh','Brook','David','Martha']
[name.upper () for name in names] # Mapping using list comprehension
```

    ['ASABENEH', 'BROOK', 'DAVID', 'MARTHA']

```python
numbers = [-4, -3, -2, -1, 0, 2, 4, 6]
[n for n in numbers if n > 0] # Filtering using list comprehension
```

    [2, 4, 6]

### Exercises

1. Declare an _empty_ list;
1. Declare a list with more than 5 number of items
1. Find the length of your list
1. Get the first item, the middle item and the last item of the list
1. Declare a list called _mixed_data_types_,put different data types and in your array and the array size should be greater than 5
1. Declare a list variable name it_companies and assign initial values Facebook, Google, Microsoft, Apple, IBM, Oracle and Amazon.
1. Print the list using _print()_
1. Print the number of companies in the list
1. Print the first, middle and last company
1. Print out each company
1. Change companies to uppercase and print them out
1. Print the list like as a sentence: Facebook, Google, Microsoft, Apple, IBM,Oracle and Amazon are big IT companies.
1. Check if a certain company exists in the it*companies list. If it exist return the company else return a company is \_not found*.
1. Filter out companies which have more than one 'o' without the filter method
1. Sort the array using _sort()_ method
1. Reverse the array without method
1. Reverse the array using method
1. Slice out the first 3 companies from the list
1. Slice out the last 3 companies from the list
1. Slice out the middle IT company or companies from the list
1. Remove the first IT company from the array
1. Remove the middle IT company or companies from the list
1. Remove the last IT company from the list
1. Remove all IT companies

## Tuples

### Creating Tuples

```python
#Tuples are just immutable lists. Use () instead of []
tp = tuple()
print(type (tp))
tp = ()
print(type(tp))
nums = (1, 2, 3)
print(nums)
len(nums)
```

    <class 'tuple'>
    <class 'tuple'>
    (1, 2, 3)





    3

```python
for n in nums:
    print(n)
```

    1
    2
    3

```python
x = (1, 2, 3)
y = (4, 5, 6)
print(x[0])
y[0]
```

    1





    4

```python
list_of_tuples = [x, y]
list_of_tuples
```

    [(1, 2, 3), (4, 5, 6)]

```python
(age, income) = "32,120000".split(',')
print(age)
print(income)
```

    32
    120000

```python
numbers = [1, 2, 3,4,5]
[(n,n * n) for n in numbers]  # maping using list comprehension

```

    [(1, 1), (2, 4), (3, 9), (4, 16), (5, 25)]

```python
names = ['Asabeneh','Brook','David','Martha']
[(name.upper (), len(name)) for name in names] # Mapping using list comprehension
```

    [('ASABENEH', 8), ('BROOK', 5), ('DAVID', 5), ('MARTHA', 6)]

## Dictionaries

```python
# Creating empty dictionary

dic = dict()
dic = {}

# Another more dictionary
person = {
    'name':'Asabenh',
    'age':250,
    'country':'Finland',
    'city':'Helsinki',
    'job':'instructor and developer',
    'skills':['HTML','CSS','JavaScript','Python','Node'],
    'is_married':True
}
print(person)
print(len(person))

```

    {'name': 'Asabenh', 'age': 250, 'country': 'Finland', 'city': 'Helsinki', 'job': 'instructor and developer', 'skills': ['HTML', 'CSS', 'JavaScript', 'Python', 'Node'], 'is_married': True}
    7

```python
print(person)
```

    {'name': 'Asabenh', 'age': 250, 'country': 'Finland', 'city': 'Helsinki', 'job': 'instructor and developer', 'skills': ['HTML', 'CSS', 'JavaScript', 'Python', 'Node'], 'is_married': True}

```python
print(person["name"])
```

    Asabenh

```python
print(person["age"])
```

    250

```python
print(person.get("is_married"))
```

    True

```python
for key in person:
        print(key + ": " + str(person[key]))

```

    name: Asabenh
    age: 250
    country: Finland
    city: Helsinki
    job: instructor and developer
    skills: ['HTML', 'CSS', 'JavaScript', 'Python', 'Node']
    is_married: True

### Dictionary Methods

**keys**, **values**, **items**

```python
keys = person.keys()
values = person.values()
items = person.items()

print(keys)
print(values)
print(items)
```

    dict_keys(['name', 'age', 'country', 'city', 'job', 'skills', 'is_married'])
    dict_values(['Asabenh', 250, 'Finland', 'Helsinki', 'instructor and developer', ['HTML', 'CSS', 'JavaScript', 'Python', 'Node'], True])
    dict_items([('name', 'Asabenh'), ('age', 250), ('country', 'Finland'), ('city', 'Helsinki'), ('job', 'instructor and developer'), ('skills', ['HTML', 'CSS', 'JavaScript', 'Python', 'Node']), ('is_married', True)])

```python
for k, v in items:
    print(k,':', v)
```

    name : Asabenh
    age : 250
    country : Finland
    city : Helsinki
    job : instructor and developer
    skills : ['HTML', 'CSS', 'JavaScript', 'Python', 'Node']
    is_married : True

```python
numbers = [1, 2, 3,4,5]
[{n:n * n} for n in numbers]  # maping using list comprehension
```

    [{1: 1}, {2: 4}, {3: 9}, {4: 16}, {5: 25}]

```python
names = ['Asabeneh','Brook','David','Martha']
[{name:len(name)} for name in names] # Mapping using list comprehension
```

    [{'Asabeneh': 8}, {'Brook': 5}, {'David': 5}, {'Martha': 6}]

## Unpacking lists, tupples

### Unpacking tuples

```python
one, two, three = (1, 2,3)
print(one)
print(two)
print(three)

first_name, last_name, country = ('Asabeneh','Yetayeh','Finland')
print(first_name)
print(last_name)
print(country)
```

    1
    2
    3
    Asabeneh
    Yetayeh
    Finland

### Unpacking lists

```python
# First Example about unpacking list
names = ['Asabeneh','Eyob','David','Lidiya', 'Woyneshet','Yetayeh']
first_person, second_person, *rest = names
print(first_person)
print(second_person)
print(rest)

# Second Example about unpacking list
first, second, third,*rest, tenth = [1,2,3,4,5,6,7,8,9,10]
print(first)
print(second)
print(third)
print(rest)
print(tenth)

# Third Example about unpacking list
countries = ['Germany', 'France','Belgium','Sweden','Denmark','Finland','Norway','Iceland','Estonia']
gr, fr, bg, sw, *scandic, es = countries
print(gr)
print(fr)
print(bg)
print(sw)
print(scandic)
print(es)

```

    Asabeneh
    Eyob
    ['David', 'Lidiya', 'Woyneshet', 'Yetayeh']
    1
    2
    3
    [4, 5, 6, 7, 8, 9]
    10
    Germany
    France
    Belgium
    Sweden
    ['Denmark', 'Finland', 'Norway', 'Iceland']
    Estonia

<h1 align="center" style="color:#306998;font-size:64px;">SET </h1>

Creating a set

```python
s = set()
s.add(1) # adding value to a set
s.add(2)
s.add(3)
s.add(4)
s.add(5)
print(s)
print(len(s))

nums = [1, 2,2,3,4,5,4,6,7,6]
numbers = set(nums)
print(numbers)
print(len(numbers))
for n in numbers:
    print(n)

```

    {1, 2, 3, 4, 5}
    5
    {1, 2, 3, 4, 5, 6, 7}
    7
    1
    2
    3
    4
    5
    6
    7

<h1 align="center" style="color:#306998;font-size:64px;">FUNCTIONS</h1>

## Function without parameter

```python
def generate_full_name ():
    first_name = 'Asabeneh'
    last_name = 'Yetayeh'
    space = ' '
    full_name = first_name + space + last_name
    print(full_name)

generate_full_name () # calling a function

def add_two_numbers ():
    num_one = 2
    num_two = 3
    total = num_one + num_two
    print(total)
add_two_numbers() # call the functionK

# Function can also return values, if a function doen't return values the value of the function is None
# Lets rewrite the above functions using return
# From now on, we return value to a function instead of priting it

def generate_full_name ():
    first_name = 'Asabeneh'
    last_name = 'Yetayeh'
    space = ' '
    full_name = first_name + space + last_name
    return full_name
print(generate_full_name())

def add_two_numbers ():
    num_one = 2
    num_two = 3
    total = num_one + num_two
    return total
print(add_two_numbers())

```

    Asabeneh Yetayeh
    5
    Asabeneh Yetayeh
    5

## Function with one parameter

```python
def greetings (name):
    message = name + ', welcome to Python for Everyone!'
    return message

print(greetings('Asabeneh'))

def add_ten(num):
    ten = 10
    return num + ten

print(add_ten(90))


def square_number(x):
    return x * x

print(square_number(2))

def area_of_circle (r):
    PI = 3.14
    area = PI * r ** 2
    return area

print(area_of_circle(10))
```

    Asabeneh, welcome to Python for Everyone!
    100
    4
    314.0

## Function with two parameter

```python
def generate_full_name (first_name, last_name):
    space = ' '
    full_name = first_name + space + last_name
    return full_name
print('Full Name: ', generate_full_name('Asabeneh','Yetayeh'))

def sum_two_numbers (num_one, num_two):
    sum = num_one + num_two
    return sum
print('Sum of two numbers: ', sum_two_numbers(1, 9))

def calculate_age (current_year, birth_year):
    age = current_year - birth_year
    return age;

print('Age: ', calculate_age(2019, 1819))

def weight_of_object (mass, gravity):
    weight = str(mass * gravity)+ ' N' # the value has to be changed to string first
    return weight
print('Weight of an object in Newton: ', weight_of_object(100, 9.81))
```

    Full Name:  Asabeneh Yetayeh
    Sum of two numbers:  10
    Age:  200
    Weight of an object in Newton:  981.0 N

## Function with arbitrary number of paramters

```python
def sum_of_numbers(*args):
    s = 0;
    for i in args:
        s = s + i
    return s
print(sum_of_numbers(1,2,3))
print(sum_of_numbers(1,2,3, 4,5,6,7,8,9,10))
```

    6
    55

## Function with default parameter

```python
def greetings (name = 'Anonymous'):
    message = name + ', welcome to Python for Everyone!'
    return message

print(greetings())
print(greetings('Asabeneh'))

def generate_full_name (first_name = 'Asabeneh', last_name = 'Yetayeh'):
    space = ' '
    full_name = first_name + space + last_name
    return full_name



print(generate_full_name())
print(generate_full_name('David','Smith'))

def calculate_age (birth_year,current_year = 2019):
    age = current_year - birth_year
    return age;
print('Age: ', calculate_age(1819))


def weight_of_object (mass, gravity = 9.81):
    weight = str(mass * gravity)+ ' N' # the value has to be changed to string first
    return weight
print('Weight of an object in Newton: ', weight_of_object(100)) # 9.81 gravity at the surface of Earth
print('Weight of an object in Newton: ', weight_of_object(100, 1.62)) # gravit at surface of Moon


```

    Anonymous, welcome to Python for Everyone!
    Asabeneh, welcome to Python for Everyone!
    Asabeneh Yetayeh
    David Smith
    Age:  200
    Weight of an object in Newton:  981.0 N
    Weight of an object in Newton:  162.0 N

## Function with default parameter and aribtrary number of parameters

```python
def generate_groups (team,*args):
    print(team)
    for i in args:
        print(i)
generate_groups('Team-1','Asabeneh','Brook','David','Eyob')
```

    Team-1
    Asabeneh
    Brook
    David
    Eyob

## Function as parameter of other function

```python
#You can pass functions around as parameters
def square_number (n):
    return n * n
def do_something(f, x):
    return f(x)

print(do_something(square_number, 3))
```

    9

## Lamda Function

Lamda function is similary to annonymous function in JavaScript. When we do not like to reuse a function we can make a lambda function. See the example below.

```python
#Lambda functions let you inline simple functions
print(do_something(lambda x: x * x * x, 3))
```

    27

### Exercises

1. Declare a function _full_name_ and it print out your full name.
1. Declare a function _full_name_ and now it takes firstName, lastName as a parameter and it returns your full - name.
1. Declare a function _add_two_numbers_ and it takes two two parameters and it returns sum.
1. An area of a rectangle is calculated as follows: _area = lenght x width_. Write a function which calculates _area_of_rectangle_.
1. A perimeter of a rectangle is calculated as follows: _perimeter= 2x(lenght + width)_. Write a function which calculates _perimeter_of_rectangle_.
1. A volume of a rectangular prism is calculated as follows: _volume = lenght x width x height_. Write a function which calculates _volume_of_rect_prism_.
1. Area of a circle is calculated as follows: _area = π x r x r_. Write a function which calculates _area_of_circle_
1. Circumference of a circle is calculated as follows: _circumference = 2πr_. Write a function which calculates \_circum_of_circle
1. Density of a substance is calculated as follows:_density= mass/volume_. Write a function which calculates _density_.
1. Speed is calculated by dividing the total distance covered by a moving object divided by the total amount of time taken. Write a fucntion which calculates a speed of a moving object, _speed_.
1. Weight of a substance is calculated as follows: _weight = mass x gravity_. Write a function which calculates _weight_.
1. Temperature in oC can be converted to oF using this formula: _oF = (oC x 9/5) + 32_. Write a function which converst oC to oF _convert_celcius_to_fahrenheit_.
1. Body mass index(BMI) is calculated as follows: _bmi = weight in Kg / (height x height) in m2_. Write a function which calculates _bmi_. BMI is used to broadly define different weight groups in adults 20 years old or older.Check if a person is _underweight, normal, overweight_ or _obsese_ based the information given below.
   - The same groups apply to both men and women.
   - _Underweight_: BMI is less than 18.5
   - _Normal weight_: BMI is 18.5 to 24.9
   - _Overweight_: BMI is 25 to 29.9
   - _Obese_: BMI is 30 or more
1. Write a function called _check-season_, it takes a month parameter and returns the season:Autumn, Winter, Spring or Summer.
1. Linear equation is calculated as follows: _ax + b = c_. Write a function which calculates value of a linear equation, _solve_linear_equation_.
1. Quadratic equation is calculated as follows: _ax2 + bx + c = 0_. Write a function which calculates value or values of a quadratic equation, _solve_quadratic_equation_.
1. Declare a function name \_print_list. It takes list as a parameter and it prints out each element of the list.
1. Declare a functin name _swap_values_. This function swaps value of x to y.
   ```python
       swap_values(3, 4) # x => 4, y=>3
       swap_values(4, 5) # x = 5, y = 4
   ```
1. Declare a function name _reverse_list_. It takes array as a parameter and it returns the reverse of the array (dont’ use method).
   ```python
       pirnt(reverseArray([1, 2, 3, 4, 5]))
       # [5, 4, 3, 2, 1]
       print(reverseArray(["A", "B", "C"]))
       # ["C", "B", "A"]
   ```
1. Declare a function name _capitalize_list_items_. It takes list as a parameter and it returns the capitalized list of the elements
1. Declare a function name \_add_item. It takess an item parameter and it returns a list after adding the element
1. Declare a function name _remove_tem_. It takes an index parameter and it returns a list after removing an element
1. Declare a function name _sum_of_numbers_. It takes a number parameter and it adds all the numbers in that range.
1. Declare a function name _sum_of_odds_. It takes a number parameter and it adds all the odd numbers in that - range.
1. Declare a function name _sum_of_even_. It takes a number parameter and it adds all the even numbers in that - range.
1. Declare a function name evens_and_odds . It takes a positive integer as parameter and it counts number of evens and odds in the number.
   ```python
       print(evens_and_odds(100))
       # The number of odds are 50.
       # The number of evens are 51.
   ```
1. Write a funcition which takes any number of arguments and return the sum of the arguments
   ```js
   sum_all_numbers(1, 2, 3) // -> 6
   sum_all_numbers(1, 2, 3, 4) // -> 10
   ```
1. Writ a function which generates a _random_user_id_.
1. Write a function which generates a _random_MAC_address_
1. Declare a function name _random_hexa_gen_. When this function is called it generates a random hexadecimal number. The function return the hexadecimal number.
   ```python
       print(random_hexa_gen());
      # '#ee33df'
   ```
1. Declare a function name _user_id_gen_. When this function is called it generates seven character id. The function return the id.
   ```python
       print(user_id_gen());
       # 41XTDbE
   ```
1. Modify question number above . Declare a function name _user_id_gen_by_user_. It doesn’t take any parameter but it takes two inputs using input(). One of the input is the number of characters and the second input is the number of ids which are supposed to be generated.
   ```python
   user_id_gen_by_user()
   "kcsy2
   SMFYb
   bWmeq
   ZXOYh
   2Rgxf
   "
    user_id_gen_by_user()
   "1GCSgPLMaBAVQZ26
   YD7eFwNQKNs7qXaT
   ycArC5yrRupyG00S
   UbGxOFI7UXSWAyKN
   dIV0SSUTgAdKwStr
   "
   ```
1. Write a function name _rgb_color_gen_ and it generates rgb colors.
   ```python
       print(rgb_color_gen())
       # rgb(125,244,255)
   ```
1. Write a function **_list_of_hexa_colors_** which return any number of hexadecimal colors in an array.
1. Write a function **_list_of_rgb_colors_** which return any number of RGB colors in an array.
1. Write a function **_convert_hexa_to_rgb_** which converts hexa color to rgb and it returns an rgb color.
1. Write a function **\*convert_rgb_to_hexa** which converts rgb to hexa color and it returns an hexa color.
1. Write a function **_generate_colors_** which can generate any number of hexa or rgb colors.

   ```python
         generate_colors('hexa', 3)
         # ['#a3e12f','#03ed55','#eb3d2b']
         generate_colors('hexa', 1)
         # '#b334ef'

         generate_colors('rgb', 3)
         # ['rgb(5, 55, 175','rgb(50, 105, 100','rgb(15, 26, 80']
         generate_colors('rgb', 1)
         # 'rgb(33,79, 176)'

   ```

1. Call your function \_shuffle_list, it takes a list as a parameter and it returns a shuffled list
1. Call your function _factorial_, it takes a whole number as a parameter and it return a factorial of the number
1. Call your function _is_empty_, it takes a parameter and it checks if it is empty or not
1. Write a function called _sum_of_list_items_, it takes a list parameter and return the sum of all the items. Check if all the list items are number types. If not give return reasonable feedback.
1. Write a function called _average_, it takes an array parameter and returns the average of the items. Check if all the array items are number types. If not give return reasonable feedback.
1. Write a function called _modify_list_ takes list as parameter and modifies the fifth element of the list and return the list. If the list length is less than five it return 'item not found'.
   ```python
       print(modifyArray(["Avocado", "Tomato", "Potato","Mango", "Lemon","Carrot"]);
       # →["Avocado", "Tomato", "Potato","Mango", "LEMON", "Carrot"]
       print(modifyArray(["Google", "Facebook","Apple", "Amazon","Microsoft",  "IBM"]);
       # →["Google", "Facebook","Apple", "Amazon","MICROSOFT",  "IBM"]
       print(modifyArray(["Google", "Facebook","Apple", "Amazon"]);
       # →"Not Found"
   ```
1. Write a function called _is_prime_, which checks if a number is prime number.
1. Write a functions which checks if all items are unique in the array.
1. Write a function which checks if all the itmes of the array are the same data type.
1. JavaScript variable name does not support special characters or symbols execpt \$ or \_. Write a function **\*is_valid_variable** which check if a variable is valid or invlaid variable.
1. Write a function which returns array of seven random numbers in a range of 0-9. All the numbers must be unique.

<h1 align="center" style="color:#306998;font-size:64px;">CLASSES</h1>

## Classes and Objects

Python is an object oriented programming language. Everything in Python is an object, with its properties and methods. A number, string, list, dictionary,tuple, set etc. used in a program is an object of a corresponding built-in class. We create class to create an object. A Class is like an object constructor, or a "blueprint" for creating objects. We instantiate a class to create an object. The class defines attributes and the behavior of the object, while the object, on the other hand, represents the class.

We have been working with classes and objects right from the beginning of these challenge unknowingly. Every element in a Python program is an object of a class.
Let's check if everything in python is class:

```py
Last login: Tue Dec 10 09:35:28 on console
asabeneh@Asabeneh:~$ pyhton
-bash: pyhton: command not found
asabeneh@Asabeneh:~$ python
Python 3.7.5 (default, Nov  1 2019, 02:16:32)
[Clang 11.0.0 (clang-1100.0.33.8)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> num = 10
>>> type(num)
<class 'int'>
>>> string = 'string'
>>> type(string)
<class 'str'>
>>> boolean = True
>>> type(boolean)
<class 'bool'>
>>> lst = []
>>> type(lst)
<class 'list'>
>>> tpl = ()
>>> type(tpl)
<class 'tuple'>
>>> set1 = set()
>>> type(set1)
<class 'set'>
>>> dct = {}
>>> type(dct)
<class 'dict'>
```

### Creating a Class

To create a class we need the key word **class** followed by colon. Class name should be **CamelCase**.

```sh
# syntax
class ClassName:
  code goes here
```

**Example:**

```py
class Person:
  pass
```

```sh
<__main__.Person object at 0x10804e510>
```

### Creating an Object

We can create an object by calling the class.

```py
p = Person()
print(p)
```

### Class Constructor

In the above examples, we have created an object from the Person class. However, Class without a constructor is not really useful in real applications. Let's use constructor function to make our class more useful. Like the constructor function in Java or JavaScript, python has also a builtin _**init**()_ constructor function. The _**init**_ constructor function has self parameter which is a reference to the current instance of the class
**Examples:**

```py
class Person:
      def __init__ (self, name):
          self.name =name

p = Person('Asabeneh')
print(p.name)
print(p)
```

```sh
# output
Asabeneh
```

Let's add more parameter to the constructor function.

```py
class Person:
      def __init__(self, firstname, lastname, age, country, city):
          self.firstname = firstname
          self.lastname = lastname
          self.age = age
          self.country = country
          self.city = city


p = Person('Asabeneh', 'Yetayeh', 250, 'Finland', 'Helsinki')
print(p.firstname)
print(p.lastname)
print(p.age)
print(p.country)
print(p.city)
```

```sh
# output
Asabeneh
Yetayeh
250
Finland
Helsinki
```

### Object Methods

Objects can have methods. The methods are functions which are belongs to the object.
**Example:**

```py
class Person:
      def __init__(self, firstname, lastname, age, country, city):
          self.firstname = firstname
          self.lastname = lastname
          self.age = age
          self.country = country
          self.city = city

      def person_info(self):
        return f'{self.firstname} {self.lastname} is {self.age} year old. He lives in {self.city}, {self.country}'


p = Person('Asabeneh', 'Yetayeh', 250, 'Finland', 'Helsinki')
print(p.person_info())
```

```sh
# output
Asabeneh Yetayeh is 250 year old. He lives in Helsinki, Finland
```

### Object default methods

Sometimes, you may want to have a default values for you object methods. If we give a default values for the parameters in the constructor, we can avoid error when we call or instantiate our class without parameters. Let's see how it looks using example.

**Example:**

```py
class Person:
      def __init__(self, firstname='Asabeneh', lastname='Yetayeh', age=250, country='Finland', city='Helsinki'):
          self.firstname = firstname
          self.lastname = lastname
          self.age = age
          self.country = country
          self.city = city

      def person_info(self):
        return f'{self.firstname} {self.lastname} is {self.age} year old. He lives in {self.city}, {self.country}.'

p1 = Person()
print(p1.person_info())
p2 = Person('John', 'Doe', 30, 'Nomanland', 'Noman city')
print(p2.person_info())
```

```sh
# output
Asabeneh Yetayeh is 250 year old. He lives in Helsinki, Finland.
John Doe is 30 year old. He lives in Noman city, Nomanland.
```

### Method to modify class default values

In the example below, the person class, all the constructor parameters have default values and in addition to that we have a skills default value which we can access it using method. Let's create add_skill method to add skill to the skills list.

```py
class Person:
      def __init__(self, firstname='Asabeneh', lastname='Yetayeh', age=250, country='Finland', city='Helsinki'):
          self.firstname = firstname
          self.lastname = lastname
          self.age = age
          self.country = country
          self.city = city
          self.skills = []

      def person_info(self):
        return f'{self.firstname} {self.lastname} is {self.age} year old. He lives in {self.city}, {self.country}.'
      def add_skill(self, skill):
          self.skills.append(skill)

p1 = Person()
print(p1.person_info())
p1.add_skill('HTML')
p1.add_skill('CSS')
p1.add_skill('JavaScript')
p2 = Person('John', 'Doe', 30, 'Nomanland', 'Noman city')
print(p2.person_info())
print(p1.skills)
print(p2.skills)
```

```sh
# output
Asabeneh Yetayeh is 250 year old. He lives in Helsinki, Finland.
John Doe is 30 year old. He lives in Noman city, Nomanland.
['HTML', 'CSS', 'JavaScript']
[]
```

### Inheritance

Using inheritance we can reuse parent class code. Inheritance allows us to define a class that inherits all the methods and properties from another class. The parent class or super or base class is the class which gives all the methods and properties. Child class is the class the inherits from another class.
Let's see create a student class by inheriting from person class.

```py
class Student(Person):
    pass


s1 = Student('Eyob', 'Yetayeh', 30, 'Finland', 'Helsinki')
s2 = Student('Lidiya', 'Teklemariam', 28, 'Finland', 'Espoo')
print(s1.person_info())
s1.add_skill('JavaScript')
s1.add_skill('React')
s1.add_skill('Python')
print(s1.skills)

print(s2.person_info())
s2.add_skill('Organizing')
s2.add_skill('Marketing')
s2.add_skill('Digital Marketing')
print(s2.skills)

```

```sh
output
Eyob Yetayeh is 30 year old. He lives in Helsinki, Finland.
['JavaScript', 'React', 'Python']
Lidiya Teklemariam is 28 year old. He lives in Espoo, Finland.
['Organizing', 'Marketing', 'Digital Marketing']
```

We didn't call the _**init**()_ constructor in the child class. If we didn't call it we can access all the properties but if we call it once we access the parent properties by calling _super_.  
We can write add a new method to the child or we can overwrite the parent class by creating the same method name in the child class. When we add the **init**() function, the child class will no longer inherit the parent's **init**() function.

### Overriding parent method

```py
class Student(Person):
    def __init__ (self, firstname='Asabeneh', lastname='Yetayeh',age=250, country='Finland', city='Helsinki', gender='male'):
        self.gender = gender
        super().__init__(firstname, lastname,age, country, city)
    def person_info(self):
        gender = 'He' if self.gender =='male' else 'She'
        return f'{self.firstname} {self.lastname} is {self.age} year old. {gender} lives in {self.city}, {self.country}.'

s1 = Student('Eyob', 'Yetayeh', 30, 'Finland', 'Helsinki','male')
s2 = Student('Lidiya', 'Teklemariam', 28, 'Finland', 'Espoo', 'female')
print(s1.person_info())
s1.add_skill('JavaScript')
s1.add_skill('React')
s1.add_skill('Python')
print(s1.skills)

print(s2.person_info())
s2.add_skill('Organizing')
s2.add_skill('Marketing')
s2.add_skill('Digital Marketing')
print(s2.skills)
```

```sh
Eyob Yetayeh is 30 year old. He lives in Helsinki, Finland.
['JavaScript', 'React', 'Python']
Lidiya Teklemariam is 28 year old. She lives in Espoo, Finland.
['Organizing', 'Marketing', 'Digital Marketing']
```

## 💻 Exercises:

1. Python has the module called _statistics_ and we can use this module to do all the statistical caluculations. Hower to challlenge ourselves, let's try to develop a program which calculate measure of central tendency of a sample(mean, median, mode) and measure of variability(range, variance, standard deviation). In addition to those measures find the min, max, count, percentile, and frequency distribution of the sample. You can create a class called Statistics and create all the functions which do statistical calculations as method for the Statistics class. Check the output below.

```py
ages = [31, 26, 34, 37, 27, 26, 32, 32, 26, 27, 27, 24, 32, 33, 27, 25, 26, 38, 37, 31, 34, 24, 33, 29, 26]

print('Count:', data.count()) # 25
print('Sum: ', data.sum()) # 744
print('Min: ', data.min()) # 24
print('Max: ', data.max()) # 38
print('Range: ', data.range() # 14
print('Mean: ', data.mean()) # 30
print('Median: ',data.median()) # 29
print('Mode: ', data.mode()) # {'mode': 26, 'count': 5}
print('Variance: ',data.var()) # 17.5
print('Standard Deviation: ', data.std()) # 4.2
print('Variance: ',data.var()) # 17.5
print('Frequency Distribution: ',data.freq_dist()) # [(20.0, 26), (16.0, 27), (12.0, 32), (8.0, 37), (8.0, 34), (8.0, 33), (8.0, 31), (8.0, 24), (4.0, 38), (4.0, 29), (4.0, 25)]
```

```sh
# you output should look like this
print(data.describe())
Count: 25
Sum:  744
Min:  24
Max:  38
Range:  14
Mean:  30
Median:  29
Mode:  (26, 5)
Variance:  17.5
Standard Deviation:  4.2
Frequency Distribution: [(20.0, 26), (16.0, 27), (12.0, 32), (8.0, 37), (8.0, 34), (8.0, 33), (8.0, 31), (8.0, 24), (4.0, 38), (4.0, 29), (4.0, 25)]
```

1. Create a class called PersonAccount. It has firstname, lastname, incomes, expenses properties and it has total_income, total_expense, account_info,add_income, add_expense and account_balance methods. Incomes is a set of incomes and its description and the same goes for expenses.

<h1 align="center" style="color:#306998;font-size:64px;">REGULAR EXPRESSONS</h1>



## Regular Expression

A regular expression or RegEx is a small programming language that helps to find pattern in data. A RegEx can be used to check if some pattern exists in a different data type. To use RegEx in python first we should import the RegEx module which is _re_.

### Import re module

After importing the module we can use it to detect or find patterns.

```py
import re
```

### re functions

To find a pattern we use different set of _re_ functions that allows to search a string for match.

- _re.match()_:searches only in the beginning of the first line of the string and return match object if found, else return none.
- _re.search_:Returns a Match object if there is a match anywhere in the string including or in multiline string.
- _re.findall_:Returns a list containing all matches
- _re.split_: Returns a list where the string has been split at each match
- _re.sub_: Replaces one or many matches with a string

#### Match

```py
# syntac
re.match(substring, string, re.I)
# substring is a string or a pattern, string is the text we look for a pattern , re.I is case ignore
```

```py
txt = 'I love to teach python or javaScript'
# It return an object with span, and match
match = re.match('I love to teach', txt, re.I)
print(match)  # <re.Match object; span=(0, 15), match='I love to teach'>
# We can get the starting and ending position of the match as tuple using span
span = match.span()
print(span)     # (0, 15)
# Lets find the start and stop position from the span
start, end = span
print(start, end)  # 0, 15
substring = txt[start:end]
print(substring)       # I love to teach
```

As you can see from the above example, the pattern we are looking for or the substring _I love to teach_ is the beginning of the text. The match function only returns an object if the text starts with the pattern.

#### Search

```py
# syntax
re.match(substring, string, re.I)
# substring is a pattern, string is the text we look for a pattern , re.I is case ignore flag
```

```py
txt = '''Python is the most beautiful language that a human begin has ever created.
I recommend python for a first programming language'''

# It return an object with span, and match
match = re.search('first', txt, re.I)
print(match)  # <re.Match object; span=(100, 105), match='first'>
# We can get the starting and ending position of the match as tuple using span
span = match.span()
print(span)     # (100, 105)
# Lets find the start and stop position from the span
start, end = span
print(start, end)  # 100 105
substring = txt[start:end]
print(substring)       # first
```

As you can see search is much better than match because it can look for the pattern through out the text. Search return returns a match object right way a first match found. A much better _re_ function is _findall_. This function check the pattern through the string and returns all the matches as a list.

#### Searching all matches using findall

_findall()_ returns all the matches as a list

```py
txt = '''Python is the most beautiful language that a human begin has ever created.
I recommend python for a first programming language'''

# It return a list
matches = re.findall('language', txt, re.I)
print(matches)  # ['language', 'language']

```

As you can see, the word language found two times in the string. Let's practice more

Let's look for the word both Python and python in the string

```py
txt = '''Python is the most beautiful language that a human begin has ever created.
I recommend python for a first programming language'''

# It returns list
matches = re.findall('python', txt, re.I)
print(matches)  # ['Python', 'python']

```

Since we are using _re.I_ both lowercase and uppercase are included but if we don't have the flag, we write our pattern differently. Let's see that

```py
txt = '''Python is the most beautiful language that a human begin has ever created.
I recommend python for a first programming language'''

matches = re.findall('Python|python', txt)
print(matches)  # ['Python', 'python']

#
matches = re.findall('[Pp]ython', txt)
print(matches)  # ['Python', 'python']

```

#### Replacing a substring

```py
txt = '''Python is the most beautiful language that a human begin has ever created.
I recommend python for a first programming language'''

match_replaced = re.sub('Python|python', 'JavaScript', txt, re.I)
print(match_replaced)  # JavaScript is the most beautiful language that a human begin has ever created.
# OR
match_replaced = re.sub('[Pp]ython', 'JavaScript', txt, re.I)
print(match_replaced)  # JavaScript is the most beautiful language that a human begin has ever created.
```

Let's add one more example, the following string is really hard to read unless we remove the % symbol. Replacing the % with a empty string will clean the text.

```py

txt = '''%I a%m te%%a%%che%r% a%n%d %% I l%o%ve te%ach%ing.
T%he%re i%s n%o%th%ing as m%ore r%ewarding a%s e%duc%at%i%ng a%n%d e%m%p%ow%er%ing p%e%o%ple.
I fo%und te%a%ching m%ore i%n%t%er%%es%ting t%h%an any other %jobs.
D%o%es thi%s m%ot%iv%a%te %y%o%u to b%e a t%e%a%cher.'''

matches = re.sub('%', '', txt)
print(matches)  # ['Python', 'python']
```

```sh
I am teacher and  I love teaching.
There is nothing as more rewarding as educating and empowering people.
I found teaching more interesting than any other jobs.
Does this motivate you to be a teacher.
```

## Spliting text using RegEx split

```py
txt = '''I am teacher and  I love teaching.
There is nothing as more rewarding as educating and empowering people.
I found teaching more interesting than any other jobs.
Does this motivate you to be a teacher.'''
print(re.split('\n', txt))
```

```sh
['I am teacher and  I love teaching.', 'There is nothing as more rewarding as educating and empowering people.', 'I found teaching more interesting than any other jobs.', 'Does this motivate you to be a teacher.']
```

## Writing RegEx pattern

To declare a string variable we use a single or double quote. To declare RegEx variable _r''_.
The following pattern only identifies apple with lowercase, to make it case insensitive either we should rewrite our pattern or we should add a flag.

```py
regex_pattern = r'apple'
txt = 'Apple and banana are fruits. An old cliche says an apple a day a doctor way has been replaced by a banana a day keeps the doctor far far away. '
matches = re.findall(regex_pattern, txt)
print(matches)  # ['apple']

# To make case insensitive adding flag '
matches = re.findall(regex_pattern, txt, re.I)
print(matches)  # ['Apple', 'apple']
# or we can use set of characters method
regex_pattern = r'[Aa]pple'  # this mean the first letter could be Apple or apple
matches = re.findall(regex_pattern, txt)
print(matches)  # ['Apple', 'apple']

```

- []: A set of characters
  - [a-c] means, a or b or c
  - [a-z] means, any letter a to z
  - [A-Z] means, any character A to Z
  - [0-3] means, 0 or 1 or 2 or 3
  - [0-9] means any number 0 to 9
  - [A-Za-z0-9] any character which is a to z, A to Z, 0 to 9
- \\: uses to escape special characters
  - \d mean:match where the string contains digits (numbers from 0-9)
  - \D mean: match where the string does not contain digits
- . : any character except new line character(\n)
- ^: starts with
  - r'^substring' eg r'^love', a sentence which starts with a word love
  - r'[^abc] mean not a, not b, not c.
- \$: ends with
  - r'substring$' eg r'love$', sentence ends with a word love
- \*: zero or more times
  - r'[a]\*' means a optional or it can be occur many times.
- +: one or more times
  - r'[a]+' mean at least once or more times
- ?: zero or one times
  - r'[a]?' mean zero times or once
- {3}: Exactly 3 characters
- {3,}: At least 3 character
- {3,8}: 3 to 8 characters
- |: Either or
  - r'apple|banana' mean either of an apple or a banana
- (): Capture and group

![Regular Expression cheat sheet](../images/regex.png)

Let's use example to clarify the above meta characters

### Square Bracket

Let's use square bracket to include lower and upper case

```py
regex_pattern = r'[Aa]pple' # this square bracket mean either A or a
txt = 'Apple and banana are fruits. An old cliche says an apple a day a doctor way has been replaced by a banana a day keeps the doctor far far away. '
matches = re.findall(regex_pattern, txt)
print(matches)  # ['Apple', 'apple']
```

If we want to look for the banana, we write the pattern as follows:

```py
regex_pattern = r'[Aa]pple|[Bb]anana' # this square bracket mean either A or a
txt = 'Apple and banana are fruits. An old cliche says an apple a day a doctor way has been replaced by a banana a day keeps the doctor far far away. '
matches = re.findall(regex_pattern, txt)
print(matches)  # ['Apple', 'banana', 'apple', 'banana']
```

Using the square bracket and or operator , we manage to extract Apple, apple, Banana and banana.

### Escape character(\\) in RegEx

```py
regex_pattern = r'\d'  # d is a special character which means digits
txt = 'This regular expression example was made in December 6,  2019.'
matches = re.findall(regex_pattern, txt)
print(matches)  # ['6', '2', '0', '1', '9'], this is not what we want

regex_pattern = r'\d+'  # d is a special character which means digits, + mean one or more
txt = 'This regular expression example was made in December 6,  2019.'
matches = re.findall(regex_pattern, txt)
print(matches)  # ['6', '2019']
```

### One or more times(+)

```py
regex_pattern = r'\d+'  # d is a special character which means digits, + mean one or more times
txt = 'This regular expression example was made in December 6,  2019.'
matches = re.findall(regex_pattern, txt)
print(matches)  # ['6', '2019']
```

### Period(.)

```py
regex_pattern = r'[a].'  # this square bracket means a and . means any character except new line
txt = '''Apple and banana are fruits'''
matches = re.findall(regex_pattern, txt)
print(matches)  # ['an', 'an', 'an', 'a ', 'ar']

regex_pattern = r'[a].+'  # . any character, + any character one or more times
matches = re.findall(regex_pattern, txt)
print(matches)  # ['and banana are fruits']

```

### Zero or more times(\*)

Zero or many times. The pattern could may not occur or it can occur many times.

```py

regex_pattern = r'[a].*'  # . any character, + any character one or more times
txt = '''Apple and banana are fruits'''
matches = re.findall(regex_pattern, txt)
print(matches)  # ['and banana are fruits']

```

### Zero or one times(?)

Zero or one times. The pattern could may not occur or it may occur once.

```py
txt = '''I am not sure if there is a convention how to write the word e-mail.
Some people write it email others may write it as Email or E-mail.'''
regex_pattern = r'[Ee]-?mail'  # ? means optional
matches = re.findall(regex_pattern, txt)
print(matches)  # ['e-mail', 'email', 'Email', 'E-mail']

```

### Quantifier in RegEx

We can specify the length of the substring we look for in a text, using a curly bracket. Lets imagine, we are interested in substring that their length are 4 characters

```py
txt = 'This regular expression example was made in December 6,  2019.'
regex_pattern = r'\d{4}'  # exactly four times
matches = re.findall(regex_pattern, txt)
print(matches)  # ['2019']

txt = 'This regular expression example was made in December 6,  2019.'
regex_pattern = r'\d{1, 4}'   # 1 to 4
matches = re.findall(regex_pattern, txt)
print(matches)  # ['6', '2019']

```

### Cart ^

- Starts with

```py
txt = 'This regular expression example was made in December 6,  2019.'
regex_pattern = r'^This'  # ^ means starts with
print(matches)  # ['This']
```

- Negation

```py
txt = 'This regular expression example was made in December 6,  2019.'
regex_pattern = r'[^A-Za-z ]+'  # ^ in set character means negation, not A to Z, not a to z, no space
matches = re.findall(regex_pattern, txt)
print(matches)  # ['e-mail', 'email', 'Email', 'E-mail']
```

## 💻 Exercises:

1. What is the most frequent word in the following paragraph ?

```py
    paragraph = 'I love teaching. If you do not love teaching what else can you love. I love Python if you do not love something which can give you all the capabilities to develop an application what else can you love.
```

```sh
    [(6, 'love'),
    (5, 'you'),
    (3, 'can'),
    (2, 'what'),
    (2, 'teaching'),
    (2, 'not'),
    (2, 'else'),
    (2, 'do'),
    (2, 'I'),
    (1, 'which'),
    (1, 'to'),
    (1, 'the'),
    (1, 'something'),
    (1, 'if'),
    (1, 'give'),
    (1, 'develop'),
    (1, 'capabilities'),
    (1, 'application'),
    (1, 'an'),
    (1, 'all'),
    (1, 'Python'),
    (1, 'If')]
```

2. The position of some particles on the horizontal x-axis -12, -4, -3 and -1 in the negative direction, 0 at origin, 4 and 8 in the positive direction. Extract these numbers and find the distance between the two furthest particles.

```py
points = ['-1', '2', '-4', '-3', '-1', '0', '4', '8']
sorted_points =  [-4, -3, -1, -1, 0, 2, 4, 8]
distance = 12
```

3. Write a pattern which identify if a string is a valid python variable
   ```sh
   is_valid_variable('first_name') # True
   is_valid_variable('first-name') # False
   is_valid_variable('1first_name') # False
   is_valid_variable('firstname') # True
   ```
4. Clean the following text. After cleaning, count three most frequent words in the string.

   ```py
   sentence = '''%I $am@% a %tea@cher%, &and& I lo%#ve %tea@ching%;. There $is nothing; &as& mo@re rewarding as educa@ting &and& @emp%o@wering peo@ple. ;I found tea@ching m%o@re interesting tha@n any other %jo@bs. %Do@es thi%s mo@tivate yo@u to be a tea@cher!?'''

   print(clean_text(sentence));
   I am a teacher and I love teaching There is nothing as more rewarding as educating and empowering people I found teaching more interesting than any other jobs Does this motivate you to be a teacher
   print(most_frequent_words(cleaned_text)) # [(3, 'I'), (2, 'teaching'), (2, 'teacher')]
   ```

<h1 align="center" style="color:#306998;font-size:64px;">MODULES</h1>

## Importing Modules

```python
import math
import re
import pandas as pd
import numpy as np
import urllib3
import lxml

print(math.sqrt(2))
print(math.pow(3,2))
print(math.pow(3,2) == 3 ** 2)
print(math.pi)
print(math.e)
# constantcs
pi = math.pi
e = math.e
t = math.tau # 2pi

print(pi)
print(e)
print(t)


A = np.random.normal(25, 5.0, 10)
print (A)
```

    1.4142135623730951
    9.0
    True
    3.141592653589793
    2.718281828459045
    3.141592653589793
    2.718281828459045
    6.283185307179586
    [22.76977213 31.19118012 31.39357782 28.82041376 18.95246175 33.6695274
     22.31571545 21.39637955 28.40572587 24.38512071]

## Python for Statistical Analysis

### Statistics

Statistics is the discipline that studies the _collection_, _organization_, _displaying_, _analysis_, _interpretation_ and _presentation_ of data.
Statistics is a branch of mathematics that is recommended to be a prerequisite for  data science and machine learning. Statistics is a very broad field but we will focus in this section only on the most relevant part.
After completing this challenge, you may go to web development, data analysis, machine learning and data science path. Whatever path you may follow, at some point in your career you will get data which you may work on. Having some statistical knowledge will help you to make decision based on data, *data tells as they say*.

### Data

What is data? Data is any set of characters that is gathered and translated for some purpose, usually analysis. It can be any character, including text and numbers, pictures, sound, or video. If data is not put into context, it doesn't give any sense to a human or computer. To make sense from data we need to work on the data using different tools.

The work flow of data analysis, data science or machine learning starts from data. Data can be provided from some data source or it can be created. There are structured and and unstructure data. 

Data can be found as small or big data format. Most of the data types we will get have been covered in the file handling section.

### Statistics Module

The python _statistics_ module provides functions for calculating mathematical statistics of numeric data. The module is not intended to be a competitor to third-party libraries such as NumPy, SciPy, or proprietary full-featured statistics packages aimed at professional statisticians such as Minitab, SAS and Matlab. It is aimed at the level of graphing and scientific calculators.

### NumPy

In the first section we defined python as a great general-purpose programming language on its own, but with the help of other popular libraries (numpy, scipy, matplotlib, pandas etc) it becomes a powerful environment for scientific computing.

Numpy is the core library for scientific computing in Python. It provides a high-performance multidimensional array object, and tools for working with arrays.

So far, we have been using vscode but from now on I would recommend using Jupyter Notebook. To access jupter notebook let's install [anaconda](https://www.anaconda.com/). If you are using anaconda most of the common packages are included and you don't have install packages if you installed anaconda.

```sh
asabeneh@Asabeneh:~/Desktop/30DaysOfPython$ pip install numpy
```

### Importing NumPy

Jupyter notebook is available if your are in favor of [jupyter notebook](https://github.com/Asabeneh/data-science-for-everyone/blob/master/numpy/numpy.ipynb)

```py
    # How to import numpy
    import numpy as np
    # How to check the version of the numpy package
    print('numpy:', np.__version__)
    # Checking the available methods
    print(dir(np))
```

### Creating numpy array using

#### Creating int numpy arrays

```py
    # Creating python List
    python_list = [1,2,3,4,5]

    # Checking data types
    print('Type:', type (python_list)) # <class 'list'>
    # 
    print(python_list) # [1, 2, 3, 4, 5]

    two_dimensional_list = [[0,1,2], [3,4,5], [6,7,8]]

    print(two_dimensional_list)  # [[0, 1, 2], [3, 4, 5], [6, 7, 8]]

    # Creating Numpy(Numerical Python) array from python list

    numpy_array_from_list = np.array(python_list) 
    print(type (numpy_array_from_list))   # <class 'numpy.ndarray'>
    print(numpy_array_from_list) # array([1, 2, 3, 4, 5])
```

### Creating float numpy arrays
Creating a float numpy array from list with a float data type parameter
```py
    # Python list
    python_list = [1,2,3,4,5]

    numy_array_from_list2 = np.array(python_list, dtype=float)
    print(numy_array_from_list2) # array([1., 2., 3., 4., 5.])
```

### Creating boolean numpy arrays

Creating a boolean a numpy array from list

```py
    numpy_bool_array = np.array([0, 1, -1, 0, 0], dtype=bool)
    print(numpy_bool_array) # array([False,  True,  True, False, False])
```

#### Creating multidimensional array using numpy

A numpy array may have one or multiple rors and columns

```py
    two_dimensional_list = [[0,1,2], [3,4,5], [6,7,8]]
    numpy_two_dimensional_list = np.array(two_dimensional_list)
    print(type (numpy_two_dimensional_list))
    print(numpy_two_dimensional_list)
```

```sh
    <class 'numpy.ndarray'>
    [[0 1 2]
     [3 4 5]
     [6 7 8]]
```

#### Converting numpy array to list

```python
# We can always convert an array back to a python list using tolist().
np_to_list = numpy_array_from_list.tolist()
print(type (np_to_list))
print('one dimensional array:', np_to_list)
print('two dimensional array: ', numpy_two_dimensional_list.tolist())
```

```sh
    <class 'list'>
    one dimensional array: [1, 2, 3, 4, 5]
    two dimensional array:  [[0, 1, 2], [3, 4, 5], [6, 7, 8]]
```

#### Creating numpy array from tuple

```py
# Numpy array from tuple
# Creating tuple in Python
python_tuple = (1,2,3,4,5)
print(type (python_tuple)) # <class 'tuple'>
print('python_tuple: ', python_tuple) # python_tuple:  (1, 2, 3, 4, 5)

numpy_array_from_tuple = np.array(python_tuple)
print(type (numpy_array_from_tuple)) # <class 'numpy.ndarray'>
print('numpy_array_from_tuple: ', numpy_array_from_tuple) # numpy_array_from_tuple:  [1 2 3 4 5]
```

#### Shape of numpy array

The shape method provide the shape of the array as a tuple. The first is the row and the second is the column. If the array is just one dimensional it returns the size of the array.

```py
    nums = np.array([1, 2, 3, 4, 5])
    print(nums)
    print('shape of nums: ', nums.shape)
    print(numpy_two_dimensional_list)
    print('shape of numpy_two_dimensional_list: ', numpy_two_dimensional_list.shape)
    three_by_four_array = np.array([[0, 1, 2, 3],
        [4,5,6,7],
        [8,9,10, 11]])
    print(three_by_four_array.shape)
```

```sh
    [1 2 3 4 5]
    shape of nums:  (5,)
    [[0 1 2]
     [3 4 5]
     [6 7 8]]
    shape of numpy_two_dimensional_list:  (3, 3)
    (3, 4)
```

#### Data type of numpy array

Type of data types: str, int, float, complex, bool, list, None

```py
int_lists = [-3, -2, -1, 0, 1, 2,3]
int_array = np.array(int_lists)
float_array = np.array(int_lists, dtype=float)

print(int_array)
print(int_array.dtype)
print(float_array)
print(float_array.dtype)
```

```sh
    [-3 -2 -1  0  1  2  3]
    int64
    [-3. -2. -1.  0.  1.  2.  3.]
    float64
```

### Size of a numpy array

In numpy to know the number of items in a numpy array list we use size

```py
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
two_dimensional_list = np.array([[0, 1, 2],
                              [3, 4, 5],
                              [6, 7, 8]])

print('The size:', numpy_array_from_list.size) # 5
print('The size:', two_dimensional_list.size)  # 3

```

```sh
    The size: 5
    The size: 9
```

### Mathematical Operation using numpy

Numpy array is not like exactly like python list. To do mathematical operation in pyhton list we have to loop through the items but numpy can allow to do any mathematical operation without looping.
Mathematical Operation:
* Addition (+)
* Subtraction (-)
* Multiplication (*)
* Division (/)
* Modules (%)
* Floor Division(//)
* Exponential(**)

#### Addition

```py
# Mathematical Operation
# Addition
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
print('original array: ', numpy_array_from_list)
ten_plus_original = numpy_array_from_list  + 10
print(ten_plus_original)

```
```sh
    original array:  [1 2 3 4 5]
    [11 12 13 14 15]
```

#### Subtraction

```python
# Subtraction
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
print('original array: ', numpy_array_from_list)
ten_minus_original = numpy_array_from_list  - 10
print(ten_minus_original)
```
```sh
    original array:  [1 2 3 4 5]
    [-9 -8 -7 -6 -5]
```

### Multiplication

```python
# Multiplication
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
print('original array: ', numpy_array_from_list)
ten_times_original = numpy_array_from_list * 10
print(ten_times_original)
```

```sh
    original array:  [1 2 3 4 5]
    [10 20 30 40 50]
```

#### Division

```python
# Division
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
print('original array: ', numpy_array_from_list)
ten_times_original = numpy_array_from_list / 10
print(ten_times_original)
```

```sh
    original array:  [1 2 3 4 5]
    [0.1 0.2 0.3 0.4 0.5]
```

#### Modulus

```python
# Modulus; Finding the remainder
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
print('original array: ', numpy_array_from_list)
ten_times_original = numpy_array_from_list % 3
print(ten_times_original)
```

```sh
    original array:  [1 2 3 4 5]
    [1 2 0 1 2]
```

#### Floor Division

```py
# Floor division: the division result without the remainder
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
print('original array: ', numpy_array_from_list)
ten_times_original = numpy_array_from_list // 10
print(ten_times_original)
```

#### Exponential

```py
# Exponential is finding some number the power of another:
numpy_array_from_list = np.array([1, 2, 3, 4, 5])
print('original array: ', numpy_array_from_list)
ten_times_original = numpy_array_from_list  ** 2
print(ten_times_original)
```

```sh
    original array:  [1 2 3 4 5]
    [ 1  4  9 16 25]
```

### Checking data types

```py
#Int,  Float numbers
numpy_int_arr = np.array([1,2,3,4])
numpy_float_arr = np.array([1.1, 2.0,3.2])
numpy_bool_arr = np.array([-3, -2, 0, 1,2,3], dtype='bool')

print(numpy_int_arr.dtype)
print(numpy_float_arr.dtype)
print(numpy_bool_arr.dtype)
```

```sh
    int64
    float64
    bool
```

##### Converting types

We can convert the data types of numpy array

1. Int to Float

```py
numpy_int_arr = np.array([1,2,3,4], dtype = 'float')
numpy_int_arr
```
    array([1., 2., 3., 4.])

2. Float to Int

```py
numpy_int_arr = np.array([1., 2., 3., 4.], dtype = 'int')
numpy_int_arr
```

```sh
    array([1, 2, 3, 4])
```

3. Int ot boolean

```py
np.array([-3, -2, 0, 1,2,3], dtype='bool')

```

```sh
    array([ True,  True, False,  True,  True,  True])
```

4. Int to str

```py
numpy_float_list.astype('int').astype('str')
```

```sh
    array(['1', '2', '3'], dtype='<U21')
```

#### Multi-dimensional Arrays

```py
# 2 Dimension Array
two_dimension_array = np.array([(1,2,3),(4,5,6), (7,8,9)])
print(type (two_dimension_array))
print(two_dimension_array)
print('Shape: ', two_dimension_array.shape)
print('Size:', two_dimension_array.size)
print('Data type:', two_dimension_array.dtype)
```

```sh
    <class 'numpy.ndarray'>
    [[1 2 3]
     [4 5 6]
     [7 8 9]]
    Shape:  (3, 3)
    Size: 9
    Data type: int64
```

#### Getting items from a numpy array

```py
# 2 Dimension Array
two_dimension_array = np.array([[1,2,3],[4,5,6], [7,8,9]])
first_row = two_dimension_array[0]
second_row = two_dimension_array[1]
third_row = two_dimension_array[2]
print('First row:', first_row)
print('Second row:', second_row)
print('Third row: ', third_row)
```

```sh
    First row: [1 2 3]
    Second row: [4 5 6]
    Third row:  [7 8 9]
```

```py
first_column= two_dimension_array[:,0]
second_column = two_dimension_array[:,1]
third_column = two_dimension_array[:,2]
print('First column:', first_column)
print('Second column:', second_column)
print('Third column: ', third_column)
print(two_dimension_array)

```

```sh
    First column: [1 4 7]
    Second column: [2 5 8]
    Third column:  [3 6 9]
    [[1 2 3]
     [4 5 6]
     [7 8 9]]
```

#### Slicing Numpy array
Slicing in numpy is similar to slicing in python list

```py
two_dimension_array = np.array([[1,2,3],[4,5,6], [7,8,9]])
first_two_rows_and_columns = two_dimension_array[0:2, 0:2]
print(first_two_rows_and_columns)
```

```sh
    [[1 2]
     [4 5]]
```

#### How to reverse the rows and the whole array?

```py
two_dimension_array[::]
```

```sh
    array([[1, 2, 3],
           [4, 5, 6],
           [7, 8, 9]])
```

#### Reverse the row and column positions

```py
    two_dimension_array = np.array([[1,2,3],[4,5,6], [7,8,9]])
    two_dimension_array[::-1,::-1]
```

```sh
    array([[9, 8, 7],
           [6, 5, 4],
           [3, 2, 1]])
```

#### How to represent missing values ?

```python
    print(two_dimension_array)
    two_dimension_array[1,1] = 55
    two_dimension_array[1,2] =44
    print(two_dimension_array)
```

```sh
    [[1 2 3]
     [4 5 6]
     [7 8 9]]
    [[ 1  2  3]
     [ 4 55 44]
     [ 7  8  9]]
```

```py
    # Numpy Zeroes
    # numpy.zeros(shape, dtype=float, order='C')
    numpy_zeroes = np.zeros((3,3),dtype=int,order='C')
    numpy_zeroes
```

```sh
    array([[0, 0, 0],
           [0, 0, 0],
           [0, 0, 0]])
```

```py
# Numpy Zeroes
numpy_ones = np.ones((3,3),dtype=int,order='C')
print(numpy_ones)
```
```sh
    [[1 1 1]
     [1 1 1]
     [1 1 1]]
```

```py
twoes = numpy_ones * 2
```

```py
# Reshape
# numpy.reshape(), numpy.flatten()
first_shape  = np.array([(1,2,3), (4,5,6)])
print(first_shape)
reshaped = first_shape.reshape(3,2)
print(reshaped)

```

```sh
    [[1 2 3]
     [4 5 6]]
    [[1 2]
     [3 4]
     [5 6]]
```

```py
flattened = reshaped.flatten()
flattened
```

```sh
    array([1, 2, 3, 4, 5, 6])
```

```py
    ## Horitzontal Stack
    np_list_one = np.array([1,2,3])
    np_list_two = np.array([4,5,6])

    print(np_list_one + np_list_two)

    print('Horizontal Append:', np.hstack((np_list_one, np_list_two)))
```

```sh
    [5 7 9]
    Horizontal Append: [1 2 3 4 5 6]
```

```py
    ## Vertical Stack
    print('Vertical Append:', np.vstack((np_list_one, np_list_two)))
```

```sh
    Vertical Append: [[1 2 3]
     [4 5 6]]
```

#### Generating Random Numbers

```py
    # Generate a random float  number
    random_float = np.random.random()
    random_float
```

```sh
    0.018929887384753874
```

```py
    # Generate a random float  number
    random_floats = np.random.random(5)
    random_floats
```

```sh
    array([0.26392192, 0.35842215, 0.87908478, 0.41902195, 0.78926418])
```

```py
    # Generating a random integers between 0 and 10

    random_int = np.random.randint(0, 11)
    random_int
```

```sh
    4
```

```py
    # Generating a random integers between 2 and 11, and creating a one row array
    random_int = np.random.randint(2,10, size=4)
    random_int
```

```sh
    array([8, 8, 8, 2])
```

```py
    # Generating a random integers between 0 and 10
    random_int = np.random.randint(2,10, size=(3,3))
    random_int
```

```sh
    array([[3, 5, 3],
           [7, 3, 6],
           [2, 3, 3]])
```

### Generationg random numbers

```py
    # np.random.normal(mu, sigma, size)
    normal_array = np.random.normal(79, 15, 80)
    normal_array

```

```sh
    array([ 89.49990595,  82.06056961, 107.21445842,  38.69307086,
            47.85259157,  93.07381061,  76.40724259,  78.55675184,
            72.17358173,  47.9888899 ,  65.10370622,  76.29696568,
            95.58234254,  68.14897213,  38.75862686, 122.5587927 ,
            67.0762565 ,  95.73990864,  81.97454563,  92.54264805,
            59.37035153,  77.76828101,  52.30752166,  64.43109931,
            62.63695351,  90.04616138,  75.70009094,  49.87586877,
            80.22002414,  68.56708848,  76.27791052,  67.24343975,
            81.86363935,  78.22703433, 102.85737041,  65.15700341,
            84.87033426,  76.7569997 ,  64.61321853,  67.37244562,
            74.4068773 ,  58.65119655,  71.66488727,  53.42458179,
            70.26872028,  60.96588544,  83.56129414,  72.14255326,
            81.00787609,  71.81264853,  72.64168853,  86.56608717,
            94.94667321,  82.32676973,  70.5165446 ,  85.43061003,
            72.45526212,  87.34681775,  87.69911217, 103.02831489,
            75.28598596,  67.17806893,  92.41274447, 101.06662611,
            87.70013935,  70.73980645,  46.40368207,  50.17947092,
            61.75618542,  90.26191397,  78.63968639,  70.84550744,
            88.91826581, 103.91474733,  66.3064638 ,  79.49726264,
            70.81087439,  83.90130623,  87.58555972,  59.95462521])
```

## Numpy and Statistics

```py
import matplotlib.pyplot as plt
import seaborn as sns
sns.set()
plt.hist(normal_array, color="grey", bins=50)
```

```sh
    (array([2., 0., 0., 0., 1., 2., 2., 0., 2., 0., 0., 1., 2., 2., 1., 4., 3.,
            4., 2., 7., 2., 2., 5., 4., 2., 4., 3., 2., 1., 5., 3., 0., 3., 2.,
            1., 0., 0., 1., 3., 0., 1., 0., 0., 0., 0., 0., 0., 0., 0., 1.]),
     array([ 38.69307086,  40.37038529,  42.04769973,  43.72501417,
             45.4023286 ,  47.07964304,  48.75695748,  50.43427191,
             52.11158635,  53.78890079,  55.46621523,  57.14352966,
             58.8208441 ,  60.49815854,  62.17547297,  63.85278741,
             65.53010185,  67.20741628,  68.88473072,  70.56204516,
             72.23935959,  73.91667403,  75.59398847,  77.27130291,
             78.94861734,  80.62593178,  82.30324622,  83.98056065,
             85.65787509,  87.33518953,  89.01250396,  90.6898184 ,
             92.36713284,  94.04444727,  95.72176171,  97.39907615,
             99.07639058, 100.75370502, 102.43101946, 104.1083339 ,
            105.78564833, 107.46296277, 109.14027721, 110.81759164,
            112.49490608, 114.17222052, 115.84953495, 117.52684939,
            119.20416383, 120.88147826, 122.5587927 ]),
     <a list of 50 Patch objects>)
```

### Matrix in numpy

```py

four_by_four_matrix = np.matrix(np.ones((4,4), dtype=float))
```

```py
four_by_four_matrix
```

```sh
matrix([[1., 1., 1., 1.],
            [1., 1., 1., 1.],
            [1., 1., 1., 1.],
            [1., 1., 1., 1.]])
```

```py
np.asarray(four_by_four_matrix)[2] = 2
four_by_four_matrix
```
```sh

matrix([[1., 1., 1., 1.],
            [1., 1., 1., 1.],
            [2., 2., 2., 2.],
            [1., 1., 1., 1.]])
```

### Numpy numpy.arange()

#### What is Arrange?

Sometimes, you want to create values that are evenly spaced within a defined interval. For instance, you want to create values from 1 to 10; you can use numpy.arange() function

```py
# creating list using range(starting, stop, step)
lst = range(0, 11, 2)
lst
```

```python
range(0, 11, 2)
```

```python
for l in lst:
    print(l)
```

```sh 0
    2
    4
    6
    8
    10
```

```py
# Similar to range arange numpy.arange(start, stop, step)
whole_numbers = np.arange(0, 20, 1)
whole_numbers
```

```sh
array([ 0,  1,  2,  3,  4,  5,  6,  7,  8,  9, 10, 11, 12, 13, 14, 15, 16,
           17, 18, 19])
```

```py
natural_numbers = np.arange(1, 20, 1)
natural_numbers
```

```py
odd_numbers = np.arange(1, 20, 2)
odd_numbers
```

```sh
    array([ 1,  3,  5,  7,  9, 11, 13, 15, 17, 19])
```

```py
even_numbers = np.arange(2, 20, 2)
even_numbers
```

```sh
    array([ 2,  4,  6,  8, 10, 12, 14, 16, 18])
```

### Creating sequence of numbers using linspace

```py
# numpy.linspace()
# numpy.logspace() in Python with Example
# For instance, it can be used to create 10 values from 1 to 5 evenly spaced.
np.linspace(1.0, 5.0, num=10)
```

```sh
    array([1.        , 1.44444444, 1.88888889, 2.33333333, 2.77777778,
           3.22222222, 3.66666667, 4.11111111, 4.55555556, 5.        ])
```

```py
# not to include the last value in the interval
np.linspace(1.0, 5.0, num=5, endpoint=False)
```

```
array([1. , 1.8, 2.6, 3.4, 4.2])
```

```py
# LogSpace
# LogSpace returns even spaced numbers on a log scale. Logspace has the same parameters as np.linspace.

# Syntax:

# numpy.logspace(start, stop, num, endpoint)

np.logspace(2, 4.0, num=4)
```

```sh

array([  100.        ,   464.15888336,  2154.43469003, 10000.        ])
```

```py
# to check the size of an array
x = np.array([1,2,3], dtype=np.complex128)
```

```py
x
```

```sh
    array([1.+0.j, 2.+0.j, 3.+0.j])
```

```py
x.itemsize
```

```sh
16
```

```py
# indexing and Slicing NumPy Arrays in Python
np_list = np.array([(1,2,3), (4,5,6)])
np_list

```

```sh
    array([[1, 2, 3],
           [4, 5, 6]])
```

```py
print('First row: ', np_list[0])
print('Second row: ', np_list[1])
```

```sh
    First row:  [1 2 3]
    Second row:  [4 5 6]
```

```p
print('First column: ', np_list[:,0])
print('Second column: ', np_list[:,1])
print('Third column: ', np_list[:,2])

```

```sh
    First column:  [1 4]
    Second column:  [2 5]
    Third column:  [3 6]
```

### NumPy Statistical Functions with Example

NumPy has quite useful statistical functions for finding minimum, maximum, mean, median, percentile,standard deviation and variance, etc from the given elements in the array.
The functions are explained as follows −
Statistical function
Numpy is equipped with the robust statistical function as listed below

- Numpy Functions
  - Min np.min()
  - Max np.max()
  - Mean np.mean()
  - Median np.median()
  - Varience
  - Percentile
  - Standard deviation np.std()

```python
np_normal_dis = np.random.normal(5, 0.5, 100)
np_normal_dis
## min, max, mean, median, sd
print('min: ', two_dimension_array.min())
print('max: ', two_dimension_array.max())
print('mean: ',two_dimension_array.mean())
# print('median: ', two_dimension_array.median())
print('sd: ', two_dimension_array.std())
```

    min:  1
    max:  55
    mean:  14.777777777777779
    sd:  18.913709183069525

```python
min:  1
max:  55
mean:  14.777777777777779
sd:  18.913709183069525
```

```python
print(two_dimension_array)
print('Column with minimum: ', np.amin(two_dimension_array,axis=0))
print('Column with maximum: ', np.amax(two_dimension_array,axis=0))
print('=== Row ==')
print('Row with minimum: ', np.amin(two_dimension_array,axis=1))
print('Row with maximum: ', np.amax(two_dimension_array,axis=1))
```

    [[ 1  2  3]
     [ 4 55 44]
     [ 7  8  9]]
    Column with minimum:  [1 2 3]
    Column with maximum:  [ 7 55 44]
    === Row ==
    Row with minimum:  [1 4 7]
    Row with maximum:  [ 3 55  9]

### How to create repeating sequences?

```python
a = [1,2,3]

# Repeat whole of 'a' two times
print('Tile:   ', np.tile(a, 2))

# Repeat each element of 'a' two times
print('Repeat: ', np.repeat(a, 2))

```

    Tile:    [1 2 3 1 2 3]
    Repeat:  [1 1 2 2 3 3]

### How to generate random numbers?

```python
# One random number between [0,1)
one_random_num = np.random.random()
one_random_in = np.random
print(one_random_num)
```

    0.6149403282678213

```python
0.4763968133790438
```

    0.4763968133790438

```python
# Random numbers between [0,1) of shape 2,3
r = np.random.random(size=[2,3])
print(r)
```

    [[0.13031737 0.4429537  0.1129527 ]
     [0.76811539 0.88256594 0.6754075 ]]



```python
print(np.random.choice(['a', 'e', 'i', 'o', 'u'], size=10))
```

    ['u' 'o' 'o' 'i' 'e' 'e' 'u' 'o' 'u' 'a']



```python
['i' 'u' 'e' 'o' 'a' 'i' 'e' 'u' 'o' 'i']
```




    ['iueoaieuoi']




```python
## Random numbers between [0, 1] of shape 2, 2
rand = np.random.rand(2,2)
rand
```




    array([[0.97992598, 0.79642484],
           [0.65263629, 0.55763145]])




```python
rand2 = np.random.randn(2,2)
rand2

```




    array([[ 1.65593322, -0.52326621],
           [ 0.39071179, -2.03649407]])




```python
# Random integers between [0, 10) of shape 2,5
rand_int = np.random.randint(0, 10, size=[5,3])
rand_int
```




    array([[0, 7, 5],
           [4, 1, 4],
           [3, 5, 3],
           [4, 3, 8],
           [4, 6, 7]])




```py
from scipy import stats
np_normal_dis = np.random.normal(5, 0.5, 1000) # mean, standard deviation, number of samples
np_normal_dis
## min, max, mean, median, sd
print('min: ', np.min(np_normal_dis))
print('max: ', np.max(np_normal_dis))
print('mean: ', np.mean(np_normal_dis))
print('median: ', np.median(np_normal_dis))
print('mode: ', stats.mode(np_normal_dis))
print('sd: ', np.std(np_normal_dis))
```
```sh

    min:  3.557811005458804
    max:  6.876317743643499
    mean:  5.035832048106663
    median:  5.020161980441937
    mode:  ModeResult(mode=array([3.55781101]), count=array([1]))
    sd:  0.489682424165213

```

```python
plt.hist(np_normal_dis, color="grey", bins=21)
plt.show()
```


![png](test_files/test_121_0.png)



```python
# numpy.dot(): Dot Product in Python using Numpy
# Dot Product
# Numpy is powerful library for matrices computation. For instance, you can compute the dot product with np.dot

# Syntax

# numpy.dot(x, y, out=None)
```


### Linear Algebra
1. Dot Product


```python
## Linear algebra
### Dot product: product of two arrays
f = np.array([1,2,3])
g = np.array([4,5,3])
### 1*4+2*5 + 3*6
np.dot(f, g)  # 23
```
    
### NumPy Matrix Multiplication with np.matmul()

```python
### Matmul: matruc product of two arrays
h = [[1,2],[3,4]]
i = [[5,6],[7,8]]
### 1*5+2*7 = 19
np.matmul(h, i)
```
```sh
    array([[19, 22],
           [43, 50]])

```
```py
## Determinant 2*2 matrix
### 5*8-7*6np.linalg.det(i)
```

```python
np.linalg.det(i)
```
    -1.999999999999999


```python
Z = np.zeros((8,8))
Z[1::2,::2] = 1
Z[::2,1::2] = 1
```

```python
Z
```
    array([[0., 1., 0., 1., 0., 1., 0., 1.],
           [1., 0., 1., 0., 1., 0., 1., 0.],
           [0., 1., 0., 1., 0., 1., 0., 1.],
           [1., 0., 1., 0., 1., 0., 1., 0.],
           [0., 1., 0., 1., 0., 1., 0., 1.],
           [1., 0., 1., 0., 1., 0., 1., 0.],
           [0., 1., 0., 1., 0., 1., 0., 1.],
           [1., 0., 1., 0., 1., 0., 1., 0.]])

```python
new_list = [ x + 2 for x in range(0, 11)]
```
```python
new_list
```

    [2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]

```python
[2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]
```
    [2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]

```python
np_arr = np.array(range(0, 11))
np_arr + 2
```
 array([ 2,  3,  4,  5,  6,  7,  8,  9, 10, 11, 12])

We use linear equation for quatities which have linear relationship. Let's see the example below:

```python
temp = np.array([1,2,3,4,5])
pressure = temp * 2 + 5
pressure
```

array([ 7,  9, 11, 13, 15])


```python
plt.plot(temp,pressure)
plt.xlabel('Temperature in oC')
plt.ylabel('Pressure in atm')
plt.title('Temperature vs Pressure')
plt.xticks(np.arange(0, 6, step=0.5))
plt.show()
```

![png](test_files/test_141_0.png)

To draw the Gaussian normal distribution using numpy. As you can see below, the numpy can generate random numbers. To create random sample, we need the mean(mu), sigma(standard deviation), mumber of data points.


```python
mu = 28
sigma = 15
samples = 100000

x = np.random.normal(mu, sigma, samples)
ax = sns.distplot(x);
ax.set(xlabel="x", ylabel='y')
plt.show()
```

![png](test_files/test_143_0.png)

# Summery

To summarise, the main differences with python lists are:

1. Arrays support vectorised operations, while lists don’t.
1. Once an array is created, you cannot change its size. You will have to create a new array or overwrite the existing one.
1. Every array has one and only one dtype. All items in it should be of that dtype.
1. An equivalent numpy array occupies much less space than a python list of lists.
1. numpy arrays support boolean indexing.

## 💻 Exercises: 
1. Repeat all the examples

## Pandas

Pandas is an open source,high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
Pandas adds data structures and tools designed to work with table-like data which is Series and Data Frames
Pandas provides tools for data manipulation: reshaping, merging, sorting, slicing, aggregation and imputation.
```py
pip install conda
conda install pandas
```
Pandas data structure is based on *Series* and *DataFrames*
A series is a column and a DataFrame is a multidimensional table made up of collection of series. In order to create a pandas series we should use numpy to create a one dimensional arrays or a python list.
Let's see an example of a series:

Names pandas Series

![pandas series](./mages/pandas-series-1.png) 

Countries Series

![pandas series](./images/pandas-series-2.png) 

Cities Series

![pandas series](./images/pandas-series-3.png)

As you can see, pandas series is just one column data. If we want to have multiple columns we use data frames. The example below shows pandas DataFrames.

Let's see, an example of a pandas data frame:

![Pandas data frame](./images/pandas-dataframe-1.png)

Data from is a collection of rows and columns. Look at the table below it has many columns than the above


![Pandas data frame](./images/pandas-dataframe-2.png)

Next, we will see how to import pandas and how to create Series and DataFrames using pandas

## Importing pandas


```python
import pandas as pd # importing pandas as pd
import numpy  as np # importing numpy as np
```

### Creating Pandas Series with default index


```python
nums = [1, 2, 3, 4,5]
s = pd.Series(nums)
s
```




    0    1
    1    2
    2    3
    3    4
    4    5
    dtype: int64



### Creating  Pandas Series with custom index


```python
nums = [1, 2, 3, 4, 5]
s = pd.Series(nums, index=[1, 2, 3, 4, 5])
s

```



    1    1
    2    2
    3    3
    4    4
    5    5
    dtype: int64


```python
fruits = ['Orange','Banana','Mangao']
fruits = pd.Series(fruits, index=[1, 2, 3])
fruits
```




    1    Orange
    2    Banana
    3    Mangao
    dtype: object



### Creating Pandas Series from a dictionary


```python
dct = {'name':'Asabeneh','country':'Finland','city':'Helsinki'}
```


```python
s = pd.Series(dct)
s
```


    name       Asabeneh
    country     Finland
    city       Helsinki
    dtype: object



### Creating a constant pandas series


```python
s = pd.Series(10, index = [1, 2,3])
s
```




    1    10
    2    10
    3    10
    dtype: int64



### Creating a  pandas series using linspace


```python
s = pd.Series(np.linspace(5, 20, 10)) # linspace(starting, end, items)
s
```




    0     5.000000
    1     6.666667
    2     8.333333
    3    10.000000
    4    11.666667
    5    13.333333
    6    15.000000
    7    16.666667
    8    18.333333
    9    20.000000
    dtype: float64


## DataFrames

Pandas data frames can be created in different ways.

### Creating DataFrames from list of lists


```python
data = [
    ['Asabeneh', 'Finland', 'Helsink'], 
    ['David', 'UK', 'London'],
    ['John', 'Sweden', 'Stockholm']
]
df = pd.DataFrame(data, columns=['Names','Country','City'])
df

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Names</th>
      <th>Country</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsink</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
    </tr>
  </tbody>
</table>
</div>



### Creating DataFrame using Dictionary


```python
data = {'Name': ['Asabeneh', 'David', 'John'], 'Country':[
    'Finland', 'UK', 'Sweden'], 'City': ['Helsiki', 'London', 'Stockholm']}
df = pd.DataFrame(data)
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsiki</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
    </tr>
  </tbody>
</table>
</div>




```python

```

### Creating DataFrams from list of dictionaries


```python
data = [
    {'Name': 'Asabeneh', 'Country': 'Finland', 'City': 'Helsinki'},
    {'Name': 'David', 'Country': 'UK', 'City': 'London'},
    {'Name': 'John', 'Country': 'Sweden', 'City': 'Stockholm'}]
df = pd.DataFrame(data)
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
    </tr>
  </tbody>
</table>
</div>



## Reading CSV File using pandas


```python
import pandas as pd

df = pd.read_csv('./data/weight-height.csv')
```

### Data Exploration
Let's read only the first 5 rows using head()


```python
df.head() # give five rows we can increase the number of rows by passing argument to the head() method
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Gender</th>
      <th>Height</th>
      <th>Weight</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Male</td>
      <td>73.847017</td>
      <td>241.893563</td>
    </tr>
    <tr>
      <td>1</td>
      <td>Male</td>
      <td>68.781904</td>
      <td>162.310473</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Male</td>
      <td>74.110105</td>
      <td>212.740856</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Male</td>
      <td>71.730978</td>
      <td>220.042470</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Male</td>
      <td>69.881796</td>
      <td>206.349801</td>
    </tr>
  </tbody>
</table>
</div>



As you can see the csv file has three rows:Gender, Height and Weight. But we don't know the number of rows. Let's use shape meathod.


```python
df.shape # as you can see 10000 rows and three columns
```


    (10000, 3)



Let's get all the columns using columns.



```python
df.columns
```




    Index(['Gender', 'Height', 'Weight'], dtype='object')



Let's read only the last 5 rows using tail()


```python
df.tail() # tails give the last five rows, we can increase the rows by passing argument to tail method
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Gender</th>
      <th>Height</th>
      <th>Weight</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>9995</td>
      <td>Female</td>
      <td>66.172652</td>
      <td>136.777454</td>
    </tr>
    <tr>
      <td>9996</td>
      <td>Female</td>
      <td>67.067155</td>
      <td>170.867906</td>
    </tr>
    <tr>
      <td>9997</td>
      <td>Female</td>
      <td>63.867992</td>
      <td>128.475319</td>
    </tr>
    <tr>
      <td>9998</td>
      <td>Female</td>
      <td>69.034243</td>
      <td>163.852461</td>
    </tr>
    <tr>
      <td>9999</td>
      <td>Female</td>
      <td>61.944246</td>
      <td>113.649103</td>
    </tr>
  </tbody>
</table>
</div>



Now, lets get specif colums using the column key



```python
heights = df['Height'] # this is now a a series
```


```python
heights
```


    0       73.847017
    1       68.781904
    2       74.110105
    3       71.730978
    4       69.881796
              ...    
    9995    66.172652
    9996    67.067155
    9997    63.867992
    9998    69.034243
    9999    61.944246
    Name: Height, Length: 10000, dtype: float64




```python
weights = df['Weight'] # this is now a series
```


```python
weights
```


    0       241.893563
    1       162.310473
    2       212.740856
    3       220.042470
    4       206.349801
               ...    
    9995    136.777454
    9996    170.867906
    9997    128.475319
    9998    163.852461
    9999    113.649103
    Name: Weight, Length: 10000, dtype: float64




```python
len(heights) == len(weights)
```

    True


```python
heights.describe() # give statisical information about height data
```

    count    10000.000000
    mean        66.367560
    std          3.847528
    min         54.263133
    25%         63.505620
    50%         66.318070
    75%         69.174262
    max         78.998742
    Name: Height, dtype: float64


```python
weights.describe()
```

    count    10000.000000
    mean       161.440357
    std         32.108439
    min         64.700127
    25%        135.818051
    50%        161.212928
    75%        187.169525
    max        269.989699
    Name: Weight, dtype: float64




```python
df.describe()  # describe can also give statistical information from a datafrom
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Height</th>
      <th>Weight</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>count</td>
      <td>10000.000000</td>
      <td>10000.000000</td>
    </tr>
    <tr>
      <td>mean</td>
      <td>66.367560</td>
      <td>161.440357</td>
    </tr>
    <tr>
      <td>std</td>
      <td>3.847528</td>
      <td>32.108439</td>
    </tr>
    <tr>
      <td>min</td>
      <td>54.263133</td>
      <td>64.700127</td>
    </tr>
    <tr>
      <td>25%</td>
      <td>63.505620</td>
      <td>135.818051</td>
    </tr>
    <tr>
      <td>50%</td>
      <td>66.318070</td>
      <td>161.212928</td>
    </tr>
    <tr>
      <td>75%</td>
      <td>69.174262</td>
      <td>187.169525</td>
    </tr>
    <tr>
      <td>max</td>
      <td>78.998742</td>
      <td>269.989699</td>
    </tr>
  </tbody>
</table>
</div>



## Modifying DataFrame



Modifying a DataFrame
    * We can create a new DataFrame
    * We can create a new column and add to DataFrame, 
    * we can remove an existing column from DataFrame, 
    * we can modify an existing column from DataFrame, 
    * we can change the data type of column values from DataFrame

### Create a DataFrame
All the time, first we import the necessary packages. Now, lets import pandas and numpy two best friends ever.


```python
import pandas as pd
import numpy as np
data = [
    {"Name": "Asabeneh", "Country":"Finland","City":"Helsinki"},
    {"Name": "David", "Country":"UK","City":"London"},
    {"Name": "John", "Country":"Sweden","City":"Stockholm"}]
df = pd.DataFrame(data)
df
```


<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
    </tr>
  </tbody>
</table>
</div>



Adding column in DataFrame is like adding a key in dictionary.

First let's use the previous example to create a DataFrame. After we create the DataFrame,  we will start modifying the columns and column values.

### Adding new column
Let's add a weight column in the DataFrame


```python
weights = [74, 78, 69]
df['Weight'] = weights
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
    </tr>
  </tbody>
</table>
</div>


Let's add a height column in the DataFrame


```python
heights = [173, 175, 169]
df['Height'] =heights
df
```


<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
      <td>173</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
      <td>175</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
      <td>169</td>
    </tr>
  </tbody>
</table>
</div>


As you can see from the above DataFrame, now we new added columns, the Weight and Height. Let's add one additional column by called BMI(Body Mass Index) by calculating their BMI using thier mass and height. BMI is mass divided by height square meter(Weight/Height * Height).

As you can see, the hieght is in centimeter, so we shoud change the height to meter. So, let's modify the height row

### Modifying column values


```python
df['Height'] = df['Height'] * 0.01
df

```

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
      <td>1.73</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
      <td>1.75</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
      <td>1.69</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Using function makes our code clean but you can just calculate the bmi without function
def calculate_bmi ():
    weights = df['Weight']
    heights = df['Height']
    bmi = []
    for w,h in zip(weights, heights):
        b = w/(h*h)
        bmi.append(b)
    return bmi
    
bmi = calculate_bmi()

```


```python
df['BMI'] = bmi
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
      <th>BMI</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
      <td>1.73</td>
      <td>24.725183</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
      <td>1.75</td>
      <td>25.469388</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
      <td>1.69</td>
      <td>24.158818</td>
    </tr>
  </tbody>
</table>
</div>



### Formating DataFrame column

The BMI of the above DataFrame has is float with many significant digits after decimal. Let's make it to have only one significant digit after point.

```python
df['BMI'] = round(df['BMI'], 1)
df
```

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
      <th>BMI</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
      <td>1.73</td>
      <td>24.7</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
      <td>1.75</td>
      <td>25.5</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
      <td>1.69</td>
      <td>24.2</td>
    </tr>
  </tbody>
</table>
</div>


The information in the DataFrame seems not yet complete, let's add birth year and current year columns.


```python
birth_year = ['1769', '1985', '1990']
current_year = pd.Series(2019, index=[0, 1,2])
df['Birth Year'] = birth_year
df['Current Year'] = current_year
df
```

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
      <th>BMI</th>
      <th>Birth Year</th>
      <th>Current Year</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
      <td>1.73</td>
      <td>24.7</td>
      <td>1769</td>
      <td>2019</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
      <td>1.75</td>
      <td>25.5</td>
      <td>1985</td>
      <td>2019</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
      <td>1.69</td>
      <td>24.2</td>
      <td>1990</td>
      <td>2019</td>
    </tr>
  </tbody>
</table>
</div>



## Checking data types of Column values


```python
df.Weight.dtype
```




    dtype('int64')




```python
df['Birth Year'].dtype # it give string object , we should change this to number

```




    dtype('O')




```python
df['Birth Year'] = df['Birth Year'].astype('int')
df['Birth Year'].dtype # let's check the data type now
```




    dtype('int64')




```python
df['Current Year'] = df['Current Year'].astype('int')
df['Current Year'].dtype
```




    dtype('int64')



Now, the column values of birth year and current year are integers. We can calculate the age.


```python
ages = df['Current Year'] - df['Birth Year']
ages
```




    0    250
    1     34
    2     29
    dtype: int64




```python
df['Ages'] = ages
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
      <th>BMI</th>
      <th>Birth Year</th>
      <th>Current Year</th>
      <th>Ages</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
      <td>1.73</td>
      <td>24.7</td>
      <td>1769</td>
      <td>2019</td>
      <td>250</td>
    </tr>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
      <td>1.75</td>
      <td>25.5</td>
      <td>1985</td>
      <td>2019</td>
      <td>34</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
      <td>1.69</td>
      <td>24.2</td>
      <td>1990</td>
      <td>2019</td>
      <td>29</td>
    </tr>
  </tbody>
</table>
</div>



The person in the first row lives 250 years. It is unlikely for someone to live 250 years. Either it is a typo or the data is cooked. So lets fill that data with average of the columns without including outlier. 

mean = (34 + 29)/ 2


```python
mean = (34 + 29)/ 2
mean
```




    31.5



### Boolean Indexing


```python
df[df['Ages'] > 120]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
      <th>BMI</th>
      <th>Birth Year</th>
      <th>Current Year</th>
      <th>Ages</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Asabeneh</td>
      <td>Finland</td>
      <td>Helsinki</td>
      <td>74</td>
      <td>1.73</td>
      <td>24.7</td>
      <td>1769</td>
      <td>2019</td>
      <td>250</td>
    </tr>
  </tbody>
</table>
</div>




```python
df[df['Ages'] < 120]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Name</th>
      <th>Country</th>
      <th>City</th>
      <th>Weight</th>
      <th>Height</th>
      <th>BMI</th>
      <th>Birth Year</th>
      <th>Current Year</th>
      <th>Ages</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>David</td>
      <td>UK</td>
      <td>London</td>
      <td>78</td>
      <td>1.75</td>
      <td>25.5</td>
      <td>1985</td>
      <td>2019</td>
      <td>34</td>
    </tr>
    <tr>
      <td>2</td>
      <td>John</td>
      <td>Sweden</td>
      <td>Stockholm</td>
      <td>69</td>
      <td>1.69</td>
      <td>24.2</td>
      <td>1990</td>
      <td>2019</td>
      <td>29</td>
    </tr>
  </tbody>
</table>
</div>


```python
df['Ages']  = df[df['Ages'] > 120]
        
        
```

## Exercises: 

1. Read the hacker_ness.csv file from data directory 
1. Get the first five rows
1. Get the last five rows
1. Get the title column as pandas series
1. Count the number of rows and columns
 * Filter the titles which contain python
 * Filter the titles which contain JavaScript
 * Explore the data and make sense of the data

<h1 align="center" style="color:#306998;font-size:64px;">Challenges Coming ...</h1>

Write python comment
Declare different varaibles
Check different data tyypes
Concatinate strings
Write some code that creates a list of integers,
loops through each element of the list,
and only prints out even numbers!

```python
list_nums = range(100);
print(list(list_nums))
```

    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 91, 92, 93, 94, 95, 96, 97, 98, 99]

```python
def sum_of_evens_and_sum_of_odds (n):
    numbers = range(n)
    evens_sum = 0;
    odds_sum = 0;
    for n in numbers:
        if n % 2 == 0 :
            evens_sum = evens_sum + n
        else:
            odds_sum = odds_sum + n;
    return [evens_sum, odds_sum]

```

```python
sum_of_evens_and_sum_of_odds(101)
```

    [2550, 2500]

```python

```
