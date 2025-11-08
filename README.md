# Brainfuck_Enchaned
Brainfuck but with a few more things

# Functions
Functions are defined with `{}` and called with `#` symbol.

## Defining Functions
Once a function definition begins number in the current position becomes the function id which can later be used to call it. First 16 ids are reserved for library functions. This means user can define up to 240 functions between range [16-255].

When `#` is received byte in the current pointer position is considered function id

## List of Library Functions
| ID    | Description                                    | Args         |
|-------|------------------------------------------------|--------------|
| 0     | Adds 16 to current memory position             |              |
| 1     | Opens a file and writes its contents to memory | char* path   |

