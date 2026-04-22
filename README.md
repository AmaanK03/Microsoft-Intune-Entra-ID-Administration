# Microsoft Intune & Entra-ID Administration Project
<img width="877" height="869" alt="Image" src="https://github.com/user-attachments/assets/37ac632f-cc75-45cc-8303-3456cb976055" />

## 📖 Overview
 This repository documents the setup of a full-scale Microsoft 365 E5 tenant. I configured this environment to practice enterprise-level IT support tasks, specifically focusing on cloud identity management, Intune device enrollment, and automated security workflows

## 🔑  Key Skills Covered

- Microsoft Entra ID user and access management  
- Microsoft Intune device enrolment and mobile device management (MDM)  
- Microsoft 365 user support and troubleshooting (logins, MFA, Outlook, Teams)  
- Basic security configuration (MFA, roles, conditional access)  
- Policy deployment and device compliance monitoring  
- Application deployment and management via Intune  
- Hands-on experience with Microsoft 365 E5 cloud environment  


## 🧩 Project Breakdown  

### Microsoft Intune Setup (Endpoint Management)
<img width="1279" height="589" alt="Image" src="https://github.com/user-attachments/assets/ca2502c7-d67b-40c6-bef2-b5b2affbddb7" />


- Set up **Microsoft Intune** within the Microsoft Endpoint Manager admin centre  
- Configured **Microsoft Entra ID (Azure AD)** for identity and access management  
- Created a cloud-based lab environment (no on-prem servers required)  

Microsoft Intune forms the foundation of this lab as a **Software-as-a-Service (SaaS)** solution, replacing traditional on-prem Active Directory by enabling **cloud-based device management, user authentication, and policy control**.  

As a SaaS platform, Intune is fully hosted and managed by Microsoft, meaning there is no need to maintain physical servers or infrastructure.  

This reflects how modern IT support teams operate today — managing users and devices remotely through Microsoft 365, improving scalability, flexibility, and security compared to traditional on-prem environments.

## 👤 Account Creation (Microsoft Intune / Entra ID)

<img width="600" height="400" alt="User Setup" src="https://github.com/user-attachments/assets/83e0bd0d-a356-470a-974f-10d8d666d373" />

### 🧩 User Setup

- Created a new user within **Microsoft Entra ID (Azure AD)** via the Microsoft 365 admin centre  

- Entered basic user details including:  
  - First name and last name  
  - Display name  
  - Username (UPN format)  

- Enabled **automatic password generation**  

- Configured the account to **require password change on first login**  


<img width="600" height="400" alt="License Assignment" src="https://github.com/user-attachments/assets/34ada7be-4039-4769-b73c-3bfa5f1f8f9b" />

### 🔑 Licence Assignment

- Assigned a **Microsoft 365 Business Premium** licence to the user  

- Set usage location to **United Kingdom** (required for licence activation)  

- Enabled access to core services such as:  
  - Outlook (Exchange Online)  
  - Microsoft Teams  
  - OneDrive  
  - SharePoint  
  - Intune (Endpoint Management)  


<img width="600" height="400" alt="Roles and Permissions" src="https://github.com/user-attachments/assets/ad2472de-289b-4c8a-8764-e799bbb4f565" />

### ⚙️ Roles & Permissions

- Assigned the user as a **standard user (no admin access)**  

- Followed the principle of **least privilege** to reduce security risk  

- Left admin roles (e.g. Global Admin, Exchange Admin) unassigned  

This task demonstrates how IT support provisions user accounts in a modern **cloud-based (SaaS)** environment, ensuring users have the correct access, licences, and security settings from day one.

