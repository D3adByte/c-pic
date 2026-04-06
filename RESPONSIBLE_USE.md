# Responsible Use Policy

This repository contains security research code demonstrating position-independent code (PIC) compilation techniques, including PEB walking, PE export resolution, and raw syscall invocation.

## Intended Use

This project is intended strictly for:
- Security research and education in low-level systems programming
- Understanding binary formats, loaders, and calling conventions
- Malware analysis and reverse engineering training
- Red team tool development under authorized engagements
- Defensive tool testing and detection engineering

## Authorization Requirement

You may only use this software:
- On systems you own, or
- On systems where you have explicit written authorization from the owner

## Prohibited Use

You may NOT use this software:
- For unauthorized access to any system or network
- To bypass security controls in production environments
- To deploy, distribute, or execute malicious payloads against real-world targets
- To evade antivirus, EDR, or other detection mechanisms outside of authorized testing
- For any illegal, unethical, or malicious activity

## Detection & Risk Notice

This project produces position-independent code blobs that may:
- Trigger antivirus or EDR alerts
- Be flagged as shellcode or malicious behavior by security tools
- Cause system instability if misused

Use only in isolated lab environments (VMs, sandboxes, air-gapped systems).

## No Warranty / Liability

This software is provided "AS IS", without warranty of any kind, express or implied.

The authors are not responsible for:
- Damage to systems or data loss
- Legal consequences resulting from misuse
- Any harm caused by unauthorized or unethical use

## Responsible Disclosure

If this research leads to the discovery of vulnerabilities in operating systems, compilers, or security products:
- Follow responsible disclosure practices
- Notify affected vendors before any public release
- Allow reasonable time for patches to be developed and deployed
