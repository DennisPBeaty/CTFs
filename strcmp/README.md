Within Terminal

1. objdump -d 0-stripped
2. gdb ./0-stripped

Within GDB 

1. break *0x804916a THIS IS THE LOCATION OF THE STRCMP
2. p (char *)$eax