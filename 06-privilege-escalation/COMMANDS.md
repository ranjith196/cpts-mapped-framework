# Privilege Escalation – Command Examples

## Linux Quick Wins
```bash
# Basic info
id; whoami; sudo -l; uname -a

# SUID
find / -perm -4000 2>/dev/null

# Capabilities
getcap -r / 2>/dev/null

# Cron
ls -la /etc/cron*; cat /etc/crontab

# Writable files
find / -writable -type f 2>/dev/null | grep -v proc
```

## Windows Quick Wins
```powershell
whoami /all
systeminfo
net user
net localgroup administrators

# Services
sc query state= all
Get-Service

# Unquoted paths / weak perms (use tools like PowerUp, winPEAS)
```

Always run automated helpers (linpeas / winpeas) after manual checks, then validate interesting findings manually.
