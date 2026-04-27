# Python Sheet 

# 1. Basic Python Syntax:                                                               

Print to Console   :  print("Hello, World!")

Variable Assignment :     x = 10

Input from User : name = input("Enter your name: ")

Check Data Type :  type(x)

Type Casting : int("10"), float("10.5"), str(100)

# 2. Data Structures:

List (Array) :  my_list = [1, 2, 3, 4, 5]

Access List Item  :  my_list[0]

List Slicing : my_list[1:4]

Add Item to List: my_list.append(6)

Remove Item from List : my_list.remove(3)

Tuple : my_tuple = (1, 2, 3, 4)

Set : my_set = {1, 2, 3, 4}

Dictionary (HashMap) : my_dict = {"key1": "value1", "key2": "value2"}

Access Dictionary Value : my_dict["key1"]

Add Key-Value Pair :  my_dict["key3"] = "value3"


# 3. Control Flow :

If Statement : if x > 10: print("x is greater than 10")

If-Else Statement : if x > 10: print("x is greater than 10") else: print("x is less than or equal to 10")

Elif Statement : if x > 10: print("x is greater") elif x == 10: print("x is 10") else: print("x is smaller")

For Loop : for i in range(5): print(i)

While Loop : while x < 10: x += 1

Break : for i in range(5): if i == 3: break

Continue : for i in range(5): if i == 3: continue

# 4. Functions:

Define Function : def my_function(): print("Hello from function!")

Function with Parameters : def greet(name): print(f"Hello, {name}!")

Return Value from Function : def add(a, b): return a + b

Lambda Function : add lambda a, b: a + b

# 5. String Manipulation:

Concatenate Strings : full_name = "Sonu" + " " + "Monu"

String Length : len("Hello")

Convert to Upper Case : "hello".upper()

Convert to Lower Case : "HELLO".lower()

Substring : "Hello, World!"

Find Substring : "Hello, World!".find("World")

Replace Substring : "Hello, World!".replace("World", "Python")

Split String : "Hello, World!".split(",")

# 6. File Handling:

Open a File : file = open("example.txt", "r")

Read File : content = file.read()

Read Line by Line : lines = file.readlines()

Write to a File : file = open("example.txt", "w"); file.write("Hello, World!")

Close a File : file.close()

# 7. List Comprehension:

Basic List Comprehension :  [x**2 for x in range(5)]

List Comprehension with Condition : [x for x in range(10) if x % 2 == 0]

# 8.Error Handling:

Try-Except Block : try: x = 10/0 except ZeroDivisionError: print("Cannot divide by zero")

Finally Block : try: x = 10/0 except ZeroDivisionError: print("Error!") finally: print("This runs always")

# 9. Working with Libraries:

Importing a Library : import math

Using a Library Function : math.sqrt(16)

Install a Library (using pip) : pip install pandas

Import Specific Function : from math import sqrt

# 10. NumPy for Numerical Operations:

Import NumPy : import numpy as np

Create NumPy Array  :  arr = np.array([1, 2, 3, 4, 5])

Array Reshaping : arr.reshape(5, 1)

Array Operations  : arr +10, arr * 2

Array Slicing : arr[1:4]

Array Statistics :  np.mean(arr), np.median(arr), np.std(arr)


# 11. Pandas for Data Handling:

Import Pandas : import pandas as pd

Create DataFrame : df = pd. DataFrame({"Name": ["Alice", "Bob"], "Age": [25, 30]})

Read CSV File : df = pd.read_csv("data.csv")

View Data : df.head()

Basic Statistics : df.describe()

Filter Data : df[df["Age"] > 25]

Group By : df.groupby("Age").mean()











