## Linux File System

Directories in linux are just folders in the Linux. Folders are used to store the information in various formats of files. 

So the bottom layer of all this folders and directories in Linux is Root. To enter into root folder you can give the command `cd /`. Directories present in the root directory of a Linux system serve various purposes and organize the file system hierarchy. Here's a brief overview of some common directories found in the root directory (`/`) and their purposes:

`/bin`: bin folder contains binary files(commands). Examples include basic shell commands like `ls`, `cp`, `mv`, `rm`, etc. The files which are present in the bin folder are all executable files.

`/boot`: boot directory handles how your linux operating system is going to boot up including the Linux kernel, boot loader configuration, etc.

`/etc`: etc folder simply contains your configuration files. It includes configuration files for various applications, services, and system settings.

`/dev`: Contains device files representing physical and virtual devices attached to the system. These files are used to communicate with hardware devices.

`/home`: home directory contains all the user data. Contains home directories for individual users. Each user typically has a subdirectory within /home where they store their personal files and configurations.

`/lib` and `/lib64`: Contains shared libraries required by programs at runtime. /lib is used for 32-bit libraries, while /lib64 is used for 64-bit libraries.

`lost+found`: Consider this as your recycle bin. It is typically empty under normal circumstances and only contains files when the file system check (fsck) utility has detected and recovered orphaned inodes or corrupted file system structures.

`media`: You connect any external drive like hard drive, all those things will get mounted in the media.

`mnt`: It is a short form of Mount. Under this folder you can mount different types of external drives. Even when you dual boot your laptop with a specified hard disk from your PC. You can still access your disk you created in Windows machine with this mount option.

`/opt`: Typically used for installing additional software packages not provided by the distribution's package manager. Third-party software and applications are often installed in subdirectories of /opt.

`/sys`: Special virtual filesystems that provide information about kernel parameters, hardware, and system settings (/sys).

`/sbin`: Contains system binaries (commands) used for system administration tasks. These binaries are typically intended to be run by the root user.

`/tmp`: Used for temporary files created by programs or users. Files in this directory are typically deleted when system is rebooted.

`/usr`: Contains user-related programs, libraries, documentation, and other data not essential for basic system operation. It's further subdivided into directories like /usr/bin, /usr/lib, /usr/share, etc.

`/var`: Contains variable data files, including logs, spool files, temporary files, and other files that may change frequently during system operation. 

---

In addition to this let's understand what is relative path and what is absolute path in Linux directories:

**Relative path**: Relative path is just path from where you are in the current file system and you can access the files and folders present in that folder. It describes the path based on your current location within the file system, without starting from the root directory (/).

**Absolute path**: If you want to access the files or folders which are present in another folder or directory you have to provide the fool path from root so you can access that particular file or directory is called Absolute path. 

