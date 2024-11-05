# **Intro to Basic Linux/Bash Commands**

Welcome to the **Intro to Linux/Bash Commands** session! This repository contains the core commands covered in our session to help you get started with navigating, managing files, and using basic utilities in the Linux terminal.

## **Table of Contents**
- [Getting Started with the Terminal](#getting-started-with-the-terminal)
- [Basic Commands](#basic-commands)
- [Basic Navigation Commands](#basic-navigation-commands)
- [File and Directory Management](#file-and-directory-management)
- [Viewing and Manipulating Files](#viewing-and-manipulating-files)
- [System and User Information](#system-and-user-information)
- [Networking Basics](#networking-basics)
- [Additional Resources](#additional-resources)

---

### **Getting Started with the Terminal**
Whether you’re on **Linux**, **macOS**, or **Windows (with WSL)**, open the terminal to start using these commands!

---
### **Basic Commands**
| Command                | Description                                        | Example                 |
|------------------------|----------------------------------------------------|-------------------------|
| `date`                 | Shows the current date and time                    | `date`                  |
| `cal`                  | Displays the calender for the current month        | `cal`                   |
| `groups`               | Lists the groups that the current user belongs     | `groups`                | 
| `file`                 | Determines and shows the file                      | `file myfile.txt`       |
| `man`                  | Opens the manual page for a specific command       | `man ls`                |
| `which`                | Displays the full path of the command’s executable | `which python`          |
| `whatis`               | Provides a brief description of a command          | `whatis grep`           |
| `apropos`              | Searches for commands related to a specific keyword| `apropos network`       |

---

### **Basic Navigation Commands**
| Command                | Description                                        | Example                 |
|------------------------|----------------------------------------------------|-------------------------|
| `pwd`                  | Print working directory (current location)         | `pwd`                   |
| `ls`                   | List files and directories                         | `ls -l`                 |
| `cd <directory>`       | Change directory                                   | `cd Documents`          |

---

### **File and Directory Management**
| Command                  | Description                                             | Example                  |
|--------------------------|---------------------------------------------------------|--------------------------|
| `mkdir <directory_name>` | Create a new directory                                  | `mkdir new_folder`       |
| `touch <file_name>`      | Create a new, empty file                                | `touch myfile.txt`       |
| `rm <file_name>`         | Remove (delete) a file                                  | `rm oldfile.txt`         |
| `rmdir <directory_name>` | Remove an empty directory                               | `rmdir empty_folder`     |
| `cp <source> <destination>` | Copies files or directories                          | ` cp myfile.txt backupfile.txt`  |
| `mv <source> <destination>` | Moves or renames files.                               | `mv myfile.txt newfile.txt`     |
| `rm <file_name>` | Deletes a file                                              | `rm myfile.txt`     |

---

### **Viewing and Manipulating Files**
| Command                       | Description                                      | Example                  |
|-------------------------------|--------------------------------------------------|--------------------------|
| `cat <file_name>`             | Display file contents                            | `cat myfile.txt`         |
| `head <file_name>`            | Show the first 10 lines of a file                | `head myfile.txt`        |
| `tail <file_name>`            | Show the last 10 lines of a file                 | `tail myfile.txt`        |
| `wc <file_name>`            | Counts the number of lines, words and characters in a file | `wc myfile.txt`    |
| `less <file_name>`            | View file content with scrolling (press `q` to exit) | `less myfile.txt`    |
| `echo "<text>" > <file_name>` | Write text to a file                             | `echo "Hello" > hello.txt` |

---

### **System and User Information**
| Command         | Description                                    | Example       |
|-----------------|------------------------------------------------|---------------|
| `df -h`         | Show disk space usage in a human-readable format | `df -h`      |
| `whoami`         | Shows the username of the current user  | `whoami`      |
| `free -h`       | Display memory (RAM) usage                     | `free -h`     |
| `who`           | Lists all users currently logged in | `who` |
| `uname -r`       | Shows the kernel version of the OS                 | `uname -r`     |
| `top`         | Displays running system processes in real-time           |  `top`       |
---

### **Networking Basics**
| Command                    | Description                                      | Example                    |
|----------------------------|--------------------------------------------------|----------------------------|
| `ping <hostname>`          | Check network connectivity                       | `ping google.com`          |
| `ifconfig`                 | Display network configuration (may require `sudo`) | `ifconfig`              |
| `netstat`                  | Show network connections and listening ports     | `netstat`                  |
| `nslookup <domain>`        | Find the IP address of a domain                  | `nslookup google.com`      |
| `traceroute <hostname>`    | Track the route packets take to reach a host     | `traceroute google.com`    |

---

### **Additional Resources**
For more in-depth learning:
- [The Linux Command Line by William Shotts](https://linuxcommand.org/tlcl.php)

---

Feel free to explore and experiment with these commands to build your Linux confidence. Happy coding!
