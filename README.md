# SQL-injection-
# SQL Injection Lab (DVWA)

## Objective
Reproduce and document a SQL Injection attack in DVWA, showing how unsanitized input can expose sensitive data.

## Lab Environment
- **Attacker:** Kali Linux
- **Target:** DVWA running on local VM (IP: 192.168.56.101)
- **DVWA Security Level:** Low
- **Authorization:** Lab-only, ethical testing environment

## Tools Used
- Kali Linux terminal
- Web browser (Firefox)
- DVWA (Damn Vulnerable Web Application)

## Key Commands / Payloads

### Step 1: Confirm target is reachable
```bash
64 bytes from 192.168.56.101: icmp_seq=1 ttl=64 time=0.045 ms

ping 192.168.56.101
