# Vendor Remediation Tracker

## Purpose

This remediation tracker documents corrective actions required for risks identified during the PayLink HR Solutions vendor risk assessment.

The goal is to track vendor risk issues, assign ownership, define required evidence, and support a conditional approval decision.

---

## Remediation Tracker Table

| Finding ID | Related Risk | Finding Title | Risk Level | Corrective Action | Owner | Target Due Date | Status | Evidence Needed for Closure |
|---|---|---|---|---|---|---|---|---|
| VF-01 | VR-01 | Incomplete Access Review Evidence | High | Request updated quarterly access review evidence showing reviewer name, completion date, system reviewed, exceptions, and remediation notes. | Vendor Security | Before onboarding | Open | Latest access review report with reviewer sign-off |
| VF-02 | VR-02 | Privileged Access Approval Gap | High | Request privileged access review evidence showing admin users, approver, approval date, business justification, and exceptions. | Vendor Security | Before onboarding | Open | Admin access review report with management approval |
| VF-03 | VR-03 | MFA Exception Tracking Weakness | High | Require vendor to provide MFA exception register with owner, approval, justification, compensating control, and expiration date. | Vendor Security | Before onboarding | Open | MFA exception register |
| VF-04 | VR-04 | Vague Incident Notification Timeline | High | Add specific customer incident notification SLA to the contract, such as 24–72 hours after confirmed impact. | Legal + Security | Before contract signature | Open | Updated contract language or security addendum |
| VF-05 | VR-05 | Outdated BCP/DR Test Evidence | Medium | Request updated business continuity and disaster recovery test results or documented upcoming test schedule. | Vendor Operations | 30 days | Open | BCP/DR test report or scheduled test plan |
| VF-06 | VR-06 | Incomplete Subprocessor Review Evidence | High | Request complete subprocessor list and evidence that critical subprocessors are reviewed for security risk. | Vendor Management | Before onboarding | Open | Subprocessor list and review evidence |
| VF-07 | VR-07 | Data Deletion Timeline Unclear | High | Define data deletion timeline and certificate of deletion requirement in the contract or data processing agreement. | Legal + Privacy | Before contract signature | Open | Contract clause or DPA language |
| VF-08 | VR-08 | Vendor-Managed Encryption Keys Only | Medium | Document vendor-managed key model and confirm compensating controls such as encryption standards, key rotation, and access restrictions. | Security | 30 days | Open | Encryption overview and risk acceptance if needed |
| VF-09 | VR-09 | Cyber Insurance Evidence Not Provided | Medium | Request cyber insurance certificate if required by procurement or vendor risk policy. | Legal / Procurement | 30 days | Open | Cyber insurance certificate |
| VF-10 | VR-10 | Bridge Letter May Be Needed | Medium | Request bridge letter if onboarding date is outside SOC 2 report coverage period. | Vendor Security | Before onboarding | Open | Bridge letter covering period after SOC 2 report end date |

---

## Status Definitions

| Status | Meaning |
|---|---|
| Open | Issue has been identified but remediation has not started |
| In Progress | Owner is working on remediation |
| Pending Vendor Response | Waiting for vendor evidence or clarification |
| Pending Internal Review | Vendor response received and awaiting review |
| Closed | Evidence reviewed and issue resolved |
| Risk Accepted | Management formally accepted the remaining risk |
| Blocker | Issue must be resolved before vendor can be approved |

---

## Conditional Approval Requirements

PayLink HR Solutions may move forward only if the following items are completed before onboarding:

1. Updated access review evidence is provided
2. Privileged access approval evidence is provided
3. MFA exception register is reviewed
4. Incident notification SLA is added to the contract
5. Subprocessor list and review evidence are provided
6. Data deletion timeline is contractually documented
7. Bridge letter is provided if needed

---

## Recommended Remediation Priority

| Priority | Finding | Reason |
|---|---|---|
| 1 | Vague incident notification timeline | Contract must clearly define breach notification expectations |
| 2 | Data deletion timeline unclear | Employee payroll and banking data must have clear deletion requirements |
| 3 | Incomplete subprocessor review evidence | Subprocessors may introduce additional third-party risk |
| 4 | MFA exception tracking weakness | Authentication exceptions must be approved and monitored |
| 5 | Incomplete access review evidence | Access review evidence supports SOC 2 assurance |
| 6 | Privileged access approval gap | Admin access must be justified and approved |

---

## Analyst Notes

The recommended decision is conditional approval, not full approval.

The vendor appears to have a structured security and compliance program, but several high-risk items must be resolved because the vendor will process sensitive employee payroll, tax, banking, and personal information.

Items related to contract language, incident notification, data deletion, and subprocessors should be resolved before contract signature. Evidence-related items should be resolved before production onboarding.

---

## Notes

This vendor remediation tracker is part of a mock GRC portfolio project. It demonstrates third-party risk remediation tracking, vendor issue management, ownership assignment, conditional approval criteria, and evidence-based closure.
