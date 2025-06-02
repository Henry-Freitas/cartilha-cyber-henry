## 💻 Comandos CMD úteis

ipconfig /all        # Mostra detalhes da rede local
ping 8.8.8.8         # Verifica conexão com a internet
tracert google.com   # Rastreia o caminho até um site
netstat -an          # Lista conexões abertas
whoami               # Exibe o usuário logado
systeminfo           # Detalhes sobre o sistema operacional


# Cyber Security Commands for CMD

This repository contains a collection of useful cyber security commands that can be executed using the Command Prompt (CMD) on Windows. These commands are helpful for various cyber security tasks such as network scanning, monitoring, and troubleshooting.

## Table of Contents

- [Network Commands](#network-commands)
- [System Information](#system-information)
- [File and Directory Operations](#file-and-directory-operations)
- [User and Group Management](#user-and-group-management)
- [Process Management](#process-management)
- [Security and Permissions](#security-and-permissions)

## Network Commands
   Command | Description |
 |---------|-------------|
 | `ipconfig` | Displays all current TCP/IP network configuration values. |
 | `ipconfig /all` | Displays detailed network configuration information. |
 | `ping <hostname or IP>` | Sends ICMP echo requests to a specified host. |
 | `tracert <hostname or IP>` | Traces the route taken by packets to a specified host. |
 | `netstat` | Displays active TCP connections and ports on which the computer is listening. |
 | `netstat -ano` | Displays active TCP connections and ports along with process IDs. |
 | `nslookup <hostname>` | Queries DNS to obtain domain name or IP address mapping. |
 | `arp -a` | Displays the ARP cache, which contains IP-to-MAC address mappings. |
 | `route print` | Displays the IP routing table. |
 | `netsh wlan show profiles` | Displays a list of wireless network profiles. |
 | `netsh wlan show networks` | Displays a list of available wireless networks. |

## System Information
 | Command | Description |
 |---------|-------------|
 | `systeminfo` | Displays detailed configuration information about a computer and its operating system. |
 | `wmic product get name,version` | Lists installed software and their versions. |
 | `driverquery` | Displays a list of all installed device drivers. |
 | `tasklist` | Displays a list of currently running processes. |
 | `wmic cpu get name,numberofcores,maxclockspeed` | Displays CPU information. |
 | `wmic memorychip get capacity,speed` | Displays RAM information. |
 | `wmic diskdrive get size,model` | Displays disk drive information. |
 | `wmic bios get serialnumber` | Displays the BIOS serial number. |
 | `wmic os get caption,version,osarchitecture` | Displays OS information. |

## File and Directory Operations
 | Command | Description |
 |---------|-------------|
 | `dir` | Lists files and directories in the current directory. |
 | `dir /s` | Lists files and directories in the current directory and all subdirectories. |
 | `cd <directory>` | Changes the current directory. |
 | `mkdir <directory>` | Creates a new directory. |
 | `rmdir <directory>` | Removes a directory. |
 | `copy <source> <destination>` | Copies a file from the source to the destination. |
 | `move <source> <destination>` | Moves a file from the source to the destination. |
 | `del <file>` | Deletes a file. |
 | `type <file>` | Displays the contents of a text file. |
 | `findstr "<pattern>" <file>` | Searches for a pattern in a file. |

## User and Group Management
 | Command | Description |
 |---------|-------------|
 | `net user` | Displays a list of user accounts on the computer. |
 | `net user <username>` | Displays information about a specific user account. |
 | `net user <username> <password> /add` | Creates a new user account. |
 | `net user <username> /delete` | Deletes a user account. |
 | `net localgroup` | Displays a list of local groups on the computer. |
 | `net localgroup <groupname>` | Displays information about a specific local group. |
 | `net localgroup <groupname> <username> /add` | Adds a user to a local group. |
 | `net localgroup <groupname> <username> /delete` | Removes a user from a local group. |

## Process Management
 | Command | Description |
 |---------|-------------|
 | `tasklist` | Displays a list of currently running processes. |
 | `taskkill /PID <PID>` | Terminates a process by its Process ID (PID). |
 | `taskkill /IM <imagename>` | Terminates a process by its image name. |
 | `wmic process get name,processid` | Displays a list of running processes with their names and PIDs. |
 | `start <program>` | Starts a new instance of a program. |
 | `shutdown /s` | Shuts down the computer. |
 | `shutdown /r` | Restarts the computer. |
 | `shutdown /l` | Logs off the current user. |

## Security and Permissions
 | Command | Description |
 |---------|-------------|
 | `cacls <file or directory>` | Displays or modifies the Access Control Lists (ACLs) of files. |
 | `icacls <file or directory>` | Displays or modifies the Discretionary Access Control Lists (DACLs) of files. |
 | `takeown /f <file or directory>` | Takes ownership of a file or directory. |
 | `auditpol` | Displays or modifies the audit policy of a computer. |
 | `gpupdate` | Refreshes local and Active Directory-based Group Policy settings. |
 | `secedit /configure /cfg <filename>` | Configures the system security settings based on a specified security template. |
 | `sc query` | Displays a list of installed services. |
 | `sc query <servicename>` | Displays information about a specific service. |

Feel free to contribute to this repository by adding more useful cyber security commands or improving the existing ones.
