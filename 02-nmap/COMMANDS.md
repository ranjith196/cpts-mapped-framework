# Nmap – Phase Specific Commands

## Host Discovery
```bash
nmap -sn 10.10.10.0/24
nmap -sn -PS22,80,443 <target>
```

## Full TCP Scan (common for CPTS)
```bash
nmap -sS -sV -sC -p- -T4 --min-rate 1000 -oA full_tcp <target>
```

## Top Ports + Scripts
```bash
nmap -sV -sC --top-ports 1000 -T4 -oA top1000 <target>
```

## UDP (selective)
```bash
nmap -sU --top-ports 50 -T4 <target>
```

## Specific Service Deep Dive
```bash
nmap -sV -p 445 --script smb-enum* <target>
nmap -sV -p 80,443 --script http-enum,http-title <target>
```

Always save output (`-oA`) and review carefully.
