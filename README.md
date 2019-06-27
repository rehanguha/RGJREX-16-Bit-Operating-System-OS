# RGJREX-16-Bit-Operating-System-OS
RGJREX O.S. is a 16-bit Operating System which boots from a floppy disk. But using emulators (VMware or QEMU) and disk imaging software’s it can be loaded to CD-R as well as pen drives.


**RGJREX O.S.**

# Contents



**Chapter 1**

1.1 Introduction_……………………………………………………………………………………_1

**Chapter 2**

2.1 Scope of the project……………………………………………………………………….1

2.2 User wise Functionalities………………………………………………………………..2

**Chapter 3**

3.1 Design diagrams……………………………………………………………………………..2



**Chapter 4**

4.1 Software requirement………………………………………………………….…….....3

4.2 Hardware Requirement………………………………………………………………….4



**Chapter 5**

5.1 Results and discussion_……………………………………………………………………_4

5.2 Future Scope….………………………………………………………………………………6

**Chapter 6**

6.1 Conclusions ……………………………………………………………………………….....6

# Chapter 1

#

**1.1 Introduction**

RGJREX O.S. is a 16-bit Operating System which boots from a floppy disk. But using emulators (VMware or QEMU) and disk imaging software&#39;s it can be loaded to CD-R as well as pen drives.

RGJREX O.S. supports FAT12 floppy drives here we have used IBM floppy format 1.44 MB, 3.5&quot; diskette.

IBM floppy gives us right to set few parameters like Disk Format, Disk Label, Disk Type, etc. using Assembly Level Coding.

#

#

# Chapter 2

**2.1 Scope of the project**

Objective and motivation of the project RGJREX O.S. are as follows:-

- Gathering knowledge about Assembly Level coding X86
- How does memory management works at low level
- How to use BIOS calls in the assembly level coding
- Understanding the basic functionality of the O.S.



**2.2 User wise Functionalities**

RGJREX O.S. is a single user single processing 16-bit operating system which opens with root access. And it focuses on executing Assembly Files (\*.asm) after converting them into Binary Files (\*.bin) using NASM or MASM. And it also executes BASIC files (\*.bas) with the help of BASIC Command Interpreter.

#

# Chapter 3

**3.1 Design diagrams**

- Memory Map

**0 - 24575 (hex: 0h - 5FFFh)**
24K kernel executable code

**24576 - 32767 (hex: 6000h - 7FFFh)**
8K kernel disk operation buffer 

**32768 - 65535 (hex: 8000h - FFFFh**
32K space for external programs

Fig. 1 – Memory Distribution

RGJREX O.S.&#39;s programs are loaded in a memory of 32KB point segment with maximum size of 32KB (Fig 1).

# Chapter 4

**4.1 Software requirement**

- End Users
  - Emulators

- --VMware Player/Workstation
- --QEMU
- --Virtual Box

- Operating System Developers
  - NASM/MASM
  - Text Editor
  - Imdisk
  - Partcopy or File Copier softwares

**4.2 Hardware Requirement**

- Real PC&#39;s

Minimum Requirement

- --Hard Disk- 8MB
- --RAM- 4MB
      -    PC Speaker



- Emulator

Minimum Requirement

- --Hard Disk- 1GB
- --RAM- 16 MB

#

# Chapter 5

**5.1 Results and discussion**

Functionalities completed so far

- Basic command line interface with commands like
  - Ver (version)
  - Time (current CPU clock time) from BIOS
  - Date (current CPU date) from BIOS
  - Clr (clear screen)
  - Cat (display contents of the file)
  -
- An option screen which displays the loaded program in the operating system including the KERNEL file.
- Dedicated BASIC (Beginner&#39;s All-purpose Symbolic Instruction Code) Interpreter with 60 instruction codes.



Screenshots:-

- Home Screen

- Menu

- Command Line

**5.2 Future Scope**

Functionalities which we want to complete for this minor project.

- The whole operating system will be structured using folders
- S. will have all kind of drivers (mouse, graphics, etc.)
- Convert this O.S. to 64-bit from 16-bit (current) with GUI

#

# Chapter 6

#

**6.1 Conclusions**

This is a 16 bit Operating System with a dedicated BASIC (Beginner&#39;s All-purpose Symbolic Instruction Code) Interpreter which helps to execute \*.bas file. RGJREX is capable to execute Binary as well as BASIC files.




## Reference 

MikeOS operating system project (Version 4.5)
