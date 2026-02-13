# Opening Files

The `open()` function lets us open an existing file or create a new file in Python. For either version of `open()` (new file or existing file), we need to specify the file name (with the file type extension) and access mode.

Core syntax for opening an existing file:

```Python
open(file_name.extension, access_mode)
```

The file type extension is the string of characters that follows the period after the file name. Examples include `.py`, `.csv`, `.txt`, etc. The types of file handling functions we are covering in this lab will generally only support reading and writing plain-text (or machine-readable) files.