# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](http://cli.learncodethehardway.org/book/). This is a great,
quick tutorial. Each "chapter" focuses on a command. Type the commands
you see in the _Do This_ section, and read the _You Learned This_
section. Move on to the next chapter. You should be able to go through
these in a couple of hours.


---

Make a cheat sheet for yourself: a list of commands and what they do, focused on things that are new, interesting, or otherwise worth remembering.

Most of the command line is new to me, but I think wildcard or the asterik (*) is a very usefull things to remember. 

---


---

What does `ls` do? What do `ls -a`, `ls -l`, and `ls -lh` do? What combinations of those flags are meaningful?

ls stands for list, which list the items on the directory. ls -a lists all files and folder which I think act similarly with just ls. ls -l lists the files and folder with detial information and we can specify the file we want to get the information. ls -lh acts similarly with ls -l, but its more human readable in which some of the information is simplified such as the size is written as kilobyte than just unit number. 

---


---

What does `xargs` do? Give an example of how to use it.

I think xargs splits a list into sublist or split a group into subgroup. I mean I can write 

$echo {1..9}
1 2 3 4 5 6 7 8 9

$echo {1..9} | xargs -n 3
1 2 3
4 5 6
7 8 9

Where xargs splits the long line 1..9 into 3 shorter items. 

---
