# 🛡️ Hackazone Security Hardening Project

## 📌 Project Overview
The goal of this project was to identify, exploit, and remediate critical security vulnerabilities within the **Hackazone** application. The assessment followed the industry-standard **OWASP Top 10** framework and focused on maintaining the **CIA Triad**:
* **Confidentiality:** Ensuring sensitive data is accessed only by authorized users.
* **Integrity:** Protecting data from unauthorized modification.
* **Availability:** Guaranteeing that services remain accessible under attack.

---

## 📁 Weekly Reports Summary

### 🔍 [Week 01: Vulnerability Discovery]
* **Focus:** Automated and manual penetration testing to identify system weaknesses.
* **Key Findings:** Identified critical flaws including `SQL Injection`, `Command Injection`, and `Stored XSS`.
* **Tools Used:** OWASP ZAP, Nmap, Burp Suite.
* **Deliverable:** [📄 View Week 1 Report](.Week_01--Security_Assessment_Report_W1.pdf)

### 🛡️ [Week 02: Mitigation & Hardening]
* **Focus:** Implementing technical defenses and closing identified security gaps.
* **Measures Taken:** * Configured **JWT Authentication** for secure session management.
    * Implemented **RBAC** (Role-Based Access Control) to restrict unauthorized access.
    * Deployed **Helmet.js** to secure HTTP headers.
* **Deliverable:** [📄 View Week 2 Report](.Week_02--Vulnerability_Mitigation_Report_W2.pdf)

### 📋 [Week 03: Auditing & Final Reporting]
* **Focus:** Post-remediation testing, verification of fixes, and system monitoring.
* **Implementation:** * Established a secure **Logging System** using the **Winston** library.
    * Conducted final audits to ensure all vulnerabilities were successfully mitigated.
* **Deliverable:** [📄 View Week 3 Report](.Week_03--Final_Security_Audit_Report_W3.pdf)

---

## 🛠️ Tools & Technologies

| Category | Tools / Libraries |
| :--- | :--- |
| **Security Testing** | `OWASP ZAP`, `Burp Suite`, `ffuf`, `Nmap` |
| **Backend Defense** | `Node.js`, `Express.js` |
| **Security Packages** | `JWT`, `Helmet.js`, `Winston Logging`, `bcrypt` |

---

## 🏁 Conclusion
Through this 3-week engagement, the application’s security posture was significantly improved. By moving from a vulnerable state to a hardened environment, we ensured that the system is better protected against modern cyber threats.
