# MIPS-disassembler
A rudimentary MIPS disassembler.

This MIPS program takes in two arrays of MIPS machine code, one for the data segment and another for the text segment,
then outputs it into a runnable (if a bit ugly) MIPS assembly language program. All I-type, R-type and J-type instructions
have been tested and should work correctly. F-type instructions have not been imeplemented.
By default, the included inputs result in an output program that lists the first several fibonacci numbers.
