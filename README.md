Working on a compiler. The compiler is coded in C and runs on a Linux system. It defines a C-like language that started out as B-like but became more C-like as I went along because I am coding the compiler in C.
The compiler consists of a lexer, a parser, and an assembler. The lexer emits a tokens.txt file which is the input for the parser. The parser emits an assembly language file (output.asm). I am using TASM as an assembler. This is the "Telemark" table assembler. It is shareware. The lexer and parser are my own.
The assembly language and binary machine code output are for my 8-bit processor (see http://cpuville.com/Kits/8-bit-processor-kit-home.html). 
