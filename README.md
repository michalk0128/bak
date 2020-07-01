# bak
simple backup function for files and directories (Linux)

How to:
- save in .bashrc and source the file,
- syntax

bak filename
- works also recirsively with directories

bak dirname
- current date and unique number (here, until 99) are added to the filename, it can be modified to date & time instead,
- works also with wildcards (so, for example, bak * or bak filename*), backups of backups are not created, new number is found,
- non-existing files are ignored,
- bak filename displayed upon successful backup,
- if used with git, you could modify .gitignore,
- backup can save your life ;)
