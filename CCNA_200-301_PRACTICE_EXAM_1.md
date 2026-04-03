# CCNA 200-301 PRACTICE EXAM 1
## Complete Exam Simulation | 70 Questions | 120 Minutes
### Real-World Difficulty Level

---

## EXAM RULES
- **Time Limit:** 120 minutes
- **Passing Score:** 750-850 out of 1000
- **Question Types:** Multiple Choice, Multiple Select, Drag & Drop, Scenario-Based
- **Instructions:** Answer all questions. Mark uncertain ones and review at end.

---

## SECTION A: NETWORK FUNDAMENTALS (Questions 1-10)

### Question 1: OSI Model Layer Function
A network technician is troubleshooting a network issue where users cannot communicate between subnets even though all physical connections are intact and all devices have IP addresses. At which OSI layer should the technician focus the initial investigation?

A) Layer 1 - Physical
B) Layer 2 - Data Link
C) Layer 3 - Network
D) Layer 4 - Transport

**YOUR ANSWER: ___**

---

### Question 2: TCP/IP Model (Multiple Select)
Which of the following are characteristics of the TCP/IP model? (Select 2)

A) It has 7 layers
B) It combines multiple OSI layers into single layers
C) It is the model used in real-world networking
D) It requires MAC addresses for every communication
E) Application layer includes HTTP, SMTP, and DNS

**YOUR ANSWERS: ___ , ___**

---

### Question 3: Packet Structure
You are analyzing a packet capture and need to identify where the source IP address is located. Which layer of the packet contains this information?

A) Ethernet header (MAC addresses)
B) IP header (IP addresses)
C) TCP/UDP header (port numbers)
D) Application layer (data)

**YOUR ANSWER: ___**

---

### Question 4: Encapsulation Process (Drag & Drop)
Match the encapsulation layer with its protocol data unit (PDU) name:

Layer 3 → __________
Layer 4 → __________
Layer 2 → __________
Layer 1 → __________

Options: Segment, Frame, Packet, Bits

**YOUR ANSWERS:**
- Layer 3 → ___
- Layer 4 → ___
- Layer 2 → ___
- Layer 1 → ___

---

### Question 5: Network Types
A company has three office buildings in the same city connected together. What type of network is this?

A) LAN (Local Area Network)
B) WAN (Wide Area Network)
C) MAN (Metropolitan Area Network)
D) PAN (Personal Area Network)

**YOUR ANSWER: ___**

---

### Question 6: IPv4 Address Classes
You are assigned the IP address 172.16.5.10. Which class is this address?

A) Class A
B) Class B
C) Class C
D) Class D

**YOUR ANSWER: ___**

---

### Question 7: Subnet Mask Purpose
What is the primary purpose of a subnet mask?

A) Encrypts data traveling on the network
B) Determines which portion of an IP address is the network and which is the host
C) Identifies the MAC address of a device
D) Blocks unauthorized users from accessing the network

**YOUR ANSWER: ___**

---

### Question 8: CIDR Notation
An administrator configures a network with the address 192.168.1.0/24. How many usable host addresses does this subnet have?

A) 256
B) 255
C) 254
D) 128

**YOUR ANSWER: ___**

---

### Question 9: IPv6 Addressing
Which of the following is a valid IPv6 address format?

A) 2001:0db8:85a3:0000:0000:8a2e:0370:7334
B) 192.168.1.1
C) 11111111.11111111.11111111.0
D) 2001:db8:85a3::8a2e:370:7334:1111:2222

**YOUR ANSWER: ___**

---

### Question 10: Network Device Function
A network device receives a frame on one interface and must forward it out another interface based on the MAC address in the frame. What is this device?

A) Router
B) Switch
C) Firewall
D) Hub

**YOUR ANSWER: ___**

---

## SECTION B: ETHERNET & SWITCHING (Questions 11-20)

### Question 11: VLAN Purpose
You need to segment a network so that the Sales department and Engineering department are isolated from each other but connected to the same physical switch. What technology should you use?

A) Subnetting only
B) VLANs
C) Access Control Lists (ACLs)
D) Virtual Private Network (VPN)

**YOUR ANSWER: ___**

---

### Question 12: VLAN Tagging (Multiple Select)
Which statements are true about VLAN tagging? (Select 2)

A) 802.1Q is the standard for VLAN tagging
B) Tagged frames include a 4-byte VLAN header
C) Access ports can only belong to one VLAN
D) Trunk ports carry traffic for multiple VLANs
E) Untagged frames automatically belong to VLAN 999

**YOUR ANSWERS: ___ , ___**

---

### Question 13: Spanning Tree Protocol (STP)
In a switched network with redundant paths, why is Spanning Tree Protocol important?

A) To increase bandwidth utilization
B) To prevent MAC address flooding
C) To prevent bridge loops and broadcast storms
D) To encrypt data between switches

**YOUR ANSWER: ___**

---

### Question 14: Port States in STP
A switch port transitions through several states before actively forwarding frames. Which of the following is NOT a standard STP port state?

A) Blocking
B) Listening
C) Learning
D) Routing

**YOUR ANSWER: ___**

---

### Question 15: Root Bridge Election
In a switched network, multiple switches are connected together using STP. How is the root bridge determined?

A) The switch with the highest MAC address
B) The switch with the lowest Bridge ID (priority + MAC)
C) The switch with the most ports
D) The first switch powered on

**YOUR ANSWER: ___**

---

### Question 16: RSTP Improvements (Multiple Select)
RSTP (Rapid STP) improves upon traditional STP in several ways. Which are accurate? (Select 2)

A) RSTP uses a different root bridge election mechanism
B) RSTP converges much faster than STP (in milliseconds vs seconds)
C) RSTP adds two new port roles: Alternate and Backup
D) RSTP eliminates the need for portfast
E) RSTP uses the same timers as legacy STP

**YOUR ANSWERS: ___ , ___**

---

### Question 17: Port Security
A network administrator wants to prevent unauthorized devices from connecting to a switch port. Which feature should be configured?

A) VTP (VLAN Trunking Protocol)
B) Port Security
C) SSH (Secure Shell)
D) Port ACLs

**YOUR ANSWER: ___**

---

### Question 18: MAC Address Learning
A switch learns MAC addresses by examining:

A) The destination MAC address in incoming frames
B) The source MAC address in incoming frames
C) The source IP address in incoming packets
D) The VLAN tag in frame headers

**YOUR ANSWER: ___**

---

### Question 19: Switch Port Configuration (Scenario)
You need to connect a router to a switch that has multiple VLANs. The router needs to be able to handle traffic for all VLANs. What type of connection should you configure?

A) Access port in VLAN 1
B) Trunk port
C) Port channel
D) Routed port

**YOUR ANSWER: ___**

---

### Question 20: Layer 2 vs Layer 3 (Scenario)
A company has two switches in different buildings connected by fiber optic cable. Devices in Building A need to communicate with devices in Building B, but they are on different subnets. What is needed for this communication?

A) A longer VLAN trunk
B) A Layer 3 device (router) to route between subnets
C) Spanning Tree Protocol reconfiguration
D) A more powerful switch

**YOUR ANSWER: ___**

---

## SECTION C: IP ROUTING (Questions 21-35)

### Question 21: Static vs Dynamic Routing
An administrator must choose between static and dynamic routing. Which statement best describes when static routing is appropriate?

A) Always use static routing for larger networks
B) Static routing is suitable for small networks with few routes
C) Dynamic routing should never be used
D) Static routing is more efficient than dynamic routing

**YOUR ANSWER: ___**

---

### Question 22: Default Route
In a routing table, what is the purpose of a default route (0.0.0.0/0)?

A) To route traffic to unmatched destinations
B) To enable DHCP on the router
C) To block all traffic by default
D) To configure the router's hostname

**YOUR ANSWER: ___**

---

### Question 23: Routing Table Lookup
A packet arrives at a router with destination IP 192.168.1.50. The router's routing table contains:
- 192.168.1.0/24 via 10.0.0.1
- 192.168.0.0/16 via 10.0.0.2
- 0.0.0.0/0 via 10.0.0.3

Which route will be used?

A) 192.168.1.0/24 via 10.0.0.1
B) 192.168.0.0/16 via 10.0.0.2
C) 0.0.0.0/0 via 10.0.0.3
D) The router will drop the packet

**YOUR ANSWER: ___**

---

### Question 24: Administrative Distance
RIP has an administrative distance of 120, while OSPF has 110. If both are running and have routes to the same destination, which will be preferred?

A) RIP because it's simpler
B) OSPF because it has a lower AD
C) RIP because it has a higher AD
D) They'll load balance equally

**YOUR ANSWER: ___**

---

### Question 25: EIGRP Characteristics (Multiple Select)
Which are characteristics of EIGRP? (Select 3)

A) It's a distance-vector routing protocol
B) It's a hybrid routing protocol
C) It uses the DUAL algorithm
D) It has a maximum hop count of 15
E) It supports unequal cost load balancing

**YOUR ANSWERS: ___ , ___ , ___**

---

### Question 26: OSPF Areas (Scenario)
A large enterprise network is divided into multiple OSPF areas. What is the primary benefit of using multiple areas?

A) Reduces CPU and memory usage on routers
B) Increases network speed
C) Eliminates the need for a backbone area
D) Allows routers to use different IP addressing schemes

**YOUR ANSWER: ___**

---

### Question 27: OSPF Timers
An OSPF router sends Hello packets every 10 seconds. What is the default Dead Interval?

A) 10 seconds
B) 20 seconds
C) 30 seconds
D) 40 seconds

**YOUR ANSWER: ___**

---

### Question 28: BGP Basics
BGP is used primarily for which type of routing?

A) Interior routing within a single organization
B) Exterior routing between autonomous systems
C) Local routing within a VLAN
D) Dynamic routing on small networks

**YOUR ANSWER: ___**

---

### Question 29: Convergence Time
After a network link failure, EIGRP reconverges much faster than RIP. Why?

A) RIP has slower processors
B) EIGRP uses a better algorithm (DUAL) and has faster timers
C) RIP requires manual configuration after a failure
D) EIGRP supports faster network links

**YOUR ANSWER: ___**

---

### Question 30: Route Summarization (Scenario)
An administrator wants to summarize these routes into a single CIDR block:
- 192.168.0.0/24
- 192.168.1.0/24
- 192.168.2.0/24
- 192.168.3.0/24

What is the correct summary route?

A) 192.168.0.0/22
B) 192.168.0.0/23
C) 192.168.0.0/25
D) 192.168.0.0/26

**YOUR ANSWER: ___**

---

### Question 31: RIP Configuration Issue (Scenario)
A network administrator configures RIP on two routers but they don't become neighbors. The routers are directly connected. What is the most likely cause?

A) RIP version mismatch
B) The routers are too far apart
C) RIP is not supported on these routers
D) The cables need to be replaced

**YOUR ANSWER: ___**

---

### Question 32: OSPF Neighbor Requirements (Multiple Select)
For two OSPF routers to become neighbors, which must match? (Select 2)

A) Router ID
B) Area ID
C) Interface IP address
D) Hello interval
E) Maximum hop count

**YOUR ANSWERS: ___ , ___**

---

### Question 33: BGP AS Number
What is the purpose of an AS (Autonomous System) number in BGP?

A) To identify a group of networks under single administrative control
B) To encrypt BGP messages
C) To limit the number of routers in a network
D) To prevent loops in the network

**YOUR ANSWER: ___**

---

### Question 34: Route Redistribution
An administrator needs to redistribute routes learned via OSPF into EIGRP. Why might this be necessary?

A) To replace OSPF with EIGRP
B) To allow networks in different routing domains to communicate
C) To increase network security
D) To reduce bandwidth usage

**YOUR ANSWER: ___**

---

### Question 35: Passive Interface
In EIGRP, what is the effect of configuring a router interface as passive?

A) The interface is shut down
B) The interface stops sending EIGRP Hello packets but can receive traffic
C) The interface sends only Hello packets
D) The interface operates at half speed

**YOUR ANSWER: ___**

---

## SECTION D: NETWORK SECURITY & SERVICES (Questions 36-55)

### Question 36: NAT Purpose
What is the primary purpose of Network Address Translation (NAT)?

A) To encrypt network traffic
B) To translate private IP addresses to public addresses
C) To prevent ping attacks
D) To increase network bandwidth

**YOUR ANSWER: ___**

---

### Question 37: Dynamic NAT
In Dynamic NAT, how are internal private addresses translated?

A) All traffic from a private IP is translated to a single public IP
B) Each private IP is dynamically assigned a public IP from a pool
C) Private IPs are never translated
D) All traffic is blocked

**YOUR ANSWER: ___**

---

### Question 38: PAT Configuration (Scenario)
A small company has one public IP address but 50 internal devices that need internet access. Which NAT type should be used?

A) Static NAT
B) Dynamic NAT
C) Port Address Translation (PAT)
D) No NAT

**YOUR ANSWER: ___**

---

### Question 39: ACL Fundamentals
An administrator wants to block traffic from a specific subnet while allowing all other traffic. Where should the deny statement be placed in the ACL?

A) At the end of the ACL
B) At the beginning of the ACL
C) Doesn't matter, the router processes them equally
D) In a separate ACL

**YOUR ANSWER: ___**

---

### Question 40: Standard vs Extended ACL (Multiple Select)
Which statements are true about ACLs? (Select 2)

A) Standard ACLs can filter based on destination IP only
B) Extended ACLs can filter based on source IP, destination IP, and port numbers
C) Standard ACLs should be placed close to the source
D) Extended ACLs should be placed close to the destination
E) ACLs are processed from bottom to top

**YOUR ANSWERS: ___ , ___**

---

### Question 41: DHCP Function
What does DHCP provide to client devices?

A) Routing information
B) IP address, subnet mask, default gateway, and DNS servers
C) Encryption for network traffic
D) Wireless network passwords

**YOUR ANSWER: ___**

---

### Question 42: DHCP Discover Message
When a DHCP client first attempts to obtain an IP address, what type of message does it send?

A) DHCP Request
B) DHCP Offer
C) DHCP Discover
D) DHCP ACK

**YOUR ANSWER: ___**

---

### Question 43: DHCP Relay (Scenario)
A DHCP server is in Building A, but clients in Building B need DHCP addresses. Building B is connected via a router. What must be configured on the router?

A) DHCP server
B) DHCP relay agent (ip helper-address)
C) DHCP client
D) A static DHCP route

**YOUR ANSWER: ___**

---

### Question 44: DNS Resolution
A user types a URL in their browser. What is the first step in DNS resolution?

A) The user's device makes a DNS query to its configured DNS server
B) The root nameserver responds immediately
C) The browser caches the IP address
D) The ISP automatically provides the IP

**YOUR ANSWER: ___**

---

### Question 45: DNS Record Types (Multiple Select)
Which DNS record types are used to map hostnames to IP addresses? (Select 2)

A) MX record
B) A record
C) AAAA record
D) CNAME record
E) SOA record

**YOUR ANSWERS: ___ , ___**

---

### Question 46: SSH vs Telnet
Why should SSH be used instead of Telnet for remote device management?

A) SSH is faster
B) SSH encrypts the connection while Telnet does not
C) Telnet is not supported on modern devices
D) SSH doesn't require authentication

**YOUR ANSWER: ___**

---

### Question 47: SNMP Function
What is SNMP used for in network management?

A) Encrypting network traffic
B) Monitoring and managing network devices
C) Routing data between networks
D) Assigning IP addresses

**YOUR ANSWER: ___**

---

### Question 48: Syslog Purpose
A network administrator wants to centrally collect log messages from multiple routers. What technology should be used?

A) SNMP
B) Syslog
C) SSH
D) Telnet

**YOUR ANSWER: ___**

---

### Question 49: NTP Function
What is the primary purpose of Network Time Protocol (NTP)?

A) To translate IP addresses
B) To synchronize time across devices in a network
C) To secure network connections
D) To distribute DHCP addresses

**YOUR ANSWER: ___**

---

### Question 50: Firewall Types (Multiple Select)
Which are types of firewalls? (Select 2)

A) Stateless firewall
B) Dynamic firewall
C) Stateful firewall
D) Encrypted firewall
E) Proxy firewall

**YOUR ANSWERS: ___ , ___**

---

### Question 51: IDS vs IPS
What is the key difference between an Intrusion Detection System (IDS) and an Intrusion Prevention System (IPS)?

A) IDS is faster
B) IDS detects attacks while IPS can also block them
C) IPS is only for wireless networks
D) They are the same thing

**YOUR ANSWER: ___**

---

### Question 52: VPN Purpose
What does a VPN (Virtual Private Network) provide?

A) Higher network bandwidth
B) Encrypted secure connection over an untrusted network
C) Local network connectivity only
D) Faster internet speeds

**YOUR ANSWER: ___**

---

### Question 53: IPSec Protocols (Scenario)
An administrator needs to encrypt IP traffic between two routers. Which IPSec protocol should be used for encryption?

A) IKE (Internet Key Exchange)
B) AH (Authentication Header)
C) ESP (Encapsulating Security Payload)
D) HMAC (Hash-based Message Authentication Code)

**YOUR ANSWER: ___**

---

### Question 54: GRE Tunneling
What does Generic Routing Encapsulation (GRE) provide?

A) Encryption for network traffic
B) A method to encapsulate protocols inside IP
C) DHCP address distribution
D) DNS name resolution

**YOUR ANSWER: ___**

---

### Question 55: Wireless Security
Which wireless security protocol is most secure?

A) WEP
B) WPA
C) WPA2
D) WPA3

**YOUR ANSWER: ___**

---

## SECTION E: ADVANCED TOPICS (Questions 56-70)

### Question 56: QoS Purpose
What is the main purpose of Quality of Service (QoS) in networking?

A) To block unwanted traffic
B) To manage and prioritize traffic based on requirements
C) To increase bandwidth
D) To encrypt all traffic

**YOUR ANSWER: ___**

---

### Question 57: QoS Marking
Before traffic can be prioritized in QoS, it must be:

A) Blocked
B) Encrypted
C) Classified and marked
D) Routed

**YOUR ANSWER: ___**

---

### Question 58: VLAN Routing Configuration (Scenario)
An administrator creates a new VLAN 10 on a switch but devices in this VLAN cannot reach devices in other VLANs. What is needed to enable inter-VLAN routing?

A) Reconfigure the switch ports
B) A Layer 3 device (router or Layer 3 switch) to route between VLANs
C) Create another VLAN
D) Enable STP

**YOUR ANSWER: ___**

---

### Question 59: Router-on-a-Stick Configuration (Multiple Select)
Which are correct when configuring a router-on-a-stick for inter-VLAN routing? (Select 2)

A) The router port must be configured as an access port
B) The router port must be configured as a trunk port
C) Subinterfaces are created for each VLAN on the router
D) Each subinterface gets a gateway IP for its VLAN
E) The router needs to be connected with a crossover cable

**YOUR ANSWERS: ___ , ___**

---

### Question 60: Network Troubleshooting - Connectivity (Scenario)
A user reports they cannot access a server on a remote network. The local gateway is reachable. Where should troubleshooting focus next?

A) The user's computer
B) The firewall
C) The routing between networks
D) The DNS server

**YOUR ANSWER: ___**

---

### Question 61: Troubleshooting Command - Traceroute
What does the traceroute command show?

A) Only if a destination is reachable
B) The path packets take to reach a destination, hop by hop
C) All devices connected to a network
D) The speed of the network connection

**YOUR ANSWER: ___**

---

### Question 62: Protocol Analysis (Scenario)
A network administrator captures packets from a slow network connection and sees retransmissions of segments. What is likely occurring?

A) The network is congested or unreliable
B) The network is too fast
C) The firewall is blocking traffic
D) The router is misconfigured

**YOUR ANSWER: ___**

---

### Question 63: Bandwidth Utilization
An administrator needs to monitor which interfaces are consuming the most bandwidth. Which tool would be most useful?

A) Ping
B) Ipconfig
C) SNMP and NetFlow
D) Nslookup

**YOUR ANSWER: ___**

---

### Question 64: Network Design Best Practice (Scenario)
A growing company needs to redesign its network. Currently, all devices are on a single large flat network. What should be recommended?

A) Keep the flat network, just add more devices
B) Divide the network into VLANs and subnets
C) Replace all switches with hubs
D) Use only wireless connectivity

**YOUR ANSWER: ___**

---

### Question 65: High Availability (Multiple Select)
Which technologies can be used to provide high availability in a network? (Select 2)

A) Network segmentation
B) Redundant links and devices
C) VLAN configuration
D) Failover mechanisms
E) Bandwidth limiting

**YOUR ANSWERS: ___ , ___**

---

### Question 66: Scalability
Why is network scalability important?

A) To make the network smaller
B) To allow the network to grow without major redesign
C) To block growth
D) To eliminate routing

**YOUR ANSWER: ___**

---

### Question 67: Network Documentation (Scenario)
Which is the most important aspect of network documentation?

A) Making the documentation very long
B) Keeping it current and accurate for reference and troubleshooting
C) Only documenting devices, not configurations
D) Verbal documentation only

**YOUR ANSWER: ___**

---

### Question 68: Cloud vs On-Premises Networking
A company is considering cloud services. What is a networking consideration?

A) Cloud services don't require network connectivity
B) Internet bandwidth and latency requirements change
C) Traditional routing protocols won't work
D) VLANs aren't needed for cloud

**YOUR ANSWER: ___**

---

### Question 69: Security Best Practice (Multiple Select)
Which are networking security best practices? (Select 2)

A) Use a single password for all devices
B) Keep router firmware updated
C) Use default router passwords
D) Implement access control lists on routers
E) Disable all monitoring

**YOUR ANSWERS: ___ , ___**

---

### Question 70: Network Compliance
Why would a company implement network compliance policies?

A) To make the network slower
B) To meet regulatory requirements and security standards
C) Compliance is not needed
D) Only large companies need compliance

**YOUR ANSWER: ___**

---

## ANSWER KEY & EXPLANATIONS

### SECTION A: NETWORK FUNDAMENTALS

**Q1: C) Layer 3 - Network**
Explanation: If physical connections and IP addressing are correct but subnets can't communicate, the issue is at Layer 3 (Network layer). This is where routing occurs. Routers at Layer 3 are needed to forward traffic between different subnets.

**Q2: B, E**
- B is correct: TCP/IP model condenses OSI layers
- E is correct: These are Application layer protocols
- A is wrong: TCP/IP has 4-5 layers
- C is technically correct but overlaps with B
- D is wrong: IP addresses are used, not only MAC

**Q3: B) IP header**
Explanation: Source IP addresses are found in the IP header, which is the Layer 3 header of the packet. This is distinct from the Layer 2 Ethernet header (MAC addresses) and Layer 4 headers (port numbers).

**Q4 (Drag & Drop):**
- Layer 3 → Packet
- Layer 4 → Segment
- Layer 2 → Frame
- Layer 1 → Bits
Explanation: Each layer has its own PDU terminology.

**Q5: C) MAN**
Explanation: Multiple buildings in the same city is a Metropolitan Area Network (MAN). LANs are usually within a building; WANs span cities/countries.

**Q6: B) Class B**
Explanation: 172 falls in the range 128-191, which is Class B. Class A is 1-126, Class C is 192-223, Class D is multicast.

**Q7: B**
Explanation: The subnet mask determines the network and host portions of an IP address by using binary AND operations.

**Q8: C) 254**
Explanation: A /24 network has 256 total addresses (2^8). Subtract 1 for network address and 1 for broadcast address = 254 usable addresses.

**Q9: A) 2001:0db8:85a3:0000:0000:8a2e:0370:7334**
Explanation: This is a valid IPv6 address. B is IPv4. C is binary. D has too many groups.

**Q10: B) Switch**
Explanation: Switches forward frames based on MAC addresses (Layer 2). This is the definition of switching.

### SECTION B: ETHERNET & SWITCHING

**Q11: B) VLANs**
Explanation: VLANs logically separate devices on the same physical switch, providing isolation while remaining connected.

**Q12: A, D**
- A: 802.1Q is the standard for VLAN tagging ✓
- D: Trunk ports carry traffic for multiple VLANs ✓
- B: 4-byte is correct but not emphasized as much
- C: True but not specifically about tagging
- E: False, no such thing as VLAN 999 default

**Q13: C) To prevent bridge loops and broadcast storms**
Explanation: STP is designed specifically to prevent loops in switched networks which would cause broadcast storms.

**Q14: D) Routing**
Explanation: The standard STP states are Blocking, Listening, Learning, Forwarding. "Routing" is not a state.

**Q15: B) The switch with the lowest Bridge ID**
Explanation: Bridge ID combines priority (configurable) and MAC address. Lower Bridge ID becomes root.

**Q16: B, C**
- B: RSTP converges in milliseconds vs STP's seconds ✓
- C: RSTP adds Alternate and Backup port roles ✓
- A: Different election? No, same
- D: False, portfast still useful
- E: False, RSTP uses faster timers

**Q17: B) Port Security**
Explanation: Port Security restricts which MAC addresses can connect to a port.

**Q18: B) Source MAC address**
Explanation: Switches learn the source MAC of incoming frames to build the MAC address table.

**Q19: B) Trunk port**
Explanation: A trunk port carries traffic for multiple VLANs, allowing the router to access all VLAN subnets.

**Q20: B) A Layer 3 device to route between subnets**
Explanation: Devices on different subnets need a router (Layer 3) to communicate.

### SECTION C: IP ROUTING

**Q21: B**
Explanation: Static routing is appropriate for small networks with few routes. Larger networks use dynamic routing.

**Q22: A) To route traffic to unmatched destinations**
Explanation: The default route (0.0.0.0/0) is a catch-all for traffic that doesn't match any other route.

**Q23: A) 192.168.1.0/24 via 10.0.0.1**
Explanation: Longest prefix match is used. /24 is more specific than /16, so it's preferred.

**Q24: B) OSPF because it has a lower AD**
Explanation: Lower administrative distance = higher trust. OSPF (110) is preferred over RIP (120).

**Q25: B, C, E**
- B: EIGRP is a hybrid protocol ✓
- C: EIGRP uses the DUAL algorithm ✓
- E: EIGRP supports unequal cost load balancing ✓
- A: False, EIGRP is hybrid, not pure distance-vector
- D: False, EIGRP has max hop of 255

**Q26: A) Reduces CPU and memory usage**
Explanation: Multiple areas reduce the SPF calculation load on routers.

**Q27: D) 40 seconds**
Explanation: Default OSPF dead interval is 4 times the hello interval (10×4=40).

**Q28: B) Exterior routing between autonomous systems**
Explanation: BGP is used for inter-AS routing on the internet.

**Q29: B) EIGRP uses better algorithm and faster timers**
Explanation: EIGRP's DUAL algorithm is efficient and hello/dead intervals are faster.

**Q30: A) 192.168.0.0/22**
Explanation: These four consecutive /24 networks can be summarized as /22 (combines 4 /24s).

**Q31: A) RIP version mismatch**
Explanation: RIPv1 and RIPv2 don't interoperate; versions must match.

**Q32: B, D**
- B: Area ID must match ✓
- D: Hello interval must match ✓
- A: Router IDs don't need to match
- C: Interface IP doesn't need to match (different subnets okay)
- E: Maximum hop count is not an OSPF parameter

**Q33: A**
Explanation: An AS is a group of networks under a single administration.

**Q34: B) Allow different routing domains to communicate**
Explanation: Redistribution allows routes from one routing protocol to be shared with another.

**Q35: B) Stops sending Hello packets but can receive traffic**
Explanation: Passive interfaces don't form adjacencies but can be advertised in routing updates.

### SECTION D: NETWORK SECURITY & SERVICES

**Q36: B) Translate private IPs to public addresses**
Explanation: NAT's primary purpose is to conserve public IP addresses and hide internal networks.

**Q37: B) Each private IP is dynamically assigned a public IP**
Explanation: Dynamic NAT creates a many-to-many mapping from a pool of public addresses.

**Q38: C) Port Address Translation (PAT)**
Explanation: PAT maps multiple private IPs to a single public IP using different ports.

**Q39: B) At the beginning**
Explanation: ACLs are processed top-to-bottom. Deny statements should come first (most specific).

**Q40: B, D**
- B: Extended ACLs filter by source, destination, protocol, port ✓
- D: Extended ACLs should be near destination ✓
- A: Standard ACLs filter by source only
- C: Standard should be near destination (they're less specific)
- E: Top to bottom, not bottom to top

**Q41: B) IP address, subnet mask, default gateway, DNS**
Explanation: DHCP provides all necessary configuration for a host to operate on the network.

**Q42: C) DHCP Discover**
Explanation: DHCP Discover is a broadcast from client to find DHCP servers.

**Q43: B) DHCP relay agent**
Explanation: The ip helper-address command configures DHCP relay, which forwards DHCP requests.

**Q44: A) Device queries its configured DNS server**
Explanation: The DNS resolution process starts with the client making a recursive query.

**Q45: B, C**
- B: A record maps hostname to IPv4 ✓
- C: AAAA record maps hostname to IPv6 ✓
- A: MX is for mail servers
- D: CNAME is for aliases
- E: SOA is zone metadata

**Q46: B) SSH encrypts while Telnet does not**
Explanation: SSH provides secure encrypted communication; Telnet sends in plain text.

**Q47: B) Monitoring and managing devices**
Explanation: SNMP collects information from network devices for monitoring.

**Q48: B) Syslog**
Explanation: Syslog is designed for centralized log collection from network devices.

**Q49: B) Synchronize time across devices**
Explanation: NTP ensures consistent time across all network devices (important for logs, certificates).

**Q50: A, C, E**
- A: Stateless firewalls don't track connections ✓
- C: Stateful firewalls track connection states ✓
- E: Proxy firewalls filter at application layer ✓
- B: No such thing
- D: Firewalls aren't classified as "encrypted"

**Q51: B) IDS detects, IPS can block**
Explanation: IDS is passive (detects only); IPS can actively prevent attacks.

**Q52: B) Encrypted secure connection**
Explanation: VPN provides confidentiality and security over untrusted networks.

**Q53: C) ESP (Encapsulating Security Payload)**
Explanation: ESP provides encryption in IPSec. AH provides authentication only.

**Q54: B) Encapsulate protocols in IP**
Explanation: GRE is a tunneling protocol that encapsulates one protocol inside another.

**Q55: D) WPA3**
Explanation: WPA3 is the latest standard, more secure than WPA2. WEP and WPA are outdated.

### SECTION E: ADVANCED TOPICS

**Q56: B) Manage and prioritize traffic**
Explanation: QoS ensures important traffic gets priority in congested networks.

**Q57: C) Classified and marked**
Explanation: Traffic must be identified and marked (with DSCP or similar) before QoS can act.

**Q58: B) A Layer 3 device**
Explanation: VLANs are logically separate; you need a router or Layer 3 switch to route between them.

**Q59: B, D**
- B: Port must be trunk to carry multiple VLANs ✓
- D: Each subinterface gets a gateway IP ✓
- A: Access port is wrong
- C: Not required, any cable works for routing
- E: Crossover not needed with modern devices

**Q60: C) Routing between networks**
Explanation: If local gateway is reachable but remote server is not, the problem is routing between networks.

**Q61: B) Shows path packets take, hop by hop**
Explanation: Traceroute displays each router (hop) along the path.

**Q62: A) Network is congested or unreliable**
Explanation: Retransmissions indicate packet loss or congestion.

**Q63: C) SNMP and NetFlow**
Explanation: SNMP collects device statistics; NetFlow specifically tracks traffic flows.

**Q64: B) Divide into VLANs and subnets**
Explanation: Network segmentation improves security, performance, and scalability.

**Q65: B, D**
- B: Redundant links and devices provide failover ✓
- D: Failover mechanisms enable HA ✓
- A: Segmentation is for security, not HA
- C: VLANs are for organization, not HA
- E: Bandwidth limiting reduces capacity

**Q66: B) Allow network to grow without major redesign**
Explanation: Scalability means the network can expand and accommodate growth.

**Q67: B) Keeping it current and accurate**
Explanation: Documentation must be maintained to be useful for troubleshooting.

**Q68: B) Internet bandwidth and latency requirements change**
Explanation: Cloud services require sufficient internet connectivity and may have latency concerns.

**Q69: B, D**
- B: Keep firmware updated prevents exploits ✓
- D: ACLs control traffic based on security policies ✓
- A: Same password = security risk
- C: Default passwords are security risk
- E: Monitoring is essential for security

**Q70: B) Meet regulatory requirements and security standards**
Explanation: Compliance ensures the network meets legal and security standards.

---

## EXAM SCORING GUIDE

**Total Questions:** 70
**Passing Score:** 750-850 out of 1000

**Calculate Your Score:**
- Count correct answers: _____ / 70
- Percentage: _____ %
- (Your correct answers ÷ 70 × 100)

**Performance Assessment:**
- **60+ correct (85%+):** EXCELLENT - Ready for exam
- **55-59 correct (75-85%):** GOOD - Review weak areas
- **50-54 correct (70-75%):** SATISFACTORY - More study needed
- **Below 50 correct (<70%):** NEEDS IMPROVEMENT - Significant study required

**Topics to Review Based on Performance:**
- Section A (Questions 1-10): Network Fundamentals
- Section B (Questions 11-20): Ethernet & Switching
- Section C (Questions 21-35): IP Routing
- Section D (Questions 36-55): Security & Services
- Section E (Questions 56-70): Advanced Topics

---

## ADDITIONAL STUDY TIPS

1. **Review Weak Areas:** Take note of questions you answered incorrectly and review that topic
2. **Take Multiple Exams:** Practice with at least 3-4 different exam sets
3. **Time Yourself:** Ensure you can complete 70 questions in 120 minutes
4. **Study Explanations:** Read the explanations even if you got the answer right
5. **Use Labs:** Implement scenarios from practice exams in actual networking labs
6. **Join Study Groups:** Discuss difficult questions with peers
7. **Re-test:** Take the exam again after 1-2 weeks to improve your score

---

**Good luck on your CCNA exam! This practice exam represents real-world difficulty level.**

