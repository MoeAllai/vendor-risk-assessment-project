# Vendor Interview Q&A

## Purpose

This document prepares interview-ready answers based on the Vendor Risk Assessment Project.

The goal is to explain the project clearly during interviews and demonstrate practical understanding of third-party risk management, vendor due diligence, SOC 2 review, risk rating, and remediation tracking.

---

## Q1: Can you walk me through this vendor risk project?

**Answer:**

This project simulates a third-party risk assessment for a mock SaaS company evaluating a new payroll vendor.

The vendor, PayLink HR Solutions, would process sensitive employee data such as payroll information, tax records, bank account details, addresses, and employment information.

I reviewed the vendor intake information, classified the data involved, reviewed security questionnaire responses, analyzed mock SOC 2 report notes, identified risks, created a vendor risk register, built a remediation tracker, and prepared an executive summary with a conditional approval recommendation.

---

## Q2: Why was this vendor considered high risk?

**Answer:**

The vendor was considered high inherent risk because it processes sensitive employee personal, financial, tax, and payroll data.

It also supports a critical business function. If the payroll vendor has an outage or security issue, it could affect employee payments, privacy, and business operations.

Because of the data sensitivity and business criticality, the vendor required a detailed security and compliance review before approval.

---

## Q3: What evidence would you request from a high-risk vendor?

**Answer:**

For a high-risk vendor, I would request:

- Completed security questionnaire
- SOC 2 Type II report
- Bridge letter if the SOC 2 period is outdated
- Information security policy summary
- Incident response policy summary
- Business continuity and disaster recovery test results
- Data retention and deletion policy
- Subprocessor list
- Encryption overview
- Access control overview
- Cyber insurance certificate if required by policy

The goal is to verify that the vendor’s questionnaire responses are supported by actual evidence.

---

## Q4: What were the biggest risks you identified?

**Answer:**

The biggest risks were:

- Vague incident notification timeline
- Unclear data deletion timeline
- Incomplete subprocessor review evidence
- MFA exception tracking weakness
- Incomplete access review evidence
- Privileged access approval gaps

These were important because the vendor would handle sensitive payroll and banking data, so weak controls or unclear contract terms could create security, privacy, and operational risk.

---

## Q5: What does conditional approval mean?

**Answer:**

Conditional approval means the vendor may continue through the onboarding process, but certain risks must be resolved before full approval or production use.

In this project, I recommended conditional approval because the vendor had a generally mature security program and a SOC 2 Type II report, but several high-priority items still needed remediation or contract clarification.

Examples included incident notification SLA, data deletion timeline, subprocessor evidence, and MFA exception tracking.

---

## Q6: How did you review the SOC 2 report?

**Answer:**

I reviewed the SOC 2 report for control areas relevant to vendor risk, including access control, privileged access, MFA, incident response, encryption, business continuity, vendor management, and monitoring.

I looked for the report period, auditor opinion, scope, exceptions, and complementary user entity controls.

The report had an unqualified opinion, which was positive, but it also had exceptions related to access review evidence, privileged access approval evidence, MFA exceptions, and outdated BCP/DR testing.

---

## Q7: What are Complementary User Entity Controls?

**Answer:**

Complementary User Entity Controls, or CUECs, are controls that the customer must perform for the vendor’s control environment to work effectively.

For example, even if the vendor has strong access controls, CloudCore Analytics still needs to manage its own PayLink users properly.

That includes approving customer-side users, removing access when employees leave, enforcing MFA where available, and reviewing customer-side access periodically.

---

## Q8: How would you handle a vendor with an old SOC 2 report?

**Answer:**

If a SOC 2 report does not cover the current period, I would request a bridge letter.

A bridge letter helps cover the gap between the SOC 2 report end date and the current onboarding or review date.

If the report is too old or the vendor cannot provide a bridge letter, I would document the risk, request additional evidence, and potentially require management risk acceptance before approval.

---

## Q9: Why is incident notification language important?

**Answer:**

Incident notification language is important because the customer needs to know when and how quickly the vendor will notify them about a security incident.

A vague phrase like “as soon as reasonably possible” may not be enough for a high-risk vendor.

For a vendor handling payroll and banking data, I would recommend a specific notification timeline in the contract or security addendum, such as notification within 24 to 72 hours after confirmed impact.

---

## Q10: Why does subprocessor risk matter?

**Answer:**

Subprocessor risk matters because the vendor may rely on other third parties to host systems, process data, or provide services.

Even if the main vendor has strong controls, a subprocessor weakness could still affect customer data.

For this project, I requested a full subprocessor list and evidence that critical subprocessors are reviewed for security risk.

---

## Q11: What is the difference between inherent risk and residual risk?

**Answer:**

Inherent risk is the risk before controls or remediation are considered.

Residual risk is the remaining risk after controls, remediation, contracts, or risk treatment are applied.

In this project, PayLink HR Solutions had high inherent risk because it processes sensitive payroll and banking data. After evidence review, remediation, and contract updates, the residual risk may become acceptable for onboarding.

---

## Q12: How would you explain this project to a hiring manager?

**Answer:**

I built a vendor risk assessment project for a mock payroll vendor to demonstrate practical third-party risk management skills.

I created a vendor intake form, reviewed security questionnaire responses, analyzed SOC 2 review notes, identified risks, built a vendor risk register, created a remediation tracker, and wrote an executive summary with a conditional approval recommendation.

The project helped me practice vendor due diligence from intake to final recommendation.

---

## Q13: How would you follow up with the vendor?

**Answer:**

I would send the vendor a follow-up request listing the missing evidence and clarification items.

I would prioritize high-risk items first, such as incident notification SLA, data deletion timeline, subprocessor review evidence, MFA exception register, access review evidence, and privileged access approval evidence.

Then I would track responses in a remediation tracker and validate whether the evidence is sufficient before closing each item.

---

## Q14: What would make you reject the vendor?

**Answer:**

I would recommend rejecting or pausing the vendor if they could not provide evidence for critical controls, refused to define incident notification or data deletion requirements, had major unresolved SOC 2 exceptions, or used high-risk subprocessors without proper oversight.

For a payroll vendor, weak security and unclear contract protections would be serious concerns because the vendor handles sensitive employee financial and personal data.

---

## Q15: Give me a short interview version of this project.

**Answer:**

I built a mock vendor risk assessment for a payroll vendor that would process sensitive employee payroll, tax, and banking data.

I reviewed the vendor intake, security questionnaire, SOC 2 notes, access control evidence, incident response, business continuity, subprocessor risk, and data deletion process.

I identified risks, rated them, created a remediation tracker, and recommended conditional approval pending evidence and contract updates.

---

## Notes

This Q&A document is part of a mock GRC portfolio project. It is designed to help explain third-party risk management work clearly during interviews.
