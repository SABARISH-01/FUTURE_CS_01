# FUTURE_CS_01 – Web Application Security Testing

## 👨‍💻 Intern Details
- **Name**: Sabarish V 
- **Internship Program**: Cyber Security Track @ Future Interns  
- **Task**: Web Application Penetration Testing  
- **Date**: 3 June 2025

## 🔎 Objective
This task focuses on identifying vulnerabilities in a web application using ethical hacking techniques. The testbed used is **OWASP Juice Shop**, which is purposely vulnerable for educational testing.

## 🛠 Tools Used
- Browser Developer Tools
- OWASP Juice Shop (Online Demo)
- Manual Payload Injection Techniques

## 🧪 Vulnerabilities Identified

### 1. SQL Injection
- **Payload Used**: `' OR '1'='1`
- **Result**: Gained unauthorized access
- **Mitigation**: Implement parameterized queries

### 2. Cross-Site Scripting (XSS)
- **Payload Used**: `<img src=x onerror=alert('XSS')>`
- **Result**: Alert box executed successfully
- **Mitigation**: Sanitize input and encode output

### 3. Authentication & Access Control
- **Test**: URL tampering and credential testing
- **Result**: No successful bypass
- **Recommendation**: Use strong session and access control mechanisms

## 📄 Deliverables
- [✔️] Final Report (attached in PDF)
- [✔️] Screenshots (included in repository)
- [✔️] README documentation

## 🔗 References
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)
- [OWASP SQL Injection Guide](https://owasp.org/www-community/attacks/SQL_Injection)
- [OWASP XSS Guide](https://owasp.org/www-community/attacks/xss/)
