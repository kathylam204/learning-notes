# Operating Systems
## Why do you need an operating system?
- controls interaction between components
- provides a common platform for applications
- provides the user interface (UI)
## Standard OS Features (list)
- file management
- application support
- I/O support
- included OS configuration and management tools
## Microsoft Windows Advantages (list)
- large industry support
- many OS options
- wide variety of software support
## Microsoft Windows Disadvantages (list)
- big target for security exploitation
- challenging integration due to the sheer amount of support for various hardware
## Linux Advantages (list)
- Free
- works on a wide variety of hardware
## Linux Disadvantages (list)
- limited driver support
- limited support options
## Mac OS Advantages
- easy to use
- extremely compatible
- relatively few security concerns
## Mac OS Disadvantages
- requires apple hardware
- high initial cost
- less industry support than Windows
## Chrome OS
- based on the Linux kernel
- created around the Chrome web browser
- most applications are web based
- many different manufacturers
- relatively cheap
- relies on the cloud
## iPad OS Tablet Features (list)
- browser (Safari)
- second monitor support (Sidecar)
- keyboard support
- Multitasking
## iOS
- based on Unix
- cloud sourced
## iOS Applications
- developed with iOS SDK on MacOS
- must be approved by Apple, prior to release
## Google Android
- from the Open Handset Alliance
- open sourced, based on Linux
- wide device and hardware support
## Google Android Applications
- developed on Windows, MacOS, and Linux, using the Android SPK
## End of Life (acronym)
- EOL
## OS EOL Policies
- vary depending on the OS
## Updating Operating Systems
- iOS, Android, and Windows check and prompt for updates.
- Chrome OS updates automatically
## Do applications have compatibility between different operating systems?
- There is almost no direct application compatibility between operating systems.
## Boot Methods for Installing an Operating System (list)
- USB storage
- must be bootable
- computer must support booting from USB
- optical media
- PXE
- SSDs and HDDs
- Internet-based
- external/hot swappable drive
- some can mount an ISO image
- boot from USB
## Preboot Execution Environment (acronym)
- PXE
## PXE
- allows for remote OS installation, over a network
- booting with PXE must be supported by the OS
## Types of Operating System Installations (list)
- in-place upgrade
- recovery partition
- clean install
- can be in conjunction with a migration tool
- image deployment
- deploy a clone on every computer
- can be completely automated
- repair installation
- does not modify user files
- remote network installation
- install across the internet, or from a local server or shared drive
## Disk Partitions
- separates the physical drive into logical pieces
- useful for maintaining multiple operating systems
- in Windows, formatted partitions are called volumes
## GUID Partition Table (acronym)
- GPT
## GPT Partition Style
- the latest partition format standard
- requires a UEFI BIOS
- can have up to 128 partitions
- maximum partition size is over 9 billion TB
- no need for extended partitions or logical drives
## Master Boot Record (acronym)
- MBR
## MBR Partition Style
- maximum partition size of 2 TB
- includes primary and extended partitions
- primary partitions:
- Bootable
- maximum of four per hard disk
- one can be marked as active
- extended partitions:
- used for extending the maximum number of partitions
- one per hard disk (though optional)
- contains additional logical partitions
- not bootable
## Disk Partitioning
- the first step when preparing disks
- disks may already be partitioned, though
- not always compatible with the new OS
- occurs during Windows startup
## Quick Format (Disk Partitioning)
- creates a new file table
- looks like data is erased, but it's not
- no additional checks
- the default option
## Full Format (Disk Partitioning)
- uses the "diskpart" utility
- writes zeroes to the whole disk, making data unrecoverable
- checks the disk for bad sectors
