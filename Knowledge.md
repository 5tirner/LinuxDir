`/bin`: It's dedicated areas for storing executable files, commonly known as binaries.\
        These binaries are required for the execution of different commands and programs on a Linux system.\
`/home`: It's the primary entry point of the user when they are login into the Linux environment.\
        It's responsible to store files, folders, data, and software on */home* directory with the respective individual user profile.\
`/etc` : It's contains system configuration information, Several files and subdirectories have been added, removed, or changed.\
`/run` : We Can Cosider it as a temporary filesystem (tmpfs), which stores volatile runtime data.\
`/usr` : It's contains read-only commands, libraries, and data, Except for the contents of the */usr/share*  directory, the files and directories in the */usr*, file system can be shared by all machines of the same hardware architecture.\
`var` : contains files that are constantly changing in size such as log and spool files.\
`/lib32` : It's for software using the x86 instruction set.\
`/libx32` : It's for software using the x86-64 instruction set but with 32-bit pointer size same as the x86 instruction set uses.\
`/lib64` : It's for software using the x86-64 instruction set.\
`/lib` : contains those shared library images needed to boot the system and run the commands in the root filesystem.\
`/sys` : It provides a filesystem-like view of information and configuration settings that the kernel provides.\
`/dev` : Contains the special device files.