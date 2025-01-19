![Image](https://github.com/user-attachments/assets/606a6ffa-4bd1-4b5f-ae8c-ffe464746d91)


Theory on Variables and Strings in Python
Variables in Python
A variable is a container that stores data values. In Python, variables are created when you assign a value to them using the = operator. Python is dynamically typed, meaning you don’t need to declare a variable's type explicitly.

Key Features
No need for explicit type declaration.
Variables are case-sensitive.
The type of a variable is determined by the value assigned.
Rules for Naming Variables
Must start with a letter (a-z, A-Z) or an underscore (_).
Can contain letters, digits (0-9), and underscores.
Cannot use reserved keywords like for, while, if, etc.
Should not start with a digit.
Examples
python
Copy
Edit
# Variable assignment
x = 10
y = 3.14
name = "Alice"

# Dynamic typing
x = "Now I'm a string!"
Types of Variables
Numeric: int, float, complex
Textual: str
Boolean: True, False
Sequence: list, tuple, range
Mapping: dict

Strings in Python
A string is a sequence of characters enclosed in single quotes (') or double quotes ("). Strings are immutable, meaning once created, they cannot be modified.

Creating Strings
python
Copy
Edit
# Using single or double quotes
string1 = 'Hello'
string2 = "World"

# Using triple quotes for multi-line strings
multi_line = """This is a
multi-line string."""
String Operations
Concatenation: Combine two or more strings.
python
Copy
Edit
greeting = "Hello, " + "world!"
Repetition: Repeat strings using *.
python
Copy
Edit
repeated = "ha" * 3  # Output: 'hahaha'
Indexing: Access specific characters using their position (0-based index).
python
Copy
Edit
s = "Python"
first_char = s[0]  # 'P'
last_char = s[-1]  # 'n'
Slicing: Extract substrings using [start:end:step].
python
Copy
Edit
substring = s[1:4]  # 'yth'
Length: Use len() to find the number of characters.
python
Copy
Edit
length = len("Python")  # 6
