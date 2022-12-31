# Lexical-Analyzer-and-Syntax-Tree-in-Python
Implementation of Lexical analyzer using `RE` library and Syntax tree using `AST` library of python.


## Implementation of lexical analyzer

The implementation of the lexical analyzer is made easy in python with the help of a built-in Library/Module. Python has a built-in package called re, which can be used to work with Regular Expressions. 

We first import the re module, when we have imported the re module, we can start using regular expressions. We then store an expression in exp variable, also can take input of expression by the user. 

The re module offers functions that allow us to search a string for a match. findall function returns a list containing all matches. We use findall function and give the arguments, the tokens we want to search, and the expression. This function then finds all the tokens in the expression and stores them in the tok variable. 

Now the tokens are stored in tok variables. And then the tokens in the expression can be printed.

## Implementation of syntax tree using AST library of python 

AST stands for Abstract Syntax Tree, which is a potent tool of the Python programming language. It allows us to interact with the Python code itself and can modify it. The ast module helps Python applications to process trees of the Python abstract syntax grammar.

We import ast library first and then use its built-in functions.

The parse() function from the module is used to generate an abstract syntax tree for the code. An abstract syntax tree can be compiled into a Python code object using the built-in compile() function.

The dump() method is used to get a formatted string of the tree. It returns the formatted string, which contains information about the fields and values for the tree. This generally helps debug and get the idea of the distribution of components on the tree.


