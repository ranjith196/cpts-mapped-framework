# Tools Mapping (from x3m1sec CPTS Notes + Common Practice)

## Core Tools by Category

### Enumeration & Scanning
- Nmap (primary)
- Common accompanying: masscan, rustscan, naabu (modern alternatives)

### Web Enumeration & Attacks
- Burp Suite / Caido (proxy)
- ffuf, gobuster, dirsearch (content discovery)
- sqlmap (SQLi)
- Common for XSS / injection testing: manual + browser tools

### Active Directory
- BloodHound / SharpHound
- Impacket suite
- CrackMapExec / NetExec
- Rubeus, Mimikatz (where applicable in lab)

### Privilege Escalation
- Linux: linpeas, linenum, GTFOBins references
- Windows: winpeas, PowerUp, Seatbelt, LOLBAS

### Shells, Transfer & Pivoting
- Metasploit Framework
- Ligolo-ng (explicitly in notes)
- chisel, ssh tunneling, socat, etc.
- Common reverse shell generators (msfvenom, revshells.com style)

### Password Attacks
- hashcat, john
- hydra, medusa, crowbar
- Password lists (rockyou, SecLists)

### Others Mentioned / Related
- Tools for CMS: wpscan, joomscan, droopescan
- Jenkins, Tomcat, Splunk, GitLab specific enumeration tools

> Note: Always verify current best tools. The GitBook focuses heavily on practical commands for the above categories.
