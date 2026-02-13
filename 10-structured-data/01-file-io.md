# File I/O

## Lecture

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
  <td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=73668810-b5ed-4fc2-b606-af36012da392">File I/O in Python</a></td>
  </tr>
  </table>

## Core Concepts

Before we start loading data files in Python, let's talk more about how programming languages handle creating, reading, and writing files.

From Busbee and Braunschweig's "[File Input and Output](https://press.rebus.community/programmingfundamentals/chapter/file-input-and-output/)," in *Programming Fundamentals*:

<blockquote>"A computer file is a computer resource for recording data discretely in a computer storage device. Just as words can be written to paper, so can information be written to a computer file.
<br><br>
"There are different types of computer files, designed for different purposes. A file may be designed to store a picture, a written message, a video, a computer program, or a wide variety of other kinds of data. Some types of files can store several types of information at once.
<br><br>
"By using computer programs, a person can open, read, change, and close a computer file. Computer files may be reopened, modified, and copied an arbitrary number of times."</blockquote>

To break that down:
- Files store information
- Files have different formats or types
- Core file tasks (when working in a programming environment): `open`, `read`, `modify` or `change`, `close`