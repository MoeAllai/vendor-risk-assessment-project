# Vendor Intake Form

## Purpose

This vendor intake form documents basic onboarding, business, data, and risk information for PayLink HR Solutions.

The goal is to determine the vendor’s inherent risk before completing the detailed security review.

---

## Vendor Intake Summary

| Field | Response |
|---|---|
| Vendor Name | PayLink HR Solutions |
| Vendor Type | Payroll and HR processing platform |
| Business Owner | HR Department |
| Requesting Department | Human Resources |
| Vendor Contact | security@paylinkhr.example |
| Service Description | Cloud-based payroll, tax documentation, direct deposit, and HR reporting platform |
| Proposed Start Date | Q3 2026 |
| Assessment Type | New vendor onboarding |
| Vendor Criticality | High |
| Inherent Risk Rating | High |
| Final Recommendation | Conditional approval pending remediation |

---

## Business Justification

The HR Department is requesting PayLink HR Solutions to reduce manual payroll processing, improve payroll accuracy, automate tax documentation, support direct deposit, and centralize employee payroll records.

The vendor supports a critical business function because payroll delays or system outages may directly affect employee payments and business operations.

---

## Data Classification

| Data Element | Classification | Notes |
|---|---|---|
| Employee names | Confidential | Personal employee information |
| Home addresses | Confidential | Personal employee information |
| Phone numbers | Confidential | Personal contact information |
| Personal email addresses | Confidential | Personal contact information |
| Salary information | Restricted | Sensitive payroll data |
| Bank account details | Restricted | Direct deposit information |
| Tax records | Restricted | Sensitive tax documentation |
| Employment status | Confidential | HR record information |
| Benefits information | Confidential | Employee benefit details |

---

## Data Access and Processing

| Question | Response |
|---|---|
| Will the vendor store company data? | Yes |
| Will the vendor process employee personal data? | Yes |
| Will the vendor process financial or banking data? | Yes |
| Will the vendor access production company systems? | No |
| Will the vendor integrate with internal HR systems? | Yes |
| Will the vendor use subcontractors? | Yes |
| Will data be stored outside the United States? | No, based on vendor response |
| Will the vendor require employee login access? | Yes |
| Will CloudCore administrators access the vendor portal? | Yes |

---

## Inherent Risk Assessment

| Risk Factor | Rating | Reason |
|---|---|---|
| Data Sensitivity | High | Vendor handles employee payroll, tax, banking, and personal data |
| Business Criticality | High | Payroll is a critical business process |
| System Integration | Medium | Vendor integrates with HRIS but does not access production SaaS systems |
| External Hosting | Medium | Vendor hosts the platform in its own cloud environment |
| Subcontractor Use | Medium | Vendor uses subprocessors for hosting and tax document processing |
| Regulatory / Privacy Exposure | High | Employee personal and financial data requires strong privacy controls |
| Overall Inherent Risk | High | Sensitive data plus critical payroll process |

---

## Required Vendor Evidence

The following evidence should be requested before approval:

| Evidence Item | Required? | Reason |
|---|---|---|
| Completed security questionnaire | Yes | Needed to assess vendor controls |
| SOC 2 Type II report | Yes | Needed to review independent control assurance |
| Bridge letter | Yes, if SOC 2 period does not cover current date | Needed to cover the gap between SOC 2 report period and onboarding |
| Information security policy summary | Yes | Needed to understand vendor security governance |
| Incident response policy summary | Yes | Needed to confirm breach response process |
| Business continuity / disaster recovery test results | Yes | Needed to confirm operational resilience |
| Data retention and deletion policy | Yes | Needed to confirm data lifecycle controls |
| Subprocessor list | Yes | Needed to assess subcontractor risk |
| Encryption overview | Yes | Needed to confirm data protection |
| Access control overview | Yes | Needed to assess user access governance |
| Cyber insurance certificate | Preferred | Useful for risk transfer and contract review |

---

## Initial Risk Decision

Based on the intake review, PayLink HR Solutions is classified as a **high inherent risk vendor** because it processes sensitive employee financial, payroll, tax, and personal information.

The vendor should not be fully approved until the security questionnaire, SOC 2 report, incident response terms, business continuity evidence, subcontractor oversight, and data retention controls are reviewed.

Recommended initial decision:

**Proceed with detailed vendor risk assessment.**

---

## Notes

This vendor intake form is part of a mock GRC portfolio project. It demonstrates vendor onboarding, data classification, inherent risk assessment, evidence request planning, and third-party risk management skills.
