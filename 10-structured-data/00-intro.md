# Structured Data in Python

In programming languages and computing more broadly, `I/O` stands for `Input` and `Output`.

We've seen `I/O` at at work elsewhere in teh course, where we provided inputs to the computer (using a CPU simulator or working at the terminal), a task or operation was performed, and there was an endpoint or output for that process. 

Similarly, programming languages can take a variety of inputs (user-provided values, data, files, etc) and return outputs in a variety of formats (data stored in memory, output that shows up in the console, newly-created or -modified files, etc). We've seen `I/O` in action in previous units, with Python's `print()` and `input()` functions.

In this chapter, we're going to look at aspects of `I/O` that have to do with reading and writing files, with a focus on two key data structures:
- Tabular data, or data stored as a table consisting of rows and columns
- Data stored as name-value pairs, specifically in the JavaScript Object Notation (`.json`) format

We'll do so by interacting with Python's `csv` module and `json` package, along with the `pandas` Python library.

## Goals

This first part of this chapter provides an overview of fundamental programming concepts in the areas of file I/O and working with structured data, with a focus on Python syntax. Topics covered include:
- Delimited (`.csv`, `.tsv`) and name-value (`.json`, `.xml`) data structures
- Escape characters in relation to delimited data structures
- Working with delimited and name-value data structures in the Python programming environment, with a focus on the `csv` + `json` modules and `list` + `dictionary` data structures
- File I/O and file methods/access modes, with a focus on Python workflows

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
  <td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=304f6392-3cee-4ba6-8da5-af36013a4191">Lab overview</a></td>
  </tr>
  </table>

This second part of this chapter covers the core components of `pandas`, including `Series` and `DataFrame` objects. It covers how to manually create and interact with `Series` and `DataFrame` objects in the Python programming environment. It covers loading a structured data file (CSV and JSON) as a `DataFrame`, and sorting, selecting, and filtering the resulting `DataFrame`. The lab also covers common data parsing and wrangling challenges like duplicate entries and missing data.

By the end of this chapter, students will be able to;
- Understand the basic components of `Series` and `DataFrame` objects in `pandas`
- Manually create `Series` and `DataFrame` objects in Python using `pandas`
- Load a structured data file as a `DataFrame` in Python using `pandas`
- Interact with a `DataFrame` using sorting, selecting, and filtering operations
- Remove duplicate rows from a `DataFrame`
- Understand how to approach common `DataFrame` parsing and loading errors using `pandas`
- Understand the basic components of how to handle missing values in a `DataFrame`

## Acknowledgements

Peer review and editing on the CSV portion of this chapter was provided by Spring 2021 graduate teaching assistant [Aidan Draper](https://github.com/adraper2).

Peer review and editing on the JSON portion of this chapter was provided by Spring 2021 graduate teaching assistant [Subhadyuti Sahoo](https://github.com/SDSAHOO703).

When building the CSV, JSON & file methods sections, the author consulted the following materials:
- Al Sweigart [*Automate the Boring Stuff With Python*](https://nostarch.com/automatestuff2) (No Starch Press, 2020).
  * Chapter 16 "Working With CSV Files and JSON Data" (371-388)
- Wes McKinney, "Chapter 6.1, Reading and Writing Data in Text Format" in [*Python for Data Analysis*](https://www.oreilly.com/library/view/python-for-data/9781491957653/) (O'Reilly, 2017): 169-184.
- Wes McKinney, Chapter 6 "Data Loading, Storage, and File Formats" from [*Python for Data Analysis*](https://www.oreilly.com/library/view/python-for-data/9781491957653/) (O'Reilly, 2018): 169-193

Information and exercises in the pandas sections were developed in consultation with the following resources:
- `pandas` package ["Getting started"](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/) documentation.
- Wes McKinney's [*Python for Data Analysis: Data Wrangling With pandas, Numpy, and IPython*](https://www.oreilly.com/library/view/python-for-data/9781491957653/) (O'Reilly, 2017)
  * Chapter 5 "Getting Started with pandas" (125-168)
  * Chapter 7 "Data Cleaning and Preparation" (195-224)
  * Chapter 8 "Data Wrangling: Join, Combine, and Reshape" (225-256)
  * Chapter 10 "Data Aggregation and Group Operations" (293-322)

## Data Files

You'll need four data files for this chapter.
- `example.csv` ([GitHub](https://raw.githubusercontent.com/kwaldenphd/python-structured-data/main/data/example.csv), [Google Drive](https://drive.google.com/file/d/1loSl4xUf3ElVgWMfWai3SR3vpGhMK6MS/view?usp=drive_link))
- `example.txt` ([GitHub](https://raw.githubusercontent.com/kwaldenphd/python-structured-data/main/data/example.txt), [Google Drive](https://drive.google.com/file/d/1Snl-QnDBz7X2qxf5SdXTd1b0Wc_4ysR5/view?usp=drive_link))
- `example.xlsx` ([GitHub](https://github.com/kwaldenphd/python-structured-data/blob/main/data/example.xlsx), [Google Drive](https://docs.google.com/spreadsheets/d/1qh2ympB2aLcSDl-u8r6VD08xePTtsun7/edit?usp=drive_link))
- `exampleWithHeader.csv` ([GitHub](https://raw.githubusercontent.com/kwaldenphd/python-structured-data/main/data/exampleWithHeader.csv), [Google Drive](https://drive.google.com/file/d/1lZwUzM3rPzzWqyl6RWquGB_Xtk2EPxlR/view?usp=drive_link))

You can also access them [via Google Drive](https://drive.google.com/drive/folders/1Sp_N34753ONJRU2AFKcocQ2DhCEhyL-m?usp=sharing) (ND users only).

You'll need to download these files and put them in the same folder as your Jupyter Notebook (or upload them to Google Colab).

## Application

Your answers to this chapter's application questions should be added to the notebook template.
- [Google Colab link](https://colab.research.google.com/drive/1DTF5vCYuvXrC-MIQJ7Evc_DNX5zg5c9M?usp=sharing) (ND users only)

Submit the Colab link on Canvas for the assignment submission.

## Chapter Contents 

```{tableofcontents}
```