# Lab 02 – ROPA and Governance Scenario (Work in Progress)

This lab will build on the DPIA work from Lab 01 and focus on operationalizing GDPR governance through:

- Records of Processing Activities (ROPA)
- Breach notification timelines and decision-making
- Cross-border data transfer risk assessment

---

## Planned Focus

### 1. ROPA Entries  
Define a small set of core processing activities for a fictional organization and create structured ROPA entries for each.

### 2. Breach Notification Scenario  
Walk through a simulated security incident to determine:

- Whether it is notifiable under GDPR  
- Who must be notified  
- The timing and key information elements  
- What should be documented in the incident log  

### 3. Cross-Border Data Transfers  
Identify any transfers outside the EU/EEA, evaluate the safeguards, and document potential risks or required mitigations.

---

## Purpose

The goal of this lab is to demonstrate how different governance artifacts connect:

- DPIA findings  
- Day-to-day processing records  
- Incident response decisions  
- Regulatory documentation  

This README is a placeholder and will be expanded as the lab is developed.

---

# Example ROPA Entry (Completed)

## Processing Activity Name
User Account Management

---

## Purpose of Processing
To allow users to create, access, and manage their accounts within the NovaPortal system, including authentication, subscription information, and basic communication functionality.

---

## Categories of Data Subjects
- Customers  
- Prospective customers who create trial accounts  

---

## Categories of Personal Data
- Identification data: Name, email address  
- Authentication data: Password hash, MFA metadata  
- Account metadata: Signup date, subscription status  

---

## Data Recipients
### Internal:
- Engineering (system maintenance)
- Security (monitoring and access control)
- Customer Support (account troubleshooting)

### External:
- Cloud hosting provider (AWS/Azure)
- Email service provider (transactional emails)

---

## Transfers to Third Countries
- Yes — data may be stored or processed in the United States.
- Safeguards:
  - Standard Contractual Clauses (SCCs)
  - Encryption in transit and at rest

---

## Retention Periods
- Account data retained for the duration of the user’s active subscription  
- Logs retained for 30 days  
- Backup snapshots retained for 30 days  

---

## Technical and Organizational Controls
- MFA required for login  
- Role-based access control for staff  
- Encrypted storage (AES-256)  
- TLS 1.2+ for data in transit  
- Monthly access reviews  
- Logging and monitoring for authentication events  

---

## DPIA Required?
- **Yes** — this processing activity is covered by the DPIA completed in Lab 01.

---

## Last Review Date
Reviewed by: S. Smith  
Date: Nov 2025

