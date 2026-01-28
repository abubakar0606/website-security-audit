**Website Security Audit**

**Project Overview**
This project focuses on performing a security audit of a web application to
identify common vulnerabilities and assess its overall security posture.
The purpose of this task is to understand how web applications are tested
for security issues and how risks can be reduced through proper analysis
and recommendations.

This work was completed as **Task 6** of the **Cybersecurity Internship at Internee.pk**.

 Objective
The main objectives of this task are:
- To test critical areas of a website such as login pages and user input forms  
- To detect common web vulnerabilities including SQL Injection, XSS, and CSRF  
- To use security tools for automated and manual testing  
- To analyze the risk level of discovered vulnerabilities  
- To provide security recommendations for improvement  



 **Test Environment**
For safe and legal practice, testing was performed on a controlled and
deliberately vulnerable web application instead of a real production site.

The test environment used:
- OWASP Juice Shop (vulnerable practice application)  
- Local browser-based testing  
- Security tools for scanning and analysis  

This ensured that all activities were ethical and focused on learning.



**Tools Used**
- OWASP ZAP (Automated vulnerability scanning)  
- Burp Suite Community Edition (Manual request inspection)  
- Web Browser (Manual interaction with the application)   

These tools are widely used in professional web security testing.



 **Testing Approach**

### Automated Scanning
Automated scans were performed using OWASP ZAP to crawl the application
and detect potential security issues such as missing headers, insecure
inputs, and common vulnerabilities.



**Manual Testing**
Manual testing was conducted on selected features such as login forms
and input fields to check for SQL Injection and XSS vulnerabilities.



**Vulnerabilities Identified**
The following types of vulnerabilities were identified during the audit:
- SQL Injection  
- Cross-Site Scripting (XSS)  
- Cross-Site Request Forgery (CSRF)  
- Security misconfigurations  

Each vulnerability was analyzed based on its potential impact and risk level.



 **Risk Analysis**
- **High Risk:** Vulnerabilities that could lead to data compromise  
- **Medium Risk:** Vulnerabilities that could affect user sessions or data integrity  
- **Low Risk:** Issues related to configuration or security headers  

Risk analysis helped prioritize which issues should be fixed first.



 **Recommendations**
To improve the security of the application, the following actions are recommended:
- Implement proper input validation and sanitization  
- Use prepared statements for database queries  
- Add CSRF protection tokens to forms  
- Configure appropriate security headers  
- Enforce HTTPS for secure data transmission  
- Regularly update and patch the application  

 **Conclusion**
This task demonstrates how a basic website security audit can be performed
using both automated and manual testing methods. By identifying common
vulnerabilities and providing recommendations, this project highlights the
importance of proactive security assessments in protecting web applications.

Overall, this task helped strengthen practical knowledge of web security
testing and vulnerability management.

 **Internship**
     **This project is part of the Cybersecurity Internship Program at Internee.pk**
