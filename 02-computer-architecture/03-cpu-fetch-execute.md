# CPU & the Fetch-Execute Cycle

## <i class="fa-solid fa-person-chalkboard" aria-hidden="true"></i> Lecture

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=023c10d6-1764-48bf-a75d-aef40109b030">CPU & the Fetch-Execute Cycle</a></td>
  </tr>
  </table>

## <i class="fa-solid fa-key" aria-hidden="true"></i> Key Concepts

```{image} ../images/ch2/input-output.png
:alt: Von Neumann Workflow
:width: 500px
:align: center
```
```{admonition} Input and Output (I/O)
:class: tip, dropdown
I/O devices provide inputs to the system and enable the computer to provide output
- Input device examples: keyboard, mouse, network card, etc.
- Output device examples: monitor, display, printer, etc.
```

```{image} ../images/ch2/von-neumann-architecture.png
:alt: Von Neumann Architecture
:width: 500px
:align: center
```

```{admonition} Processor (or processing unit)
:class: tip, dropdown
"In computing, a processor or processing unit is an electronic circuit which performs operations on some external data source, usually memory or some other data stream. The term is frequently used to refer to the central processor (central processing unit)" ([Wikipedia](https://en.wikipedia.org/wiki/Processor_(computing)))
```

```{admonition} CPU
:class: tip, dropdown
"A central processing unit (CPU), also called a central processor or main processor, is the electronic circuitry within a computer that executes instructions that make up a computer program. The CPU performs basic arithmetic, logic, controlling, and input/output (I/O) operations specified by the instructions…Principal components of a CPU include the arithmetic logic unit (ALU) that performs arithmetic and logic operations, processor registers that supply operands to the ALU and store the results of ALU operations, and a control unit that orchestrates the fetching (from memory) and execution of instructions by directing the coordinated operations of the ALU, registers and other components" ([Wikipedia](https://en.wikipedia.org/wiki/Central_processing_unit))
```

```{admonition} Bus
:class: tip, dropdown
"In computer architecture, a bus…is a communication system that transfers data between components inside a computer, or between computers. This expression covers all related hardware components (wire, optical fiber, etc.) and software" ([Wikipedia](https://en.wikipedia.org/wiki/Bus_(computing)))
```

```{admonition} Instruction Register (IR)
:class: tip, dropdown
Register with the instruction that is currently being executed
```

```{image} ../images/ch2/fetch-execute.png
:alt: Fetch-Execute Cycle
:width: 500px
:align: center
```

```{admonition} Fetch-Execute Cycle
:class: tip, dropdown
Computer processing cycle that includes four main steps:
- Fetch instruction
- Decode instruction
- Get data (if needed)
- Execute instruction
```

## <i class="fa-solid fa-clipboard-check" aria-hidden="true"></i> Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/how-computers-work/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSffdR1H3vNmMPIjRKvhaS1DkzysyDJ1h9vFjHDW_CGP_qmh5g/viewform?usp=sf_link">CPU & Fetch-Execute Comprehension Check</a></td>
  </tr>
  </table>

## <i class="fa-solid fa-clipboard-question" aria-hidden="true"></i> Application

Q3: Describe the three main steps of the fetch-execute cycle in your own words.