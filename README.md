# CPTS Mapped Framework

**Source**: [x3m1sec CPTS Notes](https://x3m1sec.gitbook.io/notes/my-certifications/cpts/notes)

Practical, phase-based mapping of Hack The Box CPTS topics into a usable penetration testing framework. Designed for learning, exam prep, and authorized engagements.

---

## Framework Phases

| Phase | Focus | Key Topics from GitBook |
|-------|-------|-------------------------|
| 01 | Enumeration & Info Gathering | Enumeration, Initial Enum, Checklist |
| 02 | Network Scanning | Nmap (full flags, protocol scans, network scanning) |
| 03 | Common Services & Applications | Attacking Common Services, CMS (WP/Joomla/Drupal), Tomcat, Jenkins, Splunk, GitLab, etc. |
| 04 | Web Attacks | SQLi, XSS, Command Injection, File Inclusion, File Upload, Broken Auth, Web Attacks, API |
| 05 | Active Directory | AD Enumeration & Attacks |
| 06 | Privilege Escalation | Linux Privesc, Windows Privesc |
| 07 | Post-Exploitation & Movement | Shells & Payloads, File Transfer, Ligolo-ng, Pivoting/Tunneling/Port Forwarding, TTY upgrade |
| 08 | Password Attacks | Password Attacks, Password Cracking |
| 09 | Supporting | Session Security, Metasploit, Server-side Attacks, Tips, CheatSheet |

---

## Repository Structure

```
cpts-mapped-framework/
├── README.md
├── 01-enumeration/
├── 02-nmap/
├── 03-common-apps-services/
├── 04-web-attacks/
├── 05-active-directory/
├── 06-privilege-escalation/
├── 07-shells-pivoting/
├── 08-password-attacks/
├── 09-supporting/
├── TOOLS.md
└── METHODOLOGY.md
```

---

## How to Use

1. Follow phases in order for CPTS-style engagements.
2. Use original GitBook pages for detailed commands and explanations.
3. Integrate with your personal bug bounty prompts, IDOR checklists, and WAF testing notes.
4. Keep notes of what works on each target.

---

## Credits & Disclaimer

- Original notes: **x3m1sec**
- This mapping and structure: for educational and authorized use only.
- Always stay within scope and legal boundaries.

Repo: https://github.com/ranjith196/cpts-mapped-framework
