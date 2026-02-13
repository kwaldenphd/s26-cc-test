# Code Reuse & Modularity (aka a quick detour into modules, packages, and libraries)

As we move forward in Python, we're going to be encountering the terms `package`, `module`, and `library.` All of these terms refer to external Python programs that we can use in our program without having to recreate the entire original code. We can think of these resources as "expansion packs" for Python that expand or extend the programming language's built-in functionality.

A few preliminary definitions...
- A ***module*** is a Python file that typically includes specialized functions and variables. Modules typically have `.py` file extensions.
- A single or simple directory of modules is called a ***package***. Packages are typically a simple directory with multiple modules.
- A ***library*** includes blocks of code that can be reused within a program. Libraries are a collection of modules that have a much more complex directory/sub-directory/etc structure than packages

Some modules, packages, and libraries are built-in to Python and require no additional installation. Others have to be installed (typically at the command line, or in the terminal) before you can import and use them in a program.

## Built-In Functions

Built-in functions don't require any extra steps to be able to access them in the programming environment. For example, you can see the source code for the `print()` function, contained in [bltinmodule.c](https://github.com/python/cpython/blob/91f4908798074db6c41925b4417bee1f933aca93/Python/bltinmodule.c#L2145) file in Python's [source code](https://github.com/python/cpython). But all we have to do is use the function name in our program.

## Modules & Packages

<p align="center"><img src="https://github.com/kwaldenphd/python-functions/blob/main/images/python_package.png?raw=true" width="500"></p>

In this example, we have a `game` package that includes `sound`, `image`, and `level` sub-packages. Each of those sub-packages includes specific modules. For example, the `sound` sub-package includes the `load.py`, `play.py`, and `pause.py` modules.

We can bring these modules into our program using an `import` statement.

For example, let's say we wanted to bring the `start.py` module from the `level` sub-package into our program.

We could do this using the following `import` statement at the start of our program.

```Python
from game.level import start
```

Now, we would be able to access any of the functions (or other code) contained in the `start.py` module, because we have **imported** them into our program.

## Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSctIknF2mA209zKSFH7lAA_6dBg9HoAmYDBg58QqNk37YgBVA/viewform?usp=sf_link">Code Reuse & Modularity in Python Comprehension Check</a></td>
  </tr>
  </table>

## Additional Resources

For more on modules, packages, and libraries in Python:
- Programmiz, "[Python Package](https://www.programiz.com/python-programming/package)
- GeeksForGeeks, "[What is the difference between Python's Module, Package and Library?](https://www.geeksforgeeks.org/what-is-the-difference-between-pythons-module-package-and-library/)" (30 September 2022)
- John Sturtz, "[Python Modules and Packages - An Introduction](https://realpython.com/python-modules-packages/)" *Real Python*