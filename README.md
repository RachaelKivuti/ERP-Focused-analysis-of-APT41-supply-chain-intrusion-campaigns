# ERP-Focused Analysis of APT41 Supply-Chain Intrusion Campaigns  

---

## Project Overview

Enterprise Resource Planning (ERP) platforms such as SAP, Oracle ERP and Microsoft Dynamics represent mission-critical digital infrastructure within modern organizations. Their central role in financial processing, supply-chain operations, authentication and third-party integration makes them highly attractive targets for advanced persistent threat (APT) actors.

This capstone project presents an ERP-focused cyber threat intelligence analysis of **APT41**, a Chinese state-aligned threat group known for software supply-chain compromise, exploitation of public-facing enterprise applications and abuse of trusted credentials and certificates.

While APT41 has been extensively documented, existing intelligence remains largely infrastructure-centric. This project addresses that gap by translating APT41’s known tactics, techniques and procedures (TTPs) into **ERP-specific, ATT&CK-aligned defensive intelligence**, with particular emphasis on SAP environments.

---

## Project Objectives

### Primary Objective
To produce an **ATT&CK-mapped intelligence dossier** analyzing APT41’s ERP-relevant supply-chain intrusion campaigns.

### Secondary Objectives
- To analyze APT41’s intrusion lifecycle and its impact on ERP ecosystems  
- To identify ERP-specific defensive monitoring priorities  
- To translate APT41 TTPs into actionable mitigation guidance for ERP environments  

---

## Threat Actor Focus: APT41

APT41 (also known as *Winnti*, *Double Dragon*, *BARIUM* or *Brass Typhoon*) is a **Chinese state-aligned advanced persistent threat** known for:

- Software **supply-chain compromise**
- Exploitation of **public-facing enterprise applications**
- Abuse of **valid credentials and trusted certificates**
- Long-term, stealthy persistence within enterprise environments

This project contextualizes APT41’s tradecraft within **ERP architectures**, highlighting how trusted integrations, service accounts, middleware and application servers can be abused without triggering traditional endpoint defenses.

---

## Analytical Framework

The project is structured around the **MITRE ATT&CK Enterprise Framework**, with a strong focus on ERP-relevant techniques, including:

| ATT&CK Technique | Description |
|-----------------|------------|
| **T1195** | Supply Chain Compromise |
| **T1190** | Exploit Public-Facing Application |
| **T1078** | Valid Accounts |
| **T1021** | Remote Services |
| **T1550** | Use of Stolen Certificates |
| **T1560** | Archive Collected Data |

Each technique is mapped to:
- ERP components affected  
- Defensive gaps  
- Monitoring considerations  
- Mitigation strategies  

## Key Deliverables

- Comprehensive ERP-focused intelligence dossier  
- Strategic technical analysis of APT41 supply-chain operations  
- ATT&CK-aligned technique mapping tables  
- ERP monitoring and mitigation priority brief  
- Conceptual ERP deception and telemetry correlation prototype  

---

## References

Key sources include:
- MITRE ATT&CK (APT41)
- Mandiant APT41 Reports
- CrowdStrike Global Threat Reports
- CISA Supply-Chain Security Advisories
- SAP Security Notes
- ESET and Kaspersky Threat Research

Full references are provided in the final report.

**Author:** Rachael Kivuti   
