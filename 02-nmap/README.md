# 02 - Nmap

**Original**: https://x3m1sec.gitbook.io/notes/my-certifications/cpts/notes/nmap

## Goals
- Discover live hosts
- Identify open ports and services
- Detect versions and potential vulnerabilities

## Practical Checklist
- [ ] Host discovery (ping sweep / ARP if local)
- [ ] Full TCP port scan on interesting hosts
- [ ] Service version detection (`-sV`)
- [ ] Default scripts (`-sC`)
- [ ] OS detection when useful (`-O`)
- [ ] UDP scan on critical services (DNS, SNMP, etc.)
- [ ] Save output in multiple formats (`-oA`)
- [ ] Review for unusual ports / services

## Common Command Patterns
```bash
nmap -sn <target>
nmap -sS -sV -sC -p- -T4 -oA full_tcp <target>
nmap -sU --top-ports 100 <target>
```

Link back to original notes for full flag explanations and protocol-specific scans.
