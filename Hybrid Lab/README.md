# Hybrid Identity and Microsoft 365 Administration Lab

## Overview

This lab was built to polish my practical skills in **Hybrid Identity, Microsoft 365 administration, Exchange Online, and SharePoint administration** through hands-on configuration in a controlled lab environment.

The goal of this project was to go beyond on-premises Windows Server and Active Directory administration by extending the environment into **Microsoft 365**, **Microsoft Entra ID**, **Hybrid Identity**, **Exchange Online**, and **SharePoint Online**.

This lab demonstrates how on-premises identity infrastructure can be integrated with cloud identity and productivity services to support real-world enterprise administration scenarios.

---

## Lab Objectives

- Create and configure a Microsoft 365 tenant
- Create users and assign administrative roles
- Integrate on-premises Active Directory with Microsoft Entra ID
- Configure hybrid identity synchronization using Entra Connect
- Assign Microsoft 365 and Entra licenses
- Enable identity security features such as SSPR and MFA
- Configure Exchange Online distribution groups for department-based mail flow
- Build a SharePoint-based IT site for asset inventory and internal ticketing

---

## Environment Used

### On-Premises Environment
- Dell PowerEdge R430
- Proxmox
- Windows Server
- Active Directory Domain Services

### Cloud Environment
- Microsoft 365
- Microsoft Entra ID
- Exchange Online
- SharePoint Online

---

# Lab Modules

---

## 1. Microsoft 365 Tenant Creation

### What I did
- Created a new Microsoft 365 tenant
- Configured the initial tenant environment
- Verified tenant details and primary domain

### Skills Demonstrated
- Microsoft 365 tenant setup
- Initial cloud environment preparation
- Tenant verification and administration



---

## 2. User Creation and Administrative Role Assignment

### What I did
- Created multiple users for the lab environment
- Assigned the **Global Administrator** role to a single designated admin account
- Assigned the **Hybrid Identity Administrator** role to a specific user for hybrid identity tasks
- Left other users as standard users for testing and administration scenarios

### Skills Demonstrated
- User lifecycle administration
- Role-based access control
- Least privilege administrative setup



---

## 3. UPN Addition in On-Premises Active Directory

### What I did
- Added a custom UPN suffix in **Active Directory Domains and Trusts**
- Updated selected on-premises users with the new UPN suffix
- Prepared identities for hybrid synchronization with Microsoft Entra ID

### Skills Demonstrated
- UPN suffix management
- Active Directory identity preparation
- Hybrid sign-in readiness



---

## 4. Hybrid Identity Configuration with Microsoft Entra Connect

### What I did
- Downloaded Microsoft Entra Connect Sync
- Installed and configured Microsoft Entra Connect
- Connected the on-premises Active Directory environment to Microsoft Entra ID
- Synchronized on-premises identities to the cloud
- Verified successful user synchronization in the Entra admin center

### Skills Demonstrated
- Hybrid identity implementation
- Entra Connect setup
- On-premises to cloud directory synchronization
- Identity validation and testing


---

## 5. License Assignment in Microsoft 365

### What I did
- Assigned **Microsoft Entra ID P2** licenses to selected users
- Assigned **Microsoft 365 E5** licenses to selected users
- Verified license assignment and service availability

### Skills Demonstrated
- License management
- Service assignment
- Cloud user provisioning



---

## 6. Self-Service Password Reset (SSPR)

### What I did
- Enabled **Self-Service Password Reset**
- Configured authentication methods for password reset
- Applied SSPR settings for lab users
- Validated the configuration for identity recovery scenarios

### Skills Demonstrated
- Identity security administration
- Password recovery configuration
- User self-service feature enablement


---

## 7. Per-User Multi-Factor Authentication (MFA)

### What I did
- Enabled **per-user MFA** for selected users
- Tested the user sign-in flow with MFA registration
- Validated second-factor registration and enforcement

### Skills Demonstrated
- MFA administration
- Identity protection
- Secure sign-in configuration



---

## 8. Exchange Online Distribution Groups and Department Mail Flow

### What I did
- Created department-based distribution groups for:
  - Sales
  - IT
  - HR
  - Operations
- Configured email aliases such as:
  - `sales@org.com`
  - `it@org.com`
  - `hr@org.com`
  - `ops@org.com`
- Added appropriate department users as members
- Tested mail flow so emails sent to each department alias were delivered to all members of that group

### Skills Demonstrated
- Exchange Online administration
- Distribution group creation
- Department-based mail routing
- Mail flow validation


---

## 9. SharePoint IT Site, Asset Inventory, and Ticketing

### What I did
- Created a SharePoint site for IT operations
- Built an **Asset Inventory** list for device and asset tracking
- Built an **IT Ticketing** list for internal issue reporting
- Configured access so:
  - Ticketing could be accessed by users across the organization
  - Asset Inventory access was limited to IT users only

### Skills Demonstrated
- SharePoint site creation
- List-based process design
- Permission management
- Role-based access in SharePoint


---

# Key Skills Demonstrated

- Microsoft 365 Administration
- Microsoft Entra ID Administration
- Hybrid Identity Configuration
- Microsoft Entra Connect Sync
- User and Role Management
- License Assignment
- Self-Service Password Reset (SSPR)
- Multi-Factor Authentication (MFA)
- Exchange Online Distribution Groups
- Department Mail Flow Configuration
- SharePoint Online Administration
- SharePoint Permissions Management

---

# Key Learnings

This lab helped me better understand how modern enterprise environments combine **on-premises infrastructure** with **cloud identity and productivity platforms**.

Some of the most valuable takeaways from this project were:
- how hybrid identity connects traditional Active Directory with Microsoft Entra ID
- how administrative roles should be assigned with least privilege in mind
- how user provisioning and licensing work in Microsoft 365
- how security features like SSPR and MFA improve identity protection
- how Exchange Online distribution groups support structured departmental communication
- how SharePoint can be used to build simple internal operational tools with controlled access

---

# Project Outcome

This lab gave me practical exposure to the administrative workflows involved in:
- setting up a Microsoft 365 environment
- preparing on-premises identities for cloud synchronization
- implementing hybrid identity
- managing users, roles, and licenses
- securing accounts with SSPR and MFA
- supporting collaboration and communication through Exchange and SharePoint

It also helped me build a stronger understanding of how identity, access, communication, and collaboration systems work together in a modern enterprise environment.

---

# Future Improvements

Planned future enhancements for this lab include:
- Conditional Access configuration
- device compliance and Intune-related testing
- deeper Exchange Online policy configuration
- more advanced SharePoint workflows
- additional hybrid identity and access governance scenarios

---

