# CSE-314-Operating-System-XV6

Prerequisite to running xv6: https://pdos.csail.mit.edu/6.828/2022/tools.html

Code-base of xv6: https://github.com/mit-pdos/xv6-riscv

You need to apply the patch files to the original xv6 codebase as an extension to the base OS.

`git apply /path/to/some-changes.patch`


### Contents
The main aim for this is to practise kernel level implementations of a simple OS that is xv6. 

**1. Shell Script:** I tried to check my basic understanding of shell scripts here

**2. Pthread Synchronization:** One of the most important aspect of OS is thread synchronization. Here by implementing simple locking mechanism like master-worker, reader-writer this concept was understood. Also a example of zemaphore is implemented too. 

**3. xv6 System Call:** In this part I added a new system calls to xv6, which helped m understand how they work and exposed me to some of the internals of the xv6 kernel

**4. xv6 Lottery Ticket Scheduling:** In this part I implemented a new scheduler for the xv6 operating system. This scheduler implemented a lottery scheduling algorithm. The basic idea is quite simple. Each process was assigned a fixed number of tickets (an integer number). A process was probabilistically assigned a time slice based on its number of tickets.

**5. xv6 Advanced Memory Management:** xv6 implements a very basic memory management system. In this part, I enhanceedit to a great extent; namely, by adding COW (Copy on Write) and Paging.
