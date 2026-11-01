# 04 · Network Analysis & Intrusion Detection

**Goal:** Read network traffic confidently and configure an IDS to alert on it.

## Packet analysis

- Captured traffic with **tcpdump** and analysed it in **Wireshark**.
- Compared **HTTP vs HTTPS**: credentials and content are readable in plain HTTP captures, while HTTPS shows only the handshake and encrypted application data.
- Practised protocol analysis (TCP handshakes, DNS, ARP) and interpreting Nmap scan traffic as evidence.

## Snort 3 IDS

- Configured **Snort 3** on Kali from scratch.
- Snort 3 differs from the Snort 2 material most guides use: configuration lives in **Lua** (`snort.lua`), and the command-line flags change (for example `-A alert_fast` for readable alerts).
- Wrote and tested rules, then generated traffic to confirm alerts fired.

## What I learned

- Encryption protects content, not metadata: who talked to whom and when is still visible.
- Always check which version of a tool you have before following a tutorial.
- An IDS rule isn't done until you've proven it fires on the traffic it's meant to catch.

**Tools:** Wireshark · tcpdump · Snort 3 · Nmap · Kali Linux
