# Cyber Governance Labs – S. Smith

This repository contains hands-on labs focused on security governance, privacy, and structured decision-making. These labs simulate real-world GRC and privacy engineering workflows, demonstrating how I analyze risk, document compliance tasks, and apply governance principles across technical and non-technical scenarios.

These labs also reflect key strengths highlighted in my CyberGen.ai assessment:
**pattern recognition, structured analysis, anomaly detection, and systematic problem solving.**

---

## 📁 Repository Structure

### **01-GDPR-Lab-DPIA/**
A foundational lab walking through a GDPR Data Protection Impact Assessment (DPIA) for a fictional organization. Includes:
- Data inventory and mapping  
- Lawful basis selection  
- Risk evaluation (confidentiality, integrity, availability)  
- Control selection and justification  

---

### **02-ROPA-Governance-Scenario/**
A follow-on scenario (work in progress) covering:
- Records of Processing Activities (ROPA)  
- Breach notification timelines  
- Cross-border data transfer risks  
- Accountability documentation practices  

---

### **templates/**
Shared governance templates such as:
- DPIA skeleton  
- ROPA skeleton  
- Checklists  
- Notes pages  

---

### **03-GDPR-Risk-Register.md**
A complete GDPR-specific Risk Register using likelihood × impact scoring. Includes:
- GDPR Article mapping  
- Risk descriptions  
- Impact + likelihood scoring  
- Recommended mitigation strategies  

**➡️ [Open the GDPR Risk Register](./03-GDPR-Risk-Register.md)**

---

### **04-GDPR-Compliance-Checklist.md**
A professional-grade GDPR Compliance Checklist covering:
- Data governance  
- Privacy by Design / Default  
- DSAR readiness  
- Incident response  
- Vendor and third-party controls  

**➡️ [Open the GDPR Compliance Checklist](./04-GDPR-Compliance-Checklist.md)**

---

## 📘 Lab 01 – GDPR DPIA Overview

This lab introduces the fundamentals of a GDPR Data Protection Impact Assessment using a fictional web application that processes personal data.

The DPIA workflow includes:
- Identifying personal data categories  
- Mapping processing purposes  
- Selecting lawful bases  
- Evaluating risks to individuals and the organization  
- Proposing proportional technical and organizational controls  
- Documenting the rationale and final assessment  

---

## 🔄 GDPR Governance Flow (High-Level)

```mermaid
flowchart TD
    A["Data Collected (User Input / System Logs)"] --> B["Identify Personal Data Categories"]
    B --> C["Determine Lawful Basis for Processing"]
    C --> D["Data Minimization Review"]
    D --> E["Assign Data Controller and Processor Roles"]
    E --> F["Conduct DPIA"]
    F --> G["Implement Technical and Organizational Controls"]
    G --> H["Document Compliance in GDPR Registry"]
    H --> I["Establish Retention and Deletion Schedule"]
    I --> J["Enable Data Subject Rights (Access, Erasure, Portability)"]
    J --> K["Ongoing Monitoring and Compliance Review"]

