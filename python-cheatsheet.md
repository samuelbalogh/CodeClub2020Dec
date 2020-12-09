# Python cheatsheet

<!-- toc -->

- [Whitespace](#whitespace)
- [Comments](#comments)
- [Variables](#variables)
- [Data types](#data-types)
  * [Numeric types](#numeric-types)
  * [Strings](#strings)
    + [Common operations](#common-operations)
  * [Booleans](#booleans)
    + [Common operations](#common-operations-1)
  * [Lists](#lists)
    + [Common operations](#common-operations-2)

<!-- tocstop -->

## Whitespace

For Python, **whitespaces** (spaces and tabs) in our code are significant.  
They are used to declare a "code block" - for example, the code of a function body is separated from the outer code by one level of indentation.

```
def find_meaning_of_life():
    return 42
```

As another example, if/else statements are also indented by one level:

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

```
favourite_food = 'mac and cheese'
```

In the above example, we have assigned the value `mac and cheese` to the name `favourite_food`.

We do this to be able to **re-use** these values in our code, and so we don't have to repeat ourselves.


## Data types

### Numeric types

- integers: `1, 2, 42`  
- floats: `3.0, 1.232, .01`

There are also complex numbers but their usage is very rare.

#### Common operations 

We can use the common mathematical operations on numbers: `+`, `-`, `*`, `**` (exponent), `/`, `//`, `%` (modulo)

```
>>> 5 * 5
25
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

#### Common operations


### Booleans

Values representing "Boolean logic": True/False. 

`True` and `False` are the only boolean values.


#### Common operations


### Lists

Lists are used to group together values. 

```
squares = [1, 4, 9, 16, 25]
```

You can put any data type into a list.

#### Common operations





