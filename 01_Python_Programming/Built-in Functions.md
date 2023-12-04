# Python Built-in Functions 
Here we will learn about the built-in functions that are available in python. 
## Functions
A function is a set of lines of code written for executing a particular task and saved with a name which can be called any number of times. 
 
  - Functions are two types based on the availability.
    - ### Built-in Functions:
      - Built-in functions are functions which written by the authors of the language and comes default with the language.
      - We can use these functions by just calling them.
      - Builtins has global scope across the programs. One dont need to import them.
   
    - ### User-defined Functions:
      - These are the functions which can be written by user and perform one's own tasks.
      - Just like built-in functions these can be called again and again to use them.
      - But unlike builtins one has to import the modules in to current module to use the functions.
      - If the functions are defined in the current module then they can be called with out using them.
  - Here we are going to learn about all the builtin functions comes along with python interpreter.

## Builtin Functions
- There are 71 Builtin functions available in python 3.12.0 version.
- These 71 builtin functions can be segregated loosely in to few groups. They are

    1. Types Constructors ------- 14
    2. Input Output ------------- 02
    3. Integer Converters ------- 03
    4. Math operations ---------- 07
    5. Higher Order Functions --- 02
    6. Decorator Functions ------ 03
    7. Attribute Functions ------ 04
    8. Verification Functions --- 05
    9. File Opening Functions ----01
    10. Namespace Access -------- 02
    11. Sequence Operations  ---- 06
    12. Iterable Functions ------ 04
    13. String Functions -------- 03
    14. Code compiling ---------- 01
    15. Miscellaneous Functions - 12

- We will learn about each function indetailed
  - Utility
  - Syntax
  - Input params
  - Output type

## Type Constructors - 14
- Python has builtin data types which are used to create, store and access data of such types.
- We use these type constructors to create the instances of the builtin types and create variables to store data.

### 1. bool()
### 2. int()
### 3. float()
### 4. complex()
### 5. str()
### 6. list()
### 7. tuple()
### 8. range()
### 9. set()
### 10. frozenset()
### 11. dict()
### 12. bytes()
### 13. bytesarray()
### 14. memoryview()

## Input & Output - 02
- A program takes input, process the input values and gives out the output.
- We can write input and output statements using the input and output builtins.

### input()
### print()

## Integer Converters - 03
- Python supports Binary, Octal, Decimal, Hexadecimal numer systems.
- It provides us builtins to conver an integer in Decimal system to other systems.

### bin()
### oct()
### hex()

## Math Functions -07
- Numbers has huge significance in programming and applications.
- There are few math related builtin functions in python

### sum()
### abs()
### round()
### min()
### max()
### divmod()
### pow()

## Higher Order Functions - 02
- A higher order function is a function which takes other functions as inputs.
- Python has few builtin higher order functions

### map()
### filter()

## Decorator Functions - 03
- A decorator is a function which used to extend or modify another function.
- Python provides decorators

### @classmethod
### @staticmethod
### @property

## Attribute Functions - 04
- When we create classes we create variables inside them which are called attributes of that class.
- Python provides few builtins to modify the attributes

### getattr()
### setattr()
### hasattr()
### delattr()
### vars()

## Verification Functions - 05
- Sometimes in code we get to verify things. The builtin verification functions come handy in doing so.

### all()
### any()
### callable()
### isinstance()
### issubclass()

## File Opening Functions - 01
- Files are the way to organize data.
- Python has one builtin function to open files in various modes.

### open()

## Namespace Access Functions - 02
- Functions has two types of variables based on the scope of the variables.
- First is Local variables & Second is global variables
- Python has builtin variables to get local & global variables list.

### local()
### global()

## Sequence Operations Functions - 06
- Data sometimes has sequences in it.
- We can perform multiple operations on these sequences using builtin functions.

### len()
### sorted()
### reversed()
### enumerate()
### zip()
### slice()

## Iterable Functions - 04

### iter()
### aiter()
### next()
### anext()

## String Functions - 03

### ascii()
### repr()
### format()

## Code compiling - 01 

### compile()

## Miscellaneous Functions - 12

### id()
### type()
### help()
### dir()
### hash()
### ord()
### chr()
### eval()
### exec()
### super()
### object()
### __import__()


