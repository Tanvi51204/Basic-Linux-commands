# **Intro to Basic Linux/Bash Commands**

Welcome to the **Intro to Linux/Bash Commands** session! This repository contains the core commands covered in our session to help you get started with navigating, managing files, and using basic utilities in the Linux terminal.

## **Table of Contents**
- [Getting Started with the Terminal](#getting-started-with-the-terminal)
- [Basic Navigation Commands](#basic-navigation-commands)
- [File and Directory Management](#file-and-directory-management)
- [Viewing and Manipulating Files](#viewing-and-manipulating-files)
- [System Information](#system-information)
- [Networking Basics](#networking-basics)
- [Additional Resources](#additional-resources)

---

### **Getting Started with the Terminal**
Whether you’re on **Linux**, **macOS**, or **Windows (with WSL)**, open the terminal to start using these commands!

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

---

### **Viewing and Manipulating Files**
| Command                       | Description                                      | Example                  |
|-------------------------------|--------------------------------------------------|--------------------------|
| `cat <file_name>`             | Display file contents                            | `cat myfile.txt`         |
| `head <file_name>`            | Show the first 10 lines of a file                | `head myfile.txt`        |
| `tail <file_name>`            | Show the last 10 lines of a file                 | `tail myfile.txt`        |
| `less <file_name>`            | View file content with scrolling (press `q` to exit) | `less myfile.txt`    |
| `echo "<text>" > <file_name>` | Write text to a file                             | `echo "Hello" > hello.txt` |

---

### **System Information**
| Command         | Description                                    | Example       |
|-----------------|------------------------------------------------|---------------|
| `df -h`         | Show disk space usage in a human-readable format | `df -h`      |
| `free -h`       | Display memory (RAM) usage                     | `free -h`     |
| `top`           | View active processes and system resource usage (press `q` to exit) | `top` |
| `history`       | List previously used commands                 | `history`     |
| `clear`         | Clear the terminal screen                     | `clear`       |

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

### **Helpful Commands for Help!**
| Command                   | Description                                      | Example                   |
|---------------------------|--------------------------------------------------|---------------------------|
| `man <command>`           | Display the manual page for a command            | `man ls`                  |
| `which <command>`         | Show the path to an executable command           | `which python`            |
| `whatis <command>`        | Get a brief description of a command             | `whatis grep`             |
| `apropos <keyword>`       | Find commands related to a keyword               | `apropos network`         |

---

### **Additional Resources**
For more in-depth learning:
- [The Linux Command Line by William Shotts](https://linuxcommand.org/tlcl.php)
- [Linux Documentation Project](https://tldp.org/)

---

Feel free to explore and experiment with these commands to build your Linux confidence. Happy coding, and may the terminal be with you!
