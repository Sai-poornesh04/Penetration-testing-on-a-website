# Penetration-testing-on-a-website

# ENGAGEMENT OVERVIEW
HackersForYou was engaged by Ma****thi.com to conduct a penetration test of
their web application hosted within their production environment.
This type of engagement aims to identify security risks, highlight potential risks,
and provide remediation guidance to support an improved security posture.

# ENGAGEMENT SCOPE
Based on the agreed objectives, the scope included the
https://conference.*********.org/ domain.
Testing was conducted using Kali Linux and Burp Suite.

 # CAVEATS
There were no applicable caveats for this engagement.

Overall, the security posture observed during the test window requires
improvement immediately. During testing it was not possible to:
• Cannot find credentials for the login page.
• Manipulate business logic issues to carry out undesired behaviours within
the domain.
However, a number of issues were discovered during the testing window.
Overall, the consultant discovered one critical risk and one low risk
vulnerabilities.
The critical-risk vulnerabilities that were detected were gaining access to admin
reports and the version and creator of the database. Gaining access to the admin
report is critical because it disclosed all of the participants personal information
registered on the platform. This is a critical vulnerability, as it can lead to privacy
violation, identity theft, financial loss, sensitive data exposure and trust and
reputation damage. Implement multi-factor authentication (MFA) to strengthen
login security and prevent unauthorized access to admin accounts.
The high-risk vulnerability that was detected was Local Privilege Escalation via
Outdated SMTP Service. Privilege escalation is when a user or program gains
higher access rights on a system or application than intended. Limit user
permissions to only what is necessary for their tasks, reducing the potential
impact of privilege escalation.
The medium-risk vulnerabilities that were detected are unnecessary open ports
and vulnerable MySQL dependency. Non web-based ports are open which can
cause a significant increase in the attack surface. A vulnerable MySQL
dependency is a weakness in MySQL that attackers can exploit to compromise system security. Follow best practices for securing MySQL, including strong
password policies, encryption, and disabling unnecessary features.
The low-risk vulnerability that was detected is exposed login page. This
increases the attack surface of Manashakti. Implement measures to prevent
brute force attacks, such as account lockout after multiple failed login attempts
or CAPTCHA verification
