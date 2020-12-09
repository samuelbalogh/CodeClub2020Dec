# Python cheatsheet

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


## Variables

We declare variables by assigning a **value** to a **name**:

```
>>> favourite_food = 'mac and cheese'
```

The name of a variable can not contain whitespaces. 


