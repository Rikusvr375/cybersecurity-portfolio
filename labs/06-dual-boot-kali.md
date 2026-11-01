# 06 · Dual-Boot Kali Workstation

**Goal:** Run Kali Linux natively alongside Windows on an ASUS VivoBook, for full hardware performance outside a VM.

## Problems I solved

| Problem | Fix |
|---|---|
| UEFI **Secure Boot** refused to boot the Kali installer | Cleared the Platform Key to put Secure Boot into setup mode, allowing the install |
| Windows demanded a **BitLocker recovery key** after the firmware changes | Recovered with the key, then understood why: BitLocker treats changed boot settings as possible tampering |
| Fresh install had no tooling | Installed `kali-tools-top10` and set up Microsoft 365 as web apps through Edge |

## What I learned

- BitLocker and Secure Boot are working as designed when they react to firmware changes. Always have the recovery key before touching BIOS settings.
- Plan partitions and back up before dual-booting; boot problems are easy to cause and slow to undo.

**Tools:** Kali Linux · UEFI / Secure Boot · BitLocker · Windows
