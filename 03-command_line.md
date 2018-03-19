# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

>
* `pwd` : Prints the current working directory
* `mkdir` : Makes a new directory
* `rmdir` : Removes a directory
* `touch` : Resets a file's timestamp, or creates a file if it does not exist
* `rm` : Removes a file
* `mv` : Moves or can be used to rename a file
* `ls` : List directory, option --all (-a) to list all files
* `cp` : Copies a file from one directory to another
* `less` : Reads a text file
* `echo` : Prints the arguments of a function or command
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> 
* `ls` : Lists visible files in the current working directory
* `ls -a` : Lists --all items in current owkring directory, including hidden ones
* `ls -l` : Lists items in long format (more details)
* `ls -lh` : In addition to long formatting, makes the text "human-readable", which just means it shorthands suffixes
* `ls -lah` : In addition to being long and human-readable, it will also list hidden files
* `ls -t` : Sorts items by their modification time
* `ls -Glp` : Lists items without the group name, in long format, and appends a forward slash to directories
---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> 
* `ls --color` : Makes things pretty!
* `ls -d` : Lists directories 
* `ls -r` : Reverses the sorting order
* `ls -R` : Recursively lists directory contents
* `ls -s` : Returns the file sizes in blocks

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> `xargs` simply allows a user to have multiple calls of a specified command.  
For example, if you wanted to create multiple files with the touch command you could use `$ xargs touch` (as opposed to typing ` $ touch` multiple times), which will create multiple (non-duplicating) files per line entered after the command is called. To submit the command, CTRL+D is used.

 

