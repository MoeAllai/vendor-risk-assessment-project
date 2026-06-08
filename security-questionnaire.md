# Security Questionnaire Review

## Purpose

This document simulates a vendor security questionnaire review for PayLink HR Solutions.

The goal is to evaluate vendor security controls, identify gaps, and determine whether additional evidence or remediation is required before onboarding.

---

## Questionnaire Summary

| Area | Overall Result | Notes |
|---|---|---|
| Security Governance | Acceptable | Vendor has documented security policies and annual review process |
| Access Control | Needs Follow-Up | Access reviews are performed, but evidence quality needs validation |
| MFA | Needs Follow-Up | MFA is enforced, but exception tracking is not fully documented |
| Encryption | Acceptable | Encryption is used in transit and at rest |
| Incident Response | Needs Follow-Up | Incident process exists, but notification SLA needs contract clarification |
| Business Continuity | Needs Follow-Up | BCP/DR exists, but latest test evidence is older than 12 months |
| Vendor / Subprocessor Management | Needs Follow-Up | Subprocessors are used, but review evidence is incomplete |
| Data Retention & Deletion | Needs Follow-Up | Process exists but deletion timeline needs clarification |
| Privacy | Acceptable | Vendor has privacy controls and customer data handling procedures |
| Compliance Evidence | Needs Follow-Up | SOC 2 report provided, but exceptions require review |

---

## Security Questionnaire

| ID | Category | Question | Vendor Response | Analyst Review | Follow-Up Required? |
|---|---|---|---|---|---|
| Q-01 | Security Governance | Does the vendor maintain written information security policies? | Yes. Policies are reviewed annually. | Acceptable. Request policy summary or table of contents as evidence. | Yes |
| Q-02 | Security Governance | Does the vendor conduct employee security awareness training? | Yes. All employees complete training annually. | Acceptable. Request latest training completion summary. | Yes |
| Q-03 | Access Control | Are user access reviews performed regularly? | Yes. Access reviews are performed quarterly. | Needs validation. SOC 2 notes mention incomplete review evidence. | Yes |
| Q-04 | Access Control | Is privileged access limited and reviewed? | Yes. Admin access is limited to authorized personnel. | Needs validation. Request admin access review evidence. | Yes |
| Q-05 | Access Control | Is access removed after employee termination? | Yes. Access is removed within 24 hours. | Acceptable if supported by offboarding evidence or SOC 2 testing. | Yes |
| Q-06 | MFA | Is MFA enforced for all employees? | Yes. MFA is required for employee access. | Needs follow-up. Exceptions must be documented and approved. | Yes |
| Q-07 | MFA | Are MFA exceptions tracked and reviewed? | Exceptions are rare and handled by IT Security. | Weak response. No clear exception register process described. | Yes |
| Q-08 | Encryption | Is data encrypted in transit? | Yes. TLS is used for data transmission. | Acceptable. | No |
| Q-09 | Encryption | Is data encrypted at rest? | Yes. Data is encrypted at rest using cloud encryption services. | Acceptable. Request encryption overview. | Yes |
| Q-10 | Encryption | Are customer-managed encryption keys supported? | No. Vendor-managed keys are used. | Not automatically a blocker, but should be documented as a risk consideration. | Yes |
| Q-11 | Incident Response | Does the vendor maintain an incident response plan? | Yes. Incident response procedures are documented and tested annually. | Acceptable. Request incident response policy summary. | Yes |
| Q-12 | Incident Response | What is the customer notification timeline for security incidents? | Customers are notified as soon as reasonably possible. | Needs contract clarification. Timeline is not specific enough. | Yes |
| Q-13 | Business Continuity | Does the vendor maintain a BCP/DR plan? | Yes. Business continuity and disaster recovery plans are documented. | Acceptable in principle. Need recent test evidence. | Yes |
| Q-14 | Business Continuity | When was the last BCP/DR test completed? | Last full test was completed 14 months ago. | Needs remediation. Evidence is older than expected. | Yes |
| Q-15 | Subprocessors | Does the vendor use subcontractors or subprocessors? | Yes. Hosting and tax document processing are supported by subprocessors. | Needs review. Request full subprocessor list and review process. | Yes |
| Q-16 | Subprocessors | Are subprocessors reviewed for security risk? | Yes, subprocessors are reviewed before approval. | Incomplete. Request evidence of most recent review. | Yes |
| Q-17 | Data Retention | Is customer data deleted after contract termination? | Yes. Data is deleted after contract termination upon request. | Needs clarification. Timeline and certificate of deletion should be defined. | Yes |
| Q-18 | Data Retention | Is a certificate of deletion provided? | Available upon request. | Acceptable if included in contract or procedure. | Yes |
| Q-19 | Privacy | Does the vendor limit employee access to customer data? | Yes. Access is role-based and limited by job responsibilities. | Acceptable, pending access review evidence. | Yes |
| Q-20 | Compliance | Does the vendor provide a SOC 2 Type II report? | Yes. SOC 2 Type II report provided under NDA. | Acceptable, but exceptions must be reviewed and tracked. | Yes |

---

## Key Follow-Up Items

The following items require additional evidence or clarification:

1. Quarterly access review evidence
2. Privileged access review evidence
3. MFA exception register
4. Incident notification timeline
5. Updated BCP/DR test results
6. Full subprocessor list
7. Subprocessor security review evidence
8. Data deletion timeline
9. Certificate of deletion process
10. SOC 2 exception remediation status

---

## Analyst Notes

PayLink HR Solutions appears to have a security program in place, but several questionnaire responses require additional validation.

The most important issue is not that controls are missing. The main concern is whether the vendor can provide complete, current, and audit-ready evidence to support its responses.

The vendor should be conditionally approved only after high-priority follow-up items are addressed or contractually documented.

---

## Initial Questionnaire Decision

**Decision:** Needs follow-up before approval.

**Reason:** The vendor handles sensitive employee payroll and banking data, so incomplete or unclear responses around access reviews, MFA exceptions, incident notification, subprocessors, business continuity, and data deletion must be resolved before full onboarding.

---

## Notes

This security questionnaire review is part of a mock GRC portfolio project. It demonstrates vendor due diligence, questionnaire review, evidence validation, third-party risk assessment, and remediation planning skills.
