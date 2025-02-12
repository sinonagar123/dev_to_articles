## What is the `input() `Function?

The `input()` function in Python is used to take user input from the keyboard. It allows your program to interact with the user by prompting them to enter data, which can then be processed or stored in variables. By default, the `input() `function returns the user's input as a string, regardless of what the user enters.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/quefhed8lb7sw7hfkh2g.jpeg)


## How Does `input()` Work?

1. It waits for the user to type something.
2. It stores the typed text as a "string" (text).
3. You can save the input in a variable.
4. You can print or use it later in the program.

## Basic Syntax

The basic syntax of the `input()` function is:

```javascript
input([prompt])
```
**`prompt` (optional)**: A string that is displayed to the user as a message or instruction. 

**Return value**: The function returns the user's input as a **string**.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/alky8bwued2joyx9x5g0.jpeg)

**Example:**

```javascript
name = input("What is your name? ")
print("Hello, " + name + "!")
```
**Output:**

```javascript
What is your name: Vayola
Hello, Vayola
```

**What happens here?**

The program asks, "**What is your name?**"
The user types their name (e.g., "**Vayola**") and presses Enter.
The program then prints "**Hello, Vayola!**"


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dfn68kfogttcgfk5pcqv.jpeg)



## Converting Input to Other Data Types

The `input()` function always takes input as a string (text).Even if the user enters a number, it will be treated as a string.

``` javascript
age = input("Enter your age: ")
print("Type of age:", type(age))  # Output: <class 'str'>

```

If you need to work with the input as a different data type (e.g., integer, float, etc.), you must convert the input to the desired type using appropriate type conversion functions.

## Here’s the syntax and examples for converting input to other data types:

**1. Convert Input to Integer**

Use the `int() `function to convert the input to an integer.

**syntax:**

```javascript
variable = int(input("Prompt message"))
```
**Example:**

```javascript
age = int(input("Enter your age: "))
print("Age in 10 years:", age + 10)
```
**output:**

```javascript
Enter your age: 25
Age in 10 years: 35
```

**2. Convert Input to Float**

Use the `float()` function to convert the input to a floating-point number.

**syntax:**

```javascript
variable = float(input("Prompt message"))
```
**Example:**

```javascript
height = float(input("Enter your height in meters: "))
print("Your height is:", height)

```
**output:**

```javascript
Enter your height in meters: 1.75
Your height is: 1.75
```
**3. Convert Input to Boolean**

Use the `bool()` function to convert the input to a boolean value. Note that non-empty strings are converted to `True`, and empty strings are converted to `False`.

**syntax:**

```javascript
variable = bool(input("Prompt message"))
```
**Example:**

```javascript
is_active = bool(input("Are you active? (Press Enter for False): "))
print("Active status:", is_active)
```
**output:**

```javascript
Are you active? (Press Enter for False): Yes
Active status: True

```

**4. Convert Input to List**

If the user enters multiple values separated by spaces or commas, you can convert the input to a list using the `split()` method.

**syntax:**

```javascript
variable = input("Prompt message").split()
```
**Example:**

```javascript
numbers = input("Enter numbers separated by spaces: ").split()
numbers = [int(num) for num in numbers]  # Convert strings to integers
print("Numbers:", numbers)
```
**output:**

```javascript
Enter numbers separated by spaces: 10 20 30
Numbers: [10, 20, 30]

```
**5. Convert Input to Tuple**

If the user enters multiple values separated by spaces or commas, you can convert the input to a list using the `split()` method.

**syntax:**

```javascript
variable = tuple(map(int, input("Prompt message").split()))
```
**Example:**

```javascript
values = tuple(map(int, input("Enter numbers separated by spaces: ").split()))
print("Values:", values)
```
**output:**

```javascript
Enter numbers separated by spaces: 1 2 3
Values: (1, 2, 3)

```
**6. Convert Input to Dictionary**

If the user enters key-value pairs, you can convert the input to a dictionary.


**syntax:**

```javascript
variable = dict(item.split(":") for item in input("Prompt message").split(","))
```
**Example:**

```javascript
data = dict(item.split(":") for item in input("Enter key:value pairs separated by commas: ").split(","))
print("Data:", data)
```
**output:**

```javascript
Enter key:value pairs separated by commas: name:Vayola,age:25
Data: {'name': 'Vayola', 'age': '25'}

```
**7. Convert Input to Set**

You can convert the input to a set by first splitting the input and then converting it.


**syntax:**

```javascript
variable = set(map(int, input("Prompt message").split()))
```
**Example:**

```javascript
unique_numbers = set(map(int, input("Enter numbers separated by spaces: ").split()))
print("Unique numbers:", unique_numbers)
```
**output:**

```javascript
Enter numbers separated by spaces: 1 2 2 3 3
Unique numbers: {1, 2, 3}

```
**8. Error Handling for Type Conversion**

When converting input to other data types, always handle potential errors (e.g., invalid input) using a `try-except` block.

**Example:**

```javascript
try:
    age = int(input("Enter your age: "))
    print("Age in 10 years:", age + 10)
except ValueError:
    print("Invalid input! Please enter a valid number.")
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4qoo73bpr028o80di5ec.jpeg)

## Here’s a program that demonstrates converting input to different data types:

```javascript
# Program to demonstrate type conversion of user input
def main():
    # Convert to integer
    age = int(input("Enter your age: "))
    print("Age in 10 years:", age + 10)

    # Convert to float
    height = float(input("Enter your height in meters: "))
    print("Your height is:", height)

    # Convert to list
    numbers = input("Enter numbers separated by spaces: ").split()
    numbers = [int(num) for num in numbers]
    print("Numbers:", numbers)

    # Convert to dictionary
    data = dict(item.split(":") for item in input("Enter key:value pairs separated by commas: ").split(","))
    print("Data:", data)

# Run the program
main()```
