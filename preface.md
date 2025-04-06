## Preface

#### Book Overview

Chapter 1: A Tour of Computer Systems

Chapter 2: Representing and Manipulating Information

Chapter 3: Machine-Level Representation of Programs

Chapter 4: Processor Architecture

- combinational and sequential logic
- x86-64 instruction set
- pipelining

Chapter 5: Optimizing Program Performance

- improving code performance

Chapter 6: The Memory Hierarchy

- RAM, ROM memories
- geometry and organization of magnetic-disk, solid state drives
- memory mountain
- improve the performance of application programs by improving temporal and spatial locality

Chapter 7: Linking

Chapter 8: Exceptional Control Flow

- low-level hardware exceptions and interrupts
- context switches between concurrent processes
- abrupt changes in control flow caused by the receipt of Linux signals
- the nonlocal jumps in C that break the stack discipline

Chapter 9: Virtual Memory

Chapter 10: System-Level I/O

- basic concepts of Unix I/O (files, descriptors)
- buffered I/O packages
- C standard I/O library and its relationship to Linux I/O

Chapter 11: Network Programming

- writing a simple web server
- client - server model
- writing Internet clients and servers using the sockets interface
- HTTP Web server

Chapter 12: Concurrent Programming

- processes, I/O multiplexing, threads : writing concurrent programs
- covering basic principles of synchronization using P, V semaphore operations
- thread level programming

#### New to This Edition

a mix of IA32 and x86-64 to one based exclusively on x86-64

#### Origins of the Book

1. Introduction to Computer Systems (ICS)
2. teaching about systems from the point of view of the programmer
3. cover a topic only if it affected the performance, correctness, or utility of user-level C programs
   1. topics such as hardware adder and bus designs were out.
   2. topics such as machine language were in
   3. not focusing on how to write assembly language by hand
   4. focus on how a C compiler translates C constructs into machine code
      - including pointers, loops, procedure calls, switch statements.

#### For Instructors: Courses Based on the Book

ORG(컴퓨터 구조), ICS, SP(시스템 프로그래밍)

#### For Instructors: Classroom-Tested Laboratory Exercises

Data Lab, Binary Bomb Lab, Buffer Overflow Lab, Architecture Lab, Performance Lab
Cache Lab, Shell Lab, Malloc Lab, Proxy Lab

#### Acknowledgments
