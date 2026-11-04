# Data Leak Risk Assessment & Least Privilege Enforcement

## Project Overview
This project investigates an internal data leak scenario within an educational technology company. The incident involved the accidental exposure of confidential business plans and internal documents to an external partner due to improper access management and unrevoked permissions.

The objective of this analysis is to evaluate the root causes, map the incident to industry security frameworks, and formulate actionable mitigation strategies based on the principle of least privilege.

---

## Key Analysis & Findings

* **Identified Issues:** The incident was primarily driven by the manager's failure to revoke folder access after a meeting, an employee accidentally sharing a link to sensitive internal folders instead of promotional materials, and the external partner inadvertently publishing the link on social media.
* **Framework Alignment:** Evaluated against the **NIST Cybersecurity Framework (CSF)** under the *Protect (PR.DS-5)* subcategory for data leakage protections, utilizing **NIST SP 800-53 (AC-6)** guidelines regarding the *Least Privilege* control.
* **Recommendations:** 
  1. Implement **Role-Based Access Control (RBAC)** to restrict sensitive resources strictly by user function.
  2. Enforce **automatic expiration and revocation** of shared links and temporary permissions.
  3. Conduct **regular access audits** to identify and eliminate privilege creep.

---

## Repository Files
* `completed-data-leak-worksheet.docx` – Completed risk assessment and security evaluation worksheet.
* `activity-template-data-leak-worksheet.docx` – Original blank activity template.
* `activity-instructions.docx` – Official task overview, scenario description, and step-by-step guidelines.

---
*Note: This practical exercise was completed as part of the **Google Cybersecurity Professional Certificate** program.*
