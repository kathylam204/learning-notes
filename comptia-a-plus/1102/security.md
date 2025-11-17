# Security
## Key Fobs
- contains a small RFID key
- Contactless
- replaces a physical key
- utilizes proximity operationality
## Smart Cards
- provide certificate based authentication
- requires a smart card reader to authenticate
## Does biometric authentication store an image of your unique biometric?
- no, biometric authentication is usually stored as a mathematical representation.
## Magnometers
- metal detectors
- provides passive scanning
## Mobile Device Management (acronym)
- MDM
## MDM
- provides centralized management for company owned and user owned devices
## Rule of Least Privilege
- rights and permissions should be set to the bare minimum for both user accounts and applications.
## Access Control Lists (acronym)
- ACL
## ACL
- used to allow or deny traffic
- also used by operating systems
- commonly used on the ingress or egress of a routing interface
## Phishing
- social engineering with a touch of spoofing
- often delivered by email or over text
## Voice Phishing (acronym)
- Vishing
## Vishing
- phishing that occurs over the phone or through voicemail
- caller ID spoofing is common
## Spear Phishing
- targeted phishing, using insider information
## Whaling
- spear phishing the CEO of a company
## Tailgating
- uses an authorized person to gain unauthorized access to a building
- the attacker does not have consent
## Piggybacking
- uses an authorized person to gain unauthorized access to a building
- unlike tailgating, the attacker does have consent
- for example, the attacker is holding donuts and asks to have the office door held for them
## Zero-Day Attacks
- an attack type that exploits a vulnerability, known to the attackers, but unknown to the application's/system's/device's vendor and support team are aware of it
- utilizes exploit code
## On-Path Attacks
- also known as a man-in-the-middle attack
- the attacker sits in between your system and the network, and redirects your traffic
## Address Resolution Protocol (acronym)
- ARP
## ARP Poisoning
- utilizes spoofing
- an on-path attack that occurs on the local IP subnet
- due to ARP's lack of security features
## On-Path Browser Attacks
- the man-in-the-middle is on the local device, in the browser
- the attacker uses the advantage of encrypted traffic being so easy to proxy
- malware, often a trojan horse does all of the proxy work
## Hashes and Hashing a Password
- represent data as a fixed-length string of test
- will likely not have a collision (match another hash)
- makes it impossible to recover an original message from the digest
- without knowing the hash, the hashing method, etc.
- SHA-256 is a common hashing method.
- different operating systems and applications use different hash algorithms.
## Brute Force Attacks
- a form of password attack where attackers try every single possible password combination, until the password's hash is matched
- time consuming
- also requires a large amount of computing power and resources
## Code Injection
- adding your own code into a data stream
- enabled due to bad programming
- many different data types
## Structured Query Language (acronym)
- SQL
## SQL Injection
- a method of code injection where SQL requests are modified
- if you can manipulate an SQL database, then you can control the application
## Cross-Site Scripting (acronym)
- XSS
## Cross-Site Scripting
- we take information from one website and share it with another
- utilizing browser security flaws
- one of the most common web application development errors
- by using malware that takes advantage of JavaScript
## Why is Cross-Site Scripting abbreviated as XSS?
- though CSS seems like a better acronym for cross-site scripting, it is already utilized for a programming language, used in website design.
## What are some of the most common programming languages, used for developing websites and web applications? (list)
- JavaScript
- provides the interactivity to websites and web applications
- HTML
- CSS (cascading style sheets)
- used for describing the presentation of code, written in a term-30markup language, such as HTML
- Java
- not related to JavaScript
- used to develop web applications, games, and software
## Uniform Resource Locator (acronym)
- URL
## Non-Persistent (Reflected) Cross-Site Scripting Attacks (steps)
- the website allows scripts to run inside of user input prompts and text boxes
- to utilize this design flaw, the attacker emails a link
- this link runs a script that sends credentials, session IDs, and cookies to the attacker
- simultaneously, the script embedded in the URL executes in the victim's browser
## URL vs Domain Name (example)
- google.com is an example of a fully qualified domain name.
- as seen above, a domain name does not include the protocol, and any subdomains, paths, or file names.
- a website URL includes all of these components.
- https://www.google.com/search?q=domain+name&sxsrf=ALiCzsYV67... is an example of a URL, and includes the domain name, "google.com", as well as the:
- protocol (HTTPS)
- subdomain (www)
- path (/search?q=domain+name&sxsrf=ALiCzsYV67/)
- always ends with "/"
- in this example, the URL is shortened due to space constraints (shown by the "..." at the end of the shown URL"
- as our web search did not lead us into viewing or opening a file, no file path is included.
- an example of a URL with a file path, however, is https://www.google.com/search/file.html (URL is made-up)
- this example's file path is "file.html"
## URL
- a complete web address
## Persistent (Stored) Cross-Site Scripting Attacks
- malicious code is placed on a centralized server, such as a social media website
- inside of a comment, for example
- everybody who visits the page or who views the comment gets attacked
- no specific target
## Will disabling JavaScript protect against Cross-Site Scripting attacks?
- yes, however, it's not a practical solution
## Standard Operating Environment (acronym)
- SOE
## Standard Operating Environments
- a set of tested and approved hardware/software systems
- often a standalone OS image
## When does Microsoft release Window's patches?
- the second tuesday of every month at 10:00am PST
## Patch Management (steps)
- Test
- Prioritize
- Deploy
## EOL Operating Systems
- manufacturer stops selling an OS
- may continue supporting it, though
## End of Service Life (acronym)
- EOSL

## EOSL
- similar to EOD, but support is no longer available
- a costly, premium support option may exist, though
## Windows Defender Antivirus
- built into Windows 10 and Windows 11
- included in the Windows security application
- operates in real-time
- virus & threat protection settings > manage settings > real-time protection
## Windows Firewall Exception Rule Types (list)
- Program
- Port
- Predefined
- Custom
## Windows Authentication
- log in using a local account or a Microsoft account or a domain account
- Windows domain credentials are SSO
## NTFS Permissions
- apply from local and network connections
- inherited from the parent
## Share Permissions
- only apply to connections over the network
- the most restrictive setting wins
## Explicit Permissions
- set by us
- take precedence over inherited permissions
## User Account Control (acronym)
- UAC
## User Account Control
- pop-up approval screen
- limits user capabilities
- secure desktop
## BitLocker
- encrypts an entire volume
- all data, including the OS
- not included in Windows Home editions
## BitLocker To Go
- BitLocker FDE for USB drives
- not included in Windows Home editions
## EFS
- encrypt at the file system level
- requires NTFS
- uses a username and password to encrypt the key
- administrative password resets cause EFS files to be inaccessible
## Autoplay
- settings > bluetooth & devices > Autoplay
- AutoRun on older Windows operating systems
## Verifying Certificate Details (list)
- Verify
- not expired
- domain name
- properly signed
- date and time
## Cache
- locally stored browser data
## Unable to Access The Network (Troubleshooting)
- may be due to malware
- Symptoms:
- slow performance and lock up
- internet connectivity issues
- OS update failures
- use malware cleaner or reload from a known good backup
## Altered System or Personal Files (Troubleshooting)
- indicates malware
- remove or reload from a known good backup
## Browser Redirection (Troubleshooting)
- malware is the most common cause
- best practice is to restore from a known good backup

