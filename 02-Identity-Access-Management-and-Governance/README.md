# 02. Identity & Access Management (IAM), Governance, and Security Controls

## Overview
This directory contains case studies, risk assessments, and practical scenarios focused on **Identity and Access Management (IAM)**, **Access Control Policies**, and **Security Frameworks** (such as NIST Cybersecurity Framework and NIST SP 800-53).

The projects documented here reflect real-world principles of enforcing data privacy, implementing least privilege access, mitigating insider risk, and aligning business operations with industry security standards.

---

## Core Competencies Demonstrated
- **Principle of Least Privilege (PoLP):** Designing, auditing, and enforcing minimal necessary permissions across organizational roles.
- **Role-Based Access Control (RBAC):** Restricting systems access to authorized users based on defined business functions.
- **Security Framework Mapping:** Applying **NIST CSF** (Identify, Protect, Detect, Respond, Recover) and specific **NIST SP 800-53** controls (e.g., AC-6) to business scenarios.
- **Data Leak Mitigation & Risk Assessment:** Analyzing operational workflows to identify privilege creep, unauthorized data sharing, and policy gaps.
- **Access Control & Incident Investigation:** Cross-referencing event logs with employee directories to detect unauthorized financial transactions and unrevoked contractor accounts.

---

## Repository Index / Case Studies

| Project / Exercise | Description | Key Standards & Tools | Status |
| :--- | :--- | :--- | :--- |
| **[Data Leak Analysis](./data-leak-risk-assessment-least-privilege/)** | Analysis of an accidental internal data leak caused by improper sharing permissions and excessive user privileges. | NIST SP 800-53 (AC-6), NIST CSF (PR.DS-5), Least Privilege | Completed |
| **[Payroll Incident Investigation](./access-control-payroll-incident-analysis/)** | Investigation of an unauthorized financial transaction using system event logs and employee directory cross-referencing. | Access Control, Separation of Duties (SoD), Offboarding Audits | Completed |
| *[Upcoming Case Study]* | *Reserved for future IAM, RBAC, or Governance projects.* | *TBD* | *In Progress* |

---

## General Takeaways
Effective security governance relies on a balance between **technical controls** (automated revocation, strict permissions) and **policy enforcement** (regular audits, role definitions). Minimizing the attack surface begins with controlling who has access to sensitive assets.

---
*Note: These practical exercises were completed as part of the **Google Cybersecurity Professional Certificate** program.*
