# Command Line on Linux and Bash Scripting

## Table of Contents

- [Command Line](#command-line)
    - [Basic Command](#basic-command)
    - [File Permission](#file-permission)
    - [File Management](#file-management)
    - [File Compression](#file-compression)
    - [File Editor](#file-editor)
    - [File Utilities](#file-utilities)
    - [Directory Utilities](#directory-utilities)
    - [Disk Utilities](#disk-utilities)
- [Bash Scripting](#bash-scripting)
    - [Bash Script Header](#bash-script-header)
    - [Variables](#variables)
    - [User Input](#user-input)
    - [Arrays](#arrays)
    - [File Test](#file-test)
    - [Comparison Operators](#comparison-operators)
        - [Integer Operators](#integer-operators)
        - [String Operators](#string-operators)
    - [Conditionals](#conditionals)
    - [Loops](#loops)
        - [For Loops](#for-loops)
        - [While Loops](#while-loops)
        - [Until Loops](#until-loops)
    - [Functions](#functions)

### Command Line
The Linux command line or also known as shell, terminal, console, command prompts or many others that is a computer program intended to interpret commands is a text interface on computer. It allows users to execute commands by manually typing at the terminal.

#### Basic Command
- `sudo [command]` allows us to run [command] in superuser mode.
- `man [command]` displays help pages of [command].
- `echo -n` displays a line of text.

#### File Permission
- `chmod -c -R` modify read, write, and executable permission of a file
- `chown -c -R` changes file ownership

#### File Management
- `find` looks for a file
- `ls` displays list content of a directory
- `rm` removes files 
- `cp` copies files or directory
- `file` identifies the file type
- `mv` moves files 
- `grep`prints lines matching pattern

#### File Compression
- `zip` creates .ZIP files
- `unzip` extracts .ZIP files

#### File Editor
- `nano` pico clone
- `vi` visual editor

#### File Utilities
- `split` splits file into pieces
- `diff` compares a file line by line
- `cat` concatenates files tot the standard output

#### Directory Utilities
- `mkdir` creates a directory
- `rmdir` removes a directory

#### Disk Utilities
- `mount -a -t` mounts a filesystem
- `unmount -f -v` unmounts a filesystem

### Bash Scripting
A Bash Script is a single command or a set of command that is used to automate repetitive tasks on Linux filesystem.

#### Bash Script Header
- `#!/bin/bash` or `#!/usr/bin/env bash` tells the operating system that this path should use to interpret the file

#### Variables
`$` used for variables and parameters
```bash
    #!/bin/bash
    name = "Eric Garcia"
    echo "Hi I'm $name"
```

#### User Input
```bash
    #!/bin/bash
    name = "What's ur name ?"
    read name
    
    echo "Nice to meet u $name"
```

#### Arrays
- `array = ("element1" "element2" "element3")` used to create an array of strings
- `${array[x]}` used to get an element of array on index "x"
- `${array[@]}` used to get the total number of elements in the array
- `${array[*]}` used to get all elements in the array
```bash
    arr=("lion" "dolphin" "cat" "bear")

    echo ${arr[0]} #it will print lion

    echo "${arr[@]}" #it will print 4 

    echo ${arr[*]} #it will print lion, dolphin, cat, bear
```

##### File Test
- ``
- ``
- ``
- ``
