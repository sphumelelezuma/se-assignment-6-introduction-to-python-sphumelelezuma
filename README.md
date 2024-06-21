[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15310137&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high-level, interpreted programming language known for its simplicity and readability. Key features include:

Easy-to-read syntax
Extensive standard library
Support for multiple programming paradigms (procedural, object-oriented, functional)
Use cases where Python excels include web development (Django, Flask), data analysis (Pandas, NumPy), artificial intelligence (TensorFlow, PyTorch), and scripting.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

Steps to Install Python:

Download the installer from python.org.
Run the installer and follow the instructions (ensure "Add Python to PATH" is checked).
Verify installation via terminal/command prompt: python --version.
Create a virtual environment: python -m venv myenv.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print("Hello, World!")
print: A built-in function to output text.
"Hello, World!": A string literal enclosed in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic Data Types:

int: Integer (e.g., 42)
float: Floating-point number (e.g., 3.14)
str: String (e.g., "hello")
bool: Boolean (e.g., True, False)

age = 30
pi = 3.14
name = "Alice"
is_student = True
print(age, pi, name, is_student)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   if age > 18:
    print("Adult")
else:
    print("Minor")

for i in range(5):
    print(i)



6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions encapsulate reusable code blocks, making programs modular and easier to maintain.

def add(a, b):
    return a + b

# Calling the function
result = add(2, 3)
print(result)



7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Lists vs. Dictionaries:

Lists: Ordered, mutable collections (e.g., [1, 2, 3]).
Dictionaries: Unordered, mutable collections of key-value pairs (e.g., {"name": "Alice", "age": 30}).

numbers = [1, 2, 3, 4, 5]
info = {"name": "Alice", "age": 30}

numbers.append(6)
info["city"] = "New York"

print(numbers)
print(info)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.


Exception handling manages runtime errors, ensuring the program can handle unexpected conditions gracefully.

try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Execution completed.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules are files containing Python code (functions, classes). Packages are directories of modules.

   import math

print(math.sqrt(16))

Modules and packages enable code reusability and organization.

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    Read File:
    with open('file.txt', 'r') as file:
    content = file.read()
    print(content)

   Write File:
   lines = ["First line", "Second line", "Third line"]
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + "\n")

File I/O allows interaction with external files for data storage and retrieval.

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


