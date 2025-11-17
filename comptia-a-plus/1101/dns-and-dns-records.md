# DNS & DNS Records
## Domain Name System (DNS)
- translates human-readable domain names into computer-readable IP addresses
- made of multiple, hierchial servers
- distributed database
## Resource Records (RR)
- database records of DNS
- over 30 record types
## Address Records (A) (AAAA)
- A Records:
- IPv4
- modify to change the host name to IP address resolution
- AAAA Records:
- IPv6
- the same DNS server, different records (modify to change the host name to IP address resolution)
## Mail Exchanger Records (MX)
- determines the host name for the mail server
## Text Records (TXT)
- human-readable text information
- useful public information
- can be used for verification purposes or email security
- use "dig [website name] txt" in cmd prompt to view (or, "nslookup -type=txt [website name/domain name]" when dig isn't - available)
## Time To Live (TTL)
- specifies how long an end station will remember the match between a fully qualifies domain name and IP address
## Sender Policy Framework (SPF)
- a list of all the email servers that are authorized to send messages using your fully qualified domain name
- prevents spoofing (mail servers perform a check to see if incoming mail really did come from an authorized host)
## Domain Keys Identified Mail (DKIM)
- digitally signs a domain's outgoing mail
- valuated by mail servers (not usually seen by the end-user)
- the public key is stored in the DKIM TXT record
## Domain-Based Message Authentication, Reporting, and Conformance (DMARC)
- prevents unauthorized email use and spoofing
- an extension of SPF and DKIM
- takes the extra step to determine the disposition that should be used when someone receives a message that cannot be validated

