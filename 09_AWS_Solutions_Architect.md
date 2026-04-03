# AWS Certified Solutions Architect (Associate) Guide (2025-2026)

## Overview
AWS Certified Solutions Architect validates expertise in designing scalable, reliable, and secure applications on AWS. It covers AWS services, architecture best practices, and cost optimization.

**Certification Code:** SAA-C03

---

## Duration & Study Timeline
- **Recommended Study Duration:** 2-3 months
- **Study Hours Required:** 100-150 hours
- **Hands-On Lab Time:** 40-60 hours
- **Prerequisites:** AWS Cloud Practitioner recommended

---

## Exam Details

### Exam Duration
- **Total Duration:** 130 minutes
- **Total Questions:** 65 questions
- **Passing Score:** 720/1000
- **Question Format:** Multiple choice, multiple select

### Exam Fee (2025-2026)
- **Exam Fee:** $150 USD
- **Retake Fee:** $150 USD
- **Training Costs:** $0-500 (optional AWS training)
- **Practice Exams:** $20-40

---

## Complete Syllabus & Topics

### Domain 1: Design Secure Architectures (30%)

#### IAM (Identity & Access Management)
- **Users, Roles, Policies**
  - IAM users and groups
  - IAM roles
  - Permission policies
  - Policy evaluation logic
  - Cross-account access
  - Temporary security credentials
- **Best Practices**
  - Principle of least privilege
  - MFA enforcement
  - Password policies
  - Access keys management
  - Service control policies (SCP)

#### Network Security
- **VPC Architecture**
  - VPC design for security
  - Subnets and routing
  - Security groups
  - NACLs (Network Access Control Lists)
  - VPC endpoints
  - VPC Flow Logs
- **Connectivity & Encryption**
  - VPN connections
  - AWS Direct Connect
  - TLS/HTTPS
  - Data encryption (at rest, in transit)
  - Key management (KMS, CloudHSM)

#### Application Security
- **WAF (Web Application Firewall)**
  - WAF rules and conditions
  - DDoS protection (Shield)
  - Rate limiting
  - SQL injection protection
- **Secrets Management**
  - AWS Secrets Manager
  - Parameter Store
  - Credential rotation
  - Certificate management

### Domain 2: Design Resilient Architectures (26%)

#### High Availability & Disaster Recovery
- **Multi-AZ Design**
  - Availability Zones
  - Multi-AZ deployment
  - Cross-region replication
  - Failover mechanisms
  - RTO/RPO considerations
- **Load Balancing**
  - Application Load Balancer (ALB)
  - Network Load Balancer (NLB)
  - Classic Load Balancer
  - Target groups
  - Health checks
  - Auto Scaling

#### Database Resilience
- **RDS (Relational Database Service)**
  - Multi-AZ deployments
  - Read replicas
  - Automated backups
  - Backup retention
  - Point-in-time recovery
- **DynamoDB**
  - Global tables
  - On-demand vs provisioned
  - Point-in-time recovery
  - Backup and restore

#### Storage & Backup
- **EBS (Elastic Block Store)**
  - EBS volumes
  - Snapshots
  - Snapshot copying
  - EBS-optimized instances
- **S3 (Simple Storage Service)**
  - S3 versioning
  - Cross-region replication
  - S3 lifecycle policies
  - Backup strategies

### Domain 3: Design High-Performing Architectures (20%)

#### Compute Services
- **EC2 Optimization**
  - Instance families and types
  - Placement groups
  - Spot instances
  - Reserved instances
  - Dedicated hosts
  - Performance optimization
- **Containers & Serverless**
  - ECS (Elastic Container Service)
  - EKS (Elastic Kubernetes Service)
  - Fargate
  - Lambda (serverless computing)
  - API Gateway

#### Caching & CDN
- **Caching Layers**
  - ElastiCache (Redis, Memcached)
  - CloudFront (CDN)
  - Caching strategies
  - Cache invalidation
- **Performance Enhancement**
  - Connection pooling
  - Compression
  - Batching operations
  - Read replicas

#### Database Performance
- **Database Selection**
  - Relational (RDS)
  - NoSQL (DynamoDB)
  - Data warehousing (Redshift)
  - Analytics (Athena)
  - In-memory databases
- **Query Optimization**
  - Indexing strategies
  - Query patterns
  - Connection pooling
  - Query caching

### Domain 4: Design Cost-Optimized Architectures (24%)

#### Cost Optimization
- **Pricing Models**
  - On-demand instances
  - Reserved instances (RI)
  - Savings plans
  - Spot instances
  - Per-second billing
  - Estimate and track costs
- **Service Selection**
  - Choosing appropriate services
  - Right-sizing instances
  - Storage optimization
  - Data transfer optimization
- **Monitoring & Management**
  - AWS Cost Explorer
  - Budget alerts
  - Trusted Advisor
  - Spot instance recommendations
  - Reservation recommendations

#### Storage Optimization
- **S3 Cost Optimization**
  - Storage classes
  - Lifecycle policies
  - Versioning management
  - Transfer acceleration
  - Intelligent-Tiering
- **Data Transfer**
  - S3 Transfer Acceleration
  - CloudFront optimization
  - VPC endpoint pricing
  - Direct Connect vs internet

#### Database Cost Optimization
- **Database Selection**
  - RDS vs DynamoDB
  - Provisioned vs on-demand
  - Retention policies
  - Backup strategies
  - Multi-AZ cost implications

---

## AWS Services to Master

### Compute
- EC2, Lambda, ECS, EKS, Fargate, AppRunner

### Storage
- S3, EBS, EFS, Glacier, Backup

### Database
- RDS, DynamoDB, ElastiCache, Redshift, Neptune

### Networking
- VPC, CloudFront, Route 53, ELB, NLB, ALB

### Security & Identity
- IAM, KMS, Secrets Manager, GuardDuty, Security Hub

### Management & Monitoring
- CloudWatch, CloudTrail, Config, Systems Manager

### Application Integration
- SQS, SNS, SES, API Gateway, EventBridge

### Analytics
- Athena, QuickSight, EMR, Kinesis

---

## Study Resources

### Official AWS Resources
- AWS Well-Architected Framework
- AWS Whitepapers
- AWS Documentation
- AWS Skill Builder (paid courses)

### Training Providers
- A Cloud Guru
- Pluralsight
- Linux Academy
- Udemy
- CloudAcademy
- Tutorial Dojo

### Hands-On Practice
- AWS Free Tier
- AWS Hands-on labs
- AWS Workshops
- CloudFormation templates
- Terraform on AWS

### Practice Exams
- AWS Official Practice Exam
- Tutorial Dojo
- Jon Bonso exams
- Boson ExamSim

---

## Hands-On Lab Scenarios

1. **Design Multi-AZ Application**
   - VPC setup
   - Load balancer configuration
   - Database replication
   - Auto-scaling

2. **Implement Security**
   - IAM policy design
   - Security group rules
   - KMS encryption
   - Secrets rotation

3. **Optimize Costs**
   - Right-sizing instances
   - Storage optimization
   - Reserved instance planning
   - Data transfer optimization

4. **Disaster Recovery**
   - Backup strategies
   - Cross-region failover
   - RTO/RPO planning
   - Restore procedures

---

## Exam Tips

1. **Time Management:** ~2 minutes per question
2. **Read Carefully:** Multiple correct-sounding answers
3. **AWS Best Practices:** Focus on recommended solutions
4. **Trade-offs:** Understand cost vs performance
5. **Service Selection:** Know when to use which service

---

## Career Paths

### Job Titles
- Solutions Architect
- Cloud Engineer
- DevOps Engineer
- Infrastructure Engineer

### Salary Range (2025-2026)
$90,000 - $150,000+ USD

### Next Certifications
- AWS Solutions Architect Professional
- AWS DevOps Engineer Professional
- AWS Security Specialist

---

## 2025-2026 Updates

- **Enhanced:** AI/ML service coverage
- **New Services:** Regular AWS service additions
- **Expanded:** Container and serverless focus
- **Updated:** Cost optimization tools

---

**Last Updated:** 2025-2026
**Difficulty Level:** ⭐⭐⭐ (Professional)
**Recommended for:** Cloud architects, engineers
**Prerequisite:** AWS Cloud Practitioner helpful
**Time to Proficiency:** 2-3 months
