# Commercial Bank Risk Assessment & Risk Register

## Project Overview
This project simulates a quantitative and qualitative security risk assessment for a commercial bank operating in a coastal environment. Aligned with the **NIST Cybersecurity Framework (NIST CSF)**, the assessment evaluates vulnerabilities threatening core assets (bank funds), calculates risk priority scores, and prioritizes remediation efforts.

---

## Risk Assessment Methodology

Risk priority scores are calculated using the standard risk formula:
$$\text{Likelihood (1–3)} \times \text{Impact Severity (1–3)} = \text{Risk Priority (1–9)}$$

### Evaluated Threat Vectors & Prioritization
1. **Financial Records Leak (Priority: 9)** – *High Likelihood (3) / High Severity (3)*: Publicly accessible database backups pose an extreme risk of severe regulatory fines, reputational destruction, and financial loss.
2. **Compromised User Database (Priority: 6)** – *Moderate Likelihood (2) / High Severity (3)*: Weak encryption on customer databases exposes sensitive financial and PII data to threat actors.
3. **Business Email Compromise (Priority: 4)** – *Moderate Likelihood (2) / Moderate Severity (2)*: Insider social engineering risks across 120 on-premise and remote employees.
4. **Physical Theft (Priority: 2)** – *Low Likelihood (1) / Moderate Severity (2)*: Unlocked safe vulnerability mitigated by a low-crime coastal location profile.
5. **Supply Chain Disruption (Priority: 1)** – *Low Likelihood (1) / Low Severity (1)*: Delivery delays driven by occasional coastal weather events.

---

## Repository Files
* `activity-instructions.docx` – Official task overview and scenario guidelines.
* `activity-template-risk-register.docx` – Original blank activity template.
* `completed-risk-register.docx` – Completed risk register matrix with likelihood, severity, and priority scoring.

---
*Note: This practical exercise was completed as part of the **Google Cybersecurity Professional Certificate** program.*
