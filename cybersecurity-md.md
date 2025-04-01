# Cybersecurity Resources

A curated collection of cybersecurity resources, standards, frameworks, and tools to support secure software development and security practices.

## Standards & Frameworks

### NIST Publications

- [NIST SP 800-53 Rev 5](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf) - Security and Privacy Controls for Information Systems and Organizations
  - **Key Sections**: 
    - Section 3.1: Control Baselines
    - Appendix F: Security Control Catalog
    - Appendix J: Privacy Control Catalog
  - **Use Case**: Reference for implementing security controls in federal information systems, but widely applicable to any organization
  - **Last Major Update**: September 2020

- [NIST SP 800-171 Rev 2](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-171r2.pdf) - Protecting Controlled Unclassified Information in Non-Federal Systems
  - **Key Focus**: Requirements for protecting the confidentiality of CUI when processed, stored, or transmitted by non-federal systems
  - **Relevance**: Essential for contractors working with the US government

- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework) - Framework for improving critical infrastructure cybersecurity
  - **Core Functions**: Identify, Protect, Detect, Respond, Recover
  - **Implementation Tiers**: Partial, Risk Informed, Repeatable, Adaptive
  - **Profiles**: Current vs. Target posture

### OWASP Resources

- [OWASP Top 10 (2021)](https://owasp.org/www-project-top-ten/) - The standard awareness document for developers and web application security
  - **A01:2021**: Broken Access Control
  - **A02:2021**: Cryptographic Failures
  - **A03:2021**: Injection
  - **A04:2021**: Insecure Design
  - **A05:2021**: Security Misconfiguration
  - **A06:2021**: Vulnerable and Outdated Components
  - **A07:2021**: Identification and Authentication Failures
  - **A08:2021**: Software and Data Integrity Failures
  - **A09:2021**: Security Logging and Monitoring Failures
  - **A10:2021**: Server-Side Request Forgery (SSRF)

- [OWASP API Security Top 10](https://owasp.org/API-Security/editions/2023/en/0x00-header/) - Focused on API security concerns
  - **API1:2023**: Broken Object Level Authorization
  - **API2:2023**: Broken Authentication
  - **API3:2023**: Broken Object Property Level Authorization
  - **API4:2023**: Unrestricted Resource Consumption
  - **API5:2023**: Broken Function Level Authorization

- [OWASP ASVS (Application Security Verification Standard)](https://owasp.org/www-project-application-security-verification-standard/) - Detailed security requirements and controls

### Other Key Frameworks

- [MITRE ATT&CK Framework](https://attack.mitre.org/) - Knowledge base of adversary tactics and techniques
  - **Enterprise Matrix**: Techniques used against enterprise networks
  - **Mobile Matrix**: Techniques targeting mobile devices
  - **ICS Matrix**: Techniques against industrial control systems

- [SANS 25 Most Dangerous Software Weaknesses](https://www.sans.org/top25-software-errors/) - Common vulnerabilities to be aware of
  - Based on CWE (Common Weakness Enumeration) data
  - Prioritized by severity, exploitability, and prevalence

## Secure Coding Guidelines

### Language-Specific Guidelines

- [SEI CERT C Coding Standard](https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard)
- [SEI CERT C++ Coding Standard](https://wiki.sei.cmu.edu/confluence/display/cplusplus/SEI+CERT+C%2B%2B+Coding+Standard)
- [SEI CERT Oracle Coding Standard for Java](https://wiki.sei.cmu.edu/confluence/display/java/SEI+CERT+Oracle+Coding+Standard+for+Java)
- [Python Security Best Practices](https://snyk.io/blog/python-security-best-practices-cheat-sheet/)
- [JavaScript Security Best Practices](https://cheatsheetseries.owasp.org/cheatsheets/Nodejs_Security_Cheat_Sheet.html)

### Web Application Security

- [Content Security Policy (CSP)](https://content-security-policy.com/) - Mitigating XSS and data injection attacks
- [OWASP Secure Headers Project](https://owasp.org/www-project-secure-headers/) - HTTP response headers for security
- [Web Security Academy](https://portswigger.net/web-security) - Free learning materials by PortSwigger

## Security Testing Tools

### Static Analysis

- [SonarQube](https://www.sonarqube.org/) - Continuous code quality and security review
- [ESLint Security Plugin](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node.js security
- [Bandit](https://github.com/PyCQA/bandit) - Security-focused static analyzer for Python code
- [PMD](https://pmd.github.io/) - Source code analyzer for Java

### Dynamic Analysis

- [OWASP ZAP](https://www.zaproxy.org/) - Integrated penetration testing tool
- [Burp Suite](https://portswigger.net/burp) - Web vulnerability scanner and proxy
- [Metasploit](https://www.metasploit.com/) - Penetration testing framework

### Dependency Scanning

- [OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/) - Identifies project dependencies with known vulnerabilities
- [Snyk](https://snyk.io/) - Find and fix vulnerabilities in dependencies
- [npm audit](https://docs.npmjs.com/cli/v8/commands/npm-audit) - Built-in security auditing in npm

## Books & Learning Resources

- [The Web Application Hacker's Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470) - Comprehensive guide to finding and exploiting security flaws
- [Practical Cryptography for Developers](https://cryptobook.nakov.com/) - Free book on cryptography concepts and implementations
- [TryHackMe](https://tryhackme.com/) - Hands-on cybersecurity training
- [HackTheBox](https://www.hackthebox.com/) - Cybersecurity training platform

## Security Certifications

- [Certified Information Systems Security Professional (CISSP)](https://www.isc2.org/Certifications/CISSP)
- [Certified Ethical Hacker (CEH)](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)
- [Offensive Security Certified Professional (OSCP)](https://www.offensive-security.com/pwk-oscp/)
- [CompTIA Security+](https://www.comptia.org/certifications/security)

## Personal Notes

*Add your personal notes, observations, and insights here. For example:*

- Key findings from NIST SP 800-53 Rev 5 that apply to my current projects
- Common vulnerabilities I've encountered in code reviews
- Effective security patterns I've implemented

---

*Last updated: [Date]*