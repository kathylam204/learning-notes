# Virtualization
## Virtualization
- allows us to run many operating systems simultaneously
- shared hardware, but each OS sees the components as its own
## Host-Based Virtulization
- runs on your desktop
## Hypervisor
- the virtual machine manager
- may require a CPU that supports virtualization
- manages hardware, networking, and security
## VM Escaping
- malware recognizes that it's on a VM and somehow compromises the hypervisor
- then, it jumps to other VMs that are managed by the hypervisor
## Virtual Machine Network Configuration Options
- Shared Network Address:
- the VM shares the same IP address as the physical host
- uses a private IP address internally
- uses NAT to convert to the physical host IP
- Bridged Network Address:
- the VM is a device on the physical network
- every VM has a different IP
- other devices can access the VM using its IP
- Private Network Address:
- the VM does not communicate outside of the physical network

