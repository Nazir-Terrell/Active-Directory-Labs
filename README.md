# 🧱 Active Directory Infrastructure & Group Policy Labs

## 📌 Project Overview
This repository contains a complete set of labs simulating the deployment and administration of an enterprise-grade Active Directory environment. The project walks through domain setup, domain trees, FSMO roles, user and OU management, replication configuration, group policy creation, software deployment, folder redirection, and delegation of administrative tasks using PowerShell and the AD GUI.

> 🛠️ Designed for educational use, these labs replicate real-world directory services design, security delegation, and policy-based management for a simulated organization: **ABS Corporation**.

---

## 🛠️ Tools & Technologies
- **Windows Server 2019**
- **Active Directory Domain Services (AD DS)**
- **DNS, DHCP, NAT, and Routing**
- **PowerShell AD Cmdlets**
- **Group Policy Management Console (GPMC)**
- **CSVDE & Pester Testing**
- **MMC Snap-ins (Schema, Sites & Services, Trusts)**

---

## ⚙️ Labs & Topics

### 🔧 Forest & Domain Setup
| Lab | Title |
|-----|-------|
| GP01 | Computer Setup (Hyper-V and VM networking) |
| GP02 | Configuring Windows Server as a Firewall (NAT/Routing) |
| GP03 | Establishing AD Prerequisites |
| GP04 | Installing AD – New Forest (`abscorp.com`) |
| GP05 | Creating a Child Domain (`research.abscorp.com`) |
| GP06 | Creating an Additional Domain Tree (`lametech.com`) |

---

### 👑 Domain Management & Logical Design
| Lab | Title |
|-----|-------|
| GP07 | Viewing & Transferring FSMO Roles |
| GP08 | Implementing the Logical OU Design |
| GP09 | Removing a Domain Controller (Lametech.com) |
| GP10 | Configuring AD Replication and Sites |

---

### 👤 AD Objects, Delegation & Security
| Lab | Title |
|-----|-------|
| GP11 | Creating AD Objects (Users, Groups, OUs via GUI and PowerShell) |
| GP12 | Delegating Administrative Control (Least Privilege, Task Delegation) |

---

### 🎯 Group Policy Implementation
| Lab | Title |
|-----|-------|
| GP13 | Creating and Linking GPOs |
| GP14 | Modifying Group Policy Processing (Loopback, Filtering, Inheritance) |
| GP15 | Creating a Central Policy Store |
| GP16 | Folder Redirection via Group Policy |
| GP17 | Configuring Security Settings in GPOs |
| GP18 | Software Deployment via GPOs |

---

### 🧪 Final Practical Assessment
| File | Summary |
|------|---------|
| CIS256-Assessment-Final Practical.docx | Culminating assessment applying AD and GPO concepts to a multi-site organization using AGDLP security model, PowerShell automation, folder permissions, and GPO configuration. |

---

## 🧰 Skills Demonstrated
- Multi-domain AD forest creation and trust management
- FSMO role transfers and schema changes
- Logical OU and object structuring for delegated administration
- Replication scheduling and AD Sites & Services design
- Group Policy creation, inheritance control, and software deployment
- Folder redirection and securing shares via AGDLP model
- PowerShell automation for user/group management
- Administrative task delegation using least privilege principles

---

## 🗂 Folder Structure Recommendation

active-directory-labs/
├── README.md
├── Infrastructure/
│ ├── GP01-Computer Setup.docx
│ ├── GP02-Configuring Firewall.docx
│ └── ... up to GP10
├── Administration/
│ ├── GP11-Creating AD Objects.docx
│ └── GP12-Delegating Control.docx
├── GroupPolicy/
│ ├── GP13-Create Link GPO.docx
│ └── ... up to GP18
├── Assessment/
│ └── CIS256-Final Practical.docx

---

## 👤 Author
**Nazir Terrell**  
Security+ Certified | Cybersecurity Graduate  
ECPI University — CIS256 (Directory Services & Infrastructure)  
Term: 2025  
🔗 [LinkedIn](https://www.linkedin.com/in/nazir-terrell-40a05b217)

---

## ✅ License
This content is intended for academic use only. All labs were performed in isolated virtual environments with no access to production networks.

