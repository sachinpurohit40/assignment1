 # ASSIGNMENT 1





```python
1. In the below elements which of them are values or an expression? eg:- values can be
integer or string and expressions will be mathematical operators.

ans.  * is an expression used as a mathematical operator in multiplication.  

      'hello'
ans.  strings. 

       -87.8
ans.   nagative value and float.
        -
ans.    -  is an expression used as a mathamatical operator in substraction.

       /
ans.  / is an expression used as a mathamatical operator in division.

       +
ans.   + is an expression used as a mathematical operator in addition.

        6
ans.   integer.

2.   What is the difference between string and variable?

     ans. string.= A String is a type of information you would store in a Variable.A String is usually words, enclosed with "" .
     eg = "my name" , " hello world " ,"sachin".
   variable =In programming,A Variable is a store of information  a variable is a value that can change, depending on    conditions or on information passed to the program. Typically, a program consists of instruction s that tell the computer what to do and data that the program uses when it is running. The data consists of constants or fixed values that never change and variable values (which are usually initialized to "0" or some default value because the actual values will be supplied by a program's user). Usually, both constants and variables are defined as certain data type s. Each data type prescribes and limits the form of the data. Examples of data types include: an integer expressed as a decimal number, or a string of text characters, usually limited in length.
 

3. Describe three different data types.
    
    
    ans a. integer= It contain negative or positive whole number. eg 0,1,100,-10,-50.
        b. float=It represents real numbers with floating point. Eg, 2.5, 25.23
        c. string=String contains sequence of characters. It represents by using single quotes, double quotes or triple quotes. It is denoted by the class str.
        eg.  “My name” ,"hello world" "purohit".


4.   What is an expression made up of? What do all expressions do?
ans  An expression is made up of a combination of one or more of the following elements:
     Literals: Constants representing fixed values, such as numbers (e.g., 5, 3.14) or strings (e.g., "hello").
     Variables: Identifiers representing memory locations holding values that can change during program execution.
     Operators: Symbols used to perform operations on one or more operands. Common operators include arithmetic operators (+,           -, *, /),
       '+' for adition and '-' is for substraction and '/' is fo division and '*' for multiplication. 
5.    This assignment statements, like spam = 10. What is the difference between an expression and a statement?
       
       
      
    ans.  In programming, "expressions" and "statements" are two fundamental concepts with distinct characteristics:
              Expression: An expression is  a combination of values, variables, operators, and function calls that produces a single value as a         result. Expressions can be as simple as a single constant value or variable, or they can be more complex involving multiple       operations. The key property of an expression is that it evaluates to a value
               eg.  x = 5  # Here, the expression is "5", which evaluates to the value 5. y = 2 * x + 3  # Here, the expression is "2 *        x + 3", which evaluates to some value based on the current value of x.
                Statement:
             A statement is a complete unit of code that performs some action, such as assigning values to variables, controlling         the flow of the program with conditionals or loops, or calling functions. Statements do not produce a value themselves,         but they may modify the program's state or behavior. 
              eg. x = 5  # This is an assignment statement that assigns the value 5 to the variable x.
              if x > 0:  # This is a conditional statement that controls the flow of the program based on the condition x > 0.
             print("x is positive")

6.        After running the following code, what does the variable bacon contain?
               bacon = 22
              bacon + 1
          ans. The variable bacon will still contain the value 22. The expression bacon + 1 evaluates to 23, but the result is                 not assigned back to the variable bacon. Therefore, the value of bacon remains unchanged, which is 22

7.       What should the values of the following two terms be?
               'spam' + 'spamspam' 
         ans=     'spamspamspam'
                'spam' * 3
         ans. =  'spamspamspam' 

8.        Why is eggs a valid variable name while 100 is invalid?

ans.     because variable is always start for alphabet.  and 100 is a value and data It may come inside a container named Eggs.
 
9.      What three functions can be used to get the integer, floating-point number, or string
         version of a value?
ans.     In many programming languages and libraries, you can use the following three functions to convert a value to its corresponding data type:

         Integer Conversion Function:

      Function Name: int() or parenthesize()
      Purpose: Converts a value to an integer data type.
       Example (Python):

      num_str = "10"
      num_int = int(num_str)  # Converts the string "10" to the integer 10

      Floating-Point Conversion Function:
 
      Function Name: float() or parseFloat()
      Purpose: Converts a value to a floating-point number data type.
      Example (Python):
      num_str = "3.14"
      num_float = float(num_str)  # Converts the string "3.14" to the floating-point number 3.14
      String Conversion Function:
      Function Name: str() or toString()
      Purpose: Converts a value to its string representation.
      Example (Python):
      num_int = 42
      num_str = str(num_int)  # Converts the integer 42 to the string "42"
10.    Why does this expression cause an error? How can you fix it?

     'I have eaten' + 99 + 'burritos'.
    
     
ans.    The reason this expression throws an error is that 99 is an integer or 'I  have eaten' and 'burritos' is a string.
       which cannot be addition in python programming.If we want the error not to come, then we have to make 99 a string and to          make a string, we have to write 99 inside quatation marks( '') and add '99'. which will not error.
       'I have eaten' + '99' + 'burritos'
```


      File <tokenize>:27
        variable =In programming,A Variable is a store of information  a variable is a value that can change, depending on    conditions or on information passed to the program. Typically, a program consists of instruction s that tell the computer what to do and data that the program uses when it is running. The data consists of constants or fixed values that never change and variable values (which are usually initialized to "0" or some default value because the actual values will be supplied by a program's user). Usually, both constants and variables are defined as certain data type s. Each data type prescribes and limits the form of the data. Examples of data types include: an integer expressed as a decimal number, or a string of text characters, usually limited in length.
        ^
    IndentationError: unindent does not match any outer indentation level
    



```python

```


