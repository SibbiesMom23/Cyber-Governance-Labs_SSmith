# Cyber Governance Labs – S. Smith

This repository contains hands-on labs focused on security governance and privacy, starting with GDPR. The goal is to show how I think through structured decision-making, risk, and compliance workflows, not just technical configuration.

These labs connect directly to the strengths highlighted in my CyberGen.ai results: pattern recognition, structured analysis, anomaly detection, and systematic problem solving.

---

## Repository Structure

- `01-GDPR-Lab-DPIA/`  
  First lab focused on a GDPR Data Protection Impact Assessment (DPIA) for a fictional organization.

- `02-ROPA-Governance-Scenario/`  
  Follow-on lab (work in progress) for Records of Processing Activities (ROPA), breach notification timelines, and cross-border data transfer risk.

- `templates/`  
  Shared governance templates, such as DPIA and ROPA skeletons or simple checklists.

---

## Lab 01 – GDPR DPIA Overview

The first lab walks through a simplified DPIA for a fictional web application that processes personal data. The focus is on:

- Identifying data categories and processing purposes
- Selecting an appropriate lawful basis
- Evaluating risks to confidentiality, integrity, and availability
- Proposing controls and documenting decisions in a repeatable way

### GDPR Governance Flow (High-Level)

```mermaid
flowchart TD
    A[Data Collected<br>(User Input / System Logs)] --> B[Identify Data Category<br>(PII, Sensitive Data, Behavioral Data)]
    B --> C[Determine Lawful Basis]
    C -->|Consent| D[Store Consent Record]
    C -->|Legitimate Interest| E[Conduct LI Balancing Test]
    C -->|Contract| F[Verify Contractual Necessity]
    D --> G[Create Processing Record (ROPA)]
    E --> G
    F --> G
    G --> H[Assess Risks<br>(Confidentiality, Integrity, Availability)]
    H --> I[Apply Controls<br>(Access Limits, Encryption, Retention Rules)]
    I --> J[Monitor & Review<br>(Audits, Incident Reports)]
