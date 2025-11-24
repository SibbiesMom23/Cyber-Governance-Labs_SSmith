# Lab 01 – GDPR Data Protection Impact Assessment (DPIA)

This lab walks through a simplified GDPR Data Protection Impact Assessment for a fictional web application that processes user registration data, basic analytics, and support tickets.

## Scenario

A mid-sized SaaS company is launching a new customer portal that will:

- Collect names, emails, and login credentials
- Store optional profile information
- Log user activity for security and basic analytics
- Allow customers to submit support tickets with free-text descriptions

The company wants to ensure that the new portal is aligned with GDPR requirements and that privacy risks are understood and documented.

---

## Objectives

- Identify what personal data is collected and why
- Determine the appropriate lawful basis for each processing activity
- Evaluate risks to data subjects
- Propose and document reasonable controls
- Capture the analysis in a structured DPIA format

---

## Lab Structure

This lab is organized into the following sections:

1. **Data Inventory** – List systems, data types, and processing purposes.  
2. **Lawful Basis Assessment** – Map each processing purpose to a lawful basis.  
3. **Risk Identification** – Identify threats and potential impacts to individuals.  
4. **Control Selection** – Propose technical and organizational controls.  
5. **DPIA Summary** – Document the overall risk posture and recommendations.

---

## Governance Flow Diagram

```mermaid
flowchart TD
    A[Collect User Data] --> B[Classify Data Types]
    B --> C[Select Lawful Basis]
    C --> D[Document Decision in DPIA]
    D --> E[Identify Risks]
    E --> F[Choose Controls]
    F --> G[Monitor, Review, and Update]

