# 202235132_ChaMinChan_lecture_note_4.md
-------------------------------------------
### Shell command
**Git Bash** = starter.  
- **pwd**  
: Shows the current path
- **cd**  
: Change directory
- **ls**  
: List files and directories  
> **ls /bin** => List the files in the " /bin "directory (or any other directory we care to specify)  
> **ls-l**   => List the files in the working directory in long format  
> **ls-l /etc /bin** => List the files in the working directory and the /etc directory in long format  
> **ls-la ..** => List all files(even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format  


--------------------------------------------
### Manipulation
- **cp**  
: Copy files and directories
> **cp file1 file2** => Copies the contents of file1 into file2. If file2 does not exist,it is **created**;otherwise,file2 is silently overwritten with the contents of file1.
> **cp-i file1 file2** => Like above however,since the "-i"(interactive) option is specified, if file2 exists, the user is promted before it is overwritten with the contents of file1.
> **cp file1 dir1** => Copy the contents of file1(into a file named file1) inside of directory dir1.
> **cp-R dir1 dir2** => Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory named dir1 within directory dir2.  

- **move**  
: Move files and directories or rename them
>
