# Week 14 Chapter 15 Compile documentation
### By Luschool

This is my documentation for the assignment to work with the c compiler.
I just did the basic route of following the chapter 15 commands on my 
local machine. Next week I will configure and compile the iPXE source
as part of the assignment. 


## Summary -  

Start by making a new file with - 

`nano hello.c`

Once in nano I added the following lines -

```
#include <stdio.h>

main() {
	printf("Hello, World.\n");
	printf("This is a test program that will be compiled and ran.\n");
}
```

Once its saved you just run the `cc` command to compile it into an executable.

`cc hello.c`

By default the output of this command will be `a.out` you can know execute this file
such as ./a.out in a terminal and it will output the print commands. 

You can also change the output file name with the `-o` flag. For example - 

`cc -o hello hello.c`

now we have a hello executable file in the same directory and it can be
ran the same way as above. 

Compiling programs from source has a lot of benefits. 
Here are a few -

* Configure options to your prefernce and needs.
* Access to additional options and features.
* More secure.(Allows you to avoid possible viruses bound to executables. You can also verify the md5 checksum of the files.)

Plus its a fun experience to build something from scratch and compile it into an executable program. 


