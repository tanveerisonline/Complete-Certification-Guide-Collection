# CEH (Certified Ethical Hacker) v12 Guide (2025-2026)

## Overview
CEH is an ethical hacking certification validating penetration testing and security auditing skills. It teaches hackers to think like attackers while operating within legal and ethical boundaries.

**Certification Code:** EC-Council CEH v12 (312-50)

---

## Duration & Study Timeline
- **Recommended Study Duration:** 3-6 months
- **Study Hours Required:** 250-400 hours
- **Hands-On Lab Time:** 100-150 hours
- **Exam Preparation:** 4-8 weeks

---

## Exam Details

### Exam Duration
- **Total Duration:** 4 hours
- **Total Questions:** 125 questions
- **Question Format:** Multiple choice, scenario-based

### Exam Structure
- **Passing Score:** 70% (87.5/125 questions)
- **Difficulty Level:** Intermediate to Advanced
- **Timer:** Visible during exam

### Exam Fee (2025-2026)
- **Exam Only:** $500 USD
- **Exam + Training:** $1,200-3,000 USD (depending on provider)
- **Exam Retake:** $500 USD
- **Official Exam:** Pearson Vue or EC-Council testing centers

### Prerequisites
- **EC-Council Requirements:**
  - 2+ years information security work experience, OR
  - CEH Practical exam, OR
  - EC-Council approved training

---

## Complete Syllabus & Topics

### Module 1: Footprinting & Reconnaissance (7%)

#### Information Gathering
- **Passive Reconnaissance**
  - OSINT techniques
  - Dork searches and SHODAN
  - Social media enumeration
  - Domain name registration info
  - Website analysis
  - Email harvesting
  - Metadata extraction
  - Search engine recon
- **Active Reconnaissance**
  - DNS enumeration
  - Whois lookups
  - Traceroute
  - Network scanning
  - Direct contact
  - Dumpster diving
  - Physical surveillance

#### Tools
- Google, Bing, DuckDuckGo advanced search
- Shodan and Censys
- theHarvester
- Whois tools
- Maltego
- Recon-ng
- SpiderFoot
- nslookup and dig

### Module 2: Scanning & Enumeration (10%)

#### Port Scanning
- **Scanning Techniques**
  - TCP connect scanning
  - SYN stealth scanning
  - ACK scanning
  - FIN, NULL, Xmas scanning
  - UDP scanning
  - Decoy scanning
  - Timing and evasion techniques
  - Service version detection
  - Firewall/IDS evasion
- **Scan Types**
  - Full port scans
  - Top 1000 ports
  - Specific protocol scans
  - Comprehensive network scans

#### Enumeration
- **OS Detection**
  - TTL analysis
  - Open port analysis
  - Response timing
  - Banner grabbing
- **Service Enumeration**
  - FTP enumeration
  - SSH enumeration
  - SMTP enumeration
  - SNMP enumeration
  - DNS enumeration (zone transfer)
  - LDAP enumeration
  - NetBIOS enumeration
  - SMB enumeration
  - SMTP User enumeration
  - NMAP NSE scripts

#### Tools
- Nmap and Zenmap
- Nessus
- OpenVAS
- Qualys
- Rapid7 InsightVM
- Shodan
- Censys

### Module 3: Vulnerability Analysis (10%)

#### Vulnerability Assessment
- **Scanning Methods**
  - Credentialed vs non-credentialed scans
  - Vulnerability scanning tools
  - Database classification
  - Common vulnerabilities (CWE/CVE)
- **Vulnerability Research**
  - CVE databases
  - CVSS scoring
  - Exploit databases
  - Vendor advisories
  - Security bulletins
- **Vulnerability Classification**
  - OWASP Top 10
  - CWE/SANS Top 25
  - CVSS ratings
  - Impact assessment

#### Tools
- Nessus Professional
- OpenVAS
- Qualys VMDR
- Rapid7 InsightVM
- Acunetix (web)
- Veracode
- BurpSuite

### Module 4: System Hacking (20%)

#### System Attacks
- **Password Attacks**
  - Password cracking tools
  - Dictionary attacks
  - Brute force attacks
  - Hybrid attacks
  - Rainbow tables
  - Salting and hashing
  - Windows password attacks
  - Linux password attacks
  - MAC password attacks
- **Privilege Escalation**
  - Windows privilege escalation
  - Linux privilege escalation
  - Kernel exploits
  - Application exploits
  - Misconfigurations
  - Sudo abuse
  - SUID exploits
  - UAC bypasses
- **Maintaining Access**
  - Backdoors
  - Rootkits
  - Web shells
  - Persistence mechanisms
  - Scheduled tasks
  - Registry modifications
  - SSH key injection

#### Exploitation
- **Exploit Development**
  - Identifying vulnerabilities
  - Creating exploits
  - Testing exploits
  - Payload generation
  - Evasion techniques
- **Metasploit Framework**
  - Payload generation
  - Exploitation
  - Post-exploitation
  - Persistence
  - Modules and scripts
- **Common Exploits**
  - Remote code execution
  - Buffer overflows
  - Format string attacks
  - SQL injection
  - Command injection

#### Tools
- Hashcat
- John the Ripper
- L0phtCrack
- Metasploit
- Burp Suite
- Mimikatz
- Keyloggers
- Rootkit tools
- mimikatz
- WinPEAS
- LinPEAS

### Module 5: Malware Threats (8%)

#### Malware Types
- **Viruses**
  - File viruses
  - Boot sector viruses
  - Polymorphic viruses
  - Metamorphic viruses
- **Worms**
  - Network propagation
  - Payload delivery
  - Examples and impacts
- **Trojans**
  - Backdoor trojans
  - Rootkit trojans
  - Remote access trojans (RAT)
  - Spyware trojans
  - Banker trojans
- **Ransomware**
  - Encryption methods
  - Payment mechanisms
  - Recovery strategies
- **Other Threats**
  - Logic bombs
  - Spyware
  - Adware
  - Keyloggers
  - Botnets

#### Malware Analysis
- **Static Analysis**
  - File type identification
  - Metadata review
  - String analysis
  - Disassembly
- **Dynamic Analysis**
  - Behavioral observation
  - Network monitoring
  - Registry monitoring
  - System calls
  - Sandbox analysis
- **Tools**
  - VirusTotal
  - Malwarebytes
  - Wireshark
  - IDA Pro
  - Ghidra
  - Process Monitor
  - Regshot

### Module 6: Session Hijacking (8%)

#### Session Management
- **Session Concepts**
  - Session tokens
  - Session IDs
  - Session lifetime
  - Session storage
  - Session prediction
- **TCP/IP Hijacking**
  - Connection prediction
  - Sequence number prediction
  - IP spoofing
  - ARP spoofing
  - RST attacks
- **Application Session Hijacking**
  - Cookie stealing
  - Session fixation
  - Session replay
  - Man-in-the-middle attacks
- **Cross-Site Request Forgery (CSRF)**
  - Token validation
  - SameSite cookies
  - Referrer checking

#### Tools
- Ettercap
- Cain and Abel
- Wireshark
- Burp Suite
- hping3
- Scapy
- mitmproxy

### Module 7: Wireless Networking Attacks (10%)

#### Wireless Fundamentals
- **WiFi Standards**
  - 802.11 generations
  - Frequency bands
  - Channel width
  - Data rates
  - Range and coverage
- **Wireless Security**
  - WEP (deprecated)
  - WPA/WPA2
  - WPA3
  - PSK vs Enterprise
  - RADIUS integration

#### Wireless Attacks
- **Reconnaissance**
  - Passive scanning
  - Active probing
  - SSID discovery
  - Signal strength mapping
  - AP discovery
- **Encryption Attacks**
  - WEP cracking
  - WPA/WPA2 cracking
  - Dictionary attacks
  - Rainbow tables
  - Brute force
- **Rogue AP Attacks**
  - Evil twin networks
  - SSID spoofing
  - Karma attacks
  - Captive portals
  - MITM attacks
- **Denial of Service**
  - Deauthentication attacks
  - Disassociation attacks
  - Jamming attacks
  - CTS flooding
  - Power save exploitation

#### Tools
- Aircrack-ng suite
- Wireshark
- Kismet
- Airmon-ng
- Airplay-ng
- Airdump-ng
- Airbase-ng
- hcxdumptool
- hashcat

### Module 8: Mobile Platform Hacking (7%)

#### Mobile Security
- **iOS Security**
  - App sandboxing
  - Code signing
  - Keychain
  - Vulnerabilities
  - Jailbreaking
- **Android Security**
  - Permission model
  - App sandboxing
  - Rooting
  - Vulnerabilities
  - Malware
- **Mobile Threats**
  - Insecure data storage
  - Insecure communication
  - Insecure authentication
  - Reverse engineering
  - Spyware

#### Tools
- Frida
- Burp Mobile
- Androguard
- Xposed
- Cydia
- APK tools

### Module 9: IoT & Embedded Systems (5%)

#### IoT Security
- **IoT Concepts**
  - Device types
  - Communication protocols
  - Firmware
  - Updates
- **IoT Threats**
  - Insecure design
  - Lack of encryption
  - Default credentials
  - Firmware extraction
  - Reverse engineering
- **SCADA/ICS**
  - Industrial systems
  - Control systems
  - Safety implications
  - Unique threats

#### Tools
- Shodan
- Wireshark
- Firmware analysis tools
- MQTT clients
- CoAP tools

### Module 10: Cloud Computing Security (5%)

#### Cloud Concepts
- **Cloud Models**
  - IaaS security
  - PaaS security
  - SaaS security
- **Cloud Threats**
  - Misconfigurations
  - Insecure APIs
  - Privilege escalation
  - Data breaches
- **Cloud Reconnaissance**
  - Service discovery
  - Configuration testing
  - Bucket enumeration
  - Metadata gathering

#### Tools
- CloudMapper
- ScoutSuite
- Prowler
- S3 bucket enumeration tools
- Cloud-specific frameworks

### Module 11: Cryptography (5%)

#### Cryptographic Concepts
- **Encryption**
  - Symmetric algorithms
  - Asymmetric algorithms
  - Key management
  - Implementation flaws
- **Hash Functions**
  - MD5, SHA family
  - Rainbow tables
  - Collision attacks
  - Salting
- **Digital Signatures**
  - PKI concepts
  - Certificate validation
  - Signature verification
- **Cryptanalysis**
  - Frequency analysis
  - Statistical analysis
  - Chosen plaintext attacks
  - Side-channel attacks

#### Tools
- OpenSSL
- GnuPG
- Hashcat
- John the Ripper
- CyberChef

### Module 12: Penetration Testing (5%)

#### Penetration Testing Process
- **Planning**
  - Scope definition
  - Rules of engagement
  - Objectives
  - Timeline
- **Reconnaissance**
  - Information gathering
  - Target identification
  - Vulnerability research
- **Exploitation**
  - Vulnerability confirmation
  - Exploit development
  - Payload delivery
  - Access maintenance
- **Reporting**
  - Findings documentation
  - Risk ratings
  - Recommendations
  - Remediation guidance
- **Ethics & Legal**
  - Authorization documentation
  - Legal compliance
  - Professional ethics
  - Responsible disclosure

---

## Hands-On Lab Environment

### Recommended Labs
- **HackTheBox** (online vulnerable machines)
- **TryHackMe** (guided hacking challenges)
- **OWASP WebGoat** (web security)
- **Metasploitable** (intentionally vulnerable Linux)
- **bWAPP** (web application security)
- **Juice Shop** (web app vulnerabilities)
- **DVWA** (Damn Vulnerable Web Application)

### Hardware Setup
- Virtual machines for lab environment
- Multiple Linux distributions
- Windows systems
- Network isolation
- Backup systems

---

## Study Resources

### Official Materials
- EC-Council CEH Study Materials
- Official CEH v12 Course
- Exam Study Guides
- Practice Labs and Exercises

### Recommended Providers
- Udemy CEH courses
- Pluralsight
- LinkedIn Learning
- YouTube (John Hammond, ippsec)
- Hack The Box
- TryHackMe

### Practice Tests
- Official EC-Council practice exams
- Boson ExamSim
- Udemy practice exams
- ExamTopics

---

## Certification Validity & Renewal

### Validity Period
- **Initial Certification:** 3 years
- **Renewal Options:**
  - Pass new CEH exam
  - Earn higher EC-Council certification
  - Complete continuing education

---

## Career Paths

### Job Titles
- Penetration Tester
- Security Auditor
- Ethical Hacker
- Vulnerability Assessor
- Security Consultant

### Salary Range (2025-2026)
$70,000 - $120,000+ USD annually

### Next Certifications
- OSCP (Offensive Security)
- CISSP
- CCNP Security
- GIAC certifications (GPEN, GWAPT)

---

## Exam Tips

1. **4-Hour Exam:** Pace yourself (1.9 minutes per question)
2. **Flag Questions:** Mark and return to difficult ones
3. **Read Carefully:** Scenario-based questions need attention
4. **Hands-On Practice:** Extensive lab work is essential
5. **Trust Your Knowledge:** You've prepared

---

## 2025-2026 Updates

- **Cloud Security:** Enhanced cloud penetration testing
- **Mobile:** Updated Android/iOS hacking techniques
- **Zero Trust:** Testing zero trust implementations
- **AI/ML:** Emerging AI/ML security concerns
- **5G:** 5G security testing basics

---

**Last Updated:** 2025-2026
**Difficulty Level:** ⭐⭐⭐⭐ (Advanced)
**Recommended for:** Penetration testers, security professionals
**Prerequisites:** 2+ years security experience or equivalent
