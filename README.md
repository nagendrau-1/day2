# day2

Learning Academy :- SKILLS UPRISE

Mentor:- Manoj kumar Koravangi

IPv4 and IPv6,private and public IP ranges, domain names, domain structure, DNS importance, ports, and protocols.
IPv4 and IPv6 are internet protocols that assign unique addresses to devices for network communication. IPv4 uses 32-bit addresses (about 4.3 billion unique ones), while IPv6 employs 128-bit addresses for vastly more capacity (3.4 x 10^38 addresses).
IPv4 vs IPv6
IPv4 addresses appear as four decimal numbers (e.g., 192.168.1.1), but exhaustion has driven IPv6 adoption with hexadecimal notation (e.g., 2001:0db8:85a3::8a2e:0370:7334). IPv6 offers simpler headers, built-in IPsec security, and end-to-end connectivity without NAT, unlike IPv4's optional features and complexity.
Private and Public Ranges
Public IPs are globally routable on the internet, while private ones are for local networks and not internet-routable. IPv4 private ranges include 10.0.0.0–10.255.255.255 (Class A), 172.16.0.0–172.31.255.255 (Class B), and 192.168.0.0–192.168.255.255 (Class C); APIPA uses 169.254.0.0–169.254.255.254. IPv6 private ranges are FC00::/7 (reserved) and FD00::/7 (unique local addresses).
Domain Names
Domain names are human-readable addresses (e.g., example.com) that map to IP addresses via DNS. They follow a hierarchical structure from right to left: top-level domain (.com), second-level (example), and subdomains (www).
Domain Structure
DNS hierarchy starts at the root (.), then top-level domains (TLDs like .com, .org), second-level domains, subdomains, and hosts. This tree allows up to 127 levels for scalability.
DNS Importance
DNS translates domains to IPs, enabling intuitive web access, scalability for millions of sites, and security against threats like phishing. It supports email, cloud services, and reliable resolution via name servers and resolvers.
Network Ports
Ports are virtual endpoints (0–65535) identifying services on a device, paired with IPs for communication. Well-known ports (0–1023) serve standards like HTTP (80), HTTPS (443); registered (1024–49151); dynamic (49152–65535).
Key Protocols
TCP is connection-oriented, reliable with error-checking and sequencing, ideal for web (HTTP/HTTPS), email (SMTP). UDP is connectionless, faster but unreliable, suited for DNS, streaming, VoIP.
