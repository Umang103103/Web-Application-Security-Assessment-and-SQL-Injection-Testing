# Web Application Security Assessment and SQL Injection Testing

This repository contains a security assessment of the Damn Vulnerable Web Application (DVWA), focused specifically on identifying and exploiting SQL Injection vulnerabilities.

##  Key Activities

- Manual and automated SQL Injection testing (Union-based, Error-based, Blind, and Authentication Bypass)
- Exploited vulnerabilities in DVWA's user input fields and login forms
- Verified results using SQLMap for automated exploitation and data dumping

##  Tools Used

- DVWA (Lab Environment)
- SQLMap
- Kali Linux

##  Remediation Recommendations

- Use parameterized queries (prepared statements)
- Sanitize and validate all user input
- Implement least privilege on database users
- Hide detailed error messages from users

##  Author

Umang Giri
