# Binary Exploitation Roadmap
## Inspired by Ret2systems Software Exploitation Course

![Demo!](Binary-Exploitation-Roadmap-v2.png)

1. **C/C++ Programming**
    
    Learn the fundamentals of the C and C++ programming languages, including variables, data types, memory management, and functions.

2. **Linux Environment**
    
    Learn the basics of the Linux operating system, specifically the command-line interface.

3. **Assembly Language**
    
    Learn the basics of assembly language, including the structure of assembly code, the syntax of assembly instructions, and the relationship between assembly code and machine code.

4. **Memory Layout/Stack Concepts**
    
    Learn about the memory layout of a program, the use of the stack to manage function calls, and the calling conventions used to pass parameters and return values between functions.

5. **Reverse Engineering**
    
    Learn how to analyze compiled code, particularly binary files, using disassemblers and decompilers to understand its functionality and identify potential vulnerabilities.

6. **Stack Smashing**
    
    Learn about buffer overflows and how they can be used to overwrite the return address on the stack, allowing an attacker to execute arbitrary code.

7. **Shellcode Crafting**
    
    Learn to write shellcode that exploits vulnerabilities and executes arbitrary code, including techniques like crafting payloads to take advantage of specific system calls like syscall execve.

8. **Stack Canaries**
    
    Learn about stack canaries, a security mechanism that mainly protects the return address from being overwritten during a buffer overflow attack.

9. **Return Oriented Programming**
    
    Learn about ROP, a technique used to bypass data execution prevention (DEP) by repurposing existing code snippets from a binary executable to execute arbitrary code.

10. **Address Space Layout Randomization**
    
    Learn about Address Space Layout Randomization (ASLR), a security mechanism that randomizes the memory layout of a process to prevent attackers from exploiting memory vulnerabilities.

11. **Heap Exploitation**
    
    Learn about heap exploitation, a challenging technique used to exploit vulnerabilities in the dynamically allocated memory area (managed by the malloc engine) of a program.

12. **Use-after-free Vulnerabilities**
    
    Learn about use-after-free vulnerabilities, a very common type of memory corruption vulnerability that occurs when a program accesses memory after it has been freed.

13. **Race Conditions**
    
    Learn about race condition vulnerabilities, an advanced technique used to exploit vulnerabilities that occur when multiple processes or threads access shared resources simultaneously.

14. **Kernel Exploitation**
    
    Learn about kernel exploitation, a highly advanced and challenging technique used to exploit vulnerabilities in the operating system kernel, which has the highest level of privilege in a system.
