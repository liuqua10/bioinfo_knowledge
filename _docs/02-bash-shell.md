---
title: "What is Shell and Bash"
permalink: /docs/bash-shell/
layout: archive
sidebar:
  nav: "docs"
---
## What is Shell and Bash
Simply put, the shell is a program that takes commands from the keyboard and gives them to the operating system to perform. In the old days, it was the only user interface available on a Unix-like system such as Linux. Nowadays, we have __graphical user interfaces (GUIs)__ in addition to __command line interfaces (CLIs)__ such as the shell.

On most Linux systems a program called [bash](http://linuxcommand.org/lc3_man_pages/bash1.html) (which stands for Bourne Again SHell, an enhanced version of the original Unix shell program, sh, written by Steve Bourne) acts as the shell program. Besides **bash**, there are other shell programs that can be installed in a Linux system. These include: **ksh**, **tcsh** and **zsh**.


## Basic Shell Command

### Navigation
**Find Current Working Directory**
```
pwd
```
Since a command line interface cannot provide graphic pictures of the file system structure, it must have a different way of representing it. Think of the file system tree as a maze, and you are standing in it. At any given moment, you are located in a single directory. Inside that directory, you can see its files and the pathway to its parent directory and the pathways to the subdirectories of the directory in which you are standing.

The directory you are standing in is called the working directory. To find the name of the working directory, use the **`pwd`** command.


**Change directory**
```
cd
```
To change your working directory (where you are standing in the maze) you use the cd command. To do this, type **`cd`** followed by the pathname of the desired working directory. A pathname is the route you take along the branches of the tree to get to the directory you want. Pathnames can be specified in one of two different ways; absolute pathnames or relative pathnames. Let's look with absolute pathnames first.

An absolute pathname begins with the root directory and follows the tree branch by branch until the path to the desired directory or file is completed. For example, there is a directory on your system in which most programs are installed. The pathname of the directory is /usr/bin. This means from the root directory (represented by the leading slash in the pathname) there is a directory called "usr" which contains a directory called "bin".

**List files**
```
ls
```
When you first log on to a Linux system, the working directory is set to your home directory. This is where you put your files. On most systems, your home directory will be called /home/your_user_name, but it can be anything according to the whims of the system administrator.

To list the files in the working directory, use the **`ls`** command.


**Important facts about file names:**
1. File names that begin with a period character are hidden. This only means that ls will not list them unless you say ls -a.
2. The file names "File1" and "file1" refer to different files. You may name files any way you like. However, while Linux itself does not care about file extensions, many application programs do.
3. Though Linux supports long file names which may contain embedded spaces and punctuation characters, limit the punctuation characters to period, dash, and underscore. Most importantly, **do not embed spaces** in file names. If you want to represent spaces between words in a file name, use underscore characters. You will thank yourself later.
{: .notice--warning}
