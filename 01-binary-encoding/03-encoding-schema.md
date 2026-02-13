# Encoding Schema

## <i class="fa-solid fa-person-chalkboard" aria-hidden="true"></i> Lecture

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
  <td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=124b4fbb-7a33-4d0d-9cc9-aef3015169e6">Encoding Schema</a></td>
  </tr>
  </table>
  
## <i class="fa-solid fa-key" aria-hidden="true"></i> Key Concepts

<table border="0"><tr><td><p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/ACM_1.png?raw=true" width="40%"></p></td>
<td><p align="center"><img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/ACM_2.png?raw=true" width="40%"></p></td></tr>
<tr><td>Table 1a. R.W. Bemer, "<a href="https://web.archive.org/web/20131017062654/http://www.trailing-edge.com/~bobbemer/SURVEY.HTM">Survey of coded character representation</a>", Commun. ACM 3, No. 12, 639-641, 1960 Dec</td><td>Table 2. H.J. Smith, Jr., F.A. Williams, "<a href="https://web.archive.org/web/20131017062654/http://www.trailing-edge.com/~bobbemer/SURVEY.HTM">Survey of punched card codes</a>", Commun. ACM 3, 639 & 642, 1960 Dec</td></tr></table>

```{admonition} Character Encoding
:class: tip, dropdown
"Character encoding is used to represent a repertoire of characters by some kind of encoding system. Depending on the abstraction level and context, corresponding code points and the resulting code space may be regarded as bit patterns, octets, natural numbers, electrical pulses, etc. A character encoding is used in computation, data storage, and transmission of textual data" ([Wikipedia](https://en.wikipedia.org/wiki/Character_encoding))
```
```{image} ../images/ch1/ASCII.png 
:alt: USB flash drive
:width: 500px
:align: center
```

```{admonition} American Standard Code for Information Interchange (ASCII)
:class: tip, dropdown
"A character encoding standard for electronic communication. ASCII codes represent text in computers, telecommunications equipment, and other devices. Most modern character-encoding schemes are based on ASCII, although they support many additional characters" ([Wikipedia](https://en.wikipedia.org/wiki/ASCII))
```

```{admonition} Hexadecimal (hex)
:class: tip, dropdown
"In mathematics and computing, hexadecimal (also base 16, or hex) is a positional system that represents numbers using a base of 16. Unlike the common way of representing numbers with ten symbols, it uses sixteen distinct symbols, most often the symbols ‘0’–’9’ to represent values zero to nine, and ‘A’–’F’ (or alternatively ‘a’–’f’) to represent values ten to fifteen. Hexadecimal numerals are widely used by computer system designers and programmers, as they provide a human-friendly representation of binary-coded values. Each hexadecimal digit represents four binary digits…For example, a single byte can have values ranging from 00000000 to 11111111 in binary form, which can be conveniently represented as 00 to FF in hexadecimal" ([Wikipedia](https://en.wikipedia.org/wiki/Hexadecimal))
```

```{admonition} Sample Conversation Table
:class: tip, dropdown
<table><tr><th>Decimal</th><th>Hex</th><th>Binary</th><th>ASCII Character</th><th>Description</th></tr>
 <tr><td>0</td><td>00</td><td>000000</td><td>NUL</td><td>Null character</td></tr>
 <tr><td>48</td><td>30</td><td>0110000</td><td>1</td><td>Digit 1</td></tr>
 <tr><td>65</td><td>42</td><td>1000001</td><td>A</td><td>Uppercase A</td></tr>
 <tr><td>97</td><td>61</td><td>1100001</td><td>1</td><td>Lowercase a</td></tr></table> 

[Click here](https://www.asciitable.xyz/) for a full ASCII conversion table.
```

```{admonition} Unicode
:class: tip, dropdown 
"Unicode is a computing industry standard for the consistent encoding, representation, and handling of text expressed in most of the world's writing systems. The standard is maintained by the Unicode Consortium, and as of May 2019 the most recent version, Unicode 12.1, contains a repertoire of 137,994 characters (consisting of 137,766 graphic characters, 163 format characters and 65 control characters) covering 150 modern and historic scripts, as well as multiple symbol sets and emoji" ([Wikipedia](https://en.wikipedia.org/wiki/Unicode))
- [Click here](https://home.unicode.org/basic-info/overview) to learn more about the Unicode consortium
```

## <i class="fa-solid fa-clipboard-check" aria-hidden="true"></i> Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/bits-bytes/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLScOk5_z6dRF8WvPUezpyU78sI2bvVrdnySVmNfH9IUGnXYh0w/viewform?usp=sf_link">Encoding Schema Comprehension Check</a></td>
  </tr>
  </table>