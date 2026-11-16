# SQL Log Analysis & Filtering for Security Investigations

## Overview
This project demonstrates the practical application of **SQL filtering techniques** to investigate security incidents, analyze login attempts, and retrieve employee data. Working within a MariaDB environment, the project applies relational database querying to detect suspicious after-hours login activity, filter unauthorized geographic access, and target specific departments for security updates.

---

## Core Competencies Demonstrated
- **Advanced SQL Filtering:** Using comparison operators (`=`, `!=`), logical operators (`AND`, `OR`), and pattern matching (`LIKE`, `NOT LIKE` with wildcards) to query database tables.
- **Log Analysis:** Investigating authentication logs (`log_in_attempts`) to isolate failed logins, time-based anomalies, and non-compliant geographic regions.
- **Asset & Personnel Management:** Querying organizational directories (`employees`) to target specific departments (Marketing, Sales, Finance) and physical office locations (East building) for patching and security updates.

---

## Repository Files
* `activity-instructions.docx` – Official task overview and step-by-step instructions.
* `activity-template-sql-filters.docx` – Original blank activity template.
* `completed-sql-filters-report.docx` – Completed report detailing SQL queries, command-line screenshots, result counts, and security analysis.
* `table-formats.docx` – Reference document detailing the schema of the `log_in_attempts` and `employees` tables.

---
*Note: This practical exercise was completed as part of the **Google Cybersecurity Professional Certificate** program.*
