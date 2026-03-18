# 🖥️ Phase 2: System Administrator Track (Months 4-12)

> **From Help Desk to System Administrator - Complete Path**

---

## 🎯 Phase 2 Overview

**Prerequisites:** Phase 1 (Help Desk Fundamentals) completed

**Duration:** 9 months (Months 4-12)

**Goal:** Transition from Help Desk to System Administrator role

**Expected Outcome:** Manage 50+ servers, automate routine tasks, handle escalations

---

## 📋 Module 2.1: Active Directory Deep Dive (Month 4-5)

### Learning Objectives
- Master Active Directory administration
- Understand AD architecture and replication
- Implement Group Policy effectively
- Troubleshoot AD issues systematically

### Topics

#### Week 1-2: AD Architecture
1. AD database structure (NTDS.dit)
2. Forest, Tree, Domain, OU hierarchy
3. FSMO roles (what, where, when to transfer/seize)
4. AD replication (how it works, troubleshooting)
5. Global Catalog and its importance
6. AD sites and services (for multi-location)

#### Week 3-4: User & Group Management
1. User account lifecycle (create → modify → disable → delete)
2. Group types and scopes (Domain Local, Global, Universal)
3. AGDLP/AGUDLP best practices
4. Bulk operations (PowerShell for mass user creation)
5. Service accounts (password management, security)
6. Managed Service Accounts (gMSA)

#### Week 5-6: Group Policy
1. GPO structure and processing order (LSDOU)
2. Common GPOs (drive maps, printers, security settings)
3. GPO filtering (security, WMI)
4. GPO troubleshooting (rsop, gpresult)
5. GPO backup and migration
6. Security policies (password, lockout, audit)

#### Week 7-8: AD Troubleshooting
1. Common AD issues (authentication, replication, DNS)
2. AD diagnostic tools (ADUC, ADSI Edit, LDP)
3. Event logs to monitor (4624, 4625, 4740, etc.)
4. AD database maintenance (offline defrag, integrity check)
5. Disaster recovery (authoritative vs non-authoritative restore)
6. AD Recycle Bin

### Hands-on Labs

| Lab | Description | Time |
|-----|-------------|------|
| **2.1.1** | Build multi-domain forest (1 forest, 2 domains) | 4 hours |
| **2.1.2** | Create 100 users via PowerShell (CSV import) | 2 hours |
| **2.1.3** | Implement AGDLP for file access | 3 hours |
| **2.1.4** | Configure 10 different GPOs | 6 hours |
| **2.1.5** | GPO filtering scenarios (5 exercises) | 3 hours |
| **2.1.6** | Troubleshoot replication issues (simulated) | 4 hours |
| **2.1.7** | FSMO role transfer and seizure | 2 hours |
| **2.1.8** | AD database backup and restore | 4 hours |
| **2.1.9** | Implement AD Recycle Bin and recover objects | 2 hours |
| **2.1.10** | Security audit (find misconfigurations) | 4 hours |
| **2.1.11** | Create AD documentation template | 2 hours |
| **2.1.12** | Capstone: Full AD design for 500-user company | 8 hours |

### Resources
- Video: [Active Directory Full Course](https://www.youtube.com/watch?v=...)
- Microsoft Docs: [Active Directory Documentation](https://docs.microsoft.com/en-us/windows-server/identity/active-directory/)
- Book: "Active Directory Administration Cookbook"

### Assessment
- Practical exam: Complete 5 AD troubleshooting scenarios in 90 minutes
- Written exam: AD architecture and concepts (50 questions)
- Capstone project: AD design document for hypothetical company

---

## 📋 Module 2.2: Windows Server Administration (Month 5-6)

### Learning Objectives
- Install and configure Windows Server 2019/2022
- Manage server roles and features
- Implement storage solutions
- Monitor and maintain server health

### Topics

#### Week 1-2: Server Installation & Configuration
1. Windows Server versions (Standard vs Datacenter)
2. Installation options (Desktop Experience vs Core)
3. Server Manager and Windows Admin Center
4. PowerShell for server management
5. Initial configuration (networking, updates, roles)
6. Server hardening basics

#### Week 3-4: Server Roles
1. File Server (FSRM, quotas, file screening)
2. Print Server (deployment, management)
3. Web Server (IIS basics)
4. DHCP Server (scopes, reservations, failover)
5. DNS Server (zones, forwarding, troubleshooting)
6. Remote Access (VPN, DirectAccess)

#### Week 5-6: Storage
1. Disk types (basic, dynamic, GPT, MBR)
2. RAID levels (0, 1, 5, 6, 10)
3. Storage Spaces (Windows software RAID)
4. iSCSI configuration
5. DFS (Distributed File System)
6. Backup strategies (Windows Server Backup, third-party)

#### Week 7-8: Monitoring & Maintenance
1. Performance Monitor (key counters)
2. Event Viewer (critical logs)
3. Resource Monitor
4. Task Scheduler (automated maintenance)
5. WSUS (Windows Server Update Services)
6. Server migration (migration tools, side-by-side)

### Hands-on Labs

| Lab | Description | Time |
|-----|-------------|------|
| **2.2.1** | Install Windows Server 2022 (Desktop & Core) | 2 hours |
| **2.2.2** | Configure Server Core via PowerShell | 4 hours |
| **2.2.3** | Set up File Server with quotas and screening | 3 hours |
| **2.2.4** | Configure DHCP with failover | 3 hours |
| **2.2.5** | DNS configuration and troubleshooting | 4 hours |
| **2.2.6** | IIS web server setup with multiple sites | 3 hours |
| **2.2.7** | Storage Spaces implementation | 3 hours |
| **2.2.8** | DFS namespace and replication | 4 hours |
| **2.2.9** | WSUS deployment and configuration | 4 hours |
| **2.2.10** | Performance baseline and monitoring | 3 hours |
| **2.2.11** | Server migration (physical to virtual) | 6 hours |
| **2.2.12** | Disaster recovery drill (full server restore) | 4 hours |

### Resources
- Microsoft Learn: [Windows Server Learning Path](https://docs.microsoft.com/learn/windows-server/)
- Video: [Windows Server 2022 Full Course](https://www.youtube.com/watch?v=...)
- Exam: AZ-800/801 (Windows Server Hybrid Administrator)

### Assessment
- Practical: Deploy and configure 5 server roles in 4 hours
- Troubleshooting exam: Fix 5 broken server configurations
- Documentation: Server deployment runbook

---

## 📋 Module 2.3: Linux Administration (Month 7-8)

### Learning Objectives
- Navigate and administer Linux systems confidently
- Manage users, permissions, and packages
- Configure common services (SSH, web, file sharing)
- Troubleshoot Linux issues effectively

### Topics

#### Week 1-2: Linux Fundamentals
1. Linux distributions (RHEL, Ubuntu, CentOS differences)
2. File system hierarchy (/etc, /var, /home, etc.)
3. Basic commands (ls, cd, cp, mv, rm, cat, grep, find)
4. File permissions (chmod, chown, ACLs)
5. Text editors (nano, vim basics)
6. Package management (apt, yum, dnf)

#### Week 3-4: User & Process Management
1. User and group management
2. Sudo configuration
3. Process management (ps, top, kill, nice)
4. Systemd services (start, stop, enable)
5. Cron jobs and scheduled tasks
6. Log management (/var/log, journalctl)

#### Week 5-6: Network Services
1. SSH configuration and key-based auth
2. Network configuration (ip, nmcli)
3. Firewall (ufw, firewalld, iptables basics)
4. Web server (Apache/Nginx basics)
5. File sharing (Samba, NFS)
6. Remote monitoring (top, htop, iotop)

#### Week 7-8: Troubleshooting & Scripting
1. Boot process and troubleshooting
2. Disk management (fdisk, mkfs, mount)
3. LVM (Logical Volume Manager)
4. Basic Bash scripting (variables, loops, conditions)
5. Log analysis (grep, awk, sed for logs)
6. Performance troubleshooting

### Hands-on Labs

| Lab | Description | Time |
|-----|-------------|------|
| **2.3.1** | Install Ubuntu Server 22.04 (minimal) | 1 hour |
| **2.3.2** | Command line navigation (20 exercises) | 4 hours |
| **2.3.3** | User management (create 20 users via script) | 3 hours |
| **2.3.4** | File permissions scenarios (10 exercises) | 3 hours |
| **2.3.5** | SSH hardening (disable root, key-only) | 2 hours |
| **2.3.6** | Apache web server with virtual hosts | 4 hours |
| **2.3.7** | Samba file server configuration | 3 hours |
| **2.3.8** | Firewall configuration (ufw/firewalld) | 2 hours |
| **2.3.9** | Bash script for system health check | 4 hours |
| **2.3.10** | LVM configuration and expansion | 3 hours |
| **2.3.11** | Log analysis and alerting script | 4 hours |
| **2.3.12** | Troubleshoot 5 broken Linux scenarios | 6 hours |
| **2.3.13** | Backup script with rotation | 3 hours |
| **2.3.14** | Docker installation and basic containers | 4 hours |
| **2.3.15** | Monitoring setup (Prometheus + Grafana) | 6 hours |
| **2.3.16** | Security hardening checklist | 4 hours |
| **2.3.17** | Migration: Windows file server to Linux | 8 hours |
| **2.3.18** | Capstone: Full Linux server deployment | 10 hours |

### Resources
- Video: [Linux Administration Full Course](https://www.youtube.com/watch?v=...)
- Website: [Linux Journey](https://linuxjourney.com/)
- Book: "How Linux Works" by Brian Ward
- Certification: Linux+ or LFCS

### Assessment
- Practical exam: Complete 10 Linux tasks in 2 hours
- Script submission: System health monitoring script
- Capstone: Deploy and document a production-ready Linux server

---

## 📋 Module 2.4: Advanced Networking (Month 8-9)

### Learning Objectives
- Design and implement enterprise network solutions
- Troubleshoot complex network issues
- Implement network security best practices
- Understand routing and switching fundamentals

### Topics

#### Week 1-2: Advanced TCP/IP
1. Subnetting (advanced, VLSM)
2. Routing concepts (static, dynamic)
3. VLANs and trunking
4. NAT and PAT
5. IPv6 fundamentals

#### Week 3-4: Network Services
1. Advanced DHCP (options, reservations)
2. Advanced DNS (conditional forwarding, zones)
3. NTP (time synchronization)
4. Load balancing concepts
5. Proxy servers

#### Week 5-6: Network Security
1. Firewall types and configuration
2. VPN (site-to-site, client-to-site)
3. Network segmentation
4. 802.1X authentication
5. IDS/IPS basics

#### Week 7-8: Troubleshooting
1. Network monitoring tools (PRTG, Nagios)
2. Packet analysis (Wireshark deep dive)
3. Network documentation
4. Common network issues and fixes
5. Performance optimization

### Hands-on Labs

| Lab | Description | Time |
|-----|-------------|------|
| **2.4.1** | Advanced subnetting (30 exercises) | 6 hours |
| **2.4.2** | VLAN configuration (managed switches or virtual) | 4 hours |
| **2.4.3** | Site-to-site VPN configuration | 4 hours |
| **2.4.4** | Load balancer setup (HAProxy or nginx) | 4 hours |
| **2.4.5** | Wireshark packet analysis (10 scenarios) | 6 hours |
| **2.4.6** | Network monitoring setup (PRTG free) | 4 hours |
| **2.4.7** | Firewall rules implementation | 4 hours |
| **2.4.8** | Network troubleshooting (10 scenarios) | 8 hours |

### Resources
- Video: [CCNA Full Course](https://www.youtube.com/watch?v=...)
- Tool: Cisco Packet Tracer
- Certification: Network+ or CCNA

### Assessment
- Practical: Design network for 3-office company
- Troubleshooting: Fix 5 network issues in 90 minutes
- Documentation: Complete network diagram and IP schema

---

## 📋 Module 2.5: Virtualization (Month 9-10)

### Learning Objectives
- Deploy and manage virtualization platforms
- Optimize VM performance
- Implement high availability
- Manage virtual infrastructure

### Topics

#### Week 1-3: VMware vSphere
1. ESXi installation and configuration
2. vCenter Server deployment
3. VM creation and management
4. vMotion and Storage vMotion
5. High Availability (HA)
6. Distributed Resource Scheduler (DRS)

#### Week 4-6: Hyper-V
1. Hyper-V installation
2. VM creation and management
3. Checkpoints and replication
4. Live Migration
5. Failover Clustering basics

#### Week 7-8: Management & Optimization
1. Resource allocation (CPU, RAM, storage)
2. Performance monitoring
3. Capacity planning
4. Backup strategies for VMs
5. Disaster recovery

### Hands-on Labs

| Lab | Description | Time |
|-----|-------------|------|
| **2.5.1** | Install ESXi 7/8 (nested virtualization) | 2 hours |
| **2.5.2** | Deploy vCenter Server Appliance | 2 hours |
| **2.5.3** | Create and manage 10 VMs | 4 hours |
| **2.5.4** | Configure vMotion | 3 hours |
| **2.5.5** | Implement HA cluster | 4 hours |
| **2.5.6** | Hyper-V cluster setup | 4 hours |
| **2.5.7** | VM backup and restore | 3 hours |
| **2.5.8** | Performance optimization | 4 hours |

### Resources
- VMware: [Free vSphere Training](https://www.vmware.com/services/training/)
- Microsoft: [Hyper-V Documentation](https://docs.microsoft.com/en-us/virtualization/)
- Certification: VCP or AZ-104

### Assessment
- Practical: Deploy and configure full virtual infrastructure
- Design document: Virtualization solution for 100-VM environment

---

## 📋 Module 2.6: Backup & Disaster Recovery (Month 10)

### Learning Objectives
- Design backup strategies
- Implement disaster recovery plans
- Test and validate backups
- Meet RPO/RTO requirements

### Topics

1. Backup types (full, incremental, differential)
2. 3-2-1 backup rule
3. Backup solutions (Veeam, Commvault, native)
4. Disaster Recovery planning
5. RPO (Recovery Point Objective) and RTO (Recovery Time Objective)
6. Business Continuity Planning
7. DR testing and documentation

### Hands-on Labs

| Lab | Description | Time |
|-----|-------------|------|
| **2.6.1** | Implement 3-2-1 backup strategy | 4 hours |
| **2.6.2** | Configure Veeam Community Edition | 4 hours |
| **2.6.3** | Test full system restore | 4 hours |
| **2.6.4** | Create DR runbook | 4 hours |
| **2.6.5** | DR drill (simulated disaster) | 6 hours |
| **2.6.6** | Document RPO/RTO for critical systems | 3 hours |
| **2.6.7** | Backup verification automation | 3 hours |
| **2.6.8** | Cloud backup integration | 4 hours |

### Assessment
- DR plan document for hypothetical company
- Practical: Complete backup and restore drill

---

## 📋 Module 2.7: Monitoring & Alerting (Month 11)

### Learning Objectives
- Implement comprehensive monitoring
- Configure meaningful alerts
- Create dashboards and reports
- Predict issues before they occur

### Topics

1. Monitoring types (infrastructure, application, logs)
2. Monitoring tools (PRTG, Nagios, Zabbix, Prometheus)
3. Log aggregation (ELK Stack, Splunk)
4. Alert configuration (avoiding alert fatigue)
5. Dashboard creation
6. Trend analysis and capacity planning

### Hands-on Labs

| Lab | Description | Time |
|-----|-------------|------|
| **2.7.1** | Deploy PRTG or Zabbix | 4 hours |
| **2.7.2** | Configure 50+ monitors | 6 hours |
| **2.7.3** | Set up alerting (email, SMS, Teams) | 3 hours |
| **2.7.4** | Create executive dashboard | 4 hours |
| **2.7.5** | ELK Stack deployment | 6 hours |
| **2.7.6** | Log analysis and correlation | 4 hours |
| **2.7.7** | Capacity planning report | 4 hours |
| **2.7.8** | Predictive alerting setup | 4 hours |

### Assessment
- Monitoring infrastructure deployment
- Dashboard presentation
- Alert configuration review

---

## 📋 Module 2.8: Capstone Project (Month 12)

### Project: Complete Infrastructure Design & Implementation

**Scenario:** Design and implement IT infrastructure for a startup growing from 20 to 200 employees.

### Requirements

1. **Active Directory Design**
   - Forest/domain structure
   - OU hierarchy
   - Group Policy strategy
   - User provisioning automation

2. **Server Infrastructure**
   - Physical vs virtual decisions
   - Server roles and placement
   - High availability design
   - Capacity planning

3. **Network Design**
   - IP addressing scheme
   - VLAN design
   - Security zones
   - Remote access solution

4. **Backup & DR**
   - Backup strategy
   - DR site design (or cloud DR)
   - RPO/RTO definitions
   - Testing schedule

5. **Monitoring**
   - Monitoring architecture
   - Alert configuration
   - Dashboard design
   - Reporting schedule

6. **Documentation**
   - Network diagrams
   - Runbooks for common tasks
   - Disaster recovery procedures
   - Knowledge base articles

### Deliverables

1. **Design Document** (50+ pages)
   - Executive summary
   - Technical design
   - Bill of materials
   - Implementation timeline

2. **Implementation**
   - Working lab environment
   - All configurations documented
   - Screenshots and diagrams

3. **Operations Manual**
   - Daily/weekly/monthly checklists
   - Troubleshooting guides
   - Escalation procedures
   - Contact lists

4. **Presentation**
   - 30-minute presentation
   - Record and upload
   - Peer review

### Time Allocation

- Week 1-2: Design phase
- Week 3-6: Implementation phase
- Week 7-8: Documentation phase
- Week 9-10: Testing and refinement
- Week 11-12: Presentation and review

### Assessment Criteria

| Criteria | Weight |
|----------|--------|
| Technical accuracy | 30% |
| Best practices adherence | 20% |
| Documentation quality | 20% |
| Presentation quality | 15% |
| Innovation/automation | 15% |

---

## 🎓 Phase 2 Completion Criteria

### **Technical Requirements**
- ✅ Complete all 8 modules
- ✅ Pass all module assessments (80%+ score)
- ✅ Complete 100+ hours of hands-on labs
- ✅ Submit capstone project

### **Certification Requirements** (Recommended)
- ✅ CompTIA Network+ OR
- ✅ Microsoft AZ-800/801 OR
- ✅ Linux+ or LFCS

### **Portfolio Requirements**
- ✅ GitHub with 10+ scripts
- ✅ 20+ KB articles
- ✅ Capstone project documentation
- ✅ Network diagrams
- ✅ Runbooks created

### **Job Readiness**
- ✅ Resume updated with Phase 2 skills
- ✅ LinkedIn profile optimized
- ✅ Mock interview completed
- ✅ Applied to 10+ SysAdmin positions

---

## 📊 Phase 2 Timeline

```
Month 4:   Active Directory      ████████████████████████
Month 5:   Windows Server        ████████████████████████
Month 6:   Windows Server (cont) ████████████████████████
Month 7:   Linux Administration  ████████████████████████
Month 8:   Linux + Networking    ████████████████████████
Month 9:   Advanced Networking   ████████████████████████
Month 10:  Virtualization        ████████████████████████
Month 11:  Monitoring            ████████████████████████
Month 12:  Capstone Project      ████████████████████████
```

**Total Duration:** 9 months  
**Total Lab Hours:** 200+ hours  
**Total Study Hours:** 150+ hours

---

**Next:** See `CURRICULUM_PHASE3.md` for DevOps Engineer Track.
