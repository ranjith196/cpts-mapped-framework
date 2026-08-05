# 06 - Privilege Escalation

**Original pages**:
- Linux Privilege Escalation
- Windows Privilege Escalation

## Linux Checklist
- [ ] Kernel exploits (carefully)
- [ ] SUID / SGID binaries (GTFOBins)
- [ ] Capabilities
- [ ] Cron jobs / timers
- [ ] Writable scripts or configs
- [ ] PATH hijacking
- [ ] Docker / LXD escape if present
- [ ] Password / key hunting in files

## Windows Checklist
- [ ] Whoami / privileges
- [ ] Service misconfigurations
- [ ] Unquoted service paths
- [ ] AlwaysInstallElevated
- [ ] Token impersonation
- [ ] Registry autoruns
- [ ] Scheduled tasks
- [ ] Potato family / other techniques

Always validate impact and stay within scope.
