# Information-security-gruyere

## Observation and Analysis of Security Weaknesses in a Vulnerable System

---

## Project Description

This project is developed to identify, analyze, and document common web application vulnerabilities using a deliberately vulnerable web application (Google Gruyere) and ethical security testing techniques.

The project demonstrates practical understanding of web security concepts, vulnerability assessment, and mitigation strategies based on industry standards such as the OWASP Top Ten.

---

## Objectives

- Identify common web application security vulnerabilities
- Perform manual and automated vulnerability testing
- Analyze security weaknesses in a controlled environment
- Propose effective mitigation strategies
- Apply ethical hacking concepts in a safe test environment

---

## Target Application

Google Gruyere  
A deliberately vulnerable web application designed for learning web security concepts.

---

## Tools Used

- OWASP ZAP (Zed Attack Proxy)
- Google Gruyere Web Application
- Manual Security Testing Techniques
- Browser-based inspection tools

---

## Identified Vulnerabilities

- Cross-Site Scripting (XSS) – Reflected
- Cross-Site Scripting (XSS) – Stored
- Broken Authentication
- Sensitive Data Exposure
- Input Validation Issues
- Security Misconfiguration
- Unrestricted File Upload
- Information Disclosure via Error Messages

---

## Methodology

- Application Exploration – Studied functionality of Google Gruyere
- Automated Scanning – Used OWASP ZAP for vulnerability detection
- Manual Testing – Tested inputs, authentication, and file upload features
- Analysis – Evaluated risks and impact
- Documentation – Recorded findings and mitigation strategies

---

## Mitigation Summary

- Input validation and output encoding
- Strong authentication mechanisms (MFA, password policies)
- Secure communication using HTTPS/TLS
- Proper session management
- Secure file upload handling
- Regular security audits
- Least privilege access control

---

## Key Learnings

- Input validation is critical to prevent injection attacks
- Authentication systems must be properly secured
- Sensitive data must never be exposed in URLs or error messages
- Automated tools must be combined with manual testing
- Security must be integrated into the development lifecycle

---

## Author

Mubashra Noor  

---

## References

- OWASP Top Ten: https://owasp.org/www-project-top-ten/
- Google Gruyere: https://google-gruyere.appspot.com/

---

## License

This project is for educational purposes only.