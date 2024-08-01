[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15492035&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   **ANSWER**

   1. Python Basics
What is Python?
Python is a high-level, interpreted programming language known for its readability and simplicity. It emphasizes code readability and has a straightforward syntax that allows developers to express concepts in fewer lines of code.

Key Features:

Easy to Learn and Use: Python’s syntax is clear and intuitive, making it accessible for beginners.
Versatile: It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
Extensive Libraries: Python has a rich standard library and a large ecosystem of third-party packages.
Interpreted Language: Python code is executed line-by-line, which makes debugging easier.
Cross-Platform: Python runs on various operating systems including Windows, macOS, and Linux.
Use Cases:

Web Development: Frameworks like Django and Flask are used to build web applications.
Data Analysis and Visualization: Libraries such as Pandas, NumPy, and Matplotlib are used for data manipulation and visualization.
Automation and Scripting: Python is commonly used for writing scripts to automate repetitive tasks.
Machine Learning: Libraries like TensorFlow and scikit-learn are used for building machine learning models.
Software Development: Python is used to develop desktop and server-side applications.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   **ANSWER 2** 

   2. Installing Python
Steps to Install Python (Windows):

Download the Installer: Go to the Python website and download the latest version of Python for Windows.
Run the Installer: Double-click the downloaded installer. Ensure to check the box that says “Add Python to PATH” before clicking “Install Now.”

Verify Installation:
Open Command Prompt and type python --version to check the Python version.
Type **pip --version** to verify that pip (Python’s package installer) is also installed.

Set Up a Virtual Environment:

-Create a directory for your project and navigate to it in Command Prompt.
-Run python -m venv myenv to create a virtual environment named myenv.
-Activate the virtual environment by running myenv\Scripts\activate.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   
   **ANSWER 3**
   
   print('Hello World !') 



4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   **ANSWER 4**

   Basic Data Types:

int: Integer values (e.g., 5, -3).
float: Floating-point numbers (e.g., 3.14, -0.001).
str: Strings (e.g., "hello", "world").
bool: Boolean values (True or False).

# Integer
age = 25

# Float
height = 5.9

# String
name = "Alice"

# Boolean
is_student = True

print(age)
print(height)
print(name)
print(is_student)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
 
 **ANSWER**

Conditional statements in Python are used to perform different actions based on different conditions. The most commonly used conditional statement is the if-else statement.

1. if Statement:
The if statement evaluates a condition (an expression that returns either True or False). If the condition is True, the code block inside the if statement is executed.
2. else Statement:

The else statement follows the if statement and is executed if the condition in the if statement evaluates to False.

3. elif Statement:

The elif (short for "else if") statement allows checking multiple conditions. It is executed if the previous if and elif conditions are False.

**EXAMPLES**

1. If-else  statement 

temperature = 25

if temperature > 30:
    print("It's a hot day.")
elif temperature > 20:
    print("It's a warm day.")
else:
    print("It's a cool day.")

2. if statement 

age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")


3. elif statement 

age = 15

if age < 0:
    print("Invalid age.")
elif age < 2:
    print("Infant")
elif age < 13:
    print("Child")
elif age < 20:
    print("Teenager")
elif age < 65:
    print("Adult")
else:
    print("Senior")


Explanation:

- if age < 0: - This condition checks if the age is less than 0, which is an invalid value. If it is, it prints "Invalid age."

* elif age < 2: - If the age is not less than 0 but less than 2, it prints "Infant."

* elif age < 13: - If the age is not less than 2 but less than 13, it prints "Child."

* elif age < 20: - If the age is not less than 13 but less than 20, it prints "Teenager."

* elif age < 65: - If the age is not less than 20 but less than 65, it prints "Adult."

- else: - If none of the above conditions are met (meaning the age is 65 or older), it prints "Senior."



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

**ANSWER 6**
Functions are reusable blocks of code that perform a specific task. They help in organizing code, avoiding repetition, and improving readability.

**EXAMPLE*
def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(5, 3)
print(result)  # Output: 8




7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Lists:

Ordered, mutable collections of items.
Example: numbers = [1, 2, 3, 4, 5]
Dictionaries:

Unordered, mutable collections of key-value pairs.
Example: person = {"name": "John", "age": 30}

# EXAMPLE 7.

# List
numbers = [1, 2, 3, 4, 5]
print(numbers[0])  # Output: 1

# Dictionary
person = {"name": "John", "age": 30}
print(person["name"])  # Output: John


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Exception handling is used to manage errors or exceptions that occur during the execution of a program. It allows the program to continue running or handle errors gracefully.
   
   # EXAMPLE 8.
   try:
    x = 1 / 0
  except ZeroDivisionError:
    print("Cannot divide by zero!")
   finally:
    print("Execution completed.")


 

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules:

Files containing Python code (functions, classes, variables) that can be imported into other scripts.

Packages:
Collections of modules organized in directories.

# EXAMPLE 9.

- import math

print(math.sqrt(16))  # Output: 4.0


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    # READING FROM A FILE 

    with open('example.txt', 'r') as file:
    content = file.read()
    print(content)

   # WRITING TO A FILE 
     
with open('example.txt', 'w') as file:
    lines = ["Hello", "World", "Python"]
    file.write("\n".join(lines))



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


