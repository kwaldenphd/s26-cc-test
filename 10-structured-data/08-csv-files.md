# CSV Files

We'll be working with the `.csv` file type. CSV stands for "comma-separated values." CSV files are tabular data structures (i.e. a spreadsheet), stored in a plain-text format. In `.csv` files, each line represents a row in the spreadsheet, and commas separate cells in each row (thus the file format name comma-separated values). 

At first glance, `.csv` files look similar to proprietary spreadsheet program file formats, such as files saved in Microsoft Excel or Apple Numbers.

A few characteristics that distinguish `.csv` files (or other plain-text delimited data formats) from proprietary spreadsheet file types:
- Columns in a `.csv` file don't have a value type. Everything is a string.
- Values in a `.csv` file don't have font or color formatting
- `.csv` files only contain single worksheets
- `.csv` files don't store formatting information like cell width/height
- `.csv` files don't recognize merged cells or other kinds of special formatting (frozen or hidden rows/columns, embedded images, etc.)

Given these limitations, especially compared to the way we often interact with spreadsheet programs like Microsoft Excel or Google Sheets, what's the advantage of working with `.csv` files? 

One key advantage of `.csv` files is their simplicity. You can load or open a `.csv` file in a text editor and be able to quickly see the values in the file. When working with data in a programming environment, `.csv` files as a plain-text format simplify the process of loading structured data.

## CSV & Python

Python's `csv` module is a useful resource for working with this data structure ([link to more detailed tutorial](https://github.com/kwaldenphd/python-structured-data/tree/main#csv-files-in-python)).