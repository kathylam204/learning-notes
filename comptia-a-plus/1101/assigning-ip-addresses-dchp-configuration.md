# Assigning IP Addresses & DHCP Configuration
## The DHCP (Dynamic Host Configuration Protocol) Process
## DORA
- happens every time a device connects to a network and needs to obtain an IP address from a DHCP server
- Discover:
- devices will try to find a DHCP server on the network
- Offer
- Request
- lock in the offer from the DHCP server
- Acknowledge
- over udp/68, by default
- the needed configuration settings are provided
## DHCP Scope Properties (Configuration Settings)
- IP address range
- subnet mask
- lease duration
- DNS server settings
- default gateway
- VoIP servers
## DHCP Leases
- configure a lease time in the DHCP server
- can set up reallocation to renew your lease
- IP addresses can also be manually released by moving to another subnet
## T1 Timer
- checks with the lending DHCP server halfway through the lease time to renew the lease
- renews the lease
## T2 Timer
- tries rebinding with any DHCP server if the original DHCP server is down, at 7/8ths or 87.5% of the lease time
## APIPA (Automatic Private IP Addressing)
- assigned to your device when it's configured to obtain a DHCP address, but there's no longer a DHCP server on the local network
- creates a link-local address, which can only communicate with devices on the local network
- automatically assigned
## Static IP Address
- an IP address that doesn't change
- needs to be manually configured or configured using IP reservation in the DHCP server (associated a specific MAC address with an IP address)
## Dynamic IP Address
- an IP address that occasionally changes
