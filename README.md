# Assessment

Style:
Use and naming of variables and functions 
Use and clarity of comments 
Good style increases readability and clarity helps avoid introducing errors

Simplicity:
One of the most important properties of any software system is the ability to understand what it is going to do without having to run it. Previous code was written in a way that's very hard to read and understand the logic, so we simplified the logic by reducing the layers of if-else statements. Now we have one layer of if-else statement with multiple conditions. Now it is very easy to see in what cases which functions will be executed and what value will be returned. 

Maintainability:
By assigning variables and having helper functions, we have modularized the code so that if any small component needs change we can do so by modifying some variable or the function without having to change the whole structure and rewriting the whole block of code. These helper functions are kind of like groups of individual functions so if we need to change or add anything to the existing code, we can do so by adding new helper functions or modifying the existing ones. When adding a new component to an existing codebase, we really want to make sure the current workflow, i.e. the parts untouched, keeps working. So modularizing your code and having different variables and functions you can use makes the code easy to organize and less prone to error. 
