# BASH Commands
## `pwd` :show the working directory
---
## `ls` :list files in current directory
* `ls -a` :lists all files (including hidden files)
* `ls ..` :list all files one directory level up
---
## `mkdir` :make new directory. 
* can chain directory names to create more than one at a time in an existing location/directory.
    * ex: `mkdir directory directory`
* `mkdir -p` :creates entire path, including parent directories
  * ex: `mkdir -p directory-1/subdirectory-1/subdirectory-2`
---
## `cd` :change directory
* `cd ..` :go up one directory level
* `cd ~` :go to home directory
* `cd -` :switch to last directory
---
## `touch` :create a new file
* can create multiple files at once
    * ex: `touch filename filename`
---
## `rm` :remove file
* `rm -rf` :remove directory
---
## `mv` :move file
* `mv filename newfilename` :rename a file
* `mv filename ..` :move file one directory level up
* `mv filename .` :move file to current directory
* can move more than one file at a time.
---
## `man` :gives a manual for a command
---
## `code` :opens visual studio code from terminal
* can open a file or directory in vs code
  * ex: `code .` `code bash.md`
---
## `cp` :copy a file
* `cp -r` :copy a directory
---
## `command -v` :verify a command is available
---
## `git config --global user.name "username"` : 
## `git config --global user.email "emailaddress"` :
## `git init` :
## `git clone` :copies repository into local directory
## `git add file or directory` :
## `git commit -m "message"` :
## `git push` :