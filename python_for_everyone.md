<div align="center">

  <h1 align="center" style="background-color:#306998;color:#FFD43B;font-size:64px;font-family:sans;padding:20px">PYTHON FOR EVERYONE<h1>

  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

<sub>Author:
<a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
<small> First Edition: July 2019</small>
</sub>

</div>
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
   Output:
   ```sh
   Enter your age: 30
   You are old enough to drive.
   ```
   Output:
   ```sh
   Enter your age:15
   You are left with 3 years to drive.
   ```
1. Compare the values of myAge and yourAge using if … else. Based on the comparison log to console who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.
   Output:
   ```sh
   Enter your age: 30
   You are 5 years older than me.
   ```
1. If a is greater than b return a is greater than b else a is less than b.
   Output:
   `sh let a = 4; let b = 3; 4 is greater than 3`
1. Write a code which give grade students according to theirs scores:
   - 80-100, A
   - 70-89, B
   - 60-69, C
   - 50-59, D
   - 0 -49, F
1. Check if the season is Autumn, Winter, Spring or Summer.
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
nums_sorted = sorted(nums_two) # mutate the original list
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

<h1 align="center" style="color:#306998;font-size:64px;">REGULAR EXPRESSONS</h1>

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

<h1 align="center" style="color:#306998;font-size:64px;">NUMPY<h1>

```python
import numpy as np

# Creating an list using np.array

x = np.array([0,1,2,3,4,5])
print(x.reshape(2,3))
print(x.ndim)
y = np.arange(10)
print(y)
print(len(x))
print(x)
```

    [[0 1 2]
     [3 4 5]]
    1
    [0 1 2 3 4 5 6 7 8 9]
    6
    [0 1 2 3 4 5]

<h1 align="center" style="color:#306998;font-size:64px;">PANDAS<h1>

<h1 align="center" style="color:#306998;font-size:64px;">Challenges Coming ...<h1>

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
