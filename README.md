# Azure VM Monitoring & Log Collection Lab

## Overview

This lab demonstrates how to deploy and monitor a Windows Server Virtual Machine in Microsoft Azure using Azure Monitor and Log Analytics Workspace.

The objective was to implement secure access controls and centralised logging aligned with operational security best practices.

---

## Technologies Used

- Microsoft Azure
- Windows Server VM
- Network Security Group (NSG)
- Azure Monitor
- Log Analytics Workspace
- Data Collection Rules (DCR)

---

## Lab Steps Completed

### 1. Created Windows Server VM
- Deployed VM with no public IP initially
- Reduced unnecessary external exposure

### 2. Enabled Controlled Administrative Access
- Added Public IP when required
- Configured NSG inbound rule for RDP access from trusted source IP only

### 3. Connected to Server
- Successfully established RDP session

### 4. Monitoring Configuration
- Used Azure Monitor to review CPU performance metrics
- Created alert visibility capability

### 5. Centralised Logging
- Created Log Analytics Workspace
- Configured Data Collection Rule
- Sent VM logs to workspace

### 6. Validation
- Confirmed logs visible in Azure Monitor / Log Analytics

---

## Security Value

- Improved visibility
- Stronger detection capability
- Better audit trail
- Supports incident response
- Cloud security operations readiness

---

## Skills Demonstrated

Azure Administration | Cloud Security | Monitoring | Logging | Threat Visibility | Security Operations
