# GDPR Risk Register

This risk register documents key GDPR-related risks, their impact, likelihood, and recommended mitigations.  
Risk scoring uses the formula:

**Risk Score = Likelihood (1–5) × Impact (1–5)**

---

## Risk Register

| Risk ID | GDPR Article | Description | Likelihood | Impact | Risk Score | Mitigation |
|--------|--------------|-------------|------------|--------|------------|------------|
| **R-01** | Art. 32 | Insufficient encryption for personal data in transit | Medium | High | **12** | Enforce TLS 1.2+/1.3 and enable HSTS across all endpoints |
| **R-02** | Art. 30 | ROPA incomplete or outdated | High | Medium | **15** | Implement quarterly ROPA reviews and require DP involvement in new processing activities |
| **R-03** | Art. 6 | Processing activities lack documented lawful basis | Medium | High | **12** | Conduct lawful basis assessment and require validation before new processing begins |
| **R-04** | Art. 35 | DPIA not completed for high-risk processing (AI, biometrics, profiling) | High | High | **20** | Establish DPIA workflow and require approval before production deployment |
| **R-05** | Art. 28 | Vendor lacks adequate processor agreements (DPAs) | Medium | High | **12** | Standardize DPA requirements and annually review third-party security |
| **R-06** | Art. 5(1)(c) | Excessive data collection beyond purpose | Medium | Medium | **9** | Apply data minimization guidelines and conduct periodic privacy reviews |
| **R-07** | Art. 33 | No defined breach response plan or unclear 72-hour reporting workflow | High | High | **20** | Implement incident response plan and conduct annual tabletop exercises |

---

## Notes
This risk register is designed to demonstrate structured GDPR governance analysis and can be adapted for real-world use by adjusting risk scoring and mitigations to organizational needs.
