# Network Security
## Message Integrity Check (acronym)
- MIC
## Wi-Fi Protected Access II (acronym)
- WPA2
## Wi-Fi Protected Access III (acronym)
- WPA3
## Advanced Encryption Standard (acronym)
- AES
## Galois Message Authentication Code (acronym)
- GCMP with GMAC
## Counter Mode with Cipher Block Chaining
- Message Authentication Code Protocol (acronym)
- CCMP with CBC-MAC
## Pre-Shared Key (acronym)
- PSK
## Simultaneous Authentication of Equals (acronym)
- SAE
## WPA2
- uses CCMP block cipher mode
- provides data confidentiality using AES encryption
- adds a MIC with CBC-MAC (compared to WPA)
## WPA3
- introduced in 2018
- uses GCMP block cipher mode
- a stronger encryption method than WPA2
- provides data confidentiality with AES
- includes MIC with GMAC
## What is WPA2's biggest security threat?
- PSK brute-force attacks
- hackers can derive the PSK hash and then brute-force the actual PSK.
- once a hacker has the PSK, they also have everyone else's wireless key
- as technology improves, so does the speed of these attacks.
## SAE
- built into the WPA3 standard, also an IEEE standard that changed the PSK authentication process
- includes mutual authentication
- creates a shared session key without sending that key across the network
- without a hash, there's no risk of brute-force attacks
- SAE uses a diffie-hellman derived key exchange with an authentication component
- everyone uses a different session key, even with the same PSK
- dragonfly handshake
## Wireless Security Modes (list)
- open system
- WPA2/3 Personal or WPA2/3 PSK
- everyone uses the same 256-bit key
- WPA2/3 Enterprise or WPA2/3 802.1x
- authenticates users individually with an authentification server
## Remote Authentication Dial-In User Service (acronym)
- RADIUS
## RADIUS
- one of the more common AAA protocols
- supported on a wide variety of platforms and devices
- not just for dial-in
- centralizes authentication for users
## Terminal Access Control Access Control System (acronym)
- TACACS
## Terminal Access Controller Access-Control System Plus (acronym)
- TACACS+
## TACACS
- remote authentication protocol
- created to control access to dial-up lines to ARPANET
## TACACS+
- the latest version of TACACS
- provides more authentication requests and response codes
- released as an open standard in 1993
- commonly associated with Cisco devices, though
## Kerberos
- network authentication protocol
- supports SSO
- provides mutual authentication between the client and the server
- prevents against on-path or replay attacks
- standard since the 1980s
- used for Windows Domain authentication
## Wireless Evil Twins
- a form of social engineering where an access point is configured to look and act like an existing network
- may overpower the original access point
## Denial of Service Attacks
- when an attacker forces a service to fail by overloading the network and systems
- however, a non malicious DoS can occur:
- unintentional DoSing
- for example, a loop on a network could be considered a network DoS
- or, accidentally exceeding allotted bandwidth could be called a DoS
## Distributed Denial of Service (acronym)
- DDoS
## Denial of Service (acronym)
- DoS
## Distributed Denial of Service Attacks
- attack that uses an army of computers to bring down a service
- the army uses all of the network resources, leaving none for the service to run
- this "army" may be utilizing a botnet
## Botnet
- a logical computer network of zombies, controlled by an attacker or attackers.
- often utilized in DoS and DDoS attacks
## Mitigating DoS and DDoS Attacks
- stop the traffic at your firewall
- use an ISP that provides anti-DDoS systems and technologies
- use an available third-party Dos/DDoS prevention technology or tool
## IP Address Filtering
- content filtering, IP address ranges, or a combination of the two
- has an allow list and a deny list
- Content Filtering
- control traffic based on the data within the content
- useful in corporate environments to restrict sensitive data

## Static WAN IP
- external IP address
- may be dynamically allocated by the ISP
- may be able to switch to a static IP address for an additional cost
- easier management
## Universal Plug and Play (acronym)
- UPnP
## UPnP
- allows network devices to automatically configure and find other network devices
- applications on the internal network can open inbound ports using UPnP
- no approval is needed
- used for many P2P applications
- best practice would be to disable UPnP
## Peer-to-Peer (acronym)
- P2P
## Screened Subnet
- previously known as the demilitarized zone (DMZ)
- an additional layer of security between the internet and you
- public access to private resources
## Port Forwarding
- 24x7 access to a service hosted internally
- external IP/port number maps to an internal IP/port
- does not have to be the same port number
- also called Destination NAT or Static NAT
- does not expire or timeout
## Network Address Translation (acronym)
- NAT

