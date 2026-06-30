# 🐍 Python for DevOps - Day 1

Welcome to **Day 1** of my **Python for DevOps** learning journey.

Today I learned the fundamentals of Python, including how Python works, variables, data types, operators, keywords, and user input.

---

# 📚 Topics Covered

- What is Python?
- How Python Works
- Python Character Set
- Variables
- Data Types
- Python Keywords
- Comments
- Operators
- User Input

---

# 🚀 What is Python?

Python is a powerful, easy-to-read, high-level programming language used for:

- 🌐 Web Development
- 🤖 Artificial Intelligence & Machine Learning
- 📊 Data Analysis
- ☁️ Cloud & DevOps Automation
- 🖥️ Desktop Applications
- 🔧 Scripting & Automation
- 📱 Software Development

Python is one of the most popular programming languages because of its simple syntax and huge collection of libraries.

---

# ⚙️ How Python Works Behind the Scenes

## Step 1: Write the Code

```python
print("Hello World")
```

Save the file as:

```text
Firstprogram.py
```

Run the program:

```bash
python Firstprogram.py
```

---

## What Happens Internally?

```
You Write Code

print("Hello World")

        │
        ▼

Save as Firstprogram.py

        │
        ▼

Run

python Firstprogram.py

        │
        ▼

Python Interpreter Starts

        │
        ▼

Reads Line 1

        │
        ▼

Finds print()

        │
        ▼

Reads "Hello World"

        │
        ▼

Calls print()

        │
        ▼

Screen Output

Hello World
```

---

## Understanding print()

```python
print("Hello World")
```

### print

- Built-in Python function
- Displays output on the screen

### Parentheses ()

Everything inside the parentheses is passed to the function.

```python
print(something)
```

The value inside the parentheses is called an **argument**.

### "Hello World"

Double quotes indicate that the value is a **String (text)**.

---

# 🔤 Python Character Set

Python supports the following character types.

## 1. Letters

```
A-Z
a-z
```

---

## 2. Digits

```
0-9
```

---

## 3. Special Symbols

```
+  -  *  /  %  =  ==  !=  <  >
( )  [ ]  { }  :  ;  ,  .  #  @
```

---

## 4. Whitespaces

- Blank Space
- Tab
- New Line
- Carriage Return
- Form Feed

---

## 5. ASCII & Unicode Characters

Python supports both ASCII and Unicode characters.

Example:

```python
name = "Rohit"
city = "मुंबई"
```

---

# 📦 Variables

A variable is a name given to a memory location where data is stored.

Example:

```python
name = "Rohit"
```

Here,

```
name → Variable
Rohit → Value
```

Another example:

```python
age = 23
```

```
age → Variable
23 → Value
```

---

# 📚 Data Types

Python supports many data types.

## 1. Integer (int)

Whole numbers without decimal points.

```python
age = 25
```

---

## 2. String (str)

Text enclosed in single or double quotes.

```python
name = "Rohit"
city = 'Mumbai'
```

---

## 3. Float

Numbers with decimal values.

```python
salary = 45000.50
```

---

## 4. Boolean (bool)

Boolean values have only two possible values.

```python
True
False
```

Example:

```python
is_logged_in = True
```

---

## 5. None

Represents no value or nothing.

```python
x = None
```

---

# 🔑 Python Keywords

Keywords are reserved words with predefined meanings.

You **cannot** use them as:

- Variable names
- Function names
- Class names

Examples:

```
False
True
if
elif
else
for
while
break
continue
pass
def
return
class
import
from
as
try
except
finally
raise
with
and
or
not
in
is
lambda
global
nonlocal
yield
assert
del
```

---

# 💬 Comments in Python

Comments are ignored by Python and are used to explain code.

### Single-line Comment

```python
# This is a comment
```

---

# ➕ Operators

Operators perform operations on values.

Example:

```python
a + b
```

```
a → Operand
+ → Operator
b → Operand
```

---

## 1. Arithmetic Operators

Used for mathematical calculations.

| Operator | Meaning |
|----------|----------|
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |
| % | Modulus (Remainder) |
| ** | Exponent (Power) |

Example:

```python
a = 10
b = 5

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a ** b)
```

---

## 2. Relational (Comparison) Operators

Compare two values and return **True** or **False**.

| Operator | Meaning |
|----------|----------|
| == | Equal |
| != | Not Equal |
| > | Greater Than |
| < | Less Than |
| >= | Greater Than or Equal |
| <= | Less Than or Equal |

Example:

```python
print(10 > 5)
```

Output

```
True
```

---

## 3. Assignment Operators

Used to assign values to variables.

Example:

```python
x = 10

x += 5

print(x)
```

Output

```
15
```

---

## 4. Logical Operators

Used to combine conditions.

| Operator | Meaning |
|----------|----------|
| and | Both conditions must be True |
| or | At least one condition must be True |
| not | Reverses True to False and vice versa |

Example:

```python
x = 10

print(x > 5 and x < 20)
```

Output

```
True
```

---

# ⌨️ input() Function

The `input()` function accepts data from the keyboard.

Example:

```python
name = input("Enter your name: ")

print(name)
```

---

## Important Note

The `input()` function always returns a **String**.

Example:

```python
age = input("Enter Age: ")

print(type(age))
```

Output

```
<class 'str'>
```

---

## Converting Input to Integer

Use `int()` when numerical calculations are required.

Example:

```python
age = int(input("Enter Age: "))

print(age + 5)
```

---

# 🎯 Key Takeaways

- Python is simple and beginner-friendly.
- Python code is executed by the Python Interpreter.
- Variables store data in memory.
- Python has multiple built-in data types.
- Keywords are reserved words.
- Comments improve code readability.
- Operators perform calculations and comparisons.
- `input()` accepts keyboard input and returns a string.
- Use `int()` to convert string input into an integer.

---

## 👨‍💻 Author

**Rohit Tambadkar**

Learning Python for DevOps | AWS | Linux | Docker | Kubernetes | Terraform | Jenkins
