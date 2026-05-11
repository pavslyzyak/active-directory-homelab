# Active Directory Homelab – Windows Server 2022

## Overview

This project demonstrates the creation and administration of a Windows Server 2022 Active Directory homelab environment using Oracle VirtualBox.

The lab was built to simulate a basic enterprise domain environment and to practise Active Directory administration, user management, organisational unit structure, group management, workstation domain joining, Group Policy Management, and PowerShell administration.

---

## Technologies Used

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy Management
- PowerShell
- Oracle VirtualBox
- Windows 11 Client

---

## Lab Objectives

- Configure Windows Server 2022
- Promote server to Domain Controller
- Create a new Active Directory forest and domain
- Configure Organisational Units (OUs)
- Create and manage users
- Disable user accounts
- Reset user passwords
- Create and manage security groups
- Add users to groups
- Join workstation to domain
- Use PowerShell to retrieve domain and user information
- Explore Group Policy Management

---

## Domain Information

| Setting | Value |
|---|---|
| Domain Name | pavlab.local |
| Domain Controller | DC01 |
| Client Device | WIN11-CLIENT |
| Server OS | Windows Server 2022 |
| Virtualisation | Oracle VirtualBox |

---

## Key Tasks Completed

### Active Directory Configuration
- Installed Active Directory Domain Services
- Promoted server to Domain Controller
- Created new forest and domain

### Organisational Unit Structure
- Created custom OUs:
  - HR
  - IT
  - Workstations
  - Disabled Users

### User Administration
- Created domain user accounts
- Disabled user accounts
- Reset user passwords
- Configured account properties

### Group Administration
- Created IT-Support security group
- Added users to security groups

### Workstation Management
- Joined Windows 11 client machine to domain

### PowerShell Administration
- Retrieved domain configuration information
- Queried Active Directory user accounts using PowerShell

### Group Policy
- Opened and explored Group Policy Management Console (GPMC)

---

## Screenshots Included

This repository contains screenshots demonstrating:
- Server configuration
- AD DS deployment
- OU structure
- User management
- Password resets
- Group membership
- Workstation domain join
- Group Policy Management
- PowerShell administration

---

## Skills Demonstrated

- Windows Server Administration
- Active Directory Administration
- Identity and Access Management (IAM)
- Group Policy Management
- PowerShell Fundamentals
- Domain Administration
- User and Group Management
- Windows Networking Fundamentals

---

## Future Improvements

- Implement Group Policy Objects (GPOs)
- Configure password policies
- Add file share permissions
- Implement roaming profiles
- Configure remote administration
- Integrate SIEM monitoring

---

## Author

Pav Slyzyak

Aspiring SOC Analyst and Cybersecurity Professional
