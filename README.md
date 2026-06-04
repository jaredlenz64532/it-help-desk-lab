![Alternative text](../screenshots/Windowsserver2022downloaded.png)

# Active Directory Help Desk Homelab

## Overview

Credit to KevTech on YouTube for his help desk support lab playlists that made this project possible.

This project demonstrates the creation and administration of a Windows-based enterprise support environment using Windows Server 2022, Active Directory Domain Services, Group Policy, patch management tools, software deployment platforms, ticketing systems, and file/print services.

The objective of this lab was to simulate common responsibilities performed by Help Desk Technicians, Desktop Support Specialists, and Junior Systems Administrators in a production environment.

## Technologies Used

* Windows Server 2022
* Windows 11 Pro
* Active Directory Domain Services (AD DS)
* Group Policy Management
* DNS
* Remote Desktop Services
* VirtualBox
* Action1
* PDQ Deploy
* PDQ Inventory
* Spiceworks Help Desk
* File and Print Services

## Lab Environment

### Domain Controller

* Hostname: AZ-DC-01
* Operating System: Windows Server 2022
* Roles:

  * Active Directory Domain Services
  * DNS
  * File Services
  * Print Services

### Client Workstation

* Operating System: Windows 11 Pro
* Domain Joined: homelab.com

### Domain

* Forest: homelab.com

## Skills Demonstrated

### Active Directory Administration

* Installed and configured Active Directory
* Promoted server to Domain Controller
* Created users, groups, and Organizational Units
* Managed account permissions and restrictions
* Delegated administrative tasks

### Group Policy Administration

* Configured password policies
* Configured account lockout policies
* Removed Task Manager access
* Restricted shutdown options
* Applied and validated GPOs

### Endpoint Management

* Deployed Action1 agents
* Installed operating system updates
* Generated compliance and hardware reports
* Deployed software using PDQ Deploy
* Audited systems using PDQ Inventory

### File and Print Services

* Created shared folders
* Configured NTFS permissions
* Implemented security group-based access control
* Mapped network drives
* Deployed shared printers

### Help Desk Operations

* Simulated account lockout troubleshooting
* Tested user login restrictions
* Managed support tickets in Spiceworks
* Conducted remote support sessions

## Project Walkthrough

| Part | Topic                                |
| ---- | ------------------------------------ |
| 1    | Windows Server Installation          |
| 2    | Active Directory Deployment          |
| 3    | User Management                      |
| 4    | Domain-Joined Workstation            |
| 5    | Group Policy and Account Security    |
| 6    | Action1 Patch Management             |
| 7    | File Shares and Security Groups      |
| 8    | User Restriction Policies            |
| 9    | Organizational Units and Home Drives |
| 10   | Action1 Agent Deployment             |
| 11   | PDQ Deploy                           |
| 12   | PDQ Inventory                        |
| 13   | Print Services                       |
| 14   | Spiceworks Help Desk                 |
| 15   | Delegation of Control                |

## Screenshots

Screenshots for each phase of the lab are available in the screenshots directory.

## Key Outcomes

* Built and administered an Active Directory environment from scratch
* Managed users, groups, permissions, and Group Policy
* Implemented patch management and software deployment
* Configured file shares and print services
* Practiced common Help Desk and System Administration workflows
* Developed troubleshooting skills in a Windows enterprise environment
