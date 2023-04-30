# KAsm
Just another attempt to create a programming language in python without using a lexer and tokens

# Feathures
- 1. String formatting:
- ^1 is :
- ^2 is |
- ^3 is ;
- ^4 is ,
- ^5 is (
- ^6 is )
- ^7 is "
- ^[/n is newline
- ^/variable is variable from VAR Keyword

- 2. Keywords ( Thats the most part of language )
- BRK                        = Breaks main section
- RET: 0|;                   = Return exit code
- EXC: some python code|;    = Run python code ( Works with compilers and a little bit corrupted )
- OUT: Hello, world!|;       = Print text to terminal
- VAL: myvar|Content|;       = Set variable

# How to run KAsm code?
To run without compiling use this command : python3 KAsm.py myfile.kasm
To compile code use this command          : python3 KAsm.py myfile.kasm compile
