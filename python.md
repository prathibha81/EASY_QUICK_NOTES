Course Overview

A comprehensive Python programming course designed specifically for absolute beginners!
This course will take you from having zero programming experience to confidently building your own Python programs and understanding real-world applications.

What You'll Achieve
> Write Python code with confidence
> Build practical programs and applications
> Understand programming fundamentals that apply to any language
> Create real-world projects including calculators, games and automation tools
Gain the foundation needed for advanced topics like web development, data science and artificial intelligence

## Module 1: Getting Started with Python
>>> Lesson 1.1: What is Python & Why Learn It?
Python is a powerful, versatile programming language that's perfect for beginners. Created by Guido van Rossum in 1991, Python emphasizes code readability and simplicity making it an excellent choice for your first programming language.

Why Python is Perfect for Beginners:
- Simple and Readable Syntax: Python code reads almost like English
- Versatile Applications: Used in web development, data science, AI, automation and more
- Large Community Support: Millions of developers worldwide use Python
- Career Opportunities: High demand for Python developers across industries
- Free and Open Source: No cost to get started

Real-World Examples of Python Usage:
* Instagram: Backend services handling millions of users
* Netflix: Recommendation algorithms and data analysis
* Spotify: Music recommendation and data processing
* Dropbox: File synchronization and storage systems
* NASA: Space exploration and scientific computing

>>> Lesson 1.2: Installing Python & Setting Up Environment
Step-by-Step Installation Guide:

For Windows:

1.Visit python.org and download Python 3.12 or later
2.Run the installer and check "Add Python to PATH"
3.Verify installation by opening Command Prompt and typing  python --version

For Mac:

1.Download Python from python.org or use Homebrew: brew install python
2.Verify with Terminal: python3 --version

For Linux:

1.Most distributions include Python: python3 --version
2.If not installed: sudo apt-get install python3
3.Setting Up Your Development Environment:

> Option 1: IDLE (Beginner-Friendly)
- Comes pre-installed with Python
- Simple interface perfect for learning
- Built-in help system

> Option 2: Visual Studio Code (Recommended)
- Free, powerful code editor
- Excellent Python support with extensions
- Debugging capabilities

> Option 3: PyCharm Community Edition
- Full-featured Python IDE
- Great for larger projects
- Advanced debugging and testing tools

>>> Lesson 1.3: Your First Python Program
Let's write our first Python program! This traditional "Hello, World!" program is where every programmer begins

~  Your very first Python program

|   print("Hello, World!")
    print("Welcome to Python programming!")
    print("Today is a great day to learn coding!")   |

~ You can also do simple calculations

|   print(5 + 3)
    print("The answer is:", 10 * 4)  |

--What this code does:
The print() function displays text and numbers on the screen
Text (strings) must be enclosed in quotes
Python can perform mathematical calculations
Each line executes from top to bottom

*** Exercise: Modify the program to print your name and a personal message about why you want to learn Python.

>>> Lesson 1.4: Understanding Python Syntax
Python syntax refers to the rules that define how Python code is structured. Understanding these rules is crucial for writing correct Python programs.

Key Syntax Rules:
* Indentation Matters: Python uses indentation (spaces) to define code blocks
* Case Sensitive: Name and name are different variables
* Comments: Use # for single-line comments
* Line Continuation: Long lines can be split using backslash \

Example of Proper Python Syntax:
#This is a comment
name = "Python Learner"  # Variable assignment
if name:  # Conditional statement
    print("Hello,", name)  # Indented code block
    print("Welcome to programming!")
-----------------------------------------------------------------------------------------------------------------
## Module 2: Python Fundamentals

>>> Lesson 2.1: Variables & Data Types
Variables are containers that store data values. In Python, you don't need to declare the type of variable explicitly Python figures it out automatically

Creating Variables:
~ String variables
|   name = "John Doe"
    city = "New York"
    print("My name is", name, "and I live in", city)   |

~ Number variables  
|   age = 25
    height = 5.9
    print(f"I am {age} years old and {height} feet tall")  |

~ Boolean variables
|   is_student = True
    has_job = False
    print("Student status:", is_student) 
    print("Employment status:", has_job)  |

~ Python Data Types:
* String (str): Text data enclosed in quotes
* Integer (int): Whole numbers
* Float: Decimal numbers
* Boolean (bool): True or False values
* List: Ordered collection of items
* Dictionary: Key-value pairs

~ Variable Naming Rules:
* Must start with a letter or underscore
* Can contain letters, numbers, and underscores
* Cannot use Python keywords (like if, for, while)
* Case-sensitive: age and Age are different

*** Exercise: Create variables for your personal information (name, age, favorite color, etc.) and display them using print statements.

>>> Lesson 2.2: Numbers & Mathematical Operations
Python can perform various mathematical operations, making it useful for calculations and data analysis.

Arithmetic Operators:
~ Basic arithmetic
|   a = 10
    b = 3
    print("Addition:", a + b)        # 13
    print("Subtraction:", a - b)     # 7
    print("Multiplication:", a * b)  # 30
    print("Division:", a / b)        # 3.333...
    print("Integer Division:", a // b) # 3
    print("Modulus (remainder):", a % b) # 1
    print("Exponentiation:", a ** b)  # 1000   |

~ Order of Operations:
Python follows the mathematical order of operations (PEMDAS):
* Parentheses
* Exponents
* Multiplication and Division (left to right)
* Addition and Subtraction (left to right)

~ Order of operations examples

|   result1 = 2 + 3 * 4        # 14 (not 20)
    result2 = (2 + 3) * 4      # 20
    result3 = 2 ** 3 * 4       # 32 (8 * 4) |

*** Exercise: Create a simple calculator that takes two numbers and performs all arithmetic operations.

--> Lesson 2.3: Strings & Text Processing
Strings are sequences of characters used to represent text. Python provides powerful tools for working with strings

- String Basics:
~ Creating strings
|   first_name = "John"
    last_name = 'Doe'  # Single or double quotes both work
    full_name = first_name + " " + last_name      # String concatenation  |

~ String formatting

|   age = 25
    message = f"Hello, I'm {full_name} and I'm {age} years old"
    print(message)   |

- Common String Methods:
|   text = "Python Programming"
    print(text.upper())           # PYTHON PROGRAMMING
    print(text.lower())           # python programming
    print(text.title())             # Python Programming
    print(len(text))                # 18 (length of string)
    print(text.replace("Python", "Java"))     # Java Programming
    print(text.split())            # ['Python', 'Programming']   |

- String Indexing and Slicing:
|   word = "Python"
    print(word)                  # P (first character)
    print(word[-1])           # n (last character)
    print(word[1:4])           # yth (characters 1 to 3)
    print(word[:3])            # Pyt (first 3 characters)
    print(word[3:])             # hon (from index 3 to end)  |

*** Exercise: Create a program that takes a user's full name and displays it in different formats (uppercase, lowercase, initials only).

--> Lesson 2.4: Input & Output Operations
Interaction with users is essential for creating useful programs. Python's input() function allows you to get data from users.

Getting User Input:
~ Basic input
|   name = input("Enter your name: ")
    print("Hello,", name)   |

~ Converting input to numbers
|   age_str = input("Enter your age: ")
    age = int(age_str)  # Convert string to integer 
    print(f"You are {age} years old")  |

~ Direct conversion
|   height = float(input("Enter your height in feet: "))
    print(f"Your height is {height} feet") |

- Advanced Output Formatting:
| name = "Alice"
    age = 30
    salary = 50000.75  |

~ Using f-strings (recommended)
print(f"Name: {name}, Age: {age}, Salary: ${salary:.2f}")

~ Using format() method
print("Name: {}, Age: {}, Salary: ${:.2f}".format(name, age, salary))

~ Using % formatting (older method)
print("Name: %s, Age: %d, Salary: $%.2f" % (name, age, salary))

*** Exercise: Create a program that collects user information (name, age, city) and displays a personalized welcome message.

>>> Lesson 2.5: Comments & Documentation
Comments are essential for making your code readable and maintainable. They explain what your code does without affecting its execution.

~ Types of Comments:
#This is a single-line comment
print("Hello, World!")  # Comment at end of line

"""
This is a multi-line comment
(also called a docstring when used
to document functions and classes)
"""

'''
You can also use triple single quotes
for multi-line comments
'''

| def calculate_area(length, width):
      """
      Calculate the area of a rectangle.
      Args:
          length (float): The length of the rectangle
          width (float): The width of the rectangle
      Returns:
          float: The area of the rectangle
      """
      return length * width  |

- Best Practices for Comments:
* Explain Why, Not What: Good comments explain the reasoning behind code
* Keep Comments Updated: Update comments when you change code
* Use Meaningful Variable Names: Good names reduce the need for comments
* Document Functions: Use docstrings to explain what functions do
-----------------------------------------------------------------------------------------------------------------
## Module 3: Control Flow & Decision Making
>>> Lesson 3.1: Conditional Statements (if/elif/else)
Conditional statements allow your programs to make decisions based on different conditions.

- Basic if Statement:
|  age = int(input("Enter your age: "))
   if age >= 18:
       print("You are an adult!")
   if age >= 65:
       print("You qualify for senior discounts.")
   elif age >= 21:
       print("You can vote and drink legally.")
   else:
       print("You can vote!")

   else:
       print("You are a minor.")
       years_left = 18 - age
       print(f"You will be an adult in {years_left} years.") |

- Multiple Conditions:

|   temperature = float(input("Enter temperature in Fahrenheit: "))
    if temperature > 90:
        print("It's very hot outside!")
    elif temperature > 70:
        print("It's warm and pleasant.")
    elif temperature > 50:
        print("It's cool outside.")
    elif temperature > 32:
        print("It's cold outside.")
    else:
        print("It's freezing!")   |

>>> Lesson 3.2: Comparison & Logical Operators
- Comparison Operators:
|   a = 10
    b = 5
    print(a == b)   # False (equal to)
    print(a != b)   # True (not equal to)
    print(a > b)    # True (greater than)
    print(a < b)    # False (less than)
    print(a >= b)   # True (greater than or equal)
    print(a <= b)   # False (less than or equal)   |

- Logical Operators:
|  age = 25
   has_license = True
   has_car = False  |

~ AND operator
|  if age >= 18 and has_license:
        print("You can drive!")  |

~ OR operator
|  if has_car or has_license:
        print("You have some form of transportation!")  |

~ NOT operator
|   if not has_car:
        print("You need to get a car or use public transport.")  |

>>> Lesson 3.3: Loops: for and while
Loops allow you to repeat code multiple times, making your programs more efficient.

For Loops:
~ Loop through a range of numbers

|    for i in range(5):
        print(f"Count: {i}")   |

~ Loop through a list

|    fruits = ["apple", "banana", "orange"]
     for fruit in fruits:
          print(f"I like {fruit}")  |

~ Loop through a string

|   word = "Python"
    for letter in word:
          print(letter)    |

While Loops:
~ Count from 1 to 5
|   count = 1
    while count <= 5:
         print(f"Count: {count}")   
    count += 1                |

~ User input validation

|  password = ""

   while password != "secret":

        password = input("Enter password: ")

        if password != "secret":
            print("Incorrect password, try again!")
   print("Access granted!")                         |

>>> Lesson 3.4: Loop Control: break and continue
Break Statement:
~ Exit loop when specific condition is met

|   for i in range(10):

        if i == 5:
            break  # Exit the loop
            print(i)                |
~ Prints: 0, 1, 2, 3, 4

Continue Statement:
~ Skip current iteration and continue with next

for i in range(10):

    if i % 2 == 0:  # If number is even

        continue  # Skip to next iteration

    print(i)

~ Prints: 1, 3, 5, 7, 9 (odd numbers only)
-----------------------------------------------------------------------------------------------------------------
## Module 4: Data Structures
Lesson 4.1: Lists: Creation & Manipulation
Lists are ordered collections that can store multiple items of different data types.

Creating and Using Lists:
~ Creating lists

|   fruits = ["apple", "banana", "orange", "grape"]
    numbers = [1, 2, 3, 4, 5]
    mixed_list = ["Python", 3.14, True, 42]
    print("Original list:", fruits)                 |

~ Adding items

|   fruits.append("strawberry")  # Add to end
    fruits.insert(1, "mango")    # Insert at specific position     |
    print("After adding items:", fruits)

~ Removing items

|    fruits.remove("banana")      # Remove by value
     last_fruit = fruits.pop()    # Remove and return last item
     print("After removing items:", fruits)
     print("Removed fruit:", last_fruit)               |

~ Accessing items

|    print("First fruit:", fruits[0])
     print("Last fruit:", fruits[-1])     
     print("Middle fruits:", fruits[1:3])               |

     List Methods and Operations:
     numbers = [3, 1, 4, 1, 5, 9, 2, 6]
     print("Original:", numbers)
     print("Length:", len(numbers))
     print("Maximum:", max(numbers))
     print("Minimum:", min(numbers))
     print("Sum:", sum(numbers))                    |

~ Sorting

|    numbers.sort()
     print("Sorted:", numbers)   |

~ Counting and finding

|    print("Count of 1:", numbers.count(1))
     print("Index of 4:", numbers.index(4))    |

>>> Lesson 4.2: Dictionaries: Key-Value Pairs
Dictionaries store data in key-value pairs, allowing you to organize and access information efficiently.

~ Creating dictionaries

|    student = {
         "name": "Alice Johnson",
         "age": 20,
         "major": "Computer Science",
         "gpa": 3.8,
         "courses": ["Python", "Math", "Physics"]
          }                           |

~ Accessing values

|      print("Student name:", student["name"])
       print("Student GPA:", student.get("gpa"))  |

~ Adding and modifying

|      student["email"] = "alice@university.edu"
       student["age"] = 21                        |

~ Looping through dictionaries

|       for key, value in student.items():
            print(f"{key}: {value}")              |

~ Dictionary methods

|       print("Keys:", list(student.keys()))
        print("Values:", list(student.values()))    |

>>> Lesson 4.3: Tuples & Sets
Tuples (Immutable sequences):
~ Creating tuples

|        coordinates = (10, 20)
         person = ("John", "Doe", 30, "Engineer")    |

~ Accessing tuple elements

|         print("X coordinate:", coordinates[0])
          print("Y coordinate:", coordinates[1])       |

~ Tuple unpacking

|      x, y = coordinates
       first_name, last_name, age, job = person        
       print(f"{first_name} {last_name} is {age} years old")   |

Sets (Unique collections):
~ Creating sets

|      fruits = {"apple", "banana", "orange", "apple"}  # Duplicates removed
       print("Fruits set:", fruits)                                |

~ Set operations

|      set1 = {1, 2, 3, 4, 5}
       set2 = {4, 5, 6, 7, 8}
       print("Union:", set1  |  set2)             # {1, 2, 3, 4, 5, 6, 7, 8}
       print("Intersection:", set1 & set2)        # {4, 5}
       print("Difference:", set1 - set2)            # {1, 2, 3}     |
--------------------------------------------------------------------------------
## Module 5: Functions & Modular Programming
>>> Lesson 5.1: Defining Functions
Functions are reusable blocks of code that perform specific tasks. They help organize your code and avoid repetition.

| def greet_user(name, age):

    """Function to greet a user with their name and age"""
       greeting = f"Hello {name}! You are {age} years old."
       return greeting
  def calculate_area(length, width):
    """Calculate area of a rectangle"""
       area = length * width
       return area                 |

~ Using the functions

|   user_name = input("Enter your name: ")
    user_age = int(input("Enter your age: "))
    message = greet_user(user_name, user_age)
    print(message)                        |

~ Calculate area

|   l = float(input("Enter length: "))
    w = float(input("Enter width: "))     

    result = calculate_area(l, w)        
    print(f"The area is: {result}")         |

>>> Lesson 5.2: Parameters & Arguments
Different Types of Parameters:
| def create_profile(name, age, city="Unknown", country="USA"):

     """Create user profile with default values"""

     profile = {

         "name": name,
         "age": age,
         "city": city,
         "country": country

    }

     return profile                       |

~ Different ways to call the function

|   profile1 = create_profile("Alice", 25)
    profile2 = create_profile("Bob", 30, "New York")
    profile3 = create_profile("Charlie", 35, city="Boston", country="USA")    |

~ Variable-length arguments

|   def calculate_average(*numbers):
       """Calculate average of any number of arguments"""
       if numbers:
           return sum(numbers) / len(numbers)
       return 0                                                   

    avg1 = calculate_average(10, 20, 30)
    avg2 = calculate_average(5, 15, 25, 35, 45)                   |
------------------------------------------------------------------------------------------------------------------
## Module 6: File Handling & Error Management
>>> Lesson 6.1: Reading & Writing Files
File handling allows your programs to store and retrieve data permanently.

~ Writing to a file

|  student_data = ["Alice", "Bob", "Charlie", "Diana"]     |

~ Write student names to file

|    with open("students.txt", "w") as file:
        file.write("Student List:\n")
        for student in student_data:
            file.write(f"- {student}\n")                   

    print("Data written to students.txt")                   |    

~ Reading from a file

try:

    with open("students.txt", "r") as file:
        content = file.read()
        print("File contents:")
        print(content)

except FileNotFoundError:

    print("File not found! Please create the file first.")

~ Working with CSV files

import csv

~ Writing CSV

students = [
    ["Name", "Age", "Grade"],
    ["Alice", 18, "A"],
    ["Bob", 19, "B+"],
    ["Charlie", 18, "A-"]

]

with open("grades.csv", "w", newline="") as file:

    writer = csv.writer(file)
    writer.writerows(students)

~  Reading CSV

with open("grades.csv", "r") as file:

    reader = csv.reader(file)
    for row in reader:

        print(", ".join(row))

>>> Lesson 6.2: Exception Handling
Exception handling allows your programs to deal with errors gracefully.

~ Basic try-except

try:

    number = int(input("Enter a number: "))
    result = 100 / number
    print(f"Result: {result}")

except ValueError:
    print("Please enter a valid number!")

except ZeroDivisionError:
    print("Cannot divide by zero!")

~ Multiple exceptions and finally

def safe_file_read(filename):

    try:

        with open(filename, "r") as file:
            content = file.read()
            return content

    except FileNotFoundError:
        print(f"File '{filename}' not found.")
        return None

    except PermissionError:
        print(f"Permission denied to read '{filename}'.")
        return None

    finally:
        print("File operation completed.")

~ Using the function

content = safe_file_read("example.txt")

if content:
    print("File content:", content)

## Module 7: Object-Oriented Programming
>>> Lesson 7.1: Introduction to Classes
Classes are blueprints for creating objects. They allow you to group related data and functions together.

class Student:

    """A class to represent a student"""

    

    def init(self, name, age, student_id):

        """Initialize a new student"""

        self.name = name
        self.age = age
        self.student_id = student_id
        self.grades = []
        self.enrolled = True

    

    def add_grade(self, subject, grade):
        """Add a grade for a subject"""
        self.grades.append({"subject": subject, "grade": grade})

    

    def get_average_grade(self):

        """Calculate average grade"""

        if not self.grades:
            return 0

        total = sum(item["grade"] for item in self.grades)
        return total / len(self.grades)

    

    def display_info(self):

        """Display student information"""

        print(f"Name: {self.name}")
        print(f"Age: {self.age}")
        print(f"Student ID: {self.student_id}")
        print(f"Average Grade: {self.get_average_grade():.2f}")
        print(f"Enrolled: {self.enrolled}")

~ Creating and using objects

student1 = Student("Alice Johnson", 20, "S001")
student1.add_grade("Math", 85)
student1.add_grade("Python", 92)
student1.add_grade("Physics", 78)
student1.display_info()

## Module 8: Libraries & External Modules
>>> Lesson 8.1: Importing Modules
Python's power comes from its extensive library ecosystem. Learn how to use existing modules and create your own.

~ Standard library imports

import math
import random
import datetime

~ Using math module

radius = 5
area = math.pi * radius * 2
print(f"Area of circle: {area:.2f}")

~ Using random module

print("Random number:", random.randint(1, 100))
print("Random choice:", random.choice(["apple", "banana", "orange"]))

~  Using datetime module

now = datetime.datetime.now()
print(f"Current date and time: {now}")

~ Specific imports

from math import sqrt, pow

print("Square root of 16:", sqrt(16))
print("2 to the power of 8:", pow(2, 8))

Lesson 8.2: Popular Libraries Overview
- Working with requests (for web APIs) 
~ First install: pip install requests 
try: 
          import requests 
          response = requests.get("https://api.github.com/users/octocat") 
          if response.status_code == 200: 
         user_data = response.json() 
         print(f"GitHub user: {user_data['name']}") 
except ImportError: 
         print("Requests library not installed. Install with: pip install requests") 

- Working with pandas (for data analysis) 

~ First install: pip install pandas 
try: 
import pandas as pd 
        data = { 
                     "Name": ["Alice", "Bob", "Charlie"], 
                    "Age": [25, 30, 35], 
                    "City": ["New York", "London", "Tokyo"] 
  } 
       df = pd.DataFrame(data) 
       print(df) 
  except ImportError: 
       print("Pandas library not installed. Install with: pip install pandas")
------------------------------------------------------------------------------------------------------------------
## Module 9: Hands-On Projects
Simple Execrise based on the topics read 
building these can give confidence on the basics of python
*** Project 1: Simple Calculator (Using Conditional Staments or Functions)
*** Project 2: Number Guessing Game (Using Operations,Random modules)
*** Project 3: To-Do List Manager (Using Functions,Match,Conditional Staments)
------------------------------------------------------------------------------------------------------------------
## Practice Platforms:
LeetCode: Algorithm problems
HackerRank: Programming challenges
Codewars: Coding kata
GitHub: Open source contributions

