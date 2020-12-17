# Get_next_line

The aim of this project is to make a function that returns a line ending with a newline, read from a file descriptor.

Prototype: int get_next_line(int fd, char ** line);

Char ** line = the address of a pointer to a character to be used to store the line read.


Static variable(s) are allowed: Life time of a static variable is the entire run of a program. Allocation is during compilation.


Memory leaks: system("leaks a.out"); By putting this in your main file, you will see if your program has memory leaks. It doesn't tell you where though. But a lot of mistakes that I made had to do with freeing pointers at the wrong place in the code.

Tests used for this project (a big thanks to the makers!):
https://github.com/saarikoski-jules/gnl_unit_tests
https://github.com/charMstr/GNL_lover
