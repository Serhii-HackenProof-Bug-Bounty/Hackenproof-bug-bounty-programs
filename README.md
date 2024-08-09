# Hackenproof
bug bounty program

https://hackenproof.com/programs/hackenproof

HackenProof is a Bug Bounty and Vulnerability Coordination Platform. We connect our customers with the global hacker community to uncover security issues in their products. By running custom-tailored bug bounty programs we help our customers significantly reduce the risk of losing their data to cybercriminals.

Target - https://hackenproof.com

In-Scope Vulnerabilities

We are interested in next web vulnerabilities:

Business Logic

Remote code execution (RCE)

Database vulnerability, SQLi

Cross Site Scripting (XSS)

Privilege escalation

Sensitive data exposure (IDOR, etc.)

Authentication bypass

Obtaining sensitive information

Password attacks

Cross-Site Request Forgery (CSRF)

Server Side Request Forgery (SSRF)


Out-of-Scope Vulnerabilities

In general, the following vulnerabilities do not correspond to the severity threshold:
Known problems: 2FA session issues

UI and UX bugs and spelling or localization mistakes.

Descriptive error messages (e.g. Stack Traces, application or server errors)

Open redirects. 99% of open redirects have low security impact. For the rare cases where the impact is higher, e.g., stealing auth tokens, we do still want to hear about them

Vulnerabilities in third-party applications

Publicly accessible login panels without proof of exploitation.

Reports that state that software is out of date/vulnerable without a proof of concept.

Host header issues without proof-of-concept demonstrating the vulnerability.

HTTP codes/pages or other HTTP non-codes/pages.

Fingerprinting/banner disclosure on common/public services.

Disclosure of known public files or directories, (e.g. robots.txt).

Clickjacking/Tapjacking and issues only exploitable through clickjacking/tapjacking.

CSRF in forms that are available to anonymous users (e.g. the contact form).

Login & Logout CSRF

Presence of application or web browser ‘autocomplete’ or ‘save password’ functionality.

Lack of Secure/HTTPOnly flags on non-security-sensitive Cookies.

OPTIONS HTTP method enabled

Lack of Security Speed bump when leaving the site.

Weak Captcha

Broken links (including social media)

Content injection issues.

HTTPS Mixed Content Scripts

Content Spoofing without embedded links/html
