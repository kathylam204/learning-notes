# Network Devices
## Routers
- routes traffic between IP subnets
- makes forwarding decisions based on IP addresses
- OSI layer 3 (network layer)
- often connection diverse (LAN, WAN, copper, fiber)
## Switches
- bridges devices together
- forwards traffic based on the data link address
- contains many ports and features
- may provide PoE (power over ethernet)
- OSI layer 2 (data link layer)
## Multilayer Switches
- contains routing functionality
- OSI layer 3 (network layer)
## Unmanaged Switches
- has very few configuration options (plug and play)
- fixed configuration (no VLANs)
- very little integration with other devices (no management protocols)
- low price point
## Managed Switches
- provides VLAN support (interconnect with other switches via 802.1Q)
- traffic prioritization
- redundancy support using STP (Spanning Tree Protocol), which prevents loops between multiple switches
- port mirroring (capture packets to troubleshoot or analyze)
- external management options (for example, SNMP, or Simple Network Management Protocol)
## Access Points
- provides wireless connectivity for a local network
- provides a link between the wireless network and the wired network (a bridge)
- makes forwarding decisions based on the destination mac address (identical process to a switch)
## Firewalls
- filters traffic based on the port number
- may be able to filter based on application traffic (OSI layer 7)
- OSI layer 4 (TCP/UDP layer)
- can encrypt traffic into and out of the network, to protect it between sites
- can proxy traffic
- may also have router functionality (OSI layer 3)
## Hubs
- multi-port repeater
- becomes less efficient as network traffic increases
- Half-duplex
- succeeded by switches
- speeds of 10 megabit and 100 megabits
## Cable Modems
- broadband communication
- transmission across multiple frequencies and different traffic types
- data over a "cable" network (using the DOCSIS, Data over Cable Service Interface Specification)
- provides high-speed networking, with speeds up to 1 gigabit per second
- can support multiple services such as data, voice, and video
## DSL (Digital Subscriber Line) Modems
- utilizes telephone lines
- asymmetric, as download speed is faster than the upload speed (hence the acronym, ADSL, or Asymmetric Digital Subscriber Line)
- distance limitations of about 10000 feet from the central office
- common speeds of about 52 megabits per second downstream, and 16 megabits per second upstream
- faster speeds are possible the closer that you are to the central office
## ONTs (Optical Network Terminal)
- gateway for fiber optic internet
