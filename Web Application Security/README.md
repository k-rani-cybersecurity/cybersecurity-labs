# Web Application Security Basics

## Objective

Identify common web application vulnerabilities in a controlled environment using DVWA and Burp Suite.

## Vulnerabilities Tested

- Reflected Cross-Site Scripting (XSS)
- SQL Injection (SQLi)

## Tools Used

- Kali Linux
- DVWA
- Docker
- Burp Suite Community Edition
- Mozilla Firefox

## Methodology

1. Deploy DVWA using Docker.
2. Configure DVWA security level to Low.
3. Configure Burp Suite as an intercepting proxy.
4. Test Reflected XSS.
5. Test SQL Injection.
6. Document findings and mitigations.

## Findings

### Reflected XSS

- Successfully executed JavaScript payload in the browser.
- Impact: Client-side script execution.

### SQL Injection

- Successfully manipulated database queries.
- Impact: Unauthorized access to data.

## Mitigation Recommendations

- Validate and sanitize user input.
- Encode output before rendering.
- Use parameterized queries.
- Implement Content Security Policy (CSP).
- Apply least-privilege principles.

## Disclaimer

All testing was conducted in a controlled laboratory environment using DVWA for educational purposes only.
