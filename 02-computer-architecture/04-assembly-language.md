# Assembly Language

## <i class="fa-solid fa-person-chalkboard" aria-hidden="true"></i> Lecture

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=bae0c40a-1e2d-43bc-b27c-aef40109b060">Assembly Language</a></td>
  </tr>
  </table>

## <i class="fa-solid fa-key" aria-hidden="true"></i> Key Concepts

```{image} ../images/ch2/pep9.png
:alt: PEP9 instruction format
:width: 500px
:align: center
```

```{admonition} Assembly Language
:class: tip, dropdown
"In computer programming, assembly language...is any low-level programming language with a very strong correspondence between the instructions in the language and the architecture's machine code instructions. Assembly language usually has one statement per machine instruction (1:1)...Because each assembly depends on the machine code instructions, each assembly language is specific to a paticular computer architecture" ([Wikipedia](https://en.wikipedia.org/wiki/Assembly_language))
```

```{admonition} Assembler
:class: tip, dropdown
"An assembler program creates object code by translating combinations of mnemonics and syntax for operations and addressing modes into their numerical equivalents. This representation typically includes an operation code ('opcode') as well as other control bits and data. The assembler also calculates constant expressions and resolves symbolic names for memory locations and other entities" ([Wikipedia](https://en.wikipedia.org/wiki/Assembly_language#Assembler))
```

```{admonition} Instruction Specifier
:class: tip, dropdown
Typically the first byte of an instruction. If present, it indicates which operation is being performed. Also tells the computer how to process the operand.
```

```{admonition} Operand Specifier
:class: tip, dropdown
Typically the second and third bytes in an instruction. If present, it can hold the operand or its address (location).
```

```{admonition} Operation Codes (opcodes)
:class: tip, dropdown
Typically 4-8 bits. It indicates the instruction specifier format and can include a register specifier.
```

```{admonition} Addressing Mode
:class: tip, dropdown
Typically 3 bits. It indicates how to interpret the operand specifier.
```

## <i class="fa-solid fa-clipboard-check" aria-hidden="true"></i> Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/how-computers-work/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSc1CvbF9ttUsh6vQhy3dlCIG3peps0y1jIlbgi7IrIPXIEe-A/viewform?usp=sf_link">Assembly Language Comprehension Check</a></td>
  </tr>
  </table>

## <i class="fa-solid fa-clipboard-question" aria-hidden="true"></i> Application

Q4: Describe the relationship of assembly language and machine language (or machine code) in your own words.
