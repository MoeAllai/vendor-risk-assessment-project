# Vendor Executive Summary

## Purpose

This executive summary provides a leadership-level overview of the vendor risk assessment for PayLink HR Solutions.

The goal is to summarize the vendor’s risk level, key findings, remediation requirements, and final approval recommendation.

---

## Vendor Assessment Overview

CloudCore Analytics is evaluating PayLink HR Solutions as a new payroll and HR processing vendor.

PayLink HR Solutions will process sensitive employee information, including personal data, salary information, tax records, and bank account details. Because of the sensitivity of the data and the critical nature of payroll operations, the vendor is classified as a **high inherent risk vendor**.

The assessment included review of vendor intake information, data sensitivity, security questionnaire responses, SOC 2 report notes, access control practices, incident response, business continuity, subprocessor oversight, data retention, and contract requirements.

---

## Overall Assessment

PayLink HR Solutions appears to have a structured security and compliance program, including documented security policies, MFA, encryption, incident response procedures, business continuity planning, and a SOC 2 Type II report.

However, the assessment identified several gaps that require remediation or contractual clarification before full approval.

The recommended decision is:

## Conditional Approval Pending Remediation

This means the vendor may continue through the onboarding process, but high-priority risks must be addressed before production use or contract signature.

---

## Inherent Risk Rating

| Risk Factor | Rating | Reason |
|---|---|---|
| Data Sensitivity | High | Vendor processes employee payroll, tax, banking, and personal data |
| Business Criticality | High | Payroll disruption may directly affect employee payments |
| External Hosting | Medium | Vendor hosts the payroll platform externally |
| Subprocessor Use | Medium | Vendor uses subprocessors for hosting and tax document processing |
| Privacy / Regulatory Impact | High | Sensitive employee information requires strong protection |
| Overall Inherent Risk | High | Sensitive data plus critical business function |

---

## Key Findings

| Priority | Finding | Risk Level | Business Impact |
|---|---|---|---|
| 1 | Vague incident notification timeline | High | Company may not receive timely notice of a security incident |
| 2 | Data deletion timeline unclear | High | Employee data may not be deleted within expected timeframes after termination of service |
| 3 | Incomplete subprocessor review evidence | High | Additional third-party risk may not be fully understood |
| 4 | MFA exception tracking weakness | High | Authentication exceptions may not be properly approved or monitored |
| 5 | Incomplete access review evidence | High | Vendor may not be able to prove access is consistently reviewed |
| 6 | Privileged access approval gap | High | Admin access may not be properly justified or approved |
| 7 | Outdated BCP/DR test evidence | Medium | Resilience testing may not be current |
| 8 | Vendor-managed encryption keys only | Medium | Customer has limited control over encryption key management |
| 9 | Cyber insurance evidence not provided | Medium | Risk transfer evidence is incomplete |
| 10 | Bridge letter may be needed | Medium | SOC 2 report may not cover the full onboarding period |

---

## Required Remediation Before Approval

The following items should be completed before final vendor approval:

1. Provide updated access review evidence with reviewer sign-off
2. Provide privileged access review evidence with management approval
3. Provide MFA exception register
4. Add specific incident notification SLA to the contract
5. Provide full subprocessor list and recent review evidence
6. Define data deletion timeline and certificate of deletion process
7. Provide updated BCP/DR test results or testing schedule
8. Provide bridge letter if SOC 2 report coverage period does not cover onboarding date

---

## Contract Recommendations

The contract or security addendum should include:

- Specific incident notification timeline
- Data retention and deletion requirements
- Certificate of deletion requirement
- Subprocessor notification and review requirements
- Security control commitments
- Right to request updated compliance evidence
- Confidentiality and data protection requirements
- Breach cooperation requirements
- Cyber insurance requirement if required by company policy

---

## Final Recommendation

Based on the vendor risk assessment, PayLink HR Solutions should receive **conditional approval**.

The vendor should not receive full production approval until high-priority issues are remediated, contract terms are clarified, and required evidence is reviewed.

If the vendor provides acceptable evidence and agrees to the required contract terms, the residual risk may be reduced to an acceptable level for onboarding.

---

## Analyst Conclusion

PayLink HR Solutions is a high inherent risk vendor due to the sensitive employee payroll, tax, banking, and personal information it will process.

The vendor has a generally mature control environment, but several gaps must be addressed before onboarding. The most important risks relate to incident notification, data deletion, subprocessor oversight, MFA exceptions, access review evidence, and privileged access approval.

The recommended decision is conditional approval with remediation tracking and legal/security follow-up before final onboarding.

---

## Notes

This vendor executive summary is part of a mock GRC portfolio project. It demonstrates third-party risk reporting, executive communication, conditional approval decision-making, risk prioritization, and remediation planning.
