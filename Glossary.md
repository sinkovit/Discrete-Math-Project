# Glossary
This file provides brief definitions of programming and math terms that may be unfamiliar

## Programming
+ <p>Syntax<a id='Syntax'></a>: A set of programming rules that the language has to follow. This includes any structure rules or keywords that are necessary for the computer to interpret the code. Examples in python include if():, not, **, for():, tab, etc. <p>

+ <p>Delimiter<a id='Delimit'></a>: A marker used to denote the boundry between different areas. For python, whitespaces serve as delimiters. 
    
    ```python
    if(something):
        some_command
        some_command2
    ```
    
    In the above case, if something is false, neither command will be executed
    
    ```python
    if(something):
        some_command
    some_command2
    ```
    
    In this case, some_command2 will always be executed, even if something is false<p>

+ <p>Whitespace<a id='Whitespace'></a>: In python, the space between different blocks of the code marks them as separate.
    
    ```python
    if(somethingandother_thing):
    ```
    
    Will check one variable named 'somethingandother_thing' for true or false
    
    ```python
    if(something and other_thing):
    ```
    
    While the above will check two variables 'something' and 'other_thing' and execute if they are both true<p>

+ <p>Arguments<a id='Arguments'></a>: An argument is a input for any procedure in programming. The argument represents the real value or object given to the procedure to operate on. 
    
    ```python
    true_or_false = false
    saved_value = 1
    if(true_or_false):
        multiply_by_10(saved_value)
    ```
    
    The definition of argument is often interchangable with the definition of parameter, so the arguments in this example are true_or_false or false for the if(): statement and saved_value or 1 for multiply_by_10() <p>
        
+ <p>Variable Types<a id='Variable_Types'></a>: A variable can have many different types which dictates how different functions will respond to it.
    
    * int: integers. e.g 1, -10, 212
    * float: numbers including decimals. e.g 1.0, -2.1, 341.212
    * boolean<a id='Booleans'></a>: True or False.
    * string<a id='String'></a>: A collection of any number of characters. e.g "a", "212", "Hello world!"
    * list<a id='Lists'></a>: A collection of any number of objects, strings, numbers. Denoted by []. e.g [1.0, "Jones", True, 212, 212]
    * set<a id='Sets'></a>: A collection similar to a list, however elements cannot be repeated and it is not ordered. Denoted by {}. e.g [1.0, "Jones", True, 212]
    * tuple: A collection similar to list, however it's contents and size cannot be changed. Denoted by (). e.g (1, "Toby", 2.34)<p>
<p>
        
+ <p>Elements<a id='Elements'></a>: Anything contained within a list or a tuple. e.g 1, "Jones", True, 212 are the elements of [1, "Jones", True, 212] <p>

+ <p>Conditional<a id='Conditional'></a>: A statement that performs an action depending on some sort of condition. Different conditionals include if statements, switch statements, or other comparison statements
    
    ```python
    if(conditional):
        do something
    ```
    
## Math
+ Sample item 1: definition

+ Sample item 2: definition