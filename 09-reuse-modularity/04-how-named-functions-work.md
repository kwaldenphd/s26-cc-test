# How Named Functions Work

So what happens when we use the `def` keyword to create a named function?

Programs are always executed sequentially, one statement at a time. Function definitions create new functions, but do not execute the bodies or statements within the functions UNTIL the functions are called.

When we call a named function, the program jumps to the definition for the function being called, executes the function's body, and then returns to the point in the program where the function was called and resumes executing the program.

As mentioned earlier, functions are an example of a control structure. 

Let's look at some examples in Python.