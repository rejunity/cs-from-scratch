# cs-from-scratch
Zero dependency self contained - Hello world!

## Computer Architecture
* How to build CPU+I/O in VHDL lectures: https://opencores.org/ocsvn/cpu_lecture/cpu_lecture/trunk (https://opencores.org/websvn/listing/cpu_lecture)
* Books:
    * “Computer Architecture: A Quantitative Approach”, John L. Hennessy, and David A. Patterson.
    * “Computer Systems: A Programmer's Perspective”, Randal E. Bryant, and David R. O'Hallaron.
    * “Structured Computer Organization”, Andrew S. Tanenbaum, and Todd Austin.

## Compiler
* Overview:
    * https://softwareengineering.stackexchange.com/questions/165543/how-to-write-a-very-basic-compiler
    * https://wiki.osdev.org/Making_a_Compiler
* Books:
    * “Dragon Book” Compilers: Principles, Techniques, and Tools (2nd Edition) https://www.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811
    * “Modern Compiler Design” https://www.amazon.com/dp/0471976970/
    * “Compiler Construction: Principles and Practice”, Kenneth C. Louden, 1997: https://www.amazon.com/dp/0534939724/
    * “Let's Build a Compiler” online, Jack Crenshaw: https://compilers.iecc.com/crenshaw/
    * “Compiler Construction”, N. Wirth 1996: https://www.amazon.com/dp/0201403536/
    * http://gnuu.org/2009/09/18/writing-your-own-toy-compiler/
    * “Crafting Interpreters” online: https://craftinginterpreters.co
        * https://github.com/munificent/craftinginterpreter
* Parsers: https://en.wikipedia.org/wiki/Comparison_of_parser_generators
* Intros:
    * “Writing a simple Code Generator” Gabriel Sassone - https://jorenjoestar.github.io/post/writing_a_simple_code_generator/
    * “I wrote a programming language. Here’s how you can, too.” https://www.freecodecamp.org/news/the-programming-language-pipeline-91d3f449c919/
* Tips:
    * Learn COFF and PE formats(for windows), alternatively understand ELF format(for Linux)
    * Learn Flex and Bison first.

## OS
* Overview: https://wiki.osdev.org/Main_Page
    * Books: https://wiki.osdev.org/Books
* Books
    * MINIX: Operating Systems: Design and Implementation (Second Edition): Andrew S. Tanenbaum, Albert S. Woodhull: 9780136386773: Amazon.com: Books
        * Online: https://mcdtu.files.wordpress.com/2017/03/tanenbaum_woodhull_operating-systems-design-implementation-3rd-edition.pdf
        * https://www.amazon.com/Operating-Systems-Design-Implementation-3rd/dp/0131429388/
    * The Design of the UNIX Operating System: Maurice J. Bach: 9780132017992: Amazon.com: Books
    * Understanding the Linux Kernel, Third Edition: Daniel P. Bovet, Marco Cesati: 9780596005658: Amazon.com: Books
    * Modern Operating Systems, Andrew S. Tanenbaum
    * Operating System Concepts, Abraham Silberschatz, Peter B. Galvin, Greg Gagne. https://www.amazon.com/Operating-System-Concepts-Seventh-Edition/dp/0471694665/
    * Operating systems: Internals and Design Principles, William Stallings
* Course
    * Udemy — Build Your Own RealTime OS (RTOS) From Ground Up™ on ARM https://www.udemy.com/rtos-building-from-ground-up-on-arm-processors/
* Online Books & Tutorials
    * The little book about OS development, Erik Helin, Adam Renberg. https://littleosbook.github.io
    * Writing a Simple Operating System from Scratch, N.Blundell. http://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf
    * Step-by-Step tutorial “How to create an OS from scratch!” Implementation for “Writing a Simple Operating System from Scratch” by Blundell - https://github.com/cfenollosa/os-tutorial
    * Bran's kernel development tutorials - http://www.osdever.net/bkerndev/index.php
    * Roll your own toy UNIX-clone OS - http://www.jamesmolloy.co.uk/tutorial_html/index.html
    * http://www.osdever.net/tutorials/
* Source:
    * https://gitlab.com/ReturnInfinity/Pure64 - Pure64 is a software loader that sets the computer into a full 64-bit state with no legacy compatibility layers and also enables all available CPU Cores in the computer. The only requirement for building Pure64 is NASM and GCC.
    * https://github.com/klange/toaruos (ToaruOS is a hobbyist, educational, Unix-like operating system built entirely from scratch and capable of hosting Python 3 and GCC. It includes a kernel, bootloader, dynamic linker, C standard library, composited windowing system, package manager, and several utilities and applications.)
    * https://github.com/dimonomid/tneo TNeo is a compact and fast real-time kernel for embedded 32/16 bits microprocessors.
* Ideas:
    * Your computer is already a distributed system. Why isn’t your OS?  https://www.usenix.org/legacy/event/hotos09/tech/full_papers/baumann/baumann.pdf
    * I’m writing my own OS - https://gusc.lv/2012/11/im-writing-my-own-os/, https://gusc.lv/2012/11/im-writing-my-own-os-p2/
    * How I ended up writing a new real-time kernel https://dmitryfrank.com/articles/how_i_ended_up_writing_my_own_kernel

## Plan of attack
* OS first steps
    * Boot sequence - https://wiki.osdev.org/Boot_Sequence
    * Simple kernel for 32-bit x86 and boot loader.  https://wiki.osdev.org/Bare_bones
    * 64-bit x86 https://gitlab.com/ReturnInfinity/Pure64
    * https://wiki.osdev.org/Category:Babystep
