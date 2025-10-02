# Text-Editor

## kilo.c - A small, self-contained text editor

**This project was completed by following this *[tutorial](https://github.com/snaptoken/kilo-tutorial)***  

This file implements a simple text editor for the terminal, inspired by the kilo editor by Salvatore Sanfilippo.  
It demonstrates terminal control, file I/O, syntax highlighting, and basic text editing features in C.

## BUILD INSTRUCTIONS

To build kilo, simply run:  
`gcc -o kilo kilo.c -Wall -Wextra -pedantic -std=c99`

## USAGE

`./kilo [filename]`

If a filename is provided, kilo will open and edit that file. If not, it starts with an empty buffer.

## KEY COMMANDS (while running)

**Ctrl-S:**     Save the current file  
**Ctrl-Q:**      Quit the editor (requires confirmation if unsaved changes)  
**Ctrl-F:**      Search within the file  

Arrow Keys  Move the cursor  
Page Up/Down, Home/End, Backspace, Delete, Enter, etc. are supported  

## FUNCTIONAL OVERVIEW  

**Arguments:**  
filename (optional): File to open and edit  

**Flags:**  
None (all options are via key commands)
