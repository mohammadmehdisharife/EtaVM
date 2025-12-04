# CSXL Script Execution Language
A lightweight scripting language for command execution and automation.

## Complete Syntax Examples
# Simple print command
PRINT Hello World

# String variable
STR name mohammad
PRINT my name is: $name

# Integer variable  
INT age 19
PRINT my age is: $age

# Shell command execution
SHELL ls -la

# Multiple variables
STR greeting "Hello"
STR target "World"
PRINT $greeting $target

# Complete sample script:
PRINT "=== System Information ==="
STR system_name "CSXL Demo"
INT version 1
PRINT System: $system_name
PRINT Version: $version
PRINT "=== Directory Listing ==="
SHELL pwd
SHELL ls
PRINT "=== Script Complete ==="

## Installation Commands
# Download the interpreter
curl -o csxl https://download.csxl.org/latest/csxl
# Make executable
chmod +x csxl
# Run a script
./csxl script.csxl

## Features
- Simple, clean syntax
- Cross-platform compatibility  
- Variable support (string and integer)
- Shell command integration
- Lightweight and fast

## License
GNU General Public License v3.0 (GPL-v3)
