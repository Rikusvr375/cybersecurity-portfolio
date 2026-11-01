# Work Integrated Learning · Everest Wealth Management

**Role:** Cybersecurity Intern (WIL), placed through Gknect · Pretoria · 2026 – present
**Programme:** CTU Training Solutions, Occupational Certificate: Cybersecurity Analyst (NQF 5)

> All work was authorised by the organisation. To protect the client, this write-up describes methodology and outcomes only. No addresses, hostnames or system details are disclosed.

## Internal penetration test

| Phase | What I did |
|---|---|
| Scoping | Agreed the authorised internal range and rules of engagement |
| Discovery | Host discovery and port/service scanning with **Nmap** across the internal network |
| Enumeration | Service and version identification on every live host |
| Validation | Confirmed selected findings safely, using **Metasploit** in a controlled test environment |
| Reporting | Formal Word report with risk ratings and remediation recommendations |

**Outcome:** Mapped the live estate and identified critical exposures, including database services reachable from the internal network and a device with an exposed debug interface, each with a recommended fix.

## Security server build

Set up a mini PC as a dedicated Kali Linux security server:

- Static addressing configured with `nmtui`
- Remote administration over **SSH** (PuTTY)
- **tmux** for persistent sessions that survive disconnects during long scans
- **Docker** containers hosting deliberately vulnerable web apps for safe, isolated testing

## Ongoing work

- OSINT investigations and network reconnaissance
- Vulnerability scanning and security reporting
- Daily logbook of tasks completed, skills applied and challenges faced
