# Named Functions

But Python also lets us to create (and name) our own functions.
- Key term: *named function(s)*

We can define or name a function using the `def` keyword. A function definition includes a few core components:
- The name of the new function
- The list of function arguments
- The sequence of statements to execute when the function is called

The core syntax for defining your own function:

```Python
# use def keyword to define function name
def function_name(argument):
 statement(s)
 return result
```

Let's unpack each of those components.
- `def function_name()` is the name you are giving to the function you create- this is the header for the function definition.
  * Function names have many of the same rules as variable names- no spaces or special characters.
- `argument` is the argument that will be passed to the function.
  * When we are initially defining the function, the `argument` value is typically a placeholder.
  * Later in the program when we call the named function, the argument being passed to the function goes in these parenthesis.
- The nested or indented line `statement(s)` is the body of the function definition. It includes a sequence of statements to execute when the function is called.
- The nested or indented line `return result` is a placeholder for the function output or endpoint- it is also part of the body of the function definition.