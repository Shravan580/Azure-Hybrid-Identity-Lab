# Azure-Hybrid-Identity-Lab

# Overview
This project demonstrates the implementation of a hybrid identity environment by integrating on-premises Active Directory with Microsoft Entra ID. The objective was to understand enterprise identity management, governance, synchronization concepts, and migration planning.


# Environment
# On-Premises

- Windows Server 2025
- Active Directory Domain Services (AD DS)
- Domain: contoso.local
- DNS integrated with Active Directory

# Cloud

- Microsoft Entra ID
- Microsoft Entra Provisioning Agent
- Microsoft Entra Cloud Sync

#  Active Directory Design


# Organizational Units
contoso.local
│
├── IT
├── Developer
└── Support
Security Groups
GG_IT_Admins
GG_Developers
GG_Support

# Activities Performed

- Installed and configured Active Directory Domain Services
- Promoted Windows Server to a Domain Controller
- Created Organizational Units (OUs)
- Created domain users and security groups
- Implemented Group Policy Objects (GPOs)
- Configured password and security policies


Hybrid Identity Integration
Architecture
On-Premises Active Directory
(contoso.local)

        │

        ▼

Microsoft Entra Provisioning Agent

        │

        ▼

Microsoft Entra ID

        │

        ▼

# Azure RBAC
Achievements

- Created Microsoft Entra administrator account
- Installed Microsoft Entra Provisioning Agent
- Registered Cloud Sync Agent successfully
- Connected Active Directory to Microsoft Entra ID
- Explored hybrid identity synchronization architecture


# Challenges Encountered
While creating Cloud Sync configurations, a Microsoft Entra ID P1/P2 license requirement was encountered.


# Troubleshooting Performed

- Verified Domain Admin permissions
- Verified Enterprise Admin permissions
- Verified Global Administrator access
- Tested HTTPS connectivity to Microsoft endpoints
- Reviewed provisioning agent logs
- Successfully registered the provisioning agent


# Skills Learned

- Active Directory Administration
- Domain Controller Management
- DNS Fundamentals
- Organizational Unit Design
- Group Policy Management
- Security Group Administration
- Microsoft Entra ID
- Hybrid Identity Concepts
- Identity Governance
- Azure RBAC
- Troubleshooting & Diagnostics


# Screenshots

Screenshots/

# Domain Controller

<img width="1872" height="1077" alt="image" src="https://github.com/user-attachments/assets/f828d7c0-44ae-4691-9dd0-b94421361474" />


#  Active Directory Users

<img width="1043" height="898" alt="image" src="https://github.com/user-attachments/assets/3a6b362f-c046-4476-94f3-8f63e63da64f" />

<img width="1083" height="912" alt="image" src="https://github.com/user-attachments/assets/36d79ae8-02e9-4759-9590-36a0e5a49546" />

<img width="1075" height="901" alt="image" src="https://github.com/user-attachments/assets/042568b8-1ada-4d0f-be0c-f3f41a3662b4" />


# Organizational Units

<img width="252" height="661" alt="image" src="https://github.com/user-attachments/assets/1350d0e1-cca1-4376-b788-6da6aa2c79c2" />



# Security Groups

<img width="1061" height="558" alt="image" src="https://github.com/user-attachments/assets/9c6dd391-8adb-4cd3-8a12-85d18ba82c6c" />



# Group Policy Management

<img width="1390" height="887" alt="image" src="https://github.com/user-attachments/assets/a58eefc6-29ad-4bd7-a3e4-2f15271a8b60" />


# Provisioning Agent

<img width="1073" height="732" alt="Screenshot 2026-11-01 181212" src="https://github.com/user-attachments/assets/de76dc4f-7cef-433d-b601-59cade1c4af1" />


# Cloud Sync Configuration 

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/b94a9c7b-a074-4862-9eae-55455a5d2447"/>



# Learning Outcome

This project provided hands-on experience with enterprise identity management and hybrid identity architecture by integrating traditional Active Directory concepts with Microsoft Entra ID services.




