# Web Attacks Expanded Checklist

## General
- [ ] Map all input points (GET, POST, headers, cookies, JSON, XML, file uploads)
- [ ] Identify technologies and frameworks
- [ ] Check for WAF / rate limiting early
- [ ] Test both authenticated and unauthenticated contexts

## Broken Access Control / IDOR
- [ ] Horizontal testing with multiple same-role accounts
- [ ] Vertical testing (low privilege → higher)
- [ ] Object ID manipulation in all locations
- [ ] Method tampering (GET↔POST, etc.)
- [ ] Parameter pollution

## Injection
- [ ] SQL Injection (error, boolean, time, UNION, stacked)
- [ ] Command Injection
- [ ] SSTI / Template Injection
- [ ] XSS (reflected, stored, DOM) + context-aware payloads
- [ ] LDAP / XPath / NoSQL if relevant

## File Related
- [ ] File Inclusion (LFI/RFI)
- [ ] File Upload (type, content, path, race, etc.)

## Authentication & Session
- [ ] Broken authentication flows
- [ ] Session fixation / prediction
- [ ] Password reset issues
- [ ] MFA bypass ideas

## Other
- [ ] SSRF
- [ ] Open Redirect
- [ ] CSRF (where impactful)
- [ ] Business logic flaws
- [ ] API specific issues (BOLA, mass assignment, etc.)

Use the prompts in `/prompts` to generate deeper trees for any of these.
