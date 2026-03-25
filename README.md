# IT Admin Homelab Project – Dell PowerEdge R430

## Overview
To strengthen my IT Administration skills in a challenging job market, I built a hands-on enterprise-style homelab using a Dell PowerEdge R430 server.

This lab helped me refresh and practice core infrastructure concepts such as virtualization, Active Directory, Group Policy, file services, redundancy, patch management, and deployment services.

## Lab Environment
- Hardware: Dell PowerEdge R430
- Virtualization: Proxmox
- OS: Windows Server
- Main Services:
  - Active Directory Domain Services
  - Group Policy Management
  - FSRM
  - WSUS
  - WDS
  - Data Deduplication

## What I Implemented

### 1. Proxmox Virtualization
- Configured Proxmox as the hypervisor
- Created and managed Windows Server virtual machines

### 2. Active Directory Domain Controller
- Set up a primary Domain Controller
- Created Organizational Units for:
  - IT
  - HR
  - Sales
  - Operations

### 3. Group Policy Objects (GPOs)
Configured department-based GPOs, including:
- Password Policy
- No Control Panel Access
- Wallpaper Policy
- Mapped Drives

### 4. File Server Resource Manager (FSRM)
- Applied folder quotas
- Set up notifications
- Configured file screening
- Blocked executable file types such as `.exe`
- Restricted unnecessary image/video storage in selected folders

### 5. Permissions Management
- Configured read, write, and modify permissions on shared folders

### 6. Redundancy / High Availability
- Added a secondary Domain Controller
- Built redundancy so the secondary DC can support authentication if the primary DC goes down

### 7. Data Deduplication
- Enabled and tested Data Deduplication to improve storage efficiency

### 8. WSUS
- Configured WSUS for centralized Windows update management

### 9. WDS
- Configured WDS on the main Domain Controller
- Tested deployment on 5 different machines over network PXE Boot.

## Skills Demonstrated
- Windows Server Administration
- Active Directory
- Group Policy
- Virtualization
- File Services and Permissions
- Redundancy and Infrastructure Planning
- Patch Management
- OS Deployment
- IT Troubleshooting

## Key Learnings
This project helped me strengthen my practical understanding of how enterprise IT environments are structured and maintained, especially around access control, policy enforcement, storage management, and continuity planning.
