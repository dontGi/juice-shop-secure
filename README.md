
Project: OWASP Juice Shop Security Audit

Objective
The objective of this task was to conduct a security audit using OWASP Juice Shop, identify vulnerabilities, attempt fixes, and ensure secure deployment. The project simulates a real-world ethical hacking environment to understand and apply secure coding and auditing practices.

🛠️ Tools Used
OWASP Juice Shop – Vulnerable web application for ethical hacking practice

OWASP ZAP – Automated vulnerability scanner

Burp Suite – Manual testing and request interception

npm audit – For checking and fixing vulnerable dependencies

 Vulnerability Audit Summary
Performed automated security audit using OWASP ZAP.

Identified issues such as:

Missing security headers

Cookie attributes misconfigured

Potentially sensitive information exposure

Ethical hacking report is attached in the deliverables.

 Security Fix Summary
Ran npm audit and npm audit fix.

Some vulnerabilities were resolved; others remained due to package version conflicts.

No major code changes were made, but audit and awareness of vulnerable packages were documented.

Secure Deployment Steps
Cloned OWASP Juice Shop locally.

Hosted and accessed it via localhost.

Used ZAP and Burp to test login, password reset, and other critical endpoints.

Followed basic secure deployment practices such as awareness of headers, HTTPS enforcement (where possible), and proper tooling.

 Deliverables
Ethical hacking report: audit-report.docx

Security fix summary: Documented in report and README

Repository: Contains Juice Shop folder with no major code changes

