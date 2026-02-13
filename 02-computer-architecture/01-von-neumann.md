# Von Neumann Architecture

```{image} ../images/ch2/laptop-spec-comparison.png
:alt: Laptop spec comparison
:width: 750px
:align: center
```

If you've ever purchased a laptop, you may have encountered an overwhelming number of details about different aspects of the product. This information is often referred to as "specifications" (or "specs"). The next few labs will focus on breaking down some of these components to better understand the hardware and software building blocks that make up a computer.

Specifically, we'll be using a framework called the `von Neumann architecture`, named for the Hungarian-American scientist [John von Neumann](https://en.wikipedia.org/wiki/John_von_Neumann). Developed in the 1940s, this computer design framework is based on the principle that data and instructions have the same logical significance to the computer. Rather than separate data and instructions, the von Neumann architecture conceptualizes a computer system that is able to store instructions and data. This is referred to as a `stored-program computer`.

To learn more about von Neumann architecture:
- [Wikipedia](https://en.wikipedia.org/wiki/Von_Neumann_architecture)
- John von Neumann, "[First Draft of a Report on the EDVAC](http://web.mit.edu/STS.035/www/PDFs/edvac.pdf)", *IEEE Annals of the History of Computing* 15:4 (1993): 29-43. Originally published in 1945.

```{image} ../images/ch2/von-neumann-architecture.png
:alt: Von Neumann Architecture diagram
:width: 500px
:align: center
```

The core components of the von Neumann architecture:
- Input and output
- Control unit
- Arithmetic and logic unit (ALU)
- Memory unit
  * The last three components (control unit, ALU, memory) make up the central processing unit (CPU) 