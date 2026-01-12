# Security Tools & Testing Guide

These are common testing tools and methodologies that support risk assessment and security control validation activities.

## Development Environment

### VS Code
- **Purpose:** Primary code editor for scripts, configurations, and documentation
- **Use Cases:** Python scripting, PowerShell, Bash, configuration files
- **Resources:** 
  - [Download](https://code.visualstudio.com/)
  - [Getting Started](https://code.visualstudio.com/docs/introvideos/basics)
- **Key Features:** Extensions for security tools, integrated terminal, Git support

### Docker Desktop
- **Purpose:** Container platform for isolated testing environments
- **Use Cases:** Running vulnerable apps, tool isolation, lab environments
- **Resources:** [Download](https://www.docker.com/products/docker-desktop/)
- **Key Features:** Easy deployment of security tools, reproducible environments

---

## Foundational Tools

### Wireshark
- **Purpose:** Network protocol analyzer and packet capture tool
- **Use Cases:** Traffic analysis, protocol debugging, network forensics
- **Resources:** [Download](https://www.wireshark.org/download/)
- **Key Features:** Deep packet inspection, protocol decoding, filtering
- **Lab Focus:** TCP/IP analysis, identifying attacks, protocol understanding

### Nmap
- **Purpose:** Network discovery and security auditing scanner
- **Use Cases:** Host discovery, port scanning, service enumeration
- **Resources:** [Download](https://nmap.org/download.html)
- **Key Features:** OS detection, script scanning, various scan types
- **Lab Focus:** Network mapping, vulnerability discovery

### Additional Network Tools
- **tcpdump**: Command-line packet capture
- **Angry IP Scanner**: Fast IP address and port scanner
- **Capsa**: Network analyzer with packet capture
- **NetScan Tools Pro**: Comprehensive network scanning suite

---

## Network Analysis & Scanning

### Aircrack-ng
- **Purpose:** WiFi security assessment suite
- **Use Cases:** WPA/WEP cracking, packet injection, WiFi monitoring
- **Resources:** [Download](https://www.aircrack-ng.org/)
- **Key Features:** Capture, attack, testing, and cracking capabilities
- **Lab Focus:** Wireless security fundamentals

### Hping
- **Purpose:** TCP/IP packet crafting and manipulation
- **Use Cases:** Firewall testing, port scanning, DoS testing
- **Resources:** [Download](http://www.hping.org/download.html)
- **Key Features:** Custom packet creation, traceroute, file transfer

### Scapy
- **Purpose:** Python-based packet manipulation library
- **Use Cases:** Custom protocol testing, packet forging, network discovery
- **Resources:** [Installation Guide](https://scapy.readthedocs.io/en/latest/installation.html)
- **Key Features:** Interactive packet crafting, pcap file manipulation

### Wireless Tools
- **Kismet**: Wireless network detector and analyzer
- **NetStumbler**: Wireless AP scanner and analyzer
- **WiFi Pilot**: Wireless network scanner

---

## Web Application Security

### OWASP ZAP (Zed Attack Proxy)
- **Purpose:** Web application vulnerability scanner
- **Use Cases:** Automated scanning, manual testing, API testing
- **Resources:** [Download](https://www.zaproxy.org/)
- **Key Features:** Intercepting proxy, active/passive scanning, automation
- **Lab Focus:** OWASP Top 10 vulnerabilities

### Burp Suite Community
- **Purpose:** Web application security testing platform
- **Use Cases:** Intercepting proxy, vulnerability scanning, manual testing
- **Resources:** [Download](https://portswigger.net/burp)
- **Key Features:** Proxy, scanner, repeater, intruder modules
- **Lab Focus:** Web application penetration testing

### Nikto
- **Purpose:** Web server vulnerability scanner
- **Use Cases:** Configuration issues, outdated software detection
- **Resources:** [Download](https://cirt.net/Nikto2)
- **Key Features:** SSL support, multiple output formats, plugin architecture

### Additional Web Tools
- **SQLMap**: Automated SQL injection testing and exploitation
- **WebInspect**: Web application scanning
- **W3AF**: Web attack and audit framework
- **Fiddler**: HTTP/HTTPS proxy for debugging

---

## Vulnerability Assessment

### Nessus Essentials
- **Purpose:** Comprehensive vulnerability scanner
- **Use Cases:** Network vulnerability assessment, compliance scanning
- **Resources:** [Download](https://www.tenable.com/products/nessus)
- **Key Features:** CVE detection, configuration auditing, reporting
- **Lab Focus:** Vulnerability management lifecycle

### OpenVAS
- **Purpose:** Open-source vulnerability assessment system
- **Use Cases:** Network vulnerability scanning, reporting
- **Resources:** [Download](https://www.openvas.org/)
- **Key Features:** Free alternative to commercial scanners

### Other Scanners
- **Qualys**: Cloud-based vulnerability and compliance scanning
- **Rapid7 Nexpose**: Dynamic vulnerability scanning
- **GFI LanGuard**: Windows network security scanner

---

## Exploitation & Penetration Testing

### Metasploit Framework
- **Purpose:** Penetration testing and exploitation framework
- **Use Cases:** Vulnerability exploitation, payload generation, post-exploitation
- **Resources:** [Download](https://www.metasploit.com/)
- **Key Features:** Exploit database, auxiliary modules, meterpreter
- **Lab Focus:** Ethical hacking fundamentals

### Kali Linux
- **Purpose:** Penetration testing Linux distribution
- **Use Cases:** Complete pentesting platform with pre-installed tools
- **Resources:** [Download](https://www.kali.org/downloads/)
- **Key Features:** 600+ security tools, regular updates, documentation
- **Lab Focus:** Linux command line, tool integration

### Additional Frameworks
- **Armitage**: GUI interface for Metasploit
- **Core Impact**: Commercial penetration testing platform
- **CANVAS**: Commercial exploitation framework
- **Mimikatz**: Windows credential dumping tool

---

## Password Security & Cracking

### John the Ripper
- **Purpose:** Password security auditing and recovery
- **Use Cases:** Password strength testing, hash cracking
- **Resources:** 
  - [Download](https://www.openwall.com/john/)
  - [macOS Version](https://download.openwall.net/pub/projects/john/contrib/macosx/)
- **Key Features:** Multiple hash formats, wordlist and brute-force modes
- **Lab Focus:** Password policy assessment

### Hashcat
- **Purpose:** Advanced password recovery tool
- **Use Cases:** GPU-accelerated hash cracking
- **Resources:** [Download](https://hashcat.net/hashcat/)
- **Key Features:** GPU acceleration, rule-based attacks

### Other Tools
- **Ophcrack**: Rainbow table-based password cracker
- **THC-Hydra**: Login brute-force tool
- **L0phtCrack**: Windows password auditing

---

## Defensive Security & Monitoring

### Splunk Enterprise (Free License)
- **Purpose:** Security information and event management (SIEM)
- **Use Cases:** Log analysis, security monitoring, incident response
- **Resources:** [Download](https://www.splunk.com/en_us/download.html)
- **Key Features:** Search processing language, dashboards, alerts
- **Lab Focus:** Log analysis, correlation, threat hunting

### Semgrep
- **Purpose:** Static application security testing (SAST)
- **Use Cases:** Code vulnerability detection, secure coding
- **Resources:** [Download](https://semgrep.dev/)
- **Key Features:** Multiple language support, custom rules

### OWASP Threat Dragon
- **Purpose:** Threat modeling and risk assessment
- **Use Cases:** Application threat modeling, risk documentation
- **Resources:** 
  - [Download](https://www.threatdragon.com/)
  - [OWASP Threat Modeling Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html)
- **Key Features:** Data flow diagrams, threat identification

### Additional Defense Tools
- **ELK Stack**: Elasticsearch, Logstash, Kibana
- **Snort/Suricata**: Intrusion detection/prevention systems
- **ArcSight**: Enterprise SIEM

---

## Learning Environments

### OWASP WebGoat
- **Purpose:** Deliberately vulnerable web application for learning
- **Use Cases:** Web security training, OWASP Top 10 practice
- **Resources:** [Download](https://owasp.org/www-project-webgoat/)
- **Key Features:** Guided lessons, hints system, progress tracking
- **Lab Focus:** Web vulnerability exploitation practice

### DVWA (Damn Vulnerable Web Application)
- **Purpose:** PHP/MySQL vulnerable web application
- **Use Cases:** Security training, testing tools
- **Resources:** [Download](https://dvwa.co.uk/)
- **Key Features:** Adjustable security levels, various vulnerabilities

### Windows/Ubuntu VMs
- **Purpose:** Operating system environments for testing
- **Resources:** 
  - [Windows 11](https://www.microsoft.com/en-us/software-download/windows11)
  - [Ubuntu](https://ubuntu.com/download/desktop)
  - [Windows Server 2022](https://www.microsoft.com/en-us/windows-server)
- **Lab Focus:** OS security, Active Directory (Windows Server)

### Other Training Resources
- **Metasploitable**: Intentional vulnerable Linux VM
- **Certified Hacker Practice Sites**: Various vulnerable apps

---

## Reconnaissance & Footprinting (Additional)

- **Netcraft**: Website technology and hosting information
- **Archive.org**: Historical website versions
- **DNS Tools**: nslookup, Dig, DNS-Digger
- **WHOIS Tools**: Domain ownership research
- **Google Hacking Database**: Public search queries for vulnerabilities

## Encryption, Forensics & Evasion

- **Encryption**: TrueCrypt/VeraCrypt, BitLocker, PGP/GnuPG
- **Forensics**: Autopsy/The Sleuth Kit, FTK, Volatility
- **Anonymization**: Tor, ProxyChains

## Standards & Methodologies

- [PTES](https://www.pentest-standard.org/): Penetration Testing Execution Standard
- [OSSTMM](https://www.isecom.org/research.html#content5-9d): Open Source Security Testing Methodology Manual
- [NIST NVD](https://nvd.nist.gov/): National Vulnerability Database
