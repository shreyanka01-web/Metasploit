# Metasploitable 2 Reconnaissance Exercise

## Student Details
- Name:Shreyanka B A
- Course: Ethical Hacking
- Date:2-5-2026

---

## Task 1: Network Connectivity
- Verified connectivity using ping
- 0% packet loss observed

---

## Task 2: Port Scanning
- Open ports identified: 21, 22, 23, 80, 3306
- Services: FTP, SSH, Telnet, HTTP, MySQL

---

## Task 3: Web Server Discovery
- Accessed web server successfully
- Found applications:
  - phpMyAdmin
  - DVWA
  - Mutillidae

---

## Task 4: Service Version Detection
- FTP: vsftpd 2.3.4
- SSH: OpenSSH 4.7p1
- HTTP: Apache 2.2.8

---

## Task 5: Vulnerability Scan (OWASP ZAP)
- Found vulnerabilities:
  - SQL Injection
  - XSS
- High-risk alerts identified

---

## Task 6: OS Detection
- OS: Linux
- Kernel: 2.6.x

---

## Task 7: FTP Analysis
- Anonymous login enabled
- Security risk identified

---

## Task 8: HTTP Analysis
- Server: Apache
- PHP version: 5.2.4

---

## Task 9: Directory Discovery
- Found directories:
  - /phpinfo.php
  - /icons/
  - /doc/
- 403 Forbidden observed on /admin

---

## Task 10: Summary

### Services Identified
| Service | Port | Status |
|--------|------|--------|
| FTP | 21 | Open |
| SSH | 22 | Open |
| HTTP | 80 | Open |

### Security Issues
1. Anonymous FTP access
2. Outdated software
3. Telnet enabled

---

## Conclusion
The system contains multiple vulnerabilities and misconfigurations, making it intentionally insecure for learning purposes.
