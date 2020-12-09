# Python cheatsheet

Table of contents

<!-- toc -->

- [Whitespace](#whitespace)
- [Comments](#comments)
- [Variables](#variables)
- [Data types](#data-types)
  * [Numeric types](#numeric-types)
  * [Strings](#strings)
  * [Booleans](#booleans)
  * [Lists](#lists)
- [Functions](#functions)

<!-- tocstop -->

## Whitespace

For Python, **whitespaces** (spaces and tabs) in our code are significant.  
They are used to declare a "code block" - for example, the code of a function body is separated from the outer code by one level of indentation.

```
def find_meaning_of_life():
    return 42
```

As another example, the bodies of if/else statements are also indented by one level:

```
favourite_food = 'beer'

my_fridge = ['beer', 'pizza']

if favourite_food in my_fridge:
    print('Yaay!')
else:
    print('Sad! :(')
```

For whitespace, you can use either spaces or tabs (but not both).

## Comments

```
# Lines starting with # are comments
# These are not evaluated by Python, they are completely ignored, 
# So we can use this to document our code for others
```

## Variables

We declare variables by assigning a **value** to a **name**:
We do this to be able to **re-use** these values in our code, and so we don't have to repeat ourselves.

```
favourite_food = 'mac and cheese'
```

In the above example, we have assigned the value `mac and cheese` to the name `favourite_food`.


A variable can be of any data type. In the above example, the `favourite_food` variable is a string. In the following example, we assing an integer type to the variable named `meaning_of_life`:  

```
meaning_of_life = 42
```


## Data types

### Numeric types

- integers: `1, 2, 42`  
- floats: `3.0, 1.232, .01`

(There is a data type for complex numbers, but their usage is very rare)

#### Common operations 

We can use the common mathematical operations on numbers: `+`, `-`, `*`, `**` (exponent), `/`, `//`, `%` (modulo)

> Note: when you see the `>>>` sign, it refers to the interactive interpreter of Python: it's the "prompt" of Python. This is what you see when you start up Python on your computer.

```
>>> 5 * 5
25
```

```
>>> 3 ** 3
27
```

```
>>> 15 / 4
3.75
```

The `//` operator does "floor division":

```
>>> 15 // 4
3
```

The modulo (`%`) gives you the **remainder** of a division:

```
>>> 15 % 4
3
```

```
>>> IBM_stock_price_yesterday = 126
>>> IBM_stock_price_today = 127
>>> stock_price_change = IBM_stock_price_today - IBM_stock_price_yesterday
>>> stock_price_change
1
```


### Strings


Strings represent **text**. They are between single or double quotes.

```
food = 'spaghetti'
```

[Python docs](https://docs.python.org/3/tutorial/introduction.html?fbclid=IwAR3knUj3nO0-f2fYMS5Yb5MbGplB93buRymiE_07F06rufql14v5bKrzErk#strings)


#### Common operations

We can make strings uppercase, lowercase, capitalized:

```
>>> 'broccoli'.upper()
'BROCCOLI'
>>> 'BEER'.lower()
'beer`
>>> 'joe'.capitalize()
'Joe'
```


### Booleans

Values representing "Boolean logic": True/False. 

`True` and `False` are the only boolean values.

[A good article about booleans](https://thomas-cokelaer.info/tutorials/python/boolean.html?fbclid=IwAR0mg4nzR6uQ4JvneWMGzLH6yiYzeb4Lo_C83ddo5vwXAcy_-lRdH61Q-Gw#notes-about-booleans-and-logical-operators)


#### Common operations


### Lists

Lists are used to group together values. 

```
squares = [1, 4, 9, 16, 25]
```

You can put any data type into a list.

[Python docs](https://docs.python.org/3/tutorial/introduction.html?fbclid=IwAR3knUj3nO0-f2fYMS5Yb5MbGplB93buRymiE_07F06rufql14v5bKrzErk#lists)
[More on lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)

#### Common operations

Lists are very versatile, you can do a lot of things with them.

You add an item to a list with the `append()` function:

```
>>> my_list = [1, 2, 3]
>>> my_list.append(4)
>>> my_list
[1, 2, 3, 4]
```


## Functions

We write functions to be able to **re-use our code** - we don't like copy-pasting a lot.

A function definition can look like the following:

```
def calculate_the_meaning_of_life(arg):
    return arg + 42
```

Some imporant points:

- The definition must start with the `def` keyword
- After the `def` keyword, we have to give a **name** to our function
- After the name, there must to be an opening parenthesis ( `(` character), after which, there can be zero or more **arguments**, then a closing parenthesis, then a colon (`:`) character. 
- The function body is **indented** by one level
- Usually a function has a **return value** which is denoted by the `return` statement. However, it's not obligatory to have a return value - a function can just return nothing, or print something, or modify something (we will look at examples for each of these later).

Arguments can be considered as the "input" to your function - you get some data in the arguments, you do something with them in the function body, and you return something.


A very detailed article about functions can be read [here](https://realpython.com/defining-your-own-python-function/#functions-in-python). 




