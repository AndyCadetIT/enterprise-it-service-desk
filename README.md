# Enterprise IT Service Desk Operations

**Project ID:** IT-P001  
**Project Type:** Independent IT Support Lab  
**Status:** Completed  
**Version:** 1.1

## Project Overview

I built a simulated enterprise IT service desk environment to practice troubleshooting common workstation, network, and application issues.

The project focuses on identifying technical problems, performing diagnostic tests, determining root causes, documenting resolutions, and verifying results.

## Lab Environment

| Component | Specifications |
|---|---|
| Physical Workstation | MacBook Air M4, 16 GB RAM |
| Host Operating System | macOS Sequoia 15.7.9 |
| Virtualization | UTM / QEMU |
| Virtual Workstation | Windows 11 Pro ARM64 |
| Virtual Resources | 6 GB RAM, 64 GB Storage |
| Email Application | Microsoft Outlook |
| ITSM Platform | ServiceNow Personal Developer Instance |

## Incident Summary

| Incident | Reported Issue | Outcome |
|---|---|---|
| INC-001 | Employee Account Access | Successful authentication verified; no password reset required |
| INC-002 | DNS Resolution Failure | Controlled timeout reproduced; normal DNS resolution verified |
| INC-003 | Missing Outlook Emails | Routing rule identified and disabled; email delivery restored |

## Technical Skills Demonstrated

- Windows 11 installation and configuration
- Virtual machine deployment
- macOS account and permission verification
- DNS troubleshooting using nslookup
- Outlook inbox rule troubleshooting
- Root cause analysis
- Incident classification and prioritization
- Workstation asset inventory
- Knowledge base documentation
- Resolution testing and verification

## ServiceNow ITSM Implementation

To extend the original technical investigations, I recreated all three support incidents within a ServiceNow Personal Developer Instance.

### Incident Records

| Portfolio Reference | ServiceNow Incident | Issue | Status |
|---|---|---|---|
| INC-001 | INC0010004 | Employee Account Access | Closed |
| INC-002 | INC0010005 | DNS Troubleshooting | Closed |
| INC-003 | INC0010006 | Outlook Email Routing | Closed |

### ITSM Skills Demonstrated

- Incident creation, classification, and prioritization
- Assignment group and technician assignment
- Internal work notes and customer-facing communication
- Functional escalation from Service Desk to Network support
- Incident resolution and closure
- Knowledge article creation and publication
- User impersonation and simulated approval workflows

### Published Knowledge Articles

| Reference | ServiceNow Article | Topic |
|---|---|---|
| KB-001 | KB0010001 | Employee Login and Password Troubleshooting |
| KB-002 | KB0010002 | DNS Resolution Troubleshooting |
| KB-003 | KB0010003 | Outlook Missing Email Troubleshooting |

All activities were performed within a controlled training environment using simulated incidents and demonstration accounts.

## Project Outcomes

- 3 completed technical investigations
- 3 resolved and closed ServiceNow incidents
- 3 published knowledge articles
- 19 supporting screenshot evidence entries
- 1 simulated functional escalation
- 3 technical project deliverables


## Project Deliverables

| Document | Description |
|---|---|
| [Technical Project Report](./Enterprise%20IT%20Service%20Desk%20-%20Technical%20Project%20Report.pdf) | Detailed troubleshooting investigations, screenshot evidence, asset inventory, and technical findings. |
| [Incident Records](./IT%20Service%20Desk%20-%20Incident%20Records.pdf) | Three simulated service desk tickets documenting diagnosis, resolution, and closure verification. |
| [Knowledge Base](./IT%20Service%20Desk%20-%20Knowledge%20Base.pdf) | Three reusable troubleshooting articles for account access, DNS, and Outlook support. |

## Key Takeaway

This project helped me understand the importance of establishing a working baseline, investigating reported symptoms, identifying the cause of an issue, and verifying results before closing a support ticket.

## Project Disclaimer

All incidents were conducted as controlled simulations in an authorized personal lab environment. This project represents independent hands-on training, not professional employment or production enterprise experience.
