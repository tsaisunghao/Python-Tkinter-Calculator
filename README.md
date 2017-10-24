# Python Tkinter Calculator

A calculator developed in Python using the standard Tkinter library. This project focused on creating an interactive GUI, with key bindings, in order to achieve an interface that is user-friendly. 

## Running the Program

Within the calulcator, the user will be able to use keyboard or button inputs. When the the operation is submitted, Python will evaluate the string using the eval() method to determine the solution. The eval function allows for standard order of operations to be recognized. 

**Ex:**

```
string = ""
string += "1+2" # Operation submitted by user
print(eval(string)) # Will print an evaluated string
```

## Functionality

This calculator can support parentheses use and decimal numbers. It can support basic operations such as:

* Addition
* Subtraction
* Multiplication
* Division
* Squareroot
* Exponents

However, this calculator does not allow for implicit multiplication. For example, if the user was to input:

```
(1+2)(2+1) # 3*3 = 9
# Correct: (1+2)*(2+1)
```

The calulcator would yield an "Invalid Input" error.

## Errors

The calculator will output an "Invalid Input" message if the user has submitted their problem incorrectly. This message can easily be cleared by beginning another query or by using the clear buttons.

## Author

* **Thomas Taylor**
