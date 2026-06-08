# SOC 2 Review Notes

## Purpose

This document simulates a review of the vendor’s SOC 2 Type II report for PayLink HR Solutions.

The goal is to identify relevant control coverage, exceptions, complementary user entity controls, and follow-up items before vendor approval.

---

## SOC 2 Report Summary

| Field | Details |
|---|---|
| Vendor | PayLink HR Solutions |
| Report Type | SOC 2 Type II |
| Trust Services Category | Security |
| Report Period | January 1, 2025 – December 31, 2025 |
| Report Status | Provided under NDA |
| Auditor Opinion | Unqualified opinion |
| Overall Result | Generally acceptable with exceptions requiring follow-up |
| Review Decision | Conditional approval pending clarification and remediation evidence |

---

## Scope Reviewed

The SOC 2 report was reviewed for controls related to:

- Logical access
- User provisioning and deprovisioning
- Privileged access
- MFA
- Change management
- Incident response
- Encryption
- Vendor/subprocessor management
- Business continuity and disaster recovery
- Monitoring and logging

---

## Key SOC 2 Observations

| Area | Observation | Analyst Assessment |
|---|---|---|
| Access Reviews | Quarterly access reviews are described, but one sample lacked documented reviewer sign-off. | Follow-up required |
| Terminated User Access | Offboarding control tested successfully for sampled users. | Acceptable |
| Privileged Access | Admin access review is included, but evidence quality was limited for one system. | Follow-up required |
| MFA | MFA is enforced for employee access. Exceptions are allowed for service accounts. | Follow-up required |
| Encryption | Data is encrypted in transit and at rest using vendor-managed keys. | Acceptable |
| Incident Response | Incident response process exists, but customer notification timeline is not specific. | Contract clarification required |
| BCP/DR | Business continuity plan exists, but latest full test was older than 12 months. | Follow-up required |
| Subprocessors | Vendor uses subprocessors for hosting and tax document processing. | Follow-up required |
| Change Management | Changes are reviewed and approved before production release. | Acceptable |
| Monitoring | Security logs are monitored for suspicious activity. | Acceptable |

---

## SOC 2 Exceptions Identified

| Exception ID | Area | Exception Summary | Risk Impact | Follow-Up Needed |
|---|---|---|---|---|
| SOC2-E01 | Access Review Evidence | One quarterly access review sample did not include reviewer sign-off. | May indicate incomplete access review evidence or weak evidence retention. | Request remediation status and updated access review evidence |
| SOC2-E02 | Privileged Access Evidence | One admin access review sample did not clearly show management approval. | May create risk of excessive privileged access. | Request latest privileged access review and approval evidence |
| SOC2-E03 | MFA Exceptions | Service account MFA exceptions were not clearly documented in the SOC 2 evidence. | May weaken authentication control if exceptions are not approved and monitored. | Request MFA exception register |
| SOC2-E04 | BCP/DR Testing | Full business continuity test evidence was older than 12 months. | May reduce confidence in operational resilience. | Request updated BCP/DR test results or management explanation |

---

## Complementary User Entity Controls

The SOC 2 report includes responsibilities that CloudCore Analytics must perform as the customer.

| CUEC ID | Customer Responsibility | CloudCore Action Needed |
|---|---|---|
| CUEC-01 | Configure customer user access appropriately | HR and IT must approve CloudCore admin users in PayLink |
| CUEC-02 | Remove customer users when access is no longer needed | CloudCore must include PayLink in offboarding checklist |
| CUEC-03 | Use strong authentication where available | CloudCore must enforce MFA for PayLink admin users |
| CUEC-04 | Review customer-side user access periodically | CloudCore should review PayLink user access quarterly |
| CUEC-05 | Notify vendor of suspected security issues | Incident response procedure should include vendor notification steps |

---

## Follow-Up Questions for Vendor

1. What remediation actions were completed for the missing access review sign-off exception?
2. Can you provide the latest quarterly access review evidence?
3. Can you provide the latest privileged access review evidence?
4. Do all MFA exceptions have documented approval, owner, justification, and expiration date?
5. Can you provide the current MFA exception register?
6. Has a full BCP/DR test been completed within the last 12 months?
7. Can you provide the full subprocessor list?
8. How frequently are subprocessors reviewed for security risk?
9. What is the committed customer notification timeline for security incidents?
10. Can the incident notification SLA be included in the contract?

---

## Analyst Assessment

The SOC 2 report provides useful assurance that PayLink HR Solutions has a structured security program. The unqualified opinion is positive, but the noted exceptions and unclear supporting evidence require follow-up before full approval.

The most important follow-up items are access review evidence, privileged access approval evidence, MFA exception tracking, incident notification terms, subprocessor oversight, and updated business continuity testing.

---

## SOC 2 Review Decision

**Decision:** Conditional approval pending follow-up.

**Reason:** The vendor has a SOC 2 Type II report and several acceptable controls, but exceptions and unclear evidence must be addressed due to the sensitivity of payroll, tax, and banking data.

---

## Notes

This SOC 2 review is part of a mock GRC portfolio project. It demonstrates SOC 2 report review, vendor due diligence, exception analysis, CUEC awareness, risk assessment, and remediation planning skills.
