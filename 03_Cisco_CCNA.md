# Cisco CCNA Certification Guide (2025-2026)

## Overview
Cisco CCNA (Cisco Certified Network Associate) is a professional-level networking certification validating the ability to install, configure, operate, and troubleshoot Cisco networks. It covers routing, switching, security, and automation.

**Certification Code:** 200-301

---

## Duration & Study Timeline
- **Recommended Study Duration:** 4-6 months
- **Study Hours Required:** 300-400 hours
- **Hands-On Lab Time:** 100-150 hours
- **Exam Preparation Time:** 2-4 weeks

---

## Exam Details

### Exam Duration
- **Total Duration:** 120 minutes
- **Total Questions:** 60-70 questions
- **Question Format:** Multiple choice, drag-and-drop, testlet, simulation

### Exam Structure
- **Passing Score:** 825/1000
- **Score Range:** 300-1000
- **Difficulty Level:** Professional

### Exam Fee (2025-2026)
- **Exam Fee:** $330 USD
- **Retake Fee:** $330 USD
- **Bundle Packages:** Available from authorized Cisco Learning Network providers
- **Pearson VUE Testing:** Available worldwide

---

## Complete Syllabus & Topics

### Domain 1: Network Fundamentals (20%)

#### Network Models
- **OSI Reference Model**
  - All 7 layers in detail
  - Data flow and encapsulation
  - Layer-specific concepts
- **TCP/IP Model**
  - Protocol interactions
  - Comparison with OSI
  - Modern Internet model
- **Network Components**
  - Hosts and end devices
  - Network devices (routers, switches)
  - Network media
  - Connection types

#### Network Addressing
- **IPv4 Addressing**
  - Address structure
  - Classless Interdomain Routing (CIDR)
  - Subnet masks and subnetting
  - Variable Length Subnet Masks (VLSM)
  - Supernetting
  - DHCP protocol
  - NAT and PAT
- **IPv6 Addressing**
  - IPv6 address format
  - IPv6 prefix notation
  - Address types (unicast, multicast, anycast)
  - Link-local addresses
  - Global unicast addresses
  - IPv6 DHCP
  - Dual-stack networking
  - Tunneling between IPv4 and IPv6

#### Network Protocols
- **TCP and UDP**
  - Segment structure
  - Connection management
  - Reliability and ordering
  - Port numbers
  - Application layer protocols
- **ICMP**
  - Echo request and reply
  - Destination unreachable messages
  - Time exceeded messages
- **DNS**
  - Name resolution process
  - Recursive and iterative queries
  - Record types (A, AAAA, MX, CNAME, NS)
  - DNS servers and zones

#### Cisco Devices
- **Routers**
  - Router hardware components
  - Flash, RAM, NVRAM storage
  - Boot process
  - Configuration registers
- **Switches**
  - Switch hardware
  - Line cards and modules
  - Management interfaces
  - Port density
- **Other Devices**
  - Firewalls and security appliances
  - Wireless access points
  - Network management platforms

### Domain 2: Network Access (20%)

#### Ethernet
- **Ethernet Standards**
  - 10BASE-T
  - 100BASE-TX
  - 1000BASE-T (Gigabit)
  - 10GBASE-T
  - PoE (Power over Ethernet)
  - Link aggregation
- **MAC Addressing**
  - MAC address structure
  - Broadcast and multicast addresses
  - MAC address tables
  - Address resolution protocol (ARP)
  - Gratuitous ARP

#### VLANs
- **VLAN Fundamentals**
  - VLAN concept and benefits
  - VLAN numbering (1-4094)
  - VLAN trunk protocol (VTP)
  - VLAN configuration
- **VLAN Types**
  - Management VLANs
  - Data VLANs
  - Voice VLANs
  - Access VLANs
- **Inter-VLAN Routing**
  - Router-on-a-stick (ROAS)
  - Layer 3 switches
  - VLAN interface configuration
  - Routing between VLANs

#### Spanning Tree Protocol (STP)
- **STP Fundamentals**
  - Bridge ID and priority
  - Root bridge election
  - Root port and designated port
  - Port states
  - BPDU (Bridge Protocol Data Unit)
- **STP Variations**
  - Rapid Spanning Tree Protocol (RSTP)
  - Multiple Spanning Tree Protocol (MSTP)
  - Per-VLAN Spanning Tree Plus (PVST+)
  - BPDU guard and root guard
  - Port fast and BPDU filter

#### Switch Configuration
- **Basic Switch Commands**
  - Accessing CLI
  - Configuration modes
  - Interface configuration
  - IP address assignment
  - Port security basics
- **Switch Management**
  - Console and Telnet access
  - SSH configuration
  - SNMP configuration
  - Syslog configuration
  - NTP synchronization

#### Wireless Networking
- **Wireless Fundamentals**
  - Wireless standards (802.11a/b/g/n/ac/ax)
  - Frequency bands (2.4 GHz, 5 GHz, 6 GHz)
  - SSID (Service Set Identifier)
  - Channel planning
- **Wireless Security**
  - Open authentication
  - WEP (Wired Equivalent Privacy) - deprecated
  - WPA (WiFi Protected Access)
  - WPA2 and WPA3
  - PSK vs Enterprise authentication
  - RADIUS integration
- **Wireless Infrastructure**
  - Lightweight Access Points (LAP)
  - Wireless LAN Controller (WLC)
  - Mesh networks
  - Roaming and handoff
  - Band steering and air time fairness

### Domain 3: IP Connectivity (25%)

#### Routing Fundamentals
- **Routing Concepts**
  - Routing table structure
  - Next hop forwarding
  - Default routes
  - Static vs dynamic routing
  - Administrative distance
  - Metric types
- **Router Configuration**
  - Enabling interfaces
  - Assigning IP addresses
  - Interface configuration
  - Router operational status

#### Static Routing
- **Static Routes**
  - Configuring static routes
  - Default routes
  - Summary static routes
  - Floating static routes
  - Static route verification
  - Troubleshooting static routes

#### Dynamic Routing - OSPF
- **OSPF Fundamentals**
  - OSPF areas and types
  - Link-state routing
  - Shortest path first (SPF) algorithm
  - OSPF costs and metrics
  - Hello and dead intervals
  - Router ID election
- **OSPF Configuration**
  - Process ID and area assignment
  - Network statements
  - Interface-specific configuration
  - Router priority
  - Passive interfaces
- **OSPF Neighbors and Adjacencies**
  - Neighbor discovery
  - Adjacency formation
  - DR and BDR election
  - OSPF packet types
- **OSPF Verification & Troubleshooting**
  - show commands
  - Debugging capabilities
  - Common issues and resolution

#### Dynamic Routing - EIGRP
- **EIGRP Fundamentals**
  - Hybrid routing protocol characteristics
  - EIGRP metrics and K values
  - Feasible successor (FS)
  - Reported distance and feasible distance
  - DUAL algorithm
- **EIGRP Configuration**
  - Autonomous system (AS) number
  - Network statements
  - Passive interfaces
  - Neighbor configuration
- **EIGRP Verification & Troubleshooting**
  - Neighbor table
  - Topology table
  - Routing table verification
  - Common EIGRP issues

#### BGP Basics
- **BGP Fundamentals**
  - Autonomous system (AS) concept
  - BGP roles (iBGP, eBGP)
  - BGP peers and sessions
  - BGP path selection
  - Well-known communities
- **BGP Configuration**
  - BGP router configuration
  - Neighbor configuration
  - Network advertisement
  - Basic route filtering

### Domain 4: IP Services (10%)

#### DHCP
- **DHCP Server Configuration**
  - DHCP pools
  - IP address lease times
  - DHCP exclusions
  - DHCP relay agents
  - DHCP options
- **DHCP Verification & Troubleshooting**
  - DHCP server status
  - Client lease information
  - DHCP conflicts and debugging

#### DNS
- **DNS Configuration**
  - DNS server configuration
  - DNS forwarding
  - Static DNS entries
  - DNS security (DNSSEC basics)
- **DNS Verification**
  - Nslookup and dig commands
  - DNS resolution troubleshooting

#### Network Address Translation (NAT)
- **NAT Concepts**
  - Inside local and global addresses
  - Outside local and global addresses
  - Static NAT
  - Dynamic NAT
  - Port Address Translation (PAT)
  - NAT overloading
- **NAT Configuration**
  - Designating inside/outside interfaces
  - Static NAT translation rules
  - Dynamic NAT pools
  - PAT configuration
  - NAT verification and troubleshooting

#### Network Time Protocol (NTP)
- **NTP Concepts**
  - Time synchronization importance
  - NTP hierarchy (stratum levels)
  - NTP modes (client, server, peer)
- **NTP Configuration**
  - NTP server configuration
  - NTP client configuration
  - NTP authentication
  - Preferred NTP servers

#### Other Services
- **Syslog**
  - Log levels and facilities
  - Syslog server configuration
  - Log analysis
- **SNMP**
  - SNMP versions (v1, v2c, v3)
  - Community strings
  - SNMP agent configuration
  - SNMP trap configuration

### Domain 5: Security Fundamentals (15%)

#### Network Security
- **Network Segmentation**
  - Demilitarized zones (DMZ)
  - VLAN-based segmentation
  - Access control lists (ACLs)
  - Firewall rules
- **Access Control Lists (ACLs)**
  - ACL fundamentals
  - Standard ACLs
  - Extended ACLs
  - Named ACLs
  - IPv6 ACLs
  - ACL placement and ordering
  - ACL configuration and verification

#### Security Protocols
- **IP Security (IPSec)**
  - IPSec overview
  - Encryption and authentication
  - IKE (Internet Key Exchange)
  - AH (Authentication Header)
  - ESP (Encapsulating Security Payload)
  - Transport and tunnel modes
- **VPN Concepts**
  - Site-to-site VPN
  - Remote access VPN
  - VPN applications
- **Other Protocols**
  - SSL/TLS
  - SSH
  - HTTPS

#### Authentication
- **Authentication Methods**
  - Local authentication
  - AAA (Authentication, Authorization, Accounting)
  - TACACS+
  - RADIUS
  - Multi-factor authentication (MFA)
  - 802.1X port-based authentication
- **Encryption**
  - Symmetric encryption
  - Asymmetric encryption
  - Hash functions
  - Digital signatures

#### Device Security
- **Device Hardening**
  - Password policies
  - Access control (console, vty, AUX)
  - Service security
  - Banner configuration
  - Encrypted communications
  - Log monitoring
- **Device Access Control**
  - Role-based access control (RBAC)
  - Privilege levels
  - Command authorization

### Domain 6: Automation & Programmability (10%)

#### Programming Fundamentals
- **Languages & Concepts**
  - Variables and data types
  - Control structures (if, loops, functions)
  - APIs and REST
  - JSON and YAML formats
  - Differences between libraries and modules

#### APIs & REST
- **API Fundamentals**
  - API concept and use
  - REST principles
  - HTTP methods (GET, POST, PUT, DELETE)
  - Request/response structure
- **Cisco APIs**
  - Cisco DNA Center API
  - Cisco Catalyst Center
  - NETCONF and YANG
  - Cisco CLI analyzer

#### Python Basics
- **Python for Networking**
  - Basic Python syntax
  - Functions and modules
  - File handling
  - Error handling
  - Libraries (requests, paramiko)
  - Network automation scripts

#### Network Automation
- **Automation Platforms**
  - Ansible basics
  - Terraform basics
  - Configuration management
- **Programmable Network Devices**
  - Network management protocols
  - Device APIs
  - Scripting device interactions

---

## Advanced Topics (2025-2026)

### Software-Defined Networking (SDN)
- **SD-WAN Concepts**
  - Compared to traditional WAN
  - Centralized control
  - Path selection
  - Cloud connectivity
- **SD-Access**
  - Network programmability
  - Policy-driven networking
  - Zero Trust security

### Cloud Connectivity
- **Cloud Integration**
  - Direct cloud connections
  - Hybrid cloud networking
  - Multi-cloud strategies
  - Cloud security groups

### Network Analytics
- **Telemetry & Analytics**
  - Model-Driven Telemetry (MDT)
  - Flow data analysis
  - Network performance monitoring
  - Anomaly detection

### IoT & Edge
- **IoT Concepts**
  - IoT protocols overview
  - Edge computing basics
  - IoT security considerations
  - Bandwidth optimization

---

## Hands-On Labs & Practical Skills

### Lab Platforms
1. **Cisco Packet Tracer** (Recommended)
   - Free network simulation
   - Interactive labs
   - Topology building
   - Basic routing/switching practice

2. **GNS3**
   - Real Cisco images
   - Complex network simulations
   - Advanced configurations
   - Lab sharing and collaboration

3. **Cisco DevNet**
   - API exploration
   - Automation labs
   - Real device access
   - Hands-on practice

### Required Practical Scenarios
1. **Network Design & Implementation**
   - Creating multi-VLAN networks
   - Implementing inter-VLAN routing
   - Configuring dynamic routing (OSPF/EIGRP)
   - Setting up static routes
   - Implementing ACLs

2. **Network Security**
   - Configuring static NAT/PAT
   - Implementing ACL security
   - VPN configuration basics
   - Device hardening

3. **Network Services**
   - DHCP server configuration
   - DNS configuration
   - NTP synchronization
   - Syslog setup

4. **Troubleshooting**
   - Connectivity issues
   - Routing problems
   - VLAN configuration issues
   - Interface problems
   - Address conflicts

5. **Wireless Networking**
   - Access point configuration
   - SSID and authentication setup
   - Roaming configuration
   - Security implementation

6. **Automation**
   - Writing basic Python scripts
   - Using Ansible for device configuration
   - REST API calls
   - NETCONF basics

---

## Study Resources & Materials

### Official Cisco Resources
- Cisco Learning Network
- CCNA 200-301 Official Cert Guide (Odom)
- Cisco DevNet Learning
- NetAcad (for some free courses)

### Recommended Study Platforms
- Pluralsight
- LinkedIn Learning
- Udemy
- A Cloud Guru (Linux Academy)
- Professor Messer (YouTube - basics)
- David Bombal (YouTube - advanced)
- John Hammond Labs

### Practice Exams
- Boson ExamSim
- Pearson VUE Exam Practice
- Official Cisco Learning Network practice exams
- Examtopics (community-driven)

### Hands-On Lab Resources
- Cisco Packet Tracer (free with NetAcad)
- GNS3 (free or paid)
- EVE-NG (free emulation)
- Network simulator software

---

## Certification Validity & Renewal

### Validity Period
- **CCNA Certification:** 3 years from passing date
- **Recertification Methods:**
  - Pass new CCNA exam
  - Pass any Cisco CCNP exam
  - Complete Cisco Continuing Learning Subscription (CLC)

### Cisco Career Certifications (CLC)
- **Option:** Pay annual or monthly subscription
- **Renewal:** Automatic if subscription active
- **Benefits:** Online learning and continuing education
- **Cost:** Varies ($300-500 annually)

---

## Career Paths After CCNA
- **Job Titles:**
  - Network Administrator
  - Network Engineer
  - Junior Network Architect
  - Systems Engineer
  - Network Support Engineer
  - Infrastructure Engineer
  - Cloud Network Engineer

- **Salary Range (2025-2026):** $60,000 - $90,000 USD annually

- **Next Certifications:**
  - Cisco CCNP (Enterprise/Security/Collaboration/Service Provider)
  - Cisco Certified DevNet Associate (automation path)
  - Cloud certifications (AWS, Azure)
  - Specialization certifications

---

## Exam Tips & Strategy

1. **Time Management:** ~100 seconds per question
2. **Read Carefully:** CCNA questions have multiple correct-sounding answers
3. **Flag & Review:** Mark difficult questions for later
4. **Simulations First:** Complete simulation questions first if comfortable
5. **Elimination:** Remove obviously wrong answers
6. **Stay Calm:** Don't panic on unfamiliar questions
7. **Review:** Use remaining time to review flagged questions
8. **Don't Overthink:** Trust your preparation and training

---

## Common Mistakes to Avoid

1. ❌ Insufficient hands-on lab time
2. ❌ Memorizing without understanding concepts
3. ❌ Skipping subnetting practice
4. ❌ Ignoring routing protocols depth
5. ❌ Not understanding packet flow
6. ❌ Rushing through practice exams
7. ❌ Poor time management during exam
8. ❌ Not reviewing weak areas sufficiently

---

## 2025-2026 Updates & Changes

- **Enhanced Automation:** Increased focus on Python and network APIs
- **Cloud Integration:** Greater emphasis on cloud networking
- **SD-WAN:** Expanded software-defined networking content
- **Security Updates:** Enhanced security practices and zero-trust concepts
- **IPv6 Expansion:** More comprehensive IPv6 coverage
- **New Tools:** Updated lab environments and modern networking practices

---

## Contact & Resources

- **Cisco Learning Network:** https://learningnetwork.cisco.com
- **Cisco Career Certifications:** https://www.cisco.com/c/en/us/training-events/training-certifications/certifications.html
- **Cisco DevNet:** https://developer.cisco.com
- **Support Forum:** Cisco Learning Network Community
- **Exam Registration:** Pearson VUE (https://www.pearsonvue.com)

---

**Last Updated:** 2025-2026
**Certification Difficulty Level:** ⭐⭐⭐ (Professional)
**Recommended for:** Network engineers, system administrators, infrastructure specialists
**Time to Proficiency:** 4-6 months of study
