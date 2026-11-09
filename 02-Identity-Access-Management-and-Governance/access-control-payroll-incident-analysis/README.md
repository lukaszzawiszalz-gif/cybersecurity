# Access Control & Payroll Incident Investigation

## Project Overview
This project investigates an unauthorized payroll transaction incident at a growing business. By cross-referencing system event logs with the employee directory, the objective is to identify the threat actor, uncover underlying access control flaws (such as overly permissive administrative rights and unrevoked contractor accounts), and formulate robust security mitigations.

---

## Key Analysis & Findings

* **Incident Details:** Event log analysis (`ID 1227`) revealed that a payroll event (`FAUX_BANK`) was executed using the `Legal\Administrator` account from IP address `152.207.255.255`.
* **Threat Actor Identification:** Cross-referencing with the employee directory identified the user as *Robert Taylor Jr.* (a legal contractor whose contract concluded on December 27, 2019). The account remained active and was accessed over three years after contract termination.
* **Access Control Issues:** 
  1. **Excessive Privileges:** Every user (including contractors and part-time staff) held full administrator rights ("everybody can do anything").
  2. **Lack of Offboarding Controls:** Accounts of former employees and contractors were never deactivated or revoked.
* **Recommendations:** 
  * Implement formal, automated procedures for revoking file and system access immediately upon employment or contract termination.
  * Introduce **Separation of Duties (SoD)** to prevent single users from holding overarching administrative rights over critical financial processes.
  * Enforce the **Principle of Least Privilege (NIST SP 800-53: AC-6)** to ensure users only possess minimum necessary permissions.

---

## Repository Files
* `completed-access-control-worksheet.docx` – Completed access control worksheet and investigation findings.
* `activity-template-access-control-worksheet.docx` – Original blank activity template.
* `accounting-exercise.xlsx` – Supporting spreadsheet containing two tabs: Event Log and Employee Directory.
* `activity-instructions.docx` – Official task overview and scenario guidelines.

---
*Note: This practical exercise was completed as part of the **Google Cybersecurity Professional Certificate** program.*
