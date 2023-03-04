---
name: Anais Martinez
semester: Spring 23
course: cis106
---

# Week Report 3

## Summary of presentations

### Introduction to Linux

**What is an operating system?**
An operating system provides all fundamental software features of a computer. An OS enables you to use the computers hardware providing you the basic tools that make the computer useful. All of those key features relay on the OS's kernel. Other OS features are owed to additional programs that run atop the kernel.

**Aside from a kernel, what other parts make an operating system?**
An OS kernel is a software component that's responsible for managing low-level features of the computer, including managing the following system hardware, memory allocation, CPU time, and program to program interaction.

**What is a Linux distribution?**
A Linux distribution is any operating system that runs the Linux kernel- such as, Arch, CentOS, Debian, openSUSE, Red Hat, Slackware, and Ubuntu.

**What is Ubuntu?**
Ubuntu is a Linux Distribution, freely available with both community and professional support.

**Define the following terms: Open Source, Closed source, free software**
Open Source: the software may be distributed for free or for a fee. The source code is distributed with the software.
Closed Source: the software is not distributed with the source code. The user is restricted from modifying the code.
Free software: the software is distributed with the source code. The software can be free of charge or obtained by a fee.

**What are the 4 freedoms defined by the free software foundation?**
Freedom 0: use the software for any purpose
Freedom 1: examine the source code and modify it as you see fit
Freedom 2: redistribute the software
Freedom 3: redistribute your modified software

### The Basics of Virtualization

**What is virtualization?**
Virtualization is defined as creating virtual versions of something.

**List 3 benefits of virtualization**
Allows running multiple OSs on one machine without dual booting.
Allows applications to be tested before installing them on a host machine.
Reduces cost by decreasing the physical hardware that must be purchased for a network.

**What is a hypervisor?**
Software or hardware in charge of creating, managing, and running virtual machines.

**What is virtualbox?**
Virtualbox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use.

### Exploring Desktop Environments
**What is a desktop environment? (Provide 3 examples)**
A desktop environment is an implementation of the desktop metaphor made of of a bundle of programs running on top of a computer operating system, which shares a common GUI, sometimes described as a graphical shell. 3 examples of a desktop environment are GNOME, KDE, and MATE.
**List 4 common elements of desktop environments**
4 common elements of desktop environments include the desktop settings, display manager, file manager, and icons.
**What is Ubuntu's desktop environment?**
Ubuntu's desktop environment is GNOME 3.
**What are the official flavors of Ubuntu?**
The official flavors of Ubuntu are XCFE and Mate

### What is a Shell
**What is Bash?**
Necessary component to modern computing now available in almost every computer in the world.
**How do you access the Linux CLI?**
Through the Terminal Emulator or the Linux Console.
**What is a console terminal?**
This mode is called Linux Console because it emulates the old days of a hard-wired console terminal and is a direct interface to the Linux system.
**What is a terminal emulator?**
A terminal emulator is a program that allows you to access the Linux CLI.
**Provide 3 examples of Linux commands**
date - displays the current time and date
cal - displays a calendar of the current months
clear - clears the screen

### Managing Software

**Which command is used for updating ubuntu**
sudo apt upgrade; sudo apt upgrade -y
**Which command is used for installing software. Provide an example.**
sudo apt install package name
Ex: sudo apt install firefox flameshot caffeine -y
**Which command is used for removing software. Provide an example.**
sudo apt remove package name
Ex: sudo apt remove firefox flameshot caffeine -y
**Which command is used for searching for software. Provide an example.**
apt search
Ex: apt search -n firefox
**Definition of the following terms:**

    Package - archives that contain binaries of software, configuration files, and information about dependencies.
    Library - reuseable code that can be used by more than one function or program.
    Repository  - a large collection of software available for download.
