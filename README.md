# Active-Directory-Home-Lab
Active Directory home lab using Windows Server 2022 and Windows 10 clients. Covers domain setup, users, groups, GPOs, DNS, DHCP, and troubleshooting.
# Active Directory Home Lab – Windows Server 2022

Project Overview
This project demonstrates the design, setup, and configuration of an Active Directory home lab using Windows Server 2022 and Windows 10 virtual machines.  
The lab simulates a real-world corporate domain environment and is built to practice IT Support (L1/L2) and Junior System Administrator tasks.

This project focuses on hands-on implementation of Active Directory, DNS, DHCP, Group Policy, and domain-joined client management.

---

Lab Environment
- Host OS: Windows 10  
- Virtualization Tool: VMware Workstation  
- Domain Controller: Windows Server 2022  
- Client Machine: Windows 10  
- Laptop RAM: 8 GB  
- Network Type: NAT / Internal Network  

---

 Network Architecture
- Windows Server 2022 configured as the Domain Controller  
- DNS installed and managed on the Domain Controller  
- DHCP configured to assign IP addresses to clients  
- Windows 10 client joined to the Active Directory domain  
- Internal network used for secure communication  

---

 Configuration & Tasks Performed
- Installed Windows Server 2022 on VMware
- Configured static IP address for the server
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created a new forest and domain
- Installed and configured DNS
- Installed and configured DHCP
- Created Organizational Units (OUs)
- Created domain users and security groups
- Joined Windows 10 client to the domain
- Configured Group Policy Objects (GPOs)
- Tested domain user login on Windows 10 client
- Performed basic Active Directory troubleshooting

---

 Step-by-Step Implementation
1. Installed Windows Server 2022 virtual machine
2. Assigned static IP and renamed the server
3. Installed AD DS role via Server Manager
4. Promoted the server to a Domain Controller
5. Created domain and forest
6. Verified DNS configuration
7. Installed and configured DHCP service
8. Created users, groups, and OUs in AD
9. Installed Windows 10 client VM
10. Joined Windows 10 client to the domain
11. Tested Group Policies and domain login
12. Verified network connectivity and authentication

---

 Skills Demonstrated
- Active Directory Administration
- Windows Server 2022 Management
- User & Group Management
- Group Policy Management
- DNS & DHCP Configuration
- Domain Join & Authentication
- IT Support & Troubleshooting
- Virtualization using VMware

---

 Screenshots
Screenshots included in this project:
- Windows Server 2022 Domain Controller setup
- Active Directory Users and Computers
- DNS and DHCP configuration
- Group Policy Management Console
- Windows 10 domain login screen

---


- Add File Server with NTFS permissions
- Implement password and account lockout policies
- Add a second Domain Controller
- Configure shared folders with access control
- Enable auditing and logging
- Simulate real-world IT support scenarios

---

 Learning Outcome
This lab provided hands-on experience in building and managing an Active Directory environment similar to what is used in real corporate networks.  
It strengthened my understanding of Windows Server administration and IT support fundamentals.

---

 Disclaimer
This project is created for educational and learning purposes only and does not represent a production environment.

