# 🎤 Python Interview Questions

This document contains the most common **Python interview questions** for beginners and aspiring **DevOps Engineers**.

---

# 1. What is Python?

### Answer

Python is a **high-level, interpreted, object-oriented programming language**. It is easy to learn, easy to read, and widely used for:

- DevOps Automation
- Web Development
- Data Science
- Artificial Intelligence
- Machine Learning
- Cloud Automation
- Scripting

---

# 2. Why is Python used in DevOps?

### Answer

Python is widely used in DevOps because it helps automate repetitive tasks such as:

- AWS Automation 
- Server Management
- File Handling
- Log Parsing
- API Calls
- CI/CD Automation
- Infrastructure Automation

---

# 3. Is Python compiled or interpreted?

### Answer

Python is an **interpreted language**.

The Python Interpreter reads the code line by line and executes it.

Example:

```python
print("Hello World")
```

---

# 4. How do you run a Python program?

### Answer

```bash
python filename.py
```

or

```bash
python3 filename.py
```

---

# 5. What is a variable?

### Answer

A variable is a name given to a memory location used to store data.

Example:

```python
name = "Rohit"
age = 24
```

---

# 6. What is an identifier?

### Answer

An identifier is the name used to identify variables, functions, classes, modules, or other objects in Python.

Example:

```python
server_name = "web01"
```

### Rules for Identifiers

- Can contain letters, digits, and `_`
- Cannot start with a number
- Cannot contain spaces
- Cannot use special characters
- Cannot use Python keywords
- Python identifiers are **case-sensitive**

Example:

```python
name = "Rohit"
Name = "AWS"
```

These are two different variables.

---

# 7. What are Python keywords?

### Answer

Keywords are reserved words that have predefined meanings in Python.

Examples:

```
if
for
while
class
def
return
import
True
False
```

**Keywords cannot be used as variable names.**

---

# 8. What are the basic data types in Python?

### Answer

Python has five commonly used data types:

| Data Type | Description | Example |
|------------|-------------|---------|
| int | Whole numbers | `25` |
| float | Decimal numbers | `25.50` |
| str | Text | `"Python"` |
| bool | True or False | `True` |
| NoneType | No value | `None` |

---

# 9. Difference between Integer and Float

| Integer | Float |
|----------|-------|
| Whole number | Decimal number |
| `25` | `25.50` |

---

# 10. Difference between String and Integer

```python
age = "24"   # String

age = 24     # Integer
```

A **String** stores text, while an **Integer** stores numeric values.

---

# 11. What is Boolean?

### Answer

Boolean has only two values:

```python
True
False
```

Example:

```python
server_running = True
```

---

# 12. What is None?

### Answer

`None` represents the absence of a value.

Example:

```python
public_ip = None
```

---

# 13. What is an operator?

### Answer

An operator is a symbol that performs an operation on one or more operands.

Example:

```python
10 + 20
```

---

# 14. What are the main types of operators in Python?

### Answer

- Arithmetic Operators
- Comparison (Relational) Operators
- Assignment Operators
- Logical Operators

---

# 15. What is the difference between `=` and `==`?

| `=` | `==` |
|-----|------|
| Assignment Operator | Comparison Operator |
| Assigns a value | Compares two values |

Example:

```python
age = 20

age == 20
```

Output:

```python
True
```

---

# 16. What does the `%` operator do?

### Answer

The `%` operator returns the remainder after division.

Example:

```python
10 % 3
```

Output:

```python
1
```

---

# 17. What does the `**` operator do?

### Answer

The `**` operator is used to calculate powers (exponents).

Example:

```python
2 ** 3
```

Output:

```python
8
```

---

# 18. What is the `input()` function?

### Answer

The `input()` function accepts input from the keyboard.

Example:

```python
name = input("Enter your name: ")
```

---

# 19. What data type does `input()` return?

### Answer

The `input()` function always returns a **String (`str`)**, even if the user enters a number.

Example:

```python
age = input("Enter Age: ")
```

---

# 20. Why do we use `int(input())`?

### Answer

Since `input()` returns a string, we use `int()` to convert it into an integer so that mathematical operations can be performed.

Example:

```python
age = int(input("Enter Age: "))
```

---

# ⭐ Quick Interview Tips

- Explain concepts in simple language.
- Mention a small example whenever possible.
- Distinguish between similar concepts (e.g., `=` vs `==`, `int` vs `float`).
- If asked about DevOps, mention Python's role in automation, AWS (Boto3), scripting, and CI/CD.

---

## 👨‍💻 Author

**Rohit Tambadkar**

Learning **Python | DevOps | AWS | Linux | Docker | Kubernetes | Terraform | Jenkins**
