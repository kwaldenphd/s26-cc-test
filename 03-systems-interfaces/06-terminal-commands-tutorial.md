# Tutorial: Working in the Terminal

You may have already noticed you're not able to navigate the terminal using your mouse or cursor. We can navigate the terminal using the keyboard. The `up` and `down` arrow keys let you move back (up) and forward (down) through previously typed commands. The `left` and `right` arrow keys let you move within characters or symbols for a specific command.

Press the `up` arrow once to show the previously-typed `echo` command. Then, use the `left` and `right` arrow keys to navigate to the characters within the quotation marks and replace them with another word or phrase of your choosing. Press `Return` or `Enter` to run the modified command. 

A couple other useful navigation tools:
- Press `Control` + `A` to move to the start of a line
- Press `Control` + `E` to move to the end of a line
- Type `clear` into the terminal and press `Return`/`Enter` to clear the screen
- When you're ready to close the terminal window, type `exit` and press `Return`/`Enter`

```{image} ../images/ch3/Fig_D.jpeg
:alt: Terminal syntax 
:width: 500px
:align: center
```

A couple notes on terminal syntax:
- `commands` tell the computer to perform an action 
- `options` modify the command and use a hyphen (`-`) symbol
  * Sometimes `options` are called `flags` or `switches`
- `arguments` specify what the command operation will be performed on (i.e. a specific file or directory)

Not all commands require arguments or options, but some commands can have one or more of each. You can also chain multiple commands together using the vertical bar `|` symbol. This is often called a `pipe`.

## Navigating Your File System

Have you ever tried to find a specific file on your computer? This is a common user task, but we can start to better understand how the computer stores and organizes information.

### `pwd`

```
pwd
```

Before we start moving around, let's use the `pwd` (print working directory) command to show your current location. Type `pwd` in the terminal and press `Enter` or `Return`. Your output might look something like this:
```
/Users/kwalden
```

This directory information is called a `path` (sometimes called a `file path` when dealing with specific files).
- The backslash `/` at the start of the path stands for your computer's `root`
- Subsequent slashes indicate subfolders or subdirectories

So in the `/Users/kwalden` example, the terminal is running in the `kwalden` subfolder which is located in the `Users` folder. The `Users` folder is located at my computer's `root`.

<p align="center"><img align="center" src="https://github.com/kwaldenphd/computer-interfaces/blob/main/images/Fig_E.jpeg?raw=true" alt="Diagram illustrating computer directory structure"></p>

The inverted tree diagram shown above shows one example of a computer's file system.
- The `root` (top of the tree) is your computer's hard drive.
- The next set of branches are a set of folders (`directories`) that are used by everyone who uses the computer
- The `users` folder includes different specific user profiles
- The folders located under a specific username are associated with that user profile
  * These folders commonly include `Applications`, `Desktop`, `Documents`, `Downloads`, etc.

If you have ever used `File Explorer` (Windows) or `Finder` (Mac), you have navigated this tree structure using the graphical user interface (GUI). Now let's think about how we navigate this structure using the command line interface (CLI).

### `ls`

Typically by default, your terminal will open in the folder or directory for your user profile.
- But you can check this using the `pwd` (print working directory) command

```
ls
```

Let's see what other files and subdirectories are located in your current path by using the list command (`ls`). Type `ls` in the terminal and press `Enter`/`Return`.

<p align="center"><img align="center" src="https://github.com/kwaldenphd/computer-interfaces/blob/main/images/Fig_F.jpeg?raw=true" alt="Terminal screenshot showing directory contents"></p>

Items that are followed by a file extension (e.g. `.docx`, `.txt`, `.xlsx`, etc) are generally individual files. Items that do not have a file extension are typically subfolders or subdirectories.

### `cd`

We can move down the tree using the `change directory` command (`cd`). Let's move from your user profile folder to the Desktop.

```
cd Desktop 
```

Type `cd Desktop` and press `Enter`/`Return`.
- You can also type `cd Desk` and press the `Tab` key (before `Enter`/`Return`) to autocomplete the command

When using the `cd` (change directory) command, we are navigating the computer's file system using `relative paths`. This means the location information we are specifying in the terminal is relative to our current position or location in the file system. The previous `cd Desktop` command is an example of a relative path. 

`Absolute paths` always start at the `root` and use backslash `/` symbols to indicate subfolders.
- `/Users/kwalden/Desktop` would be the absolute path version of the previous command
- NOTE: Be sure to replace `kwalden` with your user name

We can use the `ls` command again to see the materials located on our Desktop. We can also move back up the file system tree using the `cd` command.

``` 
cd .. 
```

Instead of using `cd` followed by a relative or absolute path, we can use `cd ..` (`cd` followed by a space and two periods) to move up one level in the tree. Type `cd ..` in the terminal and press `Enter`/`Return`. You can test using `pwd` if needed, but you should be back in the specific user profile folder.

## <i class="fa-solid fa-key" aria-hidden="true"></i> Key Concepts

```{admonition} File Manager (or File Browser)
:class: tip, dropdown
"A file manager or file browser is a computer program that provides a user interface to manage files and folders. The most common operations performed on files or groups of files include creating, opening (e.g. viewing, playing, editing or printing), renaming, copying, moving, deleting and searching for files, as well as modifying file attributes, properties and file permissions. Folders and files may be displayed in a hierarchical tree based on their directory structure" ([Wikipedia](https://en.wikipedia.org/wiki/File_manager))
- Examples: Finder (Mac), File Explorer (Windows)
```

```{admonition} File Extension (or Filename Extension)
:class: tip, dropdown 
"A filename extension, file name extension or file extension is a suffix to the name of a computer file (e.g., `.txt`, `.docx`, `.md`). The extension indicates a characteristic of the file contents or its intended use. A filename extension is typically delimited from the rest of the filename with a full stop (period)" ([Wikipedia](https://en.wikipedia.org/wiki/Filename_extension))
```

```{admonition} Directory
:class: tip, dropdown 
"In computing, a directory is a file system cataloging structure which contains references to other computer files, and possibly other directories. On many computers, directories are known as folders" ([Wikipedia](https://en.wikipedia.org/wiki/Directory_(computing)))
```

```{admonition} Path
:class: tip, dropdown 
"A path is a string of characters used to uniquely identify a location in a directory structure. It is composed by following the directory tree hierarchy in which components, separated by a delimiting character, represent each directory. The delimiting character is most commonly the slash `/`, the backslash character `\`, or colon `:`" ([Wikipedia](https://en.wikipedia.org/wiki/Path_(computing)))
```

```{admonition} Absolute Path
:class: tip, dropdown 
"An absolute or full path points to the same location in a file system, regardless of the current working directory. To do that, it must include the root directory" ([Wikipedia](https://en.wikipedia.org/wiki/Path_(computing)#Absolute_and_relative_paths))
```

```{admonition} Relative Path
:class: tip, dropdown 
"A relative path starts from some given working directory, avoiding the need to provide the full absolute path" ([Wikipedia](https://en.wikipedia.org/wiki/Path_(computing)#Absolute_and_relative_paths))
```