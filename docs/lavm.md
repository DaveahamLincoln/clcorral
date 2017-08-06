# Module 1: Linux & Virtual Machines

The first step to getting underway with learning to be a console cowboy is to familiarize yourself with the Linux operating system.  While it is possible to undertake 
development work on Windows, it is much more difficult than doing so on Linux, as each individual component and dependency must be manually installed, with no sort of 
automatic compatibility checking.  Over time, the more components and libraries you add, the harder it is to keep them working together, until you find yourself 
troubleshooting Windows more than your code.  Linux also has the advantage of being written by programmers for programmers, so it is deeply customizable and offers many 
utilities for controlling what it does at a very fine-grained level.  The las, most important difference between Windows and Linux is that it Linux is comprised of 
freely-available "open source" software.

##Why Open Source?

Open source software has a couple big advantages over "proprietary" or "licensed" software:

1. It's free!  You won't ever run into a situation where you need to pay for a software package on Linux.

2. The source code is publicly available.  As you get more experience with the concepts in this course, you will probably run into situations where you would like to 
learn how a particular application that you use does what it does, or to customize the application itself.  This isn't really something you can do with proprietary 
software (unless said software comes bundled with tools for doing so), but when it comes to open source software, it's quite easy to do (provided that you can read and 
write the programming language that the application is written in).

3. Lots of community support exists.  In the world of proprietary software, if you run into an issue, it can be very difficult to get in touch with the people who 
developed the software for help.  When it comes to open source software, simply googling an error message will return a huge number of articles and discussions about the 
issue, often with step-by-step instructions for fixing it.  Most developers also publish huge piles of documentation for their software on the internet, which you can 
refer to for help.  If all of this this fails for some reason, you can usually get directly in touch with the developers directly via email/IM, and they can probably 
help you.


##Virtual Machines
Now, you might be thinking that you'll have to install Linux on its own dedicated machine, which you might not have at the moment.  Thankfully, the technology exists 
to run Linux inside of the Windows operating system using something called a 'virtual machine.'  A virtual machine (VM) is an emulation of a computer system. Virtual 
machines are based on computer architectures and provide functionality of a physical computer. They also isolate the OS from the machine running the VM, so if you break 
something beyond repair (which you probably will at some point), you'll only have to fix the VM rather than the whole computer.

Before you can get started with this module, you're going to need two things- a hypervisor and a Linux ISO.

###Hypervisor Installation
A hypervisor or virtual machine monitor (VMM) is computer software, firmware or hardware that creates and runs virtual machines. A computer on which a hypervisor runs 
one or more virtual machines is called a host machine, and each virtual machine is called a guest machine. The hypervisor presents the guest operating systems with a 
virtual operating platform and manages the execution of the guest operating systems. Multiple instances of a variety of operating systems may share the virtualized 
hardware resources: for example, Linux, Windows, and macOS instances can all run on a single physical x86 machine.

The hypervisor that I prefer the most is VirtualBox, which you can download for free [here.](http://download.virtualbox.org/virtualbox/5.1.22/VirtualBox-5.1.22-115126-Win.exe)

Go ahead and install it, then take some time to read through the documentation [here](https://www.virtualbox.org/manual/ch01.html) and 
[here.](https://www.virtualbox.org/manual/ch04.html)

###ISO Installation
Your next step is to acquire an ISO file (basically a virtual "installation CD") for the Linux distribution you would like to use.  While there are many different kinds 
of Linux distributions (or 'distros'), the largest and most popular is called Ubuntu, and I would recommend that you start with it because there is such a large user 
base that you should be able to find information about just about any issue you run into while using it just by searching the internet.

You can acquire the [16.04 LTS (long-term service/support) Ubuntu ISO here.](https://www.ubuntu.com/download/desktop/contribute?version=16.04.2&architecture=amd64)

Once you've downloaded it, go ahead and install it on VirtualBox, [following this guide (including the Guest Additions bit).](https://linus.nci.nih.gov/bdge/installUbuntu.html)

##Now it's TIME TO LEARN SOME THINGS
Once you've gotten everything installed, start working through [this Linux sysadmin 
course.](https://www.youtube.com/watch?v=bju_FdCo42w&list=PLtK75qxsQaMLZSo7KL-PmiRarU7hrpnwK) The course will give you a complete introduction to all of the concepts 
that you'll need to learn your way around Linux.  

If at this point you feel like you might want to do a deep-dive into a Linux book, start with the free ict@innovation [Training Guide on
Linux System Administration](https://www.linuxcertification.co.za/sites/default/files/LPIManual_v_09.pdf), or the more in-depth (but still free) FTA [GNU/Linux Advanced Administration](http://ftacademy.org/sites/ftacademy.org/files/materials/fta-m2-admin_gnulinux-v1.pdf) book.

If you still find yourself wanting even more information, you can start by tracking down one of the following books:

[How Linux Works, 2nd Edition: What Every Superuser Should Know](https://www.amazon.com/How-Linux-Works-Superuser-Should/dp/1593275676)

[UNIX and Linux System Administration Handbook, 4th Edition](https://www.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0131480057)


