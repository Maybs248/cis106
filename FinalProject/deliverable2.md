---
Name: Maybel Perez
Class: cis106
Semester: spring 22
---

# Deliverable 2

## What is Virtualization?
![Virtualization](virtualization.png)

Virtualization is the replication of hardware to simulate a virtual machine inside a physical one. Two types of virtualization are; server-side virtualization and client-side virtualization. Server-side virtualization provides a desktop to all users and client-side virtualization manages virtual machines. Some benefits of virtualization are, allowing multiple OSs run on one machine and allowing applications to be tested before installing them on a host machine. Type 1 hypervisor runs on hardware such as VMware ESX and ESXi. Type 2 hypervisor runs on a host operating system such as Oracle VirtualBox. VirtualBox is a very powerful type 2 virtualization product for enterprises and at home use. Some of the benefits of Virtualization is that it allows running multiple of OS's on one machine, allows apps to be tested before installing them on a host machine, and it reduces costs by decreasing the physical hardware that must be purchased for a network. Virtualbox can run on Windows, Linux, Macintosh, and Solaris. In order for Virtualization to work on your computer you need 4GB of RAM, a Dual Core x64 processor with at least 1.3GHz or faster, and a AMD V or INTEL V compatible processor. This allows the computer to not run extremely slow and helps everything go smoothly and efficiently. 

## Virtualbox
![Virtualbox](VirtualBox.jpg)

Virtualbox allows users to extend their existing computer to run multiple operating systems including Windows, Mac OS X, Linux, and Oracle Solaris at the same time. Virtualbox comes with extension packs and a base package. The base package consists of all open source components and is licensed under GNU General Public License V2. The extension packs extends the functionality of the base package. This extension pack provides the virtual USB 2.0 (EHCI) and 3.0 (xHCI) device, Host webcam passthrough, Intel PXE boot ROM, disk image encryption with AES algorithm, and Virtualbox remote desktop protocol (VRDP) support.
<hr>

### Creating a virtual machine:
- Open Virtualbox
- Click on the machine menu
- Select New
- Set up your settings 

## Installing Ubuntu in a virtual machine
1. Name your operating system
2. Add the machine folder you'd like
3. Set to Linux and 64-bit
4. Select memory size of 2048
5. Create a VDI Hard disk
6. Select 50.00 GB for the Hard disk
7. Select Biodirectional for drag and drop and shared clipboard
8. Unselect Floppy disk
<hr>

### Updating Ubuntu
The command line to update Ubuntu is **`sudo apt update; sudo apt upgrade -y`**
### Installing Software
The command line to install software is **`sudo apt install -y`**
<hr>

## Basic Linux commands
| Linux Commands | Definition |
|----------------|------------|
|    **pwd**     | present working directory |
|     **cd**     | change directory |
|     **ls**     | lists all files in the current directory |
|    **mkdir**   | creates new directories |
|    **touch**   | creates files |
|     **rm**     | removes files |
|    **rmdir**   | removes directories |
|     **mv**     | renames and moves files and directories from one directory to another |

These are the most basic Linux commands but they are also the most used. On a day to day basis these commands will be a part of your entire life. Without them you cannot use Linux the way it was intended to be used. **pwd**, **cd**, **ls** are the commands most used for traveling throughout the Linux filesystem. **mkdir**, **touch**, **rm**, **rmdir**, **mv** are the most used commands for creating, removing, and moving directories and files. 