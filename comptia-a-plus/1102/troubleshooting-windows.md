# Troubleshooting Windows
## Blue Screens and Frequent Shutdowns
- might be linked to bad hardware, bad drivers, or a bad application
- use last known good, system restore, or rollback drivers to troubleshoot a possible software problem
- or try safe mode
- if potentially hardware related, remove or reseat the hardware
- run hardware diagnostics
## Sluggish Performance
- check task manager for high CPU and I/O utilization
- update Windows
- check for available disk space and defrag
- verify power-saving mode is turned off (laptops)
- run an anti-virus scan and an anti-malware scan
## Windows Boot Configuration (acronym)
- BCD
## Windows Boot Configuration
- "bootrec /rebuildbdcd" in the recovery console
## Boot Errors
- may be caused by a boot loader replacement or changes
- Try:
- checking boot drives
- remove any removable media
- using startup repair
- modifying BCD
## Startup Repair
- useful in missing NTLDR troubleshooting
- the main Windows boot loader is missing
- run Startup Repair or replace manually and reboot
- disconnect any removable media
- also useful with missing OS errors
- boot configuration data may be incorrect
- settings > system > recovery
- or run from advanced boot options
## Starting The System Troubleshooting
- if Windows is starting, but a device is not, check device manager and event viewer
- often due to a bad driver
- remove or replace
- the "one or more services failed to start" error is due to bad/incorrect drivers or bad hardware
- try starting manually
- check account permissions
- check service dependencies
- check system files (Windows Service)
- reinstall application (application service)
## Application Crashing
- check the event log and/or the reliability monitor
- reinstall the application
- contact application support
## Low Memory Warnings
- close large memory processes
- increase virtual memory
- system > about > advanced system settings > performance > virtual memory
## USB Controller Resource Warnings
- given when you exceed the number of USB endpoints (buffers)
- try moving the device to a different USB interface or matching the USB interface to the device capabilities
- USB 2.0 might support a larger number of endpoints
## System Instability
- general system failures
- Troubleshooting:
- run a full diagnostic (first)
- check the OS
- run SFC
- perform an anti-malware scan
## System File Checker
- verifies the integrity of the OS
- "sfc /scannow"
## System File Checker (acronym)
- SFC
## Time Drift
- enable automatic time setting
- settings > time & language > date & time
- the time zone may also need configuration
## Restarting Services
- options under "services" in task manager
## Uninstalling/Reinstalling/Updating Applications
- settings > apps > apps & features
- some options in the control panel under programs and features
## Restoring Windows Using System Restore
- system > about > system protection
- pick a restore time and let the system reboot
- user data is not modified
## Windows Reset Option
- reimage or reload the OS
- Windows 10: settings > update & security > recovery
- Windows 11: settings > system > recovery
## Update and Patch The OS (or Roll Back Updates)
- Windows 10: settings > update & security > windows update
- Windows 11: settings > windows update
## Deleting a Windows Profile (steps)
- login to the computer with domain administrator rights
- rename the \users\name folder
- backup the user's registry
- HKLM\software\microsoft\windows nt\currentversion\profilelist
- right click and export
- delete the registry entry
## Recreating a Windows Profile (steps)
- login to the computer with the user account
- the profile will be rebuilt
- login as the domain administrator and copy any important files from the old profile, to the new profile
