# Windows (Set 2)
## Windows Task Manager
- provides real-time system statistics
## Starting the Windows Task Manager (list)
- ctrl-alt-del, then select task manager
- right click the task bar and select Task Manager
- Ctrl-shift-esc
## Services Tab (ask Manager)
- non interactive applications
- background processes
- right click a service to start, stop, or restart it
## Startup Tab (Task Manager)
- manage which programs start with a Windows login
## Processes Tab (Task Manager)
- view all running processes
- including those from other accounts
## Performance Tab (Task Manager)
- view CPU, memory, disk, bluetooth, and network performance
- historical and real-time
## Users Tab (Task Manager)
- view user connections and activity
- includes options to disconnect a user and to manage user accounts
## Microsoft Management Console (acronym)
- MMC
## Microsoft Management Console
- build your own management consoles
- add snap-ins to customize
- Mmc.exe
## Event Viewer (MMC)
- provides centralized event consolidation
- application, security, setup, and system event information
- different levels for each event:
- information, warning, error, critical, successful audit, failure audit
- "Eventvwr.msc"
## Disk Management (MMC)
- manage disk operations
- individual computers or file servers
- "Diskmgmt.msc"
## Task Scheduler (MMC)
- schedule an application or a script
- includes predefined schedules
- includes organizational tools such as folders
- "Taskschd.msc"
## Device Manager (MMC)
- manages devices and their drivers
- "Devmgmt.msc"
## Certificate Manager (MMC)
- view and manage user and trusted certificates
- "Certmgr.msc"
## Local Users and Groups (MMC)
- manage users and groups
- "Lusrmgr.msc"
## Performance Monitor (MMC)
- provides OS metrics
- set alerts and automated actions
- store statistics
- provides built in performance reports
- "Perfmon.msc"
## System Information
- provides a system overview
- "msinfo32.exe"
- Sections:
- hardware resources
- Components
- software environment
## Resource Monitor
- detailed, real-time view of performance
- "resmon.exe"
- Categories:
- Overview
- CPU
- Memory
- Disk
- Network
## System Configuration
- manage boot processes, startup, services, etc.
- "Msconfig.exe"
## Disk Cleanup
- find unused or unneeded files
- "Cleanmgr.exe"
## Disk Defragmentation
- moves file fragments so that they are contiguous
- improves read and write times
- not necessary for SSDs
- graphical version of this tool is available in Drive Properties
- or use "defrag [volume]" in command line
## Windows Registry Editor
- master database
- used by almost everything in Windows
- "Regedit.exe"
## Internet Options (Control Panel)
- customize how the built-in browser will operate inside of Windows
- Tabs:
- General
- Security
- change access based on site location
- Privacy
- customize cookies, pop-up blocker, location, and InPrivate browsing settings
- Content
- manage digital certificates and auto-complete settings
- Connections
- manage VPN and proxy settings
- Programs
- modify the default browser, plugins, etc.
- Advanced
- contains detailed configuration options as well as a reset button
## Devices and Printers (Control Panel)
- shows everything on the network
- easier management than device manager
## Programs and Features (Control Panel)
- modify or remove installed applications
- turn Windows features on or off
## Network and Sharing Center (Control Panel)
- add, modify, or remove network adapters
- advanced settings and streaming options available, here
## System (Control Panel)
- shows computer information, including the version and edition of Windows
- modify system properties and system preferences
- configure remote desktop
## Mail (Control Panel)
- the mail applet icon does not appear unless a mail client is installed on the system
- provides access to local mail configuration
- account information
- data files
## Indexing Options (Control Panel)
- speed up the search process
- control what information might be searched
## File Explorer Options (Control Panel)
- Tabs:
- General
- View
- customize how files and folders are seen
- provides options to view hidden files and to hide extensions
- Search
- modify what is shown when you perform a search
## Power Options (Control Panel)
- configure how Windows uses power
- options to choose what closing the lid on a laptop does
- options for USB selective suspend
- used to disable individual USB devices
- enable or disable fast startup
- Modes:
- Hibernate
- open documents and applications are saved to the disk
- used by Fast Startup
- sleep (standby)
- open files and applications are stored in memory
- save power and startup quickly
- switches to hibernate if power is low
## How does Windows set the time, by default?
- automatically, with five minutes of tolerance
## Privacy (Settings)
- enable or disable shared application activity, shared language, and speech recognition
## System (Settings)
- modify many Windows features:
- Display
- night light, scaling, resolution
- audio settings
- Notifications
## Network and Internet (Settings)
- view internet status and modify IP address settings
## Accounts (Settings)
- manage and configure login account information
- MS accounts are considered local accounts
- includes email configuration
- manage sign-in options
## Application and Driver Operating System Compatibility
- both are specific to the OS version
- 64-bit operating systems can run 64-bit and 32-bit applications
- 32-bit apps are stored in "\Program Files (x86)"
- 64-bit apps are stored in "Program Files"
- 32-bit operating systems cannot run 64-bit applications
## Application Resource Requirements
- check with each application for it's specific requirements
- to run an application, your resources must exceed the operating systems required resources and exceed the application's required resources
## Application Graphics Resource Requirements
- may require only integrated graphics, or a dedicated graphics card
- integrated graphics:
- combined CPU and GPU chip
- uses system memory for graphics
- dedicated graphics card:
- uses it's own vRAM
## External Hardware Tokens
- manages application usage
- the application will only work if this hardware device is present
- commonly a USB device
- often used with high-end software
## ISO Files
- a sector by sector copy of the data on an optical disk
- uses the ISO 9660 file system, collapsed into a single file
- must be mounted in the OS
- appears as a separate drive
## Application Installation Impacts and Considerations (list)
- impact to device
- impact to network
- access to internal services
- rights and permissions to file shares
- impact to operation
- impact to business
- critical processes are sensitive to downtime and outages
## Hardware Compatibility Check
- runs when you perform a Windows upgrade
- run manually from the Windows setup screen
- called the Windows 10 Upgrade Checker or the PC Health Checker for Windows 11
## How long does Windows provide OS support?
- 18 to 36 months after release
