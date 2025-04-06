# CH01 A Tour of Computer Systems

#### Computer System

1. Computer System = hardware + systems software
2. All computer systems have similar hardware and software components
   1. perform similar functions

#### learning practical skills

1.  how to avoid strange numerical errors caused by the way that computers represent numbers.
2.  how to optimize C code by using clever tricks that exploit the designs of modern processors and memory systems
3.  how the compiler implements procedure calls
    1. how to use this knowledge to avoid the security holes from buffer overflow vulnerabilities
       plague network and Internet software
4.  how to recognize and avoid the nasty errors during linking that confound programmer
5.  how to write Unix shell, dynamic storage allocation package, Web server
6.  the promises and pitfalls of concurrency

#### Simple hello program

1. hello.c

   ```c
    #include <stdio.h>

    int main() {
        printf("hello, world\n");
        return 0;
    }
   ```

2. lifetime of the hello program
