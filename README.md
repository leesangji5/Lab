# Kernel, Shell

__kernel__: the kernel is the core component that manages hardware resources and facilitates communication between hardware and software.

__shell__:  the shell is a user interface that allows users to interact with the kernel, CLI or GUI

## shell commands

__pwd__: shows the current path in a hierarchical directory

__cd__: chage directory

__ls__: list files and directries

## arguments
  * / root
  * . current directory
  * .. upper-level directory
  * ~ home
  * /directory: absolute path
  * ./directory: relative path
  * ../directory: relative path

  * -l show detailed information
  * -lh same ad above, but size in unit
  * -la list all files

__cp__: copy files and directories
 * __cp file1 file2__: file2 overwritten with the contents of file1
 * __cp -i file1 dir1__: copy the contents of file1 to directory dir1 

__mv__: move files and directories or rename
 * __mv file1 file2__: if file2 does not exist, then file1 is rename file2, if exist, file2 repalced the contents of file1
 * __mv file1 file2 dir1__: file1 and file2 move directory dir1
 * __mv dir1 dir2__: dir1 dpes mpt exost. then renamed dir2, if exist dir1 is moved directory dir2


__rm__: remove files and directories
 * __rm file1 file2__: delete file1 and file2

__mkdir__: make a new directory

__help__: show commands

__exit__: exit terminal
