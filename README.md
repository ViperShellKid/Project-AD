🛡️ Active Directory Home Lab with Splunk SIEM

📌 Project Overview

This project demonstrates the setup of a complete Active Directory Home Lab using VMware, Windows Server 2022, Windows 10, and Splunk Enterprise for monitoring and log analysis.

The lab was built to practice:

🖥️ Active Directory Administration
⚙️ Windows Server Management
📊 SIEM Monitoring
📑 Sysmon Log Collection
🔐 Group Policy Management
👤 Domain User Management
🕵️ SOC & DFIR Fundamentals
🏗️ Lab Environment

Component	Details
🖥️ Hypervisor	VMware Workstation
🛠️ Domain Controller	Windows Server 2022
💻 Client Machine	Windows 10 Pro
📊 SIEM Solution	Splunk Enterprise
🔍 Monitoring Tool	Sysmon
🌐 Domain Name	MyDFIR.local
📡 Network Range	192.168.80.0/24
🧰 Technologies Used

VMware Workstation
Windows Server 2022
Windows 10 Pro
Active Directory Domain Services (AD DS)
DNS Server
Group Policy Management
Splunk Enterprise
Sysmon
PowerShell
Windows Event Viewer

🎯 Project Objectives

✅ Create an Active Directory domain environment
✅ Configure DNS and Domain Controller
✅ Join Windows 10 machine to domain
✅ Create and manage domain users
✅ Configure Group Policies (GPO)
✅ Install and configure Splunk
✅ Monitor Windows logs using Sysmon
✅ Practice SOC and DFIR workflows

🚀 Project Walkthrough
1️⃣ Windows 10 Client Setup
Installed Windows 10 Pro VM
Configured network settings
Connected client machine to domain

🔧 Key Tasks
Configured DNS server IP manually
Joined Windows 10 machine to MyDFIR.local
Verified domain login successfully

2️⃣ Windows Server 2022 Setup
Installed Windows Server 2022
Configured Administrator account
Verified server IP using:
ipconfig

🌐 Server IP
192.168.80.136
3️⃣ Active Directory Installation

Installed:

✅ Active Directory Domain Services (AD DS)
✅ DNS Server
✅ Group Policy Management

⚙️ AD Configuration
Promoted server to Domain Controller
Created new forest:
MyDFIR.local
Configured DNS automatically
Restarted server after installation
4️⃣ 👤 User Creation & Management

Used:

Active Directory Users and Computers
🛠️ Actions Performed
Created new domain users
Managed groups and permissions
Verified user accounts successfully
👨 Example User
joseph vijay

5️⃣ 💻 Windows 10 Domain Join
🧩 Steps Completed
Configured DNS to point to Domain Controller
Opened System Properties
Joined machine to:
MyDFIR.local
Logged in using domain credentials
Verified using:
whoami
✅ Output
mydfir\vijay
6️⃣ 🔐 Group Policy Management (GPO)

Configured Group Policy to:

🚫 Restrict Control Panel access
⚙️ Manage user-level policies
📂 GPO Path

User Configuration → Policies → Administrative Templates → Control Panel
🛡️ Policy Configured
Prohibit access to Control Panel and PC settings
7️⃣ 📊 Splunk SIEM Integration

Installed and configured:

Splunk Enterprise
Sysmon log forwarding
📑 Logs Monitored
🔐 Security Logs
⚙️ System Logs
📄 Application Logs
🕵️ Sysmon Operational Logs
🔍 Example SPL Query
index="endpoint"

🧠 Skills Demonstrated
🛡️ Active Directory Administration
⚙️ Windows Server Management
🌐 DNS Configuration
👥 Domain User Management
🔐 Group Policy Management
📊 SIEM Monitoring
🕵️ Sysmon Configuration
📑 Log Analysis
🖥️ Windows Event Monitoring
🔎 DFIR Fundamentals
🚨 SOC Operations
📸 Screenshots Included
🏢 Active Directory

AD DS Installation
Domain Controller Promotion
User Creation
Active Directory Users and Computers

💻 Windows 10 Client
DNS Configuration
Domain Join Process
Domain Login Verification

📊 Splunk Monitoring
Splunk Dashboard
Sysmon Log Monitoring
Windows Event Collection

🔐 Group Policy
Restrict Control Panel GPO
Policy Configuration

✅ Project Outcome

Successfully built a fully functional Active Directory Home Lab integrated with Splunk SIEM for centralized log monitoring and security analysis.

This project improved practical knowledge in:

🔵 Blue Team Operations
🛡️ Security Monitoring
⚙️ Windows Administration
📊 SIEM Management
🚨 Threat Detection Basics
🔍 DFIR Workflows
