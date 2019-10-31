---
title: "What is Unix/Linux"
permalink: /docs/unix/
layout: archive
sidebar:
  nav: "docs"
---

##  Unix's beginnings
The history of Unix begins at AT&T Bell Labs in the late 1960s with a small team of programmers looking to write a multi-tasking, multi-user operating system for the PDP-7. Two of the most notable members of this team at the Bell Labs research facility were Ken Thompson and Dennis Ritchie. While many of Unix's concepts were derivative of its predecessor, the Unix team's decision early in the 1970s to rewrite this small operating system in the C language is what separated Unix from all others. At the time, operating systems were rarely, if ever, portable. Instead, by nature of their design and low-level source language, operating systems were tightly linked to the hardware platform for which they had been authored. By refactoring Unix on the C programming language, Unix could now be ported to many hardware architectures.


## Enter Linux

What we call the Linux operating system today is really the combination of two efforts from the early 1990s. Richard Stallman was looking to create a truly free and open source alternative to the proprietary Unix system. He was working on the utilities and programs under the name GNU, a recursive acronym meaning "GNU's not Unix!" Although there was a kernel project underway, it turned out to be difficult going, and without a kernel, the free and open source operating system dream could not be realized. It was Linus Torvald's work—producing a working and viable kernel that he called Linux—that brought the complete operating system to life. Given that Linus was using several GNU tools (e.g., the GNU Compiler Collection, or GCC), the marriage of the GNU tools and the Linux kernel was a perfect match.

Linux distributions came to life with the components of GNU, the Linux kernel, MIT's X-Windows GUI, and other BSD components that could be used under the open source BSD license. The early popularity of distributions like Slackware and then Red Hat gave the "common PC user" of the 1990s access to the Linux operating system and, with it, many of the proprietary Unix system capabilities and utilities they used in their work or academic lives.

## Comparison of Linux and Unix


|| Linux            | Unix              |
|| --------            | ---------              |
| Cost | Linux can be freely distributed, downloaded freely, distributed through magazines, Books etc. There are priced versions for Linux also, but they are normally cheaper than Windows.    | Different flavors of Unix have different cost structures according to vendors   |
| Development and Distribution| Linux is developed by Open Source development i.e. through sharing and collaboration of code and features through forums etc and it is distributed by various vendors.     | Unix systems are divided into various other flavors, mostly developed by AT&T as well as various commercial vendors and non-profit organizations.         |
| Manufacturer | Linux kernel is developed by the community. Linus Torvalds oversees things.   | Three biggest distributions are Solaris (Oracle), AIX (IBM) & HP-UX Hewlett Packard. And Apple Makes OSX, an unix based os. |
| User | Everyone. From home users to developers and computer enthusiasts alike. | Unix operating systems were developed mainly for mainframes, servers and workstations except OSX, Which is designed for everyone. The Unix environment and the client-server program model were essential elements in the development of the Internet |
| Usage | Linux can be installed on a wide variety of computer hardware, ranging from mobile phones, tablet computers and video game consoles, to mainframes and supercomputers. | The UNIX operating system is used in internet servers, workstations & PCs. Backbone of the majority of finance infastructure and many 24x365 high availability solutions. |
| File system support | Ext2, Ext3, Ext4, Jfs, ReiserFS, Xfs, Btrfs, FAT, FAT32, NTFS | jfs, gpfs, hfs, hfs+, ufs, xfs, zfs format |
| Text mode interface | BASH (Bourne Again SHell) is the Linux default shell. It can support multiple command interpreters. | Originally the Bourne Shell. Now it's compatible with many others including BASH, Korn & C. |
| What is it? | Linux is an example of Open Source software development and Free Operating System (OS). | Unix is an operating system that is very popular in universities, companies, big enterprises etc. |
| GUI | Linux typically provides two GUIs, KDE and Gnome. But there are millions of alternatives such as LXDE, Xfce, Unity, Mate, twm, ect. | Initially Unix was a command based OS, but later a GUI was created called Common Desktop Environment. Most distributions now ship with Gnome. |
| Price | Free but support is available for a price. | Some free for development use (Solaris) but support is available for a price. |
| Security | Linux has had about 60-100 viruses listed till date. None of them actively spreading nowadays. | A rough estimate of UNIX viruses is between 85 -120 viruses reported till date. |
| Threat detection and solution | In case of Linux, threat detection and solution is very fast, as Linux is mainly community driven and whenever any Linux user posts any kind of threat, several developers start working on it from different parts of the world | Because of the proprietary nature of the original Unix, users have to wait for a while, to get the proper bug fixing patch. But these are not as common. |
| Processors | Dozens of different kinds. | x86/x64, Sparc, Power, Itanium, PA-RISC, PowerPC and many others. |
| Examples | Ubuntu, Fedora, Red Hat, Debian, Archlinux, Android etc. | OS X, Solaris, All Linux |
| Architectures | Originally developed for Intel's x86 hardware, ports available for over two dozen CPU types including ARM | is available on PA-RISC and Itanium machines. Solaris also available for x86/x64 based systems.OSX is PowerPC(10.0-10.5)/x86(10.4)/x64(10.5-10.8) |
| Inception | Inspired by MINIX (a Unix-like system) and eventually after adding many features of GUI, Drivers etc, Linus Torvalds developed the framework of the OS that became LINUX in 1992. The LINUX kernel was released on 17th September, 1991 | In 1969, it was developed by a group of AT&T employees at Bell Labs and Dennis Ritchie. It was written in “C” language and was designed to be a portable, multi-tasking and multi-user system in a time-sharing configuration. |
