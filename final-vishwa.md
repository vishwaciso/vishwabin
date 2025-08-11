<!-- README.md: Ultimate Cloud Career Roadmap (Full, single-file) -->

[![Status](https://img.shields.io/badge/status-complete-brightgreen)](https://github.com/)
[![Domains](https://img.shields.io/badge/domains-15-blue)](https://github.com/)
[![Difficulty](https://img.shields.io/badge/difficulty-beginners%20to%20expert-orange)](https://github.com/)
[![License](https://img.shields.io/badge/license-MIT-blueviolet)](LICENSE)

# ☁️ Ultimate Cloud Career Roadmap — 15 Domains, Step-by-step, With Marks
**All-in-one guide:** fundamentals (on-prem) → cloud equivalents → career path → certifications → projects & marks → interview prep → progress tracker.

---

## 🔥 Quick links (clickable index)
- [Overview & How to Use](#overview--how-to-use)
- [Marks & Weightage](#marks--weightage)
- Domains (click to jump)
  - [Networking](#networking)
  - [Storage](#storage)
  - [Compute](#compute)
  - [Operating Systems](#operating-systems)
  - [Middleware](#middleware)
  - [Databases](#databases)
  - [Security](#security)
  - [IAM (Identity & Access)](#iam-identity--access)
  - [DevOps](#devops)
  - [Monitoring](#monitoring)
  - [Backup-&-Disaster-Recovery](#backup--disaster-recovery)
  - [AI-ML](#ai-ml)
  - [IoT](#iot)
  - [FinOps](#finops)
  - [Development-&-Testing](#development--testing)
- [Study Plans (12/24 weeks)](#study-plans)
- [Assessment Rubric & Grading](#assessment-rubric--grading)
- [Interview Prep & Sample Questions](#interview-prep--sample-questions)
- [Resume & Portfolio Tips](#resume--portfolio-tips)
- [Progress Tracker (fillable)](#progress-tracker)
- [Appendix: Cheat-sheets & Commands](#appendix-cheat-sheets--commands)
- [License & Contact](#license--contact)

---

## 📘 Overview & How to Use
**Who this README is for:** students, freshers, mid-career professionals, and engineering leads who want a practical domain-by-domain path into cloud careers.

**How to use:**
1. Choose a track: *Specialist* (2–3 domains) or *Generalist/full-stack cloud* (all domains).  
2. For each domain: follow the ordered steps — *Foundations (Before Cloud)* → *Cloud Skills* → *Labs* → *Project (Capstone)* → *Certification* → *Interview Practice*.  
3. Record marks in the Progress Tracker and iterate.

---

## 🧾 Marks & Weightage (how scoring works)
Two options depending on how granular you want grading:

**Option A — Module-based (recommended for thorough learning)**  
- Each domain = **100 marks**.  
  - Theory / MCQ: 40  
  - Hands-on Labs: 35  
  - Project / Capstone: 15  
  - Interview / Soft skills: 10  
- Total for 15 domains = **1500 marks** (normalize to 100 as needed).

**Option B — Course-normalized (single 100 score)**  
- Assign weights per domain (edit to match your job goals). Example weights (sum = 100):
  - Networking 7, Storage 7, Compute 8, OS 6, Middleware 5, Databases 10, Security 12, IAM 8, DevOps 12, Monitoring 5, Backup/DR 4, AI/ML 6, IoT 4, FinOps 6, DevTest 5

---

---

## 🧭 Domain Modules (complete — 15 domains)
Each domain contains: **Before Cloud**, **In Cloud**, **Cert Mapping**, **Career path**, **Labs (with marks)**, **Capstone Project (with marks)**, **Real-world example**, **Estimated time**.

---

<a id="networking"></a>
## 1. Networking 🌐  — **Module Marks: 100**
**Theory 40 | Labs 35 | Project 15 | Interview 10**

**Before Cloud (Foundations)** — *20 marks*  
- OSI & TCP/IP, IP addressing & subnetting, VLANs, switching, basic routing, BGP/OSPF overview.

**In Cloud (Core Concepts)** — *30 marks*  
- VPC/VNet design, subnets, route tables, IGW/NAT, security groups, NACLs, ALB/NLB, Transit Gateway, PrivateLink, VPN/Direct Connect, hybrid connectivity.

**Labs (35 marks)**  
- Lab A: Build VPC with public/private subnets + NAT (8)  
- Lab B: ALB + Auto Scaling + health checks (12)  
- Lab C: Site-to-site VPN & connectivity tests (15)

**Capstone Project (15 marks)**  
- Multi-region VPC architecture with Transit Gateway, failover, and Terraform code. Deliverables: diagram (3), IaC (7), test-report (3), demo video (2).

**Certs & Career**  
- On-prem: CCNA → CCNP → CCIE. Cloud: AWS Cloud Practitioner → AWS Advanced Networking Specialty, Azure Network Engineer.

**Real-world**: Use AWS Transit Gateway to interconnect 20 VPCs and route traffic with minimal latency.

**Est. time:** 6–10 weeks

---

<a id="storage"></a>
## 2. Storage 📦  — **Module Marks: 100**
**Theory 40 | Labs 35 | Project 15 | Interview 10**

**Before Cloud** — DAS, NAS, SAN, RAID, IOPS/throughput, RPO/RTO fundamentals.

**In Cloud** — S3/Blob (object), EBS/Azure Disks (block), EFS/Azure Files (file), lifecycle policies, encryption at rest/in transit, storage classes (hot/cold/archive).

**Labs (35)**  
- S3 lifecycle & cross-region replication (10)  
- EBS snapshot automation + restore (12)  
- Deploy EFS and mount to app (13)

**Project (15)**  
- Cost-optimized storage lifecycle for media: architecture doc (3), IaC (5), cost savings (4), demo (3).

**Certs & Career**  
- NetApp/Dell EMC → AWS Storage Specialty, Azure Storage.

**Real-world**: Media company uses S3 Standard for active content + Glacier for archives.

**Est. time:** 4–8 weeks

---

<a id="compute"></a>
## 3. Compute 🖥️  — **Module Marks: 100**

**Before Cloud** — physical servers, virtualization (VMware), hypervisors, sizing.

**In Cloud** — EC2/VMs/Compute Engine, autoscaling groups, AMIs/Managed Images, spot/reserved instances, serverless (Lambda/Azure Functions), containers vs VMs.

**Labs (35)**  
- Auto Scaling group with ALB + CloudWatch policies (10)  
- Migrate a VM-based web app to EC2 + AMI baking (12)  
- Convert scheduled job to serverless (13)

**Project (15)**  
- Hybrid compute: EC2 core services + Lambda for async tasks. Deliverables: diagrams (3), IaC (7), load test report (3), runbook (2).

**Certs**: CompTIA Server+ → AWS SysOps / Azure Administrator → Solutions Architect.

**Real-world**: Auto-scale EC2 fleet for Black Friday surges.

**Est. time:** 4–8 weeks

---

<a id="operating-systems"></a>
## 4. Operating Systems 🐧🪟  — **Module Marks: 100**

**Before Cloud** — Linux fundamentals, shell scripting, Windows Server and PowerShell, AD basics.

**In Cloud** — AMIs/Managed Images, cloud-init, patch automation (SSM/Run Command), configuration management (Ansible, DSC), image hardening.

**Labs (35)**  
- Build & harden Ubuntu image (10)  
- Automate patching via SSM or similar (12)  
- Centralized identity integration (AD/SSO) (13)

**Project (15)**  
- Hardened image pipeline: build → test → publish. Deliverables: scripts (6), pipeline config (5), compliance checklist (4).

**Certs**: RHCSA/RHCE, MCSA/MCSE, cloud OS management courses.

**Est. time:** 4–6 weeks

---

<a id="middleware"></a>
## 5. Middleware 🔄  — **Module Marks: 100**

**Before Cloud** — Tomcat, WebSphere, session affinity, clustering.

**In Cloud** — Elastic Beanstalk, Azure App Service, containerizing middleware on Kubernetes/ECS, API Gateway, service meshes.

**Labs (35)**  
- Containerize Tomcat & deploy to EKS (12)  
- Blue/Green deploy with App Service / Beanstalk (12)  
- Implement messaging (SNS/SQS) with DLQ (11)

**Project (15)**  
- Modernize legacy app → microservices + API Gateway + CI/CD. Deliverables: architecture (4), manifests (5), pipeline (4), runbook (2).

**Certs**: Vendor middleware certs → AWS Developer, Azure DevOps.

**Est. time:** 6–10 weeks

---

<a id="databases"></a>
## 6. Databases 🗄️  — **Module Marks: 100**

**Before Cloud** — RDBMS design, normalization, indexing, HA & backups.

**In Cloud** — RDS/Cloud SQL, Aurora, DynamoDB, Cosmos DB, read replicas, multi-AZ, backups, automated failover.

**Labs (35)**  
- Launch RDS with backups + read replica (12)  
- Model access patterns in DynamoDB (12)  
- Snapshot restore & failover test (11)

**Project (15)**  
- Migrate OLTP to managed DB with HA & scaling. Deliverables: migration plan (4), IaC (5), perf & cost report (4), rollback plan (2).

**Certs**: OCP, MCSE → AWS Database Specialty, Azure DBA.

**Est. time:** 6–10 weeks

---

<a id="security"></a>
## 7. Security 🔒  — **Module Marks: 100**

**Before Cloud** — CIA triad, network security, cryptography basics, compliance.

**In Cloud** — IAM, KMS, CloudHSM, WAF/Shield, Security Groups, SIEM, CSPM & CWPP tools, incident response.

**Labs (35)**  
- Design least-privileged IAM policies (12)  
- Encrypt S3 buckets with KMS + access logging (12)  
- Execute IR playbook simulation (11)

**Project (15)**  
- Secure-by-design 3-tier app: IAM, secrets, WAF & compliance checks. Deliverables: policies (7), automated tests (4), report (4).

**Certs**: Security+, CISSP → AWS Security Specialty, Azure Security Engineer.

**Est. time:** 8–12 weeks

---

<a id="iam"></a>
## 8. IAM (Identity & Access) 🪪  — **Module Marks: 100**

**Before Cloud** — Active Directory, LDAP, Kerberos, SSO patterns.

**In Cloud** — AWS IAM, Azure AD, GCP IAM; SAML/OIDC federation, role mapping, identity management, access reviews, SCIM.

**Labs (35)**  
- Implement IAM roles, permission boundaries & policies (12)  
- SSO/OIDC integration (Azure AD → AWS SSO) (12)  
- Build least-privilege role for CI/CD (11)

**Project (15)**  
- Centralized IAM design for multi-account environment: include provisioning & audit. Deliverables: architecture (4), automation (5), access matrix (3), demo (3).

**Certs**: AD Admin → Azure Identity Engineer, Cloud Identity Architect.

**Est. time:** 6–10 weeks

---

<a id="devops"></a>
## 9. DevOps ⚙️  — **Module Marks: 100**

**Before Cloud** — Git, Jenkins, build servers, artifact repos.

**In Cloud** — CodePipeline, CodeBuild, Azure DevOps, GitHub Actions, IaC (Terraform/CloudFormation/ARM), container runtime & orchestration (EKS/GKE/AKS), pipeline security.

**Labs (35)**  
- Build CI pipeline to produce container images & publish to repo (12)  
- Terraform module with remote state (12)  
- Canary/Blue-Green deploy pipeline + rollback (11)

**Project (15)**  
- Platform build: VPC + EKS + CI/CD + IaC + monitoring. Deliverables: repo (6), Terraform modules (5), demo (4).

**Certs**: Docker, CKA, AWS DevOps Engineer.

**Est. time:** 8–12 weeks

---

<a id="monitoring"></a>
## 10. Monitoring 📊  — **Module Marks: 100**

**Before Cloud** — metrics & logs, SNMP, alerting, runbooks.

**In Cloud** — CloudWatch, Azure Monitor, GCP Operations; centralized logging (ELK/Opensearch), APM (NewRelic, Datadog), distributed tracing (OpenTelemetry, X-Ray).

**Labs (35)**  
- Create dashboards + alarms for key metrics (12)  
- Implement distributed tracing for microservices (12)  
- Build log retention & alerting strategy (11)

**Project (15)**  
- Observability platform for microservices: dashboards, alerts, traces, runbooks. Deliverables: dashboards (5), traces (4), runbooks (3), incident report (3).

**Est. time:** 4–8 weeks

---

<a id="backup--disaster-recovery"></a>
## 11. Backup & Disaster Recovery 💾  — **Module Marks: 100**

**Before Cloud** — tapes, offsite copies, restore drills.

**In Cloud** — AWS Backup, Azure Recovery Services, snapshots, cross-region replication, automated restore verification.

**Labs (35)**  
- Automate EBS snapshots + lifecycle (12)  
- Cross-region RDS backup & restore (12)  
- Simulated failover & restore test (11)

**Project (15)**  
- DR plan for 3-tier app: RTO/RPO analysis + automated failover. Deliverables: DR doc (6), IaC for backups (4), test logs (5).

**Est. time:** 4–6 weeks

---

<a id="ai-ml"></a>
## 12. AI / ML 🤖  — **Module Marks: 100**

**Before Cloud** — Python, ML basics, model validation, experimentation.

**In Cloud** — SageMaker, Vertex AI, Azure ML: training, model registry, endpoint deployment, MLOps, AutoML.

**Labs (35)**  
- Train model on SageMaker + deploy endpoint (12)  
- Build retraining CI for models (12)  
- Implement model monitoring & drift detection (11)

**Project (15)**  
- End-to-end ML pipeline: data ingestion → training → model registry → deployment → monitoring. Deliverables: notebook (5), pipeline config (5), monitoring plan (5).

**Certs**: AWS ML Specialty, Azure AI Engineer.

**Est. time:** 8–12 weeks

---

<a id="iot"></a>
## 13. IoT 📡  — **Module Marks: 100**

**Before Cloud** — embedded systems, MQTT, device firmware, gateways.

**In Cloud** — AWS IoT Core, Azure IoT Hub, device provisioning, device security, edge computing, stream processing.

**Labs (35)**  
- Register & provision devices with IoT Core (12)  
- Secure device-to-cloud connection (10)  
- Build data pipeline: Kinesis / IoT Analytics → Lambda (13)

**Project (15)**  
- Fleet telemetry system: device auth, telemetry ingestion, processing & dashboard. Deliverables: device simulator (5), ingestion pipeline (5), dashboard & cost estimate (5).

**Certs**: IoT fundamentals, AWS IoT Specialty.

**Est. time:** 6–10 weeks

---

<a id="finops"></a>
## 14. FinOps 💰  — **Module Marks: 100**

**Before Cloud** — IT budgeting, CapEx vs Opex, unit-cost analysis.

**In Cloud** — Cost Explorer, Azure Cost Management, budgets & alerts, tag governance, RI & Savings Plans, rightsizing, chargeback.

**Labs (35)**  
- Tagging + cost allocation dashboard (12)  
- Rightsize test + cost comparison (12)  
- Savings plan / RI POC & savings calc (11)

**Project (15)**  
- FinOps: build finance dashboard + governance plan that reduces monthly spend. Deliverables: dashboard (6), governance doc (4), POC (5).

**Certs**: FinOps Foundation Practitioner.

**Est. time:** 4–8 weeks

---

<a id="development--testing"></a>
## 15. Development & Testing 🛠️ (DevTest) — **Module Marks: 100**

**Purpose:** Make developing, testing and releasing software more reliable and automated — critical for cloud-native engineering.

**Before Cloud** — SDLC basics, unit/integration/E2E testing, TDD/BDD, test environments, manual QA.

**In Cloud** — Test automation frameworks in CI, parallel test execution on cloud runners, device farms, synthetic testing, chaos engineering basics.

**Key topics (Before → Cloud)**  
- Unit / Integration / E2E → Unit tests in CI, integration test environments in ephemeral infra  
- TDD / BDD → Test pipelines in GitHub Actions / CodePipeline  
- Load & Performance → JMeter/Gatling in cloud runners, distributed load (k6 cloud)  
- Security & Pen-testing → SAST/DAST in pipelines (SonarQube, OWASP ZAP), IaC scanning

**Labs (35)**  
- Lab A: Build CI job that runs unit + integration tests & reports (12)  
- Lab B: Run distributed load test using cloud instances or k6 Cloud (12)  
- Lab C: Integrate SAST and DAST into pipeline & fail build on high severity (11)

**Project (15)**  
- End-to-end CI + testing platform: automated tests, performance testing, SAST/DAST, test infra as code. Deliverables: test repo (6), pipeline (5), test reports (4).

**Certs & Career**  
- ISTQB (foundational), Automation Engineer certifications, Cloud Dev/Test specializations. Roles: QA Engineer → SDET → Test Architect → Head of Quality.

**Real-world**: Automate integration tests in ephemeral environments that spin up via Terraform on each pull request.

**Est. time:** 6–10 weeks

---

---

## 🧭 Study Plans (two recommended)
**12-week accelerated** (foundational full-stack)  
- Weeks 1–2: Networking, OS, Compute basics  
- Week 3: Storage & Databases fundamentals  
- Week 4: Security & IAM basics  
- Week 5: DevOps fundamentals & IaC  
- Week 6: Monitoring & Backup/DR  
- Week 7: Middleware & Compute advanced (containers)  
- Week 8: Databases advanced + DR  
- Week 9: AI/ML & IoT intros  
- Week 10: FinOps & DevTest practices  
- Week 11: Project sprint (capstone)  
- Week 12: Interview prep & certification planning

**24-week deep-dive** (specialist tracks)  
- Weeks 1–4: Networking deep + cert prep  
- Weeks 5–8: Security & IAM  
- Weeks 9–12: DevOps, Containers, Monitoring + CKA prep  
- Weeks 13–16: Databases + Storage architecture  
- Weeks 17–20: Observability + Backup/DR + FinOps  
- Weeks 21–24: AI/ML, IoT, DevTest + Final Capstone

---

## 🧾 Assessment Rubric & Grading
**Module Score (100)**  
- Theory / MCQ: 40  
- Hands-on Labs: 35  
- Project: 15  
- Interview/Soft Skills: 10

**Project Rubric**  
- Functionality (40%)  
- Code / IaC Quality (20%)  
- Security / Best Practices (20%)  
- Documentation & Presentation (20%)

**Lab Rubric**  
- Reproducibility (40%)  
- Completeness (40%)  
- Test/Validation (20%)

**Pass Criteria (per module)**  
- Module score >= 60 AND at least 50% in Theory & Labs individually.

---

## 🗣️ Interview Prep & Sample Questions
**General tips:** prepare diagrams, use STAR stories (S/T/A/R), practice whiteboarding, have 2–3 measurable impact stories.

**Sample technical questions by domain (pick & practice):**
- Networking: Design cross-region connectivity for high-throughput data replication.
- Storage: How to design an archive solution for petabytes — tradeoffs?
- Compute: Stateless vs stateful scaling strategies.
- Security/IAM: Designing least-privilege for CI/CD pipeline access.
- DevOps: Show a CI/CD pipeline including canary deployment & rollback.
- Databases: When choose RDS vs DynamoDB vs Aurora Serverless?
- FinOps: Plan to reduce a 3-month projected cloud spend by 20%.
- DevTest: How to run reliable integration tests for microservices in CI?

---

## 📄 Resume & Portfolio Quick Fixes
- Headline: “Cloud Engineer | AWS & Kubernetes | FinOps-aware”  
- Use metrics: “Reduced infra cost by 30% using RI & autoscaling”  
- Projects: Link 3 repos with README, diagrams, IaC, demo vids (3–5 min).  
- Add certs + exam dates.  
- Add one-line impact statements per role.

---

## 💡 Project Ideas & Portfolio Guidance
**Beginner (20–30 marks)**  
- Static site on S3 + CloudFront + TLS  
- Simple REST API on EC2 with ALB + Auto-scaling

**Intermediate (50–70 marks)**  
- K8s microservices with CI/CD + APM  
- Multi-AZ RDS + read replica & failover

**Advanced (100 marks)**  
- Full platform: VPC + EKS + RDS + CI/CD + Observability + FinOps dashboard  
- End-to-end ML pipeline with retraining & monitoring

**Presentation checklist:** Architecture PDF, GitHub repo, IaC, demo video, cost & performance notes.

---

## 📊 Progress Tracker (fillable)
| Domain | Module Score /100 | Completed (Y/N) | Notes / Links |
|--------|------------------:|:---------------:|---------------|
| Networking |  |  |  |
| Storage |  |  |  |
| Compute |  |  |  |
| Operating Systems |  |  |  |
| Middleware |  |  |  |
| Databases |  |  |  |
| Security |  |  |  |
| IAM |  |  |  |
| DevOps |  |  |  |
| Monitoring |  |  |  |
| Backup & DR |  |  |  |
| AI/ML |  |  |  |
| IoT |  |  |  |
| FinOps |  |  |  |
| Development & Testing |  |  |  |

**Total (1500)**: ______  — **Normalized (100)**: ______

---

## 📎 Appendix — Cheat-sheets & Commands
**IaC best practice:** version control your code, use modules, remote state, secrets in a vault.

**Tagging keys (must-haves):** `Environment`, `Owner`, `Project`, `CostCenter`, `Criticality`.

**AWS CLI essentials (replace placeholders):**
```bash
# create S3 bucket
aws s3 mb s3://your-unique-bucket-name-12345

# run an EC2 instance
aws ec2 run-instances --image-id ami-0123456789abcdef0 --count 1 --instance-type t3.medium --subnet-id subnet-0abc123 --associate-public-ip-address

# create EBS snapshot
aws ec2 create-snapshot --volume-id vol-0abcd1234 --description "daily-backup"
