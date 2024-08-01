---
title: "Mastering the Basics of the Linux Command Line"
seoTitle: "Linux Command Line Basics Mastery"
seoDescription: "Learn Linux commands, directory structure, user permissions, and system monitoring to boost productivity and efficiency in the terminal"
datePublished: Thu Aug 01 2024 19:47:14 GMT+0000 (Coordinated Universal Time)
cuid: clzbotbdg00000ala3er51ksz
slug: mastering-the-basics-of-the-linux-command-line
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/OqtafYT5kTw/upload/9df24b6f4c902f803bbabd2f1ee62150.jpeg
tags: linux, devops, linkedin, 2articles1week, linux-for-beginners, linux-kernel, linux-for-devops

---

### 1\. Introduction of Linux

The session was conducted by @BabarZahoor on CLI, Directory Structure and Basic Command - Linux & DevOps Bootcamp. It's a complete series on Linux, docker and Kubernetes. My learning outcomes are below:

* **Directory Structure Explanation:** In linux 'c' drive is known as root. As we use call in window os drive 'C'. It is important to store linux system directories in root.
    
* **Command Line Interface (CLI):** It is terminal used for basic navigation commands and bash shell is used for scripting.
    
* **Listing Files and Directories:** Uses `ls` command to list files, explains long listing format with `ls -al`, and describes hidden files and directories.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722538904081/f8d99ee9-ad1b-431f-95fb-058c4c957cf8.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722538949044/6ff5c72f-2ee3-4bc3-af9e-2bcc6bc433a4.jpeg align="center")

* **User Permissions and Ownership:** Explains user and group ownership, discusses administrative access with sudo, and highlights the importance of permissions.
    
* **File Types and Colors:** File types are differentiated by color, explains executable and link files, and shows examples of various file types
    

### 2\. Linux in Details

* **User and administrative commands:** User commands do not have administrative access, while administrative commands are stored separately, and libraries and executable files are discussed.
    
* **Navigating directories:** Commands to change directories, understand root and parent directories, and examples of directory navigation.
    
* **System files and directories:** Boot files and kernel files are located in /boot directory.
    
* **Device files and drivers:** Device files are devices and device drivers are also located in /dev directory.
    
* **Configuration files:** These files are located in /etc directory.
    

### 3\. Linux Directory Structure

* **User and administrative commands:** User commands are without administrative access, location of library files, and administrative commands for system management.
    
* **Directory navigation:** Changing directories using commands, understanding root and parent directories, and viewing available commands and their usage.
    
* **Boot and kernel files:** Grub with config files, kernel files, and bootable directories located in /boot.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722539242116/fe5eb539-0718-43e3-84df-c6eef7d24971.jpeg align="center")

* **Device and storage management:** Understanding device drivers, managing storage devices, and viewing device information.
    
* **System configuration and logs:** Configuration files are in the /etc directory, and system logs with system processes also here.
    

### 4\. Linux Environment

By the following way files and directories are managed in linux environment.

* **Introduction to directories: E**xplanation of home and root directories, differences between user and root directories, and the importance of directory structure.
    
* **Basic commands:** Using `ls` to list directory contents, `man` for command manuals, and `touch` and `cat` to create and view files.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722539532133/1bd01ef1-971d-4d45-99c9-7212f589a720.jpeg align="center")

* **Editing files:** Introduction to text editors like vi, basic commands for editing and saving files, and practical examples.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722539583748/670660e8-d3af-49fd-93b1-53a407644e98.jpeg align="center")

* **System monitoring:** Using `top` to monitor system resources helps in understanding CPU and memory usage, along with practical tips for system management.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722538556076/e77534c7-78a2-4bd4-a90e-fc81def88e21.jpeg align="center")

### 5\. Linux CLI

The Command Line Interface (CLI) in Linux significantly enhances productivity in several ways:

* Speed: CLI commands are typically faster to execute than navigating through graphical user interfaces (GUIs).
    
* Automation: Scripts can be easily created to automate repetitive tasks.
    
* Remote access: CLI allows efficient management of remote systems with minimal bandwidth.
    
* Resource efficiency: CLI uses fewer system resources compared to GUI applications.
    
* Precision: Commands offer precise control over system operations.
    
* Flexibility: Complex operations can be performed by combining simple commands.
    
* Text processing: Powerful text manipulation tools are available directly from the command line.
    
* System monitoring: Quick access to system information and real-time monitoring.
    
* Batch operations: Easily perform actions on multiple files or systems simultaneously.
    
* Reproducibility: Commands can be easily documented and replicated.
    
* Customization: Users can create aliases and functions to tailor their environment.
    
* Piping and redirection: Output from one command can be directly used as input for another.
    

### 6\. Users Management

The following table describes the privileges to Administrator (Root) and Regular users.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722539908657/0c484f90-fa67-42e6-b8dc-13649cc75ce3.jpeg align="center")

### 7\. Some common Commands used in CLI terminal

Here are some common CLI commands for managing files and directories in Linux:

* ls: List directory contents    Example: ls -l (detailed list)
    
* cd: Change directory    Example: cd Documents
    
* pwd: Print working directory   Example: pwd
    
* mkdir: Create a new directory    Example: mkdir (name of folder)
    
* rm: Remove files or directories    Example: rm file.txt (remove file)
    
* rm -r folder (remove directory) Example: r means recursively
    
* cp: Copy files or directories   Example: cp file.txt /path/to/destination
    
* mv: Move or rename files/directories    Example: mv old\_name.txt new\_name.txt
    
* touch: Create an empty file or update timestamps    Example: touch newfile.txt
    
* cat: Display file contents    Example: cat file.txt
    
* grep: Search for patterns in files     Example: grep "search\_term" file.txt
    
* chmod: Change file permissions     Example: chmod 755 [script.sh](http://script.sh)
    
* chown: Change file ownership     Example: chown user:group file.txt
    
* find: Search for files and directories    Example: find /home -name "\*.txt"
    
* tar: Archive files    Example: tar -cvf archive.tar files/
    
* df: Display disk space usage     Example: df -h
    

### 8\. Summary of Article

This article provides an in-depth overview of essential Linux concepts and commands, covering directory structure, basic command-line interface (CLI) operations, user permissions, system monitoring, and file management. Key sections include an introduction to user and administrative commands, navigating directories, understanding system files, managing device drivers and configuration files, leveraging the CLI for productivity, and handling common user management tasks. Practical examples and command explanations aim to enhance understanding and efficiency in using Linux. All credit goes to sir @BabarZahoor.

%[https://www.youtube.com/live/RZo45sFSSvE?si=z_VLtgMpzbBrvrr8]