# Phase 6 – Help Desk Operations & Remote Support

## Overview

The purpose of this phase was to simulate real-world Help Desk operations by working with a ticketing system, and performing remote support.

While previous phases focused on infrastructure and administration, this phase focused on the customer support side of IT operations. These activities reflect the daily responsibilities of Help Desk Technicians, Desktop Support Specialists, and IT Support Analysts who assist end users with account issues, access requests, software problems, and remote troubleshooting.

---

## Objectives

* Create and manage support tickets
* Perform remote support sessions
* Practice escalation and resolution workflows
* Gain experience with ticket lifecycle management

---

## Environment

### Domain Controller

* Hostname: AZ-DC-01
* Operating System: Windows Server 2022

### Client Workstation

* Windows 11 Pro
* Domain Joined

### Domain

* homelab.com

### Tools Used

* Spiceworks Help Desk
* Active Directory Users and Computers
* Group Policy Management
* Remote Desktop
* Command Prompt
* Windows Settings

---

# Part A – Spiceworks Help Desk Setup

## Creating a Help Desk Environment

An account was created within Spiceworks and a Help Desk environment was configured to simulate an IT support department.

The platform provides functionality for:

* Ticket creation
* Ticket assignment
* Internal notes
* User communication
* Remote support
* Resolution tracking

### Screenshot

*Insert screenshot showing Spiceworks dashboard*

---

## Exploring the Ticketing Interface

The ticket management dashboard was reviewed to become familiar with the workflow and available features.

Key areas reviewed included:

* Open tickets
* Closed tickets
* Ticket details
* Notes and communication history
* User management

### Screenshot

*Insert screenshot showing ticket queue*

---

# Part B – Ticket Lifecycle Management

## Creating a Test Ticket

A test support ticket was created to simulate an end-user support request.

Example issue:

```text id="k55ld9"
User unable to access company resources.
```

Information entered included:

* Ticket title
* Description
* Priority
* Request details

### Screenshot

*Insert screenshot showing ticket creation*

---

## Documenting Troubleshooting Steps

Internal notes were added to the ticket to document investigation activities.

Examples included:

* User account verification
* Access testing
* Policy review
* Resolution steps

Proper documentation helps ensure continuity of support and creates a record for future reference.

### Screenshot

*Insert screenshot showing internal notes*

---

## Closing the Ticket

After resolving the issue, the ticket status was updated and the ticket was closed.

The resolution was documented within the ticket record.

### Screenshot

*Insert screenshot showing closed ticket*

---

# Part C – Remote Support

## Initiating a Remote Session

Spiceworks remote support functionality was used to establish a remote connection to the Windows 11 workstation.

This simulated a common Help Desk scenario where a technician assists a remote employee.

### Screenshot

*Insert screenshot showing remote support session setup*

---

## Remote Desktop Control

Once connected, full remote access to the workstation was available through the web browser.

Administrative tasks performed included:

* Navigating Windows settings
* Reviewing user settings
* Verifying access permissions
* Performing troubleshooting actions

### Screenshot

*Insert screenshot showing active remote session*

---

## User Communication

The built-in chat feature was used to simulate communication between technician and user.

This provided experience with documenting support interactions while actively troubleshooting issues.

### Screenshot

*Insert screenshot showing chat panel*

---

# Part D – Common Help Desk Commands

Several command-line tools were used throughout the lab to verify user accounts and system configuration.

## Verify User Information

```cmd id="v3wr9x"
net user mike /domain
```

---

## View Applied Policies

```cmd id="1km23l"
gpresult /r
```

---

## Verify Network Connectivity

```cmd id="nkmq9z"
ping homelab.com
```

---

## View Drive Mappings

```cmd id="qlqvlf"
net use
```

These commands are commonly used by support technicians when diagnosing user and system issues.

---

# Skills Demonstrated

* Help Desk Operations
* Ticket Lifecycle Management
* Technical Documentation
* Remote User Support
* User Account Troubleshooting
* Active Directory Administration
* Authentication Troubleshooting
* Account Recovery
* File Share Troubleshooting
* Printer Troubleshooting
* Remote Access Support
* Customer Communication
* Incident Resolution
* IT Service Management (ITSM)

---

# Outcome

A functional Help Desk workflow was implemented using Spiceworks to simulate real-world support operations. Support tickets were created, documented, and resolved while remote support sessions were used to troubleshoot and assist users. Common authentication, access, and resource-related issues were investigated and resolved using Active Directory, Group Policy, and Windows administrative tools. This phase demonstrated the operational and customer-facing aspects of IT support that complement the infrastructure and administration skills developed throughout the lab.
