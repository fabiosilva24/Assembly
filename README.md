NOTES:




-------------------------\
-                       -\
-      CPU              - \       inside of the cpu are a bunch of variables named register they are just super fast memory that your computer uses to do operations with
-------------------------\

The width of the registers is defined by the instruction set

today we're doing a 64-bit assembly so every register is 64 bits wide they have different names like RDI and RSI and maybe R8 for example
all of this are 64 bits registers


move rdi, 8     - move the number 8 constant value in rdi



syscall sys_read sys_write

as asem.s -o asem.o
gcc -o asem asem.o -nostdlib -static
