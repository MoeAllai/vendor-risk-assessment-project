# Vendor Risk Register

## Purpose

This vendor risk register documents risks identified during the third-party risk assessment of PayLink HR Solutions.

The goal is to convert vendor review observations into clear business risks, assign risk ratings, and recommend remediation actions before vendor approval.

---

## Risk Rating Method

Risks are rated using:

- **Likelihood:** Low, Medium, High
- **Impact:** Low, Medium, High
- **Overall Risk:** Low, Medium, High

---

## Vendor Risk Register Table

| Risk ID | Risk Title | Description | Related Area | Likelihood | Impact | Overall Risk | Owner | Recommended Remediation | Status |
|---|---|---|---|---|---|---|---|---|---|
| VR-01 | Incomplete Access Review Evidence | Vendor SOC 2 notes showed one access review sample missing reviewer sign-off. | Access Control | Medium | High | High | Vendor Security | Request updated quarterly access review evidence with reviewer sign-off and remediation notes. | Open |
| VR-02 | Privileged Access Approval Gap | One privileged access review sample did not clearly show management approval. | Privileged Access | Medium | High | High | Vendor Security | Request latest privileged access review evidence showing approver, date, admin users, and exceptions. | Open |
| VR-03 | MFA Exception Tracking Weakness | Vendor allows MFA exceptions for service accounts but did not provide a complete exception register. | MFA / Authentication | Medium | High | High | Vendor Security | Require MFA exception register with owner, approval, justification, compensating control, and expiration date. | Open |
| VR-04 | Vague Incident Notification Timeline | Vendor states customers are notified “as soon as reasonably possible,” but no specific SLA is defined. | Incident Response | Medium | High | High | Legal + Security | Add a specific incident notification timeline to the contract, such as notification within 24–72 hours of confirmed impact. | Open |
| VR-05 | Outdated BCP/DR Test Evidence | Vendor’s latest full business continuity test was completed 14 months ago. | Business Continuity | Medium | Medium | Medium | Vendor Operations | Request updated BCP/DR test results or documented testing schedule. | Open |
| VR-06 | Incomplete Subprocessor Review Evidence | Vendor uses subprocessors but did not provide complete evidence of recent security reviews. | Subprocessor Risk | Medium | High | High | Vendor Management | Request full subprocessor list and evidence of security review for critical subprocessors. | Open |
| VR-07 | Data Deletion Timeline Unclear | Vendor states data is deleted after contract termination upon request, but no clear timeline is provided. | Data Retention | Medium | High | High | Legal + Privacy | Define deletion timeline and certificate of deletion requirement in the contract. | Open |
| VR-08 | Vendor-Managed Encryption Keys Only | Vendor encrypts data at rest but does not support customer-managed encryption keys. | Encryption | Low | Medium | Medium | Security | Document as accepted design limitation or request compensating controls. | Open |
| VR-09 | Cyber Insurance Evidence Not Provided | Cyber insurance certificate was preferred but not provided during initial review. | Contract / Risk Transfer | Low | Medium | Medium | Legal / Procurement | Request cyber insurance certificate before final approval if required by company policy. | Open |
| VR-10 | Bridge Letter May Be Needed | SOC 2 report period ended December 31, 2025 and may not cover the full onboarding period. | Compliance Evidence | Medium | Medium | Medium | Vendor Security | Request bridge letter if onboarding occurs after the SOC 2 report coverage period. | Open |

---

## Top Vendor Risks

The highest priority risks are:

1. Vague incident notification timeline
2. Data deletion timeline unclear
3. Incomplete subprocessor review evidence
4. MFA exception tracking weakness
5. Incomplete access review evidence
6. Privileged access approval gap

---

## Risk Treatment Summary

| Treatment Option | Meaning | Example from This Project |
|---|---|---|
| Mitigate | Reduce the risk through corrective action | Require updated access review evidence |
| Transfer | Shift or share the risk contractually | Add breach notification SLA and cyber insurance requirement |
| Accept | Management formally accepts the risk | Accept vendor-managed encryption keys with compensating controls |
| Avoid | Do not use the vendor | Reject vendor if high-risk items remain unresolved |

---

## Conditional Approval Criteria

PayLink HR Solutions may be approved only if the following conditions are met:

- Vendor provides updated access review and privileged access evidence
- MFA exception register is provided and reviewed
- Incident notification SLA is added to the contract
- Full subprocessor list and review evidence are provided
- Data deletion timeline and certificate of deletion process are contractually documented
- Updated BCP/DR evidence or test schedule is provided
- Bridge letter is provided if required

---

## Analyst Summary

PayLink HR Solutions is a high inherent risk vendor because it will process sensitive employee payroll, tax, banking, and personal information.

The vendor appears to have a mature security program, but the assessment identified several gaps that require follow-up before full approval.

The most important risks relate to incident notification, data deletion, subprocessor oversight, access review evidence, privileged access evidence, and MFA exception tracking.

The recommended decision is **conditional approval pending remediation and contract updates**.

---

## Notes

This vendor risk register is part of a mock GRC portfolio project. It demonstrates third-party risk identification, risk rating, vendor due diligence, risk treatment, and conditional approval decision-making.
