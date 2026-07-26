# User Groups

## Purpose

This document identifies the primary user groups within the National Government Technology Authority (NGTA). Understanding user roles and responsibilities helps ensure that systems, applications, and information are accessed only by authorized individuals, supporting secure and efficient business operations.

---

## User Groups

| User Group | Responsibilities | Systems Used | Access Level |
|------------|------------------|--------------|--------------|
| Executive Leadership | Define organizational strategy and approve major initiatives. | Executive Dashboards, Reports | High |
| IT Administrators | Manage servers, networks, cloud infrastructure, and enterprise systems. | Active Directory, Servers, Cloud Platform, Network Devices | Privileged |
| SOC Analysts | Monitor security events, investigate alerts, and respond to cyber threats. | SIEM, EDR, Threat Intelligence Platform | Privileged |
| Incident Response Team | Handle cybersecurity incidents and coordinate containment and recovery activities. | SIEM, Incident Management System, Forensics Tools | Privileged |
| Digital Forensics Team | Collect, preserve, and analyze digital evidence during investigations. | Forensics Workstations, Evidence Repository | Privileged |
| Help Desk Staff | Provide technical support and resolve user issues. | Ticketing System, Remote Support Tools | Standard |
| Human Resources | Manage employee records and HR operations. | HR Management System | Standard |
| Finance Department | Manage budgets, procurement, and financial reporting. | ERP System, Finance Applications | Standard |
| Government Employees | Access business applications and perform daily operational tasks. | Email, Government Portal, Collaboration Tools | Standard |
| External Vendors | Support approved technologies and maintenance activities. | Approved Vendor Systems | Limited |
| Internal Auditors | Review compliance, governance, and internal controls. | Audit Reports, Compliance Systems | Read Only |

---

## Business Need

Different groups of users require different levels of access based on their responsibilities. Clearly defining user groups helps NGTA implement secure access controls while ensuring employees have the resources needed to perform their duties effectively.

---

## Security Benefit

Identifying user groups supports the implementation of Role-Based Access Control (RBAC), least privilege, multi-factor authentication, user provisioning, and access reviews. It also improves accountability and reduces the risk of unauthorized access.

---

## Assumptions

The following assumptions were made while defining user groups:

- Access is granted based on business responsibilities.
- Privileged accounts are limited to authorized personnel.
- External vendors receive only temporary and approved access.
- All users must comply with NGTA security policies.

---

## Summary

The user groups defined in this document establish the foundation for identity and access management within NGTA. These groups will guide future IAM architecture, access control policies, and cybersecurity design throughout the Enterprise Security Transformation Program.
