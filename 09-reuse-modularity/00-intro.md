# Code Reuse & Modularity in Python

We've previously been introduced to the concept of **code blocks**. From Busbee and Braunschweig's "[Code Blocks](https://press.rebus.community/programmingfundamentals/chapter/code-blocks/)" from *Programming Fundamentals*:
- "A code block, sometimes referred to as a compound statement, is a lexical structure of source code which is grouped together. Blocks consist of one or more declarations and statements. A programming language that permits the creation of blocks, including blocks nested within other blocks, is called a block-structured programming language. Blocks are fundamental to structured programming, where control structures are formed from blocks."
   
Approaching a program as a series of components that each accomplish tasks that are part of the larger workflow gets us to a new concept: **modularity** or **modular programming**

From Busbee and Braunschweig's "[Modular Programming](https://press.rebus.community/programmingfundamentals/chapter/modular-programming/)," in *Programming Fundamentals*:
- "Modular programming is a software design technique that emphasizes separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality."

Code blocks are one way to think about these discrete parts of a program. A more precise term used in programming languages is **function.** "Functions are important because they allow us to take large complicated programs and to divide them into smaller manageable pieces. Because the function is a smaller piece of the overall program, we can concentrate on what we want it to do and test it to make sure it works properly" (Busbee and Braunschweig, [Modular Programming](https://press.rebus.community/programmingfundamentals/chapter/modular-programming/)).

## Acknowledgements

When building this chapter, the author consulted materials developed by:
- [Dr. Peter Bui](http://www3.nd.edu/~pbui/) for the [CSE 10101 "Elements of Computing I" course](https://www3.nd.edu/~pbui/teaching/cdt.30010.fa16/).
  * [Conditional and Alternative Execution](http://nbviewer.jupyter.org/urls/gitlab.com/snippets/25773/raw)
  * [Functions](http://nbviewer.jupyter.org/urls/gitlab.com/snippets/26619/raw)
- [Dr. Janet Davis](https://cs.whitman.edu/~davisj/) for the the [CSC 105 "The Digital Age" course](https://www.cs.grinnell.edu/~davisjan/csc/105/2012S/).
  * [Laboratory: Programming in Python (Decisions and Repetition)](http://www.cs.grinnell.edu/~davisjan/csc/105/labs/python3.html)
- [Dr. Corey Pennycuff](https://www3.nd.edu/~cpennycu/) for the [CSE 10101 Elements of Computing (Fall 2019)](https://www3.nd.edu/~cpennycu/2019/fa-CSE10101-CDT30010.html).
  * [Control flow structures](https://www3.nd.edu/~cpennycu/2019/assets/fall/EOC/19.09.03.ipynb)
  * [Functions](https://www3.nd.edu/~cpennycu/2019/assets/fall/EOC/19.09.19.ipynb)
  * [String functions and manipulation](https://www3.nd.edu/~cpennycu/2019/assets/fall/EOC/19.10.01.ipynb)
- [Lindsay K. Mattock](http://lindsaymattock.net/) for the the [SLIS 5020 Computing Foundations course](http://lindsaymattock.net/computingfoundations.html).

Definitions and explanations in this chapter are adapted from Kenneth Leroy Busbee and Dave Braunschweig, *[Programming Fundamentals: A Modular Structured Approach, 2nd Edition](https://press.rebus.community/programmingfundamentals/)* (Rebus Press, 2018)
- [Chapter III, Functions](https://press.rebus.community/programmingfundamentals/part/functions/)

## Chapter Contents 

```{tableofcontents}
```

## Application

Your answers to this chapter's application questions should be added to the notebook template.
- [Google Colab link](https://colab.research.google.com/drive/1MNNieBi2tzpM_HokrnMdB_YO0uyozZhW?usp=sharing) (ND users only)

Submit the Colab link on Canvas for the assignment submission.