
# Reverse Engineering / Exploit Development Training 0x00 ; Prolog


## What is Reverse Engineering?

In the world of CyberSecurity and Software Engineering, Reverse Engineering is the practice of analyzing execution patterns of executable files in order to copy a program back into it's original form, thereby gaining an understanding of how said program is structured. 

The present participle verb form of Reverse Engineering is called **Reversing**.

## Why Practice Reversing?

A few examples of the use cases for reverse engineering would be:
 - **Finding exploits and vulnerabilities within a program. Exploit Development.**
- Retrieval of lost source code for a project.
- Gain a greater understaning of how compilers translate human readable code into machine-readable code.
- Gain a greater understanding of Instruction-Set Architectures for CPU's.
- Gain a greater understanding of your own compiled code when debugging.

## What is Exploit Development?

Exploit Development is the practice of utilizing core concepts that tie closely with Reverse Engineering to find vulnerabilities within a program. 

These core concepts are Behavior Analysis and Behavior Modification. 

Sometimes a particularly challenging program can require the "full picture", and thus a full Reversing of the program is necessary to find potential attack vectors that can be used.

Exploit Development does not always require Reversing, however a full understanding of Reverse Engineering makes Exploit Development **much** easier.
## Why Develop Exploits?

Exploit Developers utilize the core concepts of Reverse Engineering to find exploits in programs in order to better protect those programs. 

The skill is essential for the security of programs, and covers the occupations of Malware Analysis, Vulnerability Researchers, and  is the basis of the SANS SSEC710 & SEC760 certifications for penetration testing.

It is a multidisciplinary skill involving a combination of Computer Science and Cybersecurity fundamentals. 

If you enjoy puzzles, and making things do what they are not supposed to do, you will enjoy exploit development.

Also, https://www.youtube.com/watch?v=ON-7v4qnHP8

## How does one begin Reversing, and by extension, developing Exploits?

For us, a simple understanding of Programming Concepts & Python is enough. 

We will start off with simple C, and x86 Assembly. We will then build from there into more advanced concepts.

***If you do not know C, I would recommend looking up "Derek Banas" on YouTube, he has a wonderful C Programming Language tutorial  with included source code & comments that will get you where you need to be, the link will follow for those of you who download these notes.*** 
https://www.youtube.com/watch?v=nXvy5900m3M  

### The Resources we will be using are as follows:

**Book**: ***Reverse Engineering for Beginners, by Dennis Yurichev.***
It can be found as a pdf at https://beginners.re

***The reason we are using this book is not only because it is the best resource for learning Reverse Engineering, but it is additionally licensed under the Creative Commons license (CC BY-SA 4.0). We are legally allowed to print this book, and I am legally allowed to use it for teaching.*** 

**Exercises**: We will be using the books' exercises located here: https://challenges.re/

- Do keep in mind these challenges are not numbered in order of difficulty, but in order of when they were written. For example, our first challenges will be #48 and #49

**In addition,** we will be using custom written binaries and labs, or sometimes we will borrow from individuals or sites such as :

- LiveOverflow's  [Binary Exploitation / Memory Corruption] playlist: https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN

- Andrew Griffith's Exploit Education Virtual Machines: http://exploit.education/ 

- Pwn, Crackme, and Reversing Challenges from a handful of sites:
	-  http://pwnable.xyz/
	-  https://crackmes.one/
	-  https://www.hackthebox.eu/




# Schedule


We will be using laptops provided by Pensacola State College with a Kali Linux image downloaded on them.

On this Kali Linux image we will have GDB with GEF installed, GCC, a few IDE's, Ghidra, and Radare2 with the Cutter GUI Frontend.

- Next Week: Pages 1-29 of book, **ONLY X86 EXAMPLES NEED TO BE READ**, exercise #48, #49, a lab example. 

