# FUTURE_CS_01 – Web Application Security Testing

Internship Track: Cyber Security (CS)  
Task: Task 1 – Web Application Vulnerability Assessment  
Intern: Fowsunnissa A.G.

---

##  Overview
This repository contains my work for Task 1 of the Future Interns Cyber Security Internship.
The objective of this task was to perform security testing on a vulnerable web application
and identify common web security vulnerabilities.

The testing was conducted on **Altoro Mutual**, a publicly available demo banking website
designed for ethical hacking and security learning.

---

## Tools Used
- Web Browser (Chrome)
- Manual penetration testing techniques
- Vulnerable test application: http://demo.testfire.net/

---

##  Vulnerabilities Identified

### SQL Injection – Found
SQL Injection payloads were used in the login form to bypass authentication,
confirming a SQL Injection vulnerability.

Payload example:
' OR 1=1--

---

### Cross-Site Scripting (XSS) – Found
JavaScript payloads were executed through user input fields,
confirming the presence of an XSS vulnerability.

Payload example:

<script>alert('XSS Test')</script>---

### Weak Login – Found
The application allowed authentication using weak or default credentials.
This indicates the absence of strong password policies and authentication controls.

---

## Evidence
Screenshots demonstrating:
- SQL Injection authentication bypass
- XSS payload execution
- Successful login using weak credentials  

are included in the `screenshots/` folder.

---

##  Detailed Report
The complete security assessment report is included as:
**Task1_Report_AltoroMutual_Fowsunnissa_AG.pdf**

---

## Learning Outcomes
- Understanding SQL Injection attacks
- Identifying XSS vulnerabilities
- Testing authentication weaknesses
- Ethical hacking methodology
- Professional security documentation

---

##  Status
Task 1 successfully completed.


---
