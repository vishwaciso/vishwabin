# ☁️ Cloud Computing Career Roadmap & Domain Guide

## 📌 Introduction
Cloud computing is not just a single technology — it’s a **collection of multiple domains** working together.  
Before cloud adoption, each domain had its own separate technologies, certifications, and career growth paths.  
Now, **everything is in the cloud**, and every engineer needs to adapt their domain skills to the cloud environment.

In this guide, you’ll learn:
- All **major cloud domains**
- How each domain worked **before cloud**
- How it works **in the cloud era**
- **Certification paths** (on-prem & cloud)
- **Career ladder** from beginner to leadership
- **Real-world examples** for interviews & projects

---

## 🌐 Domain 1: Networking

### 🔹 Before Cloud
Networking was purely on-premises, handled by network engineers within data centers.  
Certifications like:
- **CCNA** (Cisco Certified Network Associate)
- **CCNP** (Cisco Certified Network Professional)
- **CCIE** (Cisco Certified Internetwork Expert — R&S, Security, Data Center, Wireless)

**Career Path:**
- **L1**: Network Support Engineer
- **L2**: Network Administrator
- **L3**: Senior Network Engineer
- **L4**: Network Architect / Manager
- **Leadership**: Senior Manager → Director → CTO (Infrastructure)

### 🔹 In Cloud
Networking is virtualized:
- **VPCs (Virtual Private Clouds)**
- **Subnets, Route Tables, Internet Gateways**
- **Security Groups & NACLs**
- **Cloud Load Balancers**
- **PrivateLink, Transit Gateway**

### 📜 Certification Mapping
| On-Prem (Before Cloud) | Cloud Era Equivalent |
|------------------------|----------------------|
| CCNA, CCNP, CCIE       | AWS Advanced Networking Specialty, Azure Network Engineer Associate, GCP Network Engineer |

### 🎯 Real-World Scenario
_A company moves its on-prem network to AWS. Instead of configuring physical switches, engineers set up a **VPC** with **public & private subnets**, use **NACLs** for subnet-level security, and deploy a **Transit Gateway** to connect multiple VPCs._

---

## 💾 Domain 2: Storage

### 🔹 Before Cloud
Storage was managed in physical data centers with storage area networks (SAN) and network-attached storage (NAS).  
Certifications like:
- **NetApp Certified Data Administrator**
- **EMC Storage Administrator**
- **HPE Storage Solutions**

**Career Path:**
- **L1**: Storage Support Technician
- **L2**: Storage Administrator
- **L3**: Storage Architect
- **L4**: Storage Manager → Director → CTO (Infrastructure)

### 🔹 In Cloud
Storage is now **on-demand and scalable**:
- **Object Storage**: AWS S3, Azure Blob Storage, GCP Cloud Storage
- **Block Storage**: AWS EBS, Azure Managed Disks
- **File Storage**: AWS EFS, Azure File Shares
- **Cold & Archival Storage**: AWS Glacier

### 📜 Certification Mapping
| On-Prem (Before Cloud) | Cloud Era Equivalent |
|------------------------|----------------------|
| EMC, NetApp, HPE Certs | AWS S3 Deep Dive, Azure Storage Specialist, GCP Storage Solutions |

### 🎯 Real-World Scenario
_A media company used to buy NAS devices for storing video archives. Now, they use **AWS S3 with lifecycle policies** to automatically move old files to **Glacier** for cost savings._

---

## 🖥️ Domain 3: Compute (Linux & Windows)

### 🔹 Before Cloud
Compute resources were provisioned as **physical servers** in data centers.  
Engineers specialized in:
- **Linux Administration** (RHCSA, RHCE)
- **Windows Server Administration** (MCSA, MCSE)

**Career Path:**
- **L1**: System Support Engineer
- **L2**: System Administrator
- **L3**: System Engineer / Architect
- **L4**: Infra Manager → Director → CTO (IT Operations)

### 🔹 In Cloud
Servers are virtual:
- **EC2 (AWS)**, **Azure VM**, **GCP Compute Engine**
- Auto Scaling, Serverless (AWS Lambda, Azure Functions)
- Image-based provisioning (AMI, Managed Images)

### 📜 Certification Mapping
| On-Prem (Before Cloud) | Cloud Era Equivalent |
|------------------------|----------------------|
| RHCSA, RHCE, MCSA, MCSE | AWS SysOps Administrator, Azure Administrator, GCP SysOps |

### 🎯 Real-World Scenario
_A retail company needed 10 servers for a seasonal sale. Before cloud, they’d buy hardware. Now, they launch **EC2 Auto Scaling groups** that automatically spin up and down based on traffic._

---

