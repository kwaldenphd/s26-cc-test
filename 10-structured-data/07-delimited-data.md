# Delimited Data

<p align="center"><img src="https://github.com/kwaldenphd/python-structured-data/blob/main/images/table_diagram.png?raw=true" width="1000"></p>

"A delimited file is a sequential file with column delimiters. Each delimited file is a stream of records, which consists of fields that are ordered by column. Each record contains fields for one row. Within each row, individual fields are separated by column delimiters. All fields must be delimited character strings, non-delimited character strings, or external numeric values. Delimited character strings can contain column delimiters and can also contain character string delimiters when two successive character string delimiters are used to represent one character." (IBM, "[Delimited File Format](https://www.ibm.com/docs/en/db2-for-zos/11?topic=utilities-delimited-file-format)", 5 February 2022)

One of the most common examples of a delimited data structure is a table, with file formats you may often open using spreadsheet programs like Microsoft Excel, Google Sheets, or Apple Numbers.

However, the file formats associated with spreadsheet programs (`.xlsx` for Microsoft Excel and `.numbers` for Numbers) are NOT plain-text formats. Try to open these file types in a text editor and you'll quickly see the additional content and markup added by the spreadsheet program.