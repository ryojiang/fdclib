Original fdclib source zip file can be found at https://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/devel/libs/clib/

There is no much informaion for this original package. Neither OS environment nor Compiler information.
However, the original file format is Unix-like type (file end with LF). And from 'makefile' content may guest it is using Watcom C and Nasm assembler as develomment tools.

My target is to let this library could be created on 16 bit DOS environment.
Steps:
   1. Change all source files from Unix-like format (LF) to DOS format (CR/LF).
   2. Go to each directory to modify 'makefile' in order to be compiled or assembled by chosen C compiler and Assembler.
   3. When find any error message, try to find out root cause and soulution for each error.
