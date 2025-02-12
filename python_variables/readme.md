## What is a Variable?

A variable in Python is a container for storing data values. It acts as a container for data, allowing you to reference and manipulate it throughout your code.In other words it acts like a labeled box where you can store different types of information and retrieve them later.

 Example:
Imagine a box labeled `"favorite_color"`. If you put `"blue"` inside, that box now holds `"blue"`.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/flhf4eeby8ykhy52o46q.jpeg)

## Declaring Variables

A variable is created the moment you first assign a value to it. Python variables are dynamically typed, meaning you don’t need to specify their data type. The type is assigned automatically based on the value.



![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ploqvybzhkw7hen9esh4.jpeg)

```javascript
name = "Vayola"
age = 12
score = 95.5

```
**What happens here?**

`name` holds the text "`Vayola`".
`age` holds the number `12`.
`score` holds a decimal number `95.5`.

## Variable Naming Rules

Must start with a letter (`a-z`, `A-Z`) or an underscore (`_`).

    - Valid: `name`, `_age`, `Name1`

    - Invalid: `1name`, `@age`

Cannot start with a number.

    - Valid: `age1`

    - Invalid: `1age`

Can only contain alphanumeric characters and underscores (`A-Z`, `a-z`, `0-9`,` _`).

    - Valid: `user_name`, `age_1`

    - Invalid: `user-name`, `age#1`

Case-sensitive: `myVar` and `myvar` are different variables.

Cannot be a reserved keyword (e.g., `if`, `else`, `for`, `while`, etc.).

**Examples of Variable Assignments**

```javascript
# Integer
x = 10

# Float
y = 20.5

# String
name = "Vayola"

# Boolean
is_valid = True

# List
my_list = [1, 2, 3, 4]

# Tuple
my_tuple = (1, 2, 3)

# Dictionary
my_dict = {"name": "Vayola", "age": 25}

# Set
my_set = {1, 2, 3}
```

## Variable Types

Python supports various data types, and the type of a variable is determined by the value it holds. Common types include:

```javascript
Integer: x = 10  //Integer
Float: y = 20.5 //Float
String: name = "Vayola" //String
Boolean: is_valid = True //Boolean
List: my_list = [1, 2, 3] //List
Tuple: my_tuple = (1, 2, 3) //Tuple
Dictionary: my_dict = {"name": "Alice", "age": 25} //Dictionary
Set: my_set = {1, 2, 3} //Set
```

You can check the type of a variable using the `type()` function:

```javascript
x = 10
print(type(x))  # Output: <class 'int'>
```
## Changing a Variable’s Value

Variables are not permanent! You can change them anytime.

```javascript
color = "red"
print(color)  # Output: red

color = "blue"
print(color)  # Output: blue

```
First, `color` is "`red`". Then, we change it to "`blue`".

## Multiple Assignments

Python allows you to assign values to multiple variables in a single line:

```javascript
a, b, c = 1, 2, 3  # a = 1, b = 2, c = 3
```
Can also assign like this too

```javascript
x = y = z = 10  # x, y, and z all have the value 10
```

## Swapping Variables

Python makes it easy to swap values between variables without needing a temporary variable

```javascript
x, y = 10, 20
x, y = y, x  # Now x = 20 and y = 10
```

## Deleting Variables

You can delete a variable using the `del` keyword. Once deleted, the variable no longer exists in memory.

```javascript
x = 10
del x  # x is deleted
# print(x)  # This will raise a NameError 
```

## Combining Variables

You can combine variables in Python!

**String Concatenation**

```javascript
first_name = "Vayola"
last_name = "Pradeep"

full_name = first_name + " " + last_name  # Combine with a space
print(full_name)  # Output: Vayola Pradeep
```
**Using f-strings*

```javascript
name = "Vayola"
age = 12
print(f"My name is {name} and I am {age} years old.")  
# Output: My name is Vayola and I am 12 years old.
```

## Variables in Math Operations

Python allows you to perform calculations using variables.

```javascript
a = 10
b = 5

sum = a + b  # Addition
difference = a - b  # Subtraction
product = a * b  # Multiplication
quotient = a / b  # Division

print(sum, difference, product, quotient)

```

## Special Variable: None

None represents an empty or undefined value.

``` javascript
result = None
print(result)  # Output: None

result = 100  # Now it holds a value
print(result)  # Output: 100


```

## Constants in Python

A constant is a variable that should not change.
Python doesn’t have built-in constants, but we use UPPERCASE names by convention.

```javascript
PI = 3.14159
GRAVITY = 9.8
```

## Using Variables in a Simple Program

Let’s create a program that asks for user input and prints a message.

```javascript
name = input("Enter your name: ")
age = input("Enter your age: ")

print(f"Hello {name}! You are {age} years old.")
```
**What Happens?**

1. `input()` takes user input.
2. The input is stored in variables.
3. The program prints a message using `f-string`.

## Scope of Variables

The scope of a variable determines where it can be accessed in a program. There are two main types of variable scope in Python:

**Local Variables**: Defined inside a function and accessible only within that function.

**Global Variables**: Defined outside functions and accessible throughout the program.

```javascript
x = 10  # Global variable

def my_function():
    y = 20  # Local variable
    print(x)  # Access global variable
    print(y)

my_function()
print(x)  # Access global variable
# print(y)  # This will raise an error because y is local to my_function```
