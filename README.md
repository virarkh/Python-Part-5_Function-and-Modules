### :heavy_check_mark:Function, Modules and Library

## Outline
:one: [Function](#function) <br>
:two: [Modules](#modules) <br>
:three: [Library](#library)


## Function
- In Python, a function is a group of related statements that performs a specific task.
- Functions help break our program into smaller and modular chunks. As our program grows larger and larger, functions make it more organized and manageable.
- Furthermore, it avoids repetition and makes the code reusable.
#### Syntax of Function
```
def function_name(parameters):
    statement(s)
```
Above shown is a function definition that consists of the following components.
- Keyword def that marks the start of the function header.
- A function name to uniquely identify the function.
- Parameters (arguments) through which we pass values to a function. They are optional.
- A colon (:) to mark the end of the function header.
- Optional documentation string (docstring) to describe what the function does.
- One or more valid python statements that make up the function body. Statements must have the same indentation level (usually 4 spaces).
- An optional return statement to return a value from the function.
#### String in function
We can also use string in function statement.
### Return
The return statement is used to exit a function and go back to the place from where it was called.
#### Syntax of return
return [experession_list]
This statement can contain an expression that gets evaluated and the value is returned. If there is no expression in the statement or the return statement itself is not present inside a function, then the function will return the None object.
### Pass by reference vs value
- Passing by reference means the called functions' parameter will be the same as the callers' passed argument (not the value, but the identity - the variable itself).
- Pass by value means the called functions' parameter will be a copy of the callers' passed argument.
### Local vs Global Variables
This means that local variables can be accessed only inside the function in which they are declared, whereas global variables can be accessed throughout the program body by all functions. When you call a function, the variables declared inside it are brought into scope. <br>
:arrow_backward: [Back](#outline)

## Modules
A Python module is a file containing Python definitions and statements. A module can define functions, classes, and variables. A module can also include runnable code. Grouping related code into a module makes the code easier to understand and use. It also makes the code logically organized.
1. Math Module
2. Random Module
3. Date Module
4. Numpy Module
5. sys Module
6. io Module<br>
:arrow_backward: [Back](#outline)

## Library
1. Pandas
    - Series :arrow_right: A Pandas Series is like a column in a table. It is a one-dimensional array holding data of any type.
    - DataFrame :arrow_right: A Pandas DataFrame is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns.
2. Matplotlib
3. Seaborn<br>
:arrow_backward: [Back](#outline)
