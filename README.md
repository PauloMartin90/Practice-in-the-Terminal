## The Command Line 
> What is it, how does it work and how do I get to one. 

- The command line is the a text base inteface to the system.  You enter commands by typing them on the keyboard and recieving feedback from the text.
**Applications -> System or Applications -> Utilities.**

## Basic Navigation
> An introduction to the Linux directory system and how to get around it.

- To know what directory you can send text to the system by typing `pwd`

- To see the list of scripts you can use the `ls [options] [location]` command


## More About Files
> Find out some interesting characteristics of files and directories in a Linux environment.

- Files in linux must be case sensitive compared to other operating systems like windows that is case insensitive.

- Spaces in file and directory names are perfectly valid but we need to be a little careful with them.

## Manual Pages
> Learn how to make the most of the Linux commands you are learning.

- The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept.

```
man <command to look up>
```
```
user@bash: man ls
Name
    ls - list directory contents
 
Synopsis
    ls [option] ... [file] ...
 
Description
    List information about the FILEs (the current directory by default). Sort entries alphabetically if none of -cftuvSUX nor --sort is specified.
 
    Mandatory arguments to long options are mandatory for short options too.
 
    -a, --all
        do not ignore entries starting with .
 
    -A, --almost-all
        do not list implied . and ..
 
...

```

## File Manipulation
> How to make, remove, rename, copy and move files and directories.

Linux organises it's file system in a hierarchical way. It's important that we create a directory structure that will help us organise that data in a manageable way.

```
mkdir [options] <Directory>
```



## Cheat Sheet 
> A quick reference for the main points covered in this tutorial.


```
mkdir
Make Directory - ie. Create a directory.
rmdir
Remove Directory - ie. Delete a directory.
touch
Create a blank file.
cp
Copy - ie. Copy a file or directory.
mv
Move - ie. Move a file or directory (can also be used to rename).
rm
Remove - ie. Delete a file.

man <command>
Look up the manual page for a particular command.
man -k <search term>
Do a keyword search for all manual pages containing the given search term.
/<term>
Within a manual page, perform a search for 'term'
n
After performing a search within a manual page, select the next found item.

file
obtain information about what type of file a file or directory is.
ls -a
List the contents of a directory, including hidden files.

pwd
Print Working Directory - ie. Where are we currently.
ls
List the contents of a directory.
cd
Change Directories - ie. move to another directory.
```