# Cran Ecommerce – Security Audit Report  
**Auditor:** Chinelo Ebenezar, SOC Analyst  
**Date:** July 9, 2025  

---

## Overview  
This audit evaluates the cybersecurity posture of **Cran Ecommerce**, a fictional Nigerian-based online retail company. The assesment includes an analysis of 
- Network traffic
- Endpoint protection
- Access controls
- Web application vulnerabilities
- SIEM effectiveness
- Incident response readiness
- Regulatory compliance.
  
The audit was conducted using the NIST Cybersecurity Framework (CSF) and assessed compliance with:  
- **NDPR** - Nigeria Data Protection Regulation 
- **CBN Cybersecurity Framework and Guidelines for Payment Service Providers**  
- **GDPR** - General Data Protection Regulation  
- **PCI DSS** - Payment Card Industry Data Security Standard  

**Tools Used** includes Splunk, firewall logs and endpoint monitoring systems.  

This report demonstrates my ability to perform security audits, identify risks, and recommend improvements aligned with both **technical best practices** and **regulatory requirements**.  

---

## Executive Summary  
Cran Ecommerce has basic security controls in place, including firewalls and antivirus software, but lacks key protections needed to defend against modern threats. Vulnerabilities were identified in network configuration, web application security, user access control policies, and regulatory compliance.

Recommended actions include:
- Securing customer and payment data
- Implementing multi-factor authentication
- Strengthening incident response procedures
- Ensuring compliance with NDPR, CBN, GDPR, and PCI DSS
These steps will significantly improve the platform’s security posture and reduce legal and operational risk.


---


## Scope  
The audit assessed the following areas:  
- **Network infrastructure** : firewalls, IDS/IPS  
- **Endpoint protection** : patch management, antivrius coverage
- **Web application security**: SQL injection, session handling
- **Access Control** : Privilege assignment, user account management
- **Log Management** : Retention period, alerting accuracy
- **Incident response** : Playbooks, testing frequency  
- **Compliance** : Alignment with NDPR, CBN, GDPR, and PCI DSS  

---


## Methodology  

| **Activity**               | **Tools/Approach**         | **Purpose**                                 |
|----------------------------|----------------------------|---------------------------------------------|
| **Network Analysis**       | Wireshark, Firewall Logs   | Detect insecure protocols and anomalies |
| **Endpoint Review**        | Antivirus logs, patch status   | Assess device protection levels       |
| **Access Control Review**  | Active Directory Audit     | Identify overprivileged accounts            |
| **Web App Test**           | Manual inspection          | Find SQL injection, session issues          |
| **Log Review**             | Internal SIEM              | Check for visibility and alerting gaps      |
| **Incident Review**        | Past reports               | Evaluate response maturity                  |
| **Compliance Review**      | NDPR, CBN Guidelines       | Assess regulatory alignment                 |


---


## Key Findings  

| **Category**          | **Findings**                                      | **Risk Level** |
|-----------------------|---------------------------------------------------|---------------|
| **Network Security**  | Outdated firewall rules, insecure protocols (FTP/Telnet) | Medium        |
| **Endpoint Security** | Missing patches, inconsistent antivirus coverage  | Medium        |
| **Access Control**    | Overprivileged accounts, inactive users still active | High          |
| **Web Application**   | SQL injection vulnerability, insecure session handling | **Critical**  |
| **Log Management**    | Short log retention (30 days), poor alerting      | Medium        |
| **Incident Response** | No documented playbooks or drills                 | Medium        |
| **Compliance**        | Non-compliant with NDPR, CBN, GDPR, PCI DSS       | High          |


---


## Recommendations  

| **Category**          | **Recommendations**                                                                 |
|-----------------------|------------------------------------------------------------------------------------|
| **Network Security**  | Update firewall rules, disable legacy protocols (FTP/Telnet)                       |
| **Endpoint Security** | Enforce automated patching, ensure full antivirus coverage                         |
| **Access Control**    | Revoke unnecessary admin rights, remove inactive accounts                          |
| **Web Application**   | Fix SQL issue, enforce HTTPS-only cookies                                         |
| **Log Management**    | Extend retention to **90+ days**, improve SIEM rule tuning                         |
| **Incident Response** | Create response playbooks, conduct **quarterly drills**                            |
| **Compliance**        | Implement **encryption, RBAC, and formal policies** for NDPR, CBN, GDPR, PCI DSS  |


---


## Risk Ratings Summary  

| **Category**          | **Risk Level** | **Justification**                                                                 |
|-----------------------|---------------|----------------------------------------------------------------------------------|
| **Network Security**  | ⚠️ Medium     | Misconfigured firewalls increase exposure risk                                   |
| **Endpoint Security** | ⚠️ Medium     | Unpatched systems can be exploited                                              |
| **Access Control**    | ⚠️ High       | Overprivileged accounts pose insider threat risk                                |
| **Web Application**   | ⚠️ **Critical** | SQL injection could lead to **full database compromise**                        |
| **Log Management**    | ⚠️ Medium     | Limited forensic capability due to short retention                              |
| **Incident Response** | ⚠️ Medium     | Delayed response increases breach impact                                        |
| **Compliance**        | ⚠️ High       | Legal fines possible under **NDPR, CBN, GDPR, and PCI DSS**                     |


---


## Compliance Status  

| **Regulation**       | **Status**          | **Notes**                                                                       |
|-----------------------|---------------------|---------------------------------------------------------------------------------|
| **NDPR**             | ❌ Partially Compliant | Some privacy policies exist, but no formal data protection program              |
| **CBN Guidelines**   | ❌ Non-Compliant     | Required by Nigerian regulators; non-compliance may result in sanctions         |
| **GDPR**             | ❌ Non-Compliant     | Processes EU user data without proper consent or encryption                     |
| **PCI DSS**          | ❌ Non-Compliant     | Handles card data without encryption or access restrictions                     |


---


## Conclusion  
Cran Ecommerce needs **urgent improvements** to its security and compliance programs. Immediate focus should be placed on Securing the e-commerce platform, Protecting personal and payment data  and aligning with **local and global regulations**  

This audit highlights my ability to assess real-world security environments, identify critical risks, and provide **practical solutions** — combining both **SOC operations** and **GRC insights**.  
