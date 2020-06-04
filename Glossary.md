# Glossary
This file provides brief definitions of programming and math terms that may be unfamiliar

## Programming
+ <p><b>Syntax</b><a id='Syntax'></a>: A set of programming rules that the language has to follow. This includes any structure rules or keywords that are necessary for the computer to interpret the code. Examples in python include if():, not, **, for():, tab, etc. <p>

+ <p><b>Delimiter</b><a id='Delimit'></a>: A marker used to denote the boundry between different areas. For python, whitespaces serve as delimiters. 
    
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

+ <p><b>Whitespace</b><a id='Whitespace'></a>: In python, the space between different blocks of the code marks them as separate. See above for an additional example of whitespace delimiting in python.
    
    ```python
    if(somethingandother_thing):
    ```
    
    Will check one variable named 'somethingandother_thing' for true or false
    
    ```python
    if(something and other_thing):
    ```
    
    While the above will check two variables 'something' and 'other_thing' and execute if they are both true<p>

+ <p><b>Arguments</b><a id='Arguments'></a>: An argument is a input for any procedure in programming. The argument represents the real value or object given to the procedure to operate on. 
    
    ```python
    true_or_false = false
    saved_value = 1
    if(true_or_false):
        multiply_by_10(saved_value)
    ```
    
    The definition of argument is often interchangable with the definition of parameter, so the arguments in this example are true_or_false or false for the if(): statement and saved_value or 1 for multiply_by_10() <p>
        
+ <p><b>Variable Types</b><a id='Variable_Types'></a>: A variable can have many different types which dictates what kind of information is stored within it and how different functions will respond to it.
    
    * int: integers. e.g 1, -10, 212
    * float: numbers including decimals. e.g 1.0, -2.1, 341.212
    * boolean<a id='Booleans'></a>: True or False.
    * string<a id='String'></a>: A collection of any number of characters. e.g "a", "212", "Hello world!"
    * list<a id='Lists'></a>: A collection of any number of objects, strings, numbers. Denoted by []. e.g [1.0, "Jones", True, 212, 212]
    * set<a id='Sets'></a>: A collection similar to a list, however elements cannot be repeated and it is not ordered. Denoted by {}. e.g [1.0, "Jones", True, 212]
    * tuple<a id='Tuple'></a>: A collection similar to list, however it's contents and size cannot be changed. Denoted by (). e.g (1, "Toby", 2.34)<p>
<p>
        
+ <p><b>Elements</b><a id='Elements'></a>: Anything contained within a list or a tuple. e.g 1, "Jones", True, 212 are the elements of [1, "Jones", True, 212] <p>

+ <p><b>Conditional</b><a id='Conditional'></a>: A statement that performs an action depending on some sort of condition. Different conditionals include if statements, switch statements, or other comparison statements
    
    ```python
    if(condition):
        do something
    ```
    
    If the conditional evaluates to true, the something will be executed, otherwise the commands contained within the indent will be ignored.<p>
    
+ <p><b>Nesting</b><a id='Nesting'></a>: Nesting is the process of putting multiple conditional statements within one another. This is usually indicated through various levels of indentation in most programming languages, and is key in python as whitespaces serve as a delimiter for different blocks of code.
    
    ```python
    if(something):
        some_command
    
        if(something_different):
            different_command
    
            if(something_different_2):
                different_command_2
    
        while(some_other_conditional):
            some_other_command
    ```
 
    In the above example, `if(something_different)` and `while(some_other_conditional)` are both nested within `if(something)` and `if(something_different_2)` is nested within `if(something)` and `if(something_different)`<p>
    
+ <p><b>Iterate</b><a id='Iterate'></a>: Iteration is the repetition of some block of code until a specified condition is met. This is done in programming through creating some sort of loop.
    
    ```python
    while(condition_evaluates_to_true):
        some_repeated_command
    ```

    In the above example, the while loop is iterated until the condition evaluates to false.
    
    ```python
    list = [1, 2, 3]
    for(element in list):
        element = element+1
        print(element)
    ```
    
    In the above example, the loop iterates through the list, meaning that it will perform the command for each `element` in `list`. Specifically in this example, the for loop will print each element plus 1. The output will be 
    2
    3
    4<p>
    
+ <p><b>Instance</b><a id='Instance'></a>: An instance in programming is an object that has been created. Creating an object from a class is called instantiating it for this reason.
    
    ```python
    string1 = "tree"
    string2 = "bush"
    ```
    
    In the above code, we instantiate an object, `string1` and 'string2', of class string. The power of instances is that different instances can contain different variables. In this case, `string1` and `string2` are both objects of class string, however they contain different strings. <p>
        
+ <p><b>Index</b><a id='Index'></a>: The index of an object is it's position in a list, array, string, etc. The first position is at index '0'. 
    
    ```python
    string1 = "tree"
    list1 = [1, 2.0, "three"]
    ```
    
    In the above example, string1[0] would be 't', list1[0] would be 1, string1[1] would be 'r', list1[1] would be 2.0, string1[-1] would be 'e', and list1[-1] would be "three".
    
## Math
