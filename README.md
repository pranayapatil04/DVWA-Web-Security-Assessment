# DVWA-Web-Security-Assessment
Security assessment of DVWA demonstrating SQL Injection, XSS, CSRF, Brute Force, and File Inclusion vulnerabilities with mitigation recommendations and professional pentest reporting.
# DVWA Web Application Security Assessment

## Project Overview

This repository contains a Web Application Security Assessment performed on DVWA (Damn Vulnerable Web Application) in a controlled and authorized local environment.

The purpose of this project was to identify common web application vulnerabilities, understand their impact, demonstrate exploitation techniques, and recommend remediation measures.

---

## Objectives

* Install and configure DVWA locally
* Perform security testing on vulnerable modules
* Document findings with screenshots
* Analyze security risks
* Provide mitigation recommendations
* Prepare a professional penetration testing report

---

## Vulnerabilities Assessed

### SQL Injection

Demonstrated how unsanitized user input can manipulate SQL queries and expose sensitive data.

### Cross-Site Scripting (XSS)

Demonstrated execution of malicious JavaScript within the victim's browser.

### Cross-Site Request Forgery (CSRF)

Evaluated the application's resistance against unauthorized actions performed on behalf of authenticated users.

### Brute Force Authentication

Assessed authentication security against repeated login attempts.

### File Inclusion

Tested for improper handling of file path parameters that may expose sensitive files.

---

## Tools Used

* DVWA
* XAMPP
* Burp Suite Community Edition
* Web Browser

---

## Risk Summary

| Vulnerability        | Severity |
| -------------------- | -------- |
| SQL Injection        | Critical |
| Cross-Site Scripting | High     |
| File Inclusion       | High     |
| Brute Force          | Medium   |
| CSRF                 | Medium   |

---

## Deliverables

* Professional Penetration Testing Report
* Vulnerability Screenshots
* Findings and Remediation Recommendations

---


