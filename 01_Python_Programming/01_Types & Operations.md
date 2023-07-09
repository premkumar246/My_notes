Let's start Leanring Python
# 2. Object Types and Operations in Python

- In Python Data takes the form of Objects either the built-in objects or the objects we create using classes in Python
- Objects are just pieces of memory with values and associated with a set of operations.

## The Python Conceptual Hierarchy
  1. **Programs** are composed of modules.
  2. **Modules** contain statements.
  3. **Statements** contain expressions.
  4. **Expressions** create and process **Objects**.

  Programs >> Modules >> Statements >> Expressions >> Objects

## Python's Core Data Types

**Object type**-------------------**Example literals/creation**<br>
Numbers---------------------------1234, 3.1415, 3+4j, 0b111, Decimal(), Fraction()<br>
Strings---------------------------'spam', "Bob's", b'a\x01c', u'sp\xc4m'<br>
Lists-----------------------------[1, [2, 'three'], 4.5], list(range(10))<br>
Dictionaries----------------------{'food': 'spam', 'taste': 'yum'}, dict(hours=10)<br>
Tuples----------------------------(1, 'spam', 4, 'U'), tuple('spam'), namedtuple<br>
Files-----------------------------open('eggs.txt'), open(r'C:\ham.bin', 'wb')<br>
Sets------------------------------set('abc'), {'a', 'b', 'c'}<br>
Other core types------------------Booleans, types, None<br>
Program unit types----------------Functions, modules, classes (Part IV, Part V, Part VI)<br>
Implementation-related types------Compiled code, stack tracebacks (Part IV, Part VII)<br>

- In python everything is an object, which means stored in a memory cell.
- We create objects using the syntax and the interpreter fix the set of operations that we could perform in the objects.
- Which means we can perform only string operations on strings Numerical operations on numbers.
- Python is a dynamically typed language - where it decides the data type on the go for itslef
- Python is a Strongly typed language - where once you decide your data type you cannot perform other operations which not allowed on it.

## Numeric Types 
- In Python, numbers are not really a single object type, but a category of similar types.
- Python supports the usual numeric types (integers and floating points), as well as **literals** for creating numbers and **expressions** for processing them.
- The complete list of python Numerical objects consists the following
  - **Integer** & **Floating point** objects
  - **Complex Numbers**
  - **Decimal**: Fixed Precision Objects
  - **Fraction**: Rational Number Objects
  - **Sets**: Collections with set of Numeric Operations
  - **Booleans**: True or False
  - Built in **Functions** & **Modules**: Round, Math, Random etc.
  - **Expressions**; unlimited integer precision; bitwise operations; hex, octal, and binary formats.
  - Third-party extensions: **vectors**, **libraries**, **visualization**, **plotting**, etc.
