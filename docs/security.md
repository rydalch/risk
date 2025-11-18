# Information Security Testing & Tools

This document provides a comprehensive resource guide for security testing, vulnerability assessment, and penetration testing tools and methodologies. These resources support risk assessment and security control validation activities.

## Overview

Effective security programs require systematic testing and validation of controls. This guide organizes security tools by assessment phase and objective, supporting:

- Vulnerability identification and remediation
- Penetration testing and threat simulation
- Security assessment and continuous monitoring
- Evidence collection for compliance

## Standards & Methodologies

### Penetration Testing Standards

- [PTES - Penetration Testing Execution Standard](http://www.pentest-standard.org/) - Comprehensive framework for planning and executing penetration tests
- [OWASP - Open Web Application Security Project](https://www.owasp.org/) - Web application security standards and best practices
- [OSSTMM - Open Source Security Testing Methodology Manual](http://www.isecom.org/) - Methodologies for security testing

### Compliance Frameworks

- **NIST**: National Institute of Standards and Technology security standards (SP 800 series)
- **ISO**: International Organization for Standardization security standards (ISO 27001, 27002)
- **GLBA**: Gramm-Leach-Bliley Act financial services security requirements
- **HIPAA**: Health Insurance Portability and Accountability Act healthcare security requirements
- **FISMA**: Federal Information Security Modernization Act federal system requirements
- **PCI-DSS**: Payment Card Industry Data Security Standard for payment systems

## Testing & Development Environments

### Vulnerable VMs for Practice

- **Metasploitable** - Linux VM with intentional vulnerabilities for testing tools
- **WebGoat** - Insecure J2EE web application designed for security training
- [Certified Hacker Practice Sites](http://certifiedhacker.com/) - Various intentionally vulnerable applications
- **Wireshark Trace Files** - Network packet captures for analysis practice

## Reconnaissance & Footprinting

### Website & DNS Research

- **Netcraft** - Website technology and hosting information
- **Archive.org** - Historical website versions and data
- **WHOIS Tools**: Sam Spade, DNSStuff, DomainTools
- **DNS Tools**: nslookup, Dig (BIND), DNS-Digger
- **IP Tools**: ARIN, WherISIP, SpyFu

### Network Reconnaissance

- **Traceroute Tools**: VisualRoute, PingPlotter, Path Analyzer Pro
- **Web Mirroring**: BlackWidow, Wget, Teleport Pro
- **Google Hacking**: [Google Hacking Database](http://www.hackersforcharity.org/ghdb)

## Scanning & Enumeration

### Port & Service Scanning

- **Nmap/ZenMap** - Network mapper and port scanner
- **Angry IP Scanner** - Network IP scanner and pinger
- **SuperScan** - TCP/UDP port scanner and banner grabber
- **NetScan Tools Pro** - Comprehensive network scanning suite
- **Hping** - TCP/IP packet generator and analyzer

### Vulnerability Scanning

- **Nessus** - Leading vulnerability assessment platform
- **OpenVAS** - Open source vulnerability scanner
- **Qualys** - Cloud-based vulnerability and compliance scanning
- **Rapid7 Nexpose** - Dynamic vulnerability scanning and management
- **GFI LanGuard** - Windows network security scanner
- **Retina** - Vulnerability and compliance assessment
- **Nikto** - Web server vulnerability scanner

### Banner Grabbing & Service Detection

- Telnet / NetCat - Manual service identification
- **Xprobe** - OS fingerprinting tool
- **THC-AMAP** - Application mapper and banner grabber

## Web Application Testing

### Web Proxies & Interceptors

- **Burp Suite** (Pro) - Web application security testing platform
- **OWASP ZAP** - Free web security scanner
- **Paros Proxy** - Web application proxy for security testing
- **Fiddler** - HTTP/HTTPS proxy for debugging

### Web Vulnerability Scanning

- **WebInspect** - Web application scanning and testing
- **Nikto** - Web server vulnerability scanner
- **SQLMap** - SQL injection detection and exploitation
- **W3AF** - Web attack and audit framework

### SQL Injection Tools

- **SQLMap** - Automated SQL injection testing
- **SQLGET** - SQL injection exploitation
- **SQLNinja** - SQL injection penetration testing

## Network & Protocol Analysis

### Packet Capture & Analysis

- **Wireshark** - Network protocol analyzer and packet capture
- **tcpdump** - Command-line packet capture
- **Capsa** - Network analyzer with packet capture
- **Ettercap** - Network sniffing and ARP spoofing
- **tcpflow** - TCP flow extractor

### Wireless Network Assessment

- **Kismet** - Wireless network detector and analyzer
- **NetStumbler** - Wireless AP scanner and analyzer
- **Aircrack/Airodump** - WiFi cracking and packet capture
- **WiFi Pilot** - Wireless network scanner
- **Vistumbler** - Wireless network stumbler

## System & Password Testing

### Password Cracking & Testing

- **John the Ripper** - Unix password cracker
- **Ophcrack** - Rainbow table-based password cracker
- **Hashcat** - GPU-accelerated password cracker
- **L0phtCrack** - Windows password auditing
- **Aircrack** - WEP/WPA password cracking
- **THC-Hydra** - Login brute-force tool

### Keylogging & Monitoring

- **KeyProwler** - Keylogger tool
- **Actual Keylogger** - System monitoring
- **HiJackThis** - Startup and running processes monitor
- **Process Explorer** - Advanced process viewer
- **CurrPorts** - TCP/UDP port monitor

## Exploitation & Post-Exploitation

### Exploitation Frameworks

- **Metasploit** - Penetration testing framework
- **Armitage** - Metasploit GUI interface
- **Core Impact** - Commercial penetration testing platform
- **CANVAS** - Commercial exploitation framework

### System Access & Privilege Escalation

- **PSTools** - Windows system administration tools
- **Netcat** - Network utility for various purposes
- **Mimikatz** - Windows credential dumping tool
- **Privilege Escalation Exploits** - OS-specific exploit tools

## Log Analysis & Forensics

### Log Analysis & Monitoring

- **Splunk** - Enterprise log analysis and monitoring platform
- **ELK Stack** (Elasticsearch, Logstash, Kibana) - Open source log analysis
- **ArcSight** - Enterprise security information and event management
- **Syslog Analysis** - Log file parsing and analysis

### Forensics & Incident Response

- **Wireshark** - Network packet forensics
- **FTK** (Forensic Toolkit) - Digital forensics platform
- **Encase** - Computer forensics tool
- **Volatility** - Memory forensics framework
- **Mandiant Tools** - Malware analysis and incident response

## Encryption & Cryptography

### Encryption Tools

- **TrueCrypt/VeraCrypt** - Disk encryption
- **BitLocker** - Windows full disk encryption
- **OpenSSH** - Secure shell and key management
- **PGP/GnuPG** - Email and file encryption

### Hash & Cryptanalysis

- **HashCalc** - Hash calculation utility
- **MD5 Hash Generators** - MD5 hash verification
- **Cryptobench** - Cryptographic benchmarking

## Evasion & Defense

### IDS/IPS & Evasion

- **Snort** - Intrusion detection system
- **Suricata** - Network threat detection engine
- **ADMutate** - Polymorphic shellcode generator
- **NIDSBench** - IDS evasion tool

### Proxy & Anonymization

- **Tor** - Anonymization network
- **ProxyChains** - Proxy routing tool
- **Proxifier** - HTTP/HTTPS proxy client
- **psiphon** - Circumvention tool

## Security Information Resources

### Vulnerability Databases

- [NVD - National Vulnerability Database](https://nvd.nist.gov/) - NIST vulnerability data
- [SecurityTracker](https://www.securitytracker.com/) - Vulnerability tracking
- [Exploit Database](https://www.exploit-db.com/) - Public exploits repository
- [PwnedList](https://pwnedlist.com/) - Compromised account database
- [SecurityFocus](https://www.securityfocus.com/) - Security research and vulnerability data

### Information Security News & Magazines

- ISACA.org - Governance and audit resources
- SecurityManagement.com - Security management resources
- InfoSecurityMag.com - Information security magazine
- SCMagazine.com - Security industry news
- Dark Reading - Cybersecurity news and insights

## Related Resources

- [Threat Modeling](./threat-modeling.md) - Identifying threats for testing
- [GRC Tools](./tools.md) - Vulnerability management platforms
- [Control Frameworks](./frameworks.md) - Security control standards
- [Learning Resources](./learning.md) - Training and certifications

## Responsible Use

**Important**: These tools should only be used:

- On systems you own or have explicit written permission to test
- For authorized security assessments and penetration tests
- In authorized training environments and labs
- In compliance with applicable laws and regulations
- Following your organization's security policies

Unauthorized access to computer systems is illegal. Always obtain proper authorization before testing.
