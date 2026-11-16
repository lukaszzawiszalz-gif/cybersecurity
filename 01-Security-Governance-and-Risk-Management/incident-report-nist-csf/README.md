# Incident Report & NIST CSF Analysis

## Project Overview
This project documents a comprehensive cybersecurity incident report following a Denial of Service (DoS) attack against a multimedia company's internal network. Aligned with the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)**, the report applies the five core functions—*Identify, Protect, Detect, Respond, and Recover*—to analyze the event, assess the root cause (unconfigured firewall and ICMP flood), and outline proactive remediation strategies.

---

## NIST CSF Core Functions Applied
1. **Identify:** Defined the DoS attack scope, identifying impacted network resources and the underlying vulnerability (unrestricted ICMP traffic due to firewall misconfiguration).
2. **Protect:** Implemented rate-limiting rules, source IP verification, and baseline security hardening.
3. **Detect:** Deployed SIEM monitoring tools and IDS/IPS solutions to track network traffic anomalies and flag suspicious characteristics.
4. **Respond:** Established formal containment, isolation, neutralization, and log analysis procedures.
5. **Recover:** Outlined systematic validation, functional testing, and stakeholder communication protocols to restore services safely.

---

## Repository Files
* `activity-instructions.docx` – Official task overview and scenario guidelines.
* `activity-template-incident-report.docx` – Original blank analysis template.
* `applying-the-nist-csf.docx` – Reference guide detailing the five core functions of the NIST CSF.
* `completed-incident-report-analysis.docx` – Completed incident report analysis mapping the security event to the NIST CSF framework.

---
*Note: This practical exercise was completed as part of the **Google Cybersecurity Professional Certificate** program.*
