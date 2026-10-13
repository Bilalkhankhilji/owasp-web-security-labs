# 🛡️ OWASP Web Security & Vulnerability Remediation Labs

Practical code examples demonstrating common web application vulnerabilities (OWASP Top 10) and secure coding remediation patterns.

**Author:** Muhammad Bilal — Assistant Network Administrator  
**Focus:** Secure Software Development Life Cycle (SSDLC) & Code-Level Defense  

---

## 📁 Repository Structure

```text
owasp-web-security-labs/
├── sqli/
│   └── secure_login.php      # SQL Injection remediation via PDO prepared statements
├── xss/
│   └── ReflectedXSS_fix.php    # Cross-Site Scripting (XSS) mitigation via output encoding
└── README.md

# Clone the repository
git clone [https://github.com/Bilalkhankhilji/owasp-web-security-labs.git](https://github.com/Bilalkhankhilji/owasp-web-security-labs.git)
cd owasp-web-security-labs

# Start a local PHP server
php -S localhost:8000