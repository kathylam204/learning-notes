# Linux Features and Commands
## Linux Command Line Options (list)
- Terminal
- XTerm
- (etc.)
## Linux Commands
- similar to Mac OS commands
## "man" (command)
- shows the manual for a Linux command
## "ls" (command)
- lists directory contents
- similar to "dir" in Windows
- may support color coding
- blue indicates a directory
- red indicates an archive file
- add "-l" at the end to view a longer output
- adding "-l | more" will present a page by page view
- use "q" or key in ctrl-c to exit this view
## "pwd" (command)
- prints the working directory's name (path)
## "Mv"
- move or rename a file
- "mv [source] [destination]
- for example, "mv first.txt second.txt"
## "cp" (command)
- copies a file
- "cp [source] [destination]"
## "rm" (command)
- removes a file or directory
- a directory must be empty to be removed, or must be removed with "-r"
## "chmod" (command)
- changes the mode (permissions) of a file system object
- "chmod [mode] [file]"
- for example, "chmod 744 script.sh"
- this would grant the user rwx, group r--, and others r–
- can also use letters to specify the mode
## Linux File System Modes (list)
- r (read)
- w (write)
- x (execute)
## Linux File System Mode Cheat Sheet (image)
## "chown" (command)
- changes a file's owner and/or group
- requires root permissions and credentials
- "sudo chown [owner]:[group] [file]"
- "[group]" is optional
## "su" (command)
- become the super user
- grants administrative (root) privileges
## "sudo" (command)
- execute a command as the super user
- grants administrative (root) privileges, but only when using "sudo" in front of a command
## "apt-get" (command)
- advanced packaging tool
- handles the management of application packages
- "sudo apt-get [install/update/remove] [application]"
## "yum" (command)
- manages RPM (Red Hat) packages
## "ip" (command)
- manage the network interface
## Commonly Used "ip" Commands (list)
- "ip address"
- "ip route"
## "ip address" (command)
- view the interface address
- for example, "sudo ip address add [ip address and subnet mask] dev [adapter name]"
- configures the IP address of an interface
## "ip route" (command)
- view the IP routing table
## "df" (command)
- view file systems and free space
- presented in blocks
- use "df -h" to view in human-readable sizes
## "grep" (command)
- used to find text in a file or files
- "grep [text pattern] [file]"
## "ps" (command)
- view the current processes
- use "ps -e" to view all processes, including those for other users
## "top" (command)
- view resource utilization
- includes a summary of the overall load
- presented in one, five, and fifteen minute intervals
## "find" (command)
- find a file by the name or file extension
- "find . -[name] [file and extension]"
- finds files with that specific extension
- the "." indicates that the search will begin at the current folder (the working folder)
## "dig" (command)
- lookup information from DNS servers
- provides detailed domain information
## "cat" (command)
- concatenate files
- "cat [first file and extension] [second file and extension]"
- copies a file or files to another file
## "nano" (command)
- provides a full-screen text editor
## "tar" (command)
- used to create and manage tape drive archives and backups
- can be used for any type of file
- easy to script into a backup schedule
## "rsync" (command)
- provides a utility for syncing files between storage devices
- can be instant or scheduled
## Software Center
- Linux's version of the Mac OS App Store
## Anti-Virus and Anti-Malware on Linux
- no built-in options
- Clam is the recommended third-party anti-virus
- Open-source
## "Samba"
- file server utility
- often used to add SMB (Server Message Block) to Linux systems
- implement file and printer sharing
- integrate with Active Directory
- integrates Linux into a Windows environment

