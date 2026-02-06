# Customised Virtual File System (CVFS)

Project Overview:-
The Customised Virtual File System (CVFS) is a Linux-inspired virtual file system implemented in C language to understand  Operating System internals.  
This project simulates core file system components such as **Boot Block, Super Block, Inodes, File Tables, and User File Descriptor Table (UFDT)** and provides a command-line shell for file operations.

 Objectives:-
- To understand internal working of file systems
- To implement OS-level data structures manually
- To simulate system calls like create, read, write, delete
- To gain hands-on experience with low-level programming



 Core Components Implemented:-
- Boot Block – Stores booting information
- Super Block – Maintains total and free inodes
- Inode List (DILB) – Linked list of inodes
- File Table – Maintains read/write offsets and mode
- UFDT (User File Descriptor Table) – Tracks opened files
- Custom Shell – Accepts user commands



 Features:-
- Create regular files with permissions
- Read and write file data
- Delete (unlink) files
- List all files (ls)
- Display file metadata
- Manual pages (man command)
- Permission handling (Read / Write / Read + Write)
- Error handling with custom error codes



 Technologies Used:-
  Programming Language:- C  
  
 Concepts:-
  - Operating System Internals  
  - Virtual File System  
  - Inodes & File Descriptors  
  - Linked List  
  - Dynamic Memory Allocation  
