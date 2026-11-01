# Challenges I've Overcome

Most of what I've learned came from things that didn't work the first time. These are the problems that took the longest to solve.

### 1. A vulnerability scanner that wouldn't scan
Getting GVM/OpenVAS working meant fixing five faults in a row: a PostgreSQL collation mismatch, stale feed locks, a missing import-owner setting, a corrupted SCAP database and, finally, a Windows Firewall silently dropping every probe.
**Lesson:** an empty result isn't a clean result. Verify the tool can see the target. → [Lab 03](labs/03-vulnerability-management-gvm.md)

### 2. Following tutorials for the wrong version
Snort 3 replaced Snort 2's config format with Lua and changed its command-line flags, so most guides simply didn't apply.
**Lesson:** check your version first, then read that version's documentation. → [Lab 04](labs/04-network-analysis-ids.md)

### 3. Locked out by my own security controls
Dual-booting Kali meant clearing the Secure Boot Platform Key, which then triggered BitLocker recovery on Windows.
**Lesson:** security controls doing their job can look like a breakdown. Have recovery keys ready before changing firmware. → [Lab 06](labs/06-dual-boot-kali.md)

### 4. Routing an attack through a firewall
Building a three-network lab with Sophos between attacker and target meant getting interfaces, routes and rules right before any exploit could land.
**Lesson:** most "the exploit doesn't work" problems are really network problems. → [Lab 01](labs/01-firewall-exploitation-lab.md)

### 5. Testing a real network responsibly
My placement pentest was on a live business network. The challenge was being thorough without disrupting anything, and writing findings management could act on.
**Lesson:** authorisation, care and a clear report matter as much as the technical work. → [WIL write-up](workplace/wil-placement.md)

### 6. Leading a team that shrank
When members dropped out of a group assessment, I took over two core sections and still delivered the full 20-slide presentation.
**Lesson:** own the outcome, not just your part. → [Project 07](projects/phishing-incident-response.md)

### 7. Keeping a lab alive
Running several Kali VMs in VirtualBox brought GUI failures (missing keyboard data), full disks and networking-mode mix-ups.
**Lesson:** a working lab is infrastructure. Maintain it like one.
