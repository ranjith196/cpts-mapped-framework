# CPTS Engagement Methodology (Mapped)

This follows the practical flow used in CPTS-style exams and real authorized pentests, aligned with the x3m1sec notes structure.

## High-Level Flow

1. **Scope & Rules of Engagement**
2. **Enumeration / Information Gathering**
3. **Service & Application Mapping** (Nmap + Common Services/Apps)
4. **Initial Access** (Web attacks, service exploits, password attacks)
5. **Privilege Escalation** (Linux / Windows)
6. **Lateral Movement & Pivoting** (AD, Ligolo-ng, tunneling)
7. **Post-Exploitation & Persistence** (as in scope)
8. **Documentation & Reporting**

## Recommended Working Style (from real hunters + CPTS practice)

- Work in short focused blocks.
- When stuck, return to enumeration.
- Document every interesting finding immediately.
- Prefer understanding the application/service before heavy exploitation.
- Chain low findings where possible.

## Integration with Bug Bounty Style

You can overlay the detailed prompts we built earlier (IDOR, XSS + WAF, Access Control trees, etc.) on top of Phase 4 (Web Attacks) for deeper coverage.

---

**Source mapping**: Directly derived from the structure of https://x3m1sec.gitbook.io/notes/my-certifications/cpts/notes
