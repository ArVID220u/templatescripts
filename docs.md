# List of all commands

- pycr
- cpcr
- txcr

## pycr

#### Usage

    pycr filename

#### Description

Creates a very simple Python 3 file, and makes it executable.

## cpcr

#### Usage

    cpcr filename [options]

#### Options

- `-f`: Force creation of the file. If there already exists a file with the same name, overwrite it.

#### Description

Creates a simple C++ template, targeted towards competitive programming (with inclusion of all libraries and convenient typedefs). Utilizes C++11 syntax, and presumes the use of GCC compiler.

Appends the extension `.cpp` if not already present in the filename.

## txcr

#### Usage
    
    txcr filename [options]

#### Options

- `-f`: Force creation of the file. If there already exists a file with the same name, overwrite it.

#### Description

Creates a simple LaTeX template.

Appends the extension `.tex` if not already present in the filename.
