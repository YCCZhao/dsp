# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path: pwd   
* creating a directory: mkdir <dir>   
* deleting a directory: rm -r <dir>   
* creating a file using `touch` command: touch <file>    
* deleting a file: rm <file>   
* renaming a file: mv <old name> <new name>
* listing hidden files: ls -a   
* copying a file from one directory to another: cp <one director> <another>   
* find file by name: find . -name <"file name"> -print   
* find file by content: grep -ilrw <"something"> <director to search> 

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > see above

---

### Q2.  List Files in Unix   

What do the following commands do:  
> > `ls`  list files and directories under current folder   
> > `ls -a`  do not ignore entries starting with .   
> > `ls -l`  use a long listing format   
> > `ls -lh`  use a long listing format with human readable sizes   
> > `ls -lah`  list all files and directories including ones with . in a long listing format with human readable format   
> > `ls -t`  sort by modification time, newest first   
> > `ls -Glp`  in long listing, without group names and append "/" to directories.   


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -lg; ls -S; ls -X; ls -I; ls -d.


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > separate a list of input into individual input to feed into a command.
> > example: grep -irlw "udot" * | xargs /bin/rm -f


 

