# AWS + Network + Security + Cloud Infrastructure
## Complete 24-Month Learning Roadmap (4 Hours Daily)

**Daily Schedule:** 2 hours morning + 2 hours evening  
**Total Duration:** 24 months  
**Target Role:** Cloud Architect / Cloud Security Engineer  
**Expected Salary:** $150,000 - $250,000+

---

## 📌 OVERVIEW

You're committing 4 hours daily for 24 months. That's approximately **480 hours per year** or **960 hours total**. This is a professional-grade curriculum covering networking fundamentals → cloud infrastructure → security → advanced specialization.

**Time Breakdown:**
- 40% Theoretical learning (YouTube, courses)
- 60% Hands-on practice (AWS labs, building projects)

---

# PHASE 1: FOUNDATION (Months 1-6)
*Build strong networking fundamentals and learn AWS basics*

## Month 1-2: Networking Fundamentals
### Topic 1: OSI Model & TCP/IP Stack (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (10-15 days) |
| **Concepts** | OSI 7 layers, TCP/UDP, IP addressing, packet flow, network protocols |
| **YouTube Resources** | [Prof Messer Network+](https://www.youtube.com/playlist?list=PLG49S3nxzAnlCJiIcsVr_Lc7kx3i8QY7e) - Complete series (15 hours) |
| **Practical Exercise** | Create OSI layer chart, identify protocols at each layer, trace packet flow |
| **Hands-on Lab** | Use Wireshark to capture and analyze packets in real traffic |
| **Key Topics** | Layers 1-7, encapsulation, de-encapsulation, protocol headers |
| **Time Allocation** | Morning: 2 hrs theory, Evening: 2 hrs practice |

### Topic 2: Subnetting & IPv4/IPv6 (16 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 16 hours (10 days) |
| **Concepts** | CIDR notation, subnet masks, network addressing, IPv6 format |
| **YouTube Resources** | [NetworkChuck Subnetting](https://www.youtube.com/watch?v=xpWffryzQaU) - 4 hours |
| **Additional Resources** | [Prof Messer Subnetting](https://www.youtube.com/watch?v=BWZ-MHIhqjM) - 6 hours |
| **Practical Exercise** | Calculate subnets for various scenarios (8, 16, 32 host networks) |
| **Hands-on Lab** | Design IP scheme for fictional 3-office company network |
| **Key Topics** | Network/broadcast addresses, VLSM, IPv6 addressing |
| **Tools** | IP calculator apps, subnet mask generator |

### Topic 3: DNS, HTTP/HTTPS & Ports (12 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 12 hours (8 days) |
| **Concepts** | DNS resolution, HTTPS/TLS, port numbers, DNS records (A, CNAME, MX) |
| **YouTube Resources** | [DNS Explained](https://www.youtube.com/watch?v=DTQF9B-gTKs) - 2 hours |
| **Additional** | [HTTPs in 100 seconds](https://www.youtube.com/watch?v=kBzbKUirOFk) |
| **Practical Exercise** | Trace DNS lookups, understand DNS record types |
| **Hands-on Lab** | Configure DNS records, test HTTPS certificate validation |
| **Key Topics** | DNS hierarchy, recursive/iterative queries, TLS handshake, port ranges |
| **Tools** | dig, nslookup, OpenSSL |

---

## Month 3-4: Linux & Cloud Fundamentals

### Topic 4: Linux Command Line (24 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 24 hours (15 days) |
| **Concepts** | File system, basic commands, user management, file permissions, text editors |
| **YouTube Resources** | [Linux for Beginners](https://www.youtube.com/watch?v=wBp0Rb-ZJak) - 12 hours (Full course) |
| **Alternative** | [freeCodeCamp Linux](https://www.youtube.com/watch?v=sWbUDq4S6Y8) |
| **Practical Exercise** | Navigate filesystem, create/modify files, manage permissions |
| **Hands-on Lab** | Set up Ubuntu VM, configure users, secure SSH access |
| **Key Topics** | ls, cd, pwd, mkdir, chmod, chown, su, sudo, grep, awk, sed |
| **Projects** | Create automated backup script, system monitoring script |
| **Setup** | Install VirtualBox + Ubuntu 22.04 LTS |

### Topic 5: Bash Scripting (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | Variables, loops, functions, conditionals, error handling |
| **YouTube Resources** | [Bash Scripting Full Course](https://www.youtube.com/watch?v=v-F3YLd6oMw) - 4 hours |
| **Additional** | [freeCodeCamp Bash](https://www.youtube.com/watch?v=SPwyp6lF1cs) - 8 hours |
| **Practical Exercise** | Write scripts for system tasks (backup, monitoring, user management) |
| **Hands-on Lab** | Build 5 automation scripts: file backup, log analysis, service checker |
| **Key Topics** | Loops, functions, arrays, string manipulation, regular expressions |
| **Projects** | Automated WordPress backup script, system health monitor |

### Topic 6: AWS Fundamentals (16 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 16 hours (10 days) |
| **Concepts** | AWS console, service categories, regions/AZs, billing, IAM basics |
| **YouTube Resources** | [AWS Essentials for Beginners](https://www.youtube.com/watch?v=k1RI5locZE4) - 2 hours |
| **Official** | [AWS Training](https://www.aws.amazon.com/training/) - AWS Skill Builder (Free tier) |
| **Practical Exercise** | Explore AWS console, understand service categories |
| **Hands-on Lab** | Create AWS account, set up billing alerts, explore services |
| **Key Topics** | Compute, storage, networking, databases, security services |
| **Important** | Enable MFA on root account, create IAM users |

---

## Month 5-6: AWS Networking Basics

### Topic 7: VPCs & Subnets (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | VPC creation, subnet configuration, routing, internet/NAT gateways |
| **YouTube Resources** | [AWS VPC Tutorial](https://www.youtube.com/watch?v=DXCxNqcxDz8) - 2 hours |
| **Deep Dive** | [freeCodeCamp VPC](https://www.youtube.com/watch?v=g2JOt_2C-1E) - 5 hours |
| **Official Docs** | [AWS VPC Documentation](https://docs.aws.amazon.com/vpc/) |
| **Practical Exercise** | Design and create multi-tier VPC with public/private subnets |
| **Hands-on Lab** | Build VPC, add subnets, configure route tables, test connectivity |
| **Key Projects** | Create 3-tier VPC (web, app, database layers) |
| **Tools** | AWS Console, VPC diagram tools (lucidchart.com) |

### Topic 8: Security Groups & Network ACLs (16 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 16 hours (10 days) |
| **Concepts** | Inbound/outbound rules, stateful vs stateless, best practices |
| **YouTube Resources** | [AWS Security Groups Explained](https://www.youtube.com/watch?v=a0dqbJRq6Aw) - 1 hour |
| **Additional** | [Network ACLs vs Security Groups](https://www.youtube.com/watch?v=EkLcl8v-vF0) |
| **Practical Exercise** | Write security group rules for web/app/database tiers |
| **Hands-on Lab** | Apply principle of least privilege, test allowed/denied traffic |
| **Key Topics** | Rule priority, ephemeral ports, common ports (22, 80, 443, 3306) |
| **Security** | Document all rules, version control changes |

### Topic 9: EC2 & Network Interfaces (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | EC2 instances, elastic IPs, ENIs, instance types, storage |
| **YouTube Resources** | [EC2 Deep Dive](https://www.youtube.com/watch?v=5IXLbv6pfpY) - 3 hours |
| **Hands-on** | [Launch your first EC2 instance](https://www.youtube.com/watch?v=eXuKjYVVPVo) |
| **Practical Exercise** | Launch instances, configure networking, manage IPs |
| **Hands-on Lab** | Deploy web server on EC2, configure security groups, test access |
| **Project** | Create autoscaling group with load balancer |
| **Key Topics** | Instance types (t2, t3, m5), storage (EBS, EFS), pricing models |

**Phase 1 Checkpoint (Month 6):**
- ✅ Understand OSI model and TCP/IP
- ✅ Can subnet networks manually
- ✅ Comfortable with Linux CLI
- ✅ Can create VPC with multiple subnets
- ✅ Launch EC2 instances with proper security
- 💪 Ready for: Junior Cloud Engineer/AWS Associate role

---

# PHASE 2: CLOUD NETWORKING (Months 7-12)
*Master AWS networking, load balancing, and hybrid connectivity*

## Month 7-9: Advanced Cloud Networking

### Topic 10: Load Balancing (ALB/NLB/CLB) (24 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 24 hours (15 days) |
| **Concepts** | ALB vs NLB vs CLB, target groups, health checks, stickiness |
| **YouTube Resources** | [AWS Load Balancers](https://www.youtube.com/watch?v=oZXf5H7fcqg) - 2 hours |
| **Deep Dive** | [freeCodeCamp Load Balancing](https://www.youtube.com/watch?v=qMPWEJHXPCQ) - 4 hours |
| **Practical Exercise** | Design load balancing architecture for web application |
| **Hands-on Lab** | Create ALB, configure target groups, test failover |
| **Project** | Build 3-tier app with load balancer for web tier |
| **Key Topics** | Listener rules, routing algorithms, cross-zone balancing |

### Topic 11: Route 53 (DNS Management) (16 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 16 hours (10 days) |
| **Concepts** | Hosted zones, routing policies (simple, weighted, latency, failover) |
| **YouTube Resources** | [Route 53 Deep Dive](https://www.youtube.com/watch?v=AXVByKSgQ0E) - 1.5 hours |
| **Additional** | [Route 53 Routing Policies](https://www.youtube.com/watch?v=E2jTjL0qXJM) |
| **Practical Exercise** | Set up domain routing with multiple routing policies |
| **Hands-on Lab** | Configure health checks, failover routing, weighted policies |
| **Project** | Set up multi-region DNS failover for website |
| **Key Topics** | Alias records, health checks, traffic policies |

### Topic 12: VPN & Hybrid Connectivity (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | Site-to-Site VPN, Client VPN, Direct Connect, VPN tunneling |
| **YouTube Resources** | [AWS VPN Tutorial](https://www.youtube.com/watch?v=7gQl4bG0H5c) - 2 hours |
| **Additional** | [VPN Fundamentals](https://www.youtube.com/watch?v=K_Gvde1oVAw) - 1.5 hours |
| **Practical Exercise** | Configure VPN between AWS and simulated on-premises network |
| **Hands-on Lab** | Set up Site-to-Site VPN using AWS Client VPN |
| **Project** | Design hybrid AWS + on-premises network |
| **Key Topics** | IPsec, IKEv2, VPN security, redundancy |

### Topic 13: Multi-Region & Global Architecture (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | Multi-region setup, failover patterns, global accelerator, replication |
| **YouTube Resources** | [Multi-region AWS Architecture](https://www.youtube.com/watch?v=oXEb5xTx-sY) - 2 hours |
| **Advanced** | [Disaster Recovery on AWS](https://www.youtube.com/watch?v=2Hb_4QMZsYA) |
| **Practical Exercise** | Design multi-region architecture with failover |
| **Hands-on Lab** | Set up cross-region replication, test failover scenarios |
| **Project** | Build multi-region website with automatic failover |
| **Key Topics** | RTO/RPO, backup strategies, replication lag |

---

## Month 10-12: Network Security & AWS Solutions Architect Certification

### Topic 14: DDoS Protection & WAF (16 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 16 hours (10 days) |
| **Concepts** | AWS Shield, WAF rules, threat mitigation, rate limiting |
| **YouTube Resources** | [AWS WAF & Shield](https://www.youtube.com/watch?v=8DjNqfGS4fw) - 1 hour |
| **Deep Dive** | [WAF Rules Tutorial](https://www.youtube.com/watch?v=5S5R-VXEp_0) |
| **Practical Exercise** | Design WAF rules for web application |
| **Hands-on Lab** | Implement WAF rules, test with OWASP threats |
| **Project** | Protect website from common web attacks (SQL injection, XSS) |
| **Key Topics** | Rate limiting, IP reputation, geo-blocking |

### Topic 15: VPC Flow Logs & Monitoring (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | Flow logs, CloudWatch, CloudTrail, VPC monitoring |
| **YouTube Resources** | [VPC Flow Logs](https://www.youtube.com/watch?v=o63lAMLVmec) - 1.5 hours |
| **Monitoring** | [CloudWatch Deep Dive](https://www.youtube.com/watch?v=F81dHR1tCvA) - 2 hours |
| **Practical Exercise** | Analyze network traffic patterns using flow logs |
| **Hands-on Lab** | Set up VPC flow logs → S3, analyze with Athena |
| **Project** | Build network traffic dashboard in CloudWatch |
| **Key Topics** | Log formats, querying logs, anomaly detection |

### Topic 16: Zero-Trust Architecture (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | Microsegmentation, network policies, least privilege, continuous verification |
| **YouTube Resources** | [Zero Trust Security Explained](https://www.youtube.com/watch?v=_60fQWKxjKc) - 1.5 hours |
| **AWS Specific** | [AWS Zero Trust](https://www.youtube.com/watch?v=kVnWPWVoJvA) |
| **Practical Exercise** | Design zero-trust network for multi-tier application |
| **Hands-on Lab** | Implement network segmentation with security groups |
| **Project** | Redesign existing VPC with microsegmentation |
| **Key Topics** | Trust boundaries, defense in depth, verification at every layer |

### Topic 17: AWS Solutions Architect Associate Certification (40 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 40 hours (25 days) |
| **Content** | All AWS services, architectural best practices, real-world scenarios |
| **YouTube Resources** | [AWS Solutions Architect Associate](https://www.youtube.com/watch?v=Ia-UEYMA44s) - 10 hours |
| **Exam Prep** | [ExamTopics](https://www.examtopics.com/) - Practice questions |
| **Study Materials** | [A Cloud Guru](https://acloudguru.com/) - Full course (paid) |
| **Practice Exams** | Take 3+ practice exams before the real exam |
| **Key Topics** | Service selection, cost optimization, high availability, security |
| **Exam Info** | $150, 65 questions, 130 minutes, 72% pass rate |

**Phase 2 Checkpoint (Month 12):**
- ✅ AWS Solutions Architect Associate Certified
- ✅ Design secure multi-region infrastructure
- ✅ Understand load balancing strategies
- ✅ Configure hybrid connectivity
- ✅ Implement network monitoring
- 💪 Ready for: Associate Cloud Engineer role ($80-120k)

---

# PHASE 3: SECURITY + INFRASTRUCTURE (Months 13-18)
*Deep dive into cloud security, DevSecOps, and infrastructure as code*

## Month 13-15: Cloud Security Fundamentals

### Topic 18: IAM Deep Dive (24 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 24 hours (15 days) |
| **Concepts** | Users, roles, policies, cross-account access, temporary credentials |
| **YouTube Resources** | [AWS IAM Masterclass](https://www.youtube.com/watch?v=k6kDvGntLkE) - 4 hours |
| **Advanced** | [IAM Best Practices](https://www.youtube.com/watch?v=T4pNgGMg80s) |
| **Practical Exercise** | Design least-privilege IAM policy for different roles |
| **Hands-on Lab** | Create users, roles, policies; test cross-account access |
| **Project** | Design IAM structure for multi-team organization |
| **Key Topics** | Policy structure, conditions, resource-based policies, STS |

### Topic 19: Encryption (In-Transit & At-Rest) (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | TLS/SSL, symmetric/asymmetric encryption, KMS, encryption strategies |
| **YouTube Resources** | [AWS Encryption Guide](https://www.youtube.com/watch?v=L6HVBmF3D80) - 2 hours |
| **Crypto Basics** | [Encryption Explained](https://www.youtube.com/watch?v=jhXCTbFnK8o) - 3 hours |
| **Practical Exercise** | Implement encryption for S3, RDS, EBS |
| **Hands-on Lab** | Create KMS keys, enable encryption, rotate keys |
| **Project** | Design encryption strategy for financial application |
| **Key Topics** | KMS key management, envelope encryption, TLS configuration |

### Topic 20: Secrets Management (16 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 16 hours (10 days) |
| **Concepts** | Secrets Manager, Parameter Store, key rotation, secret access patterns |
| **YouTube Resources** | [AWS Secrets Manager](https://www.youtube.com/watch?v=hJCt0QLsj4I) - 1.5 hours |
| **Alternative** | [Parameter Store vs Secrets Manager](https://www.youtube.com/watch?v=VZyS9VIpADM) |
| **Practical Exercise** | Store database passwords, API keys, certificates securely |
| **Hands-on Lab** | Set up automatic secret rotation, access from applications |
| **Project** | Implement secrets management for multi-tier application |
| **Key Topics** | Rotation strategies, access control, audit logging |

### Topic 21: CloudTrail & Audit Logging (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | API logging, audit trails, compliance logging, log analysis |
| **YouTube Resources** | [CloudTrail Deep Dive](https://www.youtube.com/watch?v=BIBJv4jFh4Q) - 1.5 hours |
| **Analysis** | [AWS Log Analysis](https://www.youtube.com/watch?v=eJEUDj1S2WA) |
| **Practical Exercise** | Set up CloudTrail, analyze logs for security incidents |
| **Hands-on Lab** | Configure multi-account logging, create alerts for suspicious activity |
| **Project** | Build compliance audit system with CloudTrail |
| **Key Topics** | Log retention, data events, insight events, log validation |

---

## Month 16-18: DevSecOps & Infrastructure Security

### Topic 22: Terraform & Infrastructure as Code (28 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 28 hours (18 days) |
| **Concepts** | HCL syntax, modules, state management, security best practices |
| **YouTube Resources** | [Terraform Complete Guide](https://www.youtube.com/watch?v=SLB_c_ayRMo) - 4 hours |
| **Beginner** | [freeCodeCamp Terraform](https://www.youtube.com/watch?v=jG6SBA_gm4Q) - 8 hours |
| **Advanced** | [Terraform Best Practices](https://www.youtube.com/watch?v=4eW27lXQfNE) |
| **Practical Exercise** | Write Terraform for VPC, EC2, RDS infrastructure |
| **Hands-on Lab** | Create modules, manage state remotely (S3 + DynamoDB) |
| **Project** | Codify entire 3-tier architecture in Terraform |
| **Key Topics** | Modules, workspaces, remote state, variable management |

### Topic 23: Docker & Container Security (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | Images, containers, Dockerfile, security scanning, registry |
| **YouTube Resources** | [Docker for Beginners](https://www.youtube.com/watch?v=RqTEHOPFSWs) - 4 hours |
| **Security** | [Docker Security](https://www.youtube.com/watch?v=KINnUz2ibIk) - 2 hours |
| **Practical Exercise** | Build Docker images for web applications, scan for vulnerabilities |
| **Hands-on Lab** | Create Dockerfile with security best practices, push to ECR |
| **Project** | Containerize 3-tier application (web, API, worker) |
| **Key Topics** | Multi-stage builds, least privilege containers, image signing |

### Topic 24: Kubernetes Networking & Policies (24 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 24 hours (15 days) |
| **Concepts** | K8s cluster, networking model, network policies, service mesh |
| **YouTube Resources** | [Kubernetes Full Course](https://www.youtube.com/watch?v=d6WC3j_PCNA) - 4 hours |
| **Networking** | [K8s Networking](https://www.youtube.com/watch?v=K3jNo4z5zu0) - 3 hours |
| **Practical Exercise** | Deploy apps in K8s, configure network policies |
| **Hands-on Lab** | Set up local K8s cluster (minikube), implement policies |
| **Project** | Deploy microservices with network segmentation |
| **Key Topics** | Pods, services, ingress, calico/cilium policies |

### Topic 25: CI/CD Security & DevSecOps (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | GitHub Actions, secrets in pipelines, security scanning, SCA/SAST |
| **YouTube Resources** | [GitHub Actions Security](https://www.youtube.com/watch?v=mFFXuXjVgkU) - 2 hours |
| **DevSecOps** | [DevSecOps Pipeline](https://www.youtube.com/watch?v=tCZW_fqp1xE) - 3 hours |
| **Practical Exercise** | Build secure CI/CD pipeline with scanning |
| **Hands-on Lab** | Set up GitHub Actions, integrate security tools (Snyk, Trivy) |
| **Project** | Create production-ready pipeline for containerized app |
| **Key Topics** | Secret management in pipelines, dependency scanning, SAST/DAST |

**Phase 3 Checkpoint (Month 18):**
- ✅ Design secure cloud infrastructure with IaC
- ✅ Implement DevSecOps practices
- ✅ Containerize and orchestrate applications
- ✅ Understand network segmentation
- ✅ Set up automated security scanning
- 💪 Ready for: Cloud Security Engineer or DevSecOps Engineer ($120-160k)

---

# PHASE 4: SPECIALIZATION + JOB READY (Months 19-24)
*Advanced specialization, certifications, and portfolio building*

## Month 19-21: Advanced Security & Certifications

### Topic 26: Threat Modeling & Risk Assessment (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | STRIDE, attack trees, risk assessment, mitigation strategies |
| **YouTube Resources** | [Threat Modeling Guide](https://www.youtube.com/watch?v=xNr8MsEVyL8) - 2 hours |
| **STRIDE Deep Dive** | [Threat Modeling Essentials](https://www.youtube.com/watch?v=VO3jVFbkz5Y) |
| **Practical Exercise** | Perform threat modeling for real applications |
| **Hands-on Lab** | Create threat model for 3-tier architecture |
| **Project** | Design security controls based on threat model |
| **Key Topics** | Threat actors, attack vectors, CVSS scoring |

### Topic 27: Network Segmentation & Defense in Depth (20 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 20 hours (12 days) |
| **Concepts** | DMZ design, microsegmentation, security zones, defense layers |
| **YouTube Resources** | [Network Segmentation](https://www.youtube.com/watch?v=2nSmYc0PSQ8) - 1.5 hours |
| **Advanced** | [Microsegmentation Strategy](https://www.youtube.com/watch?v=W0fpUKQmL1Y) |
| **Practical Exercise** | Design DMZ with multiple security zones |
| **Hands-on Lab** | Implement network policies in AWS and K8s |
| **Project** | Redesign network with zero-trust architecture |
| **Key Topics** | Trust boundaries, lateral movement prevention |

### Topic 28: AWS Security Specialty Certification (40 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 40 hours (25 days) |
| **Content** | Advanced AWS security services, compliance, threat detection |
| **YouTube Resources** | [AWS Security Specialty](https://www.youtube.com/watch?v=FQLZUS7XCIQ) - 8 hours |
| **Study Plan** | [Security Specialty Exam Guide](https://docs.aws.amazon.com/security-hub/latest/userguide/what-is-securityhub.html) |
| **Practice Exams** | [Whizlabs](https://www.whizlabs.com/) or [ExamTopics](https://www.examtopics.com/) |
| **Key Topics** | Security monitoring, threat detection, incident response, compliance |
| **Exam Info** | $150, 65 questions, 170 minutes, 65% pass rate |

### Topic 29: Compliance & Audit (16 hours)

| Aspect | Details |
|--------|---------|
| **Duration** | 16 hours (10 days) |
| **Concepts** | HIPAA, PCI-DSS, SOC 2, compliance frameworks, audit trails |
| **YouTube Resources** | [AWS Compliance Overview](https://www.youtube.com/watch?v=fz2Bx2qsjBo) - 1.5 hours |
| **Frameworks** | [Compliance Frameworks Explained](https://www.youtube.com/watch?v=u6FLH3MQTxU) |
| **Practical Exercise** | Map compliance requirements to AWS controls |
| **Hands-on Lab** | Set up compliance monitoring, create audit reports |
| **Project** | Build compliance dashboard for regulated industry |
| **Key Topics** | Compliance as code, audit trails, evidence collection |

---

## Month 22-24: Portfolio Projects & Job Transition

### Portfolio Project 1: Secure Multi-Region AWS Architecture (40 hours)

**Objective:** Design and deploy a production-grade, secure, multi-region infrastructure

| Component | Details |
|-----------|---------|
| **Duration** | 40 hours (25 days) |
| **What You'll Build** | Multi-region VPC, load balancers, RDS, failover |
| **Technologies** | Terraform, AWS (EC2, RDS, ALB, Route 53), Monitoring |
| **Security Features** | Encryption, IAM policies, security groups, WAF, logging |
| **Deliverables** | GitHub repo with code, architecture diagram, documentation |
| **Key Learning** | VPC design, load balancing, disaster recovery |
| **YouTube Reference** | [Multi-region Architecture](https://www.youtube.com/watch?v=oXEb5xTx-sY) |
| **GitHub Skills** | Version control, README documentation, infrastructure-as-code |

### Portfolio Project 2: Secure CI/CD Pipeline with DevSecOps (40 hours)

**Objective:** Build automated, secure deployment pipeline

| Component | Details |
|-----------|---------|
| **Duration** | 40 hours (25 days) |
| **What You'll Build** | GitHub Actions pipeline, Docker build, security scanning |
| **Technologies** | GitHub Actions, Docker, Terraform, Snyk, Trivy |
| **Security Features** | Dependency scanning, SAST, container scanning, secret management |
| **Deliverables** | GitHub Actions workflows, scan reports, deployment automation |
| **Key Learning** | Shift-left security, automated testing, secure deployment |
| **YouTube Reference** | [DevSecOps Pipeline](https://www.youtube.com/watch?v=tCZW_fqp1xE) |
| **Outcome** | Fully automated, secure deployment from code to production |

### Portfolio Project 3: Kubernetes Cluster with Network Policies (40 hours)

**Objective:** Deploy production-grade K8s cluster with security

| Component | Details |
|-----------|---------|
| **Duration** | 40 hours (25 days) |
| **What You'll Build** | EKS cluster, microservices, network policies, monitoring |
| **Technologies** | Kubernetes, Docker, Helm, Prometheus, Calico/Cilium |
| **Security Features** | Network policies, RBAC, pod security policies, monitoring |
| **Deliverables** | K8s manifests, Helm charts, monitoring dashboard |
| **Key Learning** | Container orchestration, microservices security, observability |
| **YouTube Reference** | [Kubernetes Production Setup](https://www.youtube.com/watch?v=d6WC3j_PCNA) |
| **Outcome** | Secure, observable, production-ready K8s cluster |

### Job Transition & Networking (40 hours)

| Component | Details |
|-----------|---------|
| **Duration** | 40 hours (over the month) |
| **LinkedIn Optimization** | Professional summary, projects showcase, recommendations |
| **Interview Preparation** | System design questions, AWS questions, behavioral |
| **Resume Building** | Highlight 3 projects, quantify achievements |
| **Networking** | AWS community forums, LinkedIn connections, tech meetups |
| **Resources** | [Interview Prep YouTube](https://www.youtube.com/watch?v=SqcPQJ_d_hc) |
| **Target Companies** | AWS Partners, Tech startups, Enterprise Cloud teams |
| **Job Titles** | Cloud Architect, Cloud Security Engineer, DevOps Engineer |

---

# 📜 CERTIFICATION TIMELINE

| Certification | Target Month | Prep Hours | Exam Cost | Passing Score |
|---------------|-------------|-----------|-----------|---------------|
| CompTIA Network+ | 2-3 | 40 | $299 | 720/900 |
| AWS Solutions Architect Associate | 12 | 60 | $150 | 72% |
| AWS Security Specialty | 21 | 80 | $150 | 65% |
| Certified Kubernetes Admin (CKA) | 23 | 60 | $395 | 66% |

---

# 🛠️ TOOLS & TECH STACK

## Phase 1 Tools
- VirtualBox (Free)
- Ubuntu 22.04 LTS (Free)
- Wireshark (Free)
- AWS Free Tier
- Code editor (VS Code - Free)

## Phase 2 Tools
- AWS Console
- Terraform (Free)
- SSH/Putty
- AWS CLI
- Monitoring tools (CloudWatch - Free tier)

## Phase 3 Tools
- Docker Desktop (Free)
- Kubernetes (minikube - Free)
- GitHub (Free)
- Snyk (Free tier)
- Trivy (Free)

## Phase 4 Tools
- Prometheus (Free)
- Grafana (Free)
- HashiCorp Vault (Free)
- Splunk Trial
- OWASP Tools (Free)

## Ongoing Tools
- Git/GitHub
- AWS CLI
- kubectl
- Helm
- Terraform
- Docker
- Code editor

---

# ⏰ DAILY SCHEDULE EXAMPLE

```
6:00 AM - 8:00 AM (Morning Session)
├─ 7:00-8:00: YouTube Tutorial / Course Lecture
├─ 7:00-8:00: Follow along with practical demo
└─ Focus: Understand concepts, take notes

2:00 PM - 4:00 PM (Evening Session)
├─ 2:00-3:30: Hands-on Lab / Build project
├─ 3:30-4:00: Document learnings, GitHub commit
└─ Focus: Apply concepts, troubleshoot issues

Weekly:
├─ Practice 20-24 hours
├─ Build 2-3 small projects
├─ Review and reinforce weak areas
└─ Complete hands-on labs
```

---

# 🏠 HOME LAB SETUP CHECKLIST

## Month 1-2 (Foundation)
- [ ] VirtualBox installed
- [ ] Ubuntu 22.04 LTS VM created
- [ ] Wireshark installed for packet capture
- [ ] AWS Free Tier account created
- [ ] Cost: ~$0 (all free)

## Month 3-6 (Early Cloud)
- [ ] AWS VPC with multiple subnets
- [ ] 2-3 EC2 instances running
- [ ] Basic monitoring enabled
- [ ] RDS instance for database practice
- [ ] Cost: ~$20-50/month

## Month 7-12 (Intermediate)
- [ ] Multi-region VPC setup
- [ ] Load balancer with health checks
- [ ] Terraform code managing infrastructure
- [ ] CloudTrail enabled for all accounts
- [ ] Cost: ~$50-100/month

## Month 13-18 (Advanced)
- [ ] Local Kubernetes (minikube) cluster
- [ ] Docker images built and stored
- [ ] GitHub Actions CI/CD pipeline
- [ ] Multiple environments (dev, test, prod)
- [ ] Cost: ~$100-200/month

## Month 19-24 (Production-Grade)
- [ ] EKS cluster (managed Kubernetes)
- [ ] Service mesh (optional: Istio/Linkerd)
- [ ] Comprehensive monitoring stack
- [ ] Multi-region failover tested
- [ ] Cost: ~$200-400/month

---

# ✅ MONTHLY MILESTONES

| Month | Milestone | Skills Achieved |
|-------|-----------|-----------------|
| 1-2 | OSI/Networking mastered | Understand network fundamentals |
| 3-4 | Linux + AWS basics | Comfortable with CLI, AWS console |
| 5-6 | VPC architect | Design and build multi-tier VPCs |
| 7-9 | Load balancing expert | Configure high availability |
| 10-12 | **AWS Architect Certified** | Design production architectures |
| 13-15 | Security specialist | Implement encryption, IAM, logging |
| 16-18 | DevSecOps engineer | Build secure CI/CD pipelines |
| 19-21 | **AWS Security Specialist Certified** | Design secure, compliant systems |
| 22-24 | Full stack ready | 3 projects, interview ready |

---

# 💼 JOB ROLES BY TIMELINE

## After 6 months (Foundation Complete)
- Associate Cloud Engineer
- Junior DevOps Engineer
- AWS Support Engineer
- **Salary:** $70,000 - $100,000

## After 12 months (Architect Certified)
- Cloud Network Engineer
- Senior DevOps Engineer
- Infrastructure Engineer
- **Salary:** $100,000 - $150,000

## After 18 months (Security Knowledge)
- Cloud Security Engineer
- DevSecOps Engineer
- Cloud Infrastructure Specialist
- **Salary:** $120,000 - $180,000

## After 24 months (Specialized & Certified)
- Cloud Solutions Architect
- Cloud Security Architect
- Senior Cloud Engineer
- **Salary:** $150,000 - $250,000+

---

# 📚 BEST FREE & PAID RESOURCES

## Free YouTube Channels
- **[Professor Messer](https://www.youtube.com/@ProfessorMesser)** - Network fundamentals
- **[NetworkChuck](https://www.youtube.com/@NetworkChuck)** - Networking & Linux
- **[TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana)** - DevOps, K8s
- **[freeCodeCamp](https://www.youtube.com/@freecodecamp)** - Full courses (Linux, AWS, Docker)
- **[Edureka](https://www.youtube.com/@edurekaIN)** - Structured courses

## Free Resources
- **[AWS Skill Builder](https://skillbuilder.aws/)** - Official free courses
- **[AWS Free Tier](https://aws.amazon.com/free/)** - $300 credits for labs
- **[HackTheBox](https://www.hackthebox.com/)** - Security challenges (free tier)
- **[ExamTopics](https://www.examtopics.com/)** - Free practice questions
- **[TryHackMe](https://tryhackme.com/)** - Hands-on security labs

## Paid Resources (Optional but Recommended)
- **[A Cloud Guru](https://acloudguru.com/)** - $50-70/month, comprehensive
- **[Linux Academy](https://linuxacademy.com/)** - $49/month, hands-on labs
- **[Udemy](https://www.udemy.com/)** - $10-15/course (when on sale)
- **[Pluralsight](https://www.pluralsight.com/)** - $29/month, skill paths
- **[Whizlabs](https://www.whizlabs.com/)** - Practice exams

---

# 🚀 QUICK START (THIS WEEK!)

### Day 1: Foundation
- [ ] Watch: [AWS Basics in 5 minutes](https://www.youtube.com/watch?v=k1RI5locZE4)
- [ ] Create: AWS Free Tier account
- [ ] Explore: AWS Console (just browse)
- [ ] Time: 1 hour

### Day 2-3: Networking Basics
- [ ] Watch: [OSI Model Explained](https://www.youtube.com/watch?v=IMAP_yKvlps)
- [ ] Read: OSI layers, TCP/UDP protocols
- [ ] Project: Draw OSI model with 5 protocols at each layer
- [ ] Time: 2 hours

### Day 4-5: Linux Start
- [ ] Install: VirtualBox + Ubuntu
- [ ] Learn: 10 basic Linux commands (ls, cd, pwd, mkdir, touch, rm, cat, nano, sudo, man)
- [ ] Practice: Create files, navigate directories
- [ ] Time: 3 hours

### Day 6-7: First AWS VPC
- [ ] Watch: [AWS VPC Tutorial](https://www.youtube.com/watch?v=DXCxNqcxDz8)
- [ ] Create: Your first VPC with public and private subnets
- [ ] Configure: Security groups, Internet Gateway
- [ ] Launch: Single EC2 instance in the VPC
- [ ] Time: 3 hours

### Weekend Review
- [ ] Document: Create GitHub repo for your learning journey
- [ ] Summarize: What you learned this week (README.md)
- [ ] Plan: Schedule your daily 4-hour sessions
- [ ] Goals: Set specific targets for Month 1

---

# 🎯 SUCCESS CHECKLIST

### Month 1 Success Indicators
- ✅ Complete Prof Messer Network+ playlist (15 hours)
- ✅ Understand OSI model and TCP/IP
- ✅ Create and analyze network packets with Wireshark
- ✅ Build working Linux VM
- ✅ Create AWS account with MFA enabled

### Month 6 Success Indicators
- ✅ Comfortable with Linux command line
- ✅ Design and build multi-tier VPC
- ✅ Launch and configure EC2 instances
- ✅ Understand security groups and NACLs
- ✅ Have 2-3 projects on GitHub

### Month 12 Success Indicators
- ✅ **AWS Solutions Architect Associate Certified**
- ✅ Design multi-region architecture
- ✅ Configure load balancers and failover
- ✅ Understand Route 53 routing policies
- ✅ Have 5+ projects on GitHub demonstrating skills

### Month 24 Success Indicators
- ✅ **AWS Security Specialty Certified** (or CKA)
- ✅ Deployed Kubernetes clusters with security policies
- ✅ Built secure CI/CD pipelines
- ✅ Designed zero-trust architectures
- ✅ 3 professional-grade portfolio projects
- ✅ Interviewing for Cloud Architect roles
- ✅ Salary range: $150,000 - $250,000+

---

# 📞 FINAL TIPS

1. **Consistency Over Intensity**: 4 hours daily is sustainable. Don't burn out.
2. **Build Every Day**: Theory is 30%, hands-on is 70%.
3. **Document Your Journey**: Blog/GitHub - helps interviews and reinforces learning.
4. **Join Communities**: AWS forums, Reddit r/aws, local tech meetups.
5. **Focus on Concepts**: Tools change, but concepts remain. Understand WHY.
6. **Network Professionally**: LinkedIn connections, Twitter tech community, conferences.
7. **Practice Interviews**: Mock interviews starting Month 15.
8. **Stay Current**: AWS adds 30+ services yearly - skim updates monthly.
9. **Niche Focus**: Around Month 12, start specializing (security, networking, DevOps).
10. **Never Stop Learning**: This roadmap is foundation - keep learning after Month 24.

---

**Your journey starts TODAY. This roadmap is your compass. Make the daily commitment and you'll transform into a cloud architect earning $150-250k+ within 24 months.**

**Go build something great! 🚀**
