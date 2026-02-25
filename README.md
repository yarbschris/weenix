# weenix
A fully functional Operating System Kernel, based on UNIX, built as part of the CMPS 6770 (Operating Systems) course at Tulane University.

The projects, in order of completion:

Procs - Threads, processes, and synchronization primitives.

Drivers - Device drivers for terminals, disks, and the memory devices /dev/zero and /dev/null.

VFS (Virtual File System) - A polymorphic interface between the operating system kernel and the various file systems (such as S5FS and device drivers).

S5FS (System V File System) - A file system implementation based on the original Unix file system.

VM (Virtual Memory) - Userspace address space management, running user-level code, servicing system calls, and basically everything else needed to combine all of the previous componenets into a fully functioning operating system. This includes virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls (in particular, the fork syscall).

NOTE: This is a placeholder repo with no code to respect Tulane University's Academic Honesty Code. If you are a potential employer and would like to look at my kernel, please contact me.

